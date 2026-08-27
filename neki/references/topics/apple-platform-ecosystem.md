# Apple Platform Ecosystem

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** WWDC and platform announcements, Apple ecosystem context, compatibility history, and release-overview reading.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **652**

## Direct-source reading

- [CareKit Tutorial for iOS: Part 1 | Kodeco](https://www.kodeco.com/929-carekit-tutorial-for-ios-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Part one builds a CareKit symptom and workout tracker, showing how ORKTask and CareKit's store provide structured health activities instead of ad-hoc view state.
- [CareKit Tutorial for iOS: Part 2 | Kodeco](https://www.kodeco.com/928-carekit-tutorial-for-ios-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Part two extends the CareKit app with Insights and Connect, illustrating how stored task results become interpretable trends and shareable care-team context.
- [Universal Type Identifiers Tutorial for iOS: Importing and Exporting App Data | Kodeco](https://www.kodeco.com/8413525-universal-type-identifiers-tutorial-for-ios-importing-and-exporting-app-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds import and export flows with uniform type identifiers, including custom document types and extensions. Use it to align file declarations, document picker behavior, and data serialization instead of relying on filename conventions alone.
- [Introduction to Protocol Buffers on iOS | Kodeco](https://www.kodeco.com/749-introduction-to-protocol-buffers-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Walks through defining a .proto schema, generating Swift types, and consuming protobuf responses from an iOS client. Useful for evaluating a compact typed wire format when a backend contract needs stronger evolution rules than ad-hoc JSON.
- [iOS App with Kotlin/Native: Getting Started | Kodeco](https://www.kodeco.com/7357-ios-app-with-kotlin-native-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects Kotlin/Native common code to an iOS storyboard app, Gradle build phases, Objective-C libraries, MapKit, and network calls. Useful for seeing the integration friction around shared Kotlin logic rather than treating cross-platform code as a drop-in framework.
- [iOS File Provider Extension Tutorial | Kodeco](https://www.kodeco.com/697468-ios-file-provider-extension-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows how a File Provider extension exposes remote documents through the Files app, including identifiers, placeholders, item retrieval, and error cases. Useful for designing document access that remains integrated with system file workflows rather than a custom browser.
- [Updated Course: Your First iOS App | Kodeco](https://www.kodeco.com/6551-updated-course-your-first-ios-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Updates a beginner iOS app course around the project, controls, and interaction fundamentals. It is useful for onboarding and legacy maintenance where UIKit lifecycle and target configuration still matter.
- [Reproducing Popular iOS Controls Part 2: Robinhood | Kodeco](https://www.kodeco.com/6384-reproducing-popular-ios-controls-part-2-robinhood) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Recreates a Robinhood-style interface as a focused implementation exercise. Useful for examining how chart-like visuals and interactive finance-inspired controls can be broken into reusable state, drawing, and gesture responsibilities.
- [Core Text Tutorial for iOS: Making a Magazine App | Kodeco](https://www.kodeco.com/578-core-text-tutorial-for-ios-making-a-magazine-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Core Text to lay out magazine-style text with custom typography and flow. Useful when UILabel or Text cannot satisfy pagination, columns, or detailed glyph-level layout requirements.
- [AR Face Tracking Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/5491-ar-face-tracking-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A TrueDepth face-tracking example connects ARFaceAnchor blend-shape data to scene content, making expression-driven overlays concrete. It also exposes the hardware and privacy constraints that should shape a fallback path for devices without face tracking.
- [Drawing in iOS – Part 2: Core Graphics | Kodeco](https://www.kodeco.com/5390-drawing-in-ios-part-2-core-graphics) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Graphics drawing is applied through custom layers and views, making coordinate systems and invalidation explicit. Follow it when deciding whether a visual belongs in retained layers or a redraw-driven rendering path.
- [iOS 11 Drag and Drop with Multiple Data Representations and Custom Views | Kodeco](https://www.kodeco.com/5004-ios-11-drag-and-drop-with-multiple-data-representations-and-custom-views) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Handles drag items with multiple representations and custom drop targets. Useful when a transfer may carry different data formats and the receiving view must choose the representation it can safely consume.
- [iOS 10: The UserNotifications Framework | Kodeco](https://www.kodeco.com/4997-ios-10-the-usernotifications-framework) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces the UserNotifications framework for scheduling and managing local or remote notification behavior. Useful for separating authorization, request construction, delivery triggers, and response handling in a notification feature.
- [iOS 10: Providing Haptic Feedback | Kodeco](https://www.kodeco.com/4993-ios-10-providing-haptic-feedback) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses the system haptic generators to reinforce taps, changes, and notifications with tactile feedback. Useful for choosing feedback that confirms a meaningful state transition rather than adding vibration to every interaction.
- [iOS 10: Collaborative Messaging in iOS 10 | Kodeco](https://www.kodeco.com/4975-ios-10-collaborative-messaging-in-ios-10) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores collaborative messaging patterns built on iMessage app capabilities. Useful for thinking through how a shared conversation action must encode state, participant context, and a recoverable representation for recipients.
- [iOS 10: Custom Notification UI with Content Extensions | Kodeco](https://www.kodeco.com/4970-ios-10-custom-notification-ui-with-content-extensions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses a notification content extension to replace the system notification presentation with custom UI. Useful when a notification needs richer in-place information while respecting the extension's constrained lifecycle and interaction model.
- [iOS 10: Dynamic Sticker Packs in iMessage Apps | Kodeco](https://www.kodeco.com/4969-ios-10-dynamic-sticker-packs-in-imessage-apps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds dynamic sticker content for an iMessage app rather than a fixed asset pack. Useful for understanding when sticker generation or selection needs application state and an extension-backed interactive surface.
- [iOS 10: User Notification Management | Kodeco](https://www.kodeco.com/4968-ios-10-user-notification-management) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Manages notification categories, actions, and delivered requests through UserNotifications. Useful for treating notification behavior as a lifecycle that includes setup, delivery, user response, and later cleanup.
- [iOS 10: Audio File Speech Transcription | Kodeco](https://www.kodeco.com/4965-ios-10-audio-file-speech-transcription) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Transcribes an audio file with speech-recognition APIs and exposes the resulting text. Useful for separating authorization, audio input, recognition request, and partial or final transcription state in a speech feature.
- [iOS 11: NLP with NSLinguisticTagger | Kodeco](https://www.kodeco.com/4958-ios-11-nlp-with-nslinguistictagger) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses NSLinguisticTagger to classify and extract linguistic information from text. Useful for prototyping token, language, or semantic analysis without first building a custom natural-language processing pipeline.
- [iOS 10: Live Speech Recognition | Kodeco](https://www.kodeco.com/4957-ios-10-live-speech-recognition) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds live speech recognition around an audio engine and streaming recognition request. Useful for managing the distinction between ongoing partial results, final transcription, microphone lifecycle, and user-visible recording state.
- [iOS 10: Interactive Custom Notifications | Kodeco](https://www.kodeco.com/4956-ios-10-interactive-custom-notifications) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds actions to custom notifications so a user can respond from the notification interface. Useful for designing a concise action protocol that works within an extension instead of assuming the full app is available.
- [iOS 10: Property Animators: Timing Functions | Kodeco](https://www.kodeco.com/4955-ios-10-property-animators-timing-functions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores timing curves and custom timing behavior with UIViewPropertyAnimator. Useful when an animation's perceived quality depends on acceleration and deceleration rather than only its duration.
- [iOS 10: Capturing Live Photos | Kodeco](https://www.kodeco.com/4952-ios-10-capturing-live-photos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Captures Live Photos through the camera stack and handles their dual media output. Useful for recognizing the configuration and resource implications of recording still and motion content together.
- [React Native Tutorial: Building iOS Apps with JavaScript | Kodeco](https://www.kodeco.com/485-react-native-tutorial-building-ios-apps-with-javascript) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a React Native search screen with JSX, navigation, Flexbox, component state, and an API request. Useful for evaluating the boundary between JavaScript-driven UI composition and native iOS integration in a small but complete feature flow.
- [Beginning iOS 10 Part 2 Checklists | Kodeco](https://www.kodeco.com/3871-beginning-ios-10-part-2-checklists) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Continues a beginner iOS workflow by building a checklist app with table views, design patterns, and saved data. Useful for seeing how familiar UI and persistence concerns converge in one small application.
- [Superwall: Remote Paywall Configuration on iOS | Kodeco](https://www.kodeco.com/38677971-superwall-remote-paywall-configuration-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows a Superwall dashboard-driven paywall flow where presentation rules and campaign changes can be adjusted remotely. Treat it as a product-integration case study, especially for deciding which purchase policy must remain enforceable in app code.
- [tvOS Tutorial: Using TVML Templates | Kodeco](https://www.kodeco.com/372-tvos-tutorial-using-tvml-templates) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses TVML templates to build tvOS interfaces driven by JavaScript and structured markup. Useful for understanding the alternate UI architecture used by TVML-based apps instead of native UIKit views.
- [On-Demand Resources in tvOS Tutorial | Kodeco](https://www.kodeco.com/370-on-demand-resources-in-tvos-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Requests tagged tvOS resources with NSBundleResourceRequest, observes download progress, anticipates user actions, and purges content. Useful for planning asset delivery on storage-constrained devices where media should arrive near the moment a user needs it.
- [tvOS Top Shelf Tutorial: Static and Interactive | Kodeco](https://www.kodeco.com/366-tvos-top-shelf-tutorial-static-and-interactive) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds static and interactive tvOS Top Shelf content. Useful for exposing app media on the system surface while keeping item metadata and deep-link handling consistent with the app itself.
- [Audio Recording in watchOS Tutorial | Kodeco](https://www.kodeco.com/345-audio-recording-in-watchos-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Records audio in a watchOS application and manages the capture lifecycle. Useful for considering device constraints, permissions, and file handling in a small-screen wearable interaction.
- [Core Bluetooth in watchOS Tutorial | Kodeco](https://www.kodeco.com/336-core-bluetooth-in-watchos-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This watchOS Core Bluetooth tutorial connects an app to external BLE peripherals. It helps reason about discovery, connection lifetime and constrained-device behavior, where radio availability and background execution are separate from UI state.
- [Advanced watchOS | Kodeco](https://www.kodeco.com/3358-advanced-watchos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The advanced watchOS series extends layout and table techniques into richer watch experiences. Its value is historical but concrete: it highlights the platform’s small-screen interaction budget and the cost of porting phone-first assumptions.
- [Table Views in iOS | Kodeco](https://www.kodeco.com/3300-table-views-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds table views with cells, data sources, delegates, and interaction. Useful for separating a scrolling list's model data from its cell configuration and selection behavior.
- [watchOS: Complications | Kodeco](https://www.kodeco.com/32839701-watchos-complications) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds watchOS complications that surface app data on the watch face. Follow it when designing timeline entries, refresh policy, and compact presentation separately from the full application UI.
- [Google Material Design Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/316-google-material-design-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Material Design tutorial adapts Android’s visual language to UIKit on iOS. It is useful for evaluating cross-platform consistency against platform conventions, especially around navigation, controls and touch-target expectations.
- [Table View Helper Class for iOS | Kodeco](https://www.kodeco.com/3153-table-view-helper-class-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Extracts repeated table-view support into a helper abstraction. Useful for evaluating when shared data-source behavior reduces duplication and when it hides screen-specific configuration that should remain local.
- [Auto Complete Tutorial for iOS: How To Auto Complete With Custom Values | Kodeco](https://www.kodeco.com/3152-auto-complete-tutorial-for-ios-how-to-auto-complete-with-custom-values) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements autocomplete with custom suggestion values and user selection behavior. Useful for separating input normalization, candidate filtering, and result presentation in a search-style control.
- [Cocos2D Buttons Tutorial for iOS: How To Create Buttons in Cocos2D: Simple, Radio, and Toggle | Kodeco](https://www.kodeco.com/3149-cocos2d-buttons-tutorial-for-ios-how-to-create-buttons-in-cocos2d-simple-radio-and-toggle) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Cocos2D button examples distinguish push, radio and toggle interaction state. The article is a focused reference for game UI, where scene-graph controls need explicit hit testing and state transitions rather than UIKit’s responder behavior.
- [Box2D Tutorial for iOS: How to Use Box2D For Just Collision Detection With Cocos2D iPhone | Kodeco](https://www.kodeco.com/3144-box2d-tutorial-for-ios-how-to-use-box2d-for-just-collision-detection-with-cocos2d-iphone) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Box2D is used as a collision-only physics layer inside a Cocos2D game. Follow it to see how simulation geometry can stay separate from sprites, while tuning fixtures and callbacks for predictable gameplay behavior.
- [Three20 Tutorial for iOS | Kodeco](https://www.kodeco.com/3143-three20-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces the historical Three20 iOS library and its application helpers. Useful only for maintaining legacy projects that still depend on its bundled UI and networking abstractions.
- [XML Tutorial for iOS: How To Read and Write XML Documents with GDataXML | Kodeco](https://www.kodeco.com/3140-xml-tutorial-for-ios-how-to-read-and-write-xml-documents-with-gdataxml) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses GDataXML to parse and generate XML documents in iOS. Follow it when integrating older XML services, especially where node traversal, namespaces, and serialization decisions matter more than JSON convenience.
- [iPad Tutorial for iOS: How To Port an iPhone Application to the iPad | Kodeco](https://www.kodeco.com/3127-ipad-tutorial-for-ios-how-to-port-an-iphone-application-to-the-ipad) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adapts an iPhone app to iPad with autosizing, split views, detail coordination, and popover navigation. Useful as a historical design exercise in separating compact and regular-width behaviors instead of stretching one phone layout across both devices.
- [Three20 Tutorial for iOS: How To Use the Three20 Photo Viewer | Kodeco](https://www.kodeco.com/3123-three20-tutorial-for-ios-how-to-use-the-three20-photo-viewer) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Three20's photo viewer in an iOS app. Useful historical context when replacing or maintaining a legacy gallery component with its own navigation and caching behavior.
- [Drag and Drop Tutorial for iOS | Kodeco](https://www.kodeco.com/3121851-drag-and-drop-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** UIKit drag and drop connects session delegates, item providers and destination handling. The tutorial is useful for understanding data representation across app boundaries, including why a drop should not assume local object identity.
- [Google Translate Tutorial for iOS: How To Translate Text With Google Translate and JSON on the iPhone | Kodeco](https://www.kodeco.com/3121-google-translate-tutorial-for-ios-how-to-translate-text-with-google-translate-and-json-on-the-iphone) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A translation client parses JSON responses from a remote service and updates an iOS interface. It is useful for tracing request, decoding and presentation seams, while remembering that third-party API credentials need a protected backend.
- [Facebook Tutorial for iOS: How To Use Facebook’s New Graph API from your iPhone App | Kodeco](https://www.kodeco.com/3120-facebook-tutorial-for-ios-how-to-use-facebook-s-new-graph-api-from-your-iphone-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This legacy Graph API tutorial sends requests from an iOS app and parses social responses. It is useful for migration archaeology, emphasizing that authentication, permissions and response mapping belong behind a service boundary.
- [Facebook Tutorial for iOS: How To Post to a User’s Wall, Upload Photos, and Add a Like Button from your iPhone App | Kodeco](https://www.kodeco.com/3117-facebook-tutorial-for-ios-how-to-post-to-a-user-s-wall-upload-photos-and-add-a-like-button-from-your-iphone-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This legacy Facebook Graph API example combines posting, photo upload and social actions. It is useful chiefly for migration archaeology: external authentication, permissions and platform APIs should not be embedded in view controllers.
- [iOS Tutorial: How To Create A Simple iPhone App: Part 1/3 | Kodeco](https://www.kodeco.com/3114-ios-tutorial-how-to-create-a-simple-iphone-app-part-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a table-based bug list around a model object, custom data, and images. Useful for recognizing the basic separation between a table view's presentation and the model records it renders in a UIKit application.
- [iOS Tutorial: How To Create A Simple iPhone App Tutorial: Part 2/3 | Kodeco](https://www.kodeco.com/3113-ios-tutorial-how-to-create-a-simple-iphone-app-tutorial-part-2-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds a storyboard-backed detail controller, downloads supporting content, and integrates it with a table selection. Useful for tracing the handoff from a list to a detail screen when navigation needs to carry a chosen model object.
- [iOS Tutorial: How To Create A Simple iPhone App Tutorial: Part 3/3 | Kodeco](https://www.kodeco.com/3112-ios-tutorial-how-to-create-a-simple-iphone-app-tutorial-part-3-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Completes a simple UIKit app with record insertion, deletion, app artwork, and a long-running operation. Useful for seeing the practical UI and lifecycle work that surrounds basic CRUD beyond merely displaying a static table.
- [iTunes Tutorial for iOS: How To Integrate iTunes File Sharing With Your iOS App | Kodeco](https://www.kodeco.com/3110-itunes-tutorial-for-ios-how-to-integrate-itunes-file-sharing-with-your-ios-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains iTunes File Sharing, document packages, and import/export integration for an app's files. Useful for maintaining legacy document workflows where users need direct desktop access to files without building a separate synchronization service.
- [CALayers Tutorial for iOS: Introduction to CALayers | Kodeco](https://www.kodeco.com/3096-calayers-tutorial-for-ios-introduction-to-calayers) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** CALayer fundamentals show how backing layers own geometry, drawing and compositing beneath UIView. Follow it to decide when layer properties are preferable to view subclasses for animation and visual effects.
- [Memory Management Tutorial for iOS | Kodeco](https://www.kodeco.com/3090-memory-management-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains manual retain/release, autorelease pools, reference counts, and ownership conventions. Useful when reading older Objective-C code or interpreting historical memory-management APIs that predate ARC's automatic ownership insertion.
- [How to Write an iOS App That Uses a Web Service | Kodeco](https://www.kodeco.com/3088-how-to-write-an-ios-app-that-uses-a-web-service) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A classic web-service client traces request construction, JSON handling and UI updates in an iOS app. It remains useful for identifying coupling points that modern async networking layers should isolate behind a testable service boundary.
- [Properties Tutorial for iOS | Kodeco](https://www.kodeco.com/3086-properties-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains Objective-C property declarations, synthesized accessors, memory attributes, and their use in a Cocos2D project. Useful for deciphering pre-ARC code where property semantics determine whether an object is retained, copied, or merely referenced.
- [Pulse SDK Integration Tutorial for iOS: Network Logger | Kodeco](https://www.kodeco.com/30189310-pulse-sdk-integration-tutorial-for-ios-network-logger) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Integrates Pulse and SwiftLog, adds structured messages and metadata, then captures URLSession traffic through delegate hooks. Useful for deciding where diagnostic logging belongs so network and application events can be inspected together without ad-hoc print statements.
- [iOS For High School Students: Getting Started | Kodeco](https://www.kodeco.com/2986-ios-for-high-school-students-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces a console-style iOS programming project through variables, input, conditionals, loops, and input validation. Useful for grounding beginner control-flow reasoning in executable behavior instead of presenting syntax without a problem-solving context.
- [How To Create a PDF with Quartz 2D in iOS 5 – Part 1 | Kodeco](https://www.kodeco.com/2976-how-to-create-a-pdf-with-quartz-2d-in-ios-5-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Quartz 2D PDF generation shows how pages, graphics contexts and text drawing are assembled manually. Follow it when maintaining old export code, where coordinate systems and pagination remain the core correctness issues.
- [How To Create a PDF with Quartz 2D in iOS 5 – Part 2 | Kodeco](https://www.kodeco.com/2974-how-to-create-a-pdf-with-quartz-2d-in-ios-5-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Quartz 2D PDF generation is completed with additional drawing and page handling. It is useful for maintaining old exporters, where deterministic pagination and graphics-context lifetime remain the key correctness boundaries.
- [Swizzling in iOS 11 With UIDebuggingInformationOverlay | Kodeco](https://www.kodeco.com/295-swizzling-in-ios-11-with-uidebugginginformationoverlay) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores method swizzling with UIKit's debugging overlay. Useful for understanding runtime replacement risks while keeping private debugging hooks out of production design.
- [How to Parse HTML on iOS | Kodeco](https://www.kodeco.com/2899-how-to-parse-html-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** HTML parsing on iOS converts remote markup into structured values for app use. Follow it to examine parser and sanitization boundaries, while preferring documented APIs and a backend when source pages or credentials are not under your control.
- [Cómo Crear Una Aplicación Simple para iPhone en iOS 5: Parte 1/3 | Kodeco](https://www.kodeco.com/2887-como-crear-una-aplicacion-simple-para-iphone-en-ios-5-parte-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Begins a Spanish three-part iPhone app tutorial with a table view and an organized model. Useful historical context for seeing a small UIKit screen emerge from basic model and list responsibilities.
- [watchOS 4 Tutorial Part 2: Tables | Kodeco](https://www.kodeco.com/288-watchos-4-tutorial-part-2-tables) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements table-based interfaces in watchOS 4. It is useful for understanding row reuse, constrained display space, and selection behavior in an older WatchKit navigation model.
- [watchOS 4 Tutorial Part 1: Getting Started | Kodeco](https://www.kodeco.com/287-watchos-4-tutorial-part-1-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces a watchOS 4 project, scenes, and basic WatchKit interaction. Follow it for historical maintenance where extension lifecycle and companion-app assumptions still shape the target.
- [Beginning Passbook in iOS 6: Part 1/2 | Kodeco](https://www.kodeco.com/2855-beginning-passbook-in-ios-6-part-1-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Passbook introduction builds and signs a pass payload for system presentation. It is a historical reference for identifiers, certificates and Wallet handoff boundaries, not a recipe for current pass integrations.
- [Beginning Passbook in iOS 6: Part 2/2 | Kodeco](https://www.kodeco.com/2853-beginning-passbook-in-ios-6-part-2-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Passbook continuation handles creating and presenting a pass payload. Follow it as a historical reference for signing, identifiers and system presentation boundaries, rather than as a current Wallet integration recipe.
- [iPad for iPhone Developers 101 in iOS 6: UISplitView Tutorial | Kodeco](https://www.kodeco.com/2759-ipad-for-iphone-developers-101-in-ios-6-uisplitview-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates a split-view interface with custom controllers, a master-detail model, toolbar, popover list, and navigation alternative. Useful for understanding the coordination work required when a regular-width iPad layout exposes two related panes together.
- [iPad for iPhone Developers 101 in iOS 6: UIPopoverController Tutorial | Kodeco](https://www.kodeco.com/2758-ipad-for-iphone-developers-101-in-ios-6-uipopovercontroller-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements a popover-backed color picker and connects its presentation to application code. Useful historical context for maintaining pre-adaptive UIKit interfaces where a transient iPad selection surface had its own controller and dismissal behavior.
- [Overview of iOS Crash Reporting Tools: Part 1/2 | Kodeco](https://www.kodeco.com/2721-overview-of-ios-crash-reporting-tools-part-1-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains crash-report symbolication, dSYM discovery, and the evaluation criteria for hosted crash reporters. Useful for understanding the durable diagnostic pipeline behind any crash service, even though the named vendor landscape is historical.
- [How To Make a Music Visualizer in iOS | Kodeco](https://www.kodeco.com/2714-how-to-make-a-music-visualizer-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A music visualizer samples audio levels and turns them into animated graphics. Follow it to understand signal-to-UI smoothing and display-rate constraints, rather than mapping every audio callback directly to a view update.
- [Fat Fractal Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/2693-fat-fractal-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Fat Fractal as a backend data service for iOS. Useful historical context for evaluating how mobile object persistence, sync, and remote queries were packaged together.
- [Learn to Code iOS Apps 1: Welcome to Programming | Kodeco](https://www.kodeco.com/2690-learn-to-code-ios-apps-1-welcome-to-programming) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Walks through program structure, imports, variables, input, conditionals, and loops in a first small game. Useful for a beginner who needs to connect each language construct to execution flow instead of learning declarations in isolation.
- [Learn to Code iOS Apps 2: Strings, Arrays, Objects and Classes | Kodeco](https://www.kodeco.com/2689-learn-to-code-ios-apps-2-strings-arrays-objects-and-classes) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces objects, strings, NSString bridging, instance methods, sets, and arrays through a game project. Useful for understanding how collection and object choices affect the operations a small program can express.
- [How To Write A Simple Node.js/MongoDB Web Service for an iOS App | Kodeco](https://www.kodeco.com/2663-how-to-write-a-simple-node-js-mongodb-web-service-for-an-ios-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a Node.js and MongoDB web service for an iOS client. Useful for clarifying the API and persistence boundary behind mobile data.
- [How to Update Your App for iOS 7 | Kodeco](https://www.kodeco.com/2641-how-to-update-your-app-for-ios-7) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Walks through adapting an app to an iOS release. Useful for separating visual changes, API availability, and compatibility testing during platform upgrades.
- [Storyboards Tutorial in iOS 7: Part 1 | Kodeco](https://www.kodeco.com/2624-storyboards-tutorial-in-ios-7-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds storyboard scenes and navigation relationships. Useful for understanding how UIKit controller topology is encoded in Interface Builder.
- [ShazamKit Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/26236685-shazamkit-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses ShazamKit to recognize audio signatures. Useful for modeling catalog matching, recognition results, and user feedback around an audio-identification feature.
- [Storyboards Tutorial in iOS 7: Part 2 | Kodeco](https://www.kodeco.com/2623-storyboards-tutorial-in-ios-7-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Continues storyboard integration with concrete controller and segue behavior. Useful for tracing data handoff between scenes without hidden global state.
- [Easily Overlooked New Features in iOS 7 | Kodeco](https://www.kodeco.com/2587-easily-overlooked-new-features-in-ios-7) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This iOS 7 survey records small platform additions that affected navigation, multitasking and UI behavior. It is mainly a legacy compatibility reference, useful when explaining why older code contains seemingly unnecessary availability branches.
- [Google Analytics for iOS | Kodeco](https://www.kodeco.com/2583-google-analytics-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Google Analytics integration records events and screen activity from an iOS app. Its durable lesson is instrumentation boundaries: define a stable event schema and keep analytics calls out of core UI behavior.
- [iOS 7 Best Practices; A Weather App Case Study: Part 1/2 | Kodeco](https://www.kodeco.com/2579-ios-7-best-practices-a-weather-app-case-study-part-1-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Sets up a weather app with CocoaPods, view structure, remote weather retrieval, and a model layer. Useful as a case study in making dependencies and data transformation explicit before reactive bindings are layered onto the interface.
- [iOS 7 Best Practices; A Weather App Case Study: Part 2/2 | Kodeco](https://www.kodeco.com/2578-ios-7-best-practices-a-weather-app-case-study-part-2-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds ReactiveCocoa signals for weather requests, location, persistence, table binding, and UI updates. Useful for examining where reactive state reduces glue code and where it can obscure ownership if signal lifetimes are not carefully modeled.
- [Contacts Framework Tutorial for iOS | Kodeco](https://www.kodeco.com/2547730-contacts-framework-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Contacts framework tutorial queries and edits user records through permission-gated APIs. Follow it to understand predicates, containers and change requests, keeping contact identity and authorization outside presentation code.
- [Internationalizing Your iOS App: Getting Started | Kodeco](https://www.kodeco.com/250-internationalizing-your-ios-app-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Externalizes strings, localizes storyboards and images, formats numbers, and handles plurals across languages. Useful for locating the assumptions that make a UI nonportable before localization becomes a late-stage collection of clipped labels and hard-coded text.
- [How to Write An iOS App that Uses a Node.js/MongoDB Web Service | Kodeco](https://www.kodeco.com/2441-how-to-write-an-ios-app-that-uses-a-node-js-mongodb-web-service) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects an iOS client to a Node.js and MongoDB service. Useful for tracing request serialization, remote data, and app-side presentation boundaries.
- [Internationalization Tutorial for iOS [2014 Edition] | Kodeco](https://www.kodeco.com/2438-internationalization-tutorial-for-ios-2014-edition) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Separates text from code, localizes storyboards and images, and distinguishes locale from language. Useful for identifying the resource-boundary decisions that make an older iOS interface adaptable to new languages without duplicating its code paths.
- [Audio Tutorial for iOS: File and Data Formats [2014 Edition] | Kodeco](https://www.kodeco.com/2434-audio-tutorial-for-ios-file-and-data-formats-2014-edition) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains audio file and data formats on iOS. Useful for choosing a format based on encoding, metadata, playback, and storage constraints.
- [Audio Tutorial for iOS: Converting and Recording [2014 Edition] | Kodeco](https://www.kodeco.com/2432-audio-tutorial-for-ios-converting-and-recording-2014-edition) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This audio tutorial covers recording and format conversion through older iOS APIs. It remains useful for understanding sample-rate, codec and file-container choices, while modern implementations should use AVAudioEngine or AVAssetExportSession.
- [Audio Tutorial for iOS: Playing Audio Programatically [2014 Edition] | Kodeco](https://www.kodeco.com/2431-audio-tutorial-for-ios-playing-audio-programatically-2014-edition) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Plays audio programmatically through iOS audio APIs. Useful for separating session setup, playback control, and interruption behavior in a media feature.
- [How to Create a Framework for iOS | Kodeco](https://www.kodeco.com/2430-how-to-create-a-framework-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This framework tutorial packages reusable iOS code behind a module boundary. It is useful for legacy distribution and API-surface review, where resources, visibility and binary compatibility impose constraints beyond source-level reuse.
- [IRC for iOS Developers | Kodeco](https://www.kodeco.com/2322-irc-for-ios-developers) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Compares IRC clients, channels, and collaboration etiquette for iOS developers. Useful as historical community-routing material when researching where platform discussions occurred, rather than as a technical protocol implementation guide.
- [Core Bluetooth Tutorial for iOS: Heart Rate Monitor | Kodeco](https://www.kodeco.com/231-core-bluetooth-tutorial-for-ios-heart-rate-monitor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A Core Bluetooth heart-rate monitor discovers a peripheral, subscribes to characteristic notifications and parses measurements. Follow it to separate radio connection state from decoded domain values, especially across reconnects and background limits.
- [Arduino Tutorial: Integrating Bluetooth LE and iOS | Kodeco](https://www.kodeco.com/2295-arduino-tutorial-integrating-bluetooth-le-and-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Arduino BLE integration demonstrates advertising, characteristic reads and writes between hardware and iOS. It is useful for defining a compact protocol and handling unreliable transport without coupling device timing to the app’s view state.
- [Advanced Charles Proxy Tutorial for iOS | Kodeco](https://www.kodeco.com/22070831-advanced-charles-proxy-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Charles Proxy techniques expose request timing, headers and payloads during iOS development. Follow it to separate client serialization bugs from transport or server behavior, while keeping certificate trust and sensitive-data capture controlled.
- [UIStackView Tutorial for iOS: Introducing Stack Views | Kodeco](https://www.kodeco.com/2198310-uistackview-tutorial-for-ios-introducing-stack-views) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses UIStackView to arrange UIKit views with distribution and alignment rules. Useful for reducing constraint boilerplate while retaining adaptable layout behavior.
- [Background Tasks in iOS | Kodeco](https://www.kodeco.com/21242372-background-tasks-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Background task APIs are used to schedule work outside the foreground lifecycle. The guide helps distinguish refresh, processing and URL-session use cases, where expiration handling and limited execution time must shape the operation design.
- [Lessons Learned from Running an iOS Consultancy: Part 1 | Kodeco](https://www.kodeco.com/2100-lessons-learned-from-running-an-ios-consultancy-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shares consultancy lessons about focus, partners, and investors from an iOS business. Useful for a technical freelancer who needs to connect delivery decisions with a sustainable client relationship.
- [SF Symbols for iOS: Getting Started | Kodeco](https://www.kodeco.com/20948225-sf-symbols-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces SF Symbols for semantic iOS icons. Useful for choosing system-provided images that inherit platform weight, scale, and accessibility behavior.
- [How to Port Your App to the iPhone 6, iPhone 6 Plus and iOS 8: Top 10 Tips | Kodeco](https://www.kodeco.com/2079-how-to-port-your-app-to-the-iphone-6-iphone-6-plus-and-ios-8-top-10-tips) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This porting checklist captures the transition to larger iPhone sizes and adaptive layout. It remains a useful compatibility audit for legacy interfaces, especially where hard-coded screen dimensions still leak into constraints or assets.
- [App Clips in iOS | Kodeco](https://www.kodeco.com/20781268-app-clips-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** App Clips are introduced as a lightweight entry point for task-based experiences without a full install. The design trade-off is explicit: keep code, data and onboarding small while handing off cleanly to the installed app when the task grows.
- [Smart Lighting with HomeKit in watchOS | Kodeco](https://www.kodeco.com/20088887-smart-lighting-with-homekit-in-watchos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects a watchOS app to HomeKit smart-lighting controls. Follow it when designing capability permissions, accessory commands, and compact watch interaction without assuming the phone is always active.
- [Multipeer Connectivity in iOS | Kodeco](https://www.kodeco.com/19987381-multipeer-connectivity-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Multipeer Connectivity for nearby peer discovery, invitations, sessions, and data exchange. Useful for understanding the connection lifecycle and failure modes of local-device collaboration without requiring an internet-hosted server.
- [Kotlin Multiplatform Project for Android and iOS: Getting Started | Kodeco](https://www.kodeco.com/19144111-kotlin-multiplatform-project-for-android-and-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Sets up common Kotlin code with expect declarations, platform implementations, shared networking, and platform-specific persistence. Useful for evaluating Kotlin Multiplatform's actual sharing boundary instead of assuming UI, storage, and native integration become automatically common.
- [Accepting Credit Cards In Your iOS App Using Stripe | Kodeco](https://www.kodeco.com/182-accepting-credit-cards-in-your-ios-app-using-stripe) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Stripe integration demonstrates tokenizing card details before sending payment information to a backend. Follow it for the security boundary: the iOS app should not own raw card data or payment authorization secrets.
- [Integrating Parse and React Native for iOS | Kodeco](https://www.kodeco.com/1729-integrating-parse-and-react-native-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects a React Native property-search interface to Parse schemas, queries, location filtering, and result updates. Useful for seeing how a JavaScript UI still depends on deliberate backend modeling and query behavior when wrapping native app capabilities.
- [tvOS SDK: An iOS Developer’s Initial Impressions | Kodeco](https://www.kodeco.com/1620-tvos-sdk-an-ios-developer-s-initial-impressions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Records an iOS developer’s first observations of the tvOS SDK. Use it as historical context for focus navigation, remote input, and platform differences when adapting an older UIKit app.
- [Beginning tvOS Development with TVML Tutorial | Kodeco](https://www.kodeco.com/1579-beginning-tvos-development-with-tvml-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** TVML separates a tvOS interface description from JavaScript-driven application logic. Follow it to understand the older template-based interaction model and why focus navigation and remote input require different assumptions than touch UI.
- [Chameleon on iOS: Getting Started | Kodeco](https://www.kodeco.com/156-chameleon-on-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Chameleon provides color-scheme helpers for UIKit interfaces. The tutorial is useful for legacy theming review, showing how centralized palette decisions reduce scattered colors but can still conflict with dynamic system appearance.
- [iOS 9 Multitasking Tutorial | Kodeco](https://www.kodeco.com/1540-ios-9-multitasking-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adapts an app for iPad multitasking by handling size changes, adaptive presentation, and layout decisions. Useful for separating responsive layout behavior from device-name checks when windows can be resized or displayed beside another app.
- [iOS 9 Storyboards Tutorial: What’s New in Storyboards? | Kodeco](https://www.kodeco.com/1539-ios-9-storyboards-tutorial-what-s-new-in-storyboards) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses storyboard references and scene-dock tools to split a large interface across files and conditionally manage views. Useful for reducing merge conflicts and navigation complexity when a team maintains a sizeable storyboard-based UIKit application.
- [Preventing Man-in-the-Middle Attacks in iOS with SSL Pinning | Kodeco](https://www.kodeco.com/1484288-preventing-man-in-the-middle-attacks-in-ios-with-ssl-pinning) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains TLS validation and certificate pinning, then implements and tests Alamofire pinning with an intercepting proxy. Useful for assessing the security benefit and operational brittleness of pinning before adding it to an app with rotating backend certificates.
- [App Clips for iOS: Getting Started | Kodeco](https://www.kodeco.com/14455571-app-clips-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds an App Clip entry point and constrained experience. Useful for separating a lightweight, discoverable task flow from the installed app's full navigation and data model.
- [Sketch Tutorial for iOS Developers | Kodeco](https://www.kodeco.com/1379-sketch-tutorial-for-ios-developers) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Sketch workflows relevant to iOS interface design. Useful for translating design assets and layout intent into implementation-ready specifications rather than pixel guessing.
- [CallKit Tutorial for iOS | Kodeco](https://www.kodeco.com/1276414-callkit-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** CallKit integrates calling apps with system phone surfaces and directory extensions. Follow it to understand the entitlement, reporting and extension boundaries that make call identification feel native without granting the app unrestricted telephony control.
- [JavaScriptCore Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/1227-javascriptcore-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses JSVirtualMachine, JSContext, JSValue, and JSExport to invoke JavaScript and expose native Swift or Objective-C capabilities. Useful for evaluating embedded scripting where code execution needs a carefully controlled bridge into application objects.
- [Combine in the raywenderlich.com App | Kodeco](https://www.kodeco.com/10877489-combine-in-the-raywenderlich-com-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This case study shows Combine wiring UserDefaults-backed changes in a real open-source app. It is valuable because it exposes publisher ownership and cancellation in production-shaped code rather than an isolated toy pipeline.
- [Creating a Custom Calendar Control for iOS | Kodeco](https://www.kodeco.com/10787749-creating-a-custom-calendar-control-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The custom calendar control focuses on presenting date context and interaction state clearly, a useful case study for designing a nonstandard UIKit control.
- [Building iOS Apps with Xamarin and Visual Studio | Kodeco](https://www.kodeco.com/1044-building-ios-apps-with-xamarin-and-visual-studio) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Xamarin’s iOS workflow shows how shared C# code reaches Apple UI frameworks through bindings. It is useful for evaluating cross-platform abstraction costs, especially when debugging native lifecycle or platform-specific API behavior.
- [CALayer Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/10317653-calayer-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The CALayer introduction uses shapes, gradients, and particle effects to show how the layer tree can provide rendering capabilities beyond ordinary UIKit views.
- [WWDC 2026 Viewing Guide](https://useyourloaf.com/blog/wwdc-2026-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2026-06-15T10:16:45+01:00`
  **NeKI brief:** Curates WWDC 2026 sessions by technical theme, useful for planning a focused viewing pass and then following the linked Apple sessions for authoritative details.
- [Apple's "Snow Leopard" Year: WWDC 2026 Roundup](https://blog.jacobstechtavern.com/p/wwdc-2026-roundup) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-06-11T12:03:43.079Z`
  **NeKI brief:** Summarizes the author's WWDC 2026 takeaways across Apple-platform announcements and developer tooling. Use it as a discovery index before reading the corresponding sessions and documentation, not as an authoritative feature reference.
- [Schedule a countdown timer with AlarmKit](https://nilcoalescing.com/blog/CountdownTimerWithAlarmKit) — Nil Coalescing · article catalogue
  **Published:** `2026-06-10`
  **NeKI brief:** Schedules a countdown through AlarmKit rather than a foreground-only timer. Use it when an app needs a system-managed alert that survives normal lifecycle interruptions.
- [iPhone 17 Screen Sizes](https://useyourloaf.com/blog/iphone-17-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2025-10-13T10:44:39+01:00`
  **NeKI brief:** Summarizes the 2025 iPhone 17 screen sizes and their display differences. Use it when checking layout assumptions, preview coverage, and responsive constraints for devices introduced with that generation.
- [WWDC 2025 Viewing Guide](https://useyourloaf.com/blog/wwdc-2025-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2025-06-16T09:00:00+01:00`
  **NeKI brief:** Organizes WWDC 2025 sessions into a practical watch list, helping prioritize platform changes before validating implementation details in the corresponding Apple documentation.
- [iPhone 16 Screen Sizes](https://useyourloaf.com/blog/iphone-16-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2024-09-16T10:44:39+01:00`
  **NeKI brief:** Records iPhone 16 point and pixel dimensions, scale factors, size classes, and safe-area insets, including the new Pro sizes and camera-control hardware. Use it as a device-layout reference when validating adaptive constraints and preview coverage.
- [WWDC 2024 Viewing Guide](https://useyourloaf.com/blog/wwdc-2024-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2024-06-17T09:00:00+01:00`
  **NeKI brief:** Organizes WWDC 2024 sessions into a practical watch list, helping prioritize platform changes before validating implementation details in the corresponding Apple documentation.
- [iPad 2024 Screen Sizes](https://useyourloaf.com/blog/ipad-2024-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2024-05-13T10:05:13+01:00`
  **NeKI brief:** Summarizes the 2024 iPad Pro and Air point/pixel sizes, scale factors, size classes, safe areas, and landscape camera changes. Keep it as a concrete geometry reference when testing adaptive layouts across the new 11- and 13-inch models.
- [2 Minute Tips: iOS Springboard Paddling Pool](https://blog.jacobstechtavern.com/p/2-minute-tips-ios-springboard-paddling) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-12-25T11:00:53.989Z`
  **NeKI brief:** Uses SpringBoard's privileged userland role to explain the boundary between iOS applications, syscalls, and the kernel. It is useful platform context for understanding why app metadata and home-screen behavior are unavailable to ordinary third-party code.
- [Registering For Trait Changes](https://useyourloaf.com/blog/registering-for-trait-changes) — Use Your Loaf · article catalogue
  **Published:** `2023-10-30T11:37:54+00:00`
  **NeKI brief:** Replaces broad traitCollectionDidChange handling with iOS 17 registration for specific UITrait changes, then updates only the layout or configuration affected. The narrower invalidation model reduces unnecessary work while keeping adaptive UIKit behavior explicit.
- [iPhone 15 Screen Sizes](https://useyourloaf.com/blog/iphone-15-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2023-09-18T10:13:22+01:00`
  **NeKI brief:** Lists iPhone 15 and Pro dimensions, resolutions, scale factors, size classes, and safe-area differences after Dynamic Island reached every model. Use the measurements to check assumptions that previously depended on the notch or the discontinued mini size.
- [WWDC 2023 Viewing Guide](https://useyourloaf.com/blog/wwdc-2023-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2023-06-12T17:40:20+01:00`
  **NeKI brief:** Maps WWDC23 sessions to focused platform topics so developers can target relevant talks instead of scanning the full catalogue. The guide is a discovery aid; implementation claims still belong to the linked Apple sessions.
- [Context Menus for Tables](https://useyourloaf.com/blog/context-menus-for-tables) — Use Your Loaf · article catalogue
  **Published:** `2023-03-13T10:17:11+00:00`
  **NeKI brief:** Uses iOS 16 item-based context menus on selectable List or Table containers to vary actions with the current selection. This provides batch operations without manually inspecting selection state inside every row’s ordinary long-press menu.
- [iPad Customizable Toolbars](https://useyourloaf.com/blog/ipad-customizable-toolbars) — Use Your Loaf · article catalogue
  **Published:** `2023-02-06T10:20:25+00:00`
  **NeKI brief:** Explains iPadOS 16 toolbar placements for primary, secondary, leading, and trailing actions, then connects them to user-customizable toolbar configuration. Semantic placement lets the system adapt controls across iPad, iPhone, and Mac while preserving action priority.
- [iPhone 14 Screen Sizes](https://useyourloaf.com/blog/iphone-14-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2022-09-12T10:56:55+01:00`
  **NeKI brief:** Records the iPhone 14 generation’s point and pixel dimensions, scale factors, size classes, and safe-area insets, including the Dynamic Island change on Pro models. Use it when legacy device geometry still matters to adaptive layout and regression testing.
- [Experimenting with Live Activities – Ole Begemann](https://oleb.net/2022/live-activity) — Ole Begemann · article catalogue
  **Published:** `2022-08-03T16:50:39Z`
  **NeKI brief:** Experiments with early Live Activities APIs. Use it as historical implementation context, while checking current ActivityKit behavior and system constraints.
- [Move the most recent commits to a new branch with git | Sarunw](https://sarunw.com/posts/move-commits-to-new-branch-in-git) — Sarunw · article catalogue
  **Published:** `2022-07-28`
  **NeKI brief:** Moves recent commits onto a new Git branch, preserving shared history while correcting an accidental branch choice without rewriting collaborators' work.
- [WWDC 2022 Viewing Guide](https://useyourloaf.com/blog/wwdc-2022-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2022-06-13T10:51:03+01:00`
  **NeKI brief:** Maps WWDC22 sessions to focused platform topics, making a large conference catalogue searchable by implementation concern. Use it to select primary sessions, not as a substitute for reading API-specific evidence.
- [Should every if statement has an else clause | Sarunw](https://sarunw.com/posts/should-every-if-statement-has-else-clause) — Sarunw · article catalogue
  **Published:** `2021-10-07`
  **NeKI brief:** Discusses when an if branch needs an explicit else, distinguishing exhaustive state handling from guard-style side effects so control flow remains readable and intentional.
- [iPhone 13 Screen Sizes](https://useyourloaf.com/blog/iphone-13-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2021-09-20T10:52:43+01:00`
  **NeKI brief:** Records iPhone 13 display dimensions and scale information for layout and asset decisions. Prefer adaptive constraints over hard-coded sizes; the table is a reference for validating assumptions, not a design target.
- [iPad 2021 Screen Sizes](https://useyourloaf.com/blog/ipad-2021-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2021-09-17T12:18:47+01:00`
  **NeKI brief:** Summarizes 2021 iPad screen sizes and resolutions to support asset and interface testing. Device tables help reproduce edge cases, but size classes and dynamic type should drive production layout decisions.
- [Stack View Changes In iOS 15](https://useyourloaf.com/blog/stack-view-changes-in-ios-15) — Use Your Loaf · article catalogue
  **Published:** `2021-09-13T10:07:30+01:00`
  **NeKI brief:** Reviews iOS 15 stack-view behavior changes, helping diagnose layout regressions where intrinsic sizing or spacing assumptions no longer hold.
- [Button Configuration in iOS 15](https://useyourloaf.com/blog/button-configuration-in-ios-15) — Use Your Loaf · article catalogue
  **Published:** `2021-08-30T10:24:24+01:00`
  **NeKI brief:** Introduces UIButton.Configuration as a state-aware replacement for scattered title, image, and inset mutations. Configuration centralizes visual states and makes updates predictable, but custom drawing may still require a bespoke control.
- [How to share an iOS distribution certificate | Sarunw](https://sarunw.com/posts/how-to-share-ios-distribution-certificate) — Sarunw · article catalogue
  **Published:** `2021-06-28`
  **NeKI brief:** A distribution certificate requires its private key as well as the certificate file, so export and import it through Keychain only within an authorized team workflow. Prefer managed signing or an encrypted credential store, and never treat a certificate file alone as deployable signing access.
- [WWDC 2021 Viewing Guide](https://useyourloaf.com/blog/wwdc-2021-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2021-06-14T13:42:45+01:00`
  **NeKI brief:** Organizes WWDC21 sessions around SwiftUI, concurrency, and platform changes so teams can prioritize relevant talks. Follow linked Apple sessions for exact availability and migration details before coding.
- [The iOS Developer’s guide to WWDC 2024 – Donny Wals](https://www.donnywals.com/the-ios-developers-guide-to-wwdc-2024) — Donny Wals · article catalogue
  **Published:** `2021-05-31T12:53:39+00:00`
  **NeKI brief:** Treat WWDC as a triage exercise: filter sessions by active product needs, prioritize documentation and sample code, then schedule deliberate exploration instead of attempting to consume every announcement.
- [How to set up iOS environments: develop, staging, and production | Sarunw](https://sarunw.com/posts/how-to-set-up-ios-environments) — Sarunw · article catalogue
  **Published:** `2021-05-10`
  **NeKI brief:** Model development, staging, and production as explicit build configurations and shared schemes, with xcconfig values feeding configuration-specific settings. Keep environment endpoints and identifiers out of source literals, and ensure CI selects the same scheme and configuration deliberately.
- [Using App Store Connect API with Fastlane Match | Sarunw](https://sarunw.com/posts/using-app-store-connect-api-with-fastlane-match) — Sarunw · article catalogue
  **Published:** `2021-02-22`
  **NeKI brief:** Provide fastlane match with an App Store Connect API key through scoped environment-backed configuration, then use read-only signing access for routine CI lanes. Keep issuer, key identifier, and private key material out of the repository and handle encoded key content deliberately.
- [iPhone 12 Screen Sizes](https://useyourloaf.com/blog/iphone-12-screen-sizes) — Use Your Loaf · article catalogue
  **Published:** `2020-10-19T10:39:13+01:00`
  **NeKI brief:** Records iPhone 12 display metrics for validating layout and asset assumptions. Use the values to reproduce device-specific tests, but rely on size classes and adaptive constraints in production.
- [Stack View Background Color in iOS 14](https://useyourloaf.com/blog/stack-view-background-color-in-ios-14) — Use Your Loaf · article catalogue
  **Published:** `2020-08-17T13:16:09+01:00`
  **NeKI brief:** Shows why a stack view's background may need an explicit container or layout treatment rather than relying on arranged subviews. Separating visual background ownership prevents unexpected clipping and makes spacing behavior clearer.
- [WWDC 2020 Viewing Guide](https://useyourloaf.com/blog/wwdc-2020-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2020-06-29T16:44:01+01:00`
  **NeKI brief:** Indexes WWDC20 sessions by technology so a team can build a focused learning path instead of scanning every talk. Treat it as navigation to primary material, with availability checked against the current SDK.
- [WWDC 2020 - NSHipster](https://nshipster.com/wwdc-2020) — NSHipster · article catalogue
  **Published:** `2020-06-26T00:00:00-07:00`
  **NeKI brief:** This WWDC20 survey highlights platform APIs and development themes from that release. Use it as historical orientation for legacy code, checking current SDK documentation and availability before adopting any described approach.
- [How to change a UICollectionViewListCell’s separator inset – Donny Wals](https://www.donnywals.com/how-to-change-a-uicollectionviewlistcells-separator-inset) — Donny Wals · article catalogue
  **Published:** `2020-06-25T17:08:10+00:00`
  **NeKI brief:** List-cell separator insets are configured through the collection-list appearance APIs, keeping alignment consistent with custom content margins and layout direction.
- [How to set cornerRadius for only some corners | Sarunw](https://sarunw.com/posts/how-to-set-corner-radius-for-some-corners) — Sarunw · article catalogue
  **Published:** `2020-05-13`
  **NeKI brief:** Round selected UIKit corners with CALayer maskedCorners on supported systems, or derive a UIBezierPath mask after bounds are final. Reapply path-based masks during layout changes, since creating them before final sizing produces incorrect geometry.
- [History of Auto Layout constraints | Sarunw](https://sarunw.com/posts/history-of-auto-layout-constraints) — Sarunw · article catalogue
  **Published:** `2020-04-29`
  **NeKI brief:** Prefer modern Auto Layout anchors or constraint activation APIs over older verbose construction and third-party wrappers when standard APIs express the relationship clearly. Keep constraints grouped by layout intent, so changes reveal which spacing, alignment, or size rule is responsible.
- [Cross-Pollination - NSHipster](https://nshipster.com/cross-pollination) — NSHipster · article catalogue
  **Published:** `2020-04-22T00:00:00-07:00`
  **NeKI brief:** This essay connects SwiftUI and Combine to ideas familiar from React and Elm, then examines how function builders and Objective-C generics crossed ecosystem boundaries. Follow it as design context, not as API documentation.
- [Contact Tracing - NSHipster](https://nshipster.com/contact-tracing) — NSHipster · article catalogue
  **Published:** `2020-04-13T00:00:00-07:00`
  **NeKI brief:** The Apple-Google exposure-notification design keeps contact events as rotating identifiers and performs matching on-device, reducing central knowledge of users. The article is a historical trade-off study in privacy, Bluetooth limits, and public-health utility.
- [tintColor | Sarunw](https://sarunw.com/posts/tintcolor) — Sarunw · article catalogue
  **Published:** `2020-03-25`
  **NeKI brief:** Use UIKit tintColor as an inherited semantic accent, overriding it at the narrowest view or window scope that matches the intended theme. Custom views that derive their rendering from tint should respond in tintColorDidChange rather than caching the initial color.
- [Adding Context Menus In iOS 13](https://useyourloaf.com/blog/adding-context-menus-in-ios-13) — Use Your Loaf · article catalogue
  **Published:** `2020-01-06T20:33:28+00:00`
  **NeKI brief:** Adds UIKit context menus with preview and action providers, letting the system present secondary actions on demand. Menu actions should mirror visible affordances and remain accessible to users without pointer interaction.
- [Getting started with Combine – Donny Wals](https://www.donnywals.com/an-introduction-to-combine) — Donny Wals · article catalogue
  **Published:** `2020-01-06T08:10:33+00:00`
  **NeKI brief:** Combine models asynchronous values as composable publisher chains, but subscriptions, cancellation, schedulers, and failure types remain essential design choices.
- [Sign in with Apple Tutorial, Part 2: Private Email Relay Service | Sarunw](https://sarunw.com/posts/sign-in-with-apple-2) — Sarunw · article catalogue
  **Published:** `2019-12-22`
  **NeKI brief:** Explains Sign in with Apple's private email relay implications and user-facing account data. Follow it when storing identity attributes and designing communication paths that do not assume a real email address.
- [Modern table views with diffable data sources – Donny Wals](https://www.donnywals.com/modern-table-views-with-diffable-data-sources) — Donny Wals · article catalogue
  **Published:** `2019-12-21T08:00:29+00:00`
  **NeKI brief:** Introduces diffable data sources as a snapshot-driven replacement for manually coordinated table updates. The article connects stable identifiers and snapshot application to fewer invalid-update crashes in UIKit list screens.
- [// MARK: - What is it? | Sarunw](https://sarunw.com/posts/mark-what-is-it) — Sarunw · article catalogue
  **Published:** `2019-11-14`
  **NeKI brief:** Explains how // MARK comments create named sections in Xcode's source navigator and jump menu, including common variations. It is a small but concrete organization technique for separating extensions, lifecycle code, and feature areas without affecting runtime behavior.
- [Adding support for multiple windows to your iPadOS app – Donny Wals](https://www.donnywals.com/adding-support-for-multiple-windows-to-your-ipados-app) — Donny Wals · article catalogue
  **Published:** `2019-11-04T08:00:26+00:00`
  **NeKI brief:** iPadOS multi-window support moves state and navigation into per-scene lifecycles, requiring each window to restore independently rather than sharing one global UI.
- [Modality changes in iOS13 | Sarunw](https://sarunw.com/posts/modality-changes-in-ios13) — Sarunw · article catalogue
  **Published:** `2019-09-01`
  **NeKI brief:** Explains iOS 13's default card-style modal presentation and how it changes dismissal behavior. Use it when migrating UIKit or SwiftUI flows that relied on full-screen assumptions or custom interactive transitions.
- [WWDC 2019 Viewing Guide](https://useyourloaf.com/blog/wwdc-2019-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2019-06-10T10:05:52+01:00`
  **NeKI brief:** Indexes WWDC19 sessions by technology to create a focused learning route. Use it to find primary demonstrations, then verify API availability and behavior against current SDK documentation.
- [Declarative Views | Cocoa with Love](https://www.cocoawithlove.com/blog/declarative-views.html) — Cocoa with Love · article catalogue
  **Published:** `2019-05-03`
  **NeKI brief:** Explores declarative view construction and the state-to-rendering relationship behind it. Follow it when designing UIKit abstractions that aim to reduce imperative mutation without adopting SwiftUI wholesale.
- [Upside Down and Rotating iPhones](https://useyourloaf.com/blog/upside-down-and-rotating-iphones) — Use Your Loaf · article catalogue
  **Published:** `2018-11-12T13:33:08+00:00`
  **NeKI brief:** Explains orientation handling and the constraints around upside-down iPhone support. Treat rotation as a trait-and-layout event, not a manual frame rewrite, so scenes remain correct across device families.
- [Supporting New iPad Pro Models](https://useyourloaf.com/blog/supporting-new-ipad-pro-models) — Use Your Loaf · article catalogue
  **Published:** `2018-11-04T14:46:55+00:00`
  **NeKI brief:** Uses adaptive layout principles when new iPad Pro sizes arrive instead of adding device checks. Size classes, safe areas, and dynamic constraints provide a durable baseline for unfamiliar hardware.
- [Supporting iPhone XS Max and XR](https://useyourloaf.com/blog/supporting-iphone-xs-max-and-xr) — Use Your Loaf · article catalogue
  **Published:** `2018-09-17T10:25:18+01:00`
  **NeKI brief:** Uses adaptive constraints and safe-area layout to support iPhone XS Max and XR display differences. Avoid device-name branching; test the content's actual compression and expansion behavior.
- [A Farewell to StreamToMe | Cocoa with Love](https://www.cocoawithlove.com/blog/a-farewell-to-streamtome.html) — Cocoa with Love · article catalogue
  **Published:** `2018-09-04`
  **NeKI brief:** Removing a profitable app illustrates the maintenance burden of support, platform changes, and neglected quality; withdrawal can be a deliberate product decision when operational cost outweighs revenue.
- [Why you’re not supposed to call description – Ole Begemann](https://oleb.net/2018/dont-call-description) — Ole Begemann · article catalogue
  **Published:** `2018-08-31T19:57:26Z`
  **NeKI brief:** `CustomStringConvertible` documents a textual representation, but calling `description` directly bypasses formatting conventions and overload resolution. `String(describing:)` is the stable entry point when diagnostics should respect the value's printable contract.
- [Readable Width Table Views With iOS 12](https://useyourloaf.com/blog/readable-width-table-views-with-ios-12) — Use Your Loaf · article catalogue
  **Published:** `2018-07-09T11:43:01+01:00`
  **NeKI brief:** Configures table view content for readable width on larger screens. Use it when iPad layouts need controlled text measure rather than rows stretching edge to edge.
- [How I do analytics – Ole Begemann](https://oleb.net/blog/2018/05/how-i-do-analytics) — Ole Begemann · article catalogue
  **Published:** `2018-05-25T07:25:07Z`
  **NeKI brief:** Analytics instrumentation is more reliable when events are modeled and emitted through one small boundary instead of scattered string literals. The workflow balances useful product signals against privacy, sampling, and the maintenance cost of event schemas.
- [Supporting iPhone X](https://useyourloaf.com/blog/supporting-iphone-x) — Use Your Loaf · article catalogue
  **Published:** `2017-09-18T15:27:35+01:00`
  **NeKI brief:** Explains adapting UIKit layouts for iPhone X safe areas, insets, and screen geometry. Follow it when auditing edge-to-edge interfaces and replacing fixed assumptions about status bars or home indicators.
- [WWDC 2017 Viewing Guide](https://useyourloaf.com/blog/wwdc-2017-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2017-06-12T19:22:21+01:00`
  **NeKI brief:** Guides developers through WWDC 2017 sessions and viewing priorities. Use it as a dated session index for historical platform research, not current API advice.
- [Enums, Equatable, and exhaustiveness – Ole Begemann](https://oleb.net/blog/2017/03/enums-equatable-exhaustiveness) — Ole Begemann · article catalogue
  **Published:** `2017-03-06T17:57:40Z`
  **NeKI brief:** Enums with associated values can implement Equatable by comparing cases and payloads explicitly, while exhaustive switching keeps new cases visible to the compiler. The pattern avoids generated boilerplate without hiding model evolution.
- [Optionals and String Interpolation – Ole Begemann](https://oleb.net/blog/2016/12/optionals-string-interpolation) — Ole Begemann · article catalogue
  **Published:** `2016-12-07T16:38:07Z`
  **NeKI brief:** Explains surprising optional interpolation diagnostics and defines a custom fallback operator for nil values. Use it when auditing user-facing strings so missing data produces intentional text instead of debug-style optional descriptions.
- [Refresh Control Changes in iOS 10](https://useyourloaf.com/blog/refresh-control-changes-in-ios-10) — Use Your Loaf · article catalogue
  **Published:** `2016-11-28T16:35:53+00:00`
  **NeKI brief:** Covers the iOS 10 refresh-control API changes and integration points for scroll views. Refresh completion must follow actual data completion, otherwise the control communicates a misleading loading state.
- [Local Notifications with iOS 10](https://useyourloaf.com/blog/local-notifications-with-ios-10) — Use Your Loaf · article catalogue
  **Published:** `2016-10-31T12:09:12+01:00`
  **NeKI brief:** Schedules local notifications with the UserNotifications framework and separates request content from trigger timing. Permissions, delivery conditions, and deep-link routing need handling independently from scheduling.
- [Generic Range Algorithms – Ole Begemann](https://oleb.net/blog/2016/10/generic-range-algorithms) — Ole Begemann · article catalogue
  **Published:** `2016-10-13T18:48:10Z`
  **NeKI brief:** Generic range algorithms can operate over collection indices without assuming integer offsets, preserving correctness for slices and custom collections. The technique separates traversal guarantees from concrete storage.
- [Measurements and Units with Phantom Types – Ole Begemann](https://oleb.net/blog/2016/08/measurements-and-units-with-phantom-types) — Ole Begemann · article catalogue
  **Published:** `2016-08-22T19:26:00Z`
  **NeKI brief:** Phantom types encode a measurement's unit in the type system while storing the same numeric value, preventing accidental addition of incompatible quantities. The approach trades simple arithmetic for compile-time dimensional safety.
- [Unregistering NSNotificationCenter Observers in iOS 9](https://useyourloaf.com/blog/unregistering-nsnotificationcenter-observers-in-ios-9) — Use Your Loaf · article catalogue
  **Published:** `2016-05-30T14:46:36+01:00`
  **NeKI brief:** Explains NotificationCenter observer lifetime rules and when removal is necessary. Block observers and long-lived registrations need explicit tokens or cleanup, even where selector observers have system-managed behavior.
- [Readable Width of Table View Cells](https://useyourloaf.com/blog/readable-width-of-table-view-cells) — Use Your Loaf · article catalogue
  **Published:** `2016-05-02T10:59:06+01:00`
  **NeKI brief:** Uses readable-content layout guides to limit text line length in wide table cells. This improves typography on iPad while retaining full-width selection and separators where appropriate.
- [Camera.app Pauses Audio Playback – Ole Begemann](https://oleb.net/blog/2016/03/ios-camera-app-pauses-audio-playback) — Ole Begemann · article catalogue
  **Published:** `2016-03-22T16:36:00Z`
  **NeKI brief:** Camera and audio-session interactions reveal that system apps can interrupt an application's playback lifecycle. The observation is useful for designing interruption handling and resumption logic rather than assuming audio ownership is exclusive.
- [More Pattern Matching Examples – Ole Begemann](https://oleb.net/blog/2015/09/more-pattern-matching-examples) — Ole Begemann · article catalogue
  **Published:** `2015-09-30T21:55:00Z`
  **NeKI brief:** Additional pattern-matching examples show how associated values, optionals, and where clauses can express domain conditions together. The technique improves branch clarity when it reflects real alternatives rather than clever syntax.
- [How to Use updateConstraints – Ole Begemann](https://oleb.net/blog/2015/08/how-to-use-updateconstraints) — Ole Begemann · article catalogue
  **Published:** `2015-08-31T21:53:00Z`
  **NeKI brief:** Presents How to Use updateConstraints, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [iOS 9 Proportional Numbers](https://useyourloaf.com/blog/ios-9-proportional-numbers) — Use Your Loaf · article catalogue
  **Published:** `2015-06-29T20:24:12+01:00`
  **NeKI brief:** Uses tabular or proportional numeral font features according to whether changing numbers need alignment. Typography selection affects readability of timers and metrics without changing underlying numeric data.
- [iOS 9 Slide Over and Split View](https://useyourloaf.com/blog/ios-9-slide-over-and-split-view) — Use Your Loaf · article catalogue
  **Published:** `2015-06-15T17:15:08+01:00`
  **NeKI brief:** Adapts iPad interfaces for Slide Over and Split View using traits and responsive constraints. Treat width changes as normal runtime events rather than fixed device modes.
- [UIScreen bounds in iOS 8](https://useyourloaf.com/blog/uiscreen-bounds-in-ios-8) — Use Your Loaf · article catalogue
  **Published:** `2015-06-01T18:38:12+01:00`
  **NeKI brief:** Explains UIScreen bounds changes across orientation and coordinate-space behavior. Layout should use view bounds and safe areas where possible, reserving screen metrics for genuinely screen-level work.
- [The Minus Sign – Ole Begemann](https://oleb.net/blog/2015/02/minus-sign) — Ole Begemann · article catalogue
  **Published:** `2015-02-26T21:40:00Z`
  **NeKI brief:** The Unicode minus sign and ASCII hyphen have different semantics and typography, so formatting numeric output should select a locale-aware representation. The small detail matters for copyable values and consistent UI text.
- [Updating to the iOS 8 Search Controller](https://useyourloaf.com/blog/updating-to-the-ios-8-search-controller) — Use Your Loaf · article catalogue
  **Published:** `2015-02-16T20:13:28+00:00`
  **NeKI brief:** Migrates search interfaces to UISearchController, separating presentation from result updating. Modern search state needs lifecycle-aware ownership so dismissal and restoration do not leave stale filters.
- [Inter-Process Communication - NSHipster](https://nshipster.com/inter-process-communication) — NSHipster · article catalogue
  **Published:** `2014-10-17T00:00:00-07:00`
  **NeKI brief:** Inter-process communication on Apple platforms crosses explicit boundaries such as extensions, services and URL schemes. Use the narrowest supported mechanism, validate all received data and never assume the other process is trusted.
- [iPhone 6 Plus First Impressions – Ole Begemann](https://oleb.net/blog/2014/09/iphone-6-plus-first-impressions) — Ole Begemann · article catalogue
  **Published:** `2014-09-25T17:25:00Z`
  **NeKI brief:** Device first impressions are useful when they tie display, battery, and performance observations to real development workloads. Treat the historical hardware report as context, not current purchasing guidance.
- [Replacing Launch Images With Storyboards – Ole Begemann](https://oleb.net/blog/2014/08/replacing-launch-images-with-storyboards) — Ole Begemann · article catalogue
  **Published:** `2014-08-28T18:47:00Z`
  **NeKI brief:** Launch screen storyboards replace static image variants with adaptive layout, reducing device-specific assets. The migration must avoid app-like initialization work because the system displays the launch screen before the process is ready.
- [iOS 8 Camera Privacy Settings](https://useyourloaf.com/blog/ios-8-camera-privacy-settings) — Use Your Loaf · article catalogue
  **Published:** `2014-07-16T21:18:01+01:00`
  **NeKI brief:** Covers camera privacy permissions and the need for a clear usage description before requesting access. Denial is a normal path; provide fallback behavior instead of treating authorization as guaranteed.
- [NSProgress – Ole Begemann](https://oleb.net/blog/2014/03/nsprogress) — Ole Begemann · article catalogue
  **Published:** `2014-03-12T22:55:00Z`
  **NeKI brief:** Explains NSProgress as a composable progress tree for long-running work, while its later caveat highlights that performance and cancellation behavior must be measured before adopting it broadly.
- [UIApplicationDelegate launchOptions - NSHipster](https://nshipster.com/launch-options) — NSHipster · article catalogue
  **Published:** `2013-12-16T00:00:00-08:00`
  **NeKI brief:** Application launch options expose the cause of an iOS app startup, such as a notification or URL. The guide is useful for routing at the lifecycle boundary before scene-based APIs take over navigation responsibility.
- [WWDC Keynote 2013](https://useyourloaf.com/blog/wwdc-keynote-2013) — Use Your Loaf · article catalogue
  **Published:** `2013-06-10T20:51:00+00:00`
  **NeKI brief:** Links to the WWDC 2013 keynote as historical platform context. It is not current API evidence; use it only to trace the origin of older design or technology decisions.
- [iOS Apps: Disable the Sleep Timer for Long-Running Tasks – Ole Begemann](https://oleb.net/blog/2013/02/ios-apps-disable-sleep-timer-long-running-tasks) — Ole Begemann · article catalogue
  **Published:** `2013-02-07T15:12:00Z`
  **NeKI brief:** Uses UIApplication's idle-timer control to keep the screen awake during a legitimate long-running interaction, emphasizing that the setting should be scoped and restored to preserve battery behavior.
- [instancetype - NSHipster](https://nshipster.com/instancetype) — NSHipster · article catalogue
  **Published:** `2012-12-10T00:00:00-08:00`
  **NeKI brief:** Explains Objective-C instancetype return typing so initializers and factory methods preserve the dynamic receiver type. Follow it when auditing legacy APIs imported into Swift, where generic self-types and availability still affect call-site safety.
- [Prevent Layers From Snapping Back to Original Values When Using Explicit CAAnimations – Ole Begemann](https://oleb.net/blog/2012/11/prevent-caanimation-snap-back) — Ole Begemann · article catalogue
  **Published:** `2012-11-28T15:56:00Z`
  **NeKI brief:** Prevents explicit Core Animation from visually snapping back by updating the model layer to the final value while the presentation layer animates the transition.
- [UTF-8 – Ole Begemann](https://oleb.net/blog/2012/09/utf-8) — Ole Begemann · article catalogue
  **Published:** `2012-09-17T18:45:00Z`
  **NeKI brief:** Clarifies UTF-8 as a variable-width encoding and distinguishes bytes, Unicode scalars, and user-perceived characters, helping avoid incorrect string indexing and length assumptions.
- [WWDC 2012 Session Videos](https://useyourloaf.com/blog/wwdc-2012-session-videos) — Use Your Loaf · article catalogue
  **Published:** `2012-06-20T13:35:00+00:00`
  **NeKI brief:** Links historical WWDC 2012 sessions for background on platform evolution. Use the videos for context only and verify any implementation guidance against contemporary frameworks.
- [iOS 6 WWDC Keynote Updates](https://useyourloaf.com/blog/ios-6-wwdc-keynote-updates) — Use Your Loaf · article catalogue
  **Published:** `2012-06-11T20:51:00+00:00`
  **NeKI brief:** Summarizes iOS 6 keynote-era updates as historical reference material. The link can explain legacy code decisions, but current feature planning requires up-to-date Apple sources.
- [Programming iOS 5 by Matt Neuburg](https://useyourloaf.com/blog/programming-ios-5-by-matt-neuburg) — Use Your Loaf · article catalogue
  **Published:** `2012-05-10T22:14:00+00:00`
  **NeKI brief:** Routes to historical iOS 5 programming material for legacy-code context. Its design lessons may be useful, but APIs and recommended patterns must be checked against current platforms.
- [UIAlertView changes in iOS 5](https://useyourloaf.com/blog/uialertview-changes-in-ios-5) — Use Your Loaf · article catalogue
  **Published:** `2011-12-14T21:27:00+00:00`
  **NeKI brief:** Explains historical UIAlertView behavior changes. New code should use UIAlertController, while legacy migration must preserve action roles and dismissal paths.
- [Stanford iOS development course updated for iOS 5](https://useyourloaf.com/blog/stanford-ios-development-course-updated-for-ios-5) — Use Your Loaf · article catalogue
  **Published:** `2011-11-16T21:01:00+00:00`
  **NeKI brief:** Routes to a historical Stanford iOS course updated for iOS 5. It may explain legacy concepts, but implementation details and tooling must be revalidated today.
- [iOS 5 Split View Controller Changes](https://useyourloaf.com/blog/ios-5-split-view-controller-changes) — Use Your Loaf · article catalogue
  **Published:** `2011-10-19T19:40:00+00:00`
  **NeKI brief:** Explains iOS 5 split-view controller changes as legacy UIKit navigation context. Modern adaptive split views should preserve the same core selection and containment invariants across size changes.
- [Apple TV Update after running beta](https://useyourloaf.com/blog/apple-tv-update-after-running-beta) — Use Your Loaf · article catalogue
  **Published:** `2011-10-18T20:14:00+00:00`
  **NeKI brief:** Discusses device update behavior after beta software as historical test-device maintenance context. Treat beta recovery and update workflows as operational procedures, not application implementation guidance.
- [Accessing Image Properties Without Loading the Image Into Memory – Ole Begemann](https://oleb.net/blog/2011/09/accessing-image-properties-without-loading-the-image-into-memory) — Ole Begemann · article catalogue
  **Published:** `2011-09-30T12:14:00Z`
  **NeKI brief:** Reads image metadata through Image I/O without decoding full pixel data, a useful boundary when inspecting dimensions or EXIF information while controlling memory use.
- [Thoughts on iOS 5](https://useyourloaf.com/blog/thoughts-on-ios-5) — Use Your Loaf · article catalogue
  **Published:** `2011-06-20T19:59:00+00:00`
  **NeKI brief:** Records thoughts on iOS 5 as historical ecosystem context. It may illuminate legacy code choices, but it is not current technical guidance.
- [How Developers Should Handle All the Stuff Apple Introduced at WWDC – Ole Begemann](https://oleb.net/blog/2011/06/how-developers-should-handle-stuff-apple-introduced-at-wwdc) — Ole Begemann · article catalogue
  **Published:** `2011-06-07T18:09:00Z`
  **NeKI brief:** Proposes a post-WWDC triage workflow: start with release notes and API diffs, then prioritize documentation, sessions, and controlled SDK experiments. Use the sequence to turn a large platform release into scoped engineering investigation.
- [A history of iOS media APIs (iPhone OS 2.0 to iOS 4.3) | Cocoa with Love](https://www.cocoawithlove.com/2011/03/history-of-ios-media-apis-iphone-os-20.html) — Cocoa with Love · article catalogue
  **Published:** `2011-03-20`
  **NeKI brief:** The history of iOS media APIs tracks changing capture, playback, and codec abstractions across early releases. Follow it to understand compatibility constraints before maintaining legacy AVFoundation or MediaPlayer code.
- [Submitting functionality for a future version of iOS | Cocoa with Love](https://www.cocoawithlove.com/2011/01/submitting-functionality-for-future.html) — Cocoa with Love · article catalogue
  **Published:** `2011-01-26`
  **NeKI brief:** Designing for future iOS functionality requires isolating optional capabilities from today's shipped behavior, reducing migration risk when APIs or platform assumptions change.
- [OBSlider, a UISlider Subclass With Variable Scrubbing Speed – Ole Begemann](https://oleb.net/blog/2011/01/obslider-a-uislider-subclass-with-variable-scrubbing-speed) — Ole Begemann · article catalogue
  **Published:** `2011-01-03T16:38:00Z`
  **NeKI brief:** Implements variable-speed slider scrubbing by overriding UIControl tracking callbacks, measuring vertical touch offset, and scaling horizontal value changes through configurable thresholds. The Objective-C sample is historical, but the touch-tracking and control-event design remains useful for custom UIKit controls.
- [Localizing iPhone App Settings Strings](https://useyourloaf.com/blog/localizing-iphone-app-settings-strings) — Use Your Loaf · article catalogue
  **Published:** `2010-12-17T22:59:00+00:00`
  **NeKI brief:** Localizes Settings.bundle strings so system settings screens match the app's supported languages. Keep keys stable and validate long translated labels in the actual Settings UI.
- [Localizing iPhone App Icon is not supported](https://useyourloaf.com/blog/localizing-iphone-app-icon-is-not-supported) — Use Your Loaf · article catalogue
  **Published:** `2010-12-16T22:19:00+00:00`
  **NeKI brief:** Explains that iPhone app icons are not localized like ordinary bundle strings. Branding assets should remain consistent, while localized display names and in-app labels carry language-specific content.
- [Localize iPhone Application Name](https://useyourloaf.com/blog/localize-iphone-application-name) — Use Your Loaf · article catalogue
  **Published:** `2010-12-15T20:50:00+00:00`
  **NeKI brief:** Localizes an iPhone application's display name through bundle resources rather than hard-coded UI text. Verify each locale in system surfaces where truncation and naming rules differ from in-app labels.
- [Checking network connectivity when displaying iPhone iAds](https://useyourloaf.com/blog/checking-network-connectivity-when-displaying-iphone-iads) — Use Your Loaf · article catalogue
  **Published:** `2010-08-08T20:06:00+00:00`
  **NeKI brief:** React to connectivity changes around an ad banner instead of assuming a previously loaded ad remains actionable. Hide or refresh unavailable content when the app returns from background, so a network loss does not leave a misleading interactive surface.
- [iPad table backgroundView](https://useyourloaf.com/blog/ipad-table-backgroundview) — Use Your Loaf · article catalogue
  **Published:** `2010-07-21T20:24:00+00:00`
  **NeKI brief:** UITableView grouped backgrounds can render differently on iPad than on iPhone under the same default color. Set an explicit background view or color when appearance is part of the design, rather than relying on platform-specific system defaults.
- [Symbol not found errors in universal apps](https://useyourloaf.com/blog/symbol-not-found-errors-in-universal-apps) — Use Your Loaf · article catalogue
  **Published:** `2010-06-21T20:01:00+00:00`
  **NeKI brief:** A symbol-not-found failure in a universal app often means a device-specific code path references APIs absent from the active runtime. Guard availability and ensure all architectures link compatible symbols, rather than relying on an iPad-only success to validate iPhone execution.
- [Adding a settings bundle to an iPhone App](https://useyourloaf.com/blog/adding-a-settings-bundle-to-an-iphone-app) — Use Your Loaf · article catalogue
  **Published:** `2010-05-18T18:45:00+00:00`
  **NeKI brief:** Add a Settings bundle when preferences should be edited in the system Settings app, then read its registered defaults from the application. A rotation-lock example shows that the app must still observe and apply the preference at runtime.
- [iPad Gestures](https://useyourloaf.com/blog/ipad-gestures) — Use Your Loaf · article catalogue
  **Published:** `2010-05-04T21:30:00+00:00`
  **NeKI brief:** Use gesture recognizers for common tap, swipe, pinch, and rotation interactions instead of manually interpreting every touch sequence. Configure recognizer coexistence deliberately, because competing gestures can delay or cancel controls that previously received raw touches.
- [iPad Modal View Controllers](https://useyourloaf.com/blog/ipad-modal-view-controllers) — Use Your Loaf · article catalogue
  **Published:** `2010-05-03T11:43:00+00:00`
  **NeKI brief:** Present and dismiss modal view controllers from a clear owning controller, then select iPad presentation behavior that matches the available space. Universal apps must not assume an iPhone full-screen modal has the same lifecycle or visual role on iPad.
- [OBGradientView: A Simple UIView Wrapper for CAGradientLayer – Ole Begemann](https://oleb.net/blog/2010/04/obgradientview-a-simple-uiview-wrapper-for-cagradientlayer) — Ole Begemann · article catalogue
  **Published:** `2010-04-20T13:15:00Z`
  **NeKI brief:** Wraps CAGradientLayer in an OBGradientView UIView subclass, forwarding gradient properties while accepting UIColor arrays. The UIKit wrapper makes gradients autoresizable with ordinary view layout, avoiding manual layer management when a gradient should behave like a view background.
- [Network data requirements on iPhone OS devices | Cocoa with Love](https://www.cocoawithlove.com/2010/04/network-data-requirements-on-iphone-os.html) — Cocoa with Love · article catalogue
  **Published:** `2010-04-07`
  **NeKI brief:** Early iPhone networking constraints include bandwidth, latency, radio energy, and intermittent connectivity. The analysis helps frame request batching and caching as product behavior, not only transport optimization.
- [Dynamic ivars: solving a fragile base class problem | Cocoa with Love](https://www.cocoawithlove.com/2010/03/dynamic-ivars-solving-fragile-base.html) — Cocoa with Love · article catalogue
  **Published:** `2010-03-22`
  **NeKI brief:** Dynamic ivars avoid fragile-base-class assumptions by resolving storage at runtime, but shift safety and introspection costs into the implementation. The technique is useful historical context for Objective-C runtime compatibility.
- [Porting RRGlossCausticShader to the iPhone – Ole Begemann](https://oleb.net/blog/2010/02/porting-rrglosscausticshader-to-the-iphone) — Ole Begemann · article catalogue
  **Published:** `2010-02-28T18:02:00Z`
  **NeKI brief:** Porting a Core Graphics effect from AppKit to UIKit isolates platform color and graphics types behind a small adapter, so the rendering algorithm survives while platform-specific APIs stay at the boundary.
- [OBShapedButton: Non-Rectangular Buttons on the iPhone – Ole Begemann](https://oleb.net/blog/2009/10/obshapedbutton-non-rectangular-buttons-on-the-iphone) — Ole Begemann · article catalogue
  **Published:** `2009-10-17T16:53:00Z`
  **NeKI brief:** Nonrectangular button rendering is not enough for accurate interaction: hit testing must reject transparent image pixels so the control's touch target matches its visible shape. Reassess accessibility and performance with modern UIKit APIs.
- [The ugly side of blocks: explicit declarations and casting. | Cocoa with Love](https://www.cocoawithlove.com/2009/10/ugly-side-of-blocks-explicit.html) — Cocoa with Love · article catalogue
  **Published:** `2009-10-05`
  **NeKI brief:** The explicit side of blocks shows how capture and lifetime rules can create surprising object retention. Follow it when reviewing callback APIs where convenience syntax obscures ownership and cancellation responsibility.
- [WhereIsMyMac, a Snow Leopard CoreLocation project | Cocoa with Love](https://www.cocoawithlove.com/2009/09/whereismymac-snow-leopard-corelocation.html) — Cocoa with Love · article catalogue
  **Published:** `2009-09-21`
  **NeKI brief:** Core Location on macOS combines authorization, asynchronous updates, and accuracy trade-offs rather than a synchronous coordinates lookup. The article is useful historical context for lifecycle-aware location features.
- [The Music Player Framework in iPhone SDK 3.0 – Ole Begemann](https://oleb.net/blog/2009/07/the-music-player-framework-in-the-iphone-sdk) — Ole Begemann · article catalogue
  **Published:** `2009-07-13T13:53:00Z`
  **NeKI brief:** MediaPlayer separates application and system music-player behavior, then uses playback notifications and a media-picker delegate to keep UI state synchronized with library selection. Treat the APIs as historical context and recheck current privacy requirements.
- [WWDC 2025 summary of Apple's platforms state of the union talk for iOS developers](https://tanaschita.com/wwdc-2025-state-of-the-union-summary) — Tanaschita · article catalogue
  **NeKI brief:** Summarizes the WWDC 2025 platform changes that affect existing apps, including automatic Liquid Glass adoption after recompiling with Xcode 26, opt-out controls, and the new Apple Intelligence and SwiftUI surfaces. Use it as release orientation before checking SDK-specific API contracts.
- [Losing an iPhone: A Horror Story](https://martiancraft.com/blog/2025/11/losing-an-iphone) — MartianCraft · article catalogue
  **NeKI brief:** A lost-device incident exposes assumptions around account recovery, backups, and security, turning an anecdote into a checklist for resilient mobile operations.
- [WWDC ’23: What we’re talking about from the keynote](https://martiancraft.com/blog/2023/06/wwdc-2023-keynote) — MartianCraft · article catalogue
  **NeKI brief:** The WWDC 2023 keynote recap groups announcements by platform impact instead of reproducing the presentation order. It helps prioritize follow-up sessions and migration experiments for existing apps.
- [WWDC ’23: Using AR and VR to broaden your business](https://martiancraft.com/blog/2023/05/wwdc-ar-vr) — MartianCraft · article catalogue
  **NeKI brief:** The AR and VR discussion considers spatial computing as a product and interaction constraint, not merely a new rendering target. Follow it when evaluating whether immersive features solve a user problem.
- [Anticipation and Expectations: MartianCraft Staff Gear Up for WWDC ’23](https://martiancraft.com/blog/2023/05/wwdc-2023-expectations) — MartianCraft · article catalogue
  **NeKI brief:** The WWDC 2023 expectations article records pre-release developer priorities and uncertainties. Use it as historical context for comparing announced APIs with the problems teams expected platform updates to solve.
- [16 years of the iPhone and what it means for iOS development past and future](https://martiancraft.com/blog/2023/01/16-years-of-iphone) — MartianCraft · article catalogue
  **NeKI brief:** Sixteen years of iPhone development connect platform evolution to changing interaction, hardware, and distribution assumptions. Follow it for historical context when deciding which legacy patterns deserve migration.
- [Apple September 2022 Event: What’s new, what we liked, and what we’re still waiting for](https://martiancraft.com/blog/2022/09/september-apple-event-recap) — MartianCraft · article catalogue
  **NeKI brief:** The September event recap distinguishes hardware capabilities, operating-system behavior, and developer-facing consequences. It is useful historical context for compatibility planning across iPhone releases.
- [Reflections on Apple’s Intel to Apple Silicon Transition](https://martiancraft.com/blog/2020/06/apple-intel-to-silicon-transition) — MartianCraft · article catalogue
  **NeKI brief:** The Intel-to-Apple-Silicon transition is framed through binary compatibility, Rosetta, and ecosystem migration rather than a simple CPU swap. Follow it for historical context when auditing architecture assumptions in macOS build pipelines.
- [Notification Handling on WatchKit](https://martiancraft.com/blog/2018/02/notification-handling-on-watchkit) — MartianCraft · article catalogue
  **NeKI brief:** WatchKit notifications are treated as a primary interaction surface, with actionable content and concise context rather than miniature app screens. The demo-oriented guidance helps validate payload handling across local and push notification paths.
- [Creating Enterprise iOS App Download Pages](https://martiancraft.com/blog/2017/02/creating-ios-app-download-pages) — MartianCraft · article catalogue
  **NeKI brief:** Enterprise iOS distribution packages an IPA with a manifest and download page, then requires users to trust the enterprise signer. This differs fundamentally from standard App Store provisioning and needs a controlled distribution channel to avoid installation failures.
- [MartianCraft Smart Mirror Project—Part 1: Hardware](https://martiancraft.com/blog/2017/01/smart-mirror-hardware) — MartianCraft · article catalogue
  **NeKI brief:** An iPad-powered smart mirror keeps the display removable for maintenance while delivering locale-aware time, RSS, weather, and calendar modules. Define the physical enclosure, one-way mirror, power, and device-access constraints alongside the iOS UI.
- [Arriving at San Francisco](https://martiancraft.com/blog/2015/10/san-francisco-part-2) — MartianCraft · article catalogue
  **NeKI brief:** Examines Discover the evolution of Apple. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Living the Live Photos Dream](https://martiancraft.com/blog/2015/09/live-photos) — MartianCraft · article catalogue
  **NeKI brief:** Live Photos combine still imagery with short motion and audio, enabling effects adjacent to cinemagraphs. Product experiments must account for capture, editing, and playback constraints rather than assuming a static-image pipeline can represent the richer media.
- [Establishing Priority](https://martiancraft.com/blog/2014/07/establishing-priority) — MartianCraft · article catalogue
  **NeKI brief:** Prioritize defects by combining severity with observed frequency: a rare crash may rank below a ubiquitous visual issue, while blockers and data loss take precedence. Record uncertainty explicitly so the team can recalibrate the triage decision.

## Newsletter and related leads

- [Amethyst Vein: An Open-Source, Cross-Platform Local Persistence Framework with SwiftData-Style APIs](https://l.fatbobman.com/w0150-6) — Fatbobman’s Swift Weekly · Issue 150 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Presents Vein, an open-source local-first ORM with SwiftData-like macros, model containers, queries, migrations, and a SQLite/SQLCipher backend across Apple platforms, Linux, Android, and Windows. Use it to assess a shared Swift persistence layer rather than assuming SwiftData portability.
- [KSCrash](https://github.com/kstenerud/KSCrash) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** KSCrash is a mature iOS/macOS crash-reporting library that captures native crashes and turns them into reports for later symbolication or delivery. It is useful when comparing in-process crash capture with hosted crash-reporting SDK trade-offs.
- [NoMac](https://nomac.app/) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: AI Development · App Distribution & Store Operations · Testing
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Offers an agent-oriented cloud pipeline that creates signed iOS builds, installs them on a phone, sends them to TestFlight, and submits to the App Store. Its model avoids local Xcode and certificate handling.
- [Concentric Buttons with OS 27’s SwiftUI APIs](https://l.fatbobman.com/w0148-04) — Fatbobman’s Swift Weekly · Issue 148 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-08-10T12:01:23.212Z`
  **NeKI brief:** Builds a custom SwiftUI button border from GeometryProxy.concentricCornerRadii, including container-shape requirements, nil fallback behavior and the limitation that ButtonBorderShape remains closed.
- [VersionedDocC: Bringing Version Management to Swift-DocC](https://l.fatbobman.com/w0148-07) — Fatbobman’s Swift Weekly · Issue 148 — Article · Topics: Apple Platform Ecosystem · Developer Career & Practice · Swift
  **Published:** `2026-08-10T12:01:23.212Z`
  **NeKI brief:** Presents VersionedDocC's orchestration of immutable release documentation, stable versioned URLs, symbol-graph API comparisons and reusable publishing workflows around the standard Swift and DocC tools.
- [WWDC26: Reordering Items in SwiftUI Lists and Grids](https://serialcoder.dev/text-tutorials/swiftui/wwdc26-reordering-items-in-swiftui-lists-and-grids) — Those Who Swift · Issue 277 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-07-29T20:01:55.196Z`
  **NeKI brief:** Demonstrates iOS 27 reordering for SwiftUI lists and grids through reorderContainer and the model mutation it drives. Use it to compare the new shared mechanism with older List-only movement and custom drag implementations.
- [Building adaptive non-modal panels in SwiftUI](https://l.fatbobman.com/w0146-04) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** Builds a detent-based, non-modal SwiftUI panel that moves from the bottom edge in portrait to a side edge in wider layouts. It covers geometry-driven detents, dragging, and keeping the underlying content interactive.
- [An Indie Playbook for the WWDC26 App Store Changes](https://3nsofts.com/guides/app-store/app-store-wwdc26-monetization-indie-playbook) — iOS Dev Weekly · Issue 759 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `17th July 2026`
  **NeKI brief:** Examines WWDC26 App Store changes through an indie developer lens, connecting policy updates to pricing, subscriptions, and release planning. Useful for product decisions, but verify current Apple commerce rules before implementation.
- [Apple’s WWDC26 AI Story Is About Control, Not Just Models](https://jonbrown.org/blog/apple-intelligence-xcode-wwdc26-platform-control) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Apple Platform Ecosystem · Xcode
  **Published:** `2026-07-15`
  **NeKI brief:** Argues that Apple’s AI direction emphasizes platform control and developer tooling. Useful for strategic context when assessing how Foundation Models and Xcode capabilities shape implementation choices.
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Those Who Swift · Issue 275 — Article · Topics: Apple Platform Ecosystem · Foundation & Data Formats · Swift
  **Published:** `2026-07-15`
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [https://www.figma.com/community/file/1651309003795292092/ios-and-ipados-27](https://www.figma.com/community/file/1651309003795292092/ios-and-ipados-27?ref=createwithswift.com) — Create with Swift · Issue 115 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2026-07-10T15:00:44.000Z`
  **NeKI brief:** Apple has updated its official Figma UI kits for iOS, iPadOS, and macOS 27, giving designers and developers a refreshed set of components, styles, materials, and templates that reflect the latest platform updates. The new kits are useful for creating more…
- [What’s New In Swift: June 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-june-2026) — Those Who Swift · Issue 274 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-07-08`
  **NeKI brief:** Examines June digest in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [physical devices](https://www.rocketsim.app/docs/features/capturing/physical-device-support) — SwiftLee Weekly · Issue 331 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `2026-07-07T14:05:55.000Z`
  **NeKI brief:** Documents RocketSim capture support for USB-connected physical devices. Use it to evaluate a device-recording workflow for demos or bug evidence, checking supported OS versions and the operational limits of the tool.
- [iPhone Apps Are Resizable Now, and It's Not Just for iPad](https://dev.to/arshtechpro/wwdc26-whats-new-in-swiftui-a-developers-breakdown-1333?ref=ioscodereview.com) — iOS Code Review · Issue 81 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-06-30T16:31:22.000Z`
  **NeKI brief:** Examines iPhone Apps Are Resizable Now, and It's Not Just for iPad in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [All new frameworks presented at WWDC26](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc26) — SwiftLee Weekly · Issue 330 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** This reference inventories the 14 frameworks introduced at WWDC26 and pairs each name with its Apple-platform purpose. It is useful as a compact discovery map before following the relevant primary documentation for App Intents, AI, routing, graphics, or testing work.
- [WWDC26: SwiftUI Group Lab 2nd - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-2nd-q-and) — Those Who Swift · Issue 272 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-06-24`
  **NeKI brief:** Summarizes questions and answers from the second WWDC26 SwiftUI Group Lab, capturing implementation guidance and framework constraints discussed with Apple engineers. Useful as contextual follow-up when an API’s behavior is unclear from documentation alone.
- [Helm 2.3: WWDC & Helm CLI](https://helm-app.com/changelog/helm-2-3-helm-cli) — SwiftLee Weekly · Issue 329 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2026-06-23T14:07:47.000Z`
  **NeKI brief:** Examines Automate your App Store Connect workflows with Helm’s new CLI! in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [What’s new in SwiftUI (2-minute recap)](https://www.swiftwithvincent.com/blog/whats-new-in-swiftui-2-minute-recap) — SwiftLee Weekly · Issue 329 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-06-23T14:07:47.000Z`
  **NeKI brief:** Provides a concise tour of SwiftUI changes introduced around WWDC 2026. Use it to triage which new APIs deserve deeper investigation before reading their authoritative availability, behavior, and migration details.
- [WWDC26: Xcode Tips and Tricks Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-xcode-tips-and-tricks-group) — iOS Dev Weekly · Issue 755 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Xcode
  **Published:** `19th June 2026`
  **NeKI brief:** Explains WWDC26: Xcode Tips and Tricks Group Lab - Q&A, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How did Apple cut launch time by 30% in iOS 27?](https://blog.jacobstechtavern.com/p/ios-27-launch-time) — iOS Dev Weekly · Issue 755 — Article · Topics: Apple Platform Ecosystem
  **Published:** `19th June 2026`
  **NeKI brief:** The article investigates how Apple reduced launch time in iOS 27 and discusses the technical changes behind the performance improvement.
- [Footprint](https://github.com/naftaly/Footprint) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Apple Platform Ecosystem · Developer Career & Practice · Developer Tools
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Footprint exposes app and system memory pressure as normal, warning, urgent, critical, and terminal states, with a 500-ms heartbeat and AsyncStream updates. SwiftUI modifiers let an app adapt before memory warnings arrive too late.
- [(Some) Unanswered Swift Group Questions](https://www.massicotte.org/blog/wwdc26-unanswered-qa) — Those Who Swift · Issue 271 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-06-18`
  **NeKI brief:** Collects Swift Group questions that remained unanswered around WWDC26, making uncertainty visible instead of implying unsupported behavior. Useful for identifying topics that need direct documentation or reproducible experiments.
- [WWDC26: Swift Group Lab – Q&A](https://antongubarenko.substack.com/p/wwdc26-swift-group-lab-q-and-a) — Those Who Swift · Issue 271 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-06-18`
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
- [WWDC26 Group Labs: The Real Story Isn’t Foundation Models. It’s Evaluation.](https://divyaravidev.substack.com/p/wwdc26-group-labs-the-real-story) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Reports on WWDC26 group labs and evaluation around Foundation Models. Useful for understanding model assessment as an engineering concern rather than relying on demo quality alone.
- [🚀 WWDC26: Improvements to Instruments in Xcode 27](https://youtu.be/9zjeImiYtow?si=vEN-AD55cyLIUnr4&t=1279) — iOS CI Newsletter · Issue 89 — Video · Topics: Apple Platform Ecosystem · Performance · Xcode
  **Published:** `2026-06-17T00:00:00.000Z`
  **NeKI brief:** Records WWDC26: Improvements to Instruments in Xcode 27 as a visual walkthrough relevant to Apple Platform Ecosystem and Performance. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [❓ WWDC26: App Store Connect Group Lab](https://www.youtube.com/watch?v=QPWPgSjg9Kc) — iOS CI Newsletter · Issue 89 — Video · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2026-06-17T00:00:00.000Z`
  **NeKI brief:** Records WWDC26: App Store Connect Group Lab as a visual walkthrough relevant to App Distribution & Store Operations and Apple Platform Ecosystem. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [☁️ WWDC26: Build, deliver, and automate with Xcode Cloud](https://www.youtube.com/watch?v=sbdA41c2o88) — iOS CI Newsletter · Issue 89 — Video · Topics: Apple Platform Ecosystem · Xcode
  **Published:** `2026-06-17T00:00:00.000Z`
  **NeKI brief:** Records WWDC26: Build, deliver, and automate with Xcode Cloud as a visual walkthrough relevant to Apple Platform Ecosystem and Xcode. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [What's New In Swiftdata](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — SwiftLee Weekly · Issue 328 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Mohammad covers what’s new in SwiftData for iOS 27, showing how enum predicates, sectioned queries, compound predicates, the new .codable attribute, and ResultsObserver remove common workarounds.
- [add 30+ features to Xcode's Device Hub](https://www.rocketsim.app/docs/features/capturing/device-hub-support) — SwiftLee Weekly · Issue 328 — Article · Topics: Apple Platform Ecosystem · Xcode
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Documents add 30+ features to Xcode's Device Hub, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [WWDC 2026 - What's New in Swift](https://dev.to/arshtechpro/wwdc-2026-whats-new-in-swift-3nb2?ref=ioscodereview.com) — iOS Code Review · Issue 80 — Article · Topics: Apple Platform Ecosystem · Swift · Testing
  **Published:** `2026-06-15T17:08:20.000Z`
  **NeKI brief:** Summarises WWDC 2026 - What's New in Swift for Apple Platform Ecosystem and Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Foundation Models can now swap providers](https://www.techtimes.com/articles/318039/20260609/wwdc-2026-developer-tools-foundation-models-now-swaps-ai-providers-without-code-changes.htm?ref=ioscodereview.com) — iOS Code Review · Issue 80 — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **Published:** `2026-06-15T17:08:20.000Z`
  **NeKI brief:** Examines Foundation Models can now swap providers in the context of AI Development and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Evaluations framework](https://app.daily.dev/posts/wwdc26-meet-the-evaluations-framework-apple-e7e4p4zb5?ref=ioscodereview.com) — iOS Code Review · Issue 80 — Article · Topics: AI Development · Apple Platform Ecosystem · Xcode
  **Published:** `2026-06-15T17:08:20.000Z`
  **NeKI brief:** Examines Evaluations framework in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [WWDC26: SwiftUI Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-q-and-a) — SwiftUI Weekly · SwiftUI Weekly - Issue #235 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-06-15T15:55:05.373Z`
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
- [SwiftUI for Beginners](https://antongubarenko.substack.com/p/wwdc26-swiftui-for-beginners-group) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** A WWDC26 beginner-group Q&A focused on SwiftUI fundamentals and onboarding questions. Use it to identify recurring learning obstacles, while checking current API behavior in Apple's own session recordings and documentation.
- [Performance](https://antongubarenko.substack.com/p/wwdc26-power-and-performance-group) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Summarizes WWDC26 Power and Performance Group Lab answers, giving developers a compact route to optimization guidance and measurement caveats that may not appear in session-level summaries.
- [VisionOS](https://antongubarenko.substack.com/p/wwdc26-visionos-group-lab-q-and-a) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Collects WWDC26 visionOS Group Lab questions and answers, useful for resolving practical platform-integration details and identifying areas where direct Apple documentation or experiments remain necessary.
- [AI](https://antongubarenko.substack.com/p/wwdc26-coding-intelligence-machine) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Summarizes WWDC26 coding-intelligence discussion, helping teams distinguish model-assisted development workflows from product runtime capabilities before adopting AI tooling in an Apple-platform codebase.
- [Icon Composer](https://antongubarenko.substack.com/p/wwdc26-icon-composer-for-beginners) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** A beginner-oriented WWDC26 discussion of Icon Composer workflows and questions. Follow it for practical design-tool context, but confirm supported asset formats and platform requirements in Apple's current tooling documentation.
- [Camera and Photo](https://antongubarenko.substack.com/p/wwdc26-camera-and-photo-technologies) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** A WWDC26 camera and photo technology Q&A collecting implementation questions from developers. Use it as a topical guide to capture, processing, and media APIs, then validate specifics against Apple frameworks.
- [What’s new in Swift 6.4 at WWDC26](https://onmyway133.com/posts/whats-new-in-swift-6.4-at-wwdc26) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Surveys Swift 6.4 changes announced around WWDC26, grouping language and toolchain developments for practitioners. Use it as a release-note map and verify proposal status, syntax, and availability in Swift.org sources.
- [WWDC Quick Look](https://wwdc-quick-look.swiftgg.team/articles) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** WWDC Quick Look provides a community index of Apple developer announcements and session takeaways. Use it for fast discovery across topics, treating every summary as a pointer to the authoritative session or documentation.
- [My First Developer Notes from WWDC26](https://www.ioscoffeebreak.com/issue/issue73) — iOS Dev Weekly · Issue 754 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th June 2026`
  **NeKI brief:** Examines WWDC26 is here, and after watching the keynote and Platforms State of the Union, these are the announcements that felt most relevant to me as an Apple Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [First Impressions of WWDC 2026: In Line with Expectations, but More Pragmatic](https://fatbobman.com/en/weekly/issue-139) — iOS Dev Weekly · Issue 754 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th June 2026`
  **NeKI brief:** The page covers “First Impressions of WWDC 2026: In Line with Expectations, but More Pragmatic” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [SwiftUI reorderable containers in iOS 27](https://livsycode.com/swiftui/swiftui-reorderable-containers-in-ios-27) — SwiftLee Weekly · Issue 327 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2026-06-09T21:59:45.000Z`
  **NeKI brief:** Artem shares how SwiftUI’s new iOS 27 reorderable containers let you add drag-to-reorder support beyond List, using reorderable()and reorderContainer to make stacks, grids, and custom layouts easier to rearrange.
- [Active ReviewSE-0478File-level defaults](https://github.com/apple/swift-evolution/blob/main/proposals/0478-default-isolation-typealias.md) — SwiftLee Weekly · Issue 327 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2026-06-09T21:59:45.000Z`
  **NeKI brief:** Records Active ReviewSE-0478File-level defaults, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0516`Iterable`](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 327 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2026-06-09T21:59:45.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0529Add `FilePath` to the Standard Library](https://github.com/apple/swift-evolution/blob/main/proposals/0529-filepath-in-stdlib.md) — SwiftLee Weekly · Issue 327 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2026-06-09T21:59:45.000Z`
  **NeKI brief:** Records AcceptedSE-0529Add `FilePath` to the Standard Library, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [A Vision for Networking in Swift](https://github.com/swiftlang/swift-evolution/blob/main/visions/networking.md) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** Swift's networking vision analyzes overlapping responsibilities among URLSession, Network.framework, SwiftNIO, and related clients. Follow it when designing an abstraction that should align with the language ecosystem's planned consolidation.
- [Swift HTTP API Proposal](https://github.com/apple/swift-http-api-proposal) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** The Swift HTTP API proposal explores a common foundation for HTTP types and behavior across client and server libraries. Use it to track interoperable networking direction before committing a new cross-library adapter.
- [Michael Tsai](https://mjtsai.com/blog/2026/06/03/wwdc-2026-wish-lists) — iOS Dev Weekly · Issue 753 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `5th June 2026`
  **NeKI brief:** Examines Michael Tsai - Blog - WWDC 2026 Wish Lists. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC 2026: Community Preview](https://mjtsai.com/blog/2026/06/04/wwdc-2026-preview) — iOS Dev Weekly · Issue 753 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `5th June 2026`
  **NeKI brief:** Collects community expectations and links ahead of WWDC 2026. Useful for discovering topics to investigate while separating predictions from Apple’s eventual announcements.
- [Apple Music playlist](https://music.apple.com/ru/playlist/wwdc26-hello/pl.c2b332d45b194756aeb66a44329a2a08?l=en-GB) — Those Who Swift · Issue 269 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games
  **Published:** `2026-06-04`
  **NeKI brief:** Links an Apple Music playlist. Useful only as media navigation, not as a knowledge-index reading source.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — SwiftLee Weekly · Issue 326 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `2026-06-02T14:07:19.000Z`
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AppleInsider](https://appleinsider.com/articles/26/05/18/apple-design-awards-2026-finalists-include-cyberpunk-2077-civilization-vii?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines AppleInsider in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [TUAW](https://www.tuaw.com/2026/05/19/apple-design-awards-2026-finalists-revealed?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines TUAW in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Who’s Going to WWDC26?Add your flights • See who’s coming](https://flighty.app/wwdc26?ref=createwithswift.com) — Create with Swift · Issue 109 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2026-05-29T16:00:08.000Z`
  **NeKI brief:** As every year, Flighty is bringing back its community map so you can add your flights, see who’s flying in from around the world, and maybe even spot a few familiar faces on your route!
- [AgentKitten: Provider-Agnostic AI Agents in Swift](https://github.com/fbeeper/agentkitten) — iOS Dev Weekly · Issue 752 — Source repository · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `29th May 2026`
  **NeKI brief:** The page covers “AgentKitten: Provider-Agnostic AI Agents in Swift” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [WWDC Bingo](https://basicappleguy.com/basicappleblog/tag/Bingo) — iOS Dev Weekly · Issue 752 — Article · Topics: Apple Platform Ecosystem
  **Published:** `29th May 2026`
  **NeKI brief:** Discusses WWDC Bingo, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Make It Visible: Accessibility Meetup @ CommunityKit](https://luma.com/ro48u8fw) — SwiftLee Weekly · Issue 325 — Article · Topics: Accessibility · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `2026-05-26T14:06:24.000Z`
  **NeKI brief:** Describes Make It Visible: Accessibility Meetup @ CommunityKit, providing the event-specific information needed to identify its Apple-platform community context.
- [Xcode should be decoupled from Swift versions](https://macguru.dev/xcode-should-be-decoupled-from-swift-versions) — SwiftLee Weekly · Issue 325 — Article · Topics: Apple Platform Ecosystem · Swift · Xcode
  **Published:** `2026-05-26T14:06:24.000Z`
  **NeKI brief:** Argues that Xcode and Swift version coupling creates avoidable upgrade friction. Use it as a language-toolchain compatibility perspective when planning CI matrices, migration sequencing, and package version constraints.
- [Beer with Swift - WWDC26 Special Edition](https://luma.com/y95acvdw?ref=createwithswift.com) — Create with Swift · Issue 108 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-05-22T16:00:37.000Z`
  **NeKI brief:** Don’t miss the chance to keep the excitement going beyond the mothership, join us around Cupertino on the 9th of June for a special WWDC26 edition of our Create Beer with Swift! This is your chance to connect with fellow Swift enthusiasts, discuss Apple's…
- [Swift Student Challenge winners](https://9to5mac.com/2026/05/07/apple-highlights-four-swift-student-challenge-apps-ahead-of-wwdc-2026?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Swift Student Challenge winners in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Lil Finder Guy](https://basicappleguy.com/basicappleblog/lil-finder-guy) — iOS Dev Weekly · Issue 748 — Article · Topics: Apple Platform Ecosystem
  **Published:** `17th April 2026`
  **NeKI brief:** Discusses Lil Finder Guy, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [MacRumors](https://www.macrumors.com/roundup/wwdc?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines MacRumors in the context of Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [OpenAI: Build For iOS And macOS](https://developers.openai.com/codex/use-cases/native-ios-macos-apps) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Testing
  **Published:** `2026-04-01`
  **NeKI brief:** Examines OpenAI: Build For iOS And macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [FeaturesKit](https://github.com/adamfootdev/FeaturesKit) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** FeaturesKit models feature flags and evaluates them through injectable configuration, making rollout and test scenarios explicit. The repository helps compare a typed feature-management layer with scattered boolean checks and explains where deterministic test overrides belong.
- [AboutKit](https://github.com/adamfootdev/AboutKit) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** AboutKit provides reusable UI for an application’s About screen and related metadata. Follow its source for concrete SwiftUI or UIKit composition patterns, then verify customization and localization behavior.
- [HelpKit](https://github.com/adamfootdev/HelpKit) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** HelpKit provides reusable help or support-screen components for Apple-platform applications. Follow its source for concrete content, navigation, and presentation patterns, while checking platform and API compatibility.
- [a major shift in AI leadership](https://www.theguardian.com/technology/2025/dec/01/apple-ai-chief-john-giannandrea-steps-down) — Those Who Swift · Issue 252 — Article · Topics: AI Development · App Intents & System Surfaces · Apple Platform Ecosystem
  **Published:** `2026-02-04`
  **NeKI brief:** Reviews a major shift in AI leadership. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [InAppPurchaseKit](https://github.com/adamfootdev/InAppPurchaseKit) — iOS Dev Tools · iOS Dev Tools: Bullseye, Commander, InAppPurchaseKit — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-01-29T21:12:37.433Z`
  **NeKI brief:** InAppPurchaseKit packages common in-app-purchase workflows for Swift applications. Follow its source for concrete product loading, entitlement, and transaction abstractions, then verify StoreKit version assumptions separately.
- [rolling out changes to App Store search ads](https://www.macrumors.com/2026/01/23/more-app-store-ads-coming-soon) — Those Who Swift · Issue 251 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2026-01-28`
  **NeKI brief:** Reviews rolling out changes to App Store search ads. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [WWDC Index](https://nonstrict.eu/wwdcindex) — iOS Dev Weekly · Issue 739 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** This technical resource covers a searchable index of WWDC material. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Asset Catalog Viewer](https://github.com/artemnovichkov/asset-catalog-viewer) — iOS Dev Tools · iOS Dev Tools: Swift Commit Generator, CommonSwiftUI, Asset Catalog Viewer — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Xcode
  **Published:** `2025-12-31T16:45:21.414Z`
  **NeKI brief:** Asset Catalog Viewer inspects Xcode asset catalogs and their contained resources. Follow its source for concrete catalog parsing and preview behavior, useful when auditing image, color, and app-icon assets outside Xcode.
- [🪝 How the new App Store Connect webhooks can power your automations](https://en.zhgchg.li/posts/zrealm-dev/app-store-connect-api-webhook-automate-ci-cd-workflows-seamlessly-7c0974856393) — iOS CI Newsletter · Issue 84 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Examines How the new App Store Connect webhooks can power your automations in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Mastering SwiftUI — Free Guide](https://psimas.gumroad.com/l/swiftui?layout=discover&recommended_by=search&_gl=1%2A10g751b%2A_ga%2AODYxNDkzMDQzLjE3NjU2NDU4NjM.%2A_ga_6LJN6D94N6%2AczE3NjU2NDU4NjIkbzEkZzAkdDE3NjU2NDU4NjIkajYwJGwwJGgw) — Those Who Swift · Issue 245 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines Mastering SwiftUI — Free Guide, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift AI SDK](https://github.com/teunlao/swift-ai-sdk) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Source repository · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** Swift AI SDK provides Swift abstractions for integrating AI services or models. Follow its source for concrete request, streaming, and model interfaces, while verifying provider compatibility, credentials, and privacy requirements.
- [Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance](https://www.youtube.com/watch?v=YCRvVfDGQuY) — Those Who Swift · Issue 243 — Video · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `2025-12-10`
  **NeKI brief:** Reviews Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Sourcekit-bazel-bsp](https://github.com/spotify/sourcekit-bazel-bsp) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** Sourcekit-bazel-bsp connects Bazel-based builds with SourceKit and the Build Server Protocol. Follow its repository for concrete editor, indexing, and build integration, while verifying toolchain-version compatibility.
- [Build Server Protocol](https://build-server-protocol.github.io/) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** Build Server Protocol documents a protocol for communication between editors or IDEs and build servers. Follow it for a concrete integration boundary when designing language-tooling and build-system interoperability.
- [sourcekit-lsp](https://github.com/swiftlang/sourcekit-lsp) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** sourcekit-lsp provides language-server functionality for Swift and related source tooling. Follow its source for concrete indexing, diagnostics, completion, and editor-integration behavior, while checking current toolchain compatibility.
- [Language Server Protocol](https://microsoft.github.io/language-server-protocol) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** Defines the Language Server Protocol boundary between editors and language servers, covering features such as completion, go-to-definition, references, and hover documentation. Useful when evaluating editor tooling integrations and language-specific service architecture.
- [Embedded Swift Improvements Coming in Swift 6.3](https://www.swift.org/blog/embedded-swift-improvements-coming-in-swift-6.3) — iOS Dev Weekly · Issue 736 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `21st November 2025`
  **NeKI brief:** Examines Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low… in the context of Combine & Reactive Programming and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Find the SwiftUI Views that Update the Most Using Instruments](https://swiftdevjournal.com/posts/swiftui-frequent-view-updates) — iOS Dev Weekly · Issue 734 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `7th November 2025`
  **NeKI brief:** Mark shows how to use instrument to profile your app, spot views with high update frequency and investigate the roots of unnecessary re-renders.
- [Mark Szymczyk](https://mastodon.world/@swiftdevjournal) — iOS Dev Weekly · Issue 734 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Mark shows how to use instrument to profile your app, spot views with high update frequency and investigate the roots of unnecessary re-renders.
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) — Fatbobman’s Swift Weekly · Issue 109 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `2025-11-03T12:02:55.598Z`
  **NeKI brief:** The Dev Containers extension adds reproducible container-backed development environments to Visual Studio Code. Use it when comparing local toolchain isolation and onboarding workflows, while separating container setup from Swift package or Xcode build behavior.
- [An Apple Intelligence-Style Glow Effect in SwiftUI](https://livsycode.com/swiftui/an-apple-intelligence-style-glow-effect-in-swiftui) — iOS Dev Weekly · Issue 730 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `10th October 2025`
  **NeKI brief:** Artem demonstrates how to create an “Apple Intelligence” style glow effect in SwiftUI by applying visual effects (like blurs and overlays) to achieve a glowing UI appearance.
- [Widgetsmith Five Years Later - David Smith, Independent iOS Developer](https://david-smith.org/blog/2025/09/18/widgetsmith-at-five) — SwiftLee Weekly · Issue 290 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2025-09-23T14:09:24.000Z`
  **NeKI brief:** Explains Widgetsmith Five Years Later - David Smith, Independent iOS Developer, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.
- [Perception](http://github.com/pointfreeco/swift-perception) — SwiftUI Weekly · SwiftUI Weekly - Issue #222 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-09-01T13:02:53.458Z`
  **NeKI brief:** Provides Point-Free's backport of Swift observation capabilities for deployment targets that predate the newer Observation framework. Useful when sharing modern observable-model patterns across older OS versions.
- [SwiftUI WebView](https://troz.net/post/2025/swiftui-webview) — SwiftLee Weekly · Issue 286 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-08-26T14:12:25.000Z`
  **NeKI brief:** Presents a concrete implementation of SwiftUI WebView. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Faster iOS app releases with automated QA](https://www.qawolf.com/solutions/ios-testing) — iOS Dev Weekly · Issue 722 — Article · Topics: AI Development · Personal Essays · Testing
  **Published:** `15th August 2025`
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [xcode-build-server](https://github.com/SolaWing/xcode-build-server) — Fatbobman’s Swift Weekly · Issue 97 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Xcode
  **Published:** `2025-08-11T12:04:06.619Z`
  **NeKI brief:** xcode-build-server supplies build-server-protocol data for Xcode projects so editors can understand Swift builds. Use it when integrating non-Xcode tooling such as Zed with an existing workspace and its compiler settings.
- [xcede](https://codeberg.org/luxmentis/xcede) — Fatbobman’s Swift Weekly · Issue 97 — Article · Topics: Apple Platform Ecosystem · Product Design · Swift
  **Published:** `2025-08-11T12:04:06.619Z`
  **NeKI brief:** xcede is an editor-oriented companion for Swift development outside Xcode. Use it to explore how alternative editors can connect project metadata, language services, and build-server support rather than replacing Xcode blindly.
- [you know what to do](https://iosdevdirectory.com/contributing) — iOS Dev Weekly · Issue 721 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `8th August 2025`
  **NeKI brief:** Explores add their site for them, focusing on so, whether you’ve fully migrated to mastodon or now split. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftNetworkRequest](https://github.com/vadimkrutovlv/swift-network-request) — iOS Dev Tools · iOS Dev Tools: SparkDI, SwiftNetworkRequest, TranscriptDebugMenu — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-08-07T19:48:09.291Z`
  **NeKI brief:** SwiftNetworkRequest provides request abstractions for Swift networking. Follow its source for concrete construction, decoding, error, and cancellation semantics, then compare its concurrency model with the project’s networking layer.
- [Icon Composer Notes](https://www.virtualsanity.com/202507/icon-composer-notes) — Those Who Swift · Issue 223 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2025-07-16`
  **NeKI brief:** Reviews Icon Composer Notes. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [WWDC25 updates to Transwwdcripts & Resourwwdces](https://www.elkraneo.com/wwdc25-updates-to-transwwdcripts-resourwwdces) — iOS Dev Weekly · Issue 717 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `11th July 2025`
  **NeKI brief:** Presents WWDC25 updates to Transwwdcripts & Resourwwdces, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Transwwdcripts](https://www.elkraneo.com/transwwdcripts) — iOS Dev Weekly · Issue 717 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `11th July 2025`
  **NeKI brief:** Cristian Díaz with updates to his WWDC-related apps. Transwwdcripts lets you view and download session transcripts, and Resourwwdces is a collection of links to documentation, sample code, and other resources from the conference. I know I risk losing…
- [Resourwwdces](https://www.elkraneo.com/resourwwdces) — iOS Dev Weekly · Issue 717 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `11th July 2025`
  **NeKI brief:** Examines 1679 links, 5 categories, 10 years. That is how many resources have been shared on WWDC editions since 2014. The categories are Sample Code, Documentation Guide, Developer Forum, a. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🫙 Getting started with Apple’s Docker alternative](https://swifttoolkit.dev/posts/container) — iOS CI Newsletter · Issue 71 — Article · Topics: Apple Platform Ecosystem · Product Design · Swift
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Examines Getting started with Apple’s Docker alternative in the context of Apple Platform Ecosystem and Product Design. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Container](https://github.com/apple/container) — iOS CI Newsletter · Issue 71 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Product Design
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Apple Container provides container tooling for macOS development environments. Use it when isolating builds or services on Apple Silicon, while checking runtime constraints and image compatibility before replacing existing VM or CI workflows.
- [Apple’s On-Device Foundation Model Is Here.. But Is It Any Good?](https://ronnierocha.dev/blog/wwdc-2025-apples-on-device-foundation-model-is-here-but-is-it-any-good) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `27th June 2025`
  **NeKI brief:** Apple’s On-Device Foundation Model Is Here.. But Is It Any Good?. This link is retained as a technical reading lead for Apple-platform development.
- [Embedding Godot games in iOS apps is easy now](https://christianselig.com/2025/05/godot-ios-interop) — iOS Dev Weekly · Issue 716 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Personal Essays
  **Published:** `27th June 2025`
  **NeKI brief:** You might have missed Christian Selig’s latest article in the run up to WWDC, but it’s worth reading as it’ll quickly get you up and running with a Godot scene inside your iOS or Mac. There has been plenty of work going on with Godot on Apple platforms…
- [State of the Union: What I Took Away](https://yaacoub.github.io/articles/swift-tip/state-of-the-union-what-i-took-away) — SwiftUI Weekly · SwiftUI Weekly - Issue #218 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2025-06-23T10:41:25.657Z`
  **NeKI brief:** Distills the author's practical takeaways from Apple's Platforms State of the Union at WWDC25. Useful for quickly identifying platform changes worth following up in a SwiftUI or Apple-platform product roadmap.
- [Swift at Apple: Migrating the Password Monitoring service](https://www.swift.org/blog/swift-at-apple-migrating-the-password-monitoring-service-from-java) — iOS Dev Weekly · Issue 715 — Article · Topics: Apple Platform Ecosystem · Security & Privacy · Swift
  **Published:** `20th June 2025`
  **NeKI brief:** Describes Apple's migration of a password-monitoring service from Java to Swift, including server-side concurrency and operational considerations. Useful as a production case study for Swift beyond client applications.
- [a brief mention in a 2024 WWDC video](https://youtu.be/OWNjtWUb9bs?t=79) — iOS Dev Weekly · Issue 715 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `20th June 2025`
  **NeKI brief:** Details of how Apple use Swift in server environments have been hard to come by. It’s clear Apple care deeply about this subject from the sustained work they do on NIO and related packages. That said, apart from a brief mention in a 2024 WWDC video, there…
- [These 4 code snippets won WWDC](https://justin.searls.co/posts/these-4-code-snippets-won-wwdc) — iOS Dev Weekly · Issue 715 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `20th June 2025`
  **NeKI brief:** Examines WWDC 2025 delivered on the one thing I was hoping to see from WWDC 2024: free, unlimited invocation of Apple's on-device language models by developers. It may…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Don‘t Liquid Glass All the Things](https://david-smith.org/blog/2025/06/17/design-dary-liquid-glass-everything) — iOS Dev Weekly · Issue 715 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `20th June 2025`
  **NeKI brief:** Argues for deliberate adoption of Liquid Glass rather than applying it indiscriminately across an interface. It offers a design-review perspective for separating places where the new material improves hierarchy from places where it distracts or weakens clarity.
- [WWDC25: Highlights as an iOS Developer](https://www.youtube.com/watch?v=__RoIeqfrSY) — Those Who Swift · Issue 219 — Video · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-19`
  **NeKI brief:** Reviews WWDC25: Highlights as an iOS Developer. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Developer experience wins from WWDC25](https://tuist.dev/blog/2025/06/10/wwdc) — iOS Dev Weekly · Issue 714 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `13th June 2025`
  **NeKI brief:** Explains Developer experience wins from WWDC25, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [FlipKit](https://danielsaidi.com/blog/2025/06/01/introducing-flipkit-for-swiftui) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** Daniel Saidi’s article introduces FlipKit, a SwiftUI component for flip-style animations and transitions. Use it as a focused implementation example, checking API maintenance, accessibility behavior, and performance before adding the package to an app.
- [Automatic Observation Tracking in UIKit and AppKit: The Feature Apple Forgot to Mention | Peter Steinberger](https://steipete.me/posts/2025/automatic-observation-tracking-uikit-appkit) — SwiftLee Weekly · Issue 275 — Article · Topics: Apple Platform Ecosystem · macOS & AppKit · UIKit
  **Published:** `2025-06-12T15:03:23.000Z`
  **NeKI brief:** Explores automatic Observation tracking in UIKit and AppKit. Use it when imperative views should react to observable model reads without manually registering broad notifications.
- [All New Frameworks Presented at WWDC 25](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc25) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Catalogues frameworks introduced at WWDC 2025. Use it as a broad inventory for technology scouting, then prioritize a concrete use case and consult the corresponding primary API documentation.
- [Marco Eidinger](https://hashnode.com/@MarcoEidinger) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Marco Eidinger's Hashnode profile collects articles and experiments around developer tooling and Apple-platform technologies. Use it as an author index for related posts, evaluating each individual article rather than treating the profile as a single technical source.
- [Apple Intelligence APIs](https://alexanderlogan.co.uk/blog/wwdc25/01-apple-intelligence) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: AI Development · Apple Platform Ecosystem · Concurrency
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** The first part of a Foundation Models overview maps Apple Intelligence APIs relevant to app developers. Use it to orient implementation research, then cross-check model availability, privacy, and entitlement details against current Apple material.
- [parts here](https://alexanderlogan.co.uk/blog/wwdc25/02-apple-intelligence-tools) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Alex explains how developers can enhance on-device large language models with custom Swift tools letting their apps invoke system APIs or services (like HealthKit or network calls) and feed the real results back into the AI for richer responses.
- [What’s New with SwiftUI 26](https://dimillian.medium.com/whats-new-with-swift-26-f17e98b07c87) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Surveys SwiftUI 26 changes from a practitioner's perspective. Use it as a discovery index for APIs worth evaluating, then confirm behavior and availability in the official SDK documentation before committing a migration.
- [WWDC 2025 Group Lab Transcript](https://gist.github.com/samhenrigold) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Provides a concrete technical reference through WWDC 2025 Group Lab Transcript, useful for examining the surrounding design, tooling, or ecosystem discussion before choosing an implementation direction.
- [What It’s Like Attending WWDC25 at Apple Park](https://www.youtube.com/watch?v=66W2-H1xxnY) — Those Who Swift · Issue 218 — Video · Topics: Apple Platform Ecosystem · Personal Essays
  **Published:** `2025-06-11`
  **NeKI brief:** Reviews What It’s Like Attending WWDC25 at Apple Park. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [countless other events](https://github.com/twostraws/wwdc) — iOS Dev Weekly · Issue 713 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Developer Tools
  **Published:** `6th June 2025`
  **NeKI brief:** If you have a ticket and are going to California, I hope you have a wonderful time at the event. If you’ll be there without a ticket, I hope you have a wonderful time at CommunityKit and One More Thing, and the countless other events during the week!
- [few tickets remaining](https://www.eventbrite.com/e/james-dempsey-and-the-breakpoints-live-near-wwdc-benefit-concert-2025-tickets-1369110078099) — iOS Dev Weekly · Issue 713 — Tutorial · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `6th June 2025`
  **NeKI brief:** Describes a James Dempsey and the Breakpoints benefit concert near WWDC. It is publicly reachable but event promotion rather than Knowledge Index reading; retain only if central editorial policy explicitly allows this category.
- [livestream](https://jamesdempsey.net/2025/06/04/live-near-wwdc-2025-livestream.html) — iOS Dev Weekly · Issue 713 — Tutorial · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Community & Business
  **Published:** `6th June 2025`
  **NeKI brief:** Of course, WWDC wouldn’t be complete without a James Dempsey and the Breakpoints benefit concert, and this year it’s supporting Techtonica. You’ll be happy to hear there are a few tickets remaining, or a livestream if you can’t be there in person.
- [The pregame quiz ’25](https://www.swiftjectivec.com/wwdc-2025-the-pregame-quiz) — iOS Dev Weekly · Issue 713 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `6th June 2025`
  **NeKI brief:** Presents W.W.D.C. 2025: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [RocketSim Meetup at CommunityKit](https://lu.ma/g4m3q37q) — SwiftLee Weekly · Issue 272 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Describes RocketSim Meetup at CommunityKit, providing the event-specific information needed to identify its Apple-platform community context.
- [WWDC community events](https://github.com/twostraws/wwdc?tab=readme-ov-file) — iOS Dev Weekly · Issue 711 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Developer Tools
  **Published:** `9th May 2025`
  **NeKI brief:** I won’t be making the trip across to Cupertino this year, but if you’re making the trip then the best place to find out what’s going on all week is the WWDC community events repository, which is still accepting updates if you spot anything missing.
- [🎥 FREE Webinar: Automating Multiplatform App Releases](https://streamyard.com/watch/BwQ2t4Q5aCkk) — iOS CI Newsletter · Issue 67 — Article · Topics: Apple Platform Ecosystem · CI/CD & Automation
  **Published:** `2025-05-04T00:00:00.000Z`
  **NeKI brief:** Summarises FREE Webinar: Automating Multiplatform App Releases for Apple Platform Ecosystem and CI/CD & Automation. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [A flowing WebGL gradient, deconstructed](https://alexharri.com/blog/webgl-gradients) — iOS Dev Weekly · Issue 709 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `25th April 2025`
  **NeKI brief:** Deconstructs a flowing gradient built with a WebGL shader, noise functions, and mathematical transforms. The rendering ideas transfer well to Metal or custom graphics work when a polished animated background needs an explainable, tunable implementation.
- [latest post](https://snopia.net/en/blog/recipe-sticker-effect-swiftui) — iOS Dev Weekly · Issue 709 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `25th April 2025`
  **NeKI brief:** Presents latest post for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [article](https://swiftrocks.com/how-im-using-ai-for-software-engineering?ref=createwithswift.com) — Create with Swift · Issue 57 — Article · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2025-04-18T15:00:48.000Z`
  **NeKI brief:** Welcome to this week's edition of our newsletter.With WWDC25 one week closer, the community is continuing to buzz with hopes and ideas for the future of developer tools. Fatbobman shares his vision for the evolution of Xcode, where AI remains a recurring…
- [interesting article celebrating 20 years of Git](https://blog.gitbutler.com/20-years-of-git) — iOS Dev Weekly · Issue 707 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `11th April 2025`
  **NeKI brief:** Examines Twenty years ago, Git was born. How did this unlikely "information manager" take over the world?. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — SwiftLee Weekly · Issue 264 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `2025-03-25T15:06:57.000Z`
  **NeKI brief:** In this article, Matt shows his journey in understanding how the ModelActor protocol and how Swift Data deals with concurrency in the system.
- [mcp-swift-sdk](https://github.com/loopwork-ai/mcp-swift-sdk) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** mcp-swift-sdk implements Model Context Protocol server and client concepts in Swift. Use it when exposing Apple-platform data or app capabilities to an agent through typed tools rather than maintaining a bespoke JSON protocol.
- [🍎 Running Xcode in unsupported macOS versions](https://marcelvoss.com/2025/tricking-xcode-into-running-on-an-unsupported-macos) — iOS CI Newsletter · Issue 61 — Article · Topics: Apple Platform Ecosystem · Personal Essays · Xcode
  **Published:** `2025-02-09T00:00:00.000Z`
  **NeKI brief:** Examines Running Xcode in unsupported macOS versions in the context of Apple Platform Ecosystem and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Objective by the Sea](https://objectivebythesea.org/v7/index.html) — iOS Dev Weekly · Issue 697 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Community & Business
  **Published:** `31st January 2025`
  **NeKI brief:** The Objective by the Sea event might not be directly relevant to your everyday work as a security conference focused on Apple platforms. However, it’s close enough that you’ll almost certainly find something here to interest you.
- [📦 The Tuist Swift Package Manager Registry](https://tuist.dev/blog/2025/01/22/announcing-tuist-registry) — iOS CI Newsletter · Issue 60 — Article · Topics: Apple Platform Ecosystem · Swift · Swift Package Manager
  **Published:** `2025-01-28T00:00:00.000Z`
  **NeKI brief:** Examines The Tuist Swift Package Manager Registry in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple WWDC YouTube videos update](https://www.youtube.com/@AppleDeveloper/videos) — Those Who Swift · Issue 197 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2025-01-17`
  **NeKI brief:** Reviews Apple WWDC YouTube videos update. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Exploring TabView Advancements in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/exploring-tabview-advancements-in-swiftui-part-1) — SwiftUI Weekly · SwiftUI Weekly - Issue #205 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-12-16T17:10:10.299Z`
  **NeKI brief:** Explores newer TabView configuration and presentation APIs in SwiftUI. Useful when building adaptive tab navigation that needs explicit selection, customization, or platform-aware behavior.
- [SwiftUI Zoom Navigation Transitions: Add a Touch of Magic to Your App](https://www.stphndxn.com/swiftui-zoom-navigation-transitions-add-a-touch-of-magic-to-your-app) — SwiftUI Weekly · SwiftUI Weekly - Issue #204 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-12-03T07:24:48.832Z`
  **NeKI brief:** Demonstrates zoom navigation transitions between SwiftUI source and destination views. Useful for preserving visual continuity when tapping thumbnails into detail screens.
- [anyway](https://eclecticlight.co/2024/11/08/why-cpu-in-activity-monitor-isnt-what-you-think) — iOS Dev Weekly · Issue 687 — Article · Topics: Apple Platform Ecosystem · Developer Career & Practice · Swift
  **Published:** `15th November 2024`
  **NeKI brief:** Examines One of the most common reasons for opening Activity Monitor is to check the % CPU of processes that might be running out of control. How accurate are those figures, though, and sho. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [let me know what you hope Apple is working on](https://docs.google.com/forms/d/e/1FAIpQLScveGrTMcVtYdNnA-Uv_TObuctur2Duzfn2tJynQpwmM43RDQ/viewform) — iOS Dev Weekly · Issue 684 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th October 2024`
  **NeKI brief:** It’s almost certainly too late for feedback to influence Apple’s priorities for next year’s releases, but I’d love to know what you’d all prioritise. I’d love it if you let me know what you hope Apple is working on for WWDC 2025.
- [A Cozy WWDC](https://www.toddheberlein.com/blog/2024/10/3/a-cozy-wwdc) — iOS Dev Weekly · Issue 682 — Article · Topics: Apple Platform Ecosystem
  **Published:** `11th October 2024`
  **NeKI brief:** Presents A Cozy WWDC, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Removing 58000 lines of code using XcodeGen](https://mokacoding.com/blog/how-xcodegen-reducet-the-tdd-in-swift-codebase-by-58-000-lines) — iOS CI Newsletter · Issue 52 — Article · Topics: Apple Platform Ecosystem · Swift · Xcode
  **Published:** `2024-10-06T00:00:00.000Z`
  **NeKI brief:** Examines Removing 58000 lines of code using XcodeGen in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Insetting Scrollable Views’ Content With contentMargins In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/insetting-scrollable-views-content-with-contentmargins-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #200 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-09-30T17:14:55.385Z`
  **NeKI brief:** Demonstrates contentMargins for insetting ScrollView content in SwiftUI. Useful for consistent readable edges and indicator placement without spacer-based layout hacks.
- [Create Custom Visual Effects with SwiftUI](https://yaacoub.github.io/articles/swift-tip/create-custom-visual-effects-with-swiftui-wwdc24) — SwiftUI Weekly · SwiftUI Weekly - Issue #199 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-09-09T19:49:43.177Z`
  **NeKI brief:** Summarizes the WWDC24 SwiftUI additions for building custom visual effects and highlights the APIs that enable richer rendering. Useful when evaluating platform-provided effect composition before adopting lower-level graphics techniques.
- [SwiftUI for Mac 2024](https://troz.net/post/2024/swiftui-mac-2024) — SwiftUI Weekly · SwiftUI Weekly - Issue #198 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-08-26T10:56:58.237Z`
  **NeKI brief:** Reviews SwiftUI for macOS in 2024, including windowing, menus, and platform-specific controls. Useful for auditing which shared views need deliberate Mac adaptations.
- [of course one survived](https://9to5mac.com/2024/05/20/dtk-mac-mini-scrapped-repaired) — iOS Dev Weekly · Issue 675 — Tutorial · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `23rd August 2024`
  **NeKI brief:** Discusses of course one survived, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [What's New in SwiftUI - WWDC24](https://yaacoub.github.io/articles/swift-tip/what-s-new-in-swiftui-wwdc24) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Summarizes WWDC24 SwiftUI additions and their intended use cases. Useful as a release-oriented checklist when deciding which iOS 18 APIs can replace custom implementations.
- [Build Multilingual Ready Apps](https://yaacoub.github.io/articles/swift-tip/build-multilingual-ready-apps-wwdc24) — SwiftUI Weekly · SwiftUI Weekly - Issue #196 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2024-08-12T10:38:40.828Z`
  **NeKI brief:** Covers WWDC24 localization practices for multilingual Swift apps, including string handling and layout implications. Useful for finding hard-coded assumptions before expanding locale support.
- [🤯 Automatically migrate suites from XCTest to Swift Testing](https://github.com/giginet/swift-testing-revolutionary) — iOS CI Newsletter · Issue 47 — Source repository · Topics: Apple Platform Ecosystem · Swift · Testing
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Automatically migrate suites from XCTest to Swift Testing, relevant to Apple Platform Ecosystem and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [swift-testing](https://github.com/apple/swift-testing) — iOS CI Newsletter · Issue 47 — Source repository · Topics: Apple Platform Ecosystem · Swift · Testing
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for new macro-based open-source proof of concept Swift package, relevant to Macros & Metaprogramming and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Christopher Lawley](https://bento.me/chrislawley) — Fatbobman’s Swift Weekly · Issue 41 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `2024-07-22T12:01:42.375Z`
  **NeKI brief:** Chris Lawley's profile aggregates his developer and creative work, including Apple-platform projects and educational material. Use it as an author or product discovery page, not as a substitute for the linked technical sources.
- [Understanding Swift 6 concurrency via evolution proposal analysis](https://www.massicotte.org/concurrency-swift-6-se-0431) — iOS Dev Weekly · Issue 669 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `12th July 2024`
  **NeKI brief:** Presents understanding swift 6 concurrency via evolution proposal analysis for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Diffuse reflection UV computation tool](https://www.elkraneo.com/diffuse-reflection-uv-computation-tool) — iOS Dev Weekly · Issue 668 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `5th July 2024`
  **NeKI brief:** The page documents a tool for computing diffuse-reflection UV data and explains its use in a graphics or rendering workflow.
- [Using TextRenderer to create highlighted text](https://alexanderweiss.dev/blog/2024-06-24-using-textrenderer-to-create-highlighted-text) — SwiftUI Weekly · SwiftUI Weekly - Issue #192 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-07-02T09:09:59.000Z`
  **NeKI brief:** Uses TextRenderer to draw highlighted text in SwiftUI. Useful for search results, annotation, or syntax emphasis where attributed-string styling alone is insufficient.
- [My Favorite SwiftUI Updates in iOS 18](https://www.youtube.com/watch?v=aCbh9LmIZTI) — SwiftUI Weekly · SwiftUI Weekly - Issue #192 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-02T09:09:59.000Z`
  **NeKI brief:** Reviews notable SwiftUI updates arriving with iOS 18. Useful as a visual overview before drilling into individual API documentation and deployment constraints.
- [WWDC Notes](https://wwdcnotes.github.io/WWDCNotes/documentation/wwdcnotes/wwdc24?ref=createwithswift.com) — Create with Swift · Issue 18 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2024-06-21T15:00:36.000Z`
  **NeKI brief:** We are still looking into this year's WWDC which was jam-packed with exciting announcements and innovative new features and frameworks.
- [contributing](https://wwdcnotes.github.io/WWDCNotes/documentation/wwdcnotes/contributing?ref=createwithswift.com) — Create with Swift · Issue 18 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2024-06-21T15:00:36.000Z`
  **NeKI brief:** We are still looking into this year's WWDC which was jam-packed with exciting announcements and innovative new features and frameworks.
- [WWDC24 Bento Summaries](https://thatvirtualboy.com/wwdc24-bentos) — iOS Dev Weekly · Issue 666 — Article · Topics: Apple Platform Ecosystem
  **Published:** `21st June 2024`
  **NeKI brief:** Examines The WWDC24 Keynote was jam packed with announcements and updates to all of Apple’s major operating systems, including visionOS, macOS, iOS, watchOS, and iPadOS. The keynote even co. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Zoom navigation transition in SwiftUI](https://augmentedcode.io/2024/06/17/zoom-navigation-transition-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #191 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-06-17T19:22:55.398Z`
  **NeKI brief:** Implements SwiftUI zoom navigation transitions with matched source and destination content. Useful for building detail navigation that retains the user's visual point of origin.
- [Louie Mantia, Jr](https://lmnt.me/intro) — Fatbobman’s Swift Weekly · Issue 36 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2024-06-17T12:00:46.941Z`
  **NeKI brief:** Provides contextual background on Louie Mantia, Jr, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [WWDC Notes 2024](https://wwdcnotes.github.io/WWDCNotes/documentation/wwdcnotes) — iOS Dev Weekly · Issue 665 — Article · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `14th June 2024`
  **NeKI brief:** There have been some changes to WWDC Notes for this year. I almost missed this, because the old site has no links to the new one, which is very strange! However, the project is alive and well, which is great news! This year’s notes are hosted with DocC, and…
- [Hidde van der Ploeg](https://mastodon.design/@hidde) — iOS Dev Weekly · Issue 665 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `14th June 2024`
  **NeKI brief:** What a handy page full of example 3D models Apple has provided everyone! Thanks so much to Hidde van der Ploeg for pointing it out!
- [Dark Mode App Icons](https://lmnt.me/blog/dark-mode-app-icons.html) — iOS Dev Weekly · Issue 665 — Article · Topics: Cross-Platform & Web
  **Published:** `14th June 2024`
  **NeKI brief:** Examines Dark Mode App Icons. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Live near WWDC](https://youtu.be/xK4X5Src4oQ?t=1197) — iOS Dev Weekly · Issue 665 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `14th June 2024`
  **NeKI brief:** Examines Continuing a WWDC-week tradition that began in 2012, the annual James Dempsey and the Breakpoints show is back for 2024!Our musical band of nerds, techies, a. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [StyleGuide](https://apps.apple.com/us/app/styleguide-hig-menubar-app/id6503706164) — iOS Dev Tools · iOS Dev Tools: StyleGuide, AppScreens, AHAPpy — Article · Topics: Apple Platform Ecosystem
  **Published:** `2024-06-13T17:58:49.715Z`
  **NeKI brief:** StyleGuide previews Apple-platform typography, colors, and sizes against Human Interface Guidelines concepts. Follow it for a concrete design-validation workflow before committing visual choices to an iOS or macOS interface.
- [What is New in SwiftUI After WWDC 24](https://twtr.to/d5ygM) — Fatbobman’s Swift Weekly · Issue 35 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** This shortened link points to a community resource about what changed in SwiftUI after WWDC24. Resolve and inspect the destination before relying on it, then verify version-specific claims against Apple's release notes.
- [老司机技术](https://github.com/SwiftOldDriver/iOS-Weekly) — Fatbobman’s Swift Weekly · Issue 35 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** Indexes Chinese iOS development reading and project links in a repository-friendly format. Use it as a discovery route for community material, then verify each linked source independently before relying on it.
- [Michie Ang](https://www.wwdcscholars.com/s/4A4B50FA-4D81-49E5-B38A-7AB4B5710BA1) — iOS Dev Weekly · Issue 664 — Article · Topics: Apple Platform Ecosystem
  **Published:** `7th June 2024`
  **NeKI brief:** When I congratulated the WWDC student scholarship winners a few weeks ago, I asked if anyone knew of a replacement for the sadly abandoned WWDC Students repositories. I had no responses to that request, but I found the successor project today, and it’s…
- [Concurrency in Swift 6](https://www.massicotte.org/concurrency-swift-6-se-401) — iOS Dev Weekly · Issue 664 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `7th June 2024`
  **NeKI brief:** Presents concurrency in swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [very long list of everything](https://nonstrict.eu/wwdcindex/all) — iOS Dev Weekly · Issue 660 — Article · Topics: Apple Platform Ecosystem
  **Published:** `10th May 2024`
  **NeKI brief:** The WWDC index provides a searchable public catalogue of Apple's developer-session videos and related session information.
- [The Engineering Challenges of Scaling ChatGPT](https://newsletter.pragmaticengineer.com/p/scaling-chatgpt) — iOS Dev Weekly · Issue 658 — Tutorial · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `26th April 2024`
  **NeKI brief:** Presents the engineering challenges of scaling chatgpt for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Pulse](https://github.com/kean/Pulse) — iOS Dev Tools · iOS Dev Tools: Pow, Maccy, Pulse — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Networking
  **Published:** `2024-04-25T13:41:52.260Z`
  **NeKI brief:** Provides the public source repository for Pulse. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Alamofire](https://github.com/Alamofire/Alamofire) — iOS Dev Tools · iOS Dev Tools: Pow, Maccy, Pulse — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Networking
  **Published:** `2024-04-25T13:41:52.260Z`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
- [Get](https://github.com/kean/Get) — iOS Dev Tools · iOS Dev Tools: Pow, Maccy, Pulse — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Networking
  **Published:** `2024-04-25T13:41:52.260Z`
  **NeKI brief:** Get provides Swift networking or HTTP abstractions. Follow its source for concrete request, response, and cancellation behavior, then compare its concurrency and error model with the application’s networking layer.
- [SwiftHeroes](https://swiftheroes.com/2024?ref=createwithswift.com) — Create with Swift · Issue 8 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2024-04-12T15:00:48.000Z`
  **NeKI brief:** Next week Flora Damiano will present “Crafting Better App Icons” at SwiftHeroes in Turin, Italy. She will share her process and insights on creating app icons for various Apple platforms.
- [Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube](https://www.youtube.com/@AppleDeveloper/playlists?ref=ioscodereview.com) — iOS Code Review · Issue 67 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2024-04-03T12:22:37.000Z`
  **NeKI brief:** Records Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube as a visual walkthrough relevant to Apple Platform Ecosystem and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Adwaita for Swift](https://github.com/AparokshaUI/adwaita-swift) — Fatbobman’s Swift Weekly · Issue 25 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2024-04-01T22:00:13.872Z`
  **NeKI brief:** Adwaita for Swift applies SwiftUI-like declarative ideas to GTK-based Linux applications. Use it when assessing how much view composition can be shared across Apple and Linux UI targets.
- [released Swift 5.10](https://www.swift.org/blog/swift-5.10-released?ref=createwithswift.com) — Create with Swift · Issue 3 — Article · Topics: Swift · Testing · Xcode
  **Published:** `2024-03-08T16:00:49.000Z`
  **NeKI brief:** Summarises What's new in Swift 5.10 for Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [🤩 An unofficial App Store Connect status page](https://www.runway.team/is-app-store-connect-down) — iOS CI Newsletter · Issue 36 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Examines An unofficial App Store Connect status page in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📝 Platform-specific release notes with Xcode Cloud](https://www.finnvoorhees.com/words/platform-specific-release-notes-with-xcode-cloud) — iOS CI Newsletter · Issue 33 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Xcode
  **Published:** `2024-01-14T00:00:00.000Z`
  **NeKI brief:** Summarises Platform-specific release notes with Xcode Cloud for App Distribution & Store Operations and Apple Platform Ecosystem. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Flora Damiano](https://www.behance.net/FloraDamiano) — iOS Dev Weekly · Issue 643 — Article · Topics: Apple Platform Ecosystem · Testing
  **Published:** `12th January 2024`
  **NeKI brief:** Flora Damiano's portfolio showcases visual and interaction design work. Use it as a design reference when discussing visual language, illustration, and product presentation rather than as an engineering source.
- [SwiftUI geometryGroup() Guide: From Theory to Practice](https://medium.com/the-swift-cooperative/swiftui-geometrygroup-guide-from-theory-to-practice-1a7f4b04c4ec) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Explains geometryGroup() and the animation anomalies it addresses by grouping a view's geometry before interpolation. Useful when nested SwiftUI animations distort layout or require coordinated geometry without rebuilding the hierarchy.
- [SVGView](https://github.com/exyte/SVGView) — iOS Dev Tools · 🔨 Raycast, Build Distro, SVGView — Source repository · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2023-11-23T16:19:32.692Z`
  **NeKI brief:** SVGView renders SVG content in SwiftUI or Apple-platform interfaces. Follow its source for concrete parsing, layout, and rendering behavior, then evaluate SVG feature coverage and performance for the intended assets.
- [Mastering TipKit: Basics](https://itnext.io/mastering-tipkit-basics-dcccfdbc9927) — SwiftUI Weekly · SwiftUI Weekly - Issue #166 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2023-10-31T07:27:47.287Z`
  **NeKI brief:** Introduces TipKit's core model for defining, displaying, and controlling contextual tips in an app. Useful when planning discoverability prompts with eligibility rules and dismissals instead of ad hoc overlays.
- [Apple’s use of Swift and SwiftUI in iOS 17](https://blog.timac.org/2023/1019-state-of-swift-and-swiftui-ios17) — iOS Dev Weekly · Issue 632 — Article · Topics: Swift · SwiftUI
  **Published:** `20th October 2023`
  **NeKI brief:** Reviews Swift and SwiftUI changes around iOS 17 with implementation context. Use it to orient migration work and identify which new APIs affect deployment targets or existing view architecture.
- [silicon](https://arun.is/blog/apple-mirage) — iOS Dev Weekly · Issue 631 — Article · Topics: Apple Platform Ecosystem · Developer Career & Practice · Swift
  **Published:** `13th October 2023`
  **NeKI brief:** Examines A short photoessay about my visit to a new permanent art installation at Apple Park. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Animating with PhaseAnimator in SwiftUI](https://augmentedcode.io/2023/09/04/animating-with-phaseanimator-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #159 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2023-09-11T10:23:27.802Z`
  **NeKI brief:** Introduces PhaseAnimator for driving a view through a sequence of animation phases. Useful when an interaction needs repeatable multi-step motion with phase-specific values rather than one undifferentiated animation.
- [Examples of animating SF symbols in SwiftUI](https://augmentedcode.io/2023/08/21/examples-of-animating-sf-symbols-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #156 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2023-08-21T19:48:52.195Z`
  **NeKI brief:** Demonstrates the SF Symbols animation presets introduced for SwiftUI, including appearance, emphasis, and replacement effects. Useful when choosing a semantic symbol animation that communicates state without custom artwork.
- [Applying metal shader to text in SwiftUI](https://augmentedcode.io/2023/08/07/applying-metal-shader-to-text-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #154 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-08-08T03:29:42.397Z`
  **NeKI brief:** Applies a simple Metal shader to SwiftUI text using the shader-related view modifiers introduced with WWDC 2023. A compact first example for learning how ShaderLibrary effects connect SwiftUI views to custom Metal code.
- [Migrating to the Observation framework in SwiftUI](https://tanaschita.com/20230807-migrating-to-observation) — SwiftUI Weekly · SwiftUI Weekly - Issue #154 — Article · Topics: Apple Platform Ecosystem · Macros & Metaprogramming · Swift
  **Published:** `2023-08-08T03:29:42.397Z`
  **NeKI brief:** Explains Introduced at WWDC23, Observation is a new Swift framework for tracking changes of properties. It uses the new macro system in Swift to transform Swift types to observable objects. Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [My WWDC Design Lab Experience](https://chriswu.com/posts/wwdc/designlab2023) — iOS Dev Weekly · Issue 620 — Article · Topics: Apple Platform Ecosystem
  **Published:** `28th July 2023`
  **NeKI brief:** Examines How my app improved. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Sign up here](https://create.unity.com/spatial) — iOS Dev Weekly · Issue 619 — Article · Topics: Apple Platform Ecosystem
  **Published:** `21st July 2023`
  **NeKI brief:** Examines Here we go! Apple talked about building visionOS apps in Unity at WWDC, and we now have a way to sign up for the beta. It’s unclear how many people/companies will get access, but with the visionOS beta being open to anyo Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [video covering his demo experience](https://youtu.be/n8-wTpiuZwE) — iOS Dev Weekly · Issue 618 — Video · Topics: Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games
  **Published:** `14th July 2023`
  **NeKI brief:** It’s been a few weeks since they were published, but I’ve had two videos on my mind recently, both covering the Vision Pro headset demos from WWDC. First, just a couple of days after the conference ended, Paul Hudson posted a video covering his demo…
- [Build an app using SwiftData](https://www.youtube.com/playlist?list=PLvUWi5tdh92wZ5_iDMcBpenwTgFNan9T7) — iOS Dev Weekly · Issue 617 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Explores Build an app using SwiftData, focusing on it’s a measure of how many new things were announced. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [In-app purchase updates from WWDC](https://www.revenuecat.com/blog/engineering/wwdc2023-highlights) — iOS Dev Weekly · Issue 615 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `23rd June 2023`
  **NeKI brief:** Examines RevenueCat developer advocate Charlie Chapman shares his first impressions from WWDC 2023, focusing on subscriptions, monetisations, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The debut of ButtonRepeatBehavior](https://serialcoder.dev/text-tutorials/swiftui/wwdc23-swiftui-the-debut-of-the-buttonrepeatbehavior-view-modifier) — iOS Dev Weekly · Issue 615 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `23rd June 2023`
  **NeKI brief:** Explores The debut of ButtonRepeatBehavior, focusing on when i first read the title of this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [On skipping tests](https://www.wwdcnotes.com/notes/wwdc20/10164?ref=ioscodereview.com) — iOS Code Review · Issue 51 — Article · Topics: Apple Platform Ecosystem · Testing · Xcode
  **Published:** `2023-06-22T13:14:57.000Z`
  **NeKI brief:** Examines On skipping tests in the context of Apple Platform Ecosystem and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [available for free on the WWDCNotes site](https://www.wwdcnotes.com/notes/wwdc23/10117) — iOS CI Newsletter · Issue 17 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2023-06-11T00:00:00.000Z`
  **NeKI brief:** Summarises available for free on the WWDCNotes site for App Distribution & Store Operations and Apple Platform Ecosystem. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [make sure to add it to the site](https://www.wwdcnotes.com/what-s-missing) — iOS CI Newsletter · Issue 17 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2023-06-11T00:00:00.000Z`
  **NeKI brief:** Examines make sure to add it to the site in the context of Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Download free report](https://yo.bitrise.io/mobile-devops-assessment-report-2023-download.html) — iOS Code Review · Issue 50 — Article · Topics: Apple Platform Ecosystem · Code Quality · Cross-Platform & Web
  **Published:** `2023-06-09T10:49:04.000Z`
  **NeKI brief:** Examines Download free report in the context of Code Quality and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [The unofficial WWDC app](https://github.com/insidegui/WWDC) — iOS Dev Weekly · Issue 613 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `9th June 2023`
  **NeKI brief:** The official Developer app is excellent and gets better every year, but I reach for this independently developed app when I want to stream (or download) a WWDC video. So, I’d like to thank Gui Rambo and all the contributors for their work every year in…
- [all the contributors](https://github.com/insidegui/WWDC/graphs/contributors) — iOS Dev Weekly · Issue 613 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `9th June 2023`
  **NeKI brief:** The official Developer app is excellent and gets better every year, but I reach for this independently developed app when I want to stream (or download) a WWDC video. So, I’d like to thank Gui Rambo and all the contributors for their work every year in…
- [All new frameworks presented at WWDC23](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc23) — iOS Dev Weekly · Issue 613 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `9th June 2023`
  **NeKI brief:** Catalogues the new frameworks presented at WWDC23 and provides a compact map of the platform additions introduced that year. Useful as historical orientation before consulting the current SDK documentation for each framework.
- [An Introduction to Grids in SwiftUI](https://cctplus.dev/an-introduction-to-grids-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #145 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2023-06-05T08:35:48.243Z`
  **NeKI brief:** Introduces SwiftUI grids as adaptive layout primitives for dynamic content and changing device sizes. Useful when a collection needs responsive rows and columns instead of a manually composed stack layout.
- [SwiftUI Notes Before WWDC 2023](https://mjtsai.com/blog/2023/05/30/swiftui-notes-before-wwdc-2023) — iOS Dev Weekly · Issue 612 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2nd June 2023`
  **NeKI brief:** Explores SwiftUI Notes Before WWDC 2023, focusing on michael tsai has done a fantastic job rounding up a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [online live stream](https://jamesdempsey.net/2023/06/01/live-near-wwdc-2023-update.html) — iOS Dev Weekly · Issue 612 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `2nd June 2023`
  **NeKI brief:** Examines Oh, and while I mention James, I linked to the James Dempsey and the Breakpoints live show last week, but there will also be an online live stream! I only wish it didn’t start at 3:30 am in my timezone! 😬 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Apple Platforms Developer @ Cascable AB](https://cascable.se/jobs) — iOS Dev Weekly · Issue 609 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `12th May 2023`
  **NeKI brief:** Explores Apple Platforms Developer @ Cascable AB, focusing on apple platforms developer @ cascable ab – cascable is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The launch of the Mojo language](https://www.fast.ai/posts/2023-05-03-mojo-launch.html) — iOS Dev Weekly · Issue 608 — Article · Topics: AI Development · Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `5th May 2023`
  **NeKI brief:** The fast.ai post announces the Mojo programming language and describes its goals for high-performance machine-learning and systems development.
- [Your WWDC Insurance Policy](https://www.revenuecat.com/docs/migrating-existing-subscriptions) — iOS Dev Weekly · Issue 607 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `28th April 2023`
  **NeKI brief:** Examines Importing existing purchase data to RevenueCat can be done server-side, or client-side. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift 5.8 Released](https://www.swift.org/blog/swift-5.8-released) — iOS Dev Weekly · Issue 603 — Article · Topics: Apple Platform Ecosystem · Swift · Swift Package Manager
  **Published:** `31st March 2023`
  **NeKI brief:** Presents a concrete implementation of Swift 5.8 Released!. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [daily reminder that it’s on its way](https://mrmacintosh.com/wwdc23-wallpaper-desktop-images-4k-downloads) — iOS Dev Weekly · Issue 603 — Article · Topics: Apple Platform Ecosystem
  **Published:** `31st March 2023`
  **NeKI brief:** daily reminder that it’s on its way. This link is retained as a technical reading lead for Apple-platform development.
- [Swift 5.9 Release Process](https://forums.swift.org/t/swift-5-9-release-process/63557) — iOS Dev Weekly · Issue 600 — Article · Topics: Apple Platform Ecosystem · Swift · Xcode
  **Published:** `10th March 2023`
  **NeKI brief:** Explores Swift 5.9 Release Process, focusing on talking of new swift versions, i think this is the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [shrinkydink](https://techreflect.net/2022/06/rising-from-the-ashes-stage-manager) — iOS Dev Weekly · Issue 590 — Article · Topics: Apple Platform Ecosystem
  **Published:** `30th December 2022`
  **NeKI brief:** Examines Every year I worked on macOS/iOS, I would get attached to a handful of features that would ultimately get axed. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift for Android](https://github.com/apple/swift/blob/main/docs/Android.md) — iOS Dev Weekly · Issue 577 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Yes, you can write Swift for Android, but I think it’s fair to say that JetBrains is promoting Kotlin as a language you can use with Apple platforms more than Apple is promoting Swift for Android development. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [a language you can use with Apple platforms](https://kotlinlang.org/lp/mobile) — iOS Dev Weekly · Issue 577 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Kotlin Multiplatform is a technology for reusing up to 100% of your code across Android, iOS, web, and desktop, with Compose Multiplatform for shared UIs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [the official overview](https://www.swift.org/blog/swift-language-updates-from-wwdc22?ref=ioscodereview.com) — iOS Code Review · Issue 32 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2022-09-22T10:30:02.000Z`
  **NeKI brief:** Explores Swift language announcements from WWDC22, focusing on it’s easy to get distracted by all the swiftui, uikit. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift 5.7 Released](https://www.swift.org/blog/swift-5.7-released) — iOS Dev Weekly · Issue 576 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `16th September 2022`
  **NeKI brief:** Summarises the full list of evolution proposals released in 5.7 for Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [An Open Source Implementation of Code Signing and Notarization](https://gregoryszorc.com/blog/2022/08/08/achieving-a-completely-open-source-implementation-of-apple-code-signing-and-notarization) — iOS Dev Weekly · Issue 571 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th August 2022`
  **NeKI brief:** The page covers “An Open Source Implementation of Code Signing and Notarization” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [PyOxidizer](https://github.com/indygreg/PyOxidizer) — iOS Dev Weekly · Issue 571 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th August 2022`
  **NeKI brief:** It wasn’t a huge announcement from this year’s WWDC, but the Notary API was a big deal for some sections of this community. Here’s Gregory Szorc talking about Robin Lambertz’s pull request to PyOxidizer that allows code signing and notarization from Linux. 👍
- [Swift language announcements from WWDC22](https://www.swift.org/blog/swift-language-updates-from-wwdc22) — iOS Dev Weekly · Issue 566 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `8th July 2022`
  **NeKI brief:** Explores Swift language announcements from WWDC22, focusing on it’s easy to get distracted by all the swiftui, uikit. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Augmented Reality Digital Lounge from WWDC22](https://yono.ai/articles/wwdc22-arkit-realitykit-usdz-digital-lounge) — iOS Dev Weekly · Issue 566 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Spatial Computing
  **Published:** `8th July 2022`
  **NeKI brief:** Summarizes the WWDC22 ARKit, RealityKit, and USDZ digital-lounge material and points to the related demonstrations. Useful for orienting an augmented-reality exploration before consulting the current ARKit and RealityKit documentation.
- [Machine Learning](https://yono.ai/articles/wwdc22-machine-learning-digital-lounge) — iOS Dev Weekly · Issue 566 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Tools
  **Published:** `8th July 2022`
  **NeKI brief:** Summarizes the WWDC22 machine-learning digital-lounge material and its demonstrations. Useful as a compact orientation to the session topics before consulting Apple’s current machine-learning frameworks and documentation.
- [Creating custom extension points for Mac apps with ExtensionKit](https://rambo.codes/posts/2022-06-27-creating-custom-extension-points-with-extensionkit) — iOS Dev Weekly · Issue 565 — Article · Topics: Apple Platform Ecosystem
  **Published:** `1st July 2022`
  **NeKI brief:** Examines Gui Rambo writes about his coding and reverse engineering adventures. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using ViewThatFits to replace GeometryReader in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5jcmVhdGV3aXRoc3dpZnQuY29tL3VzaW5nLXZpZXd0aGF0Zml0cy10by1yZXBsYWNlLWdlb21ldHJ5cmVhZGVyLWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZThjMmRiMDAtOWNjYy00ZDliLWJiOTYtZDFlNjA1NzYxYTk3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhOGIyNTg0LTJhM2MtNDlkNS04ZTc5LTUzNTY3ZTQyNTk2NiIsImlhdCI6MTY3NDA2MjU1OC44NzMsImlzcyI6Im9yY2hpZCJ9.SNpycsd5yJT-2Mbxz9F_-rNT5IeEMU7DZI1u9fqXj3A) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Demonstrates ViewThatFits for selecting a layout that fits available space instead of measuring manually with GeometryReader. Useful for responsive controls that need graceful alternatives across compact and regular widths.
- [recap of WWDC](https://beckyhansmeyer.com/2022/06/13/reflections-on-wwdc-2022) — iOS Dev Weekly · Issue 563 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `17th June 2022`
  **NeKI brief:** Examines A blog about Apple and indie iOS development using Swift and SwiftUI. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftUI Digital Lounge archive](https://midnight-beanie-ccb.notion.site/swiftui-lounge-wwdc22-e20094b91f074398ba395c3fa245e63d) — iOS Dev Weekly · Issue 563 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `17th June 2022`
  **NeKI brief:** Explores SwiftUI Digital Lounge archive, focusing on the digital lounges were great again this year, but they. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [open-source](https://github.com/WWDCNotes/Content) — iOS Dev Weekly · Issue 562 — Source repository · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Developer Tools
  **Published:** `10th June 2022`
  **NeKI brief:** Examines WWDCNotes.com content. Contribute to WWDCNotes/Content development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [via Docker and VS Code development containers](https://finestructure.co/blog/2022/6/9/trying-new-swift-features-on-linux-via-vs-code-dev-containers) — iOS Dev Weekly · Issue 562 — Article · Topics: Apple Platform Ecosystem · Product Design · Swift
  **Published:** `10th June 2022`
  **NeKI brief:** Explores wrote a simple tutorial covering this feature, focusing on of course, xcode also supports all these features! so why. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Talk Show Live From WWDC 2022](https://www.youtube.com/watch?v=WfnvsepVJC0) — iOS Dev Weekly · Issue 562 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `10th June 2022`
  **NeKI brief:** I’ve not watched this as it was only published an hour ago, but it’ll be great, as always! Unless things have changed significantly, it’ll be John Gruber, Craig Federighi, and Greg Joswiak with 90 minutes of additional context about this week.
- [The Talk Show Live](https://daringfireball.net/linked/2022/06/01/the-talk-show-live-from-wwdc-2022) — iOS Dev Weekly · Issue 561 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `3rd June 2022`
  **NeKI brief:** Don’t forget the community events, either! I was going to try and summarise everything that’s going on here until I saw that Apple had produced a wonderful collection of more than ten community events happening around the world. The only missing event I know…
- [requirement to add retina assets](https://thenextweb.com/news/apple-requires-iphone-developers-to-submit-retina-screenshots-may-herald-end-of-3gs-era) — iOS Dev Weekly · Issue 556 — Article
  **Published:** `29th April 2022`
  **NeKI brief:** The article reports Apple's requirement for Retina screenshots and assets and discusses what the change meant for iPhone developers.
- [DocC is Now Open-Source](https://swift.org/blog/swift-docc) — iOS Dev Weekly · Issue 529 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `15th October 2021`
  **NeKI brief:** When DocC debuted at WWDC, Apple mentioned that the plan was to open-source the project, and here it is! I’d say the tool has had quite a mixed reception so far, although I remain optimistic about it. Contributions are open, and while there’s no formal…
- [contributions guide](https://github.com/apple/swift-docc/blob/main/CONTRIBUTING.md) — iOS Dev Weekly · Issue 529 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `15th October 2021`
  **NeKI brief:** Examines Documentation compiler that produces rich API reference documentation and interactive tutorials for your Swift framework or package. - swift-docc/CONTRIBUTING.md at main · swiftlan. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Keeping WWDC videos and sample code current](https://dimsumthinking.com/Blog/2021/08/30-KeepingCurrent.html) — iOS Dev Weekly · Issue 523 — Article · Topics: Apple Platform Ecosystem · Concurrency · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Keeping WWDC videos and sample code current, focusing on here’s another advantage of not having on-stage presentations at wwdc.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Modern Concurrency in Swift](https://www.andyibanez.com/posts/modern-concurrency-in-swift-introduction) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Explores Modern Concurrency in Swift, focusing on here’s a wonderful set of articles from andy ibanez that. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [async/await](https://www.andyibanez.com/posts/understanding-async-await-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Explores async/await, focusing on here’s a wonderful set of articles from andy ibanez that he’s been working on since wwdc. it’s a seven-part series covering async/await,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [converting your existing concurrent code](https://www.andyibanez.com/posts/converting-closure-based-code-into-async-await-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Explores converting your existing concurrent code, focusing on here’s a wonderful set of articles from andy ibanez that. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [async let](https://www.andyibanez.com/posts/structured-concurrency-in-swift-using-async-let) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Explains async let as a structured-concurrency tool for starting a small, fixed set of independent operations. Follow it when parallel work has a clear parent scope and should be awaited, cancelled, and error-handled with that scope.
- [group tasks](https://www.andyibanez.com/posts/structured-concurrency-with-group-tasks-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Covers task groups for dynamically sized concurrent work, including how results flow back to the parent task. Useful when async let is too fixed and an operation must spawn, collect, and contain a variable number of child tasks.
- [unstructured concurrency](https://www.andyibanez.com/posts/introduction-to-unstructured-concurrency-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Introduces unstructured concurrency and the lifetime it creates outside a caller’s structured task tree. Follow it when work intentionally outlives the current scope, and use its framing to avoid confusing that choice with ordinary child-task concurrency.
- [detached tasks](https://www.andyibanez.com/posts/unstructured-concurrency-with-detached-tasks-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Explains detached tasks as an unstructured-concurrency escape hatch with different inheritance and isolation characteristics. Useful when considering background work that must not inherit actor context, priority, or task-local values, and when that trade-off is justified.
- [actors](https://www.andyibanez.com/posts/understanding-actors-in-the-new-concurrency-model-in-swift) — iOS Dev Weekly · Issue 519 — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **Published:** `6th August 2021`
  **NeKI brief:** Places actors within a broader modern-concurrency series, explaining their role in protecting mutable state. A useful companion to task-based examples when a design needs both asynchronous orchestration and an explicit isolation boundary for shared data.
- [What’s New in Unit Testing with Xcode 12.5?](https://qualitycoding.org/wwdc21-unit-testing) — iOS Dev Weekly · Issue 515 — Article · Topics: Apple Platform Ecosystem · Testing · Xcode
  **Published:** `9th July 2021`
  **NeKI brief:** Explores What’s New in Unit Testing with Xcode 12.5?, focusing on the two things that stuck out for me in this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI patterns evolution: view builders](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL2FydGljbGVzL3N3aWZ0dWktcGF0dGVybnMtdmlldy1idWlsZGVycy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIzNmNmNWJjYi1mMDU3LTQzN2EtOWY3Ni1jMDQ0NTc0YWQyYjciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZWMyZjUxYTYtZTFjYy00MWFjLThhMTgtZGQxN2QxMTE4ZjYwIiwiaWF0IjoxNjc0MDYyNjc3LjA2MSwiaXNzIjoib3JjaGlkIn0.1iTXRq_oB78yxzsqRJp_rX8sxGAwzmG5SZ-hO6mmvI4) — SwiftUI Weekly · SwiftUI Weekly - Issue #66 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2021-07-06T10:24:10.000Z`
  **NeKI brief:** Traces how SwiftUI view-builder patterns evolve as APIs become more expressive. Follow it when choosing between generic composition, result builders, and concrete helper views for maintainable screen structure.
- [The Droid (Stats) You’re Looking For](https://blog.curtisherbert.com/slopes-diaries-40-the-droid-stats-youre-looking-for) — iOS Dev Weekly · Issue 514 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `2nd July 2021`
  **NeKI brief:** Examines Curtis Herbert posted this the day before WWDC started, and while I wanted to link to it, that’s terrible timing! If you write an iOS-only app, it’s so easy to dismiss the idea of creating an Android version for so many Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Catalyst Sample Code Roundup](https://www.highcaffeinecontent.com/blog/20210605-Catalyst-Sample-Code-Roundup) — iOS Dev Weekly · Issue 513 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th June 2021`
  **NeKI brief:** I’ve had this article from Steve Troughton-Smith in my queue since just before WWDC, and with all the excitement about “new things”, it stayed there for a few weeks! I do want to make sure I link to it, though, so here it is. It’s a superb collection of…
- [Building a music recognization app in SwiftUI with ShazamKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3YXBuYW5pbGRob2wubWVkaXVtLmNvbS9idWlsZGluZy1hLW11c2ljLXJlY29nbml6YXRpb24tYXBwLWluLXN3aWZ0dWktd2l0aC1zaGF6YW1raXQtN2NhYjc2NDA3ZDEwP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiOTg1NDJmZTMtOWU5Zi00ZmY4LTk5YzAtNDQ4NzU3M2JkNjQyIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImUwZDE2NzkyLTFmZjUtNGEyMS05ODRjLTRlOTQxOGI5YTM5ZSIsImlhdCI6MTY3NDA2MjY3Ny4wMSwiaXNzIjoib3JjaGlkIn0.D1X3KuG_ZZVBpnjLs42Pwiu20YFyMkC-z5viuvXke6c) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Builds a SwiftUI music-recognition app around ShazamKit. Follow it to see how capture, matching results, permissions, and asynchronous updates are connected to observable UI state.
- [App Store Review Guidelines Updates for WWDC 2021](http://www.appstorereviewguidelineshistory.com/articles/2021-06-07-wwdc-2021) — iOS Dev Weekly · Issue 511 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `11th June 2021`
  **NeKI brief:** Examines WWDC 2021 - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Big improvements to UIButton in iOS 15](https://nemecek.be/blog/107/big-improvements-to-uibutton-in-ios-15) — iOS Dev Weekly · Issue 511 — Article · Topics: Apple Platform Ecosystem
  **Published:** `11th June 2021`
  **NeKI brief:** Who had “Huge changes to UIButton” on their WWDC bingo card? I know I didn’t! Here’s Filip Němeček with the low down on what’s changed. I’ll be happy to see some standardisation come back to button design with these changes.
- [organised by the Diversity in Swift team](https://www.eventbrite.com/o/diversity-in-swift-33499837783) — iOS Dev Weekly · Issue 510 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `4th June 2021`
  **NeKI brief:** The Eventbrite organiser page lists Diversity in Swift events and provides publicly readable information about the organiser's developer-community programme.
- [try! Swift DUB DUB](https://www.tryswift.co/dub-dub) — iOS Dev Weekly · Issue 510 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `4th June 2021`
  **NeKI brief:** Examines try! Swift is an immersive community gathering about Swift Language Best Practices, Application Development in Swift, Server-Side Swift, Open Source Swift, and the Swift Community. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [NSScreencast Remote Happy Hour](https://ti.to/ficklebits/wwdc-2021-happy-hour) — iOS Dev Weekly · Issue 510 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `4th June 2021`
  **NeKI brief:** WWDC.community is back and bigger than ever this year. There’s so much going on there, you really must check it out. There’s also WWDC Together, the AltConf Keynote stream, and the Ray Wenderlich WWDC Livecast for live streams and chat. There are also a few…
- [James Dempsey and the Breakpoints](https://vi.to/hubs/live-near-wwdc) — iOS Dev Weekly · Issue 510 — Article · Topics: Apple Platform Ecosystem
  **Published:** `4th June 2021`
  **NeKI brief:** The page presents the Live Near WWDC hub for James Dempsey and the Breakpoints, with publicly readable programme and event information.
- [AASA File Identifiers](https://lickability.com/blog/insidious-bugs-number-3-apple-app-site-association-file) — iOS Dev Weekly · Issue 509 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `28th May 2021`
  **NeKI brief:** We recently struggled with AASA while trying to make the SPI Playgrounds app respond to URLs. Documentation is sparse and spread over multiple WWDC videos, and we eventually decided not to implement it. So, I read this story from Michael Amundsen with…
- [apps scrolled from one end of this huge table to the other](https://www.flickr.com/photos/kepi/7389267724/in/photolist-ceubSG-cfXVRE-88TkoC-88Q7iB) — iOS Dev Weekly · Issue 508 — Article · Topics: Apple Platform Ecosystem
  **Published:** `21st May 2021`
  **NeKI brief:** Examines In 2008 Apple had a similar app display, except back then it was a bunch of monitors mounted to the wall. This year, it was a table full of iPads. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Comparing iPhone OS 1.0 with iOS 14 using tree maps](https://blog.timac.org/2020/1122-comparing-iphone-os-with-ios-14-using-tree-maps) — iOS Dev Weekly · Issue 484 — Article · Topics: Maps & Location
  **Published:** `27th November 2020`
  **NeKI brief:** Examines Alexandre Colucci is at it again, this time with a great visualisation of what types of files make up iOS releases over the years. As many people have noticed, it’s striking how much of iOS 1 was font files, but I think Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Evolution of Programming Languages – iPhone OS 1.0 to iOS 14](https://blog.timac.org/2020/1019-evolution-of-the-programming-languages-from-iphone-os-to-ios-14) — iOS Dev Weekly · Issue 479 — Article · Topics: Swift
  **Published:** `23rd October 2020`
  **NeKI brief:** Explains Evolution of Programming Languages – iPhone OS 1.0 to iOS 14, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Mastering ScrollView in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIwLzA5LzI0L21hc3RlcmluZy1zY3JvbGx2aWV3LWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiMjRiMzQ3YmQtZTA2NS00ZGJmLThjMTAtMzJhZjQ4ZTM1MTZmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6Ijk4ZDliYTZjLWE2NjAtNDdiOC1iZjg1LTQwZmU4ODY2OGViOCIsImlhdCI6MTY3NDA2MjczNi43OTIsImlzcyI6Im9yY2hpZCJ9.8uSewvaVO9CkH6aARNQquTsEmJ6KVckQz6RnAtixA_4) — SwiftUI Weekly · SwiftUI Weekly - Issue #29 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2020-09-28T20:44:06.000Z`
  **NeKI brief:** Surveys ScrollView composition, axes, indicators, and nested content in SwiftUI. Follow it when diagnosing scrolling layout behavior or choosing between a plain scroll container and a lazy collection.
- [UnofficialSandwiches](https://github.com/dempseyatgithub/UnofficialSandwiches) — iOS Dev Weekly · Issue 471 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `28th August 2020`
  **NeKI brief:** The page covers “UnofficialSandwiches” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [What’s New in Unit Testing?](https://qualitycoding.org/wwdc20-unit-testing) — iOS Dev Weekly · Issue 464 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `10th July 2020`
  **NeKI brief:** Reviews the unit-testing changes presented at WWDC 2020 and connects them to practical Xcode test workflows. Follow it when maintaining older XCTest infrastructure and checking which release-era features can simplify test organization or diagnostics.
- [this post appeared](https://pspdfkit.com/blog/2020/sponsoring-cocoapods) — iOS Dev Weekly · Issue 463 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines PSPDFKit is sponsoring the costs of hosting the CocoaPods CND. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple machine learning in 2020](https://machinethink.net/blog/new-in-apple-machine-learning-2020) — iOS Dev Weekly · Issue 463 — Article · Topics: AI Development · Apple Platform Ecosystem
  **Published:** `3rd July 2020`
  **NeKI brief:** Covers Apple machine learning in 2020, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [How SwiftUI can now be used to build entire iOS apps](https://wwdcbysundell.com/2020/building-entire-apps-with-swiftui) — iOS Dev Weekly · Issue 462 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines How SwiftUI can now be used to build entire iOS apps, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [bit of pre-WWDC trivia fun](https://www.eventbrite.com/e/pre-wwdc-virtual-trivia-tickets-108879668018) — iOS Dev Weekly · Issue 461 — Article · Topics: Apple Platform Ecosystem
  **Published:** `19th June 2020`
  **NeKI brief:** Here we go! 🚀 Things kick off this weekend with a bit of pre-WWDC trivia fun. Almost guaranteed to be chaos on Zoom, but I’m completely up for that, and will be there!
- [try! Swift social](https://www.holler.com/meetings/8KDfOw/register) — iOS Dev Weekly · Issue 461 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `19th June 2020`
  **NeKI brief:** Examines Holler is a content & media company. Shows, stories, and social-first video worth shouting about. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [browsing through your submissions](https://wwdc.github.io/2020) — iOS Dev Weekly · Issue 461 — Article · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `19th June 2020`
  **NeKI brief:** The page is a public WWDC 2020 submissions index that lets readers browse developer projects and related submission information.
- [Grab a spot here](https://ti.to/altconf/the-altconf-keynote-2020-happy-hour) — iOS Dev Weekly · Issue 461 — Article · Topics: Apple Platform Ecosystem
  **Published:** `19th June 2020`
  **NeKI brief:** Examines AltConf is hosting an online, audio only happy hour to bring together the community across the world, to discuss the keynote and recent announcements from Apple. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Tibor Bödecs’ guide to what’s new in Swift 5.3](https://theswiftdev.com/whats-new-in-swift-5-3) — iOS Dev Weekly · Issue 456 — Article · Topics: Apple Platform Ecosystem · Swift · Xcode
  **Published:** `15th May 2020`
  **NeKI brief:** Examines Tibor Bödecs' guide to what's new in Swift 5.3, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [watch this interview](https://www.cnet.com/news/apple-unveils-wwdc-2020-coding-contest-for-students) — iOS Dev Weekly · Issue 455 — Article · Topics: Apple Platform Ecosystem · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Examines For this year's virtual WWDC, Apple's Swift Student Challenge puts the spotlight on coding and STEM. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Hacking with Swift Live](https://www.hackingwithswift.com/live) — iOS Dev Weekly · Issue 452 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `17th April 2020`
  **NeKI brief:** Covers Hacking with Swift Live, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [what an online-only WWDC could look like last week](https://iosdevsurvey.com/2019/is-wwdc-already-a-virtual-conference) — iOS Dev Weekly · Issue 447 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `13th March 2020`
  **NeKI brief:** Is WWDC already a virtual conference?. This link is retained as a technical reading lead for Apple-platform development.
- [postponed, cancelled, or going virtual](https://www.zdnet.com/article/coronavirus-2020-tech-conference-cancellations-list) — iOS Dev Weekly · Issue 446 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `6th March 2020`
  **NeKI brief:** In the light of so many tech conferences being postponed, cancelled, or going virtual there’s plenty of speculation about this year’s WWDC, especially as we get close to the date Apple might typically announce it.
- [Apple might typically announce it](https://david-smith.org/wwdc) — iOS Dev Weekly · Issue 446 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `6th March 2020`
  **NeKI brief:** In the light of so many tech conferences being postponed, cancelled, or going virtual there’s plenty of speculation about this year’s WWDC, especially as we get close to the date Apple might typically announce it.
- [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) — iOS Dev Weekly · Issue 439 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `17th January 2020`
  **NeKI brief:** Provides a sequence of SwiftUI exercises that build from view composition into state, navigation, and platform integration. Use it as structured onboarding or a gap-finding checklist, not as a current API reference.
- [How to build a UICollectionView like the App Store](https://www.youtube.com/watch?v=SR7DtcT61tA) — iOS Dev Weekly · Issue 426 — Video · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `18th October 2019`
  **NeKI brief:** Paul Hudson doing a video that isn’t about SwiftUI? Oh yes! This is a fantastic guide to the new collection view APIs introduced at this year’s WWDC. If you haven’t looked at the changes yet, this is a great way to catch up.
- [LLVS project](https://github.com/mentalfaculty/LLVS) — iOS Dev Weekly · Issue 424 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Persistence & Synchronisation
  **Published:** `4th October 2019`
  **NeKI brief:** Examines LLVS project, focusing on one topic that has been talked about consistently since wwdc is how core data (or any data persistence framework) will be…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Deriving Reactive from Imperative: An Introduction to Duals](https://jasdev.me/duals) — iOS Dev Weekly · Issue 415 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2nd August 2019`
  **NeKI brief:** Examines While Apple’s Combine framework didn’t take center stage, its implications on our community certainly will for the next decade. We now have a first-party toolkit for functional rea. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [MacVoices podcast](http://www.macvoices.com/macvoices-19175-altconf-rob-elkin-and-mike-lee-on-the-objectives-of-altconf) — iOS Dev Weekly · Issue 410 — Podcast · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `28th June 2019`
  **NeKI brief:** I’ve been catching up with a few podcast episodes from WWDC this week and found myself listening to Rob Elkin and Mike Lee on the MacVoices podcast being interviewed by Chuck Joiner.
- [“hiccups” along the way](https://9to5mac.com/2015/06/05/apple-reverses-course-will-allow-altconf-to-stream-wwdc-keynote) — iOS Dev Weekly · Issue 410 — Tutorial · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `28th June 2019`
  **NeKI brief:** Reports Apple's decision to allow AltConf to stream the WWDC keynote after earlier event friction. It is a historical note on the growth of ticket-independent developer-conference participation.
- [GRDBCombine](https://github.com/groue/GRDBCombine) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Developer Tools
  **Published:** `28th June 2019`
  **NeKI brief:** The GitHub repository provides GRDBCombine, integrating GRDB database observation with Combine publishers.
- [GRDB](https://github.com/groue/GRDB.swift) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Developer Tools
  **Published:** `28th June 2019`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [example app](https://github.com/groue/GRDBCombine/blob/master/Documentation/Demo/README.md) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Developer Tools
  **Published:** `28th June 2019`
  **NeKI brief:** The repository README documents the GRDBCombine example app and shows how the library integrates GRDB database access with Combine.
- [The Things You May Have Missed at WWDC 2019](https://patrickbalestra.com/blog/2019/06/07/wwdc-2019-the-things-you-may-have-missed.html) — iOS Dev Weekly · Issue 408 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `14th June 2019`
  **NeKI brief:** Presents The Things You May Have Missed at WWDC 2019, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Apple Platform SDK API Differences](http://codeworkshop.net/objc-diff/sdkdiffs) — iOS Dev Weekly · Issue 407 — Tutorial · Topics: Apple Platform Ecosystem
  **Published:** `7th June 2019`
  **NeKI brief:** Looking for the lowdown on everything that has changed? Look no further than the official docs for a comprehensive list of changes, by framework and class. Or, if you’d prefer a full list of only what has changed then there’s also this list generated by…
- [A first look at Xcode 11’s Swift Package Manager integration](https://wwdcbysundell.com/2019/xcode-swiftpm-first-look) — iOS Dev Weekly · Issue 407 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `7th June 2019`
  **NeKI brief:** Examines A first look at Xcode 11's Swift Package Manager integration, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Getting Started with Xcode Test Plans](https://shashikantjagtap.net/wwdc19-getting-started-with-test-plan-for-xctest) — iOS Dev Weekly · Issue 407 — Article · Topics: Apple Platform Ecosystem · Testing · Xcode
  **Published:** `7th June 2019`
  **NeKI brief:** Examines Getting Started with Xcode Test Plans, offering practical guidance on test design and automation strategy. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [organise an impromptu get together yourself](https://www.andydev.co.uk/blog/conffriends-2019) — iOS Dev Weekly · Issue 406 — Article · Topics: Apple Platform Ecosystem
  **Published:** `31st May 2019`
  **NeKI brief:** Examines With under a week until developers from around the world start to descend on San Jose for Apple’s World Wide Developer Conference. ConfFriends (formerly WWDC Family) has been updat. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [decent guide here](https://jaimzuber.com/san-jose-convention-guide.html) — iOS Dev Weekly · Issue 406 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `31st May 2019`
  **NeKI brief:** The page covers “decent guide here” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [interview with me](https://wwdcbysundell.com/2019/interviews/dave-verwer) — iOS Dev Weekly · Issue 406 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `31st May 2019`
  **NeKI brief:** Or, maybe none of that is possible this year and you’re going to be following along completely remotely. There will be plenty coverage from the session videos, and on Twitter, but one site that I’ll call out specifically is WWDC by Sundell. Yes, that’s a new…
- [Designing APIs](https://www.swiftbysundell.com/posts/designing-swift-apis) — iOS Dev Weekly · Issue 400 — Article · Topics: Code Quality · Objective-C & Cocoa · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** Explains Designing APIs, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Student submissions for the WWDC 2019 Scholarship](https://github.com/wwdc/2019) — iOS Dev Weekly · Issue 397 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `29th March 2019`
  **NeKI brief:** Presents Student submissions for the WWDC 2019 Scholarship, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Brent Simmons](https://micro.blog/brentsimmons) — iOS Dev Weekly · Issue 394 — Article · Topics: Apple Platform Ecosystem
  **Published:** `8th March 2019`
  **NeKI brief:** Brent Simmons also gets it. I have a very similar list of questions that I’ll be watching for answers to during this years WWDC.
- [list of questions](http://inessential.com/2019/03/07/questions_about_marzipan_apps_on_the_mac) — iOS Dev Weekly · Issue 394 — Article · Topics: Apple Platform Ecosystem
  **Published:** `8th March 2019`
  **NeKI brief:** Brent Simmons also gets it. I have a very similar list of questions that I’ll be watching for answers to during this years WWDC.
- [Making AR Apps and Websites](https://parall.ax/blog/view/3283/making-ar-apps-and-websites) — iOS Dev Weekly · Issue 391 — Article · Topics: Apple Platform Ecosystem
  **Published:** `15th February 2019`
  **NeKI brief:** Examines Parallax: Building better digital experiences together. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Evolving Swift On Apple Platforms After ABI Stability](https://swift.org/blog/abi-stability-and-apple) — iOS Dev Weekly · Issue 391 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `15th February 2019`
  **NeKI brief:** Examines With the release of Swift 5.0, Swift is now ABI stable and is delivered as a core component of macOS, iOS, tvOS, and watchOS. ABI stability has been a goal for Swift since its ince. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Transmit 5 on the Mac App Store](https://panic.com/blog/transmit-5-on-the-mac-app-store) — iOS Dev Weekly · Issue 379 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `23rd November 2018`
  **NeKI brief:** Examines Panic Blog » Transmit 5 on the Mac App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [article by Daniel Jalkut](https://bitsplitting.org/2018/11/15/mac-sandboxing-privileged-file-operations) — iOS Dev Weekly · Issue 379 — Article · Topics: Apple Platform Ecosystem · Security & Privacy
  **Published:** `23rd November 2018`
  **NeKI brief:** No sign of BBEdit yet, but the promised return of Transmit from this year’s WWDC finally happened. Here’s the news from Panic’s blog, and there’s also this article by Daniel Jalkut on the entitlements that it uses.
- [Lessons Learned From the RWDevCon 2018 Design Lab](https://www.raywenderlich.com/5548-lessons-learned-from-the-rwdevcon-2018-design-lab) — iOS Dev Weekly · Issue 368 — Tutorial · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `7th September 2018`
  **NeKI brief:** Discusses Lessons Learned From the RWDevCon 2018 Design Lab, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Improving Your Build Time in Xcode 10](https://patrickbalestra.com/blog/2018/08/27/improving-your-build-time-in-xcode-10.html) — iOS Dev Weekly · Issue 367 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Xcode
  **Published:** `31st August 2018`
  **NeKI brief:** Explores Improving Your Build Time in Xcode 10 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Value-Oriented Programming](https://matt.diephouse.com/2018/08/value-oriented-programming) — iOS Dev Weekly · Issue 367 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `31st August 2018`
  **NeKI brief:** Explores Value-Oriented Programming in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [available on GitHub](https://github.com/nathangitter/fluid-interfaces) — iOS Dev Weekly · Issue 364 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `10th August 2018`
  **NeKI brief:** Discusses available on GitHub, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [App Store Review Guidelines – Changes from WWDC 2018](http://www.appstorereviewguidelineshistory.com/articles/2018-06-04-wwdc2018) — iOS Dev Weekly · Issue 357 — Tutorial · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `22nd June 2018`
  **NeKI brief:** Examines Changes after WWDC 2018 - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A first look at the Natural Language framework](https://www.swiftbysundell.com/daily-wwdc/a-first-look-at-the-natural-language-framework) — iOS Dev Weekly · Issue 355 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `8th June 2018`
  **NeKI brief:** Gives an early practical look at Apple’s Natural Language framework and the kinds of text analysis it exposes. Useful historical orientation for language-processing APIs, with availability and behavior checked against current SDK documentation.
- [official app](https://itunes.apple.com/app/wwdc/id640199958) — iOS Dev Weekly · Issue 354 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `1st June 2018`
  **NeKI brief:** The page covers “official app” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Save 50% during WWDC!](https://www.hackingwithswift.com/offers/iosdev1-50) — iOS Dev Weekly · Issue 354 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Special offers for Swift tutorials. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple Silently Launched Creative Testing in App Store Search Ads](https://asostack.com/apple-secretly-launched-creative-testing-in-app-store-search-ads-761a9f7b8abb) — iOS Dev Weekly · Issue 354 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Mobile marketers and developers can as of now test different Apple Search Ads assets in the App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC 97 Videos](http://bslabs.net/2018/05/28/wwdc-1997-videos) — iOS Dev Weekly · Issue 354 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Want something to watch on the flight to San Jose this weekend? These are fantastic. 🥇 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [developer keynote](https://www.youtube.com/watch?v=flU42CTF3MQ) — iOS Dev Weekly · Issue 351 — Video · Topics: Apple Platform Ecosystem
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Learn about the latest updates to our developer products and platforms at Google in a Keynote led by Jason Titus.This video is also subtitled in Chinese, Ind. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Andreas Neusüß](https://anerma.de/blog) — iOS Dev Weekly · Issue 347 — Article · Topics: Apple Platform Ecosystem
  **Published:** `13th April 2018`
  **NeKI brief:** Examines A blog of Andreas Neusüß. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC 2018 Scholarship Submissions](https://wwdc.github.io/2018) — iOS Dev Weekly · Issue 347 — Article · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** The page is a public index of WWDC 2018 scholarship submissions and provides browsable information about the submitted projects.
- [repo](https://github.com/wwdc/2018) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** Last week I linked to one of the WWDC 2018 scholarship submissions that had caught my eye and said I felt guilty about linking to just that one when I was sure there were so many other great submissions waiting to be discovered. So, I asked if there were any…
- [2014](https://github.com/wwdc/2014) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** Examines A curated list of all the WWDC Submissions in one place - wwdc/2014. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [2015](https://github.com/wwdc/2015) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** Examines Last week I linked to one of the WWDC 2018 scholarship submissions that had caught my eye and said I felt guilty about linking to just that one when I was sure there were so many other great submissions waiting to be dis Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [2016](https://github.com/wwdc/2016) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** The page covers “2016” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [2017](https://github.com/wwdc/2017) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** Examines Student Submissions for the WWDC 2017 Scholarship - GitHub - wwdc/2017: Student Submissions for the WWDC 2017 Scholarship. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Visual Programming Language](https://github.com/NathanFlurry/VisualProgrammingLanguage) — iOS Dev Weekly · Issue 346 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `6th April 2018`
  **NeKI brief:** Presents Visual Programming Language, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [this one](https://dribbble.com/shots/4318035-Toggle) — iOS Dev Weekly · Issue 344 — Article · Topics: Apple Platform Ecosystem
  **Published:** `23rd March 2018`
  **NeKI brief:** Oh my god, this one! Also, this is DEFINITELY the look and feel of iOS 12 based on the WWDC ‘18 artwork. 😂 Obviously none of these are going to make it into an actual app, but it’s nice to step outside of the reality of implementation to get inspired…
- [Apple Networking Feedback Survey](https://forums.developer.apple.com/thread/97662) — iOS Dev Weekly · Issue 342 — Article · Topics: Apple Platform Ecosystem · Networking
  **Published:** `9th March 2018`
  **NeKI brief:** Examines Apple Networking Feedback Survey, focusing on interesting, quinn “the eskimo!” (who you may have met if you’ve ever found yourself in the labs at wwdc) is asking for…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [QUIC protocol](https://en.wikipedia.org/wiki/QUIC) — iOS Dev Weekly · Issue 342 — Article · Topics: Apple Platform Ecosystem
  **Published:** `9th March 2018`
  **NeKI brief:** Examines QUIC - Wikipedia. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [refocusing on quality and reliability](https://sixcolors.com/link/2018/01/report-apple-pushing-back-features-focusing-on-software-quality-in-next-major-ios-release) — iOS Dev Weekly · Issue 337 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `2nd February 2018`
  **NeKI brief:** As February kicks off, your thoughts might be turning to possible WWDC announcements. It’s certainly getting close to the time when we may see dates and ticket plans for this year’s conference. I’d say it’s very likely going to be in San Jose again, but we…
- [hallway track](http://sachachua.com/blog/2010/12/making-the-most-of-the-conference-hallway-track) — iOS Dev Weekly · Issue 335 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `19th January 2018`
  **NeKI brief:** The article explains how to make the most of informal hallway conversations at conferences and turn them into useful knowledge exchange.
- [templated apps](https://techcrunch.com/2017/12/08/apples-widened-ban-on-templated-apps-is-wiping-small-businesses-from-the-app-store) — iOS Dev Weekly · Issue 331 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `15th December 2017`
  **NeKI brief:** Discusses templated apps, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [panel discussion](https://news.realm.io/news/wwdc-2017-swift-panel) — iOS Dev Weekly · Issue 309 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores panel discussion in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [New stuff from WWDC 2017](https://mackuba.eu/2017/07/05/new-stuff-from-wwdc-2017) — iOS Dev Weekly · Issue 308 — Article · Topics: Apple Platform Ecosystem
  **Published:** `7th July 2017`
  **NeKI brief:** How could anyone remember everything Apple announced at WWDC? Luckily, we don’t have to, because Kuba Suder composed this detailed list of all the important announcements. He starts with the user-facing features but quickly moves on to developer and…
- [HomeKit in iOS 11](https://www.theverge.com/2017/6/8/15761800/apple-homekit-updates-ios-11-easier-build-requirements-wwdc-2017) — iOS Dev Weekly · Issue 307 — Article · Topics: Apple Platform Ecosystem
  **Published:** `30th June 2017`
  **NeKI brief:** When Apple first announced HomeKit back in 2014, I was disappointed by all the hurdles I’d have to jump through just to tinker with it. Well, with the upcoming release of iOS 11 things are finally changing for the better. If you have a few Arduinos or…
- [Save 50% on all Hacking with Swift books](https://www.hackingwithswift.com/offers/wwdc17-50) — iOS Dev Weekly · Issue 304 — Article · Topics: Apple Platform Ecosystem · Spatial Computing · Swift
  **Published:** `9th June 2017`
  **NeKI brief:** Examines Save 50% on all Hacking with Swift books, focusing on celebrate wwdc by learning something new - all hacking with swift books are 50% off for the next four days, including my…. Use it as a focused research reference for related Apple-platform work, and.
- [App Store Review Guidelines changes from WWDC 2017](http://www.appstorereviewguidelineshistory.com/articles/2017-06-08-new-rules-following-wwdc-2017) — iOS Dev Weekly · Issue 304 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `9th June 2017`
  **NeKI brief:** Examines App Store Review Guidelines changes from WWDC 2017, focusing on what else did wwdc bring us? a huge set of changes to the app store review guidelines! 📖 along with some quite shocking…. Use it as a focused research reference for related Apple-platform work.
- [Looking Back to WWDC ’97](http://bslabs.net/2017/06/01/wwdc-1997) — iOS Dev Weekly · Issue 304 — Article · Topics: Apple Platform Ecosystem
  **Published:** `9th June 2017`
  **NeKI brief:** Looking Back to WWDC ’97. This link is retained as a technical reading lead for Apple-platform development.
- [official WWDC app](https://itunes.apple.com/gb/app/wwdc/id640199958?mt=8) — iOS Dev Weekly · Issue 303 — Article · Topics: Apple Platform Ecosystem
  **Published:** `2nd June 2017`
  **NeKI brief:** Examines If you’re following along from elsewhere like me, then don’t forget that the official WWDC app has already been updated for this year, or you could use the unofficial app if you prefer viewing on a Mac. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [one of our events](https://www.buddybuild.com/blog/buddybuild-events-at-wwdc17) — iOS Dev Weekly · Issue 303 — Article · Topics: Apple Platform Ecosystem · CI/CD & Automation · Testing
  **Published:** `2nd June 2017`
  **NeKI brief:** Explores one of our events in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Protocol Oriented Programming is Not a Silver Bullet](http://chris.eidhof.nl/post/protocol-oriented-programming) — iOS Dev Weekly · Issue 278 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `25th November 2016`
  **NeKI brief:** Argues that protocol-oriented programming is often overapplied and that simpler concrete designs may solve the problem better. Use it as a counterweight when evaluating whether a protocol adds a real abstraction boundary.
- [iOS 10 Day by Day](http://www.shinobicontrols.com/blog/ios-10-day-by-day-index) — iOS Dev Weekly · Issue 273 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem
  **Published:** `21st October 2016`
  **NeKI brief:** Explores iOS 10 Day by Day in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Building Swift Playground Books](https://ashfurrow.com/blog/building-swift-playground-books) — iOS Dev Weekly · Issue 266 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2nd September 2016`
  **NeKI brief:** Explores Building Swift Playground Books in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines) — iOS Dev Weekly · Issue 266 — Article · Topics: Apple Platform Ecosystem · Code Quality · Swift
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [New stuff from WWDC 2016](https://gist.github.com/mackuba/e8fb4219c7ef611f47cdb66b93986d85) — iOS Dev Weekly · Issue 259 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `15th July 2016`
  **NeKI brief:** Examines Kuba Suder with his annual list of everything that was announced at WWDC. When you look at it like this, I dare anyone to ask “What have Apple been doing since last year?” 😄 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The Great Swift 3 Rename](https://littlebitesofcocoa.com/243-the-great-swift-3-rename) — iOS Dev Weekly · Issue 257 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `1st July 2016`
  **NeKI brief:** Explores The Great Swift 3 Rename in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Ole Begemann’s comments](http://oleb.net/blog/2016/06/swift-3) — iOS Dev Weekly · Issue 257 — Article · Topics: Apple Platform Ecosystem · Swift · UIKit
  **Published:** `1st July 2016`
  **NeKI brief:** Over the last couple of years I’ve speculated several times on whether Apple would make a more Swift friendly replacement for UIKit. I think WWDC this year showed us the last piece of the puzzle that’s been creeping up on us for a while now. Why re-engineer…
- [The Deprecation of iCloud Core Data](http://mjtsai.com/blog/2016/06/17/the-deprecation-of-icloud-core-data) — iOS Dev Weekly · Issue 257 — Article · Topics: Apple Platform Ecosystem · Core Data · Persistence & Synchronisation
  **Published:** `1st July 2016`
  **NeKI brief:** Explains the deprecation of iCloud Core Data and its implications for persistence architecture. Follow it for concrete migration and synchronization context, while verifying current Apple-supported alternatives.
- [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) — iOS Dev Weekly · Issue 257 — Source repository · Topics: Developer Community & Business · Developer Tools · UIKit
  **Published:** `1st July 2016`
  **NeKI brief:** Examines PSTModernizer, focusing on what do you do when find a bug in uikit? you file a radar of course! but then what? maybe you find a workaround and fix…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [A quick list of overlooked announcements at WWDC 16](http://alisoftware.github.io/conferences/2016/06/20/ios-10-api-diff) — iOS Dev Weekly · Issue 256 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Developer Tools
  **Published:** `24th June 2016`
  **NeKI brief:** Examines Making your Swift code more fun 🎉, magical ✨ and crunchier 👌. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [New in Notifications](http://fichek.com/blog/wwdc16-notifications) — iOS Dev Weekly · Issue 256 — Article · Topics: Apple Platform Ecosystem · UIKit
  **Published:** `24th June 2016`
  **NeKI brief:** Explores New in Notifications in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [official iOS app](https://itunes.apple.com/us/app/wwdc/id640199958?mt=8) — iOS Dev Weekly · Issue 255 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `17th June 2016`
  **NeKI brief:** Stream or download the videos from the main site, with the official iOS app. If you’re reading this on Friday then you might even still catch some of the live stream. There’s also the (unofficial) WWDC Mac app if you want to organize your downloads better on…
- [Beard Bash](http://www.loopinsight.com/2016/05/19/rsvp-for-the-beard-bash-2016-at-wwdc-now-open) — iOS Dev Weekly · Issue 251 — Article · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `20th May 2016`
  **NeKI brief:** The post announces the Beard Bash event at WWDC and provides publicly readable event details.
- [The Talk Show Live](https://daringfireball.net/thetalkshow) — iOS Dev Weekly · Issue 251 — Article · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `20th May 2016`
  **NeKI brief:** Examines Daring Fireball: The Talk Show. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [help with that](https://github.com/azzoor/WWDCTV) — iOS Dev Weekly · Issue 239 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `26th February 2016`
  **NeKI brief:** The page covers “help with that” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Videos from CocoaLove 2015](https://vimeo.com/channels/cocoalove2015) — iOS Dev Weekly · Issue 237 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** CocoaLove describes itself as a conference which “focuses on talks that aren’t deprecated at the next WWDC”. This means you’re not going to find much, if any code here but what you will find is a great set of inspirational and interesting presentations.
- [Bjango Design Resources](https://bjango.com/designresources) — iOS Dev Weekly · Issue 235 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `29th January 2016`
  **NeKI brief:** Big update to the design resources provided by Bjango this week. There’s not only an update to their Actions but also a brand new app icon template covering all of the Apple platforms (iOS, watchOS, tvOS, Mac) as well as Android, Windows and even web…
- [Actions](https://github.com/bjango/Bjango-Actions) — iOS Dev Weekly · Issue 235 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `29th January 2016`
  **NeKI brief:** Examines A collection of Photoshop actions, Photoshop scripts, Hazel rules, macOS workflows and other random things for screen designers and developers. - bjango/Bjango-Actions. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [app icon template](https://github.com/bjango/Bjango-Templates) — iOS Dev Weekly · Issue 235 — Source repository · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `29th January 2016`
  **NeKI brief:** Examines Big update to the design resources provided by Bjango this week. There’s not only an update to their Actions but also a brand new app icon template covering all of the Apple platforms (iOS, watchOS, tvOS, Mac) as well as Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [How to Use updateConstraints](http://oleb.net/blog/2015/08/how-to-use-updateconstraints) — iOS Dev Weekly · Issue 214 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `4th September 2015`
  **NeKI brief:** Presents How to Use updateConstraints, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Thoughts on Swift 2 Errors](https://gist.github.com/nicklockwood/21495c2015fd2dda56cf) — iOS Dev Weekly · Issue 212 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `21st August 2015`
  **NeKI brief:** Examines Thoughts on Swift 2 Errors. GitHub Gist: instantly share code, notes, and snippets. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple TV Event in September?](http://www.buzzfeed.com/johnpaczkowski/apple-will-debut-new-apple-tv-in-september) — iOS Dev Weekly · Issue 209 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `31st July 2015`
  **NeKI brief:** Examines The new Apple TV is headed to market along with an App Store of its own. Next step: that long-in-the-offing subscription internet-TV service. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [UICollectionViews now have easy reordering](http://nshint.io/blog/2015/07/16/uicollectionviews-now-have-easy-reordering) — iOS Dev Weekly · Issue 207 — Article · Topics: Apple Platform Ecosystem
  **Published:** `17th July 2015`
  **NeKI brief:** Explains UICollectionViews now have easy reordering with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [New stuff from WWDC 2015](https://gist.github.com/mackuba/15994186a4f9d7da3137) — iOS Dev Weekly · Issue 206 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `10th July 2015`
  **NeKI brief:** The public gist collects notes about new technologies and APIs announced at WWDC 2015.
- [Address Sanitizer](https://mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) — iOS Dev Weekly · Issue 206 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `10th July 2015`
  **NeKI brief:** Explains Address Sanitizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Valet](https://github.com/square/Valet) — iOS Dev Weekly · Issue 204 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Persistence & Synchronisation
  **Published:** `26th June 2015`
  **NeKI brief:** I’m really surprised that by iOS 9 we still don’t have a higher level API to Keychain. I actually had this saved just before WWDC but I postponed it, just in case it finally happened… Anyway, it didn’t so here you go. Yes, there are loads of these already…
- [little warning](http://nomothetis.svbtle.com/the-ghost-of-swift-bugs-future) — iOS Dev Weekly · Issue 203 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `19th June 2015`
  **NeKI brief:** Explains little warning with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The state of iBeacons](https://stawecki.wordpress.com/2015/06/11/the-state-of-ibeacons-june-2015) — iOS Dev Weekly · Issue 203 — Article · Topics: Apple Platform Ecosystem
  **Published:** `19th June 2015`
  **NeKI brief:** One thing we heard very little about last week was iBeacons (in fact, the awesome ASCIIwwdc tells me that it wasn’t mentioned at all in any session this year). Mateusz Stawecki writes about the recent use of beacons at Úll and a view on the current state of…
- [UIKonf 2015 Videos](https://www.youtube.com/playlist?list=PLdr22uU_wISpW6XI1J0S7Lp-X8Km-HaQW) — iOS Dev Weekly · Issue 202 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `12th June 2015`
  **NeKI brief:** Just in case the WWDC videos weren’t enough for you this week. Here’s the full set of videos from this year’s UIKonf in Berlin. Enjoy!
- [no selfie sticks](http://9to5mac.com/2015/04/14/wwdc-selfie-sticks) — iOS Dev Weekly · Issue 194 — Article · Topics: Apple Platform Ecosystem
  **Published:** `17th April 2015`
  **NeKI brief:** Reports WWDC event-policy changes, including Friday sessions and labs, streamed sessions, scholarship details, and a ban on selfie sticks. It is historical conference logistics rather than developer education.
- [Learn How To Create An iOS App Using HomeKit](http://www.xmcgraw.com/learn-how-to-create-an-ios-app-using-homekit) — iOS Dev Weekly · Issue 186 — Article · Topics: Apple Platform Ecosystem
  **Published:** `20th February 2015`
  **NeKI brief:** Is it just me or have we heard very little about HomeKit since WWDC last year? David McGraw has an excellent overview of what to expect when developing an app that interfaces to a HomeKit enabled device. Looks like HomeKit removes the burden of device…
- [IBInspectable / IBDesignable](http://nshipster.com/ibinspectable-ibdesignable) — iOS Dev Weekly · Issue 184 — Article · Topics: Apple Platform Ecosystem
  **Published:** `6th February 2015`
  **NeKI brief:** IBInspectable and IBDesignable expose custom view configuration and previews in Interface Builder. Use them to shorten UIKit iteration, keeping inspectable properties simple because design-time rendering has a different runtime environment.
- [pulling of all HealthKit apps due to a bug](http://www.theguardian.com/technology/2014/sep/18/apple-healthkit-bug-ios-8) — iOS Dev Weekly · Issue 164 — Article · Topics: App Distribution & Store Operations · Health Apps
  **Published:** `19th September 2014`
  **NeKI brief:** Examines Health and fitness-tracking app updates pulled, with cure expected by the end of September. By <strong>Stuart Dredge</strong>. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Form](http://www.relativewave.com/form) — iOS Dev Weekly · Issue 162 — Article · Topics: Apple Platform Ecosystem · Performance
  **Published:** `5th September 2014`
  **NeKI brief:** The former Relative Wave Form URL now redirects to Material Design guidance. Useful as redirect history; the current destination should be assessed as design documentation, not the original tool page.
- [Cocoa without the limitations of C compatibility](https://devforums.apple.com/message/1025388) — iOS Dev Weekly · Issue 160 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `22nd August 2014`
  **NeKI brief:** Explains Cocoa without the limitations of C compatibility with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [demoed in the Keynote](https://www.youtube.com/watch?feature=player_detailpage&v=w87fOAG8fjk) — iOS Dev Weekly · Issue 159 — Video · Topics: Apple Platform Ecosystem · Swift
  **Published:** `15th August 2014`
  **NeKI brief:** Apple's WWDC 2014 keynote introduces iOS 8 and OS X Yosemite, providing historical context for their original platform features and design direction. Use it to understand the announcements, not current API availability.
- [Introducing the 1Password App Extension](http://blog.agilebits.com/2014/07/30/introducing-the-1password-app-extension-for-ios-8-apps) — iOS Dev Weekly · Issue 157 — Article · Topics: App Services & Extensions · Apple Platform Ecosystem · Security & Privacy
  **Published:** `1st August 2014`
  **NeKI brief:** Explains Introducing the 1Password App Extension, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [The importance of bug reporting](http://www.imore.com/importance-of-bug-reporting) — iOS Dev Weekly · Issue 152 — Article · Topics: Apple Platform Ecosystem · Swift · Testing
  **Published:** `27th June 2014`
  **NeKI brief:** I talked about this a few weeks ago but with WWDC behind us and with iOS 8, Yosemite and Swift in our hands it’s even more important to log bugs in this period of beta testing. Now is the time to get the feedback in to Apple on bugs and feature requests…
- [Screenshot](http://xkcd.com/1373) — iOS Dev Weekly · Issue 148 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `30th May 2014`
  **NeKI brief:** Examines xkcd: Screenshot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Rob Elkin on AltConf](https://www.youtube.com/watch?v=CKm-qJamPnY&app=desktop) — iOS Dev Weekly · Issue 147 — Video · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `23rd May 2014`
  **NeKI brief:** Examines Rob Elkin is again organizing a parallel event to Apple's Worldwide Developers Conference. This year, it will be called AltConf, and is a follow-up to last y. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Orta’s WWDC party list](https://github.com/orta/wwdc_parties_2014/blob/master/README.md) — iOS Dev Weekly · Issue 147 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `23rd May 2014`
  **NeKI brief:** The page covers “Orta’s WWDC party list” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [MTDActionSheet](https://github.com/myell0w/MTDActionSheet) — iOS Dev Weekly · Issue 146 — Source repository · Topics: Developer Tools
  **Published:** `16th May 2014`
  **NeKI brief:** Examines A customizable popover-based UIActionSheet replacement for the iPhone & iPad - myell0w/MTDActionSheet. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS 8 Wishes](http://www.macstories.net/stories/ios-8-wishes) — iOS Dev Weekly · Issue 143 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th April 2014`
  **NeKI brief:** As we are only five weeks away from WWDC, it’s probably time to start speculating on iOS 8. Federico Viticci provides an in-depth look at his wishes for the new version. There’s nothing too crazy listed here as he is predicting that iOS 8 will be more of a…
- [OS X and Helvetica Neue](http://furbo.org/2014/04/18/get-ready-for-june-2nd) — iOS Dev Weekly · Issue 143 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th April 2014`
  **NeKI brief:** Examines There’s no doubt in my mind that Apple is going to overhaul the look of Mac OS X in the next version. As more and more apps bridge the gap between the desktop and mobile, the. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Contribute to ASCIIwwdc](http://asciiwwdc.com/contribute) — iOS Dev Weekly · Issue 122 — Article · Topics: Apple Platform Ecosystem
  **Published:** `29th November 2013`
  **NeKI brief:** Examines Searchable full-text transcripts of WWDC sessions. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using your tech support incidents](http://www.tuaw.com/2013/08/21/dev-juice-using-your-tech-support-incidents) — iOS Dev Weekly · Issue 108 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `23rd August 2013`
  **NeKI brief:** Explains Using your tech support incidents with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [WWDC Sample Code Downloader](https://github.com/jfahrenkrug/WWDC-Downloader) — iOS Dev Weekly · Issue 100 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `28th June 2013`
  **NeKI brief:** Provides the WWDC Sample Code Downloader source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [WWDC First-Timer Tips](http://orangejuiceliberationfront.com/wwdc-first-timer-tips) — iOS Dev Weekly · Issue 97 — Article · Topics: Apple Platform Ecosystem
  **Published:** `7th June 2013`
  **NeKI brief:** Explains WWDC First-Timer Tips with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [WWDC Expectations](http://www.loopinsight.com/2013/05/29/wwdc-expectations) — iOS Dev Weekly · Issue 96 — Tutorial · Topics: Apple Platform Ecosystem · Developer Community & Business
  **Published:** `31st May 2013`
  **NeKI brief:** Examines WWDC Expectations. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The Gathering Storm: Our Travails with iCloud Sync](http://rms2.tumblr.com/post/46505165521/the-gathering-storm-our-travails-with-icloud-sync) — iOS Dev Weekly · Issue 87 — Article · Topics: Apple Platform Ecosystem · Core Data · Persistence & Synchronisation
  **Published:** `29th March 2013`
  **NeKI brief:** Explains The Gathering Storm Our Travails with iCloud Sync with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [New accessibility techniques in iOS6](http://www.iheni.com/new-accessibility-techniques-in-ios6) — iOS Dev Weekly · Issue 65 — Article · Topics: Accessibility · Apple Platform Ecosystem
  **Published:** `26th October 2012`
  **NeKI brief:** Explains New accessibility techniques in iOS6 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Implementing Smart App Banners](http://david-smith.org/blog/2012/09/20/implementing-smart-app-banners) — iOS Dev Weekly · Issue 61 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `28th September 2012`
  **NeKI brief:** Explains Implementing Smart App Banners with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [WWDC Videos 2004-2008](http://oleb.net/blog/2012/07/wwdc-videos-2004-2008) — iOS Dev Weekly · Issue 50 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `13th July 2012`
  **NeKI brief:** Collects older WWDC videos from 2004 through 2008. Follow individual sessions for historical Apple-platform context, while using current documentation for supported APIs and behavior.
- [iOS 6 WWDC Keynote Updates](http://useyourloaf.com/blog/2012/06/11/ios-6-wwdc-keynote-updates.html) — iOS Dev Weekly · Issue 46 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `15th June 2012`
  **NeKI brief:** Examines A great, non NDA breaking round up of some of what we can talk about in iOS 6 by Keith Harrison. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Let’s Have Some Fun with the Preliminary Schedule for WWDC 2012](http://daringfireball.net/2012/05/reading_way_too_much_into_wwdc_schedule) — iOS Dev Weekly · Issue 44 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `1st June 2012`
  **NeKI brief:** Examines As much as I want to see an App Store for the Apple TV (and I really do), I am not sure I really believe it will happen now and those TBA sessions on the schedule are always less exciting than the rumours when the confer Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Appsterdam WWDC HQ](http://www.robelkin.com/wwdc) — iOS Dev Weekly · Issue 43 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th May 2012`
  **NeKI brief:** Appsterdam on tour in San Francisco with another co-working venue for WWDC week which may be useful if you are planning to do an unofficial WWDC this year. Or just pop along for one of the famous Appsterdam lunchtime lectures as they are hosting a different…
- [Alternative To WWDC 2012: Check Out Indie Developer Lab](http://www.cultofmac.com/163225/alternative-to-sold-out-wwdc-2012-launches-check-out-indie-developer-lab) — iOS Dev Weekly · Issue 39 — Article · Topics: Apple Platform Ecosystem
  **Published:** `27th April 2012`
  **NeKI brief:** Examines Apple's 2012 Worldwide Developer Conference sold out in just two hours yesterday morning, and most of the west coast got screwed because it all happened. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC-less WWDC](http://rentzsch.tumblr.com/post/20879080490/wwdc-less-wwdc) — iOS Dev Weekly · Issue 37 — Article · Topics: Apple Platform Ecosystem
  **Published:** `13th April 2012`
  **NeKI brief:** Examines Last year Victoria and I tried something different: visiting San Francisco during WWDC, but not actually attending WWDC. Here's a quick rundown of our experience. Pros: Ticket. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [What's New at WWDC 2026](https://go.peterfriese.dev/swift-whats-new-at-wwdc-2026?s=web&t=ext) — Not only Swift · Issue 99 — Article · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** Aggregates WWDC 2026 changes from session transcripts and groups them by framework and capability. It is a broad discovery map for finding relevant announcements, with final API decisions still requiring the linked Apple sessions and documentation.
- [Siri & App Intents](https://go.peterfriese.dev/wwdc-2026-siri-app?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem
  **NeKI brief:** Deep-links to the Siri and App Intents portion of a transcript-derived WWDC 2026 change index. Use it to inventory system-surface announcements before verifying schemas, availability, and behavior in primary Apple material.
- [System APIs](https://go.peterfriese.dev/wwdc-2026-system-apis?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem
  **NeKI brief:** Deep-links to the system-API portion of a transcript-derived WWDC 2026 change index. It helps narrow a large announcement set, but each capability still needs confirmation against its framework documentation and target SDK.
- [typeset](https://github.com/peterfriese/swift-book) — Not only Swift · Issue 98 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **NeKI brief:** Provides Peter Friese’s Swift book materials and examples as a public reference for learning and teaching core Swift concepts. Use it for structured study, not as version-specific API authority.
- [includes skills for Swift and SwiftUI in Xcode](https://dev.to/arshtechpro/wwdc-2026-xcode-27-ships-with-apples-own-agent-skills-what-they-are-and-how-to-use-them-3g2) — Not only Swift · Issue 98 — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Surveys the agent skills bundled with Xcode 27 and how they guide Swift, SwiftUI, testing, and Apple-framework work. Treat it as community orientation, then verify the installed skill contents and supported workflow in the actual Xcode release.
- [Play](https://youtube.com/watch?v=qx5QWrKhxM8) — Not only Swift · Issue 98 — Video · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Demonstrates a Firebase bridge that makes Gemini models available through Apple’s Foundation Models-style API. Use it to compare a cloud-model fallback with on-device sessions while keeping authentication, privacy, latency, and API compatibility explicit.
- [Get started with Firebase App Check for Apple Platforms](https://firebase.google.com/docs/app-check/ios) — Not only Swift · Issue 95 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Explains how to configure Firebase App Check for Apple platforms so backend resources can distinguish traffic from authentic app instances. Use it when adding app-attestation protections around Firebase services.
- [Bezel app](https://nonstrict.eu/bezel) — Not only Swift · Issue 90 — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Profiles Bezel, a macOS utility for displaying iOS device frames around screenshots and recordings. It is useful when preparing device-specific visuals for App Store listings, documentation, or review material.
- [an entire chapter just about toolbars](https://youtu.be/3MugGCtm26A?t=469s) — Not only Swift · Issue 84 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Links to a presentation segment focused on SwiftUI toolbars. Use the demonstration to understand composition and interaction choices, while checking current toolbar APIs and platform behavior in Apple documentation.
- [livestream to dig into some of the new stuff released at WWDC 25](https://www.youtube.com/watch?v=tmPwLamVGYM) — Not only Swift · Issue 83 — Video · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** This livestream reviews new material announced at WWDC 25 and discusses its practical implications for Apple-platform developers. The recording provides a concrete, time-bounded walkthrough of the APIs and platform changes covered after the conference.
- [another livestream](https://www.youtube.com/watch?v=8vojkFvKT1U&list=PLl-K7zZEsYLk807wutFVVKom8HsB1H9m_&index=1) — Not only Swift · Issue 83 — Video · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** This developer livestream follows the WWDC 25 and Google I/O Connect discussions with a practical look at the newly announced tools and platform capabilities. It is useful for seeing the presenter work through the changes in context rather than reading only release summaries.
- [argued that](https://www.youtube.com/watch?v=Gw5lB1Jo-bM&t=2130s) — Not only Swift · Issue 83 — Video · Topics: Apple Platform Ecosystem · Developer Community & Business · Liquid Glass
  **NeKI brief:** This Hardfork podcast segment critiques Apple's Liquid Glass design through the distinction between appearance and behavior. It offers a concrete community perspective on the interaction and usability trade-offs developers should consider when evaluating the new UI direction.
- [What's new in SwiftUI - WWDCNotes](https://wwdcnotes.com/documentation/wwdcnotes/wwdc25-256-whats-new-in-swiftui) — Not only Swift · Issue 83 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of What's new in SwiftUI - WWDCNotes. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [write-up](https://wwdcnotes.com/documentation/wwdcnotes/wwdc21-10022-demystify-swiftui) — Not only Swift · Issue 76 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** This article covers the WWDC session Demystify SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [RenderMeThis: SwiftUI Debugging Tool](https://github.com/Aeastr/RenderMeThis) — Not only Swift · Issue 76 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers visualizing SwiftUI rendering, layouts, and measurements with Loupe. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
