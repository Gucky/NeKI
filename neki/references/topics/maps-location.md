# Maps & Location

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** MapKit, Core Location, geographic data, geocoding, and location-aware apps.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **37**

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

- [ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — SwiftUI Weekly · SwiftUI Weekly - Issue #232 — Article · Topics: Maps & Location · Swift · SwiftUI
  **Published:** `2026-04-27T08:30:04.557Z`
  **NeKI brief:** Uses SwiftUI previews as an accessibility testing surface, checking labels, traits, and contrast across representative states. Useful for finding VoiceOver regressions early without waiting for a full UI-test suite.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [Fluig](https://www.fluig.cc/home) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Article · Topics: AI Development · Maps & Location
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Fluig is a developer productivity product focused on streamlining software workflows. Use it as a discovery lead when comparing tooling for planning or execution, and verify supported integrations, data residency, and workflow portability.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — SwiftLee Weekly · Issue 262 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-11T15:01:20.000Z`
  **NeKI brief:** Presents Rendering Pixel Art with SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts?ref=createwithswift.com) — Create with Swift · Issue 47 — Article · Topics: Maps & Location · Swift
  **Published:** `2025-02-07T16:00:24.000Z`
  **NeKI brief:** Uses Swift Charts to draw map-like visualizations from coordinate data. Useful for plotting paths or geographic series when a chart is sufficient and a full map renderer would add unnecessary complexity.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — iOS Dev Weekly · Issue 698 — Article · Topics: Maps & Location · Swift
  **Published:** `7th February 2025`
  **NeKI brief:** Uses Swift Charts to draw map-like visualizations from coordinate data. Useful for plotting paths or geographic series when a chart is sufficient and a full map renderer would add unnecessary complexity.
- [How to build a draggable bottom sheet with a scroll view in SwiftUI](https://tanaschita.com/20240311-draggable-sheet-with-scroll-view) — SwiftUI Weekly · SwiftUI Weekly - Issue #179 — Article · Topics: Maps & Location · Swift · SwiftUI
  **Published:** `2024-03-19T15:26:15.403Z`
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet coordinated with an inner ScrollView. Useful for designing gesture handoff and preventing sheet dragging from fighting content scrolling.
- [Apple’s use of AppKit, Catalyst, Swift and SwiftUI in macOS Sonoma](https://blog.timac.org/2023/1128-state-of-appkit-catalyst-swift-swiftui-mac) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys AppKit, Catalyst, Swift, and SwiftUI capabilities on macOS, highlighting interoperability boundaries. Useful for choosing a platform strategy when an app spans native macOS and shared UI code.
- [Link to GitHub.](https://github.com/mapbox/mapbox-maps-ios) — iOS Dev Tools · 🔨 Introducing Mapbox, Alamofire, RNCrypto — Source repository · Topics: Developer Tools · Maps & Location
  **Published:** `2023-08-03T12:40:06.374Z`
  **NeKI brief:** Mapbox Maps SDK for iOS provides vector maps, annotations, styling, navigation-oriented capabilities, and offline regions. Use it when Apple MapKit’s data or customization is insufficient, accounting for tokens, licensing, and offline package management.
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
- [CCHMapClusterController](https://github.com/choefele/CCHMapClusterController) — iOS Dev Weekly · Issue 132 — Source repository · Topics: Developer Tools
  **Published:** `7th February 2014`
  **NeKI brief:** Provides the CCHMapClusterController source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Courses on Code School](https://www.codeschool.com/courses/core-ios-7) — iOS Dev Weekly · Issue 122 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `29th November 2013`
  **NeKI brief:** Explains iOS Courses on Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Custom Callout View for iOS](http://nfarina.com/post/29883229869/callout-view) — iOS Dev Weekly · Issue 56 — Article
  **Published:** `24th August 2012`
  **NeKI brief:** Explains Custom Callout View for iOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ErrorKit](https://github.com/FlineDev/ErrorKit) — Not only Swift · Issue 81 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **NeKI brief:** ErrorKit is an Apple-platform error presentation layer that turns failures into user-facing alerts, sheets, or notifications while keeping error handling composable. The source helps evaluate a centralized approach to reporting errors across SwiftUI and UIKit flows.
