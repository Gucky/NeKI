# Maps & Location

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** MapKit, Core Location, geographic data, geocoding, and location-aware apps.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **58**

## Direct-source reading

- [MapKit Tutorial: Overlay Views | Kodeco](https://www.kodeco.com/9956648-mapkit-tutorial-overlay-views) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The tutorial builds image and line overlays on MKMapView, making the rendering layer useful for route traces or other map annotations beyond pins.
- [MapKit and Core Location | Kodeco](https://www.kodeco.com/9236-mapkit-and-core-location) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A video series combines Core Location fundamentals with MapKit routing and flyover features, useful when an app must turn a coordinate into navigable map context.
- [MapKit Tutorial: Getting Started | Kodeco](https://www.kodeco.com/7738344-mapkit-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A first MapKit project displays location details and hands off driving directions to Maps, covering the basic user flow before advanced overlays or custom tiles.
- [Augmented Reality iOS Tutorial: Location Based | Kodeco](https://www.kodeco.com/764-augmented-reality-ios-tutorial-location-based) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Location-based AR combines Core Location with camera overlays to anchor experiences in geographic context. Follow it to assess heading accuracy, permission flow and drift—constraints that can dominate usability more than the rendering code itself.
- [Google Maps iOS SDK Tutorial: Getting Started | Kodeco](https://www.kodeco.com/7363101-google-maps-ios-sdk-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A Google Maps client combines location permission, map state and nearby-place search. It is useful for comparing third-party map capabilities with MapKit, including provider-specific APIs, licensing and the extra abstraction boundary they introduce.
- [Core Location Tutorial for iOS: Tracking Visited Locations | Kodeco](https://www.kodeco.com/5247-core-location-tutorial-for-ios-tracking-visited-locations) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Location visit monitoring records significant place changes without continuous GPS polling. Follow it to assess the battery-versus-freshness trade-off and to keep authorization and background-delivery behavior explicit.
- [MapKit and Core Location | Kodeco](https://www.kodeco.com/3356-mapkit-and-core-location) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combines MapKit display with Core Location positioning and authorization. Useful for separating map rendering from the permission, accuracy, and update-policy decisions governing location data.
- [Using the Google Places API With MapKit | Kodeco](https://www.kodeco.com/2907-using-the-google-places-api-with-mapkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combines place search results with MapKit display. Useful for separating external place lookup, location coordinates, and map annotations in a discovery flow.
- [Introduction to MapKit in iOS 6 Tutorial | Kodeco](https://www.kodeco.com/2846-introduction-to-mapkit-in-ios-6-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Retrieves remote incident data, plots it on MKMapView, controls the visible region, opens Maps, and reports loading progress. Useful for a basic map-data pipeline where fetching, annotation placement, and user handoff remain separate steps.
- [Google Maps iOS SDK Tutorial: Getting Started | Kodeco](https://www.kodeco.com/197-google-maps-ios-sdk-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Google Maps SDK example combines location permission, map state and nearby-place queries. It is useful for comparing a third-party map stack with MapKit, especially where provider-specific search and licensing shape the architecture.
- [Advanced MapKit | Kodeco](https://www.kodeco.com/14255351-advanced-mapkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The advanced MapKit material contrasts overlays, renderers and custom drawing for map content. It helps choose the right rendering boundary: annotate discrete objects, use overlays for geometry, and avoid pushing large datasets through view-level work.
- [Indoor Maps on iOS: Advanced MapKit | Kodeco](https://www.kodeco.com/12690970-indoor-maps-on-ios-advanced-mapkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Decodes GeoJSON and IMDF indoor-map data with MKGeoJSONDecoder, renders levels, overlays, annotations, and location. Useful when a venue map needs semantic indoor geometry and floor selection instead of a generic outdoor map overlay.
- [Sanitizing GPX files for public sharing – Ole Begemann](https://oleb.net/2020/sanitizing-gpx) — Ole Begemann · article catalogue
  **Published:** `2020-06-22T14:01:32Z`
  **NeKI brief:** GPX files can contain timestamps, device metadata, and precise locations beyond the route a user intends to share. An XmlStarlet filtering pass removes those fields before publication, trading convenience for a reproducible privacy boundary.
- [Changes to location access in iOS 13 – Donny Wals](https://www.donnywals.com/changes-to-location-access-in-ios-13) — Donny Wals · article catalogue
  **Published:** `2019-12-02T08:00:02+00:00`
  **NeKI brief:** Location authorization changes affect when an app may receive updates, so product flows must explain permission scope and handle reduced access gracefully.
- [Mac Sandboxing: Location Services Access Requires Outgoing Connections – Ole Begemann](https://oleb.net/blog/2013/01/mac-sandboxing-location-services-outgoing-connections) — Ole Begemann · article catalogue
  **Published:** `2013-01-17T17:00:00Z`
  **NeKI brief:** Explains a macOS sandboxing dependency where Location Services can require outgoing-network entitlement, helping diagnose an otherwise surprising capability failure in sandboxed apps.
- [Animating the Drawing of a CGPath With CAShapeLayer – Ole Begemann](https://oleb.net/blog/2010/12/animating-drawing-of-cgpath-with-cashapelayer) — Ole Begemann · article catalogue
  **Published:** `2010-12-18T17:57:00Z`
  **NeKI brief:** Animates CAShapeLayer strokeEnd from zero to one to reveal a CGPath progressively, then synchronizes a keyframe-animated pen layer along the same path. The technique also connects text glyph paths to Core Text when the drawn path originates from typography.
- [mikeash.com: Friday Q&A 2015-05-29: Concurrent Memory Deallocation in the Objective-C Runtime](https://www.mikeash.com/pyblog/friday-qa-2015-05-29-concurrent-memory-deallocation-in-the-objective-c-runtime.html) — Mike Ash · article catalogue
  **NeKI brief:** The article examines how Objective-C runtime deallocation can race under concurrency; saved technical context supports a concrete ownership and synchronization brief in a later source-specific override batch.

## Newsletter and related leads

- [The CTO’s Incoming Storms](https://ctosub.com/p/the-ctos-incoming-storms) — Those Who Swift · Issue 266 — Article · Topics: AI Development · Maps & Location
  **Published:** `2026-05-13`
  **NeKI brief:** Discusses incoming risks and decisions for CTOs. Useful as engineering-leadership context when evaluating organizational resilience, technical strategy, and the operational consequences of shipping systems under changing constraints.
- [Six Years Perfecting Maps on watchOS](https://david-smith.org/blog/2026/04/29/maps-on-watchos) — SwiftLee Weekly · Issue 322 — Article · Topics: Maps & Location
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Discusses Six Years Perfecting Maps on watchOS, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [AcceptedSE-0517UniqueBox](https://github.com/apple/swift-evolution/blob/main/proposals/0517-uniquebox.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Records AcceptedSE-0517UniqueBox, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Active ReviewSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — SwiftUI Weekly · SwiftUI Weekly - Issue #232 — Article · Topics: Maps & Location · Swift · SwiftUI
  **Published:** `2026-04-27T08:30:04.557Z`
  **NeKI brief:** Rob shows how SwiftUI Previews can be used as a lightweight accessibility testing tool, letting you quickly inspect UI variations before testing on a device.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [iOS Application Rendering: A Deep Dive](https://l.fatbobman.com/w0103-06) — Fatbobman’s Swift Weekly · Issue 103 — Article · Topics: Graphics, Media & Games · Maps & Location
  **Published:** `2025-09-22T12:03:29.428Z`
  **NeKI brief:** Documents a personal investigation into how iOS renders application content. Follow it when studying rendering stages, compositing assumptions, and the boundary between observable UIKit behavior and implementation details that may change.
- [FoundationModels: Tool Calling for an Assistant App](https://destiner.io/blog/post/foundation-models-tool-calling-search-app) — Those Who Swift · Issue 229 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-08-27`
  **NeKI brief:** Applies Foundation Models tool calling to an assistant-style search app. Useful for examining tool schemas, model-controlled actions, and the validation boundary before executing search operations.
- [Finding my Way](https://david-smith.org/blog/2025/07/02/new-maps) — SwiftLee Weekly · Issue 279 — Article · Topics: Maps & Location
  **Published:** `2025-07-08T13:08:44.000Z`
  **NeKI brief:** Discusses Finding my Way, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Fluig](https://www.fluig.cc/home) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Article · Topics: AI Development · Maps & Location
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Fluig is a developer productivity product focused on streamlining software workflows. Use it as a discovery lead when comparing tooling for planning or execution, and verify supported integrations, data residency, and workflow portability.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — SwiftLee Weekly · Issue 262 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-11T15:01:20.000Z`
  **NeKI brief:** Chris explores how to display pixel art crisply in SwiftUI, ensuring sharp edges without unwanted blurring for game assets but also for low-resolution graphics.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts?ref=createwithswift.com) — Create with Swift · Issue 47 — Article · Topics: Maps & Location · Swift
  **Published:** `2025-02-07T16:00:24.000Z`
  **NeKI brief:** Artem shows how developers merge location-based data with the Swift Chart framework to create insightful data visualizations.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — iOS Dev Weekly · Issue 698 — Article · Topics: Maps & Location · Swift
  **Published:** `7th February 2025`
  **NeKI brief:** Artem shows how developers merge location-based data with the Swift Chart framework to create insightful data visualizations.
- [MapKit + Metal Shaders + H3 (Uber Hex System) + SwiftUI](https://javios.gumroad.com/l/zlnde) — Those Who Swift · Issue 199 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-01-30`
  **NeKI brief:** Combines MapKit, Metal shaders, H3, and SwiftUI in a mapping example. Useful for evaluating geographic visualization architecture and the boundary between map data, GPU effects, and SwiftUI presentation.
- [How to build a draggable bottom sheet with a scroll view in SwiftUI](https://tanaschita.com/20240311-draggable-sheet-with-scroll-view) — SwiftUI Weekly · SwiftUI Weekly - Issue #179 — Article · Topics: Maps & Location · Swift · SwiftUI
  **Published:** `2024-03-19T15:26:15.403Z`
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet coordinated with an inner ScrollView. Useful for designing gesture handoff and preventing sheet dragging from fighting content scrolling.
- [Poynton](https://maps.app.goo.gl/6tbgo9mJsg2uGYpR7) — iOS Dev Weekly · Issue 645 — Article · Topics: Maps & Location
  **Published:** `26th January 2024`
  **NeKI brief:** The link resolves to a publicly readable Google Maps place page for Poynton, preserving the location reference associated with the original item.
- [Apple’s use of AppKit, Catalyst, Swift and SwiftUI in macOS Sonoma](https://blog.timac.org/2023/1128-state-of-appkit-catalyst-swift-swiftui-mac) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys AppKit, Catalyst, Swift, and SwiftUI capabilities on macOS, highlighting interoperability boundaries. Useful for choosing a platform strategy when an app spans native macOS and shared UI code.
- [Link to GitHub.](https://github.com/mapbox/mapbox-maps-ios) — iOS Dev Tools · 🔨 Introducing Mapbox, Alamofire, RNCrypto — Source repository · Topics: Developer Tools · Maps & Location
  **Published:** `2023-08-03T12:40:06.374Z`
  **NeKI brief:** Mapbox Maps SDK for iOS provides vector maps, annotations, styling, navigation-oriented capabilities, and offline regions. Use it when Apple MapKit’s data or customization is insufficient, accounting for tokens, licensing, and offline package management.
- [👀 Uploading link maps to Emerge](https://www.roger.ml/p/emerge-linkmaps) — iOS CI Newsletter · Issue 18 — Article · Topics: Maps & Location · Performance
  **Published:** `2023-06-18T00:00:00.000Z`
  **NeKI brief:** Examines Uploading link maps to Emerge in the context of Maps & Location and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [State College, PA](https://goo.gl/maps/adU5Spv4mDvgS5F76) — iOS Dev Weekly · Issue 558 — Article · Topics: Maps & Location · Personal Essays
  **Published:** `13th May 2022`
  **NeKI brief:** I had travelled to the US on a business trip for the company I worked for at the time. I was in State College, PA, which at the time was the coldest place I had ever visited. I remember looking at a weather display in the hotel lobby and thinking, “Oh, -3º…
- [Comparing iPhone OS 1.0 with iOS 14 using tree maps](https://blog.timac.org/2020/1122-comparing-iphone-os-with-ios-14-using-tree-maps) — iOS Dev Weekly · Issue 484 — Article · Topics: Maps & Location
  **Published:** `27th November 2020`
  **NeKI brief:** Examines Alexandre Colucci is at it again, this time with a great visualisation of what types of files make up iOS releases over the years. As many people have noticed, it’s striking how much of iOS 1 was font files, but I think Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [FloatingPanel](https://github.com/SCENEE/FloatingPanel) — iOS Dev Weekly · Issue 375 — Source repository · Topics: Developer Tools · Maps & Location · Objective-C & Cocoa
  **Published:** `26th October 2018`
  **NeKI brief:** Examines A clean and easy-to-use floating panel UI component for iOS - scenee/FloatingPanel. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [StyledTextKit](http://github.com/GitHawkApp/StyledTextKit) — iOS Dev Weekly · Issue 357 — Source repository · Topics: Developer Tools · Maps & Location
  **Published:** `22nd June 2018`
  **NeKI brief:** Examines Declarative building and fast rendering attributed string library. - GitHawkApp/StyledTextKit. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [without anyone really noticing](http://appleinsider.com/articles/17/05/01/major-apps-abandoning-apple-watch-including-google-maps-amazon-ebay) — iOS Dev Weekly · Issue 299 — Article · Topics: Maps & Location
  **Published:** `5th May 2017`
  **NeKI brief:** Examines In recent months, major companies that offered dedicated Apple Watch apps have since abandoned the platform, quietly removing support for watchOS in updates submitted to the App St. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [new system font](http://9to5mac.com/2015/05/20/apple-plans-to-refresh-ios-9-os-x-10-11-using-new-apple-watch-font) — iOS Dev Weekly · Issue 199 — Article · Topics: Maps & Location
  **Published:** `22nd May 2015`
  **NeKI brief:** Pre-WWDC reporting on the possible adoption of the Apple Watch system font in iOS 9 and OS X 10.11. Treat it as historical speculation about Apple's visual-platform direction.
- [Split screen apps](http://9to5mac.com/2015/05/21/future-of-ipad-dual-app-viewing-mode-then-j99-ipad-pro-multi-user-support) — iOS Dev Weekly · Issue 199 — Article · Topics: Maps & Location
  **Published:** `22nd May 2015`
  **NeKI brief:** Pre-release reporting on split-screen iPad apps and possible multi-user support. Use it only as historical context for the period before iPad multitasking APIs were announced.
- [better transit support in maps](http://9to5mac.com/2015/05/21/apple-readies-transit-subway-train-bus-guides-for-ios-9-maps-deploys-robots-for-indoor-mapping) — iOS Dev Weekly · Issue 199 — Article · Topics: Maps & Location
  **Published:** `22nd May 2015`
  **NeKI brief:** Pre-release reporting on expanded transit directions and indoor mapping data for iOS 9 Maps. It is historical product reporting, not a guide to MapKit integration.
- [iOS 8 Location Services PSA](http://www.neglectedpotential.com/2014/09/ios-8-location-services-psa) — iOS Dev Weekly · Issue 166 — Article · Topics: Maps & Location
  **Published:** `3rd October 2014`
  **NeKI brief:** Explains iOS 8 Location Services PSA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [POI clustering on iOS](https://www.infinum.co/the-capsized-eight/articles/a-blazingly-fast-open-source-algorithm-for-poi-clustering-on-ios) — iOS Dev Weekly · Issue 165 — Article
  **Published:** `26th September 2014`
  **NeKI brief:** Explains POI clustering on iOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [work by Thoughtbot](http://robots.thoughtbot.com/how-to-handle-large-amounts-of-data-on-maps) — iOS Dev Weekly · Issue 165 — Article · Topics: Maps & Location
  **Published:** `26th September 2014`
  **NeKI brief:** Discusses strategies for displaying large datasets on iOS maps, focusing on reducing rendering and interaction costs as annotations grow. Useful when choosing clustering or aggregation approaches for map-heavy interfaces.
- [FBAnnotationClustering](https://github.com/infinum/FBAnnotationClustering) — iOS Dev Weekly · Issue 165 — Source repository · Topics: Developer Tools
  **Published:** `26th September 2014`
  **NeKI brief:** Examines iOS library for clustering map notifications in an easy and performant way - infinum/FBAnnotationClustering. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [CCHMapClusterController](https://github.com/choefele/CCHMapClusterController) — iOS Dev Weekly · Issue 132 — Source repository · Topics: Developer Tools
  **Published:** `7th February 2014`
  **NeKI brief:** Provides the CCHMapClusterController source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Courses on Code School](https://www.codeschool.com/courses/core-ios-7) — iOS Dev Weekly · Issue 122 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `29th November 2013`
  **NeKI brief:** Explains iOS Courses on Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [SVPulsingAnnotationView](https://github.com/samvermette/SVPulsingAnnotationView) — iOS Dev Weekly · Issue 84 — Source repository · Topics: Developer Tools
  **Published:** `8th March 2013`
  **NeKI brief:** Sam Vermette with a nice imageless version of the radiating map pin control seen in MapKit. It’s always nice to see artwork source files included in a project like this and in this case they are PaintCode files which is great if you want to customise the…
- [iOS 6 maps are better for applications](http://halmueller.wordpress.com/2012/09/21/ios-6-maps-are-better-for-applications) — iOS Dev Weekly · Issue 61 — Article · Topics: Maps & Location
  **Published:** `28th September 2012`
  **NeKI brief:** Examines To buck the trend of the rest of the internet I am going to link to a post praising Apple’s new maps rather than trashing them. Hal Mueller proposes that the new maps in iOS 6 look better in-app than the Google equivalen Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Custom Callout View for iOS](http://nfarina.com/post/29883229869/callout-view) — iOS Dev Weekly · Issue 56 — Article
  **Published:** `24th August 2012`
  **NeKI brief:** Explains Custom Callout View for iOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [MapBox Mobile](http://mapbox.com/mobile) — iOS Dev Weekly · Issue 38 — Article
  **Published:** `20th April 2012`
  **NeKI brief:** Examines This OpenStreetMap based MapKit replacement looks like it might be a nice solution if you want an alternative to the Google tiles. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Path uploads your entire iPhone address book to its servers](http://mclov.in/2012/02/08/path-uploads-your-entire-address-book-to-their-servers.html) — iOS Dev Weekly · Issue 28 — Article · Topics: Cross-Platform & Web · Maps & Location · Security & Privacy
  **Published:** `10th February 2012`
  **NeKI brief:** Examines Path uploads your entire iPhone address book to its servers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ErrorKit](https://github.com/FlineDev/ErrorKit) — Not only Swift · Issue 81 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **NeKI brief:** ErrorKit is an Apple-platform error presentation layer that turns failures into user-facing alerts, sheets, or notifications while keeping error handling composable. The source helps evaluate a centralized approach to reporting errors across SwiftUI and UIKit flows.
