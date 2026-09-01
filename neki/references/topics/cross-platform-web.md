# Cross-Platform & Web

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Cross-platform, Android, Flutter, web, and interoperability work adjacent to Apple-platform development.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **670**

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

- [Protecting SwiftUI Views with Authentication](https://azamsharp.com/2026/08/22/protecting-swiftui-views-with-authentication.html) — iOS Dev Weekly · Issue 765 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `28th August 2026`
  **NeKI brief:** Shows how to protect SwiftUI views behind an authentication boundary. The topic connects view composition with session state, making it useful for deciding where authenticated routing and access checks belong in a SwiftUI application.
- [More Incredible Tales of App Store Curation](https://lapcatsoftware.com/articles/2026/8/9.html) — Those Who Swift · Issue 281 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Examines Apple App Store curation through concrete examples of review and editorial treatment. It provides product and distribution context for developers whose release strategy depends on App Store visibility, rather than describing an implementation technique.
- [The Curious Case of the Missing SwiftUI Clicks](https://damian.fyi/swift/2026/08/16/curious-case-of-missing-click.html) — Those Who Swift · Issue 281 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Investigates a missing SwiftUI click in the context of a searchable, on-device timeline app. The debugging story highlights how gesture targets and view composition can diverge from the visual hierarchy, a useful reminder when diagnosing apparently inactive controls.
- [Preventing Transitive Swift Imports with Bazel](https://adincebic.com/2026/08/23/preventing-transitive-swift-imports-with.html) — Those Who Swift · Issue 281 — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Explains how permissive transitive Swift imports let a module use dependencies it did not declare directly, and presents Bazel-oriented ways to prevent that leakage. Explicit dependency ownership improves build reasoning and reduces accidental coupling between modules.
- [Detecting (Evil) Dylibs](https://objective-see.org/blog/blog_0x89.html) — SwiftLee Weekly · Issue 338 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `2026-08-25T14:06:16.000Z`
  **NeKI brief:** Surveys static, runtime, and load-time enumeration of dynamic libraries as a basis for detecting dylib-based attacks on modern macOS, including the limits of current mitigations.
- [Amethyst Vein: An Open-Source, Cross-Platform Local Persistence Framework with SwiftData-Style APIs](https://l.fatbobman.com/w0150-6) — Fatbobman’s Swift Weekly · Issue 150 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Presents Vein, an open-source local-first ORM with SwiftData-like macros, model containers, queries, migrations, and a SQLite/SQLCipher backend across Apple platforms, Linux, Android, and Windows. Use it to assess a shared Swift persistence layer rather than assuming SwiftData portability.
- [A Change of State](https://www.createchsol.com/blog/2026-08-12-a-change-of-state.html) — Those Who Swift · Issue 280 — Article · Topics: Cross-Platform & Web · Macros & Metaprogramming · Swift
  **Published:** `2026-08-19T20:31:22.272Z`
  **NeKI brief:** Discusses a change-of-state problem in a software-development context. The piece is relevant as an engineering design note because state transitions are where UI, persistence, and asynchronous work most often need explicit coordination.
- [Unit Testing Navigation Logic In Swiftui](https://azamsharp.com/2026/08/13/unit-testing-navigation-logic-in-swiftui.html) — SwiftLee Weekly · Issue 337 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `2026-08-18T14:06:21.000Z`
  **NeKI brief:** Moves business-dependent destinations into explicit router state so registration roles and conditions can be tested without driving NavigationStack UI. The example separates navigation decisions from view presentation and asserts the resulting route directly.
- [Building Testable SwiftData Apps](https://azamsharp.com/2026/08/02/building-testable-swiftdata-apps.html) — Those Who Swift · Issue 279 — Article · Topics: Swift · SwiftData · Testing
  **Published:** `2026-08-12T20:30:39.583Z`
  **NeKI brief:** Structures SwiftData code so model containers and observations can be exercised outside a SwiftUI view hierarchy. Use it to test persistence behavior and query-driven updates without coupling every assertion to UI rendering.
- [Swift Subprocess 1.0](https://l.fatbobman.com/w0148-08) — Fatbobman’s Swift Weekly · Issue 148 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2026-08-10T12:01:23.212Z`
  **NeKI brief:** Documents the cross-platform swift-subprocess package for launching processes with Swift Concurrency, including streamed I/O, process configuration and an optional Foundation integration trait.
- [getting nowhere with Apple](https://lapcatsoftware.com/articles/2026/7/6.html) — Fatbobman’s Swift Weekly · Issue 145 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-07-20T12:01:22.890Z`
  **NeKI brief:** Diagnoses an App Store Connect login loop by comparing request cookies and finding a missing `dc` session cookie. Follow it for a focused example of browser-level debugging when server behavior contradicts apparent authentication state.
- [MCP for Safari](https://webkit.org/blog/18136/introducing-the-safari-mcp-server-for-web-developers) — iOS Dev Weekly · Issue 758 — Article · Topics: Cross-Platform & Web
  **Published:** `10th July 2026`
  **NeKI brief:** Examines Safari now has an MCP! in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SideScreen](https://www.sidescreen.dev/) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: Cross-Platform & Web
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** SideScreen extends a Mac workspace across an iPad or other display. Follow it for concrete multi-display and window-management behavior, while checking network, performance, and permission requirements.
- [ZMarkupParser](https://github.com/ZhgChgLi/ZMarkupParser) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** A pure-Swift HTML-to-NSAttributedString parser that repairs malformed markup, supports custom tags and styles, and can render, strip, or select content. Its thread-safe implementation and performance report make it a concrete alternative to Foundation HTML parsing.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Those Who Swift · Issue 271 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-06-18`
  **NeKI brief:** Mohammad covers what’s new in SwiftData for iOS 27, showing how enum predicates, sectioned queries, compound predicates, the new .codable attribute, and ResultsObserver remove common workarounds.
- [Building a Custom Data Store in SwiftData](https://azamsharp.com/2026/05/26/building-a-custom-data-store-in-swiftdata.html) — iOS Dev Weekly · Issue 752 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `29th May 2026`
  **NeKI brief:** Walks through implementing a custom SwiftData store and the integration points needed to replace default persistence; useful when evaluating storage backends and their lifecycle trade-offs.
- [Hot Reloading a Bazel-Based iOS App with InjectionNext](https://adincebic.com/2026/05/17/hot-reloading-a-bazelbased-ios.html) — iOS Dev Weekly · Issue 751 — Article · Topics: Cross-Platform & Web · Systems Programming · Testing
  **Published:** `22nd May 2026`
  **NeKI brief:** Presents hot reloading a bazel-based ios app with injectionnext for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Tracking App Store Purchases With Server Notifications](https://azamsharp.com/2026/05/16/storekit2-app-store-server-notifications.html) — Those Who Swift · Issue 267 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-05-21`
  **NeKI brief:** Explains App Store server notifications for tracking subscription purchases. Useful for separating server-confirmed transaction state from client presentation and for designing entitlement updates that survive missed app launches.
- [🔧 Get started with Bazel persistent workers](https://adincebic.com/2026/05/10/a-practical-introduction-to-bazel.html) — iOS CI Newsletter · Issue 88 — Article · Topics: Cross-Platform & Web · Performance
  **Published:** `2026-05-18T00:00:00.000Z`
  **NeKI brief:** Examines Get started with Bazel persistent workers in the context of Cross-Platform & Web and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Install Swift 6.3.1 — Swift.org](https://www.swift.org/install?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Install Swift 6.3.1 — Swift.org in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.](https://www.swift.org/install/windows?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance… in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [WatchLink](https://github.com/tareksabry1337/WatchLink) — Fatbobman’s Swift Weekly · Issue 135 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2026-05-11T12:02:41.178Z`
  **NeKI brief:** WatchLink explores Watch connectivity over ordinary network protocols, allowing the peer to be an iPhone, Android device, or other IP endpoint. Use it when a watch feature should not depend on a proprietary phone-pairing transport.
- [Saying goodbye to CocoaPods: SwiftPM will soon be the default in Flutter!](https://blog.flutter.dev/saying-goodbye-to-cocoapods-swift-package-manager-is-soon-the-default-in-flutter-645a92714a57) — iOS Dev Weekly · Issue 749 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `1st May 2026`
  **NeKI brief:** Does this deserve a “Finally” comment? It’s good to see it happen, regardless. That CocoaPods read-only trunk deadline will come around sooner than we think. As far as I can tell, React Native still currently requires pod, but it appears that they are also…
- [also almost there](https://github.com/react-native-community/discussions-and-proposals/issues/587) — iOS Dev Weekly · Issue 749 — Source repository · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `1st May 2026`
  **NeKI brief:** Does this deserve a “Finally” comment? It’s good to see it happen, regardless. That CocoaPods read-only trunk deadline will come around sooner than we think. As far as I can tell, React Native still currently requires pod, but it appears that they are also…
- [Appearance Mode Changer](https://www.createchsol.com/blog/2026-04-28-appearance-mode-changer.html) — Those Who Swift · Issue 264 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-04-29`
  **NeKI brief:** Introduces OAuth with illustrated explanations. Useful for understanding authorization roles, redirects, and token boundaries before integrating an OAuth flow into an app or service.
- [Introducing Claude Design By Anthropic Labs](https://www.anthropic.com/news/claude-design-anthropic-labs) — Those Who Swift · Issue 263 — Article · Topics: Cross-Platform & Web
  **Published:** `2026-04-22`
  **NeKI brief:** Reviews Introducing Claude Design By Anthropic Labs. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [InfoWorld](https://www.infoworld.com/article/4157422/swift-for-visual-studio-code-comes-to-open-vsx-registry.html?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines InfoWorld in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [@samwize](https://samwize.com/2026/03/30/xcode-simulator-paste-broken-workaround?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: AI Development · Cross-Platform & Web · Xcode
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines @samwize in the context of AI Development and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [official setup guides for editors built on top of it](https://www.swift.org/documentation/articles/getting-started-with-cursor-swift.html) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Presents official setup guides for editors built on top of it for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** We can't wait to see what scary things you will Create with Swift tonight! 🎃👻
- [Wasm](https://www.swift.org/blog/swift-6.2-released) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Swift 6.2 is here with improvements that make coding smoother and faster. It delivers improved performance, faster build times, enhanced tools, and early WebAssembly support, making Swift easier and more reliable for developers.
- [Windows](https://www.swift.org/blog/announcing-windows-workgroup) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Introduces the Swift Windows workgroup. Useful for tracking cross-platform coordination and understanding how platform support influences package portability and contributor workflows.
- [Swift on embedded hardware](https://www.swift.org/blog/embedded-swift-improvements-coming-in-swift-6.3) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Examines Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low… in the context of Combine & Reactive Programming and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Challenges with Ancient Dates in Apple SDKs](https://casualprogrammer.com/blog/2026/03-27-old-dates-in-apple-sdks.html) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats
  **Published:** `10th April 2026`
  **NeKI brief:** What a lovely story of some extremely obscure date bugs from Aaron Trickey. Did you know that Foundation’s date arithmetic breaks before 4713 BC? Or that UIDatePicker won’t go further back than 1 AD? If you’ve ever needed convincing that working with dates…
- [Expanding Animations in SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #231 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-04-06T15:12:39.552Z`
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [CI/CD Build Speed Benchmark: Codemagic Vs GitHub Actions Vs Bitrise](https://blog.codemagic.io/build-speed-benchmark-comparison) — Those Who Swift · Issue 260 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Developer Tools
  **Published:** `2026-04-01`
  **NeKI brief:** Examines How fast can each CI/CD service build your app? in the context of CI/CD & Automation and Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.](https://www.swift.org/documentation/articles/swift-sdk-for-android-getting-started.html?ref=ioscodereview.com) — iOS Code Review · Issue 76 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `2026-03-30T18:21:46.000Z`
  **NeKI brief:** Presents getting started guide for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Those Who Swift · Issue 259 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2026-03-26`
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [SwiftUI Architecture Lessons I Wish I Knew Earlier](https://azamsharp.com/2026/02/18/swiftui-architecture-tips.html) — Those Who Swift · Issue 259 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-03-26`
  **NeKI brief:** Collects practical SwiftUI architecture lessons around state, boundaries, and maintainability. Useful for reviewing ownership and dependency confusion in a view hierarchy before introducing another abstraction.
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Those Who Swift · Issue 258 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-03-18`
  **NeKI brief:** Azam shows how to build a simple sync status monitor for SwiftData, giving users meaningful feedback on what's happening behind the scenes while their data syncs with iCloud.
- [How To Fix Xcode Source Editor Extensions That Don’t Appear In The Editor Menu](https://adincebic.com/2026/03/15/how-to-fix-xcode-source.html) — Those Who Swift · Issue 258 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `2026-03-18`
  **NeKI brief:** Diagnoses Xcode source editor extensions that do not appear in the editor menu. Useful for checking extension targets, host integration, and activation assumptions systematically before treating a missing command as an editor or signing mystery.
- [Avoid Spacers in SwiftUI Stacks](https://nerdyak.tech/development/2023/04/06/avoid-swiftui-spacers-in-stacks.html) — SwiftLee Weekly · Issue 315 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Explains Avoid Spacers in SwiftUI Stacks, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [SwiftUI transitions with distortion effect and Metal Shaders](https://nerdyak.tech/development/2023/06/16/distortionEffect-with-Metal-shaders-for-better-transitions.html) — SwiftLee Weekly · Issue 315 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Explains SwiftUI transitions with distortion effect and Metal Shaders, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Native AI chat app — ultra-fast, privacy-first, 100+ pro features](https://l.fatbobman.com/sb-boltai) — Fatbobman’s Swift Weekly · Issue 127 — Article · Topics: AI Development · Cross-Platform & Web · Security & Privacy
  **Published:** `2026-03-16T12:04:00.245Z`
  **NeKI brief:** Presents BoltAI, a native Mac application for using ChatGPT, Claude, Gemini, and local models. Follow it when evaluating desktop AI tooling, model-provider support, and the boundary between local and hosted inference.
- [what you do?](https://inessential.com/2026/03/03/i-tried-to-explain-what-i-do.html) — iOS Dev Weekly · Issue 745 — Article · Topics: Cross-Platform & Web
  **Published:** `13th March 2026`
  **NeKI brief:** Have you ever tried to explain what you do?? I really like this. ❤️
- [MVVM and the Cost of Carrying Old Patterns Forward](https://azamsharp.com/2026/03/04/mvvm-and-cost-of-old-patterns.html) — Those Who Swift · Issue 257 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-11`
  **NeKI brief:** Azam explores how continuing to apply the MVVM pattern in SwiftUI can add unnecessary complexity and overhead, arguing that developers should rethink older architectural habits and instead leverage SwiftUI’s built-in state management and simpler design…
- [Borrowing from Kotlin/Android to Architect Scalable iOS Apps in SwiftUI](https://www.infoq.com/articles/kotlin-scalable-swiftui-patterns) — SwiftUI Weekly · SwiftUI Weekly - Issue #230 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-09T13:33:31.501Z`
  **NeKI brief:** Translates scalable architecture ideas from Kotlin and Android into SwiftUI patterns, with emphasis on boundaries and composition. Useful for comparing cross-platform architectural trade-offs before adopting abstractions in a growing iOS codebase.
- [vChewing Input Method](https://vchewing.github.io/README.html) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** vChewing documents a Chinese input method built for Apple platforms, including its user-facing behavior and project context. Follow it as a case study in text-input engineering, not as a general Swift UI tutorial.
- [Developers Are Safe… Thanks to Corporate Red Tape](https://azamsharp.com/2026/02/26/developers-are-safe.html) — Those Who Swift · Issue 256 — Article · Topics: AI Development · Architecture · Cross-Platform & Web
  **Published:** `2026-03-06`
  **NeKI brief:** Discusses how corporate process and red tape affect developer safety. Useful as organizational context for evaluating engineering controls and decision friction, not as an API reference.
- [Rich HTML Editor](https://github.com/Infomaniak/swift-rich-html-editor) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** Infomaniak’s Swift Rich HTML Editor provides an editable rich-text component for Swift applications. Follow its source for concrete HTML, selection, and editor integration choices, then verify supported platforms and serialization behavior.
- [latest article](https://shapeof.com/archives/2026/2/greg_knauss_is_losing_himself.html) — iOS Dev Weekly · Issue 744 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `27th February 2026`
  **NeKI brief:** It was Gus Mueller’s latest article that prompted me to write about this topic again this week:
- [Reports have already identified](https://www.nytimes.com/2026/02/23/technology/anthropic-chinese-startups-distillation.html?unlocked_article_code=1.OlA.K6da.1rb5xxt2Us9Q&smid=url-share) — Those Who Swift · Issue 255 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `2026-02-25`
  **NeKI brief:** Reviews Reports have already identified. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [release announcement](https://forums.swift.org/t/grdb-v7-10-0-android-linux-windows-and-sqlcipher-swiftpm/84754) — Fatbobman’s Swift Weekly · Issue 124 — Article · Topics: Cross-Platform & Web · Product Design · Swift
  **Published:** `2026-02-23T12:03:12.462Z`
  **NeKI brief:** GRDB 7.10's release discussion covers Android, Linux, Windows, and SQLCipher packaging, including current SwiftPM trait limitations. Use it when planning cross-platform SQLite support and checking which dependencies Xcode still downloads unnecessarily.
- [If You’re Not Versioning Your SwiftData Schema, You’re Gambling](https://azamsharp.com/2026/02/14/if-you-are-not-versioning-your-swiftdata-schema.html) — Those Who Swift · Issue 254 — Article · Topics: App Distribution & Store Operations · Swift · SwiftData
  **Published:** `2026-02-18`
  **NeKI brief:** Azam explains why schema versioning in SwiftData is essential once your app stores real user data and shows how to define VersionedSchema, implement custom migrations, and evolve models.
- [HealthQL: SQL for Apple HealthKit](https://grantisom.com/2026/02/01/healthql-sql-for-healthkit.html) — iOS Dev Weekly · Issue 742 — Article · Topics: Cross-Platform & Web · Health Apps
  **Published:** `6th February 2026`
  **NeKI brief:** This new package from Grant Isom doesn’t need much summarising, as the purpose is right there in the title. Simple access to HealthKit data from a SQL-like language. There’s a DSL included, too, in case you crave type safety.
- [From Objective-C to Swift 6: What We Gained](https://slicker.me/swift/swift-evolution.html) — Those Who Swift · Issue 252 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-02-04`
  **NeKI brief:** Summarizes the evolution from Objective-C to Swift 6. Useful for historical context when reviewing language migration decisions and the capabilities gained across modern Swift releases.
- [Struggling to Market Your iOS or Android App? Try Affiliate Marketing](https://insertaffiliate.com/) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** This page promotes affiliate marketing as a way to market iOS or Android applications. It is commercial growth guidance rather than technical implementation reading, so use it only as business context.
- [ASCII Sketch](https://files.littlebird.com.au/ascii-sketch.html) — Those Who Swift · Issue 250 — Article · Topics: Cross-Platform & Web
  **Published:** `2026-01-21`
  **NeKI brief:** Provides an interactive ASCII sketching tool. Useful for quick text-based diagrams and lightweight planning when a visual model is needed without introducing a full design application.
- [StoreKit Subscriptions: Understanding Monetization Models](https://azamsharp.com/2025/12/26/storekit-subscriptions-understanding-monetization-models.html) — Those Who Swift · Issue 247 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-01-01`
  **NeKI brief:** Explains StoreKit subscription monetization models. Useful for separating product configuration, eligibility, entitlement state, and paywall presentation when designing subscription flows.
- [forced overnight on iOS 16–18 devices](https://lapcatsoftware.com/articles/2025/12/4.html) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-12-24`
  **NeKI brief:** Examines forced overnight behavior on iOS 16–18 devices. Useful for understanding platform lifecycle and update constraints when diagnosing behavior that appears outside normal foreground app execution.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [SwiftUI Navigation Pain](https://elegantchaos.com/2025/12/12/navigation-pain.html) — Those Who Swift · Issue 245 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines SwiftUI Navigation Pain, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance](https://www.youtube.com/watch?v=YCRvVfDGQuY) — Those Who Swift · Issue 243 — Video · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `2025-12-10`
  **NeKI brief:** Reviews Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Rich and dynamic user interfaces with Flutter and generative UI](https://blog.flutter.dev/rich-and-dynamic-user-interfaces-with-flutter-and-generative-ui-178405af2455) — iOS Dev Weekly · Issue 736 — Article · Topics: Cross-Platform & Web
  **Published:** `21st November 2025`
  **NeKI brief:** The page covers “Rich and dynamic user interfaces with Flutter and generative UI” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [GenUI](https://pub.dev/packages/genui) — iOS Dev Weekly · Issue 736 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `21st November 2025`
  **NeKI brief:** Examines Generates and displays generative user interfaces (GenUI) in Flutter using AI. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [demo video](https://youtu.be/nWr6eZKM6no) — iOS Dev Weekly · Issue 736 — Video · Topics: AI Development · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st November 2025`
  **NeKI brief:** Yes, it’s about a Flutter package, GenUI, but it was the idea that caught my attention. It takes the idea of using LLMs inside an app one step further than having the model return text or structured data. Instead, it returns UI widgets that also contain the…
- [this 30-second slice](https://www.youtube.com/watch?v=nWr6eZKM6no&t=563s) — iOS Dev Weekly · Issue 736 — Video · Topics: AI Development · Cross-Platform & Web
  **Published:** `21st November 2025`
  **NeKI brief:** Yes, it’s about a Flutter package, GenUI, but it was the idea that caught my attention. It takes the idea of using LLMs inside an app one step further than having the model return text or structured data. Instead, it returns UI widgets that also contain the…
- [GSoC 2025 Showcase: Extending Swift-Java Interoperability](https://www.swift.org/blog/gsoc-2025-showcase-swift-java) — Those Who Swift · Issue 240 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Showcases Swift-Java interoperability work from GSoC. Useful for assessing cross-language integration patterns and the practical boundaries of Swift tooling beyond Apple platforms.
- [Meet the new Swift Android SDK with Joannis Orlandos](https://www.youtube.com/watch?v=IfqdY9nuWTo) — Those Who Swift · Issue 240 — Video · Topics: Cross-Platform & Web · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Reviews Meet the new Swift Android SDK with Joannis Orlandos. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) — Fatbobman’s Swift Weekly · Issue 109 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `2025-11-03T12:02:55.598Z`
  **NeKI brief:** The Dev Containers extension adds reproducible container-backed development environments to Visual Studio Code. Use it when comparing local toolchain isolation and onboarding workflows, while separating container setup from Swift package or Xcode build behavior.
- [The Swift Android Setup I Always Wanted](https://dev.to/swiftstream/the-swift-android-setup-i-always-wanted-285d) — Fatbobman’s Swift Weekly · Issue 109 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2025-11-03T12:02:55.598Z`
  **NeKI brief:** Describes a Swift-on-Android setup combining Swift Stream IDE, swift-android-sdk, and JNIKit to build native libraries. Use it when evaluating Android targets that retain Swift source but require NDK and Java interop boundaries.
- [Android Workgroup](https://www.swift.org/android-workgroup) — iOS Dev Weekly · Issue 733 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.. This link is retained as a technical reading lead for Apple-platform development.
- [afterword](https://skip.tools/blog/native-swift-on-android-1) — iOS Dev Weekly · Issue 733 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Examines Native Swift on Android, Part 1: Setup, Compiling, Running, and Testing | Skip. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
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
- [UK designates Apple and Google as having ‘strategic market status’ opening door for more regulation](https://techcrunch.com/2025/10/22/u-k-designates-apple-and-google-as-having-strategic-market-status-opening-door-for-more-regulation) — iOS Dev Weekly · Issue 732 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th October 2025`
  **NeKI brief:** Sarah Perez reports on the UK Competition and Markets Authority’s (CMA) ruling, which starts the process of defining new rules and regulations for iOS, Android, their app stores, and browsers. There will be no immediate changes, as the regulatory process…
- [UK Competition and Markets Authority](https://www.gov.uk/government/organisations/competition-and-markets-authority) — iOS Dev Weekly · Issue 732 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th October 2025`
  **NeKI brief:** Sarah Perez reports on the UK Competition and Markets Authority’s (CMA) ruling, which starts the process of defining new rules and regulations for iOS, Android, their app stores, and browsers. There will be no immediate changes, as the regulatory process…
- [Introducing ChatGPT Atlas](https://www.youtube.com/watch?v=8UWKxJbjriY) — Those Who Swift · Issue 237 — Video · Topics: AI Development · Cross-Platform & Web
  **Published:** `2025-10-22`
  **NeKI brief:** Reviews Introducing ChatGPT Atlas. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [what happened to Apple’s legendary attention to detail?](https://blog.johnozbay.com/what-happened-to-apples-attention-to-detail.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Liquid Glass
  **Published:** `17th October 2025`
  **NeKI brief:** The page covers “what happened to Apple’s legendary attention to detail?” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [commentary on Liquid Glass from the early betas](https://lmnt.me/blog/rose-gold-tinted-liquid-glasses.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Liquid Glass
  **Published:** `17th October 2025`
  **NeKI brief:** Presents commentary on Liquid Glass from the early betas, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Now you can test Xcode apps and Swift packages in Zed](https://luxmentis.org/blog/test-xcode-apps-in-zed) — iOS Dev Weekly · Issue 731 — Article · Topics: Swift · Testing · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Presents now you can test xcode apps and swift packages in zed for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Advanced Codable](https://nothingtocommitworkingtreeclean.com/advanced_codable.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `17th October 2025`
  **NeKI brief:** There’s a nice set of Codable tips and tricks in Alan Kantz-Durand’s latest post. I especially liked the idea of a Maybe:
- [Caveat Emptor](https://elegantchaos.com/2025/10/17/caveat-emptor.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th October 2025`
  **NeKI brief:** Reflects on unfinished and experimental open-source work, and the judgement needed before adopting it. A useful counterweight to feature-driven evaluation when a dependency looks promising but its maintenance, polish, and production readiness remain uncertain.
- [Introducing Swift Profile Recorder: Identifying Performance Bottlenecks in Production](https://www.swift.org/blog/swift-profile-recorder) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Introduces Swift Profile Recorder for capturing runtime profiling data from Swift applications. Useful for collecting reproducible performance evidence in environments where full Instruments sessions are impractical.
- [React-native-enriched](https://github.com/software-mansion-labs/react-native-enriched) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** react-native-enriched exposes a native rich-text editor to React Native with synchronous styling, HTML parsing, and live style detection. Its New Architecture constraint and native text-input design are useful when evaluating editor performance and platform integration boundaries.
- [💪 ReleaseTools: A lightweight alternative to Fastlane written entirely in Swift](https://elegantchaos.com/2025/09/26/release-tools.html) — iOS CI Newsletter · Issue 76 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Swift
  **Published:** `2025-10-01T00:00:00.000Z`
  **NeKI brief:** Summarises ReleaseTools: A lightweight alternative to Fastlane written entirely in Swift for CI/CD & Automation and Cross-Platform & Web. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [incubate](https://www.swift.org/sswg/incubation-process.html) — iOS Dev Weekly · Issue 728 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `26th September 2025`
  **NeKI brief:** Examines Swift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [recommend](https://www.swift.org/sswg/incubated-packages.html) — iOS Dev Weekly · Issue 728 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `26th September 2025`
  **NeKI brief:** Explains recommend, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [YoutubeBarPlayer](https://artiomgramatin.github.io/SunnyAAGWebsite/YoutubeBarPlayer.html) — iOS Dev Tools · iOS Dev Tools: LaunchNext, Feather, DeskRest — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2025-09-25T16:45:27.027Z`
  **NeKI brief:** YoutubeBarPlayer plays YouTube videos from a macOS menu bar popover by accepting a pasted link and embedding playback. Follow it for a concrete lightweight media utility interaction without a full browser window.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Those Who Swift · Issue 232 — Article · Topics: Cross-Platform & Web · Developer Career & Practice · Observation & State Management
  **Published:** `2025-09-17`
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Swift Android Setup I Always Wanted](https://l.fatbobman.com/w0102-05) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Describes a Swift 6 Android setup using the Android NDK and JNIKit to bridge Swift code into Android. Follow it when evaluating cross-platform Swift experiments and the build and interop costs behind them.
- [JNIKit](https://github.com/swifdroid/jni-kit) — Fatbobman’s Swift Weekly · Issue 102 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** JNIKit provides Swift-friendly bindings for Android JNI interaction. Use it when a Swift Android library must call Java or Kotlin APIs, keeping conversion and reference-lifetime rules isolated from application code.
- [Swift-Build GitHub Action](https://l.fatbobman.com/w0102-07) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Provides a GitHub Action for building and testing Swift packages across platforms. Follow it when setting up matrix-based package validation and comparing CI workflows for Linux, macOS, and other supported targets.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [Elevating Android’s security to keep it open and safe](https://developer.android.com/developer-verification) — iOS Dev Weekly · Issue 726 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `12th September 2025`
  **NeKI brief:** Examines Get started building your Android apps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Subprocess](https://github.com/swiftlang/swift-subprocess) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [Watchtower](https://widgetworx.com/apps/watchtower.html) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Article · Topics: Cross-Platform & Web
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** Watchtower presents a monitoring utility for Apple devices or applications. Follow it for concrete alerting and status workflows, while checking data sources and notification boundaries before adoption.
- [🤖 How to generate GitHub Actions workflows automatically](https://elegantchaos.com/2025/08/28/action-builder.html) — iOS CI Newsletter · Issue 74 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-10T00:00:00.000Z`
  **NeKI brief:** Walks through how to generate GitHub Actions workflows automatically, with practical context for Cross-Platform & Web and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Matching Strings In Unit Tests](https://elegantchaos.com/2025/09/03/matching-strings-in-unit-tests.html) — SwiftLee Weekly · Issue 288 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `2025-09-09T18:49:30.000Z`
  **NeKI brief:** Discusses Matching Strings In Unit Tests, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Subprocess](https://l.fatbobman.com/w0101-07) — Fatbobman’s Swift Weekly · Issue 101 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-09-08T12:03:42.721Z`
  **NeKI brief:** Provides Swift Subprocess as a cross-platform package for spawning processes from Swift. Follow it when replacing platform-specific process-launch code and reviewing argument handling, output capture, and portability requirements.
- [The Psychology of Fixing Bugs](https://lapcatsoftware.com/articles/2025/8/8.html) — Those Who Swift · Issue 230 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `2025-09-03`
  **NeKI brief:** Examines the psychology of fixing bugs. Useful for recognizing diagnostic bias and improving debugging habits instead of jumping to the first plausible code change.
- [Pragma Conference](https://www.pragmaconference.com/speakers.html) — SwiftLee Weekly · Issue 287 — Article · Topics: Concurrency · Cross-Platform & Web · Developer Community & Business
  **Published:** `2025-09-02T14:17:18.000Z`
  **NeKI brief:** Describes Pragma Conference, providing the event-specific information needed to identify its Apple-platform community context.
- [ch.at](https://github.com/Deep-ai-inc/ch.at) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: AI Development · Developer Tools · Security & Privacy
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** ch.at is an open-source chat application project from Deep AI Inc. Use the repository to inspect conversational UI, networking, and model-integration patterns, while treating its architecture as an example rather than a production security baseline.
- [Writing a macOS Finder "action" Extension with Swift 6 Concurrency](https://cmsj.net/2025/05/23/finder-action-swift6.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Shows a macOS Finder action extension that bridges synchronous system callbacks into Swift 6 concurrency. Use it when adapting callback-based extension points while preserving correct actor isolation and completion timing.
- [Chris Jones](https://cmsj.net/author/chris-jones.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Provides contextual background on Chris Jones, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [The first time I was almost fired from Apple](https://www.engineersneedart.com/blog/almostfired/almostfired.html) — iOS Dev Weekly · Issue 718 — Article · Topics: Cross-Platform & Web
  **Published:** `18th July 2025`
  **NeKI brief:** The first time I was almost fired from Apple. This link is retained as a technical reading lead for Apple-platform development.
- [YoutubeTranscript](https://github.com/spaceman1412/swift-youtube-transcript) — iOS Dev Tools · iOS Dev Tools: Picasso, YoutubeTranscript, Applite — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-07-17T18:57:30.320Z`
  **NeKI brief:** YoutubeTranscript extracts or processes YouTube transcripts in Swift. Follow its source for concrete request, parsing, and text-processing behavior, while checking API limits, availability, and content-rights boundaries.
- [How to use Google Gemini in Xcode 26 beta](https://zottmann.org/2025/06/13/how-to-use-google-gemini.html) — iOS Dev Weekly · Issue 717 — Article · Topics: AI Development · Cross-Platform & Web · Xcode
  **Published:** `11th July 2025`
  **NeKI brief:** Explains using Google Gemini from a developer workflow, including request setup and practical integration considerations. Use it to compare hosted-model tooling, then verify current authentication, quotas, and data-handling terms.
- [Using WebKit to Load Web Content in SwiftUI](https://www.artemnovichkov.com/blog/using-webkit-to-load-web-content-in-swiftui) — Those Who Swift · Issue 222 — Article · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2025-07-10`
  **NeKI brief:** Artem explores the new WebView and WebPage APIs demonstrating how to integrate web views, handle loading states, and save content as snapshots, all with SwiftUI.
- [An Open‑Source SDK for Finding Dead Code](https://blog.sentry.io/an-open-source-sdk-for-finding-dead-code) — Those Who Swift · Issue 222 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-07-10`
  **NeKI brief:** Examines How Duolingo deleted 1% of their code using this Open Source tool in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Announcing the Android Workgroup](https://forums.swift.org/t/announcing-the-android-workgroup/80666) — Those Who Swift · Issue 221 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `2025-07-02`
  **NeKI brief:** Introduces the Swift Android workgroup. Useful for following Swift’s cross-platform coordination and understanding how ecosystem work affects Android support and package authors.
- [Why Liquid Glass Is Making Cross‑Platform Developers Rethink Flutter](https://ohmyswift.com/blog/2025/06/28/why-liquid-glass-is-making-developers-rethink-flutter) — Those Who Swift · Issue 221 — Article · Topics: Cross-Platform & Web · Liquid Glass · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Explains Why Liquid Glass Is Making Developers Rethink Flutter, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Android Apps in Swift: Getting Started with Skip](https://www.youtube.com/watch?v=AWRPubyQ9V8) — Those Who Swift · Issue 221 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Reviews Android Apps in Swift: Getting Started with Skip. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [AI Coding Assistant Benchmarks: Who Fixes iOS Crashes Best?](https://www.instabug.com/blog/benchmarking-ai-coding-assistants-for-mobile-app-crash-resolution) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `27th June 2025`
  **NeKI brief:** Examines Benchmarking AI Coding Assistants for Mobile App Crash Resolution | Luciq. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [fully supported platform](https://www.swift.org/documentation/articles/wasm-getting-started.html) — iOS Dev Weekly · Issue 715 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th June 2025`
  **NeKI brief:** ² With Swift 6.2, Wasm is becoming a fully supported platform.
- [Bandit - Online Security (or Not) Game](https://overthewire.org/wargames/bandit/bandit0.html) — Those Who Swift · Issue 217 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **Published:** `2025-06-18`
  **NeKI brief:** Provides the Bandit security wargame. Useful for learning command-line security concepts through progressive exercises, while keeping its intentionally vulnerable environment separate from production systems.
- [macOS Tahoe forces all app icons into iOS squircles](https://lapcatsoftware.com/articles/2025/6/2.html) — SwiftLee Weekly · Issue 276 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-06-17T14:10:56.000Z`
  **NeKI brief:** Explains macOS Tahoe forces all app icons into iOS squircles, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.
- [Discussion on Flutter’s Support for Liquid Glass](https://github.com/flutter/flutter/issues/170310) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Liquid Glass
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** This Flutter issue discusses support for Apple's Liquid Glass redesign and related platform integration concerns. Follow the thread for cross-platform implementation constraints and status, not as a guarantee of shipped Flutter behavior.
- [livestream](https://jamesdempsey.net/2025/06/04/live-near-wwdc-2025-livestream.html) — iOS Dev Weekly · Issue 713 — Tutorial · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Community & Business
  **Published:** `6th June 2025`
  **NeKI brief:** Of course, WWDC wouldn’t be complete without a James Dempsey and the Breakpoints benefit concert, and this year it’s supporting Techtonica. You’ll be happy to hear there are a few tickets remaining, or a livestream if you can’t be there in person.
- [🧪 Xtool: A cross-platform Xcode replacement](https://forums.swift.org/t/xtool-cross-platform-xcode-replacement-build-ios-apps-on-linux-and-more/79803) — iOS CI Newsletter · Issue 68 — Article · Topics: Cross-Platform & Web · Swift · Xcode
  **Published:** `2025-05-18T00:00:00.000Z`
  **NeKI brief:** Presents xtool: cross-platform xcode replacement for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Regular Expressions in Swift](https://www.iro.umontreal.ca/~lapalme/RegexInSwift/index.html) — iOS Dev Weekly · Issue 711 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `9th May 2025`
  **NeKI brief:** Presents regular expressions in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [MMKV](https://github.com/Tencent/MMKV) — iOS Dev Tools · iOS Dev Tools: WinWinLinks, MMKV, Harmonize — Source repository · Topics: Cross-Platform & Web · Developer Tools · Performance
  **Published:** `2025-05-08T14:22:48.081Z`
  **NeKI brief:** MMKV provides fast key-value persistence backed by memory-mapped files. Follow its source for concrete serialization, synchronization, and storage behavior, then evaluate durability and cross-platform trade-offs before using it for application state.
- [Why Some Mac Apps Launch Slowly: A Follow-Up](https://lapcatsoftware.com/articles/2025/5/1.html) — Those Who Swift · Issue 213 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-05-07`
  **NeKI brief:** Investigates slow Mac app launch behavior. Useful for separating startup work, system factors, and application initialization when diagnosing launch performance outside iOS.
- [AI Model Showdown: Who Fixes iOS Crashes Best?](https://www.instabug.com/blog/benchmarking-ai-code-fix-mobile-crashes) — iOS Dev Weekly · Issue 709 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `25th April 2025`
  **NeKI brief:** Examines Benchmarking AI Model Code Fix Generation for Mobile App Crashes | Luciq. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [UIApplication Delegate Deprecation Coming in iOS 19 SDK](https://lapcatsoftware.com/articles/2025/4/5.html) — Those Who Swift · Issue 211 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-04-24`
  **NeKI brief:** Discusses UIApplication delegate deprecation in the iOS 19 SDK. Useful for planning lifecycle migrations and identifying compatibility boundaries before removing established delegate-based integration.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0477Default Value in String Interpolations](https://github.com/apple/swift-evolution/blob/main/proposals/0477-default-interpolation-values.md) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Records ImplementedSE-0477Default Value in String Interpolations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Static Linux SDKs](https://www.swift.org/documentation/articles/static-linux-getting-started.html) — iOS CI Newsletter · Issue 65 — Article · Topics: Cross-Platform & Web · Product Design · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Examines Static Linux SDKs in the context of Cross-Platform & Web and Product Design. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) — Those Who Swift · Issue 208 — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2025-04-02`
  **NeKI brief:** Reviews Terminus. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [Kotlin Multiplatform Documentation](https://kotlinlang.org/docs/multiplatform.html) — Those Who Swift · Issue 206 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-03-19`
  **NeKI brief:** Documents Kotlin Multiplatform and its shared-code model. Useful for comparing cross-platform sharing boundaries with native UI and platform integration requirements in an Apple-platform project.
- [Stop Treating Mobile Apps Like Web Apps](https://www.instabug.com/blog/stop-treating-mobile-apps-like-web-apps) — iOS Dev Weekly · Issue 701 — Article · Topics: Cross-Platform & Web
  **Published:** `28th February 2025`
  **NeKI brief:** Discusses Stop Treating Mobile Apps Like Web Apps, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
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
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html?ref=createwithswift.com) — Create with Swift · Issue 46 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-31T16:30:58.000Z`
  **NeKI brief:** Azam explains how to filter SwiftData models using enum values, overcoming query limitations with raw values, while providing code examples and highlighting enums’ benefits.
- [Swift Everywhere: Bringing Swift Packages to Android](https://skip.tools/blog/android-native-swift-packages) — iOS Dev Weekly · Issue 697 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `31st January 2025`
  **NeKI brief:** Presents swift everywhere: bringing swift packages to android for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Objective by the Sea](https://objectivebythesea.org/v7/index.html) — iOS Dev Weekly · Issue 697 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Community & Business
  **Published:** `31st January 2025`
  **NeKI brief:** The Objective by the Sea event might not be directly relevant to your everyday work as a security conference focused on Apple platforms. However, it’s close enough that you’ll almost certainly find something here to interest you.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Those Who Swift · Issue 199 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-30`
  **NeKI brief:** Azam explains how to filter SwiftData models using enum values, overcoming query limitations with raw values, while providing code examples and highlighting enums’ benefits.
- [Announcing: PyObjC 11](https://blog.ronaldoussoren.net/2025/01/14/ann-pyobjc-now-with-less.html) — iOS Dev Weekly · Issue 695 — Article · Topics: Cross-Platform & Web
  **Published:** `17th January 2025`
  **NeKI brief:** I must admit I hadn’t heard of PyObjC for a while until I saw this announcement from Ronald Oussoren. It’s likely not something you want to pick up today if you’re not already using it, but I’m genuinely happy to see it still being maintained and that it…
- [iOS-uploader](https://github.com/simonnilsson/ios-uploader) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** A cross-platform command-line uploader for App Store Connect that accepts familiar altool-style arguments and can upload multiple apps concurrently. Its prebuilt binaries and npm installation make it relevant when CI must publish from Windows, Linux, or macOS.
- [The latest research results announced by Professor Chen Gang's team in China](https://www.stdaily.com/web/gdxw/2024-11/29/content_266525.html) — Fatbobman’s Swift Weekly · Issue 63 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `2024-12-23T12:01:34.355Z`
  **NeKI brief:** Provides contextual background on The latest research results announced by Professor Chen Gang's team in China, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [or Sonumi](https://shaminospage.blogspot.com/2024/02/apples-magic-sound-file-renaming.html) — iOS Dev Weekly · Issue 692 — Article · Topics: Cross-Platform & Web
  **Published:** `20th December 2024`
  **NeKI brief:** I mentioned in the last issue that I didn’t have the full context from Tony Parker and Ben Cohen’s announcement of swift-java. Now the videos from last week’s Server-Side Swift Conference are out, you can watch the whole announcement. All the other session…
- [FlutterSwift library](https://github.com/PADL/FlutterSwift) — iOS Dev Weekly · Issue 691 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `13th December 2024`
  **NeKI brief:** Examines Flutter and Swift integration for iOS, macOS, Android and eLinux - PADL/FlutterSwift. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [platform channels](https://docs.flutter.dev/platform-integration/platform-channels) — iOS Dev Weekly · Issue 691 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `13th December 2024`
  **NeKI brief:** “One thing I really want to drive home is that this is not rocket science. I’ve not done anything half as clever as the Swift team has with C++ and Java interoperability. FlutterSwift is just a few thousand lines of structured concurrency glue around Flutter…
- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) — iOS Dev Tools · iOS Dev Tools: Compose Multiplatform, CoreStore, SourceKitten — Source repository · Topics: Cross-Platform & Web · Developer Tools · Performance
  **Published:** `2024-12-05T17:49:51.669Z`
  **NeKI brief:** Compose Multiplatform shares UI code across Apple and other supported platforms. Follow its repository for concrete composition, rendering, and platform-bridge patterns, while verifying current iOS support and interoperability trade-offs.
- [How I reduce the iOS TPBank app size by half](https://ericsspace.com/articles/how-to-reduce-tpbank-appsize-by-half) — SwiftLee Weekly · Issue 248 — Article · Topics: Cross-Platform & Web
  **Published:** `2024-12-03T14:26:41.000Z`
  **NeKI brief:** Examines A practical example on how to cut your app’s size in half in the context of Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** Mohammad describes in detail the SwiftUI’s environment explaining how it facilitates the sharing of state across views. It begins by exploring the scope and injection of environment objects within the view hierarchy, delves into their behavior during view…
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #203 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-19T05:45:58.937Z`
  **NeKI brief:** Mohammad describes in detail the SwiftUI’s environment explaining how it facilitates the sharing of state across views. It begins by exploring the scope and injection of environment objects within the view hierarchy, delves into their behavior during view…
- [Siamak (Ash) Ashrafi](https://sessionize.com/Ash) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents Siamak (Ash) Ashrafi, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents guide to app architecture for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [learning pathway](https://developer.android.com/courses/pathways/android-architecture) — iOS Dev Weekly · Issue 685 — Tutorial · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents learning pathway for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Modular Navigation in SwiftUI: A Comprehensive Guide](https://ericsspace.com/articles/modular-navigation-in-swiftui-a-comprehensive-guide) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Presents a modular navigation architecture for SwiftUI with separated route and feature concerns. Useful when deep links and navigation flows outgrow a single view's path handling.
- [📦 Are Android apps smaller than iOS apps?](https://www.emergetools.com/blog/posts/are-android-apps-really-that-much-smaller-than-ios) — iOS CI Newsletter · Issue 53 — Article · Topics: Cross-Platform & Web
  **Published:** `2024-10-20T00:00:00.000Z`
  **NeKI brief:** Examines Are Android apps smaller than iOS apps? in the context of Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🔌 Beware of this argument when using xcodebuild and plugins](https://elegantchaos.com/2024/10/11/xcodebuild-platforms-and-plugins.html) — iOS CI Newsletter · Issue 53 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `2024-10-20T00:00:00.000Z`
  **NeKI brief:** Examines Beware of this argument when using xcodebuild and plugins in the context of Cross-Platform & Web and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Introduction to Communication Patterns in SwiftUI](https://azamsharp.com/2024/09/22/introduction-to-communication-patterns-in-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #200 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-09-30T17:14:55.385Z`
  **NeKI brief:** Mohammad explores different ways for SwiftUI views to communicate, such as closures, bindings, and @Environment objects through practical examples and discussing the pros and cons of each method.
- [AVAudioEffectNode: Painless low level audio effects](https://orjpap.github.io/swift/low-level/audio/avfoundation/2024/09/19/avAudioEffectNode.html) — iOS Dev Weekly · Issue 680 — Article · Topics: Cross-Platform & Web · Developer Tools · Foundation & Data Formats
  **Published:** `30th September 2024`
  **NeKI brief:** Examines In a previous post, I covered two AVFoundation nodes that can generate sound or tap into the output of an existing node. If you experiment with them, you'll quickly realize:. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Reality Distortion](https://lmnt.me/blog/reality-distortion.html) — iOS Dev Weekly · Issue 680 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats
  **Published:** `30th September 2024`
  **NeKI brief:** Examines Reality Distortion. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Introduction to Communication Patterns in SwiftUI](https://azamsharp.com/2024/09/22/introduction-to-communication-patterns-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 29 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-09-27T15:10:02.000Z`
  **NeKI brief:** Mohammad explores different ways for SwiftUI views to communicate, such as closures, bindings, and @Environment objects through practical examples and discussing the pros and cons of each method.
- [Building Large Scale Apps SwiftuiBuilding Large-Scale Apps with SwiftUI: A Guide to Modular ArchitectureAzamSharpMohammad Azam](https://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html?ref=ioscodereview.com) — iOS Code Review · Issue 71 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-09-24T10:08:19.000Z`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Global Sheets Pattern in SwiftUI](https://azamsharp.com/2024/08/18/global-sheets-pattern-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 26 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-09-06T15:00:39.000Z`
  **NeKI brief:** Mohammad Azam discusses how to simplify sheet management for apps that require multiple sheets across different screens by centralizing their logic.
- [ever run out of disk space](https://www.dzombak.com/blog/2024/09/Freeing-disk-space-on-GitHub-Actions-runners.html) — iOS Dev Weekly · Issue 677 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `6th September 2024`
  **NeKI brief:** ever run out of disk space. This link is retained as a technical reading lead for Apple-platform development.
- [Skip](https://skip.tools/blog/skip-1_0-release) — iOS Dev Weekly · Issue 676 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `30th August 2024`
  **NeKI brief:** Examines Skip 1.0 Release | Skip. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [FAQ](https://skip.tools/docs/faq) — iOS Dev Weekly · Issue 676 — Article · Topics: Cross-Platform & Web
  **Published:** `30th August 2024`
  **NeKI brief:** So, is it? I haven’t tried it, but it does sound promising after reading the FAQ. This might be worth a look if you’re staring down the barrel of a new cross-platform app.
- [React-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** React Native Vision Camera provides camera access and frame-processing capabilities for React Native applications. Follow its source for concrete native-module, permission, and frame-pipeline integration, while checking platform support.
- [Dark Mode App Icons](https://lmnt.me/blog/dark-mode-app-icons.html) — iOS Dev Weekly · Issue 665 — Article · Topics: Cross-Platform & Web
  **Published:** `14th June 2024`
  **NeKI brief:** Examines Dark Mode App Icons. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Do your builds include SwiftUI Previews and Preview Content?](https://jaredsinclair.com/2024/05/20/preview-content.html) — iOS Dev Weekly · Issue 662 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `24th May 2024`
  **NeKI brief:** Investigates whether SwiftUI previews and preview content are excluded from App Store builds, rather than assuming development assets vanish automatically. Follow it when checking release artifacts, build settings, and the shipping consequences of preview-only code or resources.
- [Google I/O](https://io.google/2024) — iOS Dev Weekly · Issue 661 — Article · Topics: Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Examines Did you catch Google I/O this week? It’s Always Interesting to see what the Android Inventors have been up to during the past Annual Interval. 😂 This 17-minute recap will get you up to speed if you missed it, but it’s s Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [This 17-minute recap](https://youtu.be/MzHCWZB5ZpE) — iOS Dev Weekly · Issue 661 — Video · Topics: Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Did you catch Google I/O this week? It’s Always Interesting to see what the Android Inventors have been up to during the past Annual Interval. 😂 This 17-minute recap will get you up to speed if you missed it, but it’s safe to say it had a theme. Mobile…
- [had a theme](https://youtu.be/MzHCWZB5ZpE?t=994) — iOS Dev Weekly · Issue 661 — Video · Topics: Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Did you catch Google I/O this week? It’s Always Interesting to see what the Android Inventors have been up to during the past Annual Interval. 😂 This 17-minute recap will get you up to speed if you missed it, but it’s safe to say it had a theme. Mobile…
- [Android Studio getting AI-powered code assistance](https://io.google/2024/explore/9986e95b-c506-40f1-b233-54f7e7092fdb) — iOS Dev Weekly · Issue 661 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Presents android studio getting ai-powered code assistance for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [new on-device Gemini model](https://io.google/2024/explore/c8b911cd-6c30-434f-a76e-6099f6a312d9) — iOS Dev Weekly · Issue 661 — Article · Topics: Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Presents new on-device Gemini model, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [updates to Jetpack Compose](https://io.google/2024/explore/d16737ba-e336-4b68-8928-24692a88e644) — iOS Dev Weekly · Issue 661 — Article · Topics: Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Did you catch Google I/O this week? It’s Always Interesting to see what the Android Inventors have been up to during the past Annual Interval. 😂 This 17-minute recap will get you up to speed if you missed it, but it’s safe to say it had a theme. Mobile…
- [Incorrect payments for App Store bundle purchases](https://lapcatsoftware.com/articles/2024/5/2.html) — iOS Dev Weekly · Issue 660 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `10th May 2024`
  **NeKI brief:** Discusses Incorrect payments for App Store bundle purchases, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Dice Challenge in three front-end mobile frameworks](https://medium.com/@jpmtech/dice-challenge-in-swiftui-a26c82ac1367) — iOS Dev Weekly · Issue 660 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `10th May 2024`
  **NeKI brief:** Presents dice challenge in three front-end mobile frameworks for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [two hard problems in computer science](https://martinfowler.com/bliki/TwoHardThings.html) — iOS Dev Weekly · Issue 659 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `3rd May 2024`
  **NeKI brief:** Martin Fowler's bliki entry explains the recurring software-engineering problem of naming and managing changing abstractions.
- [this shiny](https://lmnt.me/blog/icons/ive-drives-vol-3.html) — iOS Dev Weekly · Issue 659 — Article · Topics: Cross-Platform & Web
  **Published:** `3rd May 2024`
  **NeKI brief:** Don’t forget to post any open positions you have available on iOS Dev Jobs!
- [Swift Server Workgroup](https://www.swift.org/sswg) — Fatbobman’s Swift Weekly · Issue 26 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2024-04-08T22:00:36.243Z`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Swift for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang) — Fatbobman’s Swift Weekly · Issue 26 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2024-04-08T22:00:36.243Z`
  **NeKI brief:** Provides the Swift language extension for Visual Studio Code. Follow it when setting up language-server completion, diagnostics, and package workflows outside Xcode, while validating debugger and SDK limitations separately.
- [and beyond](https://blog.persistent.info/2024/03/infinite-mac-nextstep.html) — iOS Dev Weekly · Issue 655 — Article · Topics: Cross-Platform & Web
  **Published:** `5th April 2024`
  **NeKI brief:** Examines persistent.info: Infinite Mac: Turning To The Dark Side. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Skip](https://skip.tools/) — iOS Dev Tools · iOS Dev Tools: Skip, AppLayouts, Firefoo — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `2024-03-21T14:02:34.735Z`
  **NeKI brief:** Skip is an Xcode plugin that translates a shared iOS app codebase for Android delivery. Use it when evaluating a cross-platform workflow that retains Swift and Xcode, while validating platform-specific UI and API boundaries.
- [Making Customizable SwiftUI Components](https://otbivnoe.ru/2024/02/25/Making-Customizable-SwiftUI-Components.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #177 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-02-26T08:21:15.312Z`
  **NeKI brief:** Explains In this article, we’re going to explore different ways of creating customizable components in SwifUI. Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [Introducing Pkl](https://pkl-lang.org/blog/introducing-pkl.html) — iOS Dev Weekly · Issue 647 — Article · Topics: Cross-Platform & Web
  **Published:** `9th February 2024`
  **NeKI brief:** Examines Introducing Pkl, a programming language for configuration :: Pkl Docs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Community Showcase](https://www.swift.org/packages/showcase.html) — iOS Dev Weekly · Issue 646 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2nd February 2024`
  **NeKI brief:** For me, the most exciting part of this page is the Community Showcase, which we will update monthly with community-nominated packages. The first showcase highlights some packages recently discussed on Swift-related podcasts, but the doors are open for…
- [官网](https://letsvisionos24.swiftgg.team/cn/index.html) — Fatbobman’s Swift Weekly · Issue 17 — Article · Topics: Cross-Platform & Web · Spatial Computing · Swift
  **Published:** `2024-01-29T22:00:15.485Z`
  **NeKI brief:** Uses 官网 as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [Unfuddling the SwiftUI Alignment Guide API](https://benscheirman.com/2024/01/swiftui-alignment-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #174 — Article · Topics: Code Quality · Swift · SwiftUI
  **Published:** `2024-01-22T13:02:05.973Z`
  **NeKI brief:** Clarifies SwiftUI's alignment-guide API and the mental model behind custom alignment. Useful when nested layout requirements make default stacks insufficient and alignment closures otherwise become trial and error.
- [Is MVVM Dead in SwiftUI?](https://azamsharp.com/2024/01/09/is-mvvm-dead-in-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #173 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-01-15T11:07:04.573Z`
  **NeKI brief:** Examines whether conventional MVVM adds value in SwiftUI and argues for simpler placement of view-specific logic. Useful as an architecture trade-off discussion when deciding how much indirection a SwiftUI feature actually needs.
- [it depends](https://www.jviotti.com/2024/01/05/is-objective-c-bool-a-boolean-type-it-depends.html) — iOS Dev Weekly · Issue 643 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `12th January 2024`
  **NeKI brief:** As with the answer to most questions, the answer is it depends…
- [Core Data Lab](https://betamagic.nl/products/coredatalab.html) — iOS Dev Tools · 🔨 Setting, Core Data Lab, MonitorControl — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2024-01-11T16:12:03.171Z`
  **NeKI brief:** Core Data Lab provides a dedicated interface for inspecting Core Data stores. Follow it for a concrete local-persistence debugging workflow focused on examining application data outside the running app.
- [Testing network calls using URLProtocol](https://arturgruchala.com/testing-network-calls-using) — Fatbobman’s Swift Weekly · Issue 11 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `2023-12-18T22:00:30.856Z`
  **NeKI brief:** Uses URLProtocol interception to test network calls without a live server. Follow it when isolating request construction, response decoding, and error handling in deterministic XCTest cases.
- [documentation](https://ml-explore.github.io/mlx/build/html/index.html) — iOS Dev Weekly · Issue 639 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `8th December 2023`
  **NeKI brief:** The examples repository shows more of what it’s capable of, with samples covering transformer language models, LLaMA, LoRA, Stable Diffusion, and OpenAI’s Whisper. There’s also a quick start guide and more documentation if you want to explore further.
- [AsyncStream in the real world](https://damian.fyi/swift/2023/12/03/asyncstream-in-the-real-world-wrapping-an-apple-photos-callback.html) — iOS Dev Weekly · Issue 639 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `8th December 2023`
  **NeKI brief:** Presents asyncstream in the real world for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [The Ultimate Swift Data GuideThe Ultimate Guide to Building SwiftData ApplicationsAzamSharpMohammad Azam](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html?ref=ioscodereview.com) — iOS Code Review · Issue 61 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2023-12-07T13:38:43.000Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
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
- [Swift strings look identical but aren’t](https://damian.fyi/swift/2023/11/13/swift-strings-look-identical-but-aren't.html) — iOS Dev Weekly · Issue 636 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `17th November 2023`
  **NeKI brief:** The page covers “Swift strings look identical but aren’t” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [The Complete Guide to JSON Web Tokens (JWT) Authentication in iOS](https://azamsharp.com/2023/11/07/complete-guide-jwt-authentication.html) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** Walks through JWT authentication concepts and an iOS client integration path. Use it to review token storage, request authorization, refresh handling, and expiry failure modes before shipping a networked app.
- [Configuring VSCode](https://www.bryanbraun.com/2023/08/10/things-i-wish-someone-would-have-told-me-about-configuring-vscode) — iOS Dev Weekly · Issue 631 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `13th October 2023`
  **NeKI brief:** Presents configuring vscode for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Boop](https://boop.okat.best/) — iOS Dev Tools · 🔨 Introducing Trace, Boop, FileKit — Article · Topics: Cross-Platform & Web
  **Published:** `2023-10-12T15:37:25.698Z`
  **NeKI brief:** Boop is a small macOS utility page from OKatBest. Follow it to inspect the product’s concrete interaction and positioning, while requiring further page evidence before treating it as a substantive technical resource.
- [Core Data Lab and SwiftData](https://betamagic.nl/news/2023/2023_03.html) — iOS Dev Weekly · Issue 628 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `22nd September 2023`
  **NeKI brief:** I’ve written about Core Data Lab before, and it remains an excellent companion app with enough features specific to Core Data to make it worthwhile over a “regular” Core Data client, so I was excited to read that there’s a beta available for a new release…
- [Xcode Search Scopes](https://xcode.tips/search-scopes) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `4th August 2023`
  **NeKI brief:** Explores Xcode Search Scopes, focusing on i’m a fan of the xcode feature in this latest. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [React Native Vision Camera - Capture the World Differently](https://github.com/daltoniam/Starscream) — iOS Dev Tools · 🔨 Real-time Rendering & Stunning Imagery — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2023-07-13T13:51:39.780Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Download free report](https://yo.bitrise.io/mobile-devops-assessment-report-2023-download.html) — iOS Code Review · Issue 50 — Article · Topics: Apple Platform Ecosystem · Code Quality · Cross-Platform & Web
  **Published:** `2023-06-09T10:49:04.000Z`
  **NeKI brief:** Examines Download free report in the context of Code Quality and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [online live stream](https://jamesdempsey.net/2023/06/01/live-near-wwdc-2023-update.html) — iOS Dev Weekly · Issue 612 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `2nd June 2023`
  **NeKI brief:** Examines Oh, and while I mention James, I linked to the James Dempsey and the Breakpoints live show last week, but there will also be an online live stream! I only wish it didn’t start at 3:30 am in my timezone! 😬 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [meet-ups halfway up a climbing wall](https://dubdub.fitness/climb.html) — iOS Dev Weekly · Issue 611 — Article · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `26th May 2023`
  **NeKI brief:** But as I was gathering links to community-organised events for the newsletter, I found more and more in-person events stretching that “one day” into an entire week, if that’s what you’re looking for. There are additional official Apple events on the Sunday…
- [🤯 Running GitHub Actions workflows locally](https://grantisom.com/2023/05/15/using-act-to.html) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Developer Tools · Personal Essays
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines Running GitHub Actions workflows locally in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [this amazing article](https://bogo.wtf/arm64-to-sim.html) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines this amazing article in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📱 Edit GitHub Actions workflows from your phone](https://github.blog/changelog/2023-05-11-edit-workflow-files-on-github-mobile) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines Edit GitHub Actions workflows from your phone in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Xamarin.Mac](https://learn.microsoft.com/en-us/xamarin/mac) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web
  **Published:** `12th May 2023`
  **NeKI brief:** Examines Xamarin.Mac exposes the complete macOS SDK for .NET developers to build native Mac applications using C#. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [React Native for macOS](https://microsoft.github.io/react-native-windows) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `12th May 2023`
  **NeKI brief:** Examines Build native Windows apps with Javascript and React. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [official desktop showcase](https://microsoft.github.io/react-native-windows/resources-showcase) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `12th May 2023`
  **NeKI brief:** The React Native for Windows showcase presents official desktop resources and examples for building Windows applications with the framework.
- [The launch of the Mojo language](https://www.fast.ai/posts/2023-05-03-mojo-launch.html) — iOS Dev Weekly · Issue 608 — Article · Topics: AI Development · Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `5th May 2023`
  **NeKI brief:** The fast.ai post announces the Mojo programming language and describes its goals for high-performance machine-learning and systems development.
- [Phased Releases](https://dev.shoppingukapp.com/2023/04/12/phased-releases.html) — iOS Dev Weekly · Issue 605 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `14th April 2023`
  **NeKI brief:** Examines Dip your toe in the water. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🤯 Using the -why_load linker flag to reduce app size](https://asifmohd.github.io/ios/2023/03/30/reducing-ios-app-size-using-linker.html) — iOS CI Newsletter · Issue 13 — Article · Topics: Cross-Platform & Web · Developer Tools · Systems Programming
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Examines Using the -why_load linker flag to reduce app size in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Improving multiplatform SwiftUI code](https://www.jessesquires.com/blog/2023/03/23/improve-multiplatform-swiftui-code) — iOS Dev Weekly · Issue 602 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `24th March 2023`
  **NeKI brief:** Explores Improving multiplatform SwiftUI code, focusing on the article discusses liked the simple solution that jesse squires. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [David Smith’s post on a watchOS design conundrum](https://www.david-smith.org/blog/2023/03/16/design-notes-32) — iOS Dev Weekly · Issue 601 — Article · Topics: Cross-Platform & Web
  **Published:** `17th March 2023`
  **NeKI brief:** Examines Pixel Perfection - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building Large Scale Apps with SwiftUI](http://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html) — iOS Dev Weekly · Issue 601 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th March 2023`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Building Large-Scale Apps with SwiftUI: A Guide to Modular Architecture](https://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #134 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2023-03-06T15:27:12.172Z`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [bliki: GivenWhenThena bliki entry for GivenWhenThenmartinfowler.comMartin Fowler](https://martinfowler.com/bliki/GivenWhenThen.html?ref=ioscodereview.com) — iOS Code Review · Issue 44 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `2023-03-02T12:48:03.000Z`
  **NeKI brief:** Examines bliki: GivenWhenThena bliki entry for GivenWhenThenmartinfowler.comMartin Fowler in the context of Cross-Platform & Web and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Quickstart CI/CD by Runway](https://www.runway.team/blog/introducing-quickstart-ci-cd-by-runway) — iOS CI Newsletter · Issue 10 — Article · Topics: CI/CD & Automation · Cross-Platform & Web
  **Published:** `2023-02-26T00:00:00.000Z`
  **NeKI brief:** Examines Quickstart CI/CD by Runway in the context of CI/CD & Automation and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
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
- [Using JavaScript in a Swift app](https://douglashill.co/javascript-in-swift) — iOS Dev Weekly · Issue 594 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `27th January 2023`
  **NeKI brief:** Explains Using JavaScript in a Swift app, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [powerful tool](https://www.adobe.com/products/aftereffects.html) — iOS Dev Weekly · Issue 589 — Article · Topics: Cross-Platform & Web
  **Published:** `16th December 2022`
  **NeKI brief:** Examines With Adobe After Effects, the industry-standard motion graphics software, you can take any idea and make it move. Design for film, TV, video, and web. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Soto and Swift Build Plugin experiments](https://soto.codes/2022/12/build-plugin-experiments.html) — iOS Dev Weekly · Issue 588 — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `9th December 2022`
  **NeKI brief:** Explores Soto and Swift Build Plugin experiments, focusing on code generation during a swift package build process is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Making App Store Connect better](https://lapcatsoftware.com/articles/crappstoreconnect2.html) — iOS CI Newsletter · Issue 3 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Examines Making App Store Connect better in the context of App Distribution & Store Operations and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Lesser known features of the VS Code Swift extension](https://opticalaberration.com/2022/11/vscode-features.html) — iOS Dev Weekly · Issue 584 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `11th November 2022`
  **NeKI brief:** Examines Here are some of the less known features of the Visual Studio code Swift extension. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to regenerate Xcode managed provisioning profiles](https://lapcatsoftware.com/articles/provisioning.html) — iOS CI Newsletter · Issue 2 — Article · Topics: App Distribution & Store Operations · Performance · Xcode
  **Published:** `2022-11-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to regenerate Xcode managed provisioning profiles, with practical context for App Distribution & Store Operations and Performance. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Top Three iOS Mobile App Security Myths](https://www.guardsquare.com/video/misconceptions-about-ios-mobile-app-security) — iOS Dev Weekly · Issue 583 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **Published:** `4th November 2022`
  **NeKI brief:** It’s easy to get caught up in the myths surrounding mobile app security. But the biggest misconception may just be that iOS security is better than Android. Watch this video to learn about the most common misconceptions of iOS mobile app security and how you…
- [LSP Server is up and running](https://codeface.io/blog/posts/using-lsp-servers-in-codeface-via-lspservice/index.html) — iOS Dev Weekly · Issue 580 — Article · Topics: Cross-Platform & Web · Personal Essays
  **Published:** `14th October 2022`
  **NeKI brief:** Examines Codeface can inspect codebases of all languages because it can leverage LSP servers. Here is how to use LSPService to make these servers available. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Women Who Code Mobile Summit 2022](https://www.youtube.com/playlist?list=PLVcEZG2JPVhf_iA733UhMxPS0H8iCoouj) — iOS Dev Weekly · Issue 580 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `14th October 2022`
  **NeKI brief:** Explores Women Who Code Mobile Summit 2022, focusing on the article discusses missed this when women who code first. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [history of nil messaging](http://mutable-states.com/message-to-no-one.html) — iOS Dev Weekly · Issue 579 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `7th October 2022`
  **NeKI brief:** It has been a while since Objective-C got a mention in the newsletter. Does that make it a good time to link to this well-researched history of nil messaging? I think it does! 🙇
- [Initialization — The Swift Programming Language (Swift 5.7)](https://docs.swift.org/swift-book/LanguageGuide/Initialization.html?ref=ioscodereview.com) — iOS Code Review · Issue 33 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2022-10-06T11:12:57.000Z`
  **NeKI brief:** Examines Initialization — The Swift Programming Language (Swift 5.7) in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [macOS / iOS Developers @ Kagi Inc.](https://browser.kagi.com/faq.html) — iOS Dev Weekly · Issue 578 — Article · Topics: Cross-Platform & Web
  **Published:** `30th September 2022`
  **NeKI brief:** The page covers “macOS / iOS Developers @ Kagi Inc.” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Swift for Android](https://github.com/apple/swift/blob/main/docs/Android.md) — iOS Dev Weekly · Issue 577 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Yes, you can write Swift for Android, but I think it’s fair to say that JetBrains is promoting Kotlin as a language you can use with Apple platforms more than Apple is promoting Swift for Android development. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [a language you can use with Apple platforms](https://kotlinlang.org/lp/mobile) — iOS Dev Weekly · Issue 577 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Kotlin Multiplatform is a technology for reusing up to 100% of your code across Android, iOS, web, and desktop, with Compose Multiplatform for shared UIs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Callable structs](https://docs.swift.org/swift-book/ReferenceManual/Declarations.html?ref=ioscodereview.com) — iOS Code Review · Issue 31 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2022-09-08T10:50:25.000Z`
  **NeKI brief:** Examines Callable structs in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [iOS App Security: Is it really better than Android?](https://www.guardsquare.com/is-ios-app-security-really-better-than-android) — iOS Dev Weekly · Issue 574 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Security & Privacy
  **Published:** `2nd September 2022`
  **NeKI brief:** Examines Is iOS really more secure than Android? Here’s what you need to know about iOS mobile app security. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Sharing cross-platform code in SwiftUI apps](https://www.jessesquires.com/blog/2022/08/19/sharing-code-in-swiftui-apps) — iOS Dev Weekly · Issue 574 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2nd September 2022`
  **NeKI brief:** Explores Sharing cross-platform code in SwiftUI apps, focusing on there’s no doubt that swiftui makes cross-platform¹ development easier, but. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [late initialisation](https://kotlinlang.org/docs/properties.html) — iOS Dev Weekly · Issue 574 — Article · Topics: Cross-Platform & Web
  **Published:** `2nd September 2022`
  **NeKI brief:** Do lose sleep thinking about force unwrapped variables as a result of needing to assign values outside of initialisation? I liked the solution that Steve Landey mentions in this post of using an @AssignedOnce property wrapper. I also hadn’t come across…
- [Shaders Explained - Gradients](https://mtldoc.com/metal/2022/08/04/shaders-explained-gradients.html) — iOS Dev Weekly · Issue 570 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `5th August 2022`
  **NeKI brief:** Examines Shaders Explained: Gradients | MTLDoc. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [View Is The View Model](https://azamsharp.com/2022/07/21/view-is-the-view-model.html) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th July 2022`
  **NeKI brief:** Explores View Is The View Model, focusing on do you need view models if you’re working with swiftui?. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Multiline TextField in SwiftUI](https://otbivnoe.ru/2022/07/10/Finally-Multiline-TextField-in-SwiftUI.html) — iOS Dev Weekly · Issue 567 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `15th July 2022`
  **NeKI brief:** Explores Multiline TextField in SwiftUI, focusing on the article discusses have seen so many different implementations of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [this extension](https://github.com/alexanderweiss/nova-prettier) — iOS Dev Weekly · Issue 565 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `1st July 2022`
  **NeKI brief:** Examines Prettier extension for Nova. Contribute to alexanderweiss/nova-prettier development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Picture is Worth 1000 Words](https://github.com/girliemac/a-picture-is-worth-a-1000-words) — iOS Dev Weekly · Issue 564 — Source repository · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `24th June 2022`
  **NeKI brief:** Wow. This repository! I saw a link to Tomomi Imura’s outstanding collection of sketch notes explaining everything from algorithms and data structures through machine learning to some web development and JavaScript tips. They may not appear immediately…
- [algorithms and data structures](https://github.com/girliemac/a-picture-is-worth-a-1000-words/blob/main/algorithms) — iOS Dev Weekly · Issue 564 — Source repository · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `24th June 2022`
  **NeKI brief:** Presents algorithms and data structures, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [machine learning](https://github.com/girliemac/a-picture-is-worth-a-1000-words/blob/main/ml) — iOS Dev Weekly · Issue 564 — Source repository · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `24th June 2022`
  **NeKI brief:** Presents machine learning, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [web development and JavaScript tips](https://github.com/girliemac/a-picture-is-worth-a-1000-words/blob/main/webdev) — iOS Dev Weekly · Issue 564 — Source repository · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `24th June 2022`
  **NeKI brief:** Presents web development and JavaScript tips, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [#unavailable](https://docs.swift.org/swift-book/ReferenceManual/Attributes.html?ref=ioscodereview.com) — iOS Code Review · Issue 25 — Article · Topics: Cross-Platform & Web · Swift · Xcode
  **Published:** `2022-06-16T10:30:01.000Z`
  **NeKI brief:** Examines #unavailable in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [vscode-swift](https://github.com/swift-server/vscode-swift) — iOS Dev Weekly · Issue 559 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th May 2022`
  **NeKI brief:** Explores vscode-swift, focusing on if you had told me five years ago that in 2022, writing swift in a javascript-based text editor from microsoft called visual. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Running games in the browser with SwiftWasm](https://pyrus.io/2021/05/15/gaming-with-swiftwasm.html) — iOS Dev Weekly · Issue 559 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `20th May 2022`
  **NeKI brief:** Explains Running games in the browser with SwiftWasm, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Are alternative app stores worth it?](https://www.apptamin.com/blog/are-alternative-app-stores-worth-it) — iOS Dev Weekly · Issue 557 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `6th May 2022`
  **NeKI brief:** Examines With the looming DMA and Open Markets Acts that aim to open the app markets to alternative app stores, their time to shine may be just around the corner. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [couldn’t agree more](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/eea9b4d5fbf85893d3a5de71cc0c6bd8cbbbc8d6/FrontEnd/styles/colors.scss) — iOS Dev Weekly · Issue 556 — Source repository · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `29th April 2022`
  **NeKI brief:** The repository file shows the Swift Package Index server's frontend color stylesheet at a specific revision, providing concrete source-level styling reference.
- [Web Inspector on iOS devices and Simulators](https://bendodson.com/weblog/2022/04/13/web-inspector-on-ios-devices-simulators) — iOS Dev Weekly · Issue 554 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `15th April 2022`
  **NeKI brief:** If you’ve ever done any web development, you’ll be intimately familiar with the Safari web inspector. It’s an essential part of building anything for the web. Of course, the web browser is also often used inside native apps, so it’s a terrible shame that you…
- [with !! and friends](https://www.man7.org/linux/man-pages/man3/history.3.html) — iOS Dev Weekly · Issue 553 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web · Developer Tools
  **Published:** `8th April 2022`
  **NeKI brief:** Here’s a great Terminal tip from Presh Onyee. Combine this with !! and friends and you’ve got yourself a great recipe for saving lots of keypresses. 🚀
- [Injection](http://johnholdsworth.com/injection.html) — iOS Dev Weekly · Issue 553 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `8th April 2022`
  **NeKI brief:** Explores Injection II, the App in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [the official Swift documentation](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html?ref=ioscodereview.com) — iOS Code Review · Issue 20 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2022-04-07T10:47:31.000Z`
  **NeKI brief:** Examines the official Swift documentation in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Profiling binary size on iOS using Bloaty](https://asifmohd.github.io/ios/2022/02/03/bloaty-ios-introduction.html) — iOS Dev Weekly · Issue 545 — Article · Topics: Cross-Platform & Web · Developer Tools · Performance
  **Published:** `11th February 2022`
  **NeKI brief:** Examines I’ve been using this tool called Bloaty McBloatface1 to attribute the contribution of each swift module or file to our app’s binary. And it has worked out really well for me, the C. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html?ref=ioscodereview.com) — iOS Code Review · Issue 15 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2022-01-27T11:57:44.000Z`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html) — iOS Dev Weekly · Issue 541 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `14th January 2022`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [the official Unicode documentation](http://unicode.org/reports/tr35/tr35-31/tr35-dates.html?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Examines the official Unicode documentation in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [associated blog post](https://www.joshholtz.com/blog/2021/10/27/joshs-m1-development-environemnt.html) — iOS Dev Weekly · Issue 531 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `29th October 2021`
  **NeKI brief:** Examines This is the setup I’m using on my M1 Mac (and Rosetta) to handle homebrew, zsh, Ruby and python version managers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Evolving our business model to address developer needs](https://android-developers.googleblog.com/2021/10/evolving-business-model.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Evolving our business model to address developer needs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [announced in March](https://android-developers.googleblog.com/2021/03/boosting-dev-success.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Boosting developer success on Google Play. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Logarithmic Volume Control](https://dcordero.me/posts/logarithmic_volume_control.html) — iOS Dev Weekly · Issue 530 — Article · Topics: Cross-Platform & Web
  **Published:** `22nd October 2021`
  **NeKI brief:** Explores Logarithmic Volume Control, focusing on if you had asked me whether i’d ever link to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [the official language reference on patterns in Swift](https://docs.swift.org/swift-book/ReferenceManual/Patterns.html?ref=ioscodereview.com) — iOS Code Review · Issue 8 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2021-09-30T11:10:38.000Z`
  **NeKI brief:** Examines the official language reference on patterns in Swift in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Validate your iOS and Android translations with Locheck](https://blog.asana.com/2021/09/locheck-open-source) — iOS Dev Weekly · Issue 525 — Article · Topics: Cross-Platform & Web · Localization · Personal Essays
  **Published:** `17th September 2021`
  **NeKI brief:** This new tool from Steve Landey will be invaluable if you have a large app with localisations. It checks for several types of bugs that are easy to miss when you’re not constantly running in all your localised languages. 👍
- [Keeping WWDC videos and sample code current](https://dimsumthinking.com/Blog/2021/08/30-KeepingCurrent.html) — iOS Dev Weekly · Issue 523 — Article · Topics: Apple Platform Ecosystem · Concurrency · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Keeping WWDC videos and sample code current, focusing on here’s another advantage of not having on-stage presentations at wwdc.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Circular Gestures with the 2nd Gen Siri Remote](https://dcordero.me/posts/capture_circular_gestures_on_siri_remote_2nd_generation.html) — iOS Dev Weekly · Issue 523 — Article · Topics: App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Circular Gestures with the 2nd Gen Siri Remote, focusing on it’s been a while since i saw anyone write about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Droid (Stats) You’re Looking For](https://blog.curtisherbert.com/slopes-diaries-40-the-droid-stats-youre-looking-for) — iOS Dev Weekly · Issue 514 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `2nd July 2021`
  **NeKI brief:** Examines Curtis Herbert posted this the day before WWDC started, and while I wanted to link to it, that’s terrible timing! If you write an iOS-only app, it’s so easy to dismiss the idea of creating an Android version for so many Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Spokestack - AutoML tools that put custom voice into software](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zcG9rZXN0YWNrLmlvLz91dG1fY2FtcGFpZ249bWFrZXJfbGF1bmNoX1BBSUQmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPXN3aWZ0dWlfd2Vla2x5IiwicG9zdF9pZCI6Ijk4NTQyZmUzLTllOWYtNGZmOC05OWMwLTQ0ODc1NzNiZDY0MiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlMGQxNjc5Mi0xZmY1LTRhMjEtOTg0Yy00ZTk0MThiOWEzOWUiLCJpYXQiOjE2NzQwNjI2NzcuMDEsImlzcyI6Im9yY2hpZCJ9.atUK69hH2ROd-1KMu7E8qDPRvdFtWbAB5xcDUbJ8hiU) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Presents Spokestack tools for adding custom voice interfaces and models to software. Use it as a discovery lead when evaluating speech-triggered features, model training workflow, and service dependencies.
- [Unexpectedly](http://s.sudre.free.fr/Software/Unexpectedly/about.html) — iOS Dev Weekly · Issue 509 — Article · Topics: Cross-Platform & Web
  **Published:** `28th May 2021`
  **NeKI brief:** The page documents Unexpectedly, a macOS application, and provides its product description and usage information as an openly readable HTML page.
- [Shawn Marston](http://www.no-snagz.com/shawn.html) — iOS Dev Weekly · Issue 509 — Article · Topics: Cross-Platform & Web
  **Published:** `28th May 2021`
  **NeKI brief:** Examines Thanks so much to this week’s iOS Dev Weekly Insiders! Ilter Cengiz, Paul Jackson, Shawn Marston, shengchalover, and Russ Shanahan. Thank you so much for your generosity. 😍 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [JavaScriptCore and Swift](https://www.andyibanez.com/posts/javascriptcore-and-swift) — iOS Dev Weekly · Issue 503 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `16th April 2021`
  **NeKI brief:** Explores JavaScriptCore and Swift, focusing on like most people, i have mixed feelings about javascript. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Inspecting SwiftUI views](https://fivestars.blog/swiftui/inspecting-views.html) — iOS Dev Weekly · Issue 500 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `26th March 2021`
  **NeKI brief:** Examines Inspecting SwiftUI views, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Digging deeper into xcbuild: Rules and Tasks](https://asifmohd.github.io/ios/2021/03/11/xcbuild-debug-info.html) — iOS Dev Weekly · Issue 499 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `19th March 2021`
  **NeKI brief:** Examines While debugging incremental builds for my work project. I came across this github gist by Daniel Dunbar who worked on the llbuild build engine for Swift and Xcode. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Setting up a multi-platform SwiftUI project](https://blog.scottlogic.com/2021/03/04/Multiplatform-SwiftUI.html) — iOS Dev Weekly · Issue 499 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `19th March 2021`
  **NeKI brief:** Covers Setting up a multi-platform SwiftUI project, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Core Store](https://dimsumthinking.com/Blog/2021/03/04-CoreStore.html) — iOS Dev Weekly · Issue 497 — Article · Topics: Combine & Reactive Programming · Core Data · Persistence & Synchronisation
  **Published:** `5th March 2021`
  **NeKI brief:** Examines Core Store, focusing on core data works well with new technologies like swiftui and combine, but does it feel at home with them? it does not. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Hummingbird](https://opticalaberration.com/2021/02/hummingbird.html) — iOS Dev Weekly · Issue 496 — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **Published:** `26th February 2021`
  **NeKI brief:** Examines Hummingbird, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [fastlane and the Upcoming Two-Step/Two-Factor Enforcement](https://www.joshholtz.com/blog/2021/02/17/apples-2fa-with-fastlane.html) — iOS Dev Weekly · Issue 495 — Article · Topics: CI/CD & Automation · Concurrency · Cross-Platform & Web
  **Published:** `19th February 2021`
  **NeKI brief:** Examines Preface. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Combine Kickstart](https://editorscut.com/Blog/2021/02/04-Combine.html) — iOS Dev Weekly · Issue 493 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web · Functional Programming
  **Published:** `5th February 2021`
  **NeKI brief:** The page covers “A Combine Kickstart” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Open-Source iOS & macOS Chat SDK](https://github.com/getstream/stream-chat-swift) — iOS Dev Weekly · Issue 492 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `29th January 2021`
  **NeKI brief:** Explains Open-Source iOS & macOS Chat SDK, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Brad Cox, Creator of Objective-C, Passes](https://shapeof.com/archives/2021/1/brad_cox_objective-c_creator_passes.html) — iOS Dev Weekly · Issue 492 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th January 2021`
  **NeKI brief:** Presents Brad Cox, Creator of Objective-C, Passes, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [which scissor emojis could actually cut paper](https://wh0.github.io/2020/01/02/scissors.html) — iOS Dev Weekly · Issue 488 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `1st January 2021`
  **NeKI brief:** Covers which scissor emojis could actually cut paper, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 486 — Source repository · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `11th December 2020`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [open-source](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server) — iOS Dev Weekly · Issue 486 — Source repository · Topics: Swift · Swift Package Manager · Testing
  **Published:** `11th December 2020`
  **NeKI brief:** Examines open-source, focusing on georgios recommends the point-free swift-snapshot-testing which we also use to test the rendered html output from the…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [What went wrong with the libdispatch?](https://tclementdev.com/posts/what_went_wrong_with_the_libdispatch.html) — iOS Dev Weekly · Issue 484 — Article · Topics: Cross-Platform & Web
  **Published:** `27th November 2020`
  **NeKI brief:** This post from Thomas Clement got a fair bit of discussion on Twitter this week, and it’s definitely worth a read. If I had to summarise the post, I’d say:
- [Adaptive SwiftUI views](https://fivestars.blog/swiftui/adaptive-swiftui-views.html) — iOS Dev Weekly · Issue 480 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Adaptive SwiftUI views, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [View Controllers without XIBs](https://padraig.org/appkit/2020/10/25/layout-in-code.html) — iOS Dev Weekly · Issue 480 — Article · Topics: Cross-Platform & Web · macOS & AppKit · Swift
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Notes from a Swift programmer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building Fast and Slow](https://bthdonohue.com/2020/09/18/building-fast-and-slow.html) — iOS Dev Weekly · Issue 480 — Article · Topics: Cross-Platform & Web
  **Published:** `30th October 2020`
  **NeKI brief:** The page covers “Building Fast and Slow” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Mastering transitions in SwiftUI](https://nerdyak.tech/development/2020/10/12/transitions-in-swiftui.html) — iOS Dev Weekly · Issue 478 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `16th October 2020`
  **NeKI brief:** Examines Mastering transitions in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [App Store Reviews Should be Stricter](https://tirania.org/blog/archive/2020/Sep-24.html) — iOS Dev Weekly · Issue 475 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `25th September 2020`
  **NeKI brief:** This is a very interesting post by Miguel de Icaza talking about the benefits of having a trusted App Store. He argues for some rule amendments, as well as several changes to the purchasing UI and App Store listing pages.
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
- [Introducing the farmers pattern](http://blog.huenaerts.be/2020/08/08/farmers-pattern.html) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web
  **Published:** `14th August 2020`
  **NeKI brief:** I hadn’t heard of the farmers pattern before, and as Bram Huenaerts explains, you probably won’t have either since it’s something he made up! You should read about it though, there’s a great piece of advice in here.
- [Building a Multi-platform App with SwiftUI](https://heartbeat.fritz.ai/building-a-multi-platform-app-with-swiftui-5336bce94689) — iOS Dev Weekly · Issue 468 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `7th August 2020`
  **NeKI brief:** Examines Building a Multi-platform App with SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Creating custom .redacted effects](https://fivestars.blog/code/redacted-custom-effects.html) — iOS Dev Weekly · Issue 467 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `31st July 2020`
  **NeKI brief:** Examines Creating custom .redacted effects, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Daniel Steinberg drew some conclusions](https://www.drawingyourownconclusions.com/2020/07/06/State.html) — iOS Dev Weekly · Issue 464 — Article · Topics: Cross-Platform & Web
  **Published:** `10th July 2020`
  **NeKI brief:** Examines I loved this year’s WWDC session Data Essentials in SwiftUI. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Double-Edged Sword](https://mohsen.dev/2020/06/21/swiftui-double-edged-sword.html) — iOS Dev Weekly · Issue 462 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines Double-Edged Sword, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [TikTok logo-ish effect in SwiftUI](https://nerdyak.tech/development/2020/06/12/create-tiktok-logo-effect-in-swiftui.html) — iOS Dev Weekly · Issue 461 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `19th June 2020`
  **NeKI brief:** Examines TikTok logo-ish effect in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Blueprint Icon](https://www.wooji-juice.com/free/blueprint/index.html) — iOS Dev Weekly · Issue 457 — Article · Topics: Cross-Platform & Web
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Blueprint Icon. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Everything wrong with XCFrameworks](https://pyckamil.github.io/programming,/xcframework,/xcode/2020/05/09/everything-wrong-with-xcframeworks.html) — iOS Dev Weekly · Issue 456 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `15th May 2020`
  **NeKI brief:** Presents Everything wrong with XCFrameworks, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Developing Inclusive Mobile Apps](https://www.apress.com/gp/book/9781484258132) — iOS Dev Weekly · Issue 455 — Article · Topics: Accessibility · Cross-Platform & Web · Swift
  **Published:** `8th May 2020`
  **NeKI brief:** Examines To combat the issue of online exclusion, this book covers considerations mobile developers, or anyone creating mobile experiences, can use to make mobile work better for those with. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [accessibility in SwiftUI](https://mobilea11y.com/blog/swiftui-talk) — iOS Dev Weekly · Issue 455 — Article · Topics: Accessibility · Swift · SwiftUI
  **Published:** `8th May 2020`
  **NeKI brief:** The title of this new book from Rob Whitaker is something we should all be doing. 👍 It covers the technical side of things using both UIKit and SwiftUI (as well as some other platform called Android). Inclusivity and accessibility is so much more than just…
- [Optionals in Swift Objective-C Interoperability](https://fabiancanas.com/blog/2020/1/9/swift-undefined-behavior.html) — iOS Dev Weekly · Issue 452 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `17th April 2020`
  **NeKI brief:** Examines Optionals in Swift Objective-C Interoperability. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Loca Studio – a native Mac app to xcloc like a pro](https://www.cunningo.com/locastudio/index.html) — iOS Dev Weekly · Issue 451 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `10th April 2020`
  **NeKI brief:** Examines Loca Studio – a native Mac app to xcloc like a pro, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Useful Global Swift Functions](https://swiftrocks.com/useful-global-swift-functions.html) — iOS Dev Weekly · Issue 449 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `27th March 2020`
  **NeKI brief:** Could you have named any of the Swift global functions? I might have got dump, and then I’d probably have (wrongly) guessed print. Take a tour of them with Bruno Rocha.
- [Mac App Store in a nutshell](https://lapcatsoftware.com/articles/nutshell.html) — iOS Dev Weekly · Issue 449 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `27th March 2020`
  **NeKI brief:** Examines Mac App Store in a nutshell. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Getting the Bigger Role](https://bthdonohue.com/2020/03/25/getting-the-bigger-role.html) — iOS Dev Weekly · Issue 449 — Article · Topics: Cross-Platform & Web
  **Published:** `27th March 2020`
  **NeKI brief:** Brian Donohue with an article that’s nothing about iOS development, but will help you if you’re always hoping to move into that more senior position, but it just doesn’t seem to be happening. As always from Brian, there’s some great advice in here.
- [Understanding Combine](https://www.apeth.com/UnderstandingCombine/toc.html) — iOS Dev Weekly · Issue 448 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `20th March 2020`
  **NeKI brief:** Examines Understanding Combine. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Look Into ArgumentParser](https://www.fivestars.blog/code/a-look-into-argument-parser.html) — iOS Dev Weekly · Issue 448 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th March 2020`
  **NeKI brief:** Examines A Look Into ArgumentParser, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [the ultimate guide to Swift executables](https://www.fivestars.blog//code/ultimate-guide-swift-executables.html) — iOS Dev Weekly · Issue 448 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th March 2020`
  **NeKI brief:** Examines the ultimate guide to Swift executables, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Rewriting Messenger to be faster, smaller, and simpler](https://engineering.fb.com/data-infrastructure/messenger) — iOS Dev Weekly · Issue 446 — Article · Topics: Cross-Platform & Web
  **Published:** `6th March 2020`
  **NeKI brief:** Presents Rewriting Messenger to be faster, smaller, and simpler, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [conventional wisdom](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i) — iOS Dev Weekly · Issue 446 — Article · Topics: Cross-Platform & Web
  **Published:** `6th March 2020`
  **NeKI brief:** There is a very old, and very famous blog post from Joel Spolsky that states that the “single worst strategic mistake that any software company can make” is to rewrite an app from scratch.
- [Random Acts of Pragmatism](https://elegantchaos.com/2020/03/06/random-acts-of-pragmatism.html) — iOS Dev Weekly · Issue 446 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `6th March 2020`
  **NeKI brief:** Reflects on pragmatic engineering choices that solve the problem at hand without pretending every decision is a general architecture rule. Useful as a reminder to state constraints and trade-offs explicitly in technical work.
- [Federico Zanetello’s article on it](https://www.fivestars.blog//code/the-swift-behind-the-standard-library-preview-package.html) — iOS Dev Weekly · Issue 444 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `21st February 2020`
  **NeKI brief:** Examines Exploring iOS, SwiftUI & much more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Xcode’s Find Navigator & Search Scopes](https://patrickbalestra.com/blog/2020/02/09/xcode-find-navigator.html) — iOS Dev Weekly · Issue 443 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Xcode
  **Published:** `14th February 2020`
  **NeKI brief:** Examines Xcode's Find Navigator & Search Scopes, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Introducing Swift Crypto](https://swift.org/blog/crypto) — iOS Dev Weekly · Issue 442 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** I didn’t expect to read about a new cross-platform crypto framework that echoes the functionality of CryptoKit from Apple this week, but here it is. This is a fantastic step forward for Swift on the server, and I hope it prevents anyone from ever trying to…
- [Swift fatalError is a fatal error](https://lapcatsoftware.com/articles/fatalError.html) — iOS Dev Weekly · Issue 440 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `24th January 2020`
  **NeKI brief:** Examines Swift fatalError is a fatal error. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Animating complex shapes in SwiftUI](https://nerdyak.tech/development/2020/01/12/animating-complex-shapes-in-swiftui.html) — iOS Dev Weekly · Issue 439 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th January 2020`
  **NeKI brief:** Examines Animating complex shapes in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Using Type Erasure to Build a Dependency Injecting Routing Framework](https://swiftrocks.com/using-type-erasure-to-build-a-dependency-injector-in-swift.html) — iOS Dev Weekly · Issue 437 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `3rd January 2020`
  **NeKI brief:** Examines Using Type Erasure to Build a Dependency Injecting Routing Framework, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Custom controls in SwiftUI](https://izakpavel.github.io/development/2019/11/28/creating-custom-views-in-swiftui.html) — iOS Dev Weekly · Issue 434 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Custom controls in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dice](https://pcalc.com/dice/index.html) — iOS Dev Weekly · Issue 425 — Article · Topics: Cross-Platform & Web
  **Published:** `11th October 2019`
  **NeKI brief:** So macOS Catalina is here and with it, the first set of Catalyst apps. The conversation on Catalyst has been mostly drowned out by this all summer, so it was fascinating for me to read James Thomson’s piece on his experimentation with potentially bringing…
- [Advice for Software Apprentices](http://bthdonohue.com/2019/09/27/advice-software-apprentices.html) — iOS Dev Weekly · Issue 424 — Article · Topics: Cross-Platform & Web · Developer Career & Practice
  **Published:** `4th October 2019`
  **NeKI brief:** Discusses Advice for Software Apprentices, connecting the concrete app-design or distribution decision to practical considerations for Apple-platform developers.
- [Looking Elsewhere](https://blog.curtisherbert.com/slopes-diaries-32-looking-elsewhere) — iOS Dev Weekly · Issue 419 — Article · Topics: Cross-Platform & Web
  **Published:** `30th August 2019`
  **NeKI brief:** As with every post on Curtis Herbert’s blog, this is an exceptionally well thought out post about whether, how, and when to consider an Android version of your app.
- [The (not so) hidden cost of cross platform code](https://blogs.dropbox.com/tech/2019/08/the-not-so-hidden-cost-of-sharing-code-between-ios-and-android) — iOS Dev Weekly · Issue 417 — Article · Topics: Cross-Platform & Web
  **Published:** `16th August 2019`
  **NeKI brief:** I really enjoyed this piece by Eyal Guthmann. I don’t think it’s possible to completely generalise on this topic, and it certainly works better for some companies than others. What was really refreshing though was to hear someone talk about some of the…
- [Injecting and changing code on the fly with LLDB](https://swiftrocks.com/using-lldb-manually-xcode-console-tricks.html) — iOS Dev Weekly · Issue 416 — Article · Topics: Cross-Platform & Web · Dependency Injection · Swift
  **Published:** `9th August 2019`
  **NeKI brief:** Examines Injecting and changing code on the fly with LLDB, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [This post](https://qnoid.com/2019/07/29/Windmill-on-the-iPhone.html) — iOS Dev Weekly · Issue 415 — Article · Topics: Cross-Platform & Web
  **Published:** `2nd August 2019`
  **NeKI brief:** The post documents the Windmill project on iPhone and explains the author's implementation and experimentation details.
- [Swift 5.1 Collection Diffing](https://www.fivestars.blog/code/swift-5-1-collection-diffing.html) — iOS Dev Weekly · Issue 414 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `26th July 2019`
  **NeKI brief:** Examines Exploring iOS, SwiftUI & much more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS 13 Large Content Viewer](https://www.fivestars.blog/code/large-content-viewer.html) — iOS Dev Weekly · Issue 412 — Article · Topics: Cross-Platform & Web
  **Published:** `12th July 2019`
  **NeKI brief:** The article explains the iOS 13 Large Content Viewer accessibility feature and how developers can support it in custom interfaces.
- [One small change for Xcode, one giant leap for productivity](http://mohsen.dev/2019/05/19/one-small-change-for-xcode-one-giant-leap-for-productivity.html) — iOS Dev Weekly · Issue 409 — Article · Topics: Cross-Platform & Web · Personal Essays · Xcode
  **Published:** `21st June 2019`
  **NeKI brief:** Examines One small change for Xcode, one giant leap for productivity, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [The Things You May Have Missed at WWDC 2019](https://patrickbalestra.com/blog/2019/06/07/wwdc-2019-the-things-you-may-have-missed.html) — iOS Dev Weekly · Issue 408 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `14th June 2019`
  **NeKI brief:** Presents The Things You May Have Missed at WWDC 2019, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [XCLogParser](https://github.com/spotify/XCLogParser) — iOS Dev Weekly · Issue 408 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `14th June 2019`
  **NeKI brief:** Examines Tool to parse Xcode and xcodebuild logs stored in the xcactivitylog format - MobileNativeFoundation/XCLogParser. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How To Adopt Dark Mode In Your iOS App](https://www.fivestars.blog/code/ios-dark-mode-how-to.html) — iOS Dev Weekly · Issue 408 — Article · Topics: Cross-Platform & Web
  **Published:** `14th June 2019`
  **NeKI brief:** What a wonderfully comprehensive guide to Dark Mode from Federico Zanetello. For such a (relatively) simple feature, there’s still plenty to learn about if you’re implementing it.
- [Declarative iOS layout with Panda](http://blog.bellebcooper.com/ios-layout-with-panda.html) — iOS Dev Weekly · Issue 407 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `7th June 2019`
  **NeKI brief:** Examines Declarative iOS layout with Panda, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [decent guide here](https://jaimzuber.com/san-jose-convention-guide.html) — iOS Dev Weekly · Issue 406 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `31st May 2019`
  **NeKI brief:** The page covers “decent guide here” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [released a new declarative UI framework](https://developer.android.com/jetpack/compose) — iOS Dev Weekly · Issue 403 — Article · Topics: Cross-Platform & Web
  **Published:** `10th May 2019`
  **NeKI brief:** Finally, Google released a new declarative UI framework (which I found via this hot take 😀) at their I/O event this week.
- [NSUserDefaults In Practice](http://dscoder.com/defaults.html) — iOS Dev Weekly · Issue 400 — Article · Topics: Cross-Platform & Web
  **Published:** `19th April 2019`
  **NeKI brief:** Examines NSUserDefaults In Practice. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Understanding the iOS Responder Chain](https://swiftrocks.com/understanding-the-ios-responder-chain.html) — iOS Dev Weekly · Issue 394 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Examines Understanding the iOS Responder Chain, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [method_missing](https://ruby-doc.org/core-2.1.0/BasicObject.html) — iOS Dev Weekly · Issue 385 — Article · Topics: Cross-Platform & Web
  **Published:** `4th January 2019`
  **NeKI brief:** Examines Class : BasicObject - Ruby 2.1.0. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Fun with Unicode in Swift](https://tworingsoft.com/blog/2018/12/10/fun-with-unicode-in-swift.html) — iOS Dev Weekly · Issue 382 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `14th December 2018`
  **NeKI brief:** Examines Looking at some ways to write tricky Swift code using Unicode. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [React Native Accessibility is Pretty Bad](http://takingnotes.co//blog/2018/11/09/react-native-accessibility) — iOS Dev Weekly · Issue 381 — Article · Topics: Accessibility · Cross-Platform & Web
  **Published:** `7th December 2018`
  **NeKI brief:** Examines Allow me to preface this by saying that React Native sets out to solve problems I don’t think are very interesting to solve. In particular I don’t think that sharing a single UI be. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this is worth a read](https://lapcatsoftware.com/articles/notarization-privacy.html) — iOS Dev Weekly · Issue 381 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `7th December 2018`
  **NeKI brief:** We knew to expect changes requiring the new notarization (sic) feature in Mojave, but I must admit they’re happening quicker than I expected. Also, this is worth a read from Jeff Johnson.
- [All you need is tools](https://ppinera.es/2018/11/25/all-you-need-is-tools.html) — iOS Dev Weekly · Issue 380 — Article · Topics: Cross-Platform & Web
  **Published:** `30th November 2018`
  **NeKI brief:** The article surveys the tools the author considers useful for software development and explains their practical role in a working workflow.
- [Measuring iOS scroll performance is tough](http://thisiskyle.me/posts/measuring-ios-scroll-performance-is-tough-use-this-to-make-it-simple-and-automated.html) — iOS Dev Weekly · Issue 380 — Article · Topics: Cross-Platform & Web · Performance · Testing
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Measuring iOS scroll performance is tough, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [the concept](https://css-tricks.com/debouncing-throttling-explained-examples) — iOS Dev Weekly · Issue 380 — Article · Topics: Cross-Platform & Web
  **Published:** `30th November 2018`
  **NeKI brief:** Examines The following is a guest post by David Corbacho, a front end engineer in London. We've broached this topic before, but this time, David is going to drive the. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Implementing Support for Continuity Camera](https://thomas.zoechling.me/journal/2018/10/Continuity.html) — iOS Dev Weekly · Issue 375 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `26th October 2018`
  **NeKI brief:** Examines Build and Run: Implementing Support for Continuity Camera. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dark Mode and CSS](https://blog.iconfactory.com/2018/10/dark-mode-and-css) — iOS Dev Weekly · Issue 375 — Article · Topics: Concurrency · Cross-Platform & Web
  **Published:** `26th October 2018`
  **NeKI brief:** I know we’re straying quite far from iOS development with this article from Craig Hockenberry. But, you all have web sites to market your apps, and people look at those web sites on macOS in Dark Mode. Justified! 😂
- [Icon design considerations for modern iPhones](http://jontelang.com/blog/2018/09/27/Icon-design-considerations-for-iphone-x-etc.html) — iOS Dev Weekly · Issue 372 — Article · Topics: Cross-Platform & Web · Personal Essays
  **Published:** `5th October 2018`
  **NeKI brief:** Examines Despite what the title of this post is, this actually affects all phones running iOS 11+ and is not limited to the “X formfactor”. However I found it most vi. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [disabling all warnings](https://guides.cocoapods.org/syntax/podfile.html) — iOS Dev Weekly · Issue 369 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Objective-C & Cocoa
  **Published:** `14th September 2018`
  **NeKI brief:** Examines CocoaPods Guides - Podfile Syntax Reference v1.16.1. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Improving Your Build Time in Xcode 10](https://patrickbalestra.com/blog/2018/08/27/improving-your-build-time-in-xcode-10.html) — iOS Dev Weekly · Issue 367 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Xcode
  **Published:** `31st August 2018`
  **NeKI brief:** Explores Improving Your Build Time in Xcode 10 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [surprisingly good](https://www.adobe.com/uk/products/xd.html) — iOS Dev Weekly · Issue 367 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `31st August 2018`
  **NeKI brief:** Examines Adobe XD Help. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Active Record validations from Rails](https://guides.rubyonrails.org/active_record_validations.html) — iOS Dev Weekly · Issue 366 — Article · Topics: Cross-Platform & Web
  **Published:** `24th August 2018`
  **NeKI brief:** Validated from Brandon Williams and Stephen Celis is a tiny library for collecting multiple errors together rather than bailing at the first sign of trouble! 😀 It reminds me a little of Active Record validations from Rails.
- [How to Reply to iOS and Google Play Reviews Like a Pro](https://appfigures.com/resources/reply-to-ios-android-app-reviews) — iOS Dev Weekly · Issue 366 — Article · Topics: Cross-Platform & Web
  **Published:** `24th August 2018`
  **NeKI brief:** Examines Replying to app reviews has many benefits, but is a challenge if you want to do it right. In this guide you. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Adobe XD](https://www.adobe.com/products/xd.html) — iOS Dev Weekly · Issue 365 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `17th August 2018`
  **NeKI brief:** Examines Adobe XD Help. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Buggy code to appease the Chinese government](https://objective-see.com/blog/blog_0x34.html) — iOS Dev Weekly · Issue 360 — Article · Topics: Cross-Platform & Web
  **Published:** `13th July 2018`
  **NeKI brief:** Did you see the “Taiwan” bug that was fixed in iOS 11.4.1 this week? More interesting than the bug was the reason it existed, and even more interesting than that, the incredibly detailed explanation that Patrick Wardle always provides.
- [ARM based Macs](http://shapeof.com/archives/2018/6/marzipan_to_arm_on_mac.html) — iOS Dev Weekly · Issue 358 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th June 2018`
  **NeKI brief:** The article discusses ARM-based Macs and the possible platform and software consequences of Apple's processor transition.
- [App slices](https://developer.android.com/guide/slices) — iOS Dev Weekly · Issue 351 — Article · Topics: Cross-Platform & Web
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Slices are UI templates that display rich, dynamic, and interactive content from your app within Google Search, Google Assistant, and other surfaces, enabling users to perform task. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Retrobatch](http://shapeof.com/archives/2018/5/retrobatch_public_beta.html) — iOS Dev Weekly · Issue 351 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `11th May 2018`
  **NeKI brief:** This is a new tool from Gus Mueller (creator of Acorn) looks very cool. Think of it like Automator for image processing. If you’re regularly processing assets for your apps, you’ll want to check out this public beta.
- [Show and Tell](http://dimsumthinking.com/Blog/2018/03/28-ShowAndTell.html) — iOS Dev Weekly · Issue 345 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `30th March 2018`
  **NeKI brief:** Examines Dim Sum Thinking. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Getting Started with Flutter](https://www.raywenderlich.com/188257/getting-started-with-flutter) — iOS Dev Weekly · Issue 343 — Article · Topics: Cross-Platform & Web
  **Published:** `16th March 2018`
  **NeKI brief:** Examines Getting Started with Flutter, focusing on the author’s note that came across flutter a few weeks ago but hadn’t had a chance to check it out. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [the documentation](http://researchkit.org/docs/docs/ChartsAndGraphs/ChartsAndGraphs.html) — iOS Dev Weekly · Issue 343 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th March 2018`
  **NeKI brief:** Presents the documentation, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [The Complete List of iOS and Android Conferences in 2018](https://bugfender.com/conferences) — iOS Dev Weekly · Issue 336 — Article · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `26th January 2018`
  **NeKI brief:** Examines One place information for all the events, across the globe. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this article](https://www.bloomberg.com/news/articles/2017-12-20/apple-is-said-to-have-plan-to-combine-iphone-ipad-and-mac-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `22nd December 2017`
  **NeKI brief:** Reports the historical proposal to unify iPhone, iPad, and Mac app distribution or development. Use it as platform-strategy context when assessing multiplatform architecture, while treating predictions as historical and checking the current Apple deployment model.
- [Learning with Privacy at Scale](https://machinelearning.apple.com/2017/12/06/learning-with-privacy-at-scale.html) — iOS Dev Weekly · Issue 330 — Article · Topics: AI Development · Cross-Platform & Web · Security & Privacy
  **Published:** `8th December 2017`
  **NeKI brief:** Despite all of the other posts on analytics this week 😀 this is the one that you should read. Differential privacy is a fascinating subject and like with any posts on Apple’s machine learning blog, while I don’t understand most of it, the results are really…
- [Observing the A11’s Heterogenous Cores](http://www.mikeash.com/pyblog/friday-qa-2017-11-10-observing-the-a11s-heterogenous-cores.html) — iOS Dev Weekly · Issue 327 — Article · Topics: Cross-Platform & Web
  **Published:** `17th November 2017`
  **NeKI brief:** Let’s kick this week’s code section off in the most hardcore way possible. The A11 is an amazing chip and Mike Ash is going to give you a wonderful tour of the heterogeneous cores in the new processor. 🚀
- [Introducing Cloud Firestore](http://firebase.googleblog.com/2017/10/introducing-cloud-firestore.html) — iOS Dev Weekly · Issue 321 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `6th October 2017`
  **NeKI brief:** Introduces Cloud Firestore as a hosted document database with synchronization and querying intended for app backends. Useful historical context for choosing a managed data service, while current SDK behavior and pricing require fresh verification.
- [Swift 4 Weak References](https://mikeash.com/pyblog/friday-qa-2017-09-22-swift-4-weak-references.html) — iOS Dev Weekly · Issue 320 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `29th September 2017`
  **NeKI brief:** Examines mikeash.com: Friday Q&A 2017-09-22: Swift 4 Weak References. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Deep Learning for Siri’s Voice](https://machinelearning.apple.com/2017/08/06/siri-voices.html) — iOS Dev Weekly · Issue 315 — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `25th August 2017`
  **NeKI brief:** Examines Siri is a personal assistant that communicates using speech synthesis. Starting in iOS 10 and continuing with new features in iOS 11, we…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [what text is displayed on the screen](https://machinelearning.apple.com/2017/08/02/inverse-text-normal.html) — iOS Dev Weekly · Issue 315 — Article · Topics: App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `25th August 2017`
  **NeKI brief:** I also really enjoyed another of their articles posted this week on how Siri turns what it says into what text is displayed on the screen. What a fascinating team that must be to work on.
- [Swift in Android Apps](http://johnholdsworth.com/bothworlds.html) — iOS Dev Weekly · Issue 314 — Article · Topics: Cross-Platform & Web · Personal Essays · Swift
  **Published:** `18th August 2017`
  **NeKI brief:** Explains Swift in Android Apps, focusing on the concrete iOS implementation technique and the trade-offs relevant to production applications.
- [New report suggests app makers should charge more if they want people to buy subscriptions](https://www.theverge.com/2017/8/15/16147954/liftoff-report-apple-ios-android-app-subscriptions-conversion-rate-2017) — iOS Dev Weekly · Issue 314 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `18th August 2017`
  **NeKI brief:** There has been lots of discussion around in-app subscriptions again this week after Ulysses switched from pay-to-own to a subscription model. In this post, Lauren Goode looks at a Liftoff report which says that charging more actually reduces the cost per…
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
- [announced as a first class language for Android development](https://events.google.com/io) — iOS Dev Weekly · Issue 303 — Article · Topics: Cross-Platform & Web
  **Published:** `2nd June 2017`
  **NeKI brief:** You’ve probably heard mention of Kotlin quite a bit over the last couple of weeks since it was announced as a first class language for Android development. Even though you won’t be using it for iOS development, are you interested in what it looks like? If…
- [Swift 3 migration post mortem](https://mozilla-mobile.github.io/ios/firefox/swift/core/2017/02/22/migrating-to-swift-3.0.html) — iOS Dev Weekly · Issue 289 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** Explores Swift 3 migration post mortem in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Whither Swift?](http://lapcatsoftware.com/articles/whither-swift.html) — iOS Dev Weekly · Issue 288 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** The article reflects on Swift's direction and development ecosystem, providing a historical technical perspective on the language.
- [70 Cents Put Me on the Mac App Store Charts](http://lapcatsoftware.com/articles/70cents.html) — iOS Dev Weekly · Issue 286 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `3rd February 2017`
  **NeKI brief:** This is an unbelievable story and just shows how top heavy the MAS has become. Is it time to call it a failure yet? I think it might be. Such a shame.
- [We reverse engineered 16k apps, here’s what we found](https://hackernoon.com/we-reverse-engineered-16k-apps-heres-what-we-found-51bdf3b456bb) — iOS Dev Weekly · Issue 285 — Article · Topics: Cross-Platform & Web
  **Published:** `27th January 2017`
  **NeKI brief:** The page covers “We reverse engineered 16k apps, here’s what we found” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [list of goals](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20160725/025676.html) — iOS Dev Weekly · Issue 284 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th January 2017`
  **NeKI brief:** Examines list of goals, focusing on this document appeared last night in the swift repository and it contains a huge amount of information about the plans…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [fantastic project lead](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20170109/030078.html) — iOS Dev Weekly · Issue 283 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `13th January 2017`
  **NeKI brief:** Will this affect Swift? Well it’s a big loss for sure, but the language will be absolutely fine. Chris will still be involved as a member of the core team and it’s been a long time since it was his project. Ted is going to make a fantastic project lead and…
- [simMagnifier](http://microedition.biz/simMagnifier/index.html) — iOS Dev Weekly · Issue 283 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `13th January 2017`
  **NeKI brief:** Examines Easily access your latest run apps on iOS Simulators. Explore folders, edit Core Data content, and much more!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Android](https://github.com/kickstarter/android-oss) — iOS Dev Weekly · Issue 281 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `16th December 2016`
  **NeKI brief:** Interesting news from the team at Kickstarter as they open sourced their mobile clients this week. There’s some information and history behind the decision in the post linked here, then plenty to learn from in the iOS and Android repositories.
- [migration guide](http://asyncdisplaykit.org/docs/adoption-guide-2-0-beta1.html) — iOS Dev Weekly · Issue 280 — Article · Topics: Concurrency · Cross-Platform & Web
  **Published:** `9th December 2016`
  **NeKI brief:** Examines Texture. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Keyframes](https://github.com/facebookincubator/Keyframes) — iOS Dev Weekly · Issue 278 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `25th November 2016`
  **NeKI brief:** Examines A library for converting Adobe AE shape based animations to a data format and playing it back on Android and iOS devices. - facebookarchive/Keyframes. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [libgd](https://libgd.github.io/manuals/2.2.3/files/preamble-txt.html) — iOS Dev Weekly · Issue 278 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `25th November 2016`
  **NeKI brief:** The page covers “libgd” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Perfect code is an illusion](https://8thlight.com/blog/daniel-irvine/2016/11/11/perfect-code-is-an-illusion.html) — iOS Dev Weekly · Issue 277 — Article · Topics: Cross-Platform & Web
  **Published:** `18th November 2016`
  **NeKI brief:** Daniel Irvine argues that pursuing perfect code obscures the iterative and contextual nature of software work. It is a craft perspective for balancing refinement against delivery.
- [How to Deploy Vapor Apps to Heroku](https://www.twilio.com/blog/2016/11/how-to-deploy-vapor-apps-to-heroku.html) — iOS Dev Weekly · Issue 275 — Article · Topics: Cross-Platform & Web · Personal Essays · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Explores How to Deploy Vapor Apps to Heroku in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [significant thought and effort](http://shapeof.com/archives/2016/11/notes_on_working_with_nstouchbar_apis.html) — iOS Dev Weekly · Issue 275 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `4th November 2016`
  **NeKI brief:** The article records detailed thoughts on working with NSTouchBar APIs and the engineering effort required to integrate them.
- [Origami Studio](http://origami.design/tutorials/getting-started/Getting-Started.html) — iOS Dev Weekly · Issue 274 — Tutorial · Topics: Cross-Platform & Web
  **Published:** `28th October 2016`
  **NeKI brief:** Origami has been around for a long time now! But where it was once built on top of Quartz Composer, Origami Studio is a standalone app, and it’s great. Your workflow stays mainly the same as the old version, but it now has a modern, fast UI which is a huge…
- [How to Set up Your iOS or Android App for Viral Growth](https://blog.branch.io/tracking-virality-and-influencers-in-your-android-or-ios-app) — iOS Dev Weekly · Issue 273 — Article · Topics: Cross-Platform & Web
  **Published:** `21st October 2016`
  **NeKI brief:** Viral growth is every app developer’s dream. Creating features that drive this growth will help you sustainably grow and set your app on a path to success. This post takes you through the essential steps and code examples to identify viral features, harness…
- [Swift on Android, Part Two: What Now?](http://modocache.io/swift-on-android-now) — iOS Dev Weekly · Issue 272 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Examines There has been talk (and even action) around using Swift on Android ever since it was first open sourced. This week, Brian Gesiak wrote on the continuing progress as well as talking about whether it’s the right choice. U Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [action](https://github.com/apple/swift/pull/1442) — iOS Dev Weekly · Issue 272 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Provides the pull request source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Why I’m not a React Native Developer](https://arielelkin.github.io/articles/why-im-not-a-react-native-developer) — iOS Dev Weekly · Issue 270 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `30th September 2016`
  **NeKI brief:** Examines Why I'm not a React Native Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Migrating Code Signing Configurations to Xcode 8](http://pewpewthespells.com/blog/migrating_code_signing.html) — iOS Dev Weekly · Issue 267 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Xcode
  **Published:** `9th September 2016`
  **NeKI brief:** Walks through iOS code signing, certificates, provisioning profiles, validation, and the migration from Xcode 7 signing methods to Xcode 8. Useful when supporting projects that combine automatic and manual signing across teams.
- [React Native at Artsy](http://artsy.github.io/blog/2016/08/15/React-Native-at-Artsy) — iOS Dev Weekly · Issue 266 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines As the Artsy iOS app grew larger, we started hitting pain points: We want to support other future platforms such as Android without creatin. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The Churn by Robert C. Martin](http://blog.cleancoder.com/uncle-bob/2016/07/27/TheChurn.html) — iOS Dev Weekly · Issue 262 — Article · Topics: Cross-Platform & Web
  **Published:** `5th August 2016`
  **NeKI brief:** This essay reflects on code churn and the pressure to measure visible feature output while neglecting maintenance and design quality. It offers a useful engineering-management lens for evaluating whether process activity is improving software or merely increasing change volume.
- [post on swift-dev](https://lists.swift.org/pipermail/swift-dev/Week-of-Mon-20160725/002520.html) — iOS Dev Weekly · Issue 261 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `29th July 2016`
  **NeKI brief:** Examines post on swift-dev, focusing on jesse squires with some advice on how to approach converting your code, or in this case open source libraries, to swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Why we put an app in the Android Play Store using Swift](https://medium.com/@ephemer/why-we-put-an-app-in-the-android-play-store-using-swift-96ac87c88dfc) — iOS Dev Weekly · Issue 259 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Examines Why we put an app in the Android Play Store using Swift, focusing on can you include swift code in your android app? yes, you can. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [how they did it](https://medium.com/@ephemer/how-we-put-an-app-in-the-android-play-store-using-swift-67bd99573e3c) — iOS Dev Weekly · Issue 259 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Examines how they did it, focusing on can you include swift code in your android app? yes, you can. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [robot building](http://slideslive.com/38897350/how-i-built-open-hardware-robot-cz) — iOS Dev Weekly · Issue 257 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Examines Tomáš Jukin · How I built Open Hardware robot [CZ] · SlidesLive. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Localization works… when users download your app](https://www.ibabbleon.com/iosdevweekly.html) — iOS Dev Weekly · Issue 253 — Article · Topics: Cross-Platform & Web · Localization
  **Published:** `3rd June 2016`
  **NeKI brief:** Examines The only localization company made up of ONLY translators. Every language in the App Store!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [reason](https://lists.swift.org/pipermail/swift-users/Week-of-Mon-20160530/002087.html) — iOS Dev Weekly · Issue 253 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `3rd June 2016`
  **NeKI brief:** The Swift Users mailing-list post contains a public developer discussion about the reason behind a Swift language or API behavior.
- [open source](https://github.com/decosoftware/deco-ide) — iOS Dev Weekly · Issue 253 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd June 2016`
  **NeKI brief:** If you’re getting started with React Native and looking for something more than just a standard text editor to assist you, this is worth a look. It’s early days and it’s a little buggy, but there’s a component library which will save you looking up the…
- [Will We See Android-Like Instant Apps on iOS?](http://holko.pl/2016/05/22/instant-apps) — iOS Dev Weekly · Issue 252 — Article · Topics: Cross-Platform & Web
  **Published:** `27th May 2016`
  **NeKI brief:** Explains Will We See Android-Like Instant Apps on iOS?, focusing on the concrete iOS implementation technique and the trade-offs relevant to production applications.
- [Paw](https://luckymarmot.com/paw) — iOS Dev Weekly · Issue 252 — Article
  **Published:** `27th May 2016`
  **NeKI brief:** Micha Mazaheri on the process of allowing Paw (which is excellent if you haven’t tried it) to support JavaScript extensions. There’s all sorts of information in here, from the technical details of how to do it right through to how it encouraged them to think…
- [Render: Swift and UIKit a la React](https://github.com/alexdrone/Render) — iOS Dev Weekly · Issue 252 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `27th May 2016`
  **NeKI brief:** Examines Render: Swift and UIKit a la React, focusing on if you like the concept of your ui being purely a function of your app’s state, but are not quite ready to go all in on…. Use it as a focused research reference for related.
- [Why porting an iOS design to Android will not work](http://martiancraft.com/blog/2016/05/porting-ios-design-to-andoid) — iOS Dev Weekly · Issue 252 — Article · Topics: Cross-Platform & Web
  **Published:** `27th May 2016`
  **NeKI brief:** Explains why directly porting an iOS design to Android can fail across platform conventions. Follow it for concrete cross-platform design trade-offs and platform-specific interaction reasoning.
- [speeding up the test suite](https://corner.squareup.com/2016/04/debugging-ios9-test-slowness.html) — iOS Dev Weekly · Issue 248 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `29th April 2016`
  **NeKI brief:** Examines The Corner is Square's technical blog covering software engineering, APIs, data, open source and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dan Grover](http://dangrover.com/blog/2016/04/20/bots-wont-replace-apps.html) — iOS Dev Weekly · Issue 248 — Article · Topics: Cross-Platform & Web
  **Published:** `29th April 2016`
  **NeKI brief:** So let’s say that bots are the future of apps. How would they look inside iOS if they were blessed by Apple? J.B. Chaykowsky takes a look at a possible future where AgentKit is a thing. Or, if you’re not convinced, you might agree more with Dan Grover or…
- [Presenting unanticipated errors to users](http://www.cocoawithlove.com/blog/2016/04/14/error-recovery-attempter.html) — iOS Dev Weekly · Issue 247 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Presenting errors to users is one of the trickiest things to get right in any app. Matt Gallagher follows up his previous article and this time takes a look at what to do when the user needs to be notified.
- [previous article](http://www.cocoawithlove.com/blog/2016/03/17/non-pure-errors.html) — iOS Dev Weekly · Issue 247 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Presenting errors to users is one of the trickiest things to get right in any app. Matt Gallagher follows up his previous article and this time takes a look at what to do when the user needs to be notified.
- [available on GitHub](https://github.com/fbsamples/f8app) — iOS Dev Weekly · Issue 246 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `15th April 2016`
  **NeKI brief:** Examines Source code of the official F8 app of 2017, powered by React Native and other Facebook open source projects. - fbsamples/f8app. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Google may be considering Swift for use on Android](http://thenextweb.com/dd/2016/04/07/google-facebook-uber-swift) — iOS Dev Weekly · Issue 245 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `8th April 2016`
  **NeKI brief:** Examines Sources tell The Next Web that Google is considering making Swift a “first class” language for Android, while Facebook and Uber mull their options. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [React Native for OS X](https://github.com/ptmt/react-native-desktop) — iOS Dev Weekly · Issue 244 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `1st April 2016`
  **NeKI brief:** The page covers “React Native for OS X” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Breaking Swift with reference counted structs](http://www.cocoawithlove.com/blog/2016/03/27/on-delete.html) — iOS Dev Weekly · Issue 244 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `1st April 2016`
  **NeKI brief:** Examines Matt Gallagher digs into the weeds of Swift structs and reference counting. It’s pretty obvious that you should never use some of the techniques in this article, but it makes an interesting read and you’ll definitely lea Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Creating Swift Frameworks for iOS, watchOS, and tvOS](http://basememara.com/creating-cross-platform-swift-frameworks-ios-watchos-tvos-via-carthage-cocoapods) — iOS Dev Weekly · Issue 243 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `25th March 2016`
  **NeKI brief:** Explains Creating Swift Frameworks for iOS watchOS and tvOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Dates, Done Right](http://www.markbernstein.org/Feb16/DatesDoneRight.html) — iOS Dev Weekly · Issue 238 — Article · Topics: Cross-Platform & Web
  **Published:** `19th February 2016`
  **NeKI brief:** Mark Bernstein explains how the invention of the railroad caused a date bug. Great story.
- [Your iOS app on the Play Store for just 30% of your original cost](https://myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 237 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `12th February 2016`
  **NeKI brief:** Explains Your iOS app on the Play Store for just 30% of your original cost, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [official blog](http://researchkit.org/blog.html) — iOS Dev Weekly · Issue 237 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** Examines Develop groundbreaking apps for research studies and patient care with these two open source frameworks. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Partial functions in Swift, Part 1: Avoidance](http://cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html) — iOS Dev Weekly · Issue 235 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `29th January 2016`
  **NeKI brief:** Explains Partial functions in Swift Part 1 Avoidance with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Bjango Design Resources](https://bjango.com/designresources) — iOS Dev Weekly · Issue 235 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `29th January 2016`
  **NeKI brief:** Big update to the design resources provided by Bjango this week. There’s not only an update to their Actions but also a brand new app icon template covering all of the Apple platforms (iOS, watchOS, tvOS, Mac) as well as Android, Windows and even web…
- [Actions](https://github.com/bjango/Bjango-Actions) — iOS Dev Weekly · Issue 235 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `29th January 2016`
  **NeKI brief:** Examines A collection of Photoshop actions, Photoshop scripts, Hazel rules, macOS workflows and other random things for screen designers and developers. - bjango/Bjango-Actions. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [app icon template](https://github.com/bjango/Bjango-Templates) — iOS Dev Weekly · Issue 235 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `29th January 2016`
  **NeKI brief:** Examines Big update to the design resources provided by Bjango this week. There’s not only an update to their Actions but also a brand new app icon template covering all of the Apple platforms (iOS, watchOS, tvOS, Mac) as well as Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Tips for Success on Google Play](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_ElGrEtiEXc83m1SeYu3-Q) — iOS Dev Weekly · Issue 235 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `29th January 2016`
  **NeKI brief:** Yes, you read that correctly. Don’t stop reading! It’s true that this set of videos are completely about Google Play and Android apps, but that doesn’t mean that they aren’t worth watching. Clearly you can skip the ones specifically about the Play Store, but…
- [Feature Toggles](http://martinfowler.com/articles/feature-toggles.html) — iOS Dev Weekly · Issue 234 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Testing
  **Published:** `22nd January 2016`
  **NeKI brief:** Explains Feature Toggles with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [SwiftAndroid](https://github.com/SwiftAndroid/swift/releases/tag/swiftandroid-2016-01-06) — iOS Dev Weekly · Issue 232 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `8th January 2016`
  **NeKI brief:** Will you ever be able to write Android apps in Swift? I can’t imagine this becoming super popular (just like I don’t think that iOS apps written in Java would become popular if it were possible). However it’s an interesting experiment and there may be some…
- [dynamism in Swift](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20151207/001948.html) — iOS Dev Weekly · Issue 229 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `18th December 2015`
  **NeKI brief:** The Swift Evolution mailing-list post discusses dynamism in Swift and the language-design considerations raised by the proposal.
- [Making Popovers Adapt to Size Classes](http://useyourloaf.com/blog/making-popovers-adapt-to-size-classes.html) — iOS Dev Weekly · Issue 227 — Article · Topics: Cross-Platform & Web
  **Published:** `4th December 2015`
  **NeKI brief:** Examines Size Classes might seem easy at first but there’s a load of edge cases which you’ll need to be careful with, especially around popovers. Keith Harrison has a great article here on how to cope with some of the problems yo Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Split Views and Unexpected Keyboards](http://useyourloaf.com/blog/split-views-and-unexpected-keyboards.html) — iOS Dev Weekly · Issue 226 — Article · Topics: Cross-Platform & Web · Hardware & Devices
  **Published:** `27th November 2015`
  **NeKI brief:** Examines When considering iOS split-screen multitasking it’s easy to forget some of the edge cases that your app will need to cope with. For example, what happens when the keyboard is presented from the other app when your app is Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [3D ReTouch: An Experimental Retouching App Using 3D Touch](http://flexmonkey.blogspot.co.uk/2015/10/3d-retouch-experimental-retouching-app.html) — iOS Dev Weekly · Issue 221 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `23rd October 2015`
  **NeKI brief:** Simon Gladman is back again this week with more 3D Touch experiments. This time it’s an experimental UI for retouching photos using pressure to vary the intensity of whatever retouch effect you’re currently applying. Of course, full source code is included…
- [Nobody is using App Transport Security; what’s next?](https://www.dzombak.com/blog/2015/09/Nobody-is-using-App-Transport-Security--what-s-next-.html) — iOS Dev Weekly · Issue 217 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `25th September 2015`
  **NeKI brief:** Chris Dzombak has done a bit of analysis on which popular apps have actually shipped with ATS switched on. It’s very early days, and I’m not surprised by this at all. I think this year will be our chance to opt in voluntarily before it becomes mandatory with…
- [Managing Xcode](http://pewpewthespells.com/blog/managing_xcode.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains Managing Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [guide to xcconfig files](http://pewpewthespells.com/blog/xcconfig_guide.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains The Unofficial Guide to xcconfig files with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Acorn 5’s Live Help Search](http://shapeof.com/archives/2015/8/acorn_5_search_index.html) — iOS Dev Weekly · Issue 213 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Presents Acorn 5’s Live Help Search, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [using identifiers](http://useyourloaf.com/blog/using-identifiers-to-debug-autolayout.html) — iOS Dev Weekly · Issue 212 — Article · Topics: Cross-Platform & Web · Developer Tools · Objective-C & Cocoa
  **Published:** `21st August 2015`
  **NeKI brief:** The article shows how identifiers can be used to debug Auto Layout constraints and locate the relevant views or constraints in an iOS interface.
- [tutorials](http://principleformac.com/tutorial.html) — iOS Dev Weekly · Issue 212 — Tutorial · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st August 2015`
  **NeKI brief:** This looks great. It’s a combination of a prototyping and timeline based animation tool. There’s some really nice touches though, like automatic animations between layers which have the same name on different artboards. You should check out the video on the…
- [Protocols - My Current Recommendations](http://owensd.io/2015/08/06/protocols.html) — iOS Dev Weekly · Issue 211 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `14th August 2015`
  **NeKI brief:** Explains Protocols My Current Recommendations with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Ji](https://github.com/honghaoz/Ji) — iOS Dev Weekly · Issue 210 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `7th August 2015`
  **NeKI brief:** Remember XML? 😃 You might occasionally still come across a situation where you need to parse some. Actually, it’s more likely that you’ll need to consume the odd bit of HTML these days rather than XML. Luckily, this new library by Honghao Zhang does both and…
- [iOS Build Infrastructure at Square](https://corner.squareup.com/2015/07/ios-build-infrastructure.html) — iOS Dev Weekly · Issue 209 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `31st July 2015`
  **NeKI brief:** You just hit the play button, right? 😎 Interesting article from Michael Tauraso on how Square use Jenkins and other tools to get both their App Store and internal apps built and shipped.
- [performSelector](http://owensd.io/2015/07/22/dynamic-swift.html) — iOS Dev Weekly · Issue 208 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Also, performSelector, which I didn’t expect but am happy to see! Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Address Sanitizer](https://mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) — iOS Dev Weekly · Issue 206 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `10th July 2015`
  **NeKI brief:** Explains Address Sanitizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Code spiral](http://www.pushing-pixels.org/2015/06/11/code-spiral.html) — iOS Dev Weekly · Issue 203 — Article · Topics: Code Quality · Cross-Platform & Web
  **Published:** `19th June 2015`
  **NeKI brief:** When developers are faced with a code review or pull request containing a small change it’s usually pretty easy to quickly get a handle on what’s needed. However, larger reviews can be tricky 🙈. There’s some good advice on the subject here from Kirill…
- [Add Google to your iOS Apps with CocoaPods](http://googledevelopers.blogspot.com/2015/05/add-google-to-your-ios-apps-with.html) — iOS Dev Weekly · Issue 201 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Google IO last week saw an interesting iOS announcement from Google. CocoaPods will be the preferred method for installation for all Google iOS libraries. It made the IO keynote and Google also put together a cute introduction video. Congratulations to the…
- [Change the Width of the Master View in a Split View Controller](http://useyourloaf.com/blog/2015/05/25/change-the-width-of-master-view-in-split-view-controller.html) — iOS Dev Weekly · Issue 200 — Article · Topics: Cross-Platform & Web
  **Published:** `29th May 2015`
  **NeKI brief:** The article shows how to change the master-view width in a UISplitViewController and explains the relevant iOS layout behavior.
- [Senior iOS Engineer (Twenty20 / Los Angeles, CA)](http://twenty20.theresumator.com/apply/Y6eZhv/Sr-Mobile-Software-Engineer.html) — iOS Dev Weekly · Issue 199 — Article · Topics: Cross-Platform & Web
  **Published:** `22nd May 2015`
  **NeKI brief:** Come build the next generation of stock photography in sunny Los Angeles.
- [Finally, true native iOS to Android code conversion at your fingertips](https://www.myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web
  **Published:** `8th May 2015`
  **NeKI brief:** Instantly and automatically convert your iOS source code to be a native Android app. No SDK, no re-coding, no new frameworks & languages, fully editable converted code. Sign-up and get three months free.
- [Bringing Clang to Windows](http://blogs.msdn.com/b/vcblog/archive/2015/05/01/bringing-clang-to-windows.aspx) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Examines As you may know, Visual Studio now supports building Android and iOS applications using Clang. We realize the need of our users to write cross-platform. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [video from the Build conference](http://channel9.msdn.com/events/Build/2015/3-610) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Interesting post by the Microsoft Visual C++ team on the process of compiling iOS and Android code to Windows via Clang. It’s also worth checking out this video from the Build conference if you want to learn more. Think back a few years, would you have…
- [flexbox](https://github.com/facebook/css-layout) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Objective-C & Cocoa
  **Published:** `8th May 2015`
  **NeKI brief:** Like SwiftBox, this is based on the Facebook implementation of flexbox. This time, Robert Böhnke has had a go at bringing this layout technology to Objective-C. Check out the included playground for an example of how it works.
- [compiled and simulated](http://techcrunch.com/2015/04/29/microsoft-makes-it-easier-for-developers-to-bring-their-android-and-ios-apps-to-windows-10) — iOS Dev Weekly · Issue 196 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st May 2015`
  **NeKI brief:** Explains compiled and simulated, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [A First Look at ReactiveCocoa 3.0](http://blog.scottlogic.com/2015/04/24/first-look-reactive-cocoa-3.html) — iOS Dev Weekly · Issue 195 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `24th April 2015`
  **NeKI brief:** Explains A First Look at ReactiveCocoa 3.0 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Make peace](http://www.pushing-pixels.org/2015/04/15/make-peace.html) — iOS Dev Weekly · Issue 194 — Article · Topics: Cross-Platform & Web
  **Published:** `17th April 2015`
  **NeKI brief:** Examines Make learning easier for millions of students around the world. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [iOS Charts](https://github.com/danielgindi/ios-charts) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the iOS Charts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the MPAndroidChart source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Plying Game](http://www.macworld.com/article/2905352/the-plying-game-an-inside-look-at-the-voracious-and-insatiable-world-of-app-store-reviews.html) — iOS Dev Weekly · Issue 192 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `3rd April 2015`
  **NeKI brief:** Examines Michael Simon with a look at the ups and downs (OK, mainly downs) of the rating and review system on the App Store. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [SSL MiTM attack in AFNetworking 2.5.1](http://blog.mindedsecurity.com/2015/03/ssl-mitm-attack-in-afnetworking-251-do.html) — iOS Dev Weekly · Issue 191 — Article · Topics: Cross-Platform & Web · Networking · Security & Privacy
  **Published:** `27th March 2015`
  **NeKI brief:** This security advisory describes an SSL man-in-the-middle issue affecting AFNetworking 2.5.1 and points to the 2.5.2 fix. It is valuable historical dependency-risk context for checking networking-library versions and responding quickly to security releases.
- [available publicly](https://github.com/facebook/react-native) — iOS Dev Weekly · Issue 191 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the available publicly source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [an overview](http://blog.scottlogic.com/2015/03/26/react-native-retrospective.html) — iOS Dev Weekly · Issue 191 — Tutorial · Topics: Cross-Platform & Web
  **Published:** `27th March 2015`
  **NeKI brief:** This retrospective evaluates React Native from an early-access perspective, combining an overview of the development model with practical observations from using the beta. It is useful for comparing cross-platform trade-offs against native iOS implementation choices.
- [a tutorial](http://www.raywenderlich.com/99473/introducing-react-native-building-apps-javascript) — iOS Dev Weekly · Issue 191 — Tutorial · Topics: Cross-Platform & Web
  **Published:** `27th March 2015`
  **NeKI brief:** Examines In this React Native tutorial you’ll learn how to build native iOS and Android apps based on the hugely popular React JavaScript library. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Implementing React.js in Swift](http://blog.scottlogic.com/2015/03/05/reactjs-in-swift.html) — iOS Dev Weekly · Issue 188 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Explains Implementing React.js in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [SwiftMoment](https://github.com/akosma/SwiftMoment) — iOS Dev Weekly · Issue 186 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th February 2015`
  **NeKI brief:** Provides the SwiftMoment source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Updating to the iOS 8 Search Controller](http://useyourloaf.com/blog/2015/02/16/updating-to-the-ios-8-search-controller.html) — iOS Dev Weekly · Issue 186 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `20th February 2015`
  **NeKI brief:** Explains how to update an iOS 8 search controller. Follow it for concrete UIKit search and presentation patterns, while verifying lifecycle details against current APIs.
- [Silver](http://elementscompiler.com/elements/silver) — iOS Dev Weekly · Issue 185 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `13th February 2015`
  **NeKI brief:** Discusses Silver, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [First Impressions using React Native](http://jlongster.com/First-Impressions-using-React-Native) — iOS Dev Weekly · Issue 185 — Article · Topics: Cross-Platform & Web
  **Published:** `13th February 2015`
  **NeKI brief:** The page is an archived first-impressions article about using React Native, describing the author's early experience and implementation observations.
- [SwiftBox](https://github.com/joshaber/SwiftBox) — iOS Dev Weekly · Issue 185 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `13th February 2015`
  **NeKI brief:** Like SwiftBox, this is based on the Facebook implementation of flexbox. This time, Robert Böhnke has had a go at bringing this layout technology to Objective-C. Check out the included playground for an example of how it works.
- [thoughts](http://khanlou.com/2015/02/layout-abstractions) — iOS Dev Weekly · Issue 185 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `13th February 2015`
  **NeKI brief:** SwiftBox from Josh Abernathy is a wrapper around Facebook’s css-layout library which provides a box model for laying out views. The syntax looks pretty clean and there’s a sample project too. Speaking of layout abstraction it’s also worth reading Soroush…
- [whole host](http://download.revealapp.com/Reveal.app-1.5.0-releasenotes.html) — iOS Dev Weekly · Issue 184 — Article · Topics: Cross-Platform & Web
  **Published:** `6th February 2015`
  **NeKI brief:** This week saw a significant new version of Reveal (which made it into my “Best of Tools” issue of iOS Dev Weekly recently). The biggest new feature is inspection (and editing) of Auto Layout constraints but there’s a whole host of other features and…
- [Introducing React Native](https://m.youtube.com/watch?v=KVZ-P-ZI6W4) — iOS Dev Weekly · Issue 183 — Video · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `30th January 2015`
  **NeKI brief:** Examines Tom Occhino reviews the past and present of React in 2015, and teases where it's going next. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [TIOBE](http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html) — iOS Dev Weekly · Issue 181 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `16th January 2015`
  **NeKI brief:** Explains TIOBE with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [A better App Store Pricing Matrix](http://www.equinux.com/us/appdevelopers/pricematrix.html) — iOS Dev Weekly · Issue 181 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Product Design
  **Published:** `16th January 2015`
  **NeKI brief:** The page presents an App Store pricing matrix for developers and explains the price-point structure used when setting application prices.
- [Debugging: A Case Study](http://www.objc.io/issue-19/debugging-case-study.html) — iOS Dev Weekly · Issue 176 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Debugging A Case Study with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Pcalc](http://www.pcalc.com/english/whatsnew.html) — iOS Dev Weekly · Issue 174 — Article · Topics: Cross-Platform & Web
  **Published:** `28th November 2014`
  **NeKI brief:** Examines Gabriel Theodoropoulos with a thorough post on building an app which takes advantage of Handoff. I’ve been loving the integration built into the standard iOS 8 and Yosemite apps but the only apps I’ve come across taking Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [open source the .NET framework](http://tirania.org/blog/archive/2014/Nov-12.html) — iOS Dev Weekly · Issue 172 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `14th November 2014`
  **NeKI brief:** Examines Miguel de Icaza. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Finally, true native iOS to Android code conversion at your fingertips](http://www.myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 171 — Article · Topics: Cross-Platform & Web
  **Published:** `7th November 2014`
  **NeKI brief:** Instantly and automatically convert your iOS source code to be a native Android app. No SDK, no re-coding, no new frameworks & languages, fully editable converted code. Sign-up and get three months free.
- [Continuous Integration With Xcode Server](http://useyourloaf.com/blog/2014/11/02/continuous-integration-with-xcode-server.html) — iOS Dev Weekly · Issue 171 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Xcode
  **Published:** `7th November 2014`
  **NeKI brief:** A historical Xcode Server CI setup guide showing how bots, integrations, and signing fit together. It is useful for understanding the pre-Xcode-Cloud workflow and its operational constraints.
- [Senior iOS Developer at EveryMove - Seattle](http://everymove.theresumator.com/apply/QiAmVO/Mobile-Developer-Native-IOS.html?source=iOS+Dev+Weekly) — iOS Dev Weekly · Issue 166 — Article · Topics: Cross-Platform & Web
  **Published:** `3rd October 2014`
  **NeKI brief:** This page advertises a senior native iOS developer role at EveryMove. It is recruitment material rather than technical reading and should normally be excluded from the knowledge index.
- [Jonathon Mah’s recent post](http://devetc.org/code/2014/07/07/auto-layout-and-views-that-wrap.html) — iOS Dev Weekly · Issue 161 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `29th August 2014`
  **NeKI brief:** This article works through Auto Layout for views whose content wraps and changes intrinsic height. It provides a concrete UIKit layout pattern for combining constraints with dynamic text without hard-coding the final view dimensions.
- [Self Sizing Table View Cells](http://useyourloaf.com/blog/2014/08/07/self-sizing-table-view-cells.html) — iOS Dev Weekly · Issue 158 — Article · Topics: Cross-Platform & Web
  **Published:** `8th August 2014`
  **NeKI brief:** Examines Last updated: Jun 12, 2020 It only took five years but this is much easier to do with Interface Builder in Xcode 11. See Self Sizing Table View Cells in Interface Builder Dynamic T. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Bringing Google’s Authentic Motion to iOS](http://holko.pl//2014/07/09/authentic-motion-ios) — iOS Dev Weekly · Issue 154 — Article · Topics: Cross-Platform & Web
  **Published:** `11th July 2014`
  **NeKI brief:** Shows how to recreate Google’s Authentic Motion effect on iOS. Follow it for concrete motion, animation, and interaction techniques, while verifying framework behavior against current UIKit and Core Animation APIs.
- [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) — iOS Dev Weekly · Issue 153 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `4th July 2014`
  **NeKI brief:** Examines Custom UIButton effect inspired by Google Material Design - zoonooz/ZFRippleButton. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [There is no later for your customers](http://bokardo.com/archives/later) — iOS Dev Weekly · Issue 153 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `4th July 2014`
  **NeKI brief:** Examines The web development mantra of “Ship early and ship often” is something that iOS & Mac developers have not been particularly quick to adopt but with automatic app updates now being taken for granted, review times which ar Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Google Design](http://www.google.com/design) — iOS Dev Weekly · Issue 152 — Article · Topics: Cross-Platform & Web
  **Published:** `27th June 2014`
  **NeKI brief:** Discusses Google Design, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Friday Q&A: Interesting Swift Features](https://mikeash.com/pyblog/friday-qa-2014-06-20-interesting-swift-features.html) — iOS Dev Weekly · Issue 152 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `27th June 2014`
  **NeKI brief:** Explains Friday Q A Interesting Swift Features with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [How Apple Cheats](http://marksands.github.io/2014/05/27/how-apple-cheats.html) — iOS Dev Weekly · Issue 148 — Article · Topics: Cross-Platform & Web · Developer Tools · Security & Privacy
  **Published:** `30th May 2014`
  **NeKI brief:** Examines It should be blindingly obvious, and expected, that Apple don’t play by the same rules that we have to (for example, sandboxing and all of their Mac apps) but I did like Mark Sands’ investigation into how iBooks & iTunes Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Mobile Designer at MailChimp](http://mailchimp.theresumator.com/apply/4Jnpzz/DesignerMobile-Apps-Team.html) — iOS Dev Weekly · Issue 146 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `16th May 2014`
  **NeKI brief:** Explains Mobile Designer at MailChimp with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Running Custom Clang Analyzer Builds](http://useyourloaf.com/blog/2014/04/16/running-custom-clang-analyzer-builds.html) — iOS Dev Weekly · Issue 142 — Article · Topics: Cross-Platform & Web · Personal Essays
  **Published:** `18th April 2014`
  **NeKI brief:** Explains Running Custom Clang Analyzer Builds with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Senior iOS Developer - Engineer Apps You’ll Love](http://raizlabs.theresumator.com/apply/ApvQjq/Senior-Mobile-Developer-IPhone-And-Android.html) — iOS Dev Weekly · Issue 140 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `4th April 2014`
  **NeKI brief:** Examines Trying to apply for a job? JazzHR is an applicant tracking system (ATS) used by businesses to organize hiring — not a job board. Here's how to find the roles you're looki. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Effective Objective-C 2.0](http://useyourloaf.com/blog/2014/03/19/effective-objective-c-2-dot-0.html) — iOS Dev Weekly · Issue 139 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `28th March 2014`
  **NeKI brief:** The article explains effective Objective-C 2.0 techniques and practical language and API usage guidance for iOS developers.
- [Quick Look on UIViews](http://useyourloaf.com/blog/2014/03/12/xcode-debugger-quick-look.html) — iOS Dev Weekly · Issue 137 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th March 2014`
  **NeKI brief:** Explains Quick Look on UIViews with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [8 Tips for working effectively with Interface Builder](http://codesheriff.blogspot.co.il/2014/03/8-tips-for-working-effectively-with.html) — iOS Dev Weekly · Issue 137 — Article · Topics: Cross-Platform & Web
  **Published:** `14th March 2014`
  **NeKI brief:** This article collects practical Interface Builder techniques for keeping storyboard and nib-based layouts manageable. It is useful for UIKit teams that want to reduce friction in visual editing, constraints, reusable components, and day-to-day Xcode interface work.
- [Where Apple design is headed in 2014](http://www.macworld.com/article/2104064/where-apple-design-is-headed-in-2014.html) — iOS Dev Weekly · Issue 136 — Article · Topics: Cross-Platform & Web
  **Published:** `7th March 2014`
  **NeKI brief:** iOS 7 may still feel shiny and new but it’s easy to forget that we only have a few months until we get a peek at what’s coming next. Dave Wiskus takes a look at possible directions for iOS 8 and OS X 10.10 (or OS XI?) and speculates on possible directions. I…
- [everyone makes mistakes](http://www.pushing-pixels.org/2014/02/24/living-in-a-stone-age.html) — iOS Dev Weekly · Issue 135 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `28th February 2014`
  **NeKI brief:** The truth is that security is hard, everyone makes mistakes and new challenges appear every day but I do believe that Apple have user’s best interests at heart and I wouldn’t be on any other mobile platform, despite this week.
- [Apple scoops up Burstly, owner of TestFlight](http://www.macworld.com/article/2099906/apple-scoops-up-burstly-owner-of-testflight-beta-testing-platform.html) — iOS Dev Weekly · Issue 135 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Testing
  **Published:** `28th February 2014`
  **NeKI brief:** The Macworld article reports Apple's acquisition of Burstly, the company behind the TestFlight beta-testing platform.
- [Learn by Doing with Code School](https://www.codeschool.com/paths/ios) — iOS Dev Weekly · Issue 134 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `21st February 2014`
  **NeKI brief:** Explains Learn by Doing with Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why Indie Developers Go Insane](http://jeff-vogel.blogspot.co.uk/2014/02/why-indie-developers-go-insane.html) — iOS Dev Weekly · Issue 133 — Article · Topics: Cross-Platform & Web
  **Published:** `14th February 2014`
  **NeKI brief:** Examines The Bottom Feeder: Why Indie Developers Go Insane. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [NSString and Unicode](http://www.objc.io/issue-9/unicode.html) — iOS Dev Weekly · Issue 133 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `14th February 2014`
  **NeKI brief:** Explains NSString and Unicode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Introduction to libclang](https://mikeash.com/pyblog/friday-qa-2014-01-24-introduction-to-libclang.html) — iOS Dev Weekly · Issue 131 — Article · Topics: Cross-Platform & Web
  **Published:** `31st January 2014`
  **NeKI brief:** The Friday Q&A article introduces libclang and explains how developers can use Clang's parsing interfaces from tooling code.
- [Cocos2D V3 - Release Candidate 1](http://www.cocos2d-iphone.org/cocos2d-v3-rc1-release) — iOS Dev Weekly · Issue 130 — Article · Topics: Cross-Platform & Web
  **Published:** `24th January 2014`
  **NeKI brief:** The release post announces Cocos2D version 3 release candidate 1 and describes the changes for iOS game developers.
- [objClean](http://objclean.com/blog.html) — iOS Dev Weekly · Issue 130 — Article · Topics: Cross-Platform & Web
  **Published:** `24th January 2014`
  **NeKI brief:** Examines ���ơ����� (kaiyun)�ٷ���վ_kaiyun sport��������26���Ƽ� ����ơ�[���ղ�����������tiyu1818.com��tiyu1819.com]��ʼ��1988�� (2005��2���ڸ۽�������) ��ԭ����ʡ��ҵ�ܹ�˾�����ϸ���������ԭΪ����ʡ�������. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Tips on Designing Sounds for iOS Apps](http://raisedbeaches.com/octave/tips.html) — iOS Dev Weekly · Issue 129 — Article · Topics: Cross-Platform & Web
  **Published:** `17th January 2014`
  **NeKI brief:** Explains Tips on Designing Sounds for iOS Apps, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Software in 2014](https://www.tbray.org/ongoing/When/201x/2014/01/01/Software-in-2014) — iOS Dev Weekly · Issue 128 — Article · Topics: Cross-Platform & Web
  **Published:** `10th January 2014`
  **NeKI brief:** Presents Software in 2014, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Synthesized Speech From Text](http://useyourloaf.com/blog/2014/01/08/synthesized-speech-from-text.html) — iOS Dev Weekly · Issue 128 — Article · Topics: Cross-Platform & Web
  **Published:** `10th January 2014`
  **NeKI brief:** Keith Harrison with a great rundown of the text to speech APIs in iOS 7. I hadn’t really thought about it before but naturally this is multi-lingual as well, what a fantastic resource to have available to us as developers.
- [My “Doom” 20th Anniversary Stories](http://blog.wilshipley.com/2013/12/my-doom-20th-anniversary-stories.html?m=1) — iOS Dev Weekly · Issue 125 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `20th December 2013`
  **NeKI brief:** Dan Counsell with an excellent article on optimising your app store listing for search and discoverability. This is a tricky subject which attracts lots of misinformation but Dan cuts through it all to give a clear and sensible set of tips on getting your…
- [Podlife](http://davander.com/podlife.html) — iOS Dev Weekly · Issue 121 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains Podlife with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Build Process](http://www.objc.io/issue-6/build-process.html) — iOS Dev Weekly · Issue 120 — Article · Topics: Cross-Platform & Web · Testing · Xcode
  **Published:** `15th November 2013`
  **NeKI brief:** Explains The Build Process with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Demonstrates compiling an Objective-C iOS game for Android with Apportable and SpriteBuilder, including platform-framework mapping. Treat it as historical cross-platform tooling context rather than a current deployment recommendation.
- [iMessage Privacy](http://blog.quarkslab.com/imessage-privacy.html) — iOS Dev Weekly · Issue 116 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `18th October 2013`
  **NeKI brief:** This very clear explanation of the security and internals of iMessage made for some interesting reading this week. The biggest surprise here is that iMessage transmits your actual password (over HTTPS, naturally) but I also found the discussion of the other…
- [Friday Q&A: Why Registers Are Fast and RAM Is Slow](http://www.mikeash.com/pyblog/friday-qa-2013-10-11-why-registers-are-fast-and-ram-is-slow.html) — iOS Dev Weekly · Issue 116 — Article · Topics: Cross-Platform & Web
  **Published:** `18th October 2013`
  **NeKI brief:** Registers, caches, and RAM have radically different latency and bandwidth characteristics, so data locality shapes performance more than isolated instruction counts. This helps interpret profiling results.
- [Handlebars for Objective-C](https://github.com/fotonauts/handlebars-objc) — iOS Dev Weekly · Issue 116 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th October 2013`
  **NeKI brief:** Provides the Handlebars for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [An Interesting iOS App Store Upgrade Example](http://www.macdrifter.com/2013/10/an-interesting-ios-app-store-upgrade-example.html) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `18th October 2013`
  **NeKI brief:** Examines An Interesting iOS App Store Upgrade Example - Macdrifter. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Non-pointer isa](http://www.sealiesoftware.com/blog/archive/2013/09/24/objc_explain_Non-pointer_isa.html) — iOS Dev Weekly · Issue 113 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `27th September 2013`
  **NeKI brief:** Explains Non-pointer isa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLDB-QuickLook](https://github.com/ryanolsonk/LLDB-QuickLook) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the LLDB-QuickLook source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Most Forward Thinking Apple Yet](http://cannyvision.com/2013/09/12/the-most-forward-thinking-apple-yet.html) — iOS Dev Weekly · Issue 112 — Article · Topics: Cross-Platform & Web
  **Published:** `20th September 2013`
  **NeKI brief:** Examines I liked this analysis of the move to 64 bit ARM by Sisir Koppaka. I am still holding out for an Apple TV SDK and it certainly has the potential to be a platform which could put a significant amount of memory (> 4Gb) to u Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [IGHTMLQuery](https://github.com/siuying/IGHTMLQuery) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the IGHTMLQuery source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Callbacks as our Generations’ Go To Statement](http://tirania.org/blog/archive/2013/Aug-15.html) — iOS Dev Weekly · Issue 107 — Article · Topics: Concurrency · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th August 2013`
  **NeKI brief:** Explains Callbacks as our Generations’ Go To Statement with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Sword & Sworcery Sales Infographic](http://www.swordandsworcery.com/news/2013/7/26/sworcery-sales-infographic.html) — iOS Dev Weekly · Issue 105 — Article · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `2nd August 2013`
  **NeKI brief:** Nathan Vella takes an in depth look at the sales figures from Sword & Sworcery across multiple platforms, not just iOS. It’s amazing to see the iOS sales stack up so high even against things like multiple Humble Bundle deals, especially in terms of revenue.
- [Why mobile web apps are slow](http://sealedabstract.com/rants/why-mobile-web-apps-are-slow) — iOS Dev Weekly · Issue 102 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Performance
  **Published:** `12th July 2013`
  **NeKI brief:** The article analyzes performance problems in mobile web applications and explains the technical reasons users experience them as slow.
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
- [Everything you need to know about OS X Mavericks](http://www.macworld.com/article/2041581/faq-everything-you-need-to-know-about-os-x-mavericks.html) — iOS Dev Weekly · Issue 98 — Article · Topics: Cross-Platform & Web
  **Published:** `14th June 2013`
  **NeKI brief:** With all of the iOS 7 talk, it’s easy to forget that we also had an announcement of a major new version of Mac OS this week as well.
- [State Preservation and Restoration](http://useyourloaf.com/blog/2013/05/21/state-preservation-and-restoration.html) — iOS Dev Weekly · Issue 95 — Article · Topics: Cross-Platform & Web
  **Published:** `24th May 2013`
  **NeKI brief:** Keith Harrison on implementing the state restoration features that were introduced with iOS 6. I (like most people, I think) am guilty of largely ignoring this problem but with these APIs there really is much less of an excuse for that. Keith has also…
- [Starters Guide to iOS Design](http://taybenlor.com/2013/05/21/designing-for-ios.html) — iOS Dev Weekly · Issue 95 — Article · Topics: Cross-Platform & Web
  **Published:** `24th May 2013`
  **NeKI brief:** Examines As someone who does work on both the development and design side of iOS apps I find that many designers struggle with the transition to UI work, or with the different processes inv. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple’s new Objective-C to Javascript Bridge](http://www.steamclock.com/blog/2013/05/apple-objective-c-javascript-bridge) — iOS Dev Weekly · Issue 94 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `17th May 2013`
  **NeKI brief:** Explains Apple’s new Objective-C to Javascript Bridge with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Proper Use of Asserts](http://www.mikeash.com/pyblog/friday-qa-2013-05-03-proper-use-of-asserts.html) — iOS Dev Weekly · Issue 93 — Article · Topics: Cross-Platform & Web
  **Published:** `10th May 2013`
  **NeKI brief:** Assertions document programmer invariants and fail early in development, while recoverable user or network errors need normal control flow. The article helps keep diagnostic checks from becoming production error handling.
- [We Need A Standard Layered Image Format](http://shapeof.com/archives/2013/4/we_need_a_standard_layered_image_format.html) — iOS Dev Weekly · Issue 92 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `3rd May 2013`
  **NeKI brief:** Explains We Need A Standard Layered Image Format with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Capture a Signature on iOS](http://www.nearinfinity.com/blogs/jason_harwig/2012/11/06/capture-a-signature-on-ios.html) — iOS Dev Weekly · Issue 90 — Article · Topics: Cross-Platform & Web
  **Published:** `19th April 2013`
  **NeKI brief:** Examines Near Infinity. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [StringScore](https://github.com/thetron/StringScore) — iOS Dev Weekly · Issue 90 — Source repository · Topics: Developer Tools
  **Published:** `19th April 2013`
  **NeKI brief:** Examines StringScore is an Objective-C library which provides super fast fuzzy string matching/scoring. Based on the JavaScript library of the same name. - thetron/StringScore. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building Facebook Home with Quartz Composer](http://vimeo.com/user5164093/videos) — iOS Dev Weekly · Issue 90 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `19th April 2013`
  **NeKI brief:** Facebook Home is obviously it is only available on Android but something interesting came out in the media coverage of the recent launch, prototypes of Home were created in Quartz Composer. David O Brien has put together a great set of video tutorials…
- [A $5 app isn’t expensive](http://www.macworld.com/article/2032847/a-5-app-isnt-expensive-customers-need-to-help-fix-the-app-store-economy.html) — iOS Dev Weekly · Issue 89 — Article · Topics: Cross-Platform & Web
  **Published:** `12th April 2013`
  **NeKI brief:** Echoing last weeks sentiment by Jury, this article by Lex Friedman also argues that we should be raising our prices. I couldn’t agree more.
- [Learn the ropes of Mobile Services with Brent Simmons](http://www.windowsazure.com/en-us/develop/mobile/ios?WT.mc_id=azuregb_us_display_mirluna_2) — iOS Dev Weekly · Issue 87 — Article · Topics: App Services & Extensions
  **Published:** `29th March 2013`
  **NeKI brief:** Explains Learn the ropes of Mobile Services with Brent Simmons with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [Befriending Apple](http://kevinhoctor.blogspot.co.uk/2013/03/befriending-apple.html) — iOS Dev Weekly · Issue 85 — Article · Topics: Cross-Platform & Web
  **Published:** `15th March 2013`
  **NeKI brief:** The post discusses the author's relationship with Apple's platform and provides a publicly readable perspective on Apple development.
- [Xcode 4.6 Recommended Build Settings](http://useyourloaf.com/blog/2013/03/03/xcode-4-dot-6-recommended-build-settings.html) — iOS Dev Weekly · Issue 84 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `8th March 2013`
  **NeKI brief:** Explains Xcode 4.6 Recommended Build Settings with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple Rejecting Apps Using Cookie-Tracking Methods](http://techcrunch.com/2013/02/25/apple-rejecting-apps-using-cookie-tracking-methods-signaling-push-to-its-own-ad-identifier-technology-is-now-underway) — iOS Dev Weekly · Issue 83 — Article · Topics: Cross-Platform & Web
  **Published:** `1st March 2013`
  **NeKI brief:** Reports Apple’s rejection of apps using cookie-based tracking methods during the shift toward its own advertising identifier. Follow it for concrete privacy and review-policy history.
- [Friday Q&A 2013-02-22: Let’s Build UITableView](http://www.mikeash.com/pyblog/friday-qa-2013-02-22-lets-build-uitableview.html) — iOS Dev Weekly · Issue 83 — Article · Topics: Cross-Platform & Web
  **Published:** `1st March 2013`
  **NeKI brief:** Matthew Elton takes the reins for the Friday Q&A this week with a look at implementing UITableView from scratch. The sample code provided has options to toggle the cell reuse optimisation which gives a glimpse of how life could have been without the reuse…
- [TimesSquare: a calendar view for iOS and Android apps](http://corner.squareup.com/2013/01/times-square.html) — iOS Dev Weekly · Issue 79 — Article · Topics: Cross-Platform & Web
  **Published:** `1st February 2013`
  **NeKI brief:** Examines I have never been a big fan of UIDatePicker on iOS, sure it’s functional but I think people prefer to pick dates with a calendar view style control. If you agree then you might be interested in this new control from Squa Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The Case Against Xcode Plugins](http://www.edgecasesshow.com/032-the-case-against-xcode-plugins.html) — iOS Dev Weekly · Issue 77 — Podcast · Topics: Cross-Platform & Web · Developer Community & Business · Xcode
  **Published:** `18th January 2013`
  **NeKI brief:** Explains The Case Against Xcode Plugins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Halving size of iPad app with ImageOptim+ImageAlpha](http://imageoptim.com/tweetbot.html) — iOS Dev Weekly · Issue 76 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `11th January 2013`
  **NeKI brief:** Explains Halving size of iPad app with ImageOptim+ImageAlpha with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Friday Q&A: Objective-C Pitfalls](http://www.mikeash.com/pyblog/friday-qa-2012-12-14-objective-c-pitfalls.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st December 2012`
  **NeKI brief:** Objective-C pitfalls often arise from dynamic dispatch, nil messaging, ownership conventions, and type erasure interacting unexpectedly. The review is useful for locating boundaries where static Swift assumptions do not apply.
- [Making Crisp Retina Icons for your App](http://gigliwood.com/blog/making-crisp-retina-icons.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web
  **Published:** `21st December 2012`
  **NeKI brief:** The article explains techniques for making crisp Retina icons and preparing high-resolution app assets.
- [My Sales & Experience in the Education App Market - 2012 Report](http://blog.lescapadou.com/2012/12/my-sales-experience-in-education-app.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Performance
  **Published:** `21st December 2012`
  **NeKI brief:** Examines This detailed report from L’Escapadou on their performance over the past year selling educational apps on iOS. There are some good nuggets of information in there we can all use as well and it’s always nice to hear about Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Introducing CMUnistrokeGestureRecognizer](http://blog.chrismiles.info/2012/12/introducing-cmunistrokegesturerecognizer.html) — iOS Dev Weekly · Issue 72 — Article · Topics: Cross-Platform & Web
  **Published:** `14th December 2012`
  **NeKI brief:** Chris Miles with a port of the $1 Unistroke Recogniser completely encapsulated in a UIGestureRecognizer. Easy to use too, all that is needed is a path with the shape you want to recognise passed to the recogniser. The demo works really well and when I looked…
- [Let’s Build objc_msgSend](http://www.mikeash.com/pyblog/friday-qa-2012-11-16-lets-build-objc_msgsend.html) — iOS Dev Weekly · Issue 69 — Article · Topics: Cross-Platform & Web
  **Published:** `23rd November 2012`
  **NeKI brief:** Rebuilding objc_msgSend exposes selector lookup, receiver dispatch, and calling-convention constraints at the Objective-C runtime boundary. The experiment explains why dynamic messaging cannot be replaced with an arbitrary function pointer.
- [Blake’s iOS Device Specification Grid](http://blakespot.com/ios_device_specifications_grid.html) — iOS Dev Weekly · Issue 67 — Article · Topics: Cross-Platform & Web
  **Published:** `9th November 2012`
  **NeKI brief:** Provides a dense comparison table of Apple device identifiers, SoCs, memory, CPU and GPU details, screen metrics, connectors, and supported OS versions. Useful for compatibility matrices and device-specific testing decisions, with dates checked before relying on values.
- [My 2012 Compatibility Lab](http://david-smith.org/blog/2012/11/07/my-2012-compatibility-lab) — iOS Dev Weekly · Issue 67 — Article · Topics: Cross-Platform & Web
  **Published:** `9th November 2012`
  **NeKI brief:** Presents My 2012 Compatibility Lab, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Spicy with Beans](http://kevinhoctor.blogspot.co.uk/2012/11/spicy-with-beans.html) — iOS Dev Weekly · Issue 66 — Article · Topics: Cross-Platform & Web
  **Published:** `2nd November 2012`
  **NeKI brief:** Kevin Hoctor with some good advice on marketing or making real Texan chilli, I’m not entirely sure which.
- [Chaos Testing With UI AutoMonkey](http://cocoamanifest.net/articles/2012/11/chaos-testing-with-ui-automonkey.html) — iOS Dev Weekly · Issue 66 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains Chaos Testing With UI AutoMonkey with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Developers stymied by Mac App Store approval delays](http://www.macworld.com/article/2011430/developers-stymied-by-mac-app-store-approval-delays.html) — iOS Dev Weekly · Issue 63 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `12th October 2012`
  **NeKI brief:** So we hit the news a little this week with several stories about the steadily increasing Mac App Store review times triggered by data from our review times site. I have always been a defender of the App Store review processes and so I am really sad to see…
- [Implementing Smart App Banners](http://david-smith.org/blog/2012/09/20/implementing-smart-app-banners) — iOS Dev Weekly · Issue 61 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `28th September 2012`
  **NeKI brief:** Explains Implementing Smart App Banners with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Remote Packet Capture for iOS devices](http://useyourloaf.com/blog/2012/02/07/remote-packet-capture-for-ios-devices.html) — iOS Dev Weekly · Issue 60 — Article · Topics: Cross-Platform & Web · Developer Tools · Networking
  **Published:** `21st September 2012`
  **NeKI brief:** Examines Continuing the networking theme Keith Harrison on examining network data from a real device on your Mac using a remote virtual interface rather than a proxy. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Beware of the Sorrell: Gambling For Kids: A How To Guide](http://www.bewareofthesorrell.com/2012/09/gambling-for-kids-how-to-guide.html) — iOS Dev Weekly · Issue 59 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `14th September 2012`
  **NeKI brief:** Examines It’s easy to think that the questionable tactic of targeting digital goods and In-App purchases at kids is a new phenomenon but Mark Sorrell reminds us that this has been going on for a long time and that maybe what we n Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The White House App released as Open Sorce](https://github.com/WhiteHouse/wh-app-ios) — iOS Dev Weekly · Issue 58 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `7th September 2012`
  **NeKI brief:** Provides the The White House App released as Open Sorce source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PonyDebugger: Remote Debugging Tools for Native iOS Apps](http://corner.squareup.com/2012/08/ponydebugger-remote-debugging.html) — iOS Dev Weekly · Issue 57 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `31st August 2012`
  **NeKI brief:** Explains PonyDebugger Remote Debugging Tools for Native iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Stop Xcode Automatic Termination](http://useyourloaf.com/blog/2012/08/13/xcode-automatic-termination.html) — iOS Dev Weekly · Issue 55 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `17th August 2012`
  **NeKI brief:** Explains Stop Xcode Automatic Termination with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [A Tour of CommonCrypto](http://www.mikeash.com/pyblog/friday-qa-2012-08-10-a-tour-of-commoncrypto.html) — iOS Dev Weekly · Issue 55 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `17th August 2012`
  **NeKI brief:** The Friday Q&A article gives a technical tour of Apple's CommonCrypto APIs and explains their use from application code.
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
- [iOS 6 WWDC Keynote Updates](http://useyourloaf.com/blog/2012/06/11/ios-6-wwdc-keynote-updates.html) — iOS Dev Weekly · Issue 46 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `15th June 2012`
  **NeKI brief:** Examines A great, non NDA breaking round up of some of what we can talk about in iOS 6 by Keith Harrison. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [My Top 5 Factors for iOS Contracting Success](http://www.escortmissions.com/blog/2012/6/10/my-top-5-factors-for-ios-contracting-success.html) — iOS Dev Weekly · Issue 46 — Article · Topics: Concurrency · Cross-Platform & Web · Developer Career & Practice
  **Published:** `15th June 2012`
  **NeKI brief:** Examines A solid list of tips for those of you just starting out as independent or freelance developers from Carl Brown although I would say that any developer should be doing most of these. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Sizes of iPhone UI Elements](http://www.idev101.com/code/User_Interface/sizes.html) — iOS Dev Weekly · Issue 43 — Article · Topics: Cross-Platform & Web
  **Published:** `25th May 2012`
  **NeKI brief:** Useful reference from iDev 101 with all of the standard sizes for iOS UI elements, one to bookmark.
- [Shell Apps and Silver Bullets](http://sandofsky.com/blog/shell-apps.html) — iOS Dev Weekly · Issue 41 — Article · Topics: Cross-Platform & Web
  **Published:** `11th May 2012`
  **NeKI brief:** Explains Shell Apps and Silver Bullets with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS 5.1 Upgrade Stats](http://david-smith.org/blog/2012/03/10/ios-5-dot-1-upgrade-stats/index.html) — iOS Dev Weekly · Issue 39 — Article · Topics: Cross-Platform & Web
  **Published:** `27th April 2012`
  **NeKI brief:** Examines iOS 5.1 Upgrade Stats - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Friday Q&A: Nib Memory Management](http://mikeash.com/pyblog/friday-qa-2012-04-13-nib-memory-management.html) — iOS Dev Weekly · Issue 38 — Article · Topics: Cross-Platform & Web · Developer Career & Practice
  **Published:** `20th April 2012`
  **NeKI brief:** Explains Friday Q A Nib Memory Management with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple is allowed to intervene in Lodsys lawsuit against app developers](http://www.fosspatents.com/2012/04/apple-is-allowed-at-long-last-to.html) — iOS Dev Weekly · Issue 37 — Article · Topics: Cross-Platform & Web
  **Published:** `13th April 2012`
  **NeKI brief:** Examines It has been a long time since there has been any kind of news on the Lodsys cases but this has to be a step in the right direction for those developers who are still dealing with it. Good news. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Introducing PLWeakCompatibility](http://www.mikeash.com/pyblog/introducing-plweakcompatibility.html) — iOS Dev Weekly · Issue 36 — Article · Topics: Cross-Platform & Web
  **Published:** `6th April 2012`
  **NeKI brief:** PLWeakCompatibility backports weak-reference behavior for runtimes without native support, relying on runtime hooks and careful lifecycle handling. It is valuable historical context for mixed deployment targets and compatibility shims.
- [Papermill - The first few weeks](http://www.papermill.me/firstweeks) — iOS Dev Weekly · Issue 36 — Article · Topics: Cross-Platform & Web
  **Published:** `6th April 2012`
  **NeKI brief:** Ryan Bateman with a detailed write up of the first few weeks of his Android Instapaper client, Papermill.
- [Paid Upgrades and the Mac App Store](http://www.mentalfaculty.com/mentalfaculty/Blog/Entries/2012/3/28_Paid_Upgrades_and_the_Mac_App_Store.html) — iOS Dev Weekly · Issue 35 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `30th March 2012`
  **NeKI brief:** The page covers “Paid Upgrades and the Mac App Store” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sir Jonathan Ive: The iMan cometh](http://www.thisislondon.co.uk/lifestyle/london-life/sir-jonathan-ive-the-iman-cometh-7562170.html) — iOS Dev Weekly · Issue 33 — Article · Topics: Cross-Platform & Web · Product Design
  **Published:** `16th March 2012`
  **NeKI brief:** Examines This is London magazine has been established for over 65 years, providing readers with information about events, exhibitions, music, concerts, theatre and dining. As life returns t. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Let’s Build NSMutableArray](http://www.mikeash.com/pyblog/friday-qa-2012-03-09-lets-build-nsmutablearray.html) — iOS Dev Weekly · Issue 33 — Article · Topics: Cross-Platform & Web
  **Published:** `16th March 2012`
  **NeKI brief:** Presents Let’s Build NSMutableArray, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Key-Value Observing Done Right: Take 2](http://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — iOS Dev Weekly · Issue 32 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th March 2012`
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Git branch management with Xcode](http://useyourloaf.com/blog/2012/2/29/git-branch-management-with-xcode.html) — iOS Dev Weekly · Issue 31 — Article · Topics: Developer Career & Practice · Developer Tools · Xcode
  **Published:** `2nd March 2012`
  **NeKI brief:** Explains Git branch management with Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Path uploads your entire iPhone address book to its servers](http://mclov.in/2012/02/08/path-uploads-your-entire-address-book-to-their-servers.html) — iOS Dev Weekly · Issue 28 — Article · Topics: Cross-Platform & Web · Maps & Location · Security & Privacy
  **Published:** `10th February 2012`
  **NeKI brief:** Examines Path uploads your entire iPhone address book to its servers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Introducing SocketRocket](http://corner.squareup.com/2012/02/socketrocket-websockets.html) — iOS Dev Weekly · Issue 28 — Article · Topics: Cross-Platform & Web · Networking
  **Published:** `10th February 2012`
  **NeKI brief:** Explains Introducing SocketRocket with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Core Data Queries Using Expressions](http://useyourloaf.com/blog/2012/1/19/core-data-queries-using-expressions.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `27th January 2012`
  **NeKI brief:** Explains Core Data Queries Using Expressions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UIStoryboard Power Drill](http://jleeiii.blogspot.com/2012/01/uistoryboard-power-drill.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Cross-Platform & Web
  **Published:** `27th January 2012`
  **NeKI brief:** Explains UIStoryboard Power Drill with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Dependency Graph Tool for iOS Projects](http://jomnius.blogspot.com/2012/01/dependency-graph-tool-for-ios-projects.html) — iOS Dev Weekly · Issue 24 — Article · Topics: Cross-Platform & Web · Dependency Injection · Objective-C & Cocoa
  **Published:** `13th January 2012`
  **NeKI brief:** Examines Jouni Miettunen has been playing with (and fixing) with a visualisation tool for Objective-C project dependencies. I haven’t had a chance to play with it yet but it looks like fun. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [BBC iPlayer: Designing the iPhone app](http://www.bbc.co.uk/blogs/bbcinternet/2011/12/iphone_bbc_iplayer_design.html) — iOS Dev Weekly · Issue 21 — Article · Topics: Cross-Platform & Web
  **Published:** `23rd December 2011`
  **NeKI brief:** Chris Elphick from the BBC gives a detailed look into the design of their iPhone app which was released a couple of weeks ago.
- [UIAlertView changes in iOS 5](http://useyourloaf.com/blog/2011/12/14/uialertview-changes-in-ios-5.html) — iOS Dev Weekly · Issue 20 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th December 2011`
  **NeKI brief:** Explains UIAlertView changes in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLVM 3.0 Release Notes](http://llvm.org/releases/3.0/docs/ReleaseNotes.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Systems Programming · Xcode
  **Published:** `9th December 2011`
  **NeKI brief:** Explains LLVM 3.0 Release Notes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Object File Inspection Tools](http://www.mikeash.com/pyblog/friday-qa-2011-12-02-object-file-inspection-tools.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web
  **Published:** `9th December 2011`
  **NeKI brief:** I have been trying not to link to Mike Ash every week (you really should be subscribed!) but I couldn’t let this one pass unnoticed. This week takes a look at otool, nm, otx and class-dump.
- [When GCD Isn’t The Best Abstraction](http://cocoamanifest.net/articles/2011/12/when-gcd-isn-t-the-best-abstraction.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th December 2011`
  **NeKI brief:** Jonathan Penn on MKNetworkKit using NSOperation over GCD. Personally I am a big fan of NSOperation and usually find myself reaching for it in preference to GCD as I find it easier to write clean code with concurrent code being well separated into classes. I…
- [Deconstructing and Putting Back Together Some Icons in Acorn](http://shapeof.com/archives/2011/11/deconstructing_and_putting_back_together_some_icons_in_acorn.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th December 2011`
  **NeKI brief:** Examines Deconstructing and Putting Back Together Some Icons in Acorn. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Simple iOS 5 UI Design Tutorial Using Storyboard in XCode 4](http://kurrytran.blogspot.com/2011/07/simple-ios-5-tutorial-using-storyboard.html) — iOS Dev Weekly · Issue 18 — Tutorial · Topics: Cross-Platform & Web · Xcode
  **Published:** `2nd December 2011`
  **NeKI brief:** Explains Simple iOS 5 UI Design Tutorial Using Storyboard in XCode 4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [The inevitable frustration of 1★ reviews on Android](https://skitch.com/daveverwer/gc7dy/path-android-market) — iOS Dev Weekly · Issue 18 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2nd December 2011`
  **NeKI brief:** I really don’t want to bash Android in this email but when investigating to see if I could get a glimpse of the Path UI for Android yesterday I was immediately struck by the negative reviews left on the marketplace being primarily related to different screen…
- [Stanford iOS development course updated for iOS 5](http://useyourloaf.com/blog/2011/11/16/stanford-ios-development-course-updated-for-ios-5.html) — iOS Dev Weekly · Issue 16 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `18th November 2011`
  **NeKI brief:** Describes an updated Stanford iOS development course for iOS 5. Follow it for historical teaching and platform context, while using current Swift and Apple documentation for implementation.
- [Settings Radio Group Element](http://useyourloaf.com/blog/2011/11/1/settings-radio-group-element.html) — iOS Dev Weekly · Issue 14 — Article · Topics: Cross-Platform & Web
  **Published:** `4th November 2011`
  **NeKI brief:** Explains Settings Radio Group Element with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sync preference data with iCloud](http://useyourloaf.com/blog/2011/10/24/sync-preference-data-with-icloud.html) — iOS Dev Weekly · Issue 13 — Article · Topics: Cross-Platform & Web
  **Published:** `28th October 2011`
  **NeKI brief:** Explains Sync preference data with iCloud with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [How I Made 200,000$ in the iOS Education Market](http://blog.lescapadou.com/2011/10/how-ive-made-200000-in-ios-education.html) — iOS Dev Weekly · Issue 13 — Article · Topics: Cross-Platform & Web · Developer Community & Business
  **Published:** `28th October 2011`
  **NeKI brief:** A comprehensive look at sales across a variety of educational apps by Pierre Abel of L’Escapadou.
- [Using Regular Expressions Part 2 - the Cocoa Connection](http://www.escortmissions.com/blog/2011/10/15/using-regular-expressions-part-2-the-cocoa-connection.html) — iOS Dev Weekly · Issue 12 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st October 2011`
  **NeKI brief:** Explains Using Regular Expressions Part 2 the Cocoa Connection with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Automatic Reference Counting](http://www.mikeash.com/pyblog/friday-qa-2011-09-30-automatic-reference-counting.html) — iOS Dev Weekly · Issue 10 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `7th October 2011`
  **NeKI brief:** Simply the clearest and best explanation of ARC that I have seen so far. Fascinating.
- [Mobile Usability Update](http://www.useit.com/alertbox/mobile-usability.html) — iOS Dev Weekly · Issue 9 — Article · Topics: Cross-Platform & Web
  **Published:** `30th September 2011`
  **NeKI brief:** Explains Mobile Usability Update with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple, Apps, Appeals, & Appeasement: the Story of Drift](http://generalspecificity.com/2011/09/27/apple-apps-appeals-and-appeasement.html) — iOS Dev Weekly · Issue 9 — Article · Topics: Cross-Platform & Web · Developer Tools · Product Design
  **Published:** `30th September 2011`
  **NeKI brief:** Examines This 11.13 clause is really harming the user experience of apps like this github gist client (not to mention Kindle and the like). I really hope Apple are able to make changes to their terms soon to make this kind of app Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Xcode 4 DerivedData and cleaning the build directory](http://useyourloaf.com/blog/2011/9/14/xcode-4-deriveddata-and-cleaning-the-build-directory.html) — iOS Dev Weekly · Issue 8 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `23rd September 2011`
  **NeKI brief:** Explains Xcode 4 DerivedData and cleaning the build directory with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Let’s Build Reference Counting](http://www.mikeash.com/pyblog/friday-qa-2011-09-16-lets-build-reference-counting.html) — iOS Dev Weekly · Issue 8 — Article · Topics: Cross-Platform & Web
  **Published:** `23rd September 2011`
  **NeKI brief:** Explains Let’s Build Reference Counting with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [What to Do When Business Breaks Down](http://www.huffingtonpost.com/april-rudin/rework-crisis-communicati_b_954839.html) — iOS Dev Weekly · Issue 7 — Article · Topics: Cross-Platform & Web
  **Published:** `16th September 2011`
  **NeKI brief:** Examines What to Do When Business Breaks Down: One Guy. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Why native apps are here to stay](http://www.mentalfaculty.com/mentalfaculty/Blog/Entries/2011/9/8_WHY_NATIVE_APPS_ARE_HERE_TO_STAY.html) — iOS Dev Weekly · Issue 6 — Article · Topics: Cross-Platform & Web
  **Published:** `9th September 2011`
  **NeKI brief:** Lots of discussion after Jeremy Keith’s presentation at UpdateConf this week on why web apps should replace native apps. Drew McCormack gives a nice overview of the talk, and offers an alternative view.
- [Friday Q&A: Let’s Build NSAutoreleasePool](http://www.mikeash.com/pyblog/friday-qa-2011-09-02-lets-build-nsautoreleasepool.html) — iOS Dev Weekly · Issue 6 — Article · Topics: Cross-Platform & Web
  **Published:** `9th September 2011`
  **NeKI brief:** Explains Friday Q A Let’s Build NSAutoreleasePool with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iTunes Connect App Status Flowchart](http://useyourloaf.com/blog/2011/8/29/itunes-connect-app-status-update.html) — iOS Dev Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2nd September 2011`
  **NeKI brief:** Examines Almost a year ago I created a flowchart to try and make sense of the various states an app can go through during the iOS App Store submission process. There have been some recent c. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Friday Q&A: Namespaced Constants and Functions](http://www.mikeash.com/pyblog/friday-qa-2011-08-19-namespaced-constants-and-functions.html) — iOS Dev Weekly · Issue 4 — Article · Topics: Cross-Platform & Web
  **Published:** `26th August 2011`
  **NeKI brief:** Explains Friday Q A Namespaced Constants and Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [A Familiar Place](http://kevinhoctor.blogspot.com/2011/08/familiar-place.html) — iOS Dev Weekly · Issue 4 — Article · Topics: Cross-Platform & Web
  **Published:** `26th August 2011`
  **NeKI brief:** The article reflects on a familiar software or design experience and presents the author's observations in a readable public post.
- [ARC](http://clang.llvm.org/docs/AutomaticReferenceCounting.html) — iOS Dev Weekly · Issue 2 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `12th August 2011`
  **NeKI brief:** This Clang specification defines the semantics and compiler rules of Objective-C Automatic Reference Counting. It is the authoritative technical reference for understanding ownership qualifiers, retain and release insertion, and ARC edge cases in mixed-language Apple code.
- [An iOS Developer Takes on Android](http://nfarina.com/post/8239634061/ios-to-android) — iOS Dev Weekly · Issue 1 — Article · Topics: Cross-Platform & Web
  **Published:** `5th August 2011`
  **NeKI brief:** Explains An iOS Developer Takes on Android, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [iOS Integration Testing](http://corner.squareup.com/2011/07/ios-integration-testing.html) — iOS Dev Weekly · Issue 1 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `5th August 2011`
  **NeKI brief:** Explains iOS Integration Testing, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [MCP is dead. Long live the CLI](https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html) — Not only Swift · Issue 95 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **NeKI brief:** This article covers the case for durable command-line interfaces over MCP-only tooling. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Apple Docs MCP](https://github.com/kimsungwhee/apple-docs-mcp) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** This source repository covers an MCP server for searching Apple developer documentation. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [A Software Library with No Code](https://www.dbreunig.com/2026/01/08/a-software-library-with-no-code.html) — Not only Swift · Issue 92 — Article · Topics: Cross-Platform & Web
  **NeKI brief:** This article covers software libraries that contain no implementation code. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Why We've Tried to Replace Developers Every Decade Since 1969](https://www.caimito.net/en/blog/2025/12/07/the-recurring-dream-of-replacing-developers.html) — Not only Swift · Issue 90 — Article · Topics: Cross-Platform & Web
  **NeKI brief:** This article covers historical attempts to automate away software developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Some thoughts on LLMs and Software Development](https://martinfowler.com/articles/202508-ai-thoughts.html) — Not only Swift · Issue 87 — Article · Topics: AI Development · Cross-Platform & Web
  **NeKI brief:** Martin Fowler examines how generative AI is changing software-development practice, including the effects on programming tasks, review, design, and engineering judgment. The article is useful for evaluating where AI assistance changes development workflows while retaining responsibility for technical outcomes.
- [radial menu](https://bigmedium.com/ideas/radial-menus-for-touch-ui.html) — Not only Swift · Issue 85 — Article · Topics: Cross-Platform & Web · Liquid Glass · Swift
  **NeKI brief:** This article covers radial menus as a touch-interface pattern. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Introducing Swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Not only Swift · Issue 78 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
