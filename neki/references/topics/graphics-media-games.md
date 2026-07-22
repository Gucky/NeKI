# Graphics, Media & Games

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Rendering, GPU work, image/audio/video processing, computer vision, and game-development techniques.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **361**

## Direct-source reading

- [Moving from OpenGL to Metal | Kodeco](https://www.kodeco.com/9211-moving-from-opengl-to-metal) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The migration walkthrough maps an OpenGL renderer onto Metal's command queues, buffers, and shaders, highlighting the explicit resource and pipeline setup required by Apple's lower-level API.
- [Image Depth Maps Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/8246240-image-depth-maps-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains AVDepthData as depth or disparity, then turns it into masks and depth-driven image filters. It helps decide how portrait-camera depth can control focus, highlights, or selective processing instead of treating depth as opaque photo metadata.
- [iOS Photos Framework | Kodeco](https://www.kodeco.com/7910383-ios-photos-framework) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces the Photos framework's asset access and library-oriented model for iOS. Useful for understanding the privacy and data-source boundary between an app's own image files and a user's system photo library.
- [Visually Rich Links Tutorial for iOS: Image Thumbnails | Kodeco](https://www.kodeco.com/7565482-visually-rich-links-tutorial-for-ios-image-thumbnails) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The tutorial builds rich link previews with image thumbnails, showing how metadata and generated visual assets can improve an iOS sharing experience.
- [Game Center for iOS: Building a Turn-Based Game | Kodeco](https://www.kodeco.com/7544-game-center-for-ios-building-a-turn-based-game) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A turn-based Game Center example combines player authentication with match state and turn submission. It is useful for understanding the service boundary and lifecycle, where network delays and participant availability must not be treated as local game state.
- [Metal Tutorial: Getting Started | Kodeco](https://www.kodeco.com/7475-metal-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Traces Metal's minimum rendering path from MTLDevice and CAMetalLayer through buffers, shader functions, pipeline state, command encoding, and presentation. A practical map of which objects bridge CPU setup to GPU work when debugging a first renderer.
- [ML Kit Tutorial for iOS: Recognizing Text in Images | Kodeco](https://www.kodeco.com/6565-ml-kit-tutorial-for-ios-recognizing-text-in-images) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Integrates ML Kit text recognition with camera input, accounts for image orientation and scaling, then maps detected frames back onto the displayed image. Useful when OCR results must be both extracted and accurately highlighted in an iOS interface.
- [Video Depth Maps Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/5999357-video-depth-maps-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses video depth data to drive image or video effects. Useful for separating depth capture, coordinate alignment, and rendering decisions in camera features that react to foreground geometry.
- [Saliency Analysis in iOS using Vision | Kodeco](https://www.kodeco.com/5807038-saliency-analysis-in-ios-using-vision) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Vision saliency analysis on a live video feed to identify visually prominent regions. It is a practical reference for choosing image-processing requests and for deciding how computed regions should drive effects or cropping.
- [Metal Rendering Pipeline Tutorial | Kodeco](https://www.kodeco.com/5493-metal-rendering-pipeline-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects a renderer's CPU-side buffer and command setup to each GPU pipeline stage: vertex fetch, processing, primitive assembly, rasterization, fragments, and framebuffer output. Useful for locating whether a rendering defect originates in data, shaders, or pipeline configuration.
- [Core Image: From CIImage to Metal and Beyond | Kodeco](https://www.kodeco.com/5428948-core-image-from-ciimage-to-metal-and-beyond) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Image’s CIImage pipeline is connected to built-in filters and custom Metal kernels for efficient image and video processing. The trade-off discussion is useful when choosing GPU-backed composition without prematurely writing a full rendering engine.
- [On-Demand Resources in iOS Tutorial | Kodeco](https://www.kodeco.com/520-on-demand-resources-in-ios-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Organizes asset packs with tags and NSBundleResourceRequest, covering priority, error handling, disk pressure, and purging. Useful for deciding which large, infrequently used resources can be fetched on demand without making first launch carry their storage cost.
- [GLKit Tutorial for iOS: Getting started with OpenGL ES | Kodeco](https://www.kodeco.com/5146-glkit-tutorial-for-ios-getting-started-with-opengl-es) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The GLKit example builds a spinning OpenGL ES cube while explaining projection and render setup. It is a historical graphics reference, useful for maintaining legacy renderers and recognizing why Metal migration changes the command model.
- [iOS 10: Editing Live Photos | Kodeco](https://www.kodeco.com/5001-ios-10-editing-live-photos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores editing Live Photos while preserving their paired still-image and motion components. Useful for recognizing why a Live Photo edit has different data and export constraints than a single bitmap transformation.
- [iOS 10: Capturing Photo Thumbnails | Kodeco](https://www.kodeco.com/4999-ios-10-capturing-photo-thumbnails) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Captures and prepares photo thumbnails for a camera-driven interface. Useful for separating a fast preview-sized representation from full-resolution capture work that would otherwise block interaction or consume unnecessary memory.
- [iOS 10: Sending Custom Messages in iMessage | Kodeco](https://www.kodeco.com/4954-ios-10-sending-custom-messages-in-imessage) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Sends custom iMessage content with a structured message representation. Useful for considering what recipient-recoverable state must travel with a collaborative message rather than sending only a visual preview.
- [Photo Stacking in iOS with Vision and Metal | Kodeco](https://www.kodeco.com/3733151-photo-stacking-in-ios-with-vision-and-metal) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Aligns a burst with Vision, combines images through a custom Core Image kernel, and uses Metal for the pixel work. Useful for understanding a computational-photography pipeline where registration must happen before denoising or detail-enhancing stack composition.
- [What’s New With PhotosPicker in iOS 16 | Kodeco](https://www.kodeco.com/36653975-what-s-new-with-photospicker-in-ios-16) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates PhotosPicker's user-mediated asset selection and transferable loading for images and videos, avoiding broad photo-library access. It helps assess privacy-friendly import flows and the asynchronous conversion work required after selection.
- [Beginning Metal | Kodeco](https://www.kodeco.com/3537-beginning-metal) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Beginning Metal explains the command-buffer and render-pipeline model by building a small renderer. Follow it when moving beyond high-level drawing APIs, but treat its setup as foundational rather than a current best-practice abstraction for every app.
- [Cocos2D Tutorial for iOS: How To Make A Space Shooter iPhone Game | Kodeco](https://www.kodeco.com/3165-cocos2d-tutorial-for-ios-how-to-make-a-space-shooter-iphone-game) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a Cocos2D space shooter with sprites, movement, collisions, and game state. Useful for understanding a scene-graph game framework's separation of rendering nodes and gameplay rules.
- [Cocos2D Tutorial for iOS: How To Create A Mole Whacking Game: Part 2/2 | Kodeco](https://www.kodeco.com/3093-cocos2d-tutorial-for-ios-how-to-create-a-mole-whacking-game-part-2-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Cocos2D sequel completes touch scoring, timing and scene transitions for a small game. It is useful for tracing how gameplay state drives animation, while modern implementations should preserve that state-machine separation.
- [Chipmunk Tutorial for iOS: How To Create A Simple iPhone Game | Kodeco](https://www.kodeco.com/3079-chipmunk-tutorial-for-ios-how-to-create-a-simple-iphone-game) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Chipmunk physics is integrated into a small iPhone game to model bodies, forces and collisions. Follow it to see how simulation state should drive sprites, while keeping physics stepping separate from UI event handling.
- [Game Center Tutorial for iOS: How To Make A Simple Multiplayer Game: Part 1/2 | Kodeco](https://www.kodeco.com/3074-game-center-tutorial-for-ios-how-to-make-a-simple-multiplayer-game-part-1-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Game Center multiplayer tutorial establishes authentication, matchmaking and game state for a two-player flow. Follow it to separate service callbacks from local scene state, especially when players disconnect or matches arrive asynchronously.
- [Game Center Tutorial for iOS: How To Make A Simple Multiplayer Game: Part 2/2 | Kodeco](https://www.kodeco.com/3071-game-center-tutorial-for-ios-how-to-make-a-simple-multiplayer-game-part-2-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Game Center continuation handles multiplayer turn state and match updates. Follow it to keep asynchronous service callbacks separate from the local game board, especially when a participant leaves or a match resumes later.
- [Beginning Turn-Based Gaming with iOS 5 Part 2 | Kodeco](https://www.kodeco.com/2998-beginning-turn-based-gaming-with-ios-5-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The turn-based gaming continuation models turn submission and match progression through Game Center. It helps expose asynchronous game-state transitions that should remain separate from the local board’s rendering and input rules.
- [iOS For High School Students: Text Adventure Game | Kodeco](https://www.kodeco.com/2939-ios-for-high-school-students-text-adventure-game) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a text-adventure game with methods, helper functions, properties, object structure, and narrative state. Useful for practicing how small functions and stored state cooperate before a learner encounters the added complexity of UIKit or SwiftUI.
- [What’s New with Game Center in iOS 6 | Kodeco](https://www.kodeco.com/2845-what-s-new-with-game-center-in-ios-6) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Reviews Game Center additions in iOS 6, including service integration points. It is useful historical context for maintaining older games where authentication, leaderboards, and achievements shaped controller flow.
- [How to Make a Simple iOS and Android Game with Corona Tutorial | Kodeco](https://www.kodeco.com/2838-how-to-make-a-simple-ios-and-android-game-with-corona-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Corona shares game logic and rendering concepts across iOS and Android through a scripting engine. Follow it to assess cross-platform iteration speed against native API access and platform-specific packaging constraints.
- [Beginning Unity 3D for iOS: Part 1/3 | Kodeco](https://www.kodeco.com/2804-beginning-unity-3d-for-ios-part-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Unity 3D scene setup, assets, and gameplay foundations for iOS. Useful for orienting game objects, input, and physics before platform-specific deployment concerns.
- [Beginning Unity 3D for iOS: Part 2/3 | Kodeco](https://www.kodeco.com/2803-beginning-unity-3d-for-ios-part-2-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Unity iOS series connects scene objects, input and mobile deployment settings. Follow it to understand the engine-to-native boundary, where rendering, lifecycle and platform services do not share UIKit assumptions.
- [Beginning Unity 3D for iOS: Part 3/3 | Kodeco](https://www.kodeco.com/2802-beginning-unity-3d-for-ios-part-3-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Unity continuation addresses touch controls, scenes and packaging a 3D game for iOS. Its routing value is deployment awareness: engine assets and native app lifecycle have different performance and update constraints.
- [Intermediate Unity 3D for iOS: Part 1/3 | Kodeco](https://www.kodeco.com/2800-intermediate-unity-3d-for-ios-part-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a Unity basketball scene from assets, materials, cameras, colliders, rigid bodies, prefabs, and lighting. Useful for understanding how scene composition and physics setup produce gameplay before scripting starts coordinating player behavior.
- [Intermediate Unity 3D for iOS: Part 2/3 | Kodeco](https://www.kodeco.com/2799-intermediate-unity-3d-for-ios-part-2-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds Unity scripts for collisions, input, game state, animation, player components, and message handling. Useful for seeing how a playable scene turns into coordinated runtime behavior instead of leaving game logic distributed across anonymous callbacks.
- [Learn to Code iOS Apps 4: Making It Beautiful | Kodeco](https://www.kodeco.com/2784-learn-to-code-ios-apps-4-making-it-beautiful) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Finishes a beginner game by adapting images for display density, composing backgrounds, and adding sound. Useful for showing that visual polish involves asset resolution, layering, and feedback choices rather than a final cosmetic pass detached from implementation.
- [Learn to Code iOS Apps 3: Your First App | Kodeco](https://www.kodeco.com/2783-learn-to-code-ios-apps-3-your-first-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a storyboard game using views, controllers, controls, delegates, timers, and game-over transitions. Useful for seeing how basic UIKit event delivery and time-based state changes combine in a small interactive app.
- [Cocos2D-X Tutorial for iOS and Android: Space Game | Kodeco](https://www.kodeco.com/2728-cocos2d-x-tutorial-for-ios-and-android-space-game) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Cocos2D-X demonstrates sharing a game scene across iOS and Android while retaining platform build concerns. It is useful for assessing engine-level reuse versus native integration costs in a cross-platform game.
- [iOS 7 Multitasking Tech Talk Video | Kodeco](https://www.kodeco.com/2576-ios-7-multitasking-tech-talk-video) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces iOS 7 multitasking APIs such as background fetch and silent push notifications. Useful historical context for distinguishing system-scheduled refresh from a foreground app's immediate work.
- [Core Image Tutorial for iOS: Custom Filters | Kodeco](https://www.kodeco.com/25658084-core-image-tutorial-for-ios-custom-filters) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Custom Core Image filters show how kernels transform CIImage values within a GPU-friendly pipeline. The article is useful for deciding when a reusable filter graph beats CPU pixel loops, while tracking color space and performance costs.
- [iOS 7 Blur Effects with GPUImage | Kodeco](https://www.kodeco.com/2558-ios-7-blur-effects-with-gpuimage) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Compares static and live blur approaches, captures view content, handles threading, and applies GPUImage to video. Useful for separating a visual blur's snapshot-based implementation from its more expensive continuously updated rendering path.
- [CocoaPods Tech Talk Video | Kodeco](https://www.kodeco.com/2549-cocoapods-tech-talk-video) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains practical CocoaPods usage and common dependency-management questions. Useful historical context for repositories that still use Pods and need to separate package integration from application code.
- [Video Tutorial: Using LLDB in iOS Part 1: Getting Started | Kodeco](https://www.kodeco.com/2429-video-tutorial-using-lldb-in-ios-part-1-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces LLDB for iOS debugging. Useful for moving beyond print statements toward inspecting state in a paused process.
- [Video Tutorial: Using LLDB in iOS Part 2: Using Expressions | Kodeco](https://www.kodeco.com/2428-video-tutorial-using-lldb-in-ios-part-2-using-expressions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses LLDB expressions to inspect and evaluate runtime values. Useful for testing hypotheses without editing or rebuilding source code.
- [Video Tutorial: Using LLDB in iOS Part 3: Backtraces, Threads, and Frames | Kodeco](https://www.kodeco.com/2426-video-tutorial-using-lldb-in-ios-part-3-backtraces-threads-and-frames) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Reads LLDB backtraces, threads, and frames. Useful for locating the execution path and concurrent context behind a stalled or failing operation.
- [Video Tutorial: Using LLDB in iOS Part 4: Watchpoint, Script, Command | Kodeco](https://www.kodeco.com/2423-video-tutorial-using-lldb-in-ios-part-4-watchpoint-script-command) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses watchpoints, scripts, and LLDB commands to observe memory changes. Useful for catching an unexpected mutation at the instant it occurs.
- [Video Tutorial: Using LLDB in iOS Part 5: Finding Help and Creating Aliases | Kodeco](https://www.kodeco.com/2421-video-tutorial-using-lldb-in-ios-part-5-finding-help-and-creating-aliases) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Finds LLDB help and creates command aliases. Useful for turning repeated debugging steps into a reliable, low-friction personal workflow.
- [Video Tutorial: Using LLDB in iOS Part 6: Extending LLDB | Kodeco](https://www.kodeco.com/2417-video-tutorial-using-lldb-in-ios-part-6-extending-lldb) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Extends LLDB with custom commands and automation. Useful when a recurring diagnostic needs structured output beyond the built-in debugger interface.
- [Video Tutorial: Using LLDB in iOS Part 7: Custom Summaries | Kodeco](https://www.kodeco.com/2416-video-tutorial-using-lldb-in-ios-part-7-custom-summaries) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates LLDB custom summaries for domain objects. Useful for making a paused object's important fields legible without repeatedly expanding implementation detail.
- [Video Tutorial: Using LLDB in iOS Part 8: Using Chisel | Kodeco](https://www.kodeco.com/2414-video-tutorial-using-lldb-in-ios-part-8-using-chisel) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Chisel commands alongside LLDB for UIKit inspection. Useful for rapidly probing view hierarchy and layout state during interactive debugging.
- [Video Tutorial: Using LLDB in iOS Part 9: Using Quicklook | Kodeco](https://www.kodeco.com/2412-video-tutorial-using-lldb-in-ios-part-9-using-quicklook) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Quick Look from LLDB to visualize runtime values. Useful when an image, color, or view is easier to inspect visually than textually.
- [iOS 7 Game Controller Tutorial | Kodeco](https://www.kodeco.com/2399-ios-7-game-controller-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Handles hardware controller connection, thumb-stick input, pause actions, player indicators, and serialized input playback. Useful for designing controller support as a normalized input layer rather than scattering device-specific callbacks through game logic.
- [Video Tutorial: Saving Data in iOS Part 1: NSString and NSData | Kodeco](https://www.kodeco.com/2384-video-tutorial-saving-data-in-ios-part-1-nsstring-and-nsdata) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces NSString and NSData as basic file-backed representations in older iOS code. It provides useful maintenance context for text and byte storage, including the conversion boundaries newer Swift types hide.
- [Video Tutorial: Saving Data in iOS Part 2: Using The Filemanager | Kodeco](https://www.kodeco.com/2378-video-tutorial-saving-data-in-ios-part-2-using-the-filemanager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains writing and organizing files with FileManager in an iOS app. Follow it when choosing document, caches, and support directories, because location and backup policy are part of persistence correctness.
- [Video Tutorial: Saving Data in iOS Part 4: Encoding and Decoding Objects | Kodeco](https://www.kodeco.com/2374-video-tutorial-saving-data-in-ios-part-4-encoding-and-decoding-objects) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows encoding and decoding objects for durable storage in an iOS app. Follow it to reason about archive compatibility, type identity, and migration risks before persisting application models directly.
- [Video Tutorial: Saving Data in iOS Part 9: Introduction to FMDB | Kodeco](https://www.kodeco.com/2366-video-tutorial-saving-data-in-ios-part-9-introduction-to-fmdb) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces FMDB as an Objective-C wrapper around SQLite for iOS persistence. It helps identify the trade-off between direct SQL control and wrapper convenience, including how connection and statement lifetimes affect reliability.
- [SceneKit 3D Programming for iOS: Getting Started | Kodeco](https://www.kodeco.com/23483920-scenekit-3d-programming-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces SceneKit 3D scene construction and rendering. Useful for orienting nodes, cameras, lights, and assets before building interactive spatial behavior.
- [Video Tutorial: Saving Data in iOS Part 6: Using XML | Kodeco](https://www.kodeco.com/2344-video-tutorial-saving-data-in-ios-part-6-using-xml) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates storing and reading XML data in an iOS persistence workflow. Use it when maintaining legacy formats, where parser choice and schema compatibility matter more than adopting a newer serialization convention.
- [Video Tutorial: Saving Data in iOS Part 7: Using JSON | Kodeco](https://www.kodeco.com/2338-video-tutorial-saving-data-in-ios-part-7-using-json) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates storing application data as JSON in iOS. It is useful for understanding serialization trade-offs and file lifecycle before choosing Codable, a database, or a remote synchronization strategy.
- [Image Processing in iOS Part 1: Raw Bitmap Modification | Kodeco](https://www.kodeco.com/2335-image-processing-in-ios-part-1-raw-bitmap-modification) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains pixel bytes, color spaces, coordinate systems, compression, and direct bitmap changes before building a monochrome filter. Useful for grounding image-processing bugs in actual memory representation rather than treating every image effect as a black box.
- [Image Processing in iOS Part 2: Core Graphics, Core Image, and GPUImage | Kodeco](https://www.kodeco.com/2334-image-processing-in-ios-part-2-core-graphics-core-image-and-gpuimage) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements the same image effect with Core Graphics, Core Image, and GPUImage. Useful for comparing CPU drawing, filter pipelines, and GPU-backed processing so an effect's implementation can match its performance and composability needs.
- [How to Port Your Sprite Kit Game from iOS to OS X | Kodeco](https://www.kodeco.com/2299-how-to-port-your-sprite-kit-game-from-ios-to-os-x) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Ports a SpriteKit game from iOS to macOS. Useful for identifying which input, windowing, and presentation assumptions prevent a scene from being truly cross-platform.
- [iOS 8 App Extensions Tech Talk Video | Kodeco](https://www.kodeco.com/2277-ios-8-app-extensions-tech-talk-video) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Gives an overview of iOS 8 app extensions, including Today and Photo extensions. Useful for understanding the separate lifecycle and capability boundary an extension adds to an app product.
- [Video Streaming Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/22372639-video-streaming-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements video streaming in an iOS app. Useful for separating playback configuration, remote media URLs, buffering state, and user controls.
- [Video Tutorial: iOS App Extensions Part 0: Introduction | Kodeco](https://www.kodeco.com/2160-video-tutorial-ios-app-extensions-part-0-introduction) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Provides an overview of iOS app extensions and their distinct execution model. It is useful for deciding whether functionality belongs in an extension, an app, or a shared framework before implementation details lock in.
- [Video Tutorial: iOS App Extensions Part 1: Photo Extensions: Getting Started | Kodeco](https://www.kodeco.com/2159-video-tutorial-ios-app-extensions-part-1-photo-extensions-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces the Photo Editing extension lifecycle and initial integration points. Follow it to understand how the host photo app supplies content, what the extension must return, and where editing state should be isolated.
- [Video Tutorial: iOS App Extensions Part 2: Photo Extensions: Saving Data | Kodeco](https://www.kodeco.com/2155-video-tutorial-ios-app-extensions-part-2-photo-extensions-saving-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows a Photo Editing extension saving adjustment data alongside edited output. The workflow clarifies which representation is durable and how an extension can preserve editability without retaining the original UI session.
- [Video Tutorial: iOS App Extensions Part 3: Photo Extensions: Loading Data | Kodeco](https://www.kodeco.com/2151-video-tutorial-ios-app-extensions-part-3-photo-extensions-loading-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Loads adjustment data in a Photo Editing extension so prior edits can be reopened. Follow it when designing non-destructive editing, where persisted adjustment metadata must be compatible with later rendering.
- [Video Tutorial: iOS App Extensions Part 4: Photo Extensions: Shared Settings | Kodeco](https://www.kodeco.com/2148-video-tutorial-ios-app-extensions-part-4-photo-extensions-shared-settings) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains shared settings for a Photo Editing extension and its containing app. Use it when coordinating configuration across processes, keeping app-group storage and extension lifecycle assumptions explicit.
- [Detect Hand & Body Poses with Vision in iOS | Kodeco](https://www.kodeco.com/21129427-detect-hand-body-poses-with-vision-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Vision hand and body pose detection turns camera frames into normalized landmark observations. Follow it to reason about confidence thresholds, coordinate conversion and frame-processing cost before driving interactive UI from noisy detections.
- [Vonage Video API: Real-Time Video in iOS | Kodeco](https://www.kodeco.com/20935718-vonage-video-api-real-time-video-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Integrates a real-time video API in an iOS app. Useful for modeling session connection, participant streams, permissions, and call-state UI separately.
- [Video Tutorial: WatchKit Part 16: Communicating with the iOS App | Kodeco](https://www.kodeco.com/2085-video-tutorial-watchkit-part-16-communicating-with-the-ios-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows communication between a WatchKit interface and its iOS companion app. Follow it when designing cross-device commands and data transfer, keeping connectivity availability and delayed responses explicit.
- [Video Tutorial: iOS App Extensions Part 6: Today Extensions: Layout | Kodeco](https://www.kodeco.com/2083-video-tutorial-ios-app-extensions-part-6-today-extensions-layout) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds the compact interface of a Today extension and its layout constraints. It is useful for understanding extension-specific presentation limits rather than applying full-app assumptions about available space and interaction.
- [Video Tutorial: iOS App Extensions Part 5: Today Extensions: Getting Started | Kodeco](https://www.kodeco.com/2080-video-tutorial-ios-app-extensions-part-5-today-extensions-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Today extension setup, lifecycle, and embedding in an iOS project. It is useful for understanding extension targets, shared capabilities, and the tighter execution model compared with the containing app.
- [Video Tutorial: iOS App Extensions Part 9: Today Extensions: OpenURL | Kodeco](https://www.kodeco.com/2077-video-tutorial-ios-app-extensions-part-9-today-extensions-openurl) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows a Today extension opening URLs through the host system. The useful boundary is deciding when an extension should hand off to the containing app instead of attempting work that exceeds its limited execution context.
- [Video Tutorial: iOS App Extensions Part 8 Today Extensions: Updating Data | Kodeco](https://www.kodeco.com/2074-video-tutorial-ios-app-extensions-part-8-today-extensions-updating-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains how a Today extension performs network work and refreshes without launching the containing app. Follow it to reason about extension execution limits, cached state, and refresh triggers under system scheduling.
- [Tesseract OCR Tutorial for iOS | Kodeco](https://www.kodeco.com/2010498-tesseract-ocr-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Runs Tesseract OCR on iOS images. Useful for understanding preprocessing, recognition output, and the trade-off between embedded OCR control and service-based recognition.
- [Vision Tutorial for iOS: Detect Body and Hand Pose | Kodeco](https://www.kodeco.com/19454476-vision-tutorial-for-ios-detect-body-and-hand-pose) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Vision body and hand pose detection to extract landmarks from camera imagery. Follow it when gesture or pose features need confidence-aware processing instead of treating every detected point as equally reliable.
- [Vision Framework Tutorial for iOS: Scanning Barcodes | Kodeco](https://www.kodeco.com/12663654-vision-framework-tutorial-for-ios-scanning-barcodes) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a camera-based barcode scanner with Vision and routes recognized payloads into URL handling. The workflow highlights separating capture-session lifecycle, request processing, and user confirmation before opening data supplied by a code.
- [3D Graphics with Metal | Kodeco](https://www.kodeco.com/1258241-3d-graphics-with-metal) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds 3D graphics with Metal through geometry, transforms, shaders, and GPU pipeline setup. Useful for separating matrix math and scene data from draw-command encoding.
- [Face Detection Tutorial Using the Vision Framework for iOS | Kodeco](https://www.kodeco.com/1163620-face-detection-tutorial-using-the-vision-framework-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Vision face detection is applied to a camera feed and its feature bounds are overlaid, demonstrating the handoff from image analysis to on-screen geometry.
- [What’s New In SpriteKit on iOS 10: A Look At Tile Maps | Kodeco](https://www.kodeco.com/1079-what-s-new-in-spritekit-on-ios-10-a-look-at-tile-maps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains SpriteKit tile maps introduced around iOS 10 for building game environments. Follow it when replacing hand-placed nodes with grid-based terrain, keeping map data and rendering concerns separate.
- [Manim - NSHipster](https://nshipster.com/manim) — NSHipster · article catalogue
  **Published:** `2025-10-01T00:00:00-07:00`
  **NeKI brief:** Introduces Manim as a tool for generating mathematical animations from code. Useful for developers creating explanatory visualizations, while keeping its Python-oriented workflow separate from app runtime code.
- [Rendering quadratic Bézier curves with Metal](https://nilcoalescing.com/blog/RenderingQuadraticBezierCurvesWithMetal) — Nil Coalescing · article catalogue
  **Published:** `2025-03-31`
  **NeKI brief:** For freehand strokes with thousands of points, a quadratic Bézier representation can move curve rendering to Metal while tolerating self-intersections. The implementation favors a simple GPU pipeline, making its performance compromises explicit for production drawing tools.
- [Custom function evaluation on the GPU with MPSGraph](https://nilcoalescing.com/blog/FunctionsOnYourGPU) — Nil Coalescing · article catalogue
  **Published:** `2024-08-05`
  **NeKI brief:** MPSGraph evaluates custom functions on the GPU by translating tensor operations into a graph execution plan. The article helps weigh setup overhead and data-transfer cost against throughput for numeric workloads.
- [Advanced Core Image](https://blog.jacobstechtavern.com/p/advanced-core-image) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-06-17T16:15:52.294Z`
  **NeKI brief:** Builds advanced Core Image processing around filter graphs, custom kernels, and GPU-backed rendering, showing how image pipelines compose lazily and where color spaces, context reuse, and output conversion determine correctness and performance.
- [Core Image: The Basics](https://blog.jacobstechtavern.com/p/core-image-the-basics) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-05-27T16:15:04.516Z`
  **NeKI brief:** Introduces Core Image's filter and image-processing model with a practical baseline for composing effects. It is useful for choosing GPU-backed image transformations, while API availability and performance need current verification.
- [Apple Animation Through the Ages: 2019](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-580) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-09-26T08:15:42.449Z`
  **NeKI brief:** Places Apple's animation stack in a historical timeline and connects the 2019 APIs to earlier programming models. Follow it for conceptual context when choosing an animation layer, then verify current framework behavior and availability in Apple documentation.
- [Apple Animation Through the Ages: 2014](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-265) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-09-19T08:15:09.850Z`
  **NeKI brief:** Uses Apple's 2014 animation era to show how framework abstractions evolved across the platform. It is a historical route into animation design decisions; treat version-specific APIs as context and confirm modern equivalents before implementation.
- [Apple Animation Through the Ages: 2007](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-e96) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-09-12T08:15:08.403Z`
  **NeKI brief:** Connects the 2007 iPhone-era animation model to the constraints and abstractions that shaped early UIKit development. Follow for historical perspective on why APIs look the way they do, not as current implementation guidance.
- [Apple Animation Through the Ages: 2001](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-c54) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-09-05T08:15:04.496Z`
  **NeKI brief:** Traces the 2001 transition in Apple's animation tooling and relates it to the programming model later exposed on Apple platforms. The historical comparison helps explain abstraction trade-offs while requiring current API verification.
- [Apple Animation Through the Ages: 1989](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-08-29T08:15:13.907Z`
  **NeKI brief:** Introduces the earliest Apple animation milestone in the series and links hardware-era constraints to later compositing abstractions. Use it as background for platform evolution rather than as a recipe for present-day animation code.
- [What's new in SF Symbols 5 | Sarunw](https://sarunw.com/posts/whats-new-in-sf-symbols-5) — Sarunw · article catalogue
  **Published:** `2023-06-07`
  **NeKI brief:** Covers SF Symbols 5 animation capabilities, including symbolEffect behaviors and customization of layers and timing. It is a versioned design-and-implementation route for adding motion while respecting symbol rendering structure.
- [How to find a font name of a custom font in iOS | Sarunw](https://sarunw.com/posts/how-to-find-font-name-in-ios) — Sarunw · article catalogue
  **Published:** `2022-11-12`
  **NeKI brief:** Finds a font's PostScript name for iOS registration, avoiding silent fallback when custom font files use different display names.
- [SF Font Expanded, Condensed, and Compressed: Three New font width styles in iOS 16 | Sarunw](https://sarunw.com/posts/sf-font-width-styles) — Sarunw · article catalogue
  **Published:** `2022-09-08`
  **NeKI brief:** Explains SF font width styles such as expanded and condensed. Use it when fitting text density while preserving the system typeface and Dynamic Type behavior.
- [What is image rendering mode in iOS | Sarunw](https://sarunw.com/posts/what-is-image-rendering-mode-in-ios) — Sarunw · article catalogue
  **Published:** `2021-12-09`
  **NeKI brief:** UIImage rendering mode determines whether pixels display as authored or as a tintable template. Set it deliberately for icons and controls; an accidental template mode can discard color detail, while original mode prevents expected tint adaptation.
- [How to position an UIButton image to the right side of the text | Sarunw](https://sarunw.com/posts/how-to-position-uibutton-image-to-th-right-side-of-text.md) — Sarunw · article catalogue
  **Published:** `2021-11-18`
  **NeKI brief:** Place a UIButton image after its title using the modern configuration image placement or carefully coordinated semantic layout direction for older APIs. Keep spacing and content insets in the same approach, so right-to-left layouts do not invert a purely visual workaround.
- [How to make a macOS menu bar app | Sarunw](https://sarunw.com/posts/how-to-make-macos-menu-bar-app) — Sarunw · article catalogue
  **Published:** `2021-11-15`
  **NeKI brief:** Build a macOS menu-bar utility by configuring a status item and presenting only the compact actions or popover that belong there. Treat the menu bar as a persistent but low-attention surface, and keep full workflows in a separate window when necessary.
- [How to use different fonts for different languages in an iOS application | Sarunw](https://sarunw.com/posts/how-to-use-different-fonts-for-different-languages-in-ios-application) — Sarunw · article catalogue
  **Published:** `2021-11-08`
  **NeKI brief:** Uses language-specific fonts for localized iOS content. Use it when glyph coverage or typographic conventions require different font choices per locale.
- [How to use custom fonts in WKWebView | Sarunw](https://sarunw.com/posts/how-to-use-custom-fonts-in-wkwebview) — Sarunw · article catalogue
  **Published:** `2021-11-04`
  **NeKI brief:** Loads bundled custom fonts into WKWebView by making the font resource reachable to the HTML/CSS context, keeping native asset registration separate from web-document styling.
- [How to add custom fonts to iOS app | Sarunw](https://sarunw.com/posts/how-to-add-custom-fonts-to-ios-app) — Sarunw · article catalogue
  **Published:** `2021-10-25`
  **NeKI brief:** Bundle custom font files, register them in the target configuration, and verify the PostScript name before applying them in UIKit or SwiftUI. Treat font licensing and Dynamic Type behavior as part of the integration, not merely an asset-copying step.
- [How to resize and position an image in UIImageView using contentMode | Sarunw](https://sarunw.com/posts/how-to-resize-and-position-image-in-uiimageview-using-contentmode) — Sarunw · article catalogue
  **Published:** `2021-03-29`
  **NeKI brief:** Use UIImageView contentMode to choose scaling versus cropping and, where appropriate, positional alignment within its bounds. Match scaleAspectFit, scaleAspectFill, or scaleToFill to the visual contract before changing constraints, because content mode does not change the view's layout size.
- [How to resize an UIImageView to fit a container view using auto layout | Sarunw](https://sarunw.com/posts/how-to-resize-uiimageview-to-fit-container-view-using-auto-layout) — Sarunw · article catalogue
  **Published:** `2021-01-27`
  **NeKI brief:** When an image view competes with other Auto Layout content, lower its compression-resistance priority on the constrained axis instead of hard-coding dimensions. This lets the layout express which view may shrink while preserving the container's required constraints.
- [How to change the color of SF Symbols | Sarunw](https://sarunw.com/posts/how-to-change-color-of-sf-symbols) — Sarunw · article catalogue
  **Published:** `2021-01-04`
  **NeKI brief:** Configure SF Symbol color with tint, foreground styles, or a symbol rendering mode chosen for the intended hierarchy. Use multicolor only where the symbol supports it and the semantic state remains clear, rather than baking a fixed image for every appearance.
- [How to save/export an image in Mac Catalyst | Sarunw](https://sarunw.com/posts/how-to-save-export-image-in-mac-catalyst) — Sarunw · article catalogue
  **Published:** `2020-09-23`
  **NeKI brief:** Export a generated UIImage by writing image data to a temporary URL and presenting a document picker for the user-selected destination. Configure the Mac Catalyst sandbox entitlement and clean up the temporary file after completion or cancellation.
- [What is backIndicatorTransitionMaskImage | Sarunw](https://sarunw.com/posts/what-is-backindicatortransitionmaskimage) — Sarunw · article catalogue
  **Published:** `2020-06-04`
  **NeKI brief:** Explains UIKit's backIndicatorTransitionMaskImage and its role in navigation-bar back indicator transitions. Use it when customizing the back glyph without breaking transition rendering.
- [How to change a back button image | Sarunw](https://sarunw.com/posts/how-to-change-back-button-image) — Sarunw · article catalogue
  **Published:** `2020-05-31`
  **NeKI brief:** Shows changing a UINavigationBar back-button image. Use it when branding navigation while preserving hit targets, tint behavior, and standard back navigation semantics.
- [Match a view's shadow to the Sketch shadow | Sarunw](https://sarunw.com/posts/match-view-shadow-to-sketch-shadow) — Sarunw · article catalogue
  **Published:** `2020-05-20`
  **NeKI brief:** Translates Sketch blur and spread settings into UIKit shadow radius, offset, opacity, and an optional shape-based spread layer. It is useful when visual specifications cannot be matched by assigning design-tool values directly to CALayer properties.
- [Browse SF Symbols on Mac | Sarunw](https://sarunw.com/posts/browse-sf-symbols) — Sarunw · article catalogue
  **Published:** `2019-06-19`
  **NeKI brief:** Use Apple's SF Symbols app to find canonical symbol names, inspect rendering variants, and verify availability before coding UIKit or SwiftUI icons. Prefer system symbol configuration over baked images so weight, scale, color, and accessibility behavior remain platform-adaptive.
- [MapKit JS - NSHipster](https://nshipster.com/mapkit-js) — NSHipster · article catalogue
  **Published:** `2019-03-11T00:00:00-07:00`
  **NeKI brief:** MapKit JS moves Apple's map rendering and search model into web clients, with token configuration and browser lifecycle replacing native delegates. The article highlights the integration trade-off between shared map capabilities and web-specific authentication and performance.
- [macOS Dynamic Desktop - NSHipster](https://nshipster.com/macos-dynamic-desktop) — NSHipster · article catalogue
  **Published:** `2018-10-01T00:00:00-07:00`
  **NeKI brief:** Explains macOS Dynamic Desktop image metadata and the time-aware asset format behind it. Use it when working with appearance- or time-dependent desktop imagery and separating system integration from ordinary image loading.
- [A Farewell to StreamToMe | Cocoa with Love](https://www.cocoawithlove.com/blog/a-farewell-to-streamtome.html) — Cocoa with Love · article catalogue
  **Published:** `2018-09-04`
  **NeKI brief:** Removing a profitable app illustrates the maintenance burden of support, platform changes, and neglected quality; withdrawal can be a deliberate product decision when operational cost outweighs revenue.
- [UIActivityViewController - NSHipster](https://nshipster.com/uiactivityviewcontroller) — NSHipster · article catalogue
  **Published:** `2014-04-21T00:00:00-07:00`
  **NeKI brief:** UIActivityViewController offers system and extension-provided sharing actions for supplied items. Use it to avoid hand-built share menus, excluding unsuitable activity types only when product requirements genuinely demand it.
- [Presenting a Mac dialog sheet with visual cue effects | Cocoa with Love](https://www.cocoawithlove.com/2011/05/presenting-mac-dialog-sheet-with-visual.html) — Cocoa with Love · article catalogue
  **Published:** `2011-05-05`
  **NeKI brief:** AppKit dialog sheets combine modal flow with visual cue effects, requiring window lifecycle coordination so animation feedback does not obscure dismissal or focus behavior.
- [A history of iOS media APIs (iPhone OS 2.0 to iOS 4.3) | Cocoa with Love](https://www.cocoawithlove.com/2011/03/history-of-ios-media-apis-iphone-os-20.html) — Cocoa with Love · article catalogue
  **Published:** `2011-03-20`
  **NeKI brief:** The history of iOS media APIs tracks changing capture, playback, and codec abstractions across early releases. Follow it to understand compatibility constraints before maintaining legacy AVFoundation or MediaPlayer code.
- [Advanced drawing using AppKit | Cocoa with Love](https://www.cocoawithlove.com/2011/01/advanced-drawing-using-appkit.html) — Cocoa with Love · article catalogue
  **Published:** `2011-01-31`
  **NeKI brief:** Advanced AppKit drawing composes paths, transforms, and clipping to control raster output, trading manual geometry for predictable rendering beyond standard controls.
- [Back to the Mac? 12 features from iOS I'd like to see in Lion | Cocoa with Love](https://www.cocoawithlove.com/2010/11/back-to-mac-12-features-from-ios-i-like.html) — Cocoa with Love · article catalogue
  **Published:** `2010-11-20`
  **NeKI brief:** Comparing iOS interaction features with Mac conventions highlights where platform transfer improves consistency and where pointer, keyboard, and window models require different decisions.
- [An iOS tone generator (an introduction to AudioUnits) | Cocoa with Love](https://www.cocoawithlove.com/2010/10/ios-tone-generator-introduction-to.html) — Cocoa with Love · article catalogue
  **Published:** `2010-10-20`
  **NeKI brief:** An AudioUnit tone generator demonstrates buffer-level synthesis and real-time constraints, where allocation or blocking in the render callback would immediately damage playback.
- [Alternative Objective-C object allocation for large arrays | Cocoa with Love](https://www.cocoawithlove.com/2010/08/alternative-objective-c-object.html) — Cocoa with Love · article catalogue
  **Published:** `2010-08-30`
  **NeKI brief:** Alternative Objective-C allocation strategies can reduce overhead for very large arrays by changing object layout and initialization cost. The article is useful historical evidence that allocation behavior should be measured against workload.
- [5 ways to draw a 2D shape with a hole in CoreGraphics | Cocoa with Love](https://www.cocoawithlove.com/2010/05/5-ways-to-draw-2d-shape-with-hole-in.html) — Cocoa with Love · article catalogue
  **Published:** `2010-05-17`
  **NeKI brief:** Core Graphics can create a hole through winding rules, clipping, paths, masks, or compositing, each with different antialiasing behavior. Comparing them helps choose the right rendering mechanism for complex shapes.
- [Streaming MP3/AAC audio again | Cocoa with Love](https://www.cocoawithlove.com/2010/03/streaming-mp3aac-audio-again.html) — Cocoa with Love · article catalogue
  **Published:** `2010-03-29`
  **NeKI brief:** Streaming compressed audio requires buffering, format negotiation, and interruption handling in addition to decoding. Follow it for diagnosing underruns and designing playback that remains responsive on variable networks.
- [Porting RRGlossCausticShader to the iPhone – Ole Begemann](https://oleb.net/blog/2010/02/porting-rrglosscausticshader-to-the-iphone) — Ole Begemann · article catalogue
  **Published:** `2010-02-28T18:02:00Z`
  **NeKI brief:** Porting a Core Graphics effect from AppKit to UIKit isolates platform color and graphics types behind a small adapter, so the rendering algorithm survives while platform-specific APIs stay at the boundary.
- [Creating alpha masks from text on the iPhone and Mac | Cocoa with Love](https://www.cocoawithlove.com/2009/09/creating-alpha-masks-from-text-on.html) — Cocoa with Love · article catalogue
  **Published:** `2009-09-09`
  **NeKI brief:** Creating alpha masks from text uses Core Graphics rendering and image compositing to turn glyph shapes into reusable transparency. Follow it when custom text effects need deterministic raster output.
- [Animating a window to fullscreen on the Mac | Cocoa with Love](https://www.cocoawithlove.com/2009/08/animating-window-to-fullscreen-on-mac.html) — Cocoa with Love · article catalogue
  **Published:** `2009-08-14`
  **NeKI brief:** Animating a Mac window to fullscreen requires coordinating frame changes, screen bounds, and restoration state. Follow it when custom AppKit transitions must remain coherent across displays and resize events.
- [Intercepting status bar touches on the iPhone | Cocoa with Love](https://www.cocoawithlove.com/2009/05/intercepting-status-bar-touches-on.html) — Cocoa with Love · article catalogue
  **Published:** `2009-05-19`
  **NeKI brief:** Intercepting status-bar touches requires working with UIKit's event-routing assumptions rather than adding an ordinary view. The technique is useful historical context for custom gesture behavior near system-controlled areas.
- [Easy custom UITableView drawing | Cocoa with Love](https://www.cocoawithlove.com/2009/04/easy-custom-uitableview-drawing.html) — Cocoa with Love · article catalogue
  **Published:** `2009-04-28`
  **NeKI brief:** Custom UITableView drawing can layer decoration without abandoning cell reuse, but must avoid expensive per-scroll rendering. The article helps balance visual customization against list performance in legacy UIKit.
- [An Asteroids-style game in CoreAnimation, Part Three. | Cocoa with Love](https://www.cocoawithlove.com/2009/03/asteroids-style-game-in-coreanimation.html) — Cocoa with Love · article catalogue
  **Published:** `2009-03-01`
  **NeKI brief:** Core Animation game mechanics require separating model updates from layer presentation so collision and motion remain deterministic. Follow it when visual interpolation must not become the game's source of truth.
- [An Asteroids-style game in CoreAnimation, Part Two. | Cocoa with Love](https://www.cocoawithlove.com/2009/02/asteroids-style-game-in-coreanimation_22.html) — Cocoa with Love · article catalogue
  **Published:** `2009-02-22`
  **NeKI brief:** The Core Animation Asteroids follow-up explores frame updates and layer composition under an interactive workload. It is useful for understanding where rendering convenience stops and game-loop state management begins.
- [An Asteroids-style game in CoreAnimation, Part One. | Cocoa with Love](https://www.cocoawithlove.com/2009/02/asteroids-style-game-in-coreanimation.html) — Cocoa with Love · article catalogue
  **Published:** `2009-02-17`
  **NeKI brief:** Use Core Animation as a 2D game's renderer behind a model-view-controller design, with a constant-aspect view for resolution independence. Keeping world coordinates separate from the window prevents display size from leaking into gameplay calculations.
- [Drawing a custom window on Mac OS X | Cocoa with Love](https://www.cocoawithlove.com/2008/12/drawing-custom-window-on-mac-os-x.html) — Cocoa with Love · article catalogue
  **Published:** `2008-12-12`
  **NeKI brief:** Custom Mac window drawing coordinates frame view rendering, title-bar behavior, and window controls without discarding AppKit lifecycle. Follow it when branding a desktop window while retaining system interactions.
- [Streaming and playing an MP3 stream | Cocoa with Love](https://www.cocoawithlove.com/2008/09/streaming-and-playing-live-mp3-stream.html) — Cocoa with Love · article catalogue
  **Published:** `2008-09-28`
  **NeKI brief:** Extend AudioFileStreamExample into a Cocoa app that incrementally receives, parses, queues, and plays remote MP3 data. The implementation documents stream-buffer boundaries and a crash workaround, showing that live audio needs defensive handling beyond a local-file player.
- [Drawing gloss gradients in CoreGraphics | Cocoa with Love](https://www.cocoawithlove.com/2008/09/drawing-gloss-gradients-in-coregraphics.html) — Cocoa with Love · article catalogue
  **Published:** `2008-09-13`
  **NeKI brief:** Derive every stop in a gloss gradient from one base color, then render the composed effect with Core Graphics. Encapsulating highlight and caustic calculations in one function produces consistent chrome while allowing the base palette to vary.
- [Parametric acceleration curves in Core Animation | Cocoa with Love](https://www.cocoawithlove.com/2008/09/parametric-acceleration-curves-in-core.html) — Cocoa with Love · article catalogue
  **Published:** `2008-09-09`
  **NeKI brief:** CAMediaTimingFunction only covers a limited family of easing curves. Sample a desired parametric curve into CAKeyframeAnimation values when the motion profile matters, accepting more generated keyframes in exchange for exact acceleration behavior.
- [CoreGraphics curves and lines: a sample app | Cocoa with Love](https://www.cocoawithlove.com/2008/07/coregraphics-curves-and-lines-sample.html) — Cocoa with Love · article catalogue
  **Published:** `2008-07-12`
  **NeKI brief:** A small Core Graphics sample exposes line and curve primitives through draggable control points, turning geometry into observable behavior. Interactive handles make Bézier parameters and endpoint relationships easier to validate than static drawing code alone.
- [viewWillDraw - a welcome addition to NSView in 10.5 | Cocoa with Love](https://www.cocoawithlove.com/2008/04/viewwilldraw-welcome-addition-to-nsview.html) — Cocoa with Love · article catalogue
  **Published:** `2008-04-20`
  **NeKI brief:** NSView's viewWillDraw consolidates older layout and drawing-preparation hooks into one pre-draw point. Put geometry-dependent preparation there when it must reflect final layout, rather than scattering equivalent work through obsolete callbacks.
- [mikeash.com: NSOpenGLContext and one-shot](https://www.mikeash.com/pyblog/nsopenglcontext-and-one-shot.html) — Mike Ash · article catalogue
  **NeKI brief:** NSOpenGLContext setup depends on pixel formats, context ownership, and buffer presentation; a one-shot rendering path exposes those prerequisites clearly. Follow it when debugging legacy OpenGL initialization rather than blaming drawing code.
- [mikeash.com: Friday Q&A 2012-08-31: Obtaining and Interpreting Image Data](https://www.mikeash.com/pyblog/friday-qa-2012-08-31-obtaining-and-interpreting-image-data.html) — Mike Ash · article catalogue
  **NeKI brief:** Image buffers require explicit interpretation of pixel format, row stride, color space, and alpha representation before processing. The article prevents treating raw bytes as universal RGBA values.
- [How to scan QR codes with VisionKit for iOS](https://tanaschita.com/20230410-how-to-scan-qr-codes-with-visionkit-for-ios) — Tanaschita · article catalogue
  **NeKI brief:** VisionKit’s DataScannerViewController scans QR codes through a camera-backed system UI. The guide is useful for permission and availability handling, while keeping recognized payloads validated before acting on them.
- [Using SpriteKit to create custom watchOS loading animations](https://martiancraft.com/blog/2017/09/spritekit-tutorial) — MartianCraft · article catalogue
  **NeKI brief:** Embed an SKScene in a watchOS interface controller to create a loading animation when standard watch controls lack the required motion. Separating scene construction from controller hookup keeps rendering behavior contained and makes the animation reusable.

## Newsletter and related leads

- [Rendering SwiftUI Previews with Xcode's MCP Server](https://cuteios.dev/2026/07/14/previews-and-mcp) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Graphics, Media & Games · Xcode
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Builds a SwiftUI preview gallery by combining Xcode’s MCP server, project context, and generated preview metadata. The article maps the moving parts and current limitations, making it useful when evaluating agent-assisted preview tooling.
- [_UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots?ref=createwithswift.com) — Create with Swift · Issue 113 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-27T18:12:28.000Z`
  **NeKI brief:** Explores UIKit's UIPortalView for live view replication without copying or taking snapshots. Follow it when evaluating mirrored or glass-like effects and when deciding how rendering, hierarchy, interaction, and performance constraints affect the design.
- [UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots) — Those Who Swift · Issue 272 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-24`
  **NeKI brief:** Explores UIKit's UIPortalView for live view replication without copying or taking snapshots. Follow it when evaluating mirrored or glass-like effects and when deciding how rendering, hierarchy, interaction, and performance constraints affect the design.
- [WWDC26: Xcode Tips and Tricks Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-xcode-tips-and-tricks-group) — iOS Dev Weekly · Issue 755 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Xcode
  **Published:** `19th June 2026`
  **NeKI brief:** Explains WWDC26: Xcode Tips and Tricks Group Lab - Q&A, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift](https://antongubarenko.substack.com/p/wwdc26-swift-group-lab-q-and-a) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
- [SwiftUI for Beginners](https://antongubarenko.substack.com/p/wwdc26-swiftui-for-beginners-group) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** A WWDC26 beginner-group Q&A focused on SwiftUI fundamentals and onboarding questions. Use it to identify recurring learning obstacles, while checking current API behavior in Apple's own session recordings and documentation.
- [SwiftUI Advanced](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-q-and-a) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
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
- [Clueso](https://www.clueso.io/) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** Clueso creates product tutorials and documentation from recorded workflows, combining screen capture with automated narration or editing. It is useful for producing onboarding material quickly, provided generated explanations are reviewed for accuracy and accessibility.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — SwiftLee Weekly · Issue 326 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `2026-06-02T14:07:19.000Z`
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [KadrUI](https://github.com/SteliyanH/kadr-ui) — Fatbobman’s Swift Weekly · Issue 134 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-05-04T12:03:54.604Z`
  **NeKI brief:** KadrUI supplies SwiftUI editing components such as multi-track timelines, inspectors, overlays, and keyframe editing. Use it when a video or motion-editing product needs a structured editor surface rather than isolated custom controls.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [SwiftUI Live Broadcasting With AWS IVS](https://medium.com/@itsuki.enjoy/swiftui-live-broadcasting-with-aws-ivs-bcd461764e2b) — Those Who Swift · Issue 259 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-26`
  **NeKI brief:** Examines SwiftUI Live Broadcasting With AWS IVS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Those Who Swift · Issue 258 — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Learning to develop more accessible iOS games](https://accessibilityupto11.com/post/2026-02-22-01) — SwiftLee Weekly · Issue 315 — Article · Topics: Accessibility · Graphics, Media & Games
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Presents Learning to develop more accessible iOS games, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Speed Hacks for iOS Builds](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Those Who Swift · Issue 257 — Article · Topics: Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Those Who Swift · Issue 257 — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Building a Reusable Network Manager in Swift](https://www.youtube.com/watch?v=zEzIxdA8zLQ) — Those Who Swift · Issue 256 — Video · Topics: Concurrency · Networking · Swift
  **Published:** `2026-03-06`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Morphing Sheets Out of Buttons in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/morphing-sheets-out-of-buttons-in-swiftui) — iOS Dev Weekly · Issue 743 — Tutorial · Topics: AI Development · Swift · SwiftUI
  **Published:** `13th February 2026`
  **NeKI brief:** Demonstrates morphing a SwiftUI button into sheet content using matched visual state and presentation transitions. Useful for building expressive modal affordances while keeping trigger state, accessibility, and dismissal behavior explicit.
- [Swift Concurrency from Zero to Hero](https://swiftology.io/articles/swift-concurrency-zero-to-hero) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Concurrency · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Explores Swift Concurrency from Zero to Hero with concrete Swift concurrency examples. Follow it to reason about isolation, cancellation, and Sendable boundaries, then verify availability and diagnostics against current Swift documentation.
- [WWDC Index](https://nonstrict.eu/wwdcindex) — iOS Dev Weekly · Issue 739 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** This technical resource covers a searchable index of WWDC material. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Agent Skills explained: Replacing AGENTS.md with reusable AI knowledge](https://www.youtube.com/watch?v=khekVi1PK3o) — SwiftLee Weekly · Issue 306 — Video · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — SwiftLee Weekly · Issue 306 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Provides a SwiftUI learning course playlist covering navigation and related interface patterns. Use it as a structured route through implementations, checking each example against current APIs before adopting its presentation or state-management techniques.
- [MarkdownView](https://github.com/LiYanan2004/MarkdownView) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** MarkdownView renders richer Markdown in SwiftUI, including mixed text and image layouts, selectable content, and interaction hooks. Use it when AttributedString's built-in Markdown support is too limited for a document-reading surface.
- [RichText](https://github.com/LiYanan2004/RichText) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** RichText supplies interactive, styled rich-text components for SwiftUI beyond ordinary Text rendering. Use it when links, mixed media, selection, or fine-grained text actions need an explicit view-layer solution.
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://youtu.be/y_Qc8cT-O_g?si=W2ExWkL4BbMjT8cH) — SwiftLee Weekly · Issue 298 — Video · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-18T19:03:17.000Z`
  **NeKI brief:** Presents Approachable Concurrency in Swift 6.2: A Clear Guide as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Those Who Swift · Issue 240 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — SwiftUI Weekly · SwiftUI Weekly - Issue #224 — Video · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `2025-11-03T11:19:35.224Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Build performance analysis for speeding up Xcode builds](https://youtu.be/9L1p0McuThM) — SwiftLee Weekly · Issue 295 — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **Published:** `2025-10-28T15:02:32.000Z`
  **NeKI brief:** Presents Build performance analysis for speeding up Xcode builds as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [video that demonstrates it](https://youtu.be/jYhRXZwO0cc) — iOS Dev Weekly · Issue 732 — Video · Topics: Graphics, Media & Games · Liquid Glass
  **Published:** `24th October 2025`
  **NeKI brief:** Presents video that demonstrates it for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Crafting Interactive Tiles in SwiftUI](https://uvolchyk.me/blog/crafting-interactive-tiles-in-swiftui) — Those Who Swift · Issue 237 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-22`
  **NeKI brief:** Examines Crafting Interactive Tiles in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — SwiftLee Weekly · Issue 294 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents SwiftUI Architecture: Structure Views for Reusability and Clarity as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Transforming Glass Views with the glassEffectID in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/transforming-glass-views-with-the-glasseffectid-modifier-in-swiftui) — SwiftLee Weekly · Issue 294 — Tutorial · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents Transforming Glass Views with the glassEffectID in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Those Who Swift · Issue 236 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-15`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Ship better paywalls faster with RevenueCat’s native, customizable Paywall Builder](https://www.revenuecat.com/docs/tools/paywalls-v2) — iOS Dev Weekly · Issue 726 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th September 2025`
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Haptic Video Sync](https://github.com/thomasdye12/HapticPlayer) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** HapticPlayer is an iOS haptic playback example, providing a focused repository for experimenting with Core Haptics patterns. Useful for isolating feedback timing and device capability checks before embedding haptics into a larger feature.
- [Pedometer++ Redesign Walkthrough](https://david-smith.org/blog/2025/09/04/pedometer-redesign) — iOS Dev Weekly · Issue 725 — Article · Topics: Graphics, Media & Games · Liquid Glass · Testing
  **Published:** `5th September 2025`
  **NeKI brief:** Presents pedometer++ redesign walkthrough for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Rauhul Varma wrote about writing Playdate games in Swift](https://www.swift.org/blog/byte-sized-swift-tiny-games-playdate) — iOS Dev Weekly · Issue 724 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `29th August 2025`
  **NeKI brief:** Presents rauhul varma wrote about writing playdate games in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [High-Level Anatomy of a Camera Capturing Session](https://mfaani.com/posts/ios/swiftui-camera-learnings) — Those Who Swift · Issue 229 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-08-27`
  **NeKI brief:** Examines High-Level Anatomy of a Camera Capturing Session, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Core Image Metal Shader Library in a Swift Package Plugin](https://juniperphoton.substack.com/p/creating-core-image-metal-shader) — Those Who Swift · Issue 227 — Article · Topics: Graphics, Media & Games · Swift · Swift Package Manager
  **Published:** `2025-08-13`
  **NeKI brief:** Examines Creating Core Image Metal Shader Library in a Swift Package Plugin, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [current code](https://projects.blender.org/blender/blender.git) — Fatbobman’s Swift Weekly · Issue 95 — Tutorial · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `2025-07-28T12:02:57.187Z`
  **NeKI brief:** Blender is a large open-source 3D creation suite with a mature cross-platform codebase. Use the repository as a comparison point for graphics tooling and architecture, not as a Swift or Apple UI dependency.
- [Build Real-Time Communication Experiences with Stream](https://getstream.io/chat/sdk/ios) — iOS Dev Weekly · Issue 719 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `25th July 2025`
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 92 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-07-07T12:01:56.119Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 278 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Xcode
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [macOS by Tutorials](https://sarahreichelt.gumroad.com/l/oximx) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Presents macos by tutorials for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Introducing PickerKit for SwiftUI](https://danielsaidi.com/blog/2025/06/10/introducing-pickerkit-for-swiftui) — SwiftLee Weekly · Issue 275 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-06-12T15:03:23.000Z`
  **NeKI brief:** Presents Introducing PickerKit for SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The pregame quiz ’25](https://www.swiftjectivec.com/wwdc-2025-the-pregame-quiz) — iOS Dev Weekly · Issue 713 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `6th June 2025`
  **NeKI brief:** Presents W.W.D.C. 2025: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to profile a SwiftUI app's performance?](https://www.youtube.com/watch?v=Dyh-ymg-qAo) — Those Who Swift · Issue 212 — Video · Topics: Performance · Swift · SwiftUI
  **Published:** `2025-04-30`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [A flowing WebGL gradient, deconstructed](https://alexharri.com/blog/webgl-gradients) — iOS Dev Weekly · Issue 709 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `25th April 2025`
  **NeKI brief:** Deconstructs a flowing gradient built with a WebGL shader, noise functions, and mathematical transforms. The rendering ideas transfer well to Metal or custom graphics work when a polished animated background needs an explainable, tunable implementation.
- [latest post](https://snopia.net/en/blog/recipe-sticker-effect-swiftui) — iOS Dev Weekly · Issue 709 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `25th April 2025`
  **NeKI brief:** Presents latest post for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift 6.1 ReleasedSwift 6.1 is now available!Swift.orgApple Inc.](https://www.swift.org/blog/swift-6.1-released?ref=createwithswift.com) — Create with Swift · Issue 56 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2025-04-11T15:33:31.000Z`
  **NeKI brief:** Summarizes the Swift 6.1 release and its ecosystem changes. Use it as a starting point for compiler or package upgrades, verifying source compatibility, concurrency diagnostics, and platform support against the toolchain you actually ship.
- [Tracking Down Memory Leaks with Instruments](https://www.youtube.com/watch?v=j8y-LtRV4hM) — Those Who Swift · Issue 207 — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **Published:** `2025-03-28`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [next edition](https://swiftheroes.com/2025) — iOS Dev Weekly · Issue 704 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `21st March 2025`
  **NeKI brief:** Swift Heroes 2025 is a conference resource for Swift developers. Use its talks and programme to discover community approaches to language, frameworks, architecture, and tooling.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui?ref=createwithswift.com) — Create with Swift · Issue 52 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-14T17:00:20.000Z`
  **NeKI brief:** Presents Rendering Pixel Art with SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — iOS Dev Weekly · Issue 703 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `14th March 2025`
  **NeKI brief:** Presents Rendering Pixel Art with SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [Swift DevRoom at FOSDEM 2025 Videos](https://swiftlang.github.io/event-fosdem) — iOS Dev Weekly · Issue 701 — Article · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `28th February 2025`
  **NeKI brief:** Collects Swift DevRoom talks from FOSDEM 2025 in one searchable programme and video index. Use the recordings to compare implementation techniques and ecosystem direction, then follow the referenced repositories or proposals when a talk informs production design.
- [SwiftUI Image Playground](https://www.youtube.com/watch?v=fjtWpQGs5lU) — Those Who Swift · Issue 200 — Video · Topics: AI Development · Swift · SwiftUI
  **Published:** `2025-02-05`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [What was that doing in my database](https://eieio.games/essays/the-secret-in-one-million-checkboxes) — iOS Dev Weekly · Issue 692 — Article · Topics: Graphics, Media & Games · Persistence & Synchronisation
  **Published:** `20th December 2024`
  **NeKI brief:** Presents what was that doing in my database for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftUI Zoom Navigation Transitions: Add a Touch of Magic to Your App](https://www.stphndxn.com/swiftui-zoom-navigation-transitions-add-a-touch-of-magic-to-your-app) — SwiftUI Weekly · SwiftUI Weekly - Issue #204 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-12-03T07:24:48.832Z`
  **NeKI brief:** Demonstrates zoom navigation transitions between SwiftUI source and destination views. Useful for preserving visual continuity when tapping thumbnails into detail screens.
- [SwiftUI Experiments](https://github.com/mikelikesdesign/SwiftUI-experiments) — iOS Dev Weekly · Issue 688 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `22nd November 2024`
  **NeKI brief:** Presents swiftui experiments for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [MockData, PreviewModifiers and PreviewTraits in SwiftUI](https://www.youtube.com/watch?v=Yw7H4Ujpwtg) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [MeshGradients in iOS 18](https://www.youtube.com/watch?v=s_eQZ8rRV8Y) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Video · Topics: Graphics, Media & Games
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Olympic Logo in SwiftUI](https://medium.com/@alessandromanilii/olympic-logo-in-swiftui-dee37cbd53f1) — SwiftUI Weekly · SwiftUI Weekly - Issue #195 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-08-05T15:18:59.956Z`
  **NeKI brief:** Builds the Olympic logo with SwiftUI shapes and composition. Useful as a concrete exercise in layering, geometry, and reusable vector-style drawing.
- [SwiftConf](https://swiftconf.com/) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** SwiftConf is a conference resource featuring talks on Swift, Apple frameworks, architecture, and engineering practice. Use its programme to find community perspectives and verify technical claims independently.
- [PragmaConf](https://pragmaconference.com/) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** Provides the Pragmaconference event hub for talks and community sessions about Apple development. Use it to discover practitioner perspectives and verify session details before relying on a conference presentation.
- [Building chat and struggling with state, push notifications, and more? 🤓💬](https://getstream.io/tutorials/ios-chat) — iOS Dev Weekly · Issue 671 — Tutorial · Topics: App Services & Extensions · Graphics, Media & Games
  **Published:** `26th July 2024`
  **NeKI brief:** Walks through integrating Stream's chat SDK into an iOS app, including message UI and networking. Useful as an implementation reference when evaluating managed real-time messaging.
- [Zoom Transitions in SwiftUI](https://www.youtube.com/watch?v=malwmE5fDHw) — SwiftUI Weekly · SwiftUI Weekly - Issue #194 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-15T12:03:07.308Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Laying out views with ContainerRelativeFrame in SwiftUI](https://www.youtube.com/watch?v=DudvesMYAAY) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [My Favorite SwiftUI Updates in iOS 18](https://www.youtube.com/watch?v=aCbh9LmIZTI) — SwiftUI Weekly · SwiftUI Weekly - Issue #192 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-02T09:09:59.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using TextRenderer to create highlighted text](https://alexanderweiss.dev/blog/2024-06-24-using-textrenderer-to-create-highlighted-text) — iOS Dev Weekly · Issue 667 — Article · Topics: Graphics, Media & Games
  **Published:** `28th June 2024`
  **NeKI brief:** Uses TextRenderer to draw highlighted text in SwiftUI. Useful for search results, annotation, or syntax emphasis where attributed-string styling alone is insufficient.
- [Did you know that Xcode Previews also work with UIKit?](https://www.youtube.com/watch?v=sC0WnigbmJw) — SwiftUI Weekly · SwiftUI Weekly - Issue #187 — Video · Topics: Graphics, Media & Games · UIKit · Xcode
  **Published:** `2024-05-20T22:04:41.287Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Flighty in SwiftUI](https://www.youtube.com/watch?v=81FwPLo-1eE) — SwiftUI Weekly · SwiftUI Weekly - Issue #185 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-05-06T13:22:31.904Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How to add a privacy manifest file to your app for required reason API usage?](https://www.donnywals.com/how-to-add-a-privacy-manifest-file-to-your-app-for-required-reason-api-usage?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Tutorial · Topics: Graphics, Media & Games · Security & Privacy
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A privacy manifest declares required-reason API use for review tooling, so entries must match actual calls and remain maintained as dependencies change.
- [The Curious Case of Apple's Third-Party SDK List for Privacy Manifests](https://www.jessesquires.com/blog/2024/04/29/sdk-privacy-manifests?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Tutorial · Topics: Graphics, Media & Games · Security & Privacy
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** Uses The Curious Case of Apple's Third-Party SDK List for Privacy Manifests as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [Swift Server Workgroup](https://www.swift.org/sswg) — iOS Dev Weekly · Issue 658 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Improve Test Clarity (TDD with SwiftUI)](https://www.youtube.com/watch?v=AF8cCxrJr8M) — SwiftUI Weekly · SwiftUI Weekly - Issue #183 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-04-22T17:42:59.039Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How to Play Spatial Video On iOS 17.2](https://xreality.zone/zh/posts/how-to-play-spatial-video-on-ios-17-2) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Demonstrates playing spatial video on iOS 17.2 and discusses the media and device prerequisites involved. Use it to investigate immersive-video playback paths while verifying format support and availability against current Apple APIs.
- [App Localizations](https://www.youtube.com/watch?v=kbgNL7VrQPo) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: Graphics, Media & Games · Localization · Swift
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Inferno](https://github.com/twostraws/Inferno) — Fatbobman’s Swift Weekly · Issue 7 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Inferno is a SwiftUI-focused learning and example repository from Paul Hudson. Useful as a code-reading route for modern view composition, provided examples are checked against the target SDK.
- [creating custom shaders](https://www.youtube.com/watch?v=EgzWwgRpUuw) — Fatbobman’s Swift Weekly · Issue 7 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Shader course](https://www.hackingwithswift.com/plus/advanced-swiftui/how-to-create-metal-shaders-for-swiftui-part-1) — Fatbobman’s Swift Weekly · Issue 7 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Introduces a course workflow for creating Metal shaders used by SwiftUI, from shader functions to view integration. Use it to structure GPU-effect experiments while keeping parameter flow, performance, and fallback behavior testable.
- [Stream](https://getstream.io/chat/sdk/swiftui) — iOS Dev Weekly · Issue 635 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `10th November 2023`
  **NeKI brief:** Presents stream for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Building Complex Scroll Animations With New iOS 17 API's](https://www.youtube.com/watch?v=ytRim2TSdyY) — SwiftUI Weekly · SwiftUI Weekly - Issue #167 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-06T09:00:48.537Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [A Comprehensive Guide to App Accessibility](https://getstream.io/blog/app-accessibility-guide) — Fatbobman’s Swift Weekly · Issue 4 — Article · Topics: Accessibility · Graphics, Media & Games · Performance
  **Published:** `2023-10-30T15:20:20.330Z`
  **NeKI brief:** Presents an app accessibility guide spanning semantic labeling, contrast, and assistive-technology interaction. Use it as a broad review checklist before drilling into platform-specific VoiceOver or Dynamic Type fixes.
- [On Launching your Indie App: Part 1](https://www.swiftjectivec.com/on-launching-your-indie-app) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Reflects on launching an independent app, including product scope, marketing, and release realities. Use it as practitioner context when planning an indie product beyond implementation alone.
- [Running Stable Diffusion with Core ML on iOS smoothly](https://zenn.dev/shu223/articles/coreml-stable-diffusion) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: Graphics, Media & Games · Personal Essays
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Describes running Stable Diffusion with Core ML on iOS and the optimization constraints involved in local inference. Use it to investigate model conversion, memory pressure, and device performance before adopting generative image features.
- [iPhone 15 Pro / Apple Vision Pro 上的空间视频，到底是什么？](https://xreality.zone/zh/posts/what-is-spatial-video-on-iphone-15-pro-and-apple-vision-pro) — Fatbobman’s Swift Weekly · Issue 1 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Introduces spatial video captured on iPhone 15 Pro and viewed on Apple Vision Pro, covering the format's stereoscopic intent. Use it to orient media-pipeline decisions while validating capture, playback, and conversion support in current frameworks.
- [Daniel Steinberg - SwiftUI to destroy the Publishing Industry](https://www.youtube.com/watch?v=rhqASksgJu0) — SwiftUI Weekly · SwiftUI Weekly - Issue #163 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T12:59:37.492Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Chris Eidhof - A Day in the Life of a SwiftUI View](https://www.youtube.com/watch?v=MRY3UCUVv98) — SwiftUI Weekly · SwiftUI Weekly - Issue #163 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T12:59:37.492Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Applying metal shader to text in SwiftUI](https://augmentedcode.io/2023/08/07/applying-metal-shader-to-text-in-swiftui) — iOS Dev Weekly · Issue 622 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Applies a simple Metal shader to SwiftUI text using the shader-related view modifiers introduced with WWDC 2023. A compact first example for learning how ShaderLibrary effects connect SwiftUI views to custom Metal code.
- [Swift Macros](https://www.youtube.com/playlist?list=PLlc_rDuPW0Y2Z2T1Dv-je_fG1ZQyIhehi) — iOS Dev Weekly · Issue 620 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Swift
  **Published:** `28th July 2023`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [SwiftUI AlignmentGuides](https://www.youtube.com/watch?v=fdSGlCgz1fQ) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [React Native Vision Camera - Capture the World Differently](https://github.com/daltoniam/Starscream) — iOS Dev Tools · 🔨 Real-time Rendering & Stunning Imagery — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2023-07-13T13:51:39.780Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Build an app using SwiftData](https://www.youtube.com/playlist?list=PLvUWi5tdh92wZ5_iDMcBpenwTgFNan9T7) — iOS Dev Weekly · Issue 617 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Relationships In SwiftData](https://www.youtube.com/watch?v=_QMalUGTM4E&feature=youtu.be) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Data Flow in iOS 17 - Observation](https://www.youtube.com/watch?v=EK7SthdWV2w) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift-Macros: A curated list of awesome Swift Macros](https://github.com/krzysztofzablocki/Swift-Macros) — iOS Dev Weekly · Issue 614 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `16th June 2023`
  **NeKI brief:** Explores Swift-Macros: A curated list of awesome Swift Macros, focusing on the article discusses want to write something more detailed about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Display Text Like a Pro in SwiftUI](https://youtu.be/AJMycg7Llv0) — iOS Dev Weekly · Issue 610 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `19th May 2023`
  **NeKI brief:** Explores Display Text Like a Pro in SwiftUI, focusing on this video from vincent pradeilles and natalia panferova is excellent.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Showcase View - Highlight App New Features](https://www.youtube.com/watch?v=I9v-zqrE8gI) — SwiftUI Weekly · SwiftUI Weekly - Issue #142 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-05-15T09:13:45.627Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Apple Platforms Developer @ Cascable AB](https://cascable.se/jobs) — iOS Dev Weekly · Issue 607 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `28th April 2023`
  **NeKI brief:** Explores Apple Platforms Developer @ Cascable AB, focusing on apple platforms developer @ cascable ab – cascable is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Speedrun Design: Heart Rate Zone View in SwiftUI](https://www.david-smith.org/blog/2023/04/24/design-notes-35) — SwiftUI Weekly · SwiftUI Weekly - Issue #140 — Article · Topics: Graphics, Media & Games · Personal Essays · Swift
  **Published:** `2023-04-25T07:37:25.660Z`
  **NeKI brief:** Builds a SwiftUI heart-rate-zone view as a compact design exercise, exposing the visual decisions behind a data-driven display. It is useful for studying how a constrained, real-world metric can become a readable custom SwiftUI component.
- [Can ChatGPT write better SwiftUI code than you?](https://www.youtube.com/watch?v=dxxCPdcMcFw) — SwiftUI Weekly · SwiftUI Weekly - Issue #136 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-03-27T21:57:02.938Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The difference between List and LazyVStack](https://dimillian.medium.com/swiftui-the-difference-between-list-and-lazyvstack-3d5eeaccb156) — iOS Dev Weekly · Issue 599 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `3rd March 2023`
  **NeKI brief:** Compares List with LazyVStack through the rendering, scrolling, and interaction behaviour that makes them different despite similar output. Follow it before replacing one with the other in a performance-sensitive screen or a layout needing list-specific capabilities.
- [Arc Coding Chronicles](https://www.youtube.com/watch?v=94asyypYj5c) — SwiftUI Weekly · SwiftUI Weekly - Issue #132 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2023-02-21T07:37:59.536Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — SwiftUI Weekly · SwiftUI Weekly - Issue #121 — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **Published:** `2022-11-21T12:42:39.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Women Who Code Mobile Summit 2022](https://www.youtube.com/playlist?list=PLVcEZG2JPVhf_iA733UhMxPS0H8iCoouj) — iOS Dev Weekly · Issue 580 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `14th October 2022`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Extracting Views Into Components in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9Rkk0WXJtR2VncWciLCJwb3N0X2lkIjoiZmM1Y2I3MDEtMzdkNy00YTFjLWI1ZmUtMGY3NjAzYzcxNDVmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhNWVmMDA2LWIzZWMtNDcyZi1iNDgxLTIyMzdlYjE4NmZjNyIsImlhdCI6MTY3NDA2MjU1Ny45ODUsImlzcyI6Im9yY2hpZCJ9.gTL9x1122ggPRSt8rIVlwZE8wGlOmIW2f0Z_J-RWaso) — SwiftUI Weekly · SwiftUI Weekly - Issue #111 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-08-01T20:26:06.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Mastering NavigationStack in SwiftUI. Navigator Pattern.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA2LzE1L21hc3RlcmluZy1uYXZpZ2F0aW9uc3RhY2staW4tc3dpZnR1aS1uYXZpZ2F0b3ItcGF0dGVybi8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.-tZb7r5BXvSxhCgyx7-7lMYTg9-uqRno78zJ8Lvvbjs) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Explains a navigator pattern around NavigationStack, turning destinations and routing decisions into explicit state. Useful for testing deep links, centralizing navigation mutations, and keeping feature views independent of presentation mechanics.
- [Build a 3D Bar Chart in SceneKit With SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2JldHRlcnByb2dyYW1taW5nLnB1Yi9idWlsZC1hLTNkLWJhci1jaGFydC1pbi1zY2VuZWtpdC13aXRoLXN3aWZ0dWktNzg5YTI2MzFlZjZmP2dpPTg1YzdjMDE1YTk1JnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZThjMmRiMDAtOWNjYy00ZDliLWJiOTYtZDFlNjA1NzYxYTk3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhOGIyNTg0LTJhM2MtNDlkNS04ZTc5LTUzNTY3ZTQyNTk2NiIsImlhdCI6MTY3NDA2MjU1OC44NzMsImlzcyI6Im9yY2hpZCJ9.oERc-pJ7HTDhbqnjYoyFf6zEXGXSuMjroDQDR8UEYh8) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Combines SceneKit’s 3D bar geometry with SwiftUI presentation to visualize data interactively. Useful when a chart needs depth, rotation, or custom scene rendering beyond native SwiftUI charts.
- [How to Make a Game Like Wordle in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8zMTY2MTI2My1ob3ctdG8tbWFrZS1hLWdhbWUtbGlrZS13b3JkbGUtaW4tc3dpZnR1aS1wYXJ0LW9uZT9oc3NfY2hhbm5lbD10dy04MDg0MzI2MiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fY29udGVudD0yMDg5OTg0MjUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyIiwicG9zdF9pZCI6ImRhYmRkNzEwLWM0MDgtNGFmYS04NDI4LTRlZGUxNWIzMmM3NSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJiOGViODljMC02MGFkLTQ2MjYtODY4Zi1mZWJkNDAzYTdhNzkiLCJpYXQiOjE2NzQwNjI1NTkuMTI5LCJpc3MiOiJvcmNoaWQifQ.hnLhTIeWgfOZ5bBnbKNbq0UhoAvhtPpAB7w93UZfYns) — SwiftUI Weekly · SwiftUI Weekly - Issue #104 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-05-23T22:33:49.000Z`
  **NeKI brief:** Builds a Wordle-style game in SwiftUI, covering tile state, guesses, keyboard input, and feedback. Useful as a concrete exercise in modeling transient game state and composing grid-based UI.
- [Build an Onboarding Flow in SwiftUI with @AppStorage, Transition, Login & Logout](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9eGk5VDhqZjdSWFkiLCJwb3N0X2lkIjoiZGFiZGQ3MTAtYzQwOC00YWZhLTg0MjgtNGVkZTE1YjMyYzc1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImI4ZWI4OWMwLTYwYWQtNDYyNi04NjhmLWZlYmQ0MDNhN2E3OSIsImlhdCI6MTY3NDA2MjU1OS4xMjksImlzcyI6Im9yY2hpZCJ9.akbcSLgLlU5s2GXo_iu6cFB4rQrMCYzqJZjyvqmRbTI) — SwiftUI Weekly · SwiftUI Weekly - Issue #104 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-05-23T22:33:49.000Z`
  **NeKI brief:** Constructs an onboarding and authentication flow using @AppStorage, transitions, and login/logout state. Useful for separating persisted session decisions from view presentation while keeping first-run navigation predictable.
- [Better performance with canvas in SwiftUI](https://swdevnotes.com/swift/2022/better-performance-with-canvas-in-swiftui) — iOS Dev Weekly · Issue 548 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `4th March 2022`
  **NeKI brief:** Explores Better performance with canvas in SwiftUI, focusing on the article discusses enjoyed this article from eric callanan on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Filtering with the Searchable Modifier](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD90PThzJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj13em9YV2haVUI1byIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.MIRHY06NAcrGpIiXhmfgyOFumNl-UFq7Q2nKMIMwGeY) — SwiftUI Weekly · SwiftUI Weekly - Issue #94 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2022-02-28T09:54:32.000Z`
  **NeKI brief:** Demonstrates searchable-based filtering in SwiftUI, connecting query text to collection results. Useful for building discoverable list search while deciding where normalization, debouncing, and empty-state handling belong.
- [Building a Camera App With SwiftUI and Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8yNjI0NDc5My1idWlsZGluZy1hLWNhbWVyYS1hcHAtd2l0aC1zd2lmdHVpLWFuZC1jb21iaW5lP3V0bV9jYW1wYWlnbj1idWZmZXImdXRtX2NvbnRlbnQ9YnVmZmVyZDA5NDUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyLmNvbSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.EYtjzcEt9k9qHn7Q5bQvobwNg9NVsUag7xF3x7v0QKc) — SwiftUI Weekly · SwiftUI Weekly - Issue #83 — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `2021-11-15T14:19:45.000Z`
  **NeKI brief:** Builds a camera experience by bridging capture APIs into SwiftUI with Combine-backed state. Useful for understanding preview integration, authorization, capture events, and lifecycle management around UIKit services.
- [Getting Started with Swift Concurrency](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1VNmxRdXN0aVRHRSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.b6NKewbwPA4mJtumWudUDdzfNgnrnE7GRvN53k3htnk) — SwiftUI Weekly · SwiftUI Weekly - Issue #83 — Tutorial · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `2021-11-15T14:19:45.000Z`
  **NeKI brief:** Introduces Swift concurrency concepts and basic async code through practical examples. Useful for understanding async/await, task structure, and the migration mindset before applying concurrency to SwiftUI features.
- [Keeping WWDC videos and sample code current](https://dimsumthinking.com/Blog/2021/08/30-KeepingCurrent.html) — iOS Dev Weekly · Issue 523 — Article · Topics: Apple Platform Ecosystem · Concurrency · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Keeping WWDC videos and sample code current, focusing on here’s another advantage of not having on-stage presentations at wwdc.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Testing your mobile app internally isn’t enough to ensure its quality](https://instabug.com/product/app-performance-monitoring) — iOS Dev Weekly · Issue 517 — Article · Topics: Graphics, Media & Games · Performance · Testing
  **Published:** `23rd July 2021`
  **NeKI brief:** Explores Testing your mobile app internally isn’t enough to ensure its quality, focusing on whether it’s a crash, slow screen transitions, slow network calls. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Protocols in Gradient and Chroma Game](https://rudrank.blog/protocols-in-gradient-game) — iOS Dev Weekly · Issue 515 — Article · Topics: Concurrency · Graphics, Media & Games
  **Published:** `9th July 2021`
  **NeKI brief:** Explores Protocols in Gradient and Chroma Game, focusing on the article discusses really liked this story of refactoring an. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [this YouTube channel](https://www.youtube.com/channel/UCOYNV2EifmBprMdSESVEu9g/videos) — iOS Dev Weekly · Issue 505 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `30th April 2021`
  **NeKI brief:** Explores this YouTube channel, focusing on the article discusses lost about two hours yesterday to this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [in video form](https://vimeo.com/536908653) — iOS Dev Weekly · Issue 504 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `23rd April 2021`
  **NeKI brief:** Explores in video form, focusing on i’m not sure i know anyone who cares quite as. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Build Complete Apple Watch Tasks App Clone in WatchOS, SwiftUI with CoreData](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9OVFxdzU5NXFkY0UiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.WcabseSQh2BOGdp0_x6eltLYiVZeTSCbK1h_Kcxqhs4) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Tutorial · Topics: Core Data · Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using UIKit Components in SwiftUI (Coordinators)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9V29KdHJsREJseVkiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.61EuLk6HarMsg30D45ewI7xYWDhIoZOmzg6CjyKYvDE) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [AutomaticSettings](https://github.com/krzysztofzablocki/AutomaticSettings) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Examines AutomaticSettings, focusing on this new library from krzysztof zabłocki is interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [Yes, it’s the full thing. I’m sorry](https://github.com/felixrieseberg/macintosh.js) — iOS Dev Weekly · Issue 488 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `1st January 2021`
  **NeKI brief:** Examines Yes, it’s the full thing. I’m sorry, focusing on how do you record videos of your apple watch apps? you have the watch on your wrist, tap the screen with your other hand,…. Use it as a focused research reference for related Apple-platform work.
- [SwiftCamera: The source project for the SwiftCamera tutorial](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vcm9yb2RyaWd1ZXoxMTYvU3dpZnRDYW1lcmE_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjN2YyODU5OC04ODgxLTRiOTQtYTM0MC00MDkyYTA5NzI4NDAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNmQzODZmMTYtMDc2Zi00YjNkLWE4OWQtNTFmZWUwMDQ2NmM2IiwiaWF0IjoxNjc0MDYyNzM2LjgxNiwiaXNzIjoib3JjaGlkIn0.NmimYkKoustjVoU5_ZFzajEkdlaWS9ctJUv9ZJ8dgmI) — SwiftUI Weekly · SwiftUI Weekly - Issue #33 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2020-10-27T16:57:07.000Z`
  **NeKI brief:** Provides source for a SwiftCamera tutorial project. Use it to inspect camera-session setup, preview integration, and capture flow as a concrete UIKit or SwiftUI interoperability reference.
- [Parma](https://github.com/dasautoooo/Parma) — iOS Dev Weekly · Issue 470 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `21st August 2020`
  **NeKI brief:** Examines Parma, focusing on markdown rendering engine, using swiftui views? that sounds interesting! that’s what leonard chan has created here. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [What’s New in Unit Testing?](https://qualitycoding.org/wwdc20-unit-testing) — iOS Dev Weekly · Issue 464 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `10th July 2020`
  **NeKI brief:** Reviews the unit-testing changes presented at WWDC 2020 and connects them to practical Xcode test workflows. Follow it when maintaining older XCTest infrastructure and checking which release-era features can simplify test organization or diagnostics.
- [SwiftUI Grids](https://nsscreencast.com/episodes/445-swiftui-grids) — iOS Dev Weekly · Issue 462 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines SwiftUI Grids, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Building a view debugger using SceneKit](https://www.youtube.com/watch?v=S6YN2Bsde_Q) — iOS Dev Weekly · Issue 459 — Video · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2020`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Techniques for Testing](https://www.youtube.com/watch?v=Or6xjaCUCd4) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games · Swift · Testing
  **Published:** `5th June 2020`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Integrating SwiftUI & UIKit](https://www.youtube.com/watch?v=ssz02HMEoR0) — iOS Dev Weekly · Issue 459 — Video · Topics: Swift · SwiftUI · UIKit
  **Published:** `5th June 2020`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [this walkthrough video](https://www.pointfree.co/episodes/ep100-a-tour-of-the-composable-architecture-part-1) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** A free tour of the newly open-sourced Composable Architecture that builds an application while introducing its state-management model. Useful for assessing the framework from a concrete implementation rather than only its API surface or architectural claims.
- [Exploring SwiftUI Apple Watch Performance](https://david-smith.org/blog/2020/01/07/exploring-swiftui-apple-watch-performance) — iOS Dev Weekly · Issue 438 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `10th January 2020`
  **NeKI brief:** Examines Exploring SwiftUI Apple Watch Performance, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Saliency Analysis with the Vision framework](https://www.raywenderlich.com/5807038-saliency-analysis-in-ios-using-vision) — iOS Dev Weekly · Issue 433 — Article · Topics: Graphics, Media & Games
  **Published:** `6th December 2019`
  **NeKI brief:** Covers Saliency Analysis with the Vision framework, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [SwiftUI by Example](https://www.hackingwithswift.com/quick-start/swiftui) — iOS Dev Weekly · Issue 422 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `20th September 2019`
  **NeKI brief:** Covers SwiftUI by Example, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [new set of 14 videos](https://www.youtube.com/playlist?list=PLuoeXyslFTubw4NtepDCis5tTqK37zT3Q) — iOS Dev Weekly · Issue 422 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `20th September 2019`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Learn how to create custom UIs and animations in SwiftUI](https://designcode.io/swiftui?promo=learnswiftui) — iOS Dev Weekly · Issue 417 — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `16th August 2019`
  **NeKI brief:** Examines Learn how to create custom UIs and animations in SwiftUI, focusing on 6-hour video course teaching design, coding custom user interfaces and animated interactions for ios 13. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Hacking with Swift Live](https://www.hackingwithswift.com/live) — iOS Dev Weekly · Issue 413 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `19th July 2019`
  **NeKI brief:** Covers Hacking with Swift Live, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [RetroRampage](https://github.com/nicklockwood/RetroRampage) — iOS Dev Weekly · Issue 411 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `5th July 2019`
  **NeKI brief:** Examines RetroRampage, focusing on finally with a welcome break from swiftui hot takes is this tutorial series from nick lockwood on how to implement a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Videos from ServerSide.swift](https://www.serversideswift.info/videos) — iOS Dev Weekly · Issue 394 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Covers Videos from ServerSide.swift, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Xcode in 20 Seconds](https://www.youtube.com/playlist?list=PLuoeXyslFTuYQ9Hoh42Bw8sPYMlTOV0V7) — iOS Dev Weekly · Issue 389 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `1st February 2019`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Designing a Modern Swift Network Stack](http://mikezornek.com/posts/2019/1/designing-a-modern-swift-network-stack-video-and-slides) — iOS Dev Weekly · Issue 387 — Article · Topics: Graphics, Media & Games · Networking · Swift
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Designing a Modern Swift Network Stack, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Picking and Hit-Testing in Metal](http://metalbyexample.com/picking-hit-testing) — iOS Dev Weekly · Issue 377 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `9th November 2018`
  **NeKI brief:** Examines Picking and Hit-Testing in Metal, offering practical guidance on test design and automation strategy. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Instabug](https://try.instabug.com/product/ios) — iOS Dev Weekly · Issue 376 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `2nd November 2018`
  **NeKI brief:** Examines Receive Detailed Feedback and Debug your iOS App 10x Faster, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [The Aqua Screenshot Library](https://512pixels.net/projects/aqua-screenshot-library) — iOS Dev Weekly · Issue 366 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `24th August 2018`
  **NeKI brief:** A browsable reference library of Mac screenshots spanning Aqua, pinstripes, brushed metal, linen, translucency, and vibrancy. It is useful for visual-history research and design comparison.
- [Metal Programming Guide: Tutorial and Reference via Swift](https://www.amazon.com/dp/0134668944) — iOS Dev Weekly · Issue 333 — Tutorial · Topics: Graphics, Media & Games · Swift
  **Published:** `5th January 2018`
  **NeKI brief:** Examines Metal Programming Guide: Tutorial and Reference via Swift, focusing on janie clayton’s long-awaited book on metal programming is now available for pre-order! with topics ranging from the most…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Ease](https://github.com/roberthein/Ease) — iOS Dev Weekly · Issue 331 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `15th December 2017`
  **NeKI brief:** Examines Ease, focusing on robert-hein hooijmans just released this animation framework which makes adding spring animations a breeze. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AudioKit 4](https://github.com/AudioKit/AudioKit/releases/tag/v4.0) — iOS Dev Weekly · Issue 319 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd September 2017`
  **NeKI brief:** Examines AudioKit 4, focusing on the author’s discussion of don’t think we’ve ever actually directly linked to audiokit before (although there was a video about it in issue 241)…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AudioKit](https://github.com/AudioKit/AudioKit) — iOS Dev Weekly · Issue 319 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd September 2017`
  **NeKI brief:** Provides the public source repository for AudioKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Managing Temporary Files in Swift](https://medium.com/@victor.pavlychko/managing-temporary-files-in-swift-b076e1444c76) — iOS Dev Weekly · Issue 313 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `11th August 2017`
  **NeKI brief:** Examines Managing Temporary Files in Swift, focusing on temporary files are a pain to deal with, and if you don’t take care of them correctly you can end up with gigabytes of…. Use it as a focused research reference for related Apple-platform work, and verify.
- [Embed in-app support with the Zendesk kit on Fabric](https://www.fabric.io/kits/ios/zendesk) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Embed in-app support with the Zendesk kit on Fabric in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Using SpriteKit to create animations in Swift](https://www.swiftbysundell.com/posts/using-spritekit-to-create-animations-in-swift) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Using SpriteKit to create animations in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Dealing With Asynchrony in a Synchronous Swift World](https://news.realm.io/news/greg-heo-dealing-asynchrous-synchronous-swift-swift-language-user-group-2017) — iOS Dev Weekly · Issue 308 — Article · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `7th July 2017`
  **NeKI brief:** Explores Dealing With Asynchrony in a Synchronous Swift World in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swift panel discussion](https://news.realm.io/news/wwdc-2017-swift-panel) — iOS Dev Weekly · Issue 306 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `23rd June 2017`
  **NeKI brief:** Explores panel discussion in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Machine Learning for everyone](http://machinethink.net/blog/ios-11-machine-learning-for-everyone) — iOS Dev Weekly · Issue 305 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `16th June 2017`
  **NeKI brief:** Explores Machine Learning for everyone in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Writing your UI Swiftly](https://news.realm.io/news/sommer-panage-writing-your-ui-swiftly) — iOS Dev Weekly · Issue 298 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `28th April 2017`
  **NeKI brief:** Explores Writing your UI Swiftly in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Free video: Natural Swift](https://gumroad.com/l/natural-swift) — iOS Dev Weekly · Issue 286 — Article · Topics: Functional Programming · Graphics, Media & Games · Swift
  **Published:** `3rd February 2017`
  **NeKI brief:** Examines Free video: Natural Swift, focusing on what makes “swifty” swift? paul hudson from hacking with swift has produced a free video that teaches you how to use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Zendesk: save $177 with coupon “DEV280”](https://www.zendesk.com/in-app-customer-service) — iOS Dev Weekly · Issue 280 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `9th December 2016`
  **NeKI brief:** Profiles Zendesk’s in-app customer-support tooling for embedding help and issue reporting inside an iOS product. Evaluate SDK integration, privacy and data handling, operational ownership, and user-experience trade-offs before adopting a vendor support channel.
- [Real World Swift Performance](https://realm.io/news/real-world-swift-performance) — iOS Dev Weekly · Issue 273 — Article · Topics: Graphics, Media & Games · Performance · Swift
  **Published:** `21st October 2016`
  **NeKI brief:** Explores Real World Swift Performance in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [video recorded recently](https://realm.io/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed) — iOS Dev Weekly · Issue 272 — Article · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Examines video recorded recently, focusing on iglistkit is a new open source library focused on splitting up your massive collection view controllers, and also being…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Say It Ain’t So: Implementing Speech Recognition in Your App](https://realm.io/news/tryswift-marc-brown-say-it-aint-so-implementing-speech-recognition) — iOS Dev Weekly · Issue 270 — Article · Topics: App Intents & System Surfaces · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `30th September 2016`
  **NeKI brief:** Explores Say It Ain’t So: Implementing Speech Recognition in Your App in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines) — iOS Dev Weekly · Issue 266 — Article · Topics: Apple Platform Ecosystem · Code Quality · Swift
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Amazing Physically Based Rendering Using the New iOS 10 SceneKit](https://medium.com/@avihay/amazing-physically-based-rendering-using-the-new-ios-10-scenekit-2489e43f7021) — iOS Dev Weekly · Issue 262 — Article · Topics: Graphics, Media & Games
  **Published:** `5th August 2016`
  **NeKI brief:** Examines Amazing Physically Based Rendering Using the New iOS 10 SceneKit, focusing on not being involved with anything which has needed scenekit, i wasn’t aware of exactly what it was capable of these days. Use it as a focused research reference for related Apple-platform work.
- [Interactive Messages in iOS 10](https://medium.com/@prianka.kariat/interactive-messages-in-ios-10-4cea542fbd9a) — iOS Dev Weekly · Issue 262 — Article · Topics: Graphics, Media & Games
  **Published:** `5th August 2016`
  **NeKI brief:** Examines Interactive Messages in iOS 10, focusing on talking of imessage apps, prianka liz kariat gives us a walkthrough of creating a tic tac toe game inside messages. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Neural Networks in iOS 10 and macOS](https://www.bignerdranch.com/blog/neural-networks-in-ios-10-and-macos) — iOS Dev Weekly · Issue 257 — Article · Topics: Graphics, Media & Games · macOS & AppKit · Networking
  **Published:** `1st July 2016`
  **NeKI brief:** Explores Neural Networks in iOS 10 and macOS in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [ImageButter](https://github.com/dollarshaveclub/ImageButter) — iOS Dev Weekly · Issue 247 — Source repository · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `22nd April 2016`
  **NeKI brief:** Provides the ImageButter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Code Injection for Xcode](http://artsy.github.io/blog/2016/03/05/iOS-Code-Injection) — iOS Dev Weekly · Issue 241 — Article · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `11th March 2016`
  **NeKI brief:** Explains Code Injection for Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Injection for Xcode](https://github.com/johnno1962/injectionforxcode) — iOS Dev Weekly · Issue 241 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `11th March 2016`
  **NeKI brief:** Provides the Injection for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIDynamics, UIKit or OpenGL? 3 Types of iOS Animations for Star Wars](https://yalantis.com/blog/uidynamics-uikit-or-opengl-3-types-of-ios-animations-for-the-star-wars) — iOS Dev Weekly · Issue 221 — Article · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `23rd October 2015`
  **NeKI brief:** Explains UIDynamics UIKit or OpenGL 3 Types of iOS Animations for Star Wars with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is.
- [videos](https://www.youtube.com/watch?v=-IPMNWqA638) — iOS Dev Weekly · Issue 168 — Video · Topics: Concurrency · Graphics, Media & Games
  **Published:** `17th October 2014`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using Vector Images in Xcode 6](http://martiancraft.com/blog/2014/09/vector-images-xcode6) — iOS Dev Weekly · Issue 164 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `19th September 2014`
  **NeKI brief:** Use vector PDFs in Xcode asset handling to reduce manually exported device-size variants. Verify which asset types and OS versions preserve vector fidelity, since vector source input does not mean every runtime use remains resolution independent.
- [Getting Started with Metal in Swift](http://www.raywenderlich.com/77488/ios-8-metal-tutorial-swift-getting-started) — iOS Dev Weekly · Issue 163 — Tutorial · Topics: Graphics, Media & Games · Swift
  **Published:** `12th September 2014`
  **NeKI brief:** Explains Getting Started with Metal in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Coursera iOS Software Engineer - Mountain View, CA](https://www.coursera.org/about/careers/96aecab7-9cb9-424a-b95c-002842a792e8) — iOS Dev Weekly · Issue 156 — Tutorial · Topics: Architecture · Developer Career & Practice · Developer Community & Business
  **Published:** `25th July 2014`
  **NeKI brief:** Explains Coursera iOS Software Engineer Mountain View CA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [SkipCasts](https://www.youtube.com/user/SkipCasts/videos) — iOS Dev Weekly · Issue 155 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `18th July 2014`
  **NeKI brief:** Explains SkipCasts with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Mobile Designers who Code](http://www.meetup.com/Mobile-Designers-Code/events/186929152) — iOS Dev Weekly · Issue 152 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `27th June 2014`
  **NeKI brief:** Explains Mobile Designers who Code with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Building Paper](https://www.youtube.com/watch?v=OiY1cheLpmI&feature=youtu.be) — iOS Dev Weekly · Issue 143 — Video · Topics: Graphics, Media & Games · Performance
  **Published:** `25th April 2014`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [BRFlabbyTable](https://github.com/brocoo/BRFlabbyTable) — iOS Dev Weekly · Issue 140 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `4th April 2014`
  **NeKI brief:** Provides the BRFlabbyTable source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIImageView+FaceAwareFill](https://github.com/Julioacarrettoni/UIImageView_FaceAwareFill) — iOS Dev Weekly · Issue 129 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th January 2014`
  **NeKI brief:** Provides the UIImageView+FaceAwareFill source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Courses on Code School](https://www.codeschool.com/courses/core-ios-7) — iOS Dev Weekly · Issue 122 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `29th November 2013`
  **NeKI brief:** Explains iOS Courses on Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Unity Survival Game Tutorial](http://www.youtube.com/playlist?list=PLPV2KyIb3jR7F_B4p8X3YwHPaExh0R9Kk) — iOS Dev Weekly · Issue 121 — Video · Topics: Graphics, Media & Games
  **Published:** `22nd November 2013`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [MoarFonts](http://pitaya.ch/moarfonts) — iOS Dev Weekly · Issue 119 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `8th November 2013`
  **NeKI brief:** Explains MoarFonts with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [WWDC Sample Code Downloader](https://github.com/jfahrenkrug/WWDC-Downloader) — iOS Dev Weekly · Issue 100 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `28th June 2013`
  **NeKI brief:** Provides the WWDC Sample Code Downloader source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIRefreshControl Fun and Games](http://useyourloaf.com/blog/2013/06/18/uirefreshcontrol-fun-and-games.html) — iOS Dev Weekly · Issue 99 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st June 2013`
  **NeKI brief:** Explains UIRefreshControl Fun and Games with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why Apple Created Sprite Kit And What It Means For Cocos2D](http://www.learn-cocos2d.com/2013/06/apple-create-spritekit) — iOS Dev Weekly · Issue 98 — Article · Topics: Graphics, Media & Games
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Why Apple Created Sprite Kit And What It Means For Cocos2D with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [PHFComposeBarView](https://github.com/fphilipe/PHFComposeBarView) — iOS Dev Weekly · Issue 93 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `10th May 2013`
  **NeKI brief:** Provides the PHFComposeBarView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Trigonometry for Game Programming](http://www.raywenderlich.com/35866/trigonometry-for-game-programming-part-1) — iOS Dev Weekly · Issue 91 — Article · Topics: Graphics, Media & Games · UIKit
  **Published:** `26th April 2013`
  **NeKI brief:** Explains Trigonometry for Game Programming with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Xamarin Studio](http://blog.xamarin.com/announcing-xamarin-2.0) — iOS Dev Weekly · Issue 82 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `22nd February 2013`
  **NeKI brief:** Explains Xamarin Studio with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Vitamins](http://ashfurrow.com/blog/objective-c-vitamins) — iOS Dev Weekly · Issue 79 — Article · Topics: Accessibility · Objective-C & Cocoa · Testing
  **Published:** `1st February 2013`
  **NeKI brief:** Explains Objective-C Vitamins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [MSCachedAsyncViewDrawing](https://github.com/mindsnacks/MSCachedAsyncViewDrawing) — iOS Dev Weekly · Issue 68 — Source repository · Topics: Concurrency · Developer Tools · Graphics, Media & Games
  **Published:** `16th November 2012`
  **NeKI brief:** Provides the MSCachedAsyncViewDrawing source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SKBounceAnimation](https://github.com/khanlou/SKBounceAnimation) — iOS Dev Weekly · Issue 61 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `28th September 2012`
  **NeKI brief:** Provides the SKBounceAnimation source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Collision Detection Using the Separating Axis Theorem](http://gamedev.tutsplus.com/tutorials/implementation/collision-detection-with-the-separating-axis-theorem) — iOS Dev Weekly · Issue 54 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `10th August 2012`
  **NeKI brief:** Explains Collision Detection Using the Separating Axis Theorem with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [SCOtutor for ScreenFlow](http://www.screencastsonline.com/appstore) — iOS Dev Weekly · Issue 43 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `25th May 2012`
  **NeKI brief:** Explains SCOtutor for ScreenFlow with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [How to Market and Promote your Games and Apps: Part 1/4](http://www.raywenderlich.com/11359/how-to-market-and-promote-your-games-and-apps-part-1) — iOS Dev Weekly · Issue 36 — Article · Topics: Graphics, Media & Games
  **Published:** `6th April 2012`
  **NeKI brief:** Explains How to Market and Promote your Games and Apps Part 1/4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Apple clarifies its UDID position: no rejections yet for use, only for lack of user opt-in](http://www.pocketgamer.biz/r/PG%2EBiz/Apple+news/news.asp?c=39375) — iOS Dev Weekly · Issue 35 — Article · Topics: Graphics, Media & Games
  **Published:** `30th March 2012`
  **NeKI brief:** Explains Apple clarifies its UDID position no rejections yet for use only for lack of with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because.
- [SMShadowedLayer](https://github.com/Spaceman-Labs/ShadowedLayer/blob/master/fiatlux/SMShadowedLayer.m) — iOS Dev Weekly · Issue 34 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Product Design
  **Published:** `23rd March 2012`
  **NeKI brief:** Provides the SMShadowedLayer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Insurgent Games Makes All Games Free, Releases Everything as Open Source](http://www.insurgentgames.com/open-source) — iOS Dev Weekly · Issue 31 — Article · Topics: Graphics, Media & Games
  **Published:** `2nd March 2012`
  **NeKI brief:** Explains Insurgent Games Makes All Games Free Releases Everything as Open Source with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [GPUImage](https://github.com/BradLarson/GPUImage) — iOS Dev Weekly · Issue 29 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th February 2012`
  **NeKI brief:** Provides the GPUImage source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FTCoreText](https://github.com/FuerteInternational/FTCoreText) — iOS Dev Weekly · Issue 27 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd February 2012`
  **NeKI brief:** Provides the FTCoreText source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Beginning Core Image in iOS 5](http://www.raywenderlich.com/5689/beginning-core-image-in-ios-5) — iOS Dev Weekly · Issue 16 — Article · Topics: Graphics, Media & Games
  **Published:** `18th November 2011`
  **NeKI brief:** Explains Beginning Core Image in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS 5 Tech Talk: Allan Schaffer on OpenGL ES with GLKit](http://oleb.net/blog/2011/11/ios5-tech-talk-allan-schaffer-opengl-es-glkit) — iOS Dev Weekly · Issue 15 — Article · Topics: Graphics, Media & Games
  **Published:** `11th November 2011`
  **NeKI brief:** Explains iOS 5 Tech Talk Allan Schaffer on OpenGL ES with GLKit with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Creating an iTunes store style “jump” animation](http://stackoverflow.com/questions/6915702/creating-itunes-store-style-jump-animation) — iOS Dev Weekly · Issue 11 — Article · Topics: Graphics, Media & Games
  **Published:** `14th October 2011`
  **NeKI brief:** Explains Creating an iTunes store style jump animation with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Play](https://youtube.com/watch?v=Y_Ov-ddMb24) — Not only Swift · Issue 97 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Links to a public video about Play. Use the talk for practitioner context and demonstrations, then verify platform behavior, API availability, and recommended production practices in current primary documentation.
- [The SwiftUI Way](https://books.nilcoalescing.com/the-swiftui-way) — Not only Swift · Issue 97 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** The SwiftUI Way targets experienced developers with production patterns and anti-patterns informed by SwiftUI framework experience. Use it when evaluating a complex view architecture rather than looking up an isolated control API.
- [VecturaKit](https://github.com/rryam/VecturaKit) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Graphics, Media & Games
  **NeKI brief:** Provides the public source repository for VecturaKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Flexible rich text rendering in SwiftUI](https://github.com/gonzalezreal/textual) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers rich attributed-text rendering in SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers the maintenance status and migration path from Swift Markdown UI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Second Brain app](https://www.youtube.com/playlist?list=PLsnLd2esiGRTmfGZcZMnEy6hkBHXBH_en) — Not only Swift · Issue 85 — Video · Topics: Graphics, Media & Games · Liquid Glass · Swift
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [this repository](https://github.com/FirebaseExtended/firebase-video-samples/tree/main/firebase-ai-friendly-meals/apple) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **NeKI brief:** Contains the Apple client sample for Firebase AI Friendly Meals, showing practical integration boundaries around Firebase services and SwiftUI. Inspect it for a runnable reference, then check current SDK setup and security guidance.
- [Foundation Models Playgrounds: Comprehensive Examples for Apple's AI Framework](https://github.com/IvanCampos/Foundation-Models-Playgrounds) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers Foundation Models Framework examples for Apple-platform development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Olleh: Ollama-compatible CLI for Apple's Foundation Models](https://github.com/loopwork/olleh) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers an Ollama-compatible command-line interface for Apple Foundation Models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [write-up](https://wwdcnotes.com/documentation/wwdcnotes/wwdc21-10022-demystify-swiftui) — Not only Swift · Issue 76 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** This article covers the WWDC session Demystify SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [RenderMeThis: SwiftUI Debugging Tool](https://github.com/Aeastr/RenderMeThis) — Not only Swift · Issue 76 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers visualizing SwiftUI rendering, layouts, and measurements with Loupe. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
