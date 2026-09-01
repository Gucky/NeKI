# Graphics, Media & Games

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Rendering, GPU work, image/audio/video processing, computer vision, and game-development techniques.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **878**

## Direct-source reading

- [Keeping canvas interactions responsive with frame reprojection](https://nilcoalescing.com/blog/KeepingCanvasInteractionsResponsiveWithFrameReprojection) — Nil Coalescing · article catalogue
  **Published:** `2026-07-28`
  **NeKI brief:** Shows how Exsto keeps large Metal canvases responsive by reprojecting the last rendered frame while a newer offscreen frame is queued, then synchronising transform and texture updates with CAMetalLayer, CATransaction, overdraw, and gesture-time MSAA reduction.
- [Blend modes in SwiftUI](https://nilcoalescing.com/blog/BlendModesInSwiftUI) — Nil Coalescing · article catalogue
  **Published:** `2026-07-24`
  **NeKI brief:** Catalogues all 21 SwiftUI blend modes with focused visual examples and explains their colour or alpha calculations. The closing compositingGroup examples clarify how to constrain which sibling views participate in a blend operation.
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
- [Col.or: Discover a Universe of Colors Right in Your Pocket - iOS Dev Tools](https://iosdev.tools/blog/col-or) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-02-09T10:35:00+00:00`
  **NeKI brief:** Profiles Col.or as discover a Universe of Colors Right in Your Pocket. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [From Pixel Capture to Metadata - Reimagining Screen Recording Architecture on macOS](https://fatbobman.com/en/posts/screensage-from-pixel-to-meta) — Fatbobman · article catalogue
  **Published:** `2026-02-04T14:12:00.000Z`
  **NeKI brief:** Uses a macOS recorder to connect ScreenCaptureKit and Metal capture, bitrate control, crash recovery, multi-window behavior, and SwiftUI timeline performance. The engineering log helps separate recording architecture from product-facing metadata workflows.
- [Surviving tvOS - An Engineering Log of an Atypical Media Player](https://fatbobman.com/en/posts/surviving-tvos) — Fatbobman · article catalogue
  **Published:** `2026-01-14T14:12:00.000Z`
  **NeKI brief:** Documents a media player's tvOS-specific focus behavior, storage limits, SwiftUI workarounds, AVPlayer tuning, and synchronization strategy. It is useful for identifying platform constraints that an enlarged-iPad mental model misses.
- [Solving SwiftUI Pain Points and Performance Bottlenecks - Zipic Development Technical Retrospective](https://fatbobman.com/en/posts/zipic-3-technical-details) — Fatbobman · article catalogue
  **Published:** `2025-12-22T14:10:00.000Z`
  **NeKI brief:** Explains Zipic's SwiftUI adaptation, Core Graphics and PDF compression work, Raycast integration, and performance fixes. The retrospective connects low-level image processing with native macOS interaction and component constraints.
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
- [ScanTexter: Scan Text on Screen and Translate It at Once - iOS Dev Tools](https://iosdev.tools/blog/scantexter) — iOS Dev Tools Blog · article catalogue
  **Published:** `2024-02-03T21:43:46+00:00`
  **NeKI brief:** Profiles ScanTexter as scan Text on Screen and Translate It at Once. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
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
  **NeKI brief:** In the first two versions of watchOS, animations were limited to cycling through images like a flip book. Then, watchOS 3 added SpriteKit and SceneKit support allowing more complex, dynamic animations. Cory Bohon demonstrates how SpriteKit and the scene…

## Newsletter and related leads

- [JoltPhysics](https://github.com/EvgenijLutz/JoltPhysics) — iOS Dev Tools · iOS Dev Tools: JoltPhysics, asc-cli, Xtend — Source repository · Topics: Developer Tools · Graphics, Media & Games · Performance
  **Published:** `2026-08-27T20:30:45.555Z`
  **NeKI brief:** Provides a Swift-facing package around the Jolt C++ physics engine for real-time simulation. Assess native dependency, determinism, and supported-platform trade-offs before making it an app dependency.
- [Reely](https://getreely.co/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Produces app-launch and promotional video from a screenshot, screen recording, or prompt, avoiding a separate capture and editing session. Use it to evaluate agent-assisted marketing asset generation and its visual-review requirements.
- [Macshot](https://macshot.io/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: Graphics, Media & Games
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Open-source macOS capture utility for annotated screenshots, recordings, scrolling capture, OCR, and uploads. It is useful for inspecting a native developer-facing capture workflow and its annotation feature set.
- [Adapting EPUB 3 Features to CoreText in Yuedu Reader](https://chang-jui-lin.github.io/Yuedu-reader/2026/06/08/coretext-epub3-adaptation) — Those Who Swift · Issue 280 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `2026-08-19T20:31:22.272Z`
  **NeKI brief:** Explains how the Yuedu Reader maps EPUB 3 features such as fixed layout, media overlays, HTML5 media, CSS floats, tables, and bidirectional text onto a native CoreText engine. The article is a concrete case study in preserving rich document semantics across a custom reader layout.
- [From XCUITest to Promo Video](https://l.fatbobman.com/w0149-04) — Fatbobman’s Swift Weekly · Issue 149 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-08-17T12:03:38.576Z`
  **NeKI brief:** Treats screenshots and promo videos as reproducible build artifacts: launch into exact SwiftUI state, drive capture with XCUITest, compose with Remotion, and bind inputs through manifests and hashes. It exposes where automation paid off.
- [Pocket Screen](https://labs.toybird.com/apps/pocket-screen) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: Graphics, Media & Games
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Turns one or two macOS windows into compact always-on-top reference views, with a shortcut to replace the selected view and controls for freezing or click-through behavior. It supports document, browser, chat, and dashboard workflows.
- [SwiftUI blend modes](https://nilcoalescing.com/blog/BlendModesInSwiftUI?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Catalogues all 21 SwiftUI blend modes with focused visual examples and explains their colour or alpha calculations. The closing compositingGroup examples clarify how to constrain which sibling views participate in a blend operation.
- [keeping a Metal canvas responsive with frame reprojection](https://nilcoalescing.com/blog/KeepingCanvasInteractionsResponsiveWithFrameReprojection?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Shows how Exsto keeps large Metal canvases responsive by reprojecting the last rendered frame while a newer offscreen frame is queued, then synchronising transform and texture updates with CAMetalLayer, CATransaction, overdraw, and gesture-time MSAA reduction.
- [The Map, Drawn Twice](https://l.fatbobman.com/w0147-01) — Fatbobman’s Swift Weekly · Issue 147 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-08-03T12:02:34.944Z`
  **NeKI brief:** Maps responsibilities across Core Graphics, Core Text, Core Image, Core Animation, and SwiftUI by rendering the same scenes through Apple APIs and a clean-room engine. The paired output makes framework boundaries and hidden behavior easier to compare.
- [Bridging Gemini Video with Foundation Models and CustomSegment](https://rudrank.com/exploring-foundation-models-bridging-gemini-video-with-customsegment) — Those Who Swift · Issue 277 — Article · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `2026-07-29T20:01:55.196Z`
  **NeKI brief:** Bridges unsupported video input through a custom Transcript segment and LanguageModelExecutor that delegates analysis to Gemini. The layered verification is useful when extending Foundation Models-style sessions beyond the on-device model’s native modalities.
- [Rendering SwiftUI Previews with Xcode's MCP Server](https://cuteios.dev/2026/07/14/previews-and-mcp) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Graphics, Media & Games · Xcode
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Builds a SwiftUI preview gallery by combining Xcode’s MCP server, project context, and generated preview metadata. The article maps the moving parts and current limitations, making it useful when evaluating agent-assisted preview tooling.
- [Peeku](https://apps.apple.com/app/peeku-presence-coach/id6773651327) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Article · Topics: Graphics, Media & Games
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** Peeku combines menu-bar break reminders with optional camera-based walk-away detection and screen-saver activation. Follow it for a concrete macOS utility design involving periodic prompts, presence sensing, and privacy-sensitive local processing.
- [conference talks](https://swiftology.io/videos) — iOS Dev Weekly · Issue 757 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `3rd July 2026`
  **NeKI brief:** The page lists Swiftology video recordings and conference talks, providing publicly readable session information.
- [iOS Simulator Camera: Test Camera Flows](https://www.rocketsim.app/blog/ios-simulator-camera) — SwiftLee Weekly · Issue 330 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** Documents iOS Simulator Camera: Test Camera Flows, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [_UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots?ref=createwithswift.com) — Create with Swift · Issue 113 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-27T18:12:28.000Z`
  **NeKI brief:** Artem dives deep on how the private UIKit _UIPortalView mirrors live view content without duplicating view hierarchies or taking snapshots, using it as a window into how UIKit, Core Animation, and Liquid Glass-style effects compose live UI at the rendering…
- [Lucide Swift](https://github.com/ajaxjiang96/lucide-swift) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** Lucide Swift provides Swift-compatible Lucide icon assets and rendering helpers. Follow its repository for concrete symbol integration and customization patterns, while checking licensing, generated assets, and supported UI frameworks.
- [UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots) — Those Who Swift · Issue 272 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-24`
  **NeKI brief:** Artem dives deep on how the private UIKit _UIPortalView mirrors live view content without duplicating view hierarchies or taking snapshots, using it as a window into how UIKit, Core Animation, and Liquid Glass-style effects compose live UI at the rendering…
- [OpenCore Legacy Patcher](https://dortania.github.io/OpenCore-Legacy-Patcher) — iOS Dev Weekly · Issue 755 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `19th June 2026`
  **NeKI brief:** Examines Experience macOS just like before. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC26: Xcode Tips and Tricks Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-xcode-tips-and-tricks-group) — iOS Dev Weekly · Issue 755 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Xcode
  **Published:** `19th June 2026`
  **NeKI brief:** Explains WWDC26: Xcode Tips and Tricks Group Lab - Q&A, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [RTSP Live Streaming on iOS with AWS](https://github.com/hariharanjagan/RTSP-Streaming-iOS-AWS/blob/main/index.md) — iOS Dev Weekly · Issue 755 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `19th June 2026`
  **NeKI brief:** Streaming live video via RTSP on iOS has always been a bit of a challenge since AVPlayer does not support it out of the box. Hariharan Jagan has put together a comprehensive guide exploring how to bridge this gap using AWS infrastructure. The project walks…
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
- [Apple Music playlist](https://music.apple.com/ru/playlist/wwdc26-hello/pl.c2b332d45b194756aeb66a44329a2a08?l=en-GB) — Those Who Swift · Issue 269 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games
  **Published:** `2026-06-04`
  **NeKI brief:** Links an Apple Music playlist. Useful only as media navigation, not as a knowledge-index reading source.
- [Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel](https://www.youtube.com/watch?v=KlCqHP32c8M) — Those Who Swift · Issue 269 — Video · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2026-06-04`
  **NeKI brief:** Reviews Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — SwiftLee Weekly · Issue 326 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `2026-06-02T14:07:19.000Z`
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0532`Optional` noncopyable improvements and generalizations](https://github.com/apple/swift-evolution/blob/main/proposals/0532-optional-noncopyable-improvements.md) — SwiftLee Weekly · Issue 326 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-06-02T14:07:19.000Z`
  **NeKI brief:** Records AcceptedSE-0532`Optional` noncopyable improvements and generalizations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AppleInsider](https://appleinsider.com/articles/26/05/18/apple-design-awards-2026-finalists-include-cyberpunk-2077-civilization-vii?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines AppleInsider in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [TUAW](https://www.tuaw.com/2026/05/19/apple-design-awards-2026-finalists-revealed?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines TUAW in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [From WebView to CoreText: Building a Native EPUB Reader for iOS](https://chang-jui-lin.github.io/Yuedu-reader/2026/05/20/from-webview-to-coretext?ref=createwithswift.com) — Create with Swift · Issue 108 — Article · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-05-22T16:00:37.000Z`
  **NeKI brief:** Chang-Jui shares the journey behind Yuedu Reader, an open source EPUB reader for iOS, and why supporting CJK vertical writing made a custom CoreText rendering engine unavoidable.
- [The Aesthetics of Code with Andyy Hope](https://www.youtube.com/watch?v=QW4LytX2rNo&t=1s) — iOS Dev Weekly · Issue 751 — Video · Topics: Graphics, Media & Games
  **Published:** `22nd May 2026`
  **NeKI brief:** The video discusses the aesthetics of code with Andyy Hope and provides publicly readable talk metadata.
- [Livable](https://github.com/whatsinlab/livable) — iOS Dev Tools · iOS Dev Tools: MacPane, Livable, Sherlock — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-05-21T16:30:30.985Z`
  **NeKI brief:** Livable is a Swift or Apple-platform project with a focused developer workflow. Follow its README and source to identify the concrete API and problem it solves, then verify maintenance and platform assumptions.
- [Slideshot](https://slideshot.ai/) — iOS Dev Tools · iOS Dev Tools: MacPane, Livable, Sherlock — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2026-05-21T16:30:30.985Z`
  **NeKI brief:** Slideshot AI generates or assists with presentation slides. Follow it for concrete content-to-slide workflows, while checking export formats, data handling, and limitations before use.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Artem walks through iOS performance as a layered system covering metrics, architecture, UI rendering, networking, caching, memory, and CPU behavior.
- [try! Swift Tokyo 2026](https://www.youtube.com/playlist?list=PLCl5NM4qD3u-57q9cEMJmG8LwHSkcJmRM) — iOS Dev Weekly · Issue 750 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `8th May 2026`
  **NeKI brief:** Collects the try! Swift Tokyo 2026 recordings in one public playlist. Useful for discovering related talks as a group; assess each individual recording separately before relying on its technical claims or current API advice.
- [Yep](https://youtu.be/0OcOFBe0jbQ) — iOS Dev Weekly · Issue 750 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `8th May 2026`
  **NeKI brief:** Provides the linked technical presentation recording, whose surrounding issue uses it as a concise reaction or demonstration. Useful for following the original speaker context when the accompanying newsletter excerpt is too brief to stand alone.
- [Hokusai](https://github.com/ivantokar/hokusai) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Source repository · Topics: Developer Tools · Graphics, Media & Games · Performance
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** Hokusai is a Swift or Apple-platform developer library. Follow its README and source to inspect the concrete API and workflow it provides, then verify platform, dependency, and maintenance assumptions.
- [Tella](https://www.tella.com/) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Article · Topics: Graphics, Media & Games
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** Tella records and shares screen-based videos for asynchronous communication. Follow it for concrete capture, editing, and technical-demo workflows, while checking permissions, storage, and sharing controls.
- [KadrUI](https://github.com/SteliyanH/kadr-ui) — Fatbobman’s Swift Weekly · Issue 134 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-05-04T12:03:54.604Z`
  **NeKI brief:** KadrUI supplies SwiftUI editing components such as multi-track timelines, inspectors, overlays, and keyframe editing. Use it when a video or motion-editing product needs a structured editor surface rather than isolated custom controls.
- [SimCam](https://simcam.swmansion.com/) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** SimCam provides camera simulation or testing capabilities for Apple-platform development. Follow it for concrete input and device-testing workflows, while checking supported simulators, APIs, and project integration.
- [IndustrialKit](https://forums.swift.org/t/industrialkit-a-swift-framework-for-design-and-control-of-robotic-means-of-production/86168) — iOS Dev Weekly · Issue 749 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `1st May 2026`
  **NeKI brief:** The page covers “IndustrialKit” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Microsoft Accidentally Told The Truth About AI](https://www.youtube.com/watch?v=4CIlTOnc6I8) — Those Who Swift · Issue 264 — Video · Topics: AI Development · Graphics, Media & Games
  **Published:** `2026-04-29`
  **NeKI brief:** Reviews Microsoft Accidentally Told The Truth About AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [GPT Image 2 Prompts](https://youmind.com/gpt-image-2-prompts) — Those Who Swift · Issue 264 — Article · Topics: Graphics, Media & Games
  **Published:** `2026-04-29`
  **NeKI brief:** Presents GPT Image 2 prompt guidance. Useful for understanding image-generation controls and prompt structure when evaluating AI-assisted visual workflows.
- [Watch here.](https://www.youtube.com/@trySwiftConference/videos) — Those Who Swift · Issue 263 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2026-04-22`
  **NeKI brief:** Reviews Watch here.. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift](https://www.swift.org/blog/expanding-swift-ide-support?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines Swift in the context of AI Development and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Harold Serrano](https://www.haroldserrano.com/blog?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines Harold Serrano in the context of Graphics, Media & Games and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swish: Clojure-Like Lisp For Swift Video Series](https://www.youtube.com/playlist?list=PLgZNfD3JAd4_2JeJQaFaOwuXV3Z5OX-SB) — Those Who Swift · Issue 262 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `2026-04-15`
  **NeKI brief:** Reviews Swish: Clojure-Like Lisp For Swift Video Series. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Introducing Untold Engine](https://forums.swift.org/t/introducing-untold-engine-a-3d-renderer-written-in-swift-using-metal/85702) — iOS Dev Weekly · Issue 747 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** It’s not every day you get to talk about a new game engine written in Swift, but today is one of those days! Harold Serrano made an announcement his new Metal-based game engine this week, and with a focus on XR scenes and with visionOS support already…
- [iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More](https://www.youtube.com/watch?v=VU-NiioUpxg&t=237s) — Those Who Swift · Issue 260 — Video · Topics: AI Development · App Distribution & Store Operations · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Reviews iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift 6.3 ReleasedSwift is designed to be the language you reach for at every layer of the software stack. Whether you’re building embedded firmware, internet-scale services, or full-featured mobile apps, Swift delivers strong safety guarantees, performance control when you need it, and expressive language features and APIs.Swift.orgApple Inc.](https://www.swift.org/blog/swift-6.3-released?ref=ioscodereview.com) — iOS Code Review · Issue 76 — Article · Topics: Graphics, Media & Games · Swift · Testing
  **Published:** `2026-03-30T18:21:46.000Z`
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [MacRumors](https://www.macrumors.com/2026/03/26/apple-swift-student-challenge-winners-2026?ref=ioscodereview.com) — iOS Code Review · Issue 76 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2026-03-30T18:21:46.000Z`
  **NeKI brief:** Examines MacRumors in the context of App Distribution & Store Operations and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [SwiftUI Live Broadcasting With AWS IVS](https://medium.com/@itsuki.enjoy/swiftui-live-broadcasting-with-aws-ivs-bcd461764e2b) — Those Who Swift · Issue 259 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-26`
  **NeKI brief:** Examines SwiftUI Live Broadcasting With AWS IVS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Under The Hood: What’s Really Happening When You Update View](https://www.youtube.com/watch?v=_zmQnn7Ki1E&t=28s) — Those Who Swift · Issue 258 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Reviews SwiftUI Under The Hood: What’s Really Happening When You Update View. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Those Who Swift · Issue 258 — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Turns a large SwiftUI list into a searchable, dynamically sortable browser, then adds a Contacts-style section index and draggable scrubber. Useful for coordinating section identifiers with programmatic scrolling and live drag feedback.
- [SGConf iOS Videos Are Now Available](https://www.youtube.com/@iOSConfSG/videos) — Those Who Swift · Issue 258 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `2026-03-18`
  **NeKI brief:** Reviews SGConf iOS Videos Are Now Available. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Learning to develop more accessible iOS games](https://accessibilityupto11.com/post/2026-02-22-01) — SwiftLee Weekly · Issue 315 — Article · Topics: Accessibility · Graphics, Media & Games
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Daniel shares lessons from making his new game, RetroRapid!, more accessible, focusing on multiple control options, alternative feedback, and customizable settings to make gameplay inclusive.
- [SwiftUI transitions with distortion effect and Metal Shaders](https://nerdyak.tech/development/2023/06/16/distortionEffect-with-Metal-shaders-for-better-transitions.html) — SwiftLee Weekly · Issue 315 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Explains SwiftUI transitions with distortion effect and Metal Shaders, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Speed Hacks for iOS Builds](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Those Who Swift · Issue 257 — Article · Topics: Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Those Who Swift · Issue 257 — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Builds a project-root CLAUDE.md for Swift, SwiftUI, and Xcode agents, covering architecture, build, test, and style instructions plus nested or shared configurations. Useful for comparing repository guidance loaded automatically by coding agents.
- [Building a Reusable Network Manager in Swift](https://www.youtube.com/watch?v=zEzIxdA8zLQ) — Those Who Swift · Issue 256 — Video · Topics: Concurrency · Networking · Swift
  **Published:** `2026-03-06`
  **NeKI brief:** Refactors view-specific URLSession code into a generic async NetworkManager with HTTP validation, typed failures, dictionary and array decoding, and caller-configured date strategies. Useful for keeping decoding flexibility outside the shared transport layer.
- [Swift Concurrency from Zero to Hero](https://swiftology.io/articles/swift-concurrency-zero-to-hero) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Concurrency · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Explores Swift Concurrency from Zero to Hero with concrete Swift concurrency examples. Follow it to reason about isolation, cancellation, and Sendable boundaries, then verify availability and diagnostics against current Swift documentation.
- [Let’s end open source together with this one simple trick](https://fosdem.org/2026/schedule/event/SUVS7G-lets_end_open_source_together_with_this_one_simple_trick) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Examines FOSDEM 2026 - Let's end open source together with this one simple trick. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift talks at this year’s FOSDEM](https://fosdem.org/2026/schedule/events) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Yes, there were Swift talks at this year’s FOSDEM, but this one by Dylan Ayrey and Mike Nolan was the one that caught my eye. They ask the question of whether open source is doomed in the age of LLMs, and it’s really a fantastic talk.
- [Swift Pre-FOSDEM Community Event 2026](https://www.youtube.com/playlist?list=PLeb93j_rsErO182fdoJ4m1p_suKAOcBnM) — iOS Dev Weekly · Issue 743 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Examines The Swift open source community will be participating in this year's FOSDEM in the form of a community event the day before the conference, along with talks. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How Apple Hooks Fifty Thousand Methods](https://www.youtube.com/watch?v=SuQGQ1vh9k0&t=1s) — Those Who Swift · Issue 252 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2026-02-04`
  **NeKI brief:** Reviews How Apple Hooks Fifty Thousand Methods. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [How Apple Hooks Entire Frameworks](https://bryce.co/swizzle-everything) — SwiftLee Weekly · Issue 309 — Article · Topics: Graphics, Media & Games
  **Published:** `2026-02-03T15:08:20.000Z`
  **NeKI brief:** This investigation reverse-engineers framework-wide method swizzling and the trade-offs that appear when scaling from thousands to millions of methods. It connects Main Thread Checker-style instrumentation to binary-size limits and a practical library implementation.
- [Solving the View Model Problem (Part 1)](https://talk.objc.io/episodes/S01E476-solving-the-view-model-problem-part-1) — Those Who Swift · Issue 251 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-01-28`
  **NeKI brief:** Examines the view-model problem in SwiftUI. Useful for reviewing state ownership and deciding when a view model clarifies behavior versus adding an unnecessary indirection layer.
- [NSSpain 2025 Videos](https://www.youtube.com/playlist?list=PLztE34GS_piKKQ6y1dkkuhW76jLBHm3NV) — iOS Dev Weekly · Issue 740 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `23rd January 2026`
  **NeKI brief:** I had missed that NSSpain had finished releasing videos from last year’s conference. As always, they had a great line-up of speakers, and you’re sure to find at least a few talks here that will interest you.
- [Why Do iOS Timers Stop When You Scroll?](https://www.youtube.com/watch?v=Uso8T5xBidk) — Those Who Swift · Issue 250 — Video · Topics: Graphics, Media & Games
  **Published:** `2026-01-21`
  **NeKI brief:** Reviews Why Do iOS Timers Stop When You Scroll?. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Mastering Switch Statements in Swift](https://www.youtube.com/watch?v=84HoS9W2tpw) — Those Who Swift · Issue 250 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-01-21`
  **NeKI brief:** Reviews Mastering Switch Statements in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [WWDC Index](https://nonstrict.eu/wwdcindex) — iOS Dev Weekly · Issue 739 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** This technical resource covers a searchable index of WWDC material. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Detecting Text in Images With the Vision Framework](https://danielsaidi.com/blog/2026/01/10/detecting-text-in-images-with-the-vision-framework) — Those Who Swift · Issue 249 — Article · Topics: Graphics, Media & Games
  **Published:** `2026-01-14`
  **NeKI brief:** Uses Vision to detect text in images. Useful for mapping image preprocessing, recognition requests, and result handling into a testable pipeline rather than treating OCR as a single opaque call.
- [Rendering Markdown in SwiftUI](https://artemnovichkov.com/blog/rendering-markdown-in-swiftui) — Those Who Swift · Issue 249 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-01-14`
  **NeKI brief:** Artem shows how to display Markdown content in SwiftUI using Apple’s Markdown support from basic rich text formatting to handling links, lists, and custom styles.
- [Agent Skills explained: Replacing AGENTS.md with reusable AI knowledge](https://www.youtube.com/watch?v=khekVi1PK3o) — SwiftLee Weekly · Issue 306 — Video · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Explains how coding-agent skills differ from repository instructions, how they are discovered, installed, and updated, then applies a Swift concurrency skill to a real app refactor. Useful for assessing reusable agent workflows.
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — SwiftLee Weekly · Issue 306 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Documents building and launching an open-source app toward $10K monthly recurring revenue, including releases, App Store review, crashes, growth, pricing, and technical decisions. Useful for connecting product milestones with implementation trade-offs.
- [VideoKit](https://github.com/danielsaidi/VideoKit) — iOS Dev Tools · iOS Dev Tools: VideoKit, MacsyZones, SwiftUI Routes — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2025-12-18T17:31:09.014Z`
  **NeKI brief:** VideoKit provides video playback, capture, or processing abstractions for Apple platforms. Follow its source for concrete AVFoundation integration and media workflows, while verifying codec, concurrency, and platform requirements.
- [Smarter Lists, Labels, and Dictionary Grouping in SwiftUI](https://www.youtube.com/watch?v=PBMqJgtznn4) — Those Who Swift · Issue 245 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Reviews Smarter Lists, Labels, and Dictionary Grouping in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift Protocols as Existential Types vs. Generic Constraints](https://www.youtube.com/watch?v=-e8Ey6oTI24&t=320s) — Those Who Swift · Issue 245 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2025-12-17`
  **NeKI brief:** Reviews Swift Protocols as Existential Types vs. Generic Constraints. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Finishing the Rich Notes App in SwiftUI](https://www.youtube.com/watch?v=UUvgm9-yltE) — Those Who Swift · Issue 244 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-12-11`
  **NeKI brief:** Reviews Finishing the Rich Notes App in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [MarkdownView](https://github.com/LiYanan2004/MarkdownView) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** MarkdownView renders richer Markdown in SwiftUI, including mixed text and image layouts, selectable content, and interaction hooks. Use it when AttributedString's built-in Markdown support is too limited for a document-reading surface.
- [RichText](https://github.com/LiYanan2004/RichText) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** RichText supplies interactive, styled rich-text components for SwiftUI beyond ordinary Text rendering. Use it when links, mixed media, selection, or fine-grained text actions need an explicit view-layer solution.
- [demo video](https://youtu.be/nWr6eZKM6no) — iOS Dev Weekly · Issue 736 — Video · Topics: AI Development · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st November 2025`
  **NeKI brief:** Yes, it’s about a Flutter package, GenUI, but it was the idea that caught my attention. It takes the idea of using LLMs inside an app one step further than having the model return text or structured data. Instead, it returns UI widgets that also contain the…
- [Videos from ServerSide.swift 2025](https://www.youtube.com/playlist?list=PLTFt3GGfH3hl2rTYswjVXCaNvXmafQ3bt) — iOS Dev Weekly · Issue 736 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `21st November 2025`
  **NeKI brief:** Examines Videos from ServerSide.swift 1st-3rd October 2025. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [TinyFast](https://tinyfast.app/) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI 2.0, SettingsKit, SwiftCache — Article · Topics: Graphics, Media & Games
  **Published:** `2025-11-20T16:50:33.113Z`
  **NeKI brief:** TinyFast is a macOS utility or developer product page. Follow it for the concrete workflow described there, while requiring current documentation before relying on its technical behavior.
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://youtu.be/y_Qc8cT-O_g?si=W2ExWkL4BbMjT8cH) — SwiftLee Weekly · Issue 298 — Video · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-18T19:03:17.000Z`
  **NeKI brief:** Explains Swift 6.2 approachable concurrency through default actor isolation, nonisolated async behavior, isolated conformances, and upcoming features, then applies the migration concepts to RocketSim. Useful for planning incremental concurrency adoption.
- [Videos from #Pragma Conference 2025](https://www.youtube.com/playlist?list=PLAVm70iJlMuvTihK1OzK9S4Vzw_KO71b0) — iOS Dev Weekly · Issue 735 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `14th November 2025`
  **NeKI brief:** Here’s another wonderful set of conference videos, this time from #Pragma Conference, which happened just a couple of weeks ago! You should watch them all, of course, but if you need to pick just one then make it Arkadiusz Świętnicki’s incredibly inspiring…
- [Joys and challenges of a sightless coder](https://youtu.be/Ry77etLCAfg) — iOS Dev Weekly · Issue 735 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `14th November 2025`
  **NeKI brief:** Examines How is it to code while blind? What are the challenges and some less obvious quirks one can face on this adventure? Close your eyes, and just listen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Proven with 3D printing](https://matthewcassinelli.com/apple-logos-actually-3d-renderings-app-icons) — iOS Dev Weekly · Issue 735 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `14th November 2025`
  **NeKI brief:** Did you know both the App Store and Shortcuts logos are actually made up of 3D icons? Proven with 3D printing. 🖨️
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Those Who Swift · Issue 240 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Builds an on-device travel chatbot from a Foundation Models LanguageModelSession transcript, rendering user and model messages with thinking, scrolling, availability, guardrail, and error states. Useful for connecting session history to SwiftUI presentation.
- [Swift Leeds Videos 2025](https://www.youtube.com/playlist?list=PL-wmxEeX64YTpDbpfszWMV76oZZO3wxZH) — iOS Dev Weekly · Issue 734 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Speaking of Swift Leeds, the organisers finished posting all the session videos from last month’s conference. There are plenty of talks and a panel discussion to pick from. However, given the previous link, it’s worth noting that Swift Leeds had four…
- [panel discussion](https://youtu.be/g_b_fzuKnw4) — iOS Dev Weekly · Issue 734 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Examines Enjoy as our panel of Swift engineers explore many topics including Liquid Glass, AI, and the future of iOS.Panellists (from left to right)- Hidde van der Pl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Kim Gyuri](https://youtu.be/d0UOoLcsI8g) — iOS Dev Weekly · Issue 734 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Speaking of Swift Leeds, the organisers finished posting all the session videos from last month’s conference. There are plenty of talks and a panel discussion to pick from. However, given the previous link, it’s worth noting that Swift Leeds had four…
- [Erin Sparling](https://youtu.be/M1DtFXDsS_4) — iOS Dev Weekly · Issue 734 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Speaking of Swift Leeds, the organisers finished posting all the session videos from last month’s conference. There are plenty of talks and a panel discussion to pick from. However, given the previous link, it’s worth noting that Swift Leeds had four…
- [Oksana Shcherban](https://youtu.be/vUe6uQae5PE) — iOS Dev Weekly · Issue 734 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `7th November 2025`
  **NeKI brief:** Speaking of Swift Leeds, the organisers finished posting all the session videos from last month’s conference. There are plenty of talks and a panel discussion to pick from. However, given the previous link, it’s worth noting that Swift Leeds had four…
- [Optimize Your App’s Speed & Efficiency: Q&A](https://antongubarenko.substack.com/p/optimize-your-apps-speed-and-efficiency) — Those Who Swift · Issue 239 — Article · Topics: Developer Career & Practice · Graphics, Media & Games · Performance
  **Published:** `2025-11-05`
  **NeKI brief:** Answers practical questions about improving app speed and efficiency. Useful for turning broad performance concerns into measurable work across launch, rendering, networking, and resource usage.
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — SwiftUI Weekly · SwiftUI Weekly - Issue #224 — Video · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `2025-11-03T11:19:35.224Z`
  **NeKI brief:** Summarizes a Meet with Apple performance session spanning power use, Foundation Models response latency, SwiftUI responsiveness, and Snap's diagnostic tools. Useful as a map of optimization areas before consulting the corresponding primary guidance.
- [Videos from Swift Connection 2025](https://www.youtube.com/playlist?list=PLZsRQnRG-mlIkHsjeax_cRq6kAclNrWBF) — iOS Dev Weekly · Issue 733 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Earlier this month, a group of people gathered in Paris to be educated and entertained at Swift Connection 2025. If you didn’t manage to make it to the conference, this set of videos from the event is the next best thing.
- [Foundation Models Framework in Swift Getting Started with On Device AI](https://www.youtube.com/watch?v=p17HrjVQKOQ) — Those Who Swift · Issue 238 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-10-29`
  **NeKI brief:** Reviews Foundation Models Framework in Swift Getting Started with On Device AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Build performance analysis for speeding up Xcode builds](https://youtu.be/9L1p0McuThM) — SwiftLee Weekly · Issue 295 — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **Published:** `2025-10-28T15:02:32.000Z`
  **NeKI brief:** Shows how to investigate Xcode build performance using the Build Navigator, timing summaries, compiler flags, script phases, and clean-versus-incremental comparisons. It also covers slow SwiftUI expressions and tracking improvements across a team.
- [video that demonstrates it](https://youtu.be/jYhRXZwO0cc) — iOS Dev Weekly · Issue 732 — Video · Topics: Graphics, Media & Games · Liquid Glass
  **Published:** `24th October 2025`
  **NeKI brief:** Examines the iOS 26.1 beta Liquid Glass Tinted setting, comparing its increased opacity, contrast, and readability with the default appearance in light and dark modes. Treat the demonstrated behavior as prerelease SDK context.
- [File Renamer AI](https://filerenamerai.com/) — iOS Dev Tools · iOS Dev Tools: GitHub Feedback SDK, CornerCraft, Appbot — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-10-23T17:57:34.511Z`
  **NeKI brief:** File Renamer AI applies AI-assisted naming or organization to local files. Follow it for a concrete batch-automation workflow, while verifying how suggestions, previews, and destructive rename safeguards operate.
- [Crafting Interactive Tiles in SwiftUI](https://uvolchyk.me/blog/crafting-interactive-tiles-in-swiftui) — Those Who Swift · Issue 237 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-22`
  **NeKI brief:** Examines Crafting Interactive Tiles in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — SwiftLee Weekly · Issue 294 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Refactors a large SwiftUI view into reusable components, modifiers, extensions, and a small UI library. It explains why computed view properties alone do not provide the isolation or reuse of genuine component boundaries.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Those Who Swift · Issue 236 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-15`
  **NeKI brief:** Explores SwiftUI's ConcentricRectangle and concentric-corner clipping APIs through per-corner radii, container-aware shapes, sheets, popovers, and tiled images. Useful for understanding how nested geometry can preserve visually consistent corners.
- [Brainfish](https://www.brainfishai.com/) — iOS Dev Tools · iOS Dev Tools: LaunchNext, Feather, DeskRest — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-09-25T16:45:27.027Z`
  **NeKI brief:** Brainfish AI presents an AI-powered product or support workflow. Follow it for concrete search, answer, or knowledge-base behavior, while verifying data handling, integrations, and provider boundaries.
- [YoutubeBarPlayer](https://artiomgramatin.github.io/SunnyAAGWebsite/YoutubeBarPlayer.html) — iOS Dev Tools · iOS Dev Tools: LaunchNext, Feather, DeskRest — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2025-09-25T16:45:27.027Z`
  **NeKI brief:** YoutubeBarPlayer plays YouTube videos from a macOS menu bar popover by accepting a pasted link and embedding playback. Follow it for a concrete lightweight media utility interaction without a full browser window.
- [iOS Application Rendering: A Deep Dive](https://l.fatbobman.com/w0103-06) — Fatbobman’s Swift Weekly · Issue 103 — Article · Topics: Graphics, Media & Games · Maps & Location
  **Published:** `2025-09-22T12:03:29.428Z`
  **NeKI brief:** Documents a personal investigation into how iOS renders application content. Follow it when studying rendering stages, compositing assumptions, and the boundary between observable UIKit behavior and implementation details that may change.
- [Five years ago, a TikTok video changed my life](https://david-smith.org/blog/2025/09/18/widgetsmith-at-five) — iOS Dev Weekly · Issue 727 — Article · Topics: Graphics, Media & Games
  **Published:** `19th September 2025`
  **NeKI brief:** Explains Widgetsmith Five Years Later - David Smith, Independent iOS Developer, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.
- [Ship better paywalls faster with RevenueCat’s native, customizable Paywall Builder](https://www.revenuecat.com/docs/tools/paywalls-v2) — iOS Dev Weekly · Issue 726 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th September 2025`
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Haptic Video Sync](https://github.com/thomasdye12/HapticPlayer) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** HapticPlayer is an iOS haptic playback example, providing a focused repository for experimenting with Core Haptics patterns. Useful for isolating feedback timing and device capability checks before embedding haptics into a larger feature.
- [Pedometer++ Redesign Walkthrough](https://david-smith.org/blog/2025/09/04/pedometer-redesign) — iOS Dev Weekly · Issue 725 — Article · Topics: Graphics, Media & Games · Liquid Glass · Testing
  **Published:** `5th September 2025`
  **NeKI brief:** Presents pedometer++ redesign walkthrough for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Pragma Conference](https://www.pragmaconference.com/speakers.html) — SwiftLee Weekly · Issue 287 — Article · Topics: Concurrency · Cross-Platform & Web · Developer Community & Business
  **Published:** `2025-09-02T14:17:18.000Z`
  **NeKI brief:** Describes Pragma Conference, providing the event-specific information needed to identify its Apple-platform community context.
- [Swiftfin](https://github.com/jellyfin/Swiftfin) — iOS Dev Tools · iOS Dev Tools: WhisperKit, Swiftfin, Pearcleaner — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2025-08-29T06:38:01.785Z`
  **NeKI brief:** Swiftfin is a Swift client for Jellyfin media services. Follow its source for concrete API, playback, authentication, and caching integration patterns, while verifying server and platform compatibility.
- [Four Corners: the first Playdate game written in Swift](https://news.play.date/news/four-corners-swift) — iOS Dev Weekly · Issue 724 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `29th August 2025`
  **NeKI brief:** It’s been more than a year since Rauhul Varma wrote about writing Playdate games in Swift, but it’s great to see they’re now appearing in the Catalog! 👍
- [Rauhul Varma wrote about writing Playdate games in Swift](https://www.swift.org/blog/byte-sized-swift-tiny-games-playdate) — iOS Dev Weekly · Issue 724 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `29th August 2025`
  **NeKI brief:** Presents rauhul varma wrote about writing playdate games in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Catalog](https://play.date/games/catalog) — iOS Dev Weekly · Issue 724 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `29th August 2025`
  **NeKI brief:** It’s been more than a year since Rauhul Varma wrote about writing Playdate games in Swift, but it’s great to see they’re now appearing in the Catalog! 👍
- [High-Level Anatomy of a Camera Capturing Session](https://mfaani.com/posts/ios/swiftui-camera-learnings) — Those Who Swift · Issue 229 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-08-27`
  **NeKI brief:** Examines High-Level Anatomy of a Camera Capturing Session, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Inspect & Optimize Image Decoding Timing in iOS](https://juniperphoton.substack.com/p/inspect-and-optimize-image-decoding) — Those Who Swift · Issue 228 — Article · Topics: Graphics, Media & Games · Performance
  **Published:** `2025-08-20`
  **NeKI brief:** Measures image-decoding timing in iOS. Useful for locating decoding work on the critical path and deciding whether image format, sizing, caching, or scheduling changes will improve responsiveness.
- [Creating Core Image Metal Shader Library in a Swift Package Plugin](https://juniperphoton.substack.com/p/creating-core-image-metal-shader) — Those Who Swift · Issue 227 — Article · Topics: Graphics, Media & Games · Swift · Swift Package Manager
  **Published:** `2025-08-13`
  **NeKI brief:** Examines Creating Core Image Metal Shader Library in a Swift Package Plugin, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How to Build iOS Apps with Cursor and Claude Code](https://www.youtube.com/watch?v=OgWbnJ3romI) — Those Who Swift · Issue 227 — Video · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-08-13`
  **NeKI brief:** Reviews How to Build iOS Apps with Cursor and Claude Code. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Qwen-Image](https://huggingface.co/Qwen/Qwen-Image) — Those Who Swift · Issue 226 — Article · Topics: Graphics, Media & Games
  **Published:** `2025-08-06`
  **NeKI brief:** Presents Qwen-Image and its model artifacts. Useful for evaluating image-generation capabilities and deployment constraints while keeping benchmark results separate from app-level product decisions.
- [current code](https://projects.blender.org/blender/blender.git) — Fatbobman’s Swift Weekly · Issue 95 — Tutorial · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `2025-07-28T12:02:57.187Z`
  **NeKI brief:** Blender is a large open-source 3D creation suite with a mature cross-platform codebase. Use the repository as a comparison point for graphics tooling and architecture, not as a Swift or Apple UI dependency.
- [Build Real-Time Communication Experiences with Stream](https://getstream.io/chat/sdk/ios) — iOS Dev Weekly · Issue 719 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `25th July 2025`
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [Pikzels](https://pikzels.com/) — iOS Dev Tools · iOS Dev Tools: XCFolder, Mocking Star, SwiftPostgresClient — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-07-24T17:41:16.681Z`
  **NeKI brief:** Pikzels provides a visual content-generation or marketing workflow. Follow it for concrete asset-production behavior, while distinguishing commercial product claims from Apple-platform implementation guidance.
- [Swift’s Measurement API — From Miles to Meters and Beyond](https://www.youtube.com/watch?v=tXbYO5MGjYU) — Those Who Swift · Issue 223 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `2025-07-16`
  **NeKI brief:** Reviews Swift’s Measurement API — From Miles to Meters and Beyond. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Two Practical Ways to Use matchedGeometryEffect() in SwiftUI](https://www.youtube.com/watch?v=i87zOQubYoI) — Those Who Swift · Issue 223 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-07-16`
  **NeKI brief:** Reviews Two Practical Ways to Use matchedGeometryEffect() in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [How To Put Swift in a Box](https://youtu.be/MV0wACpikyw) — iOS Dev Weekly · Issue 717 — Video · Topics: Graphics, Media & Games · Personal Essays · Swift
  **Published:** `11th July 2025`
  **NeKI brief:** Examines Don't miss out! Join us at the next Open Source Summit in Hyderabad, India (August 5); Amsterdam, Netherland (August 25-29); Seoul, South Korea (November 4-5. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Open Source Summit](https://events.linuxfoundation.org/open-source-summit-north-america) — iOS Dev Weekly · Issue 717 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games · Personal Essays
  **Published:** `11th July 2025`
  **NeKI brief:** The Linux Foundation page describes the Open Source Summit North America event and its programme for open-source developers and maintainers.
- [PlayCover](https://github.com/PlayCover/PlayCover) — iOS Dev Tools · iOS Dev Tools: FluidAudio, PlayCover, FlashSpace — Source repository · Topics: Developer Tools · Graphics, Media & Games · Hardware & Devices
  **Published:** `2025-07-10T20:12:55.159Z`
  **NeKI brief:** PlayCover runs iOS applications on macOS through a compatibility layer. Follow its source for concrete packaging, runtime, and input-mapping techniques, while treating compatibility and legal boundaries as project-specific constraints.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 92 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-07-07T12:01:56.119Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Android Apps in Swift: Getting Started with Skip](https://www.youtube.com/watch?v=AWRPubyQ9V8) — Those Who Swift · Issue 221 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Reviews Android Apps in Swift: Getting Started with Skip. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 278 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Xcode
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Embedding Godot games in iOS apps is easy now](https://christianselig.com/2025/05/godot-ios-interop) — iOS Dev Weekly · Issue 716 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Personal Essays
  **Published:** `27th June 2025`
  **NeKI brief:** You might have missed Christian Selig’s latest article in the run up to WWDC, but it’s worth reading as it’ll quickly get you up and running with a Godot scene inside your iOS or Mac. There has been plenty of work going on with Godot on Apple platforms…
- [a brief mention in a 2024 WWDC video](https://youtu.be/OWNjtWUb9bs?t=79) — iOS Dev Weekly · Issue 715 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `20th June 2025`
  **NeKI brief:** Details of how Apple use Swift in server environments have been hard to come by. It’s clear Apple care deeply about this subject from the sustained work they do on NIO and related packages. That said, apart from a brief mention in a 2024 WWDC video, there…
- [Escape from Tutorial Hell](https://sarahreichelt.gumroad.com/l/iqdry) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Is there an irony in the title of Sarah Reichelt’s new book when her previous book was named “macOS by Tutorials“? Maybe! 😂 But it doesn’t make the problem people face any less real. How do you transition from following a YouTube video or blog article to…
- [macOS by Tutorials](https://sarahreichelt.gumroad.com/l/oximx) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Presents macos by tutorials for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Manus – AI Video Generation is Now Live](https://manus.im/app) — Those Who Swift · Issue 219 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-06-19`
  **NeKI brief:** Introduces Manus as an AI video-generation product. Useful for product capability context, not as a technical Apple-platform source.
- [Task Closure Lifecycle in Swift Explained (vs Regular Closures)](https://www.youtube.com/watch?v=_0r7VL69l7I) — Those Who Swift · Issue 217 — Video · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `2025-06-18`
  **NeKI brief:** Reviews Task Closure Lifecycle in Swift Explained (vs Regular Closures). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Bandit - Online Security (or Not) Game](https://overthewire.org/wargames/bandit/bandit0.html) — Those Who Swift · Issue 217 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **Published:** `2025-06-18`
  **NeKI brief:** Provides the Bandit security wargame. Useful for learning command-line security concepts through progressive exercises, while keeping its intentionally vulnerable environment separate from production systems.
- [Introducing PickerKit for SwiftUI](https://danielsaidi.com/blog/2025/06/10/introducing-pickerkit-for-swiftui) — SwiftLee Weekly · Issue 275 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-06-12T15:03:23.000Z`
  **NeKI brief:** Presents Introducing PickerKit for SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The pregame quiz ’25](https://www.swiftjectivec.com/wwdc-2025-the-pregame-quiz) — iOS Dev Weekly · Issue 713 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `6th June 2025`
  **NeKI brief:** Presents W.W.D.C. 2025: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Google AI Studio’s new Gen Media](https://aistudio.google.com/gen-media) — Those Who Swift · Issue 216 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-05-28`
  **NeKI brief:** Introduces Google AI Studio’s generative-media capability. Useful for assessing AI asset workflows and their product boundaries before integrating generated media into an application.
- [SwiftUI Youtube Web Player](https://www.youtube.com/watch?v=eBjzQ1NCXQ4) — Those Who Swift · Issue 216 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-05-28`
  **NeKI brief:** Reviews SwiftUI Youtube Web Player. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [add it to the GitHub issue](https://github.com/AvdLee/RocketSimApp/issues/607) — SwiftLee Weekly · Issue 273 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `2025-05-27T14:08:19.000Z`
  **NeKI brief:** Points to add it to the GitHub issue, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Demystifying Picture in Picture on iOSA deep dive into using PiP mode.Artem Novichkov](https://www.artemnovichkov.com/blog/demystifying-picture-in-picture-on-ios?ref=createwithswift.com) — Create with Swift · Issue 60 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games · Swift
  **Published:** `2025-05-09T15:30:59.000Z`
  **NeKI brief:** Artem provides a practical guide for implementing Picture in Picture (PiP) functionality in iOS apps from setting up a camera feed using UIKit and AVFoundation, configuring the capture session, and enabling PiP mode.
- [Demystifying Picture in Picture on iOS](https://www.artemnovichkov.com/blog/demystifying-picture-in-picture-on-ios) — Those Who Swift · Issue 213 — Article · Topics: Graphics, Media & Games
  **Published:** `2025-05-07`
  **NeKI brief:** Artem provides a practical guide for implementing Picture in Picture (PiP) functionality in iOS apps from setting up a camera feed using UIKit and AVFoundation, configuring the capture session, and enabling PiP mode.
- [How to profile a SwiftUI app's performance?](https://www.youtube.com/watch?v=Dyh-ymg-qAo) — Those Who Swift · Issue 212 — Video · Topics: Performance · Swift · SwiftUI
  **Published:** `2025-04-30`
  **NeKI brief:** Profiles a SwiftUI app with Instruments to locate unexpected body reevaluations and slow code. The walkthrough covers collecting a representative trace, interpreting redraw behavior, and distinguishing measured bottlenecks from assumptions.
- [A flowing WebGL gradient, deconstructed](https://alexharri.com/blog/webgl-gradients) — iOS Dev Weekly · Issue 709 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `25th April 2025`
  **NeKI brief:** Deconstructs a flowing gradient built with a WebGL shader, noise functions, and mathematical transforms. The rendering ideas transfer well to Metal or custom graphics work when a polished animated background needs an explainable, tunable implementation.
- [latest post](https://snopia.net/en/blog/recipe-sticker-effect-swiftui) — iOS Dev Weekly · Issue 709 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `25th April 2025`
  **NeKI brief:** Presents latest post for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [top App Store earnings](https://appfigures.com/resources/insights/20250411?f=3) — iOS Dev Weekly · Issue 708 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `18th April 2025`
  **NeKI brief:** Examines March is officially behind us and that means it. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [try! Swift](https://tryswift.jp/en) — iOS Dev Weekly · Issue 708 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `18th April 2025`
  **NeKI brief:** Examines Swiftを使った開発のコツや最新の事例を求めて 世界中から開発者が集います。 日頃のSwiftの知識やスキルを披露し、協力しあうことを目的に、 2027年3月2日 - 4日の３日間開催します！. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Flappy Swift](https://sliemeobn.github.io/flappy-swift) — iOS Dev Weekly · Issue 708 — Article · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `18th April 2025`
  **NeKI brief:** try! Swift Tokyo was happening just a few days ago, and the organisers already have the entire set of videos available if you were not able to make the trip to Japan. Why not enjoy a few of them this weekend?
- [World Clock](https://apps.apple.com/us/app/world-clock-time-zone-widgets/id956377119) — iOS Dev Tools · iOS Dev Tools: FormattedListKit, Libraried, Pressdeck — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `2025-04-17T13:23:18.210Z`
  **NeKI brief:** World Clock presents analog or digital city times through Home Screen, Lock Screen, and Dynamic Island widgets. Follow it for a concrete cross-surface time-zone utility and widget configuration pattern.
- [Swift 6.1 ReleasedSwift 6.1 is now available!Swift.orgApple Inc.](https://www.swift.org/blog/swift-6.1-released?ref=createwithswift.com) — Create with Swift · Issue 56 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2025-04-11T15:33:31.000Z`
  **NeKI brief:** The community has already shared some excellent insights. If you’re looking to dive deeper, we highly recommend checking out this video by Vincent!
- [What’s New in Swift 6.1: TaskGroup Updates, Member Import Visibility & More](https://www.youtube.com/watch?v=rW3dKjQJOBY&t=425s) — Those Who Swift · Issue 209 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `2025-04-09`
  **NeKI brief:** Reviews What’s New in Swift 6.1: TaskGroup Updates, Member Import Visibility & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) — Those Who Swift · Issue 208 — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2025-04-02`
  **NeKI brief:** Reviews Terminus. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [GameShell](https://www.clockworkpi.com/gameshell) — Those Who Swift · Issue 208 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `2025-04-02`
  **NeKI brief:** Reviews GameShell. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Tracking Down Memory Leaks with Instruments](https://www.youtube.com/watch?v=j8y-LtRV4hM) — Those Who Swift · Issue 207 — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **Published:** `2025-03-28`
  **NeKI brief:** Reproduces an older-iPad crash, enables Malloc Stack Logging, and uses Instruments' Leaks template to trace per-stroke Metal texture allocation. Reusing the texture resolves the memory growth and provides a concrete profiling workflow.
- [Videos from Swift Heroes 2024](https://www.youtube.com/playlist?list=PLfCiO1zYKkATN7rOAaU1lyNEWJ3sXeKXx) — iOS Dev Weekly · Issue 704 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `21st March 2025`
  **NeKI brief:** It’s been a little while since 2024’s edition of Swift Heroes, but here’s a reminder of what you missed and why you might want to attend the next edition. 🦸‍♂️
- [2024’s edition](https://swiftheroes.com/2024) — iOS Dev Weekly · Issue 704 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `21st March 2025`
  **NeKI brief:** Next week Flora Damiano will present “Crafting Better App Icons” at SwiftHeroes in Turin, Italy. She will share her process and insights on creating app icons for various Apple platforms.
- [next edition](https://swiftheroes.com/2025) — iOS Dev Weekly · Issue 704 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `21st March 2025`
  **NeKI brief:** Swift Heroes 2025 is a conference resource for Swift developers. Use its talks and programme to discover community approaches to language, frameworks, architecture, and tooling.
- [10 Years of Swift: A decade in review](https://www.youtube.com/watch?v=cHiU-n6fZQ8) — Those Who Swift · Issue 206 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `2025-03-19`
  **NeKI brief:** Reviews 10 Years of Swift: A decade in review. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui?ref=createwithswift.com) — Create with Swift · Issue 52 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-14T17:00:20.000Z`
  **NeKI brief:** Chris explores how to display pixel art crisply in SwiftUI, ensuring sharp edges without unwanted blurring for game assets but also for low-resolution graphics.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — iOS Dev Weekly · Issue 703 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `14th March 2025`
  **NeKI brief:** Chris explores how to display pixel art crisply in SwiftUI, ensuring sharp edges without unwanted blurring for game assets but also for low-resolution graphics.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [BackEyes](https://apps.apple.com/cn/app/backeyes/id6741500980) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** BackEyes uses an offline camera model to detect nearby faces and hide selected applications when screen peeking is detected. Follow it for a concrete privacy-oriented interaction combining local inference, alerts, and app visibility control.
- [Spatial Rendering for Apple Vision Pro](https://www.youtube.com/watch?v=vO0M4c9mb2E) — iOS Dev Weekly · Issue 702 — Video · Topics: Graphics, Media & Games · Spatial Computing · Swift
  **Published:** `7th March 2025`
  **NeKI brief:** The video presents spatial rendering techniques for Apple Vision Pro and provides publicly readable developer-session metadata.
- [this repository](https://github.com/metal-by-example/spatial-rendering) — iOS Dev Weekly · Issue 702 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `7th March 2025`
  **NeKI brief:** I’ve had this repository from Warren Moore in my list of “things to check out” for a while now. Finally, seeing the release of this video made me do it. It’s an hour-long overview of his Swift-based renderer for visionOS, and while the content of his talk…
- [Swift DevRoom at FOSDEM 2025 Videos](https://swiftlang.github.io/event-fosdem) — iOS Dev Weekly · Issue 701 — Article · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `28th February 2025`
  **NeKI brief:** Collects Swift DevRoom talks from FOSDEM 2025 in one searchable programme and video index. Use the recordings to compare implementation techniques and ecosystem direction, then follow the referenced repositories or proposals when a talk informs production design.
- [Viz](https://github.com/alienator88/Viz) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Developer Tools · Graphics, Media & Games · macOS & AppKit
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Viz is a GitHub project for visualizing or inspecting data on Apple platforms. Follow its source and examples for concrete rendering and interaction patterns, while verifying the project’s supported frameworks and current maintenance.
- [this](https://www.gamedeveloper.com/business/steam-suddenly-banned-in-vietnam) — iOS Dev Weekly · Issue 699 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `14th February 2025`
  **NeKI brief:** Examines Valve. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to Do Apple Search Ads (ASA) Right and Grow Your Downloads](https://www.youtube.com/watch?v=W6_bN3AZo_s) — iOS Dev Weekly · Issue 698 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `7th February 2025`
  **NeKI brief:** Examines ► Search Ads Insights: https://appfigures.com/reports/competitor-search-ads► Keyword Inspector: https://appfigures.com/reports/keyword-inspector► Start a FRE. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftUI Image Playground](https://www.youtube.com/watch?v=fjtWpQGs5lU) — Those Who Swift · Issue 200 — Video · Topics: AI Development · Swift · SwiftUI
  **Published:** `2025-02-05`
  **NeKI brief:** Integrates Image Playground into SwiftUI so users can generate images from concepts or an existing source image. The walkthrough covers availability requirements, presentation, generated-image handling, and fallback-aware application structure.
- [Xcode 16: new features to know](https://www.youtube.com/watch?v=Ow0hU6bhiwo) — Those Who Swift · Issue 200 — Video · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `2025-02-05`
  **NeKI brief:** Reviews Xcode 16: new features to know. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [this great conference talk from GodotCon](https://youtu.be/irVRaTj0SGU) — iOS Dev Weekly · Issue 697 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Testing
  **Published:** `31st January 2025`
  **NeKI brief:** Examines Bringing Godot to the iPad has been a fabulous and fun adventure.In this talk I will discuss both the technical challenges imposed by the platform as well as. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Objective by the Sea](https://objectivebythesea.org/v7/index.html) — iOS Dev Weekly · Issue 697 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Community & Business
  **Published:** `31st January 2025`
  **NeKI brief:** The Objective by the Sea event might not be directly relevant to your everyday work as a security conference focused on Apple platforms. However, it’s close enough that you’ll almost certainly find something here to interest you.
- [Manual View Orientation Control](https://www.youtube.com/watch?v=9dyOYuv9p2Y) — Those Who Swift · Issue 199 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-01-30`
  **NeKI brief:** Reviews Manual View Orientation Control. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [MapKit + Metal Shaders + H3 (Uber Hex System) + SwiftUI](https://javios.gumroad.com/l/zlnde) — Those Who Swift · Issue 199 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-01-30`
  **NeKI brief:** Combines MapKit, Metal shaders, H3, and SwiftUI in a mapping example. Useful for evaluating geographic visualization architecture and the boundary between map data, GPU effects, and SwiftUI presentation.
- [Discover How AI Enables Zero-Maintenance Apps](https://www.instabug.com/blog/webinar-how-ai-transforms-mobile-observability-to-deliver-zero-maintenance-mobile-apps) — iOS Dev Weekly · Issue 696 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `24th January 2025`
  **NeKI brief:** Watch Instabug’s CPO, Kenny Johnston in this recorded webinar as he showcases how cutting-edge AI is changing the mobile observability and app quality game. Discover how AI automates the detection and fixing of app quality issues, leaving mobile teams to…
- [Swift Argument Parser with Guilherme Rambo](https://swifttoolkit.dev/posts/clis-rambo) — iOS Dev Weekly · Issue 695 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `17th January 2025`
  **NeKI brief:** Join Natan Rolnik and Gui Rambo as they discuss Swift Argument Parser. I love the argument parser, but PathKit, which they also showcase, was new to me.
- [Apple WWDC YouTube videos update](https://www.youtube.com/@AppleDeveloper/videos) — Those Who Swift · Issue 197 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2025-01-17`
  **NeKI brief:** Reviews Apple WWDC YouTube videos update. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [What was that doing in my database](https://eieio.games/essays/the-secret-in-one-million-checkboxes) — iOS Dev Weekly · Issue 692 — Article · Topics: Graphics, Media & Games · Persistence & Synchronisation
  **Published:** `20th December 2024`
  **NeKI brief:** Presents what was that doing in my database for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube](https://youtube.com/playlist?list=PLvHc56e5L-7xgZsgvF2yL7P13lmTwNcoh&ref=ioscodereview.com) — iOS Code Review · Issue 74 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `2024-12-04T11:30:50.000Z`
  **NeKI brief:** Records ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube as a visual walkthrough relevant to Graphics, Media & Games and Xcode. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [SwiftUI Zoom Navigation Transitions: Add a Touch of Magic to Your App](https://www.stphndxn.com/swiftui-zoom-navigation-transitions-add-a-touch-of-magic-to-your-app) — SwiftUI Weekly · SwiftUI Weekly - Issue #204 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-12-03T07:24:48.832Z`
  **NeKI brief:** Demonstrates zoom navigation transitions between SwiftUI source and destination views. Useful for preserving visual continuity when tapping thumbnails into detail screens.
- [SwiftUI Experiments](https://github.com/mikelikesdesign/SwiftUI-experiments) — iOS Dev Weekly · Issue 688 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `22nd November 2024`
  **NeKI brief:** Presents swiftui experiments for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift bindings](https://github.com/migueldeicaza/SwiftGodot) — iOS Dev Weekly · Issue 688 — Source repository · Topics: Developer Tools · Observation & State Management · Swift
  **Published:** `22nd November 2024`
  **NeKI brief:** I’ve been curious about Godot for a long time now. I got even more curious when Miguel de Icaza started working on Swift bindings for it. If you’re also curious then you should watch him giving this presentation from GodotCon 2024. I did, and thoroughly…
- [GodotCon 2024](https://conference.godotengine.org/2024) — iOS Dev Weekly · Issue 688 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Observation & State Management
  **Published:** `22nd November 2024`
  **NeKI brief:** Examines GodotCon Berlin October 12-13. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Understanding TextRenderer to Animate Words](https://www.rudrank.com/exploring-swiftui-textrenderer-to-animate-words) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Explains This protocol helps to replace the default text view rendering behaviour and helps you to customise how SwiftUI text is drawn for an entire view tree. Just typing that out felt cool. Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [MockData, PreviewModifiers and PreviewTraits in SwiftUI](https://www.youtube.com/watch?v=Yw7H4Ujpwtg) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Shows mock data, PreviewModifiers, and PreviewTraits for SwiftUI previews. Useful for repeatable preview environments that exercise realistic states without production dependencies.
- [Kavsoft](https://www.youtube.com/@Kavsoft?ref=createwithswift.com) — Create with Swift · Issue 31 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** Kavsoft presents a clean and intuitive onboarding implementation that utilizes the same style as native iOS apps, making it both familiar and effective for users.
- [Videos from Server-Side Swift Conference 2024](https://www.youtube.com/playlist?list=PLTFt3GGfH3hkUrqGFbHU5RX9qilN1QKDP) — iOS Dev Weekly · Issue 681 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `4th October 2024`
  **NeKI brief:** I mentioned in the last issue that I didn’t have the full context from Tony Parker and Ben Cohen’s announcement of swift-java. Now the videos from last week’s Server-Side Swift Conference are out, you can watch the whole announcement. All the other session…
- [watch the whole announcement](https://youtu.be/wn6C_XEv1Mo?si=pX2hHIR8M-qCRU73) — iOS Dev Weekly · Issue 681 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `4th October 2024`
  **NeKI brief:** Examines A special conference keynote discussing the latest developments with Swift and Interoperability🎥 Recorded at the ServerSide.swift conference in London in 20. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [or Sonumi](https://shaminospage.blogspot.com/2024/02/apples-magic-sound-file-renaming.html) — iOS Dev Weekly · Issue 681 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `4th October 2024`
  **NeKI brief:** I mentioned in the last issue that I didn’t have the full context from Tony Parker and Ben Cohen’s announcement of swift-java. Now the videos from last week’s Server-Side Swift Conference are out, you can watch the whole announcement. All the other session…
- [Exploring Core Graphics: Extract Prominent and Unique Colors from UIImage](https://www.rudrank.com/exploring-core-graphics-extract-prominent-unique-colors-uiimage?ref=createwithswift.com) — Create with Swift · Issue 28 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `2024-09-20T16:00:04.000Z`
  **NeKI brief:** Rudrank Riyam shows how he used Core Graphics to extract the prominent and unique colors from an image so you can use them to create effects like the mesh gradient on Apple Music.
- [StreamUI](https://github.com/StreamUI/StreamUI) — iOS Dev Tools · iOS Dev Tools: Inject, StreamUI, Hero — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2024-08-29T14:10:45.103Z`
  **NeKI brief:** StreamUI is a SwiftUI-related project providing reusable interface components or patterns. Follow its source for concrete view composition and state-handling choices, while verifying supported platform versions before adoption.
- [MeshGradients in iOS 18](https://www.youtube.com/watch?v=s_eQZ8rRV8Y) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Video · Topics: Graphics, Media & Games
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Demonstrates mesh gradients introduced for iOS 18 visual effects. Useful for evaluating animated, multicolor backgrounds without manually composing many gradient layers.
- [Olympic Logo in SwiftUI](https://medium.com/@alessandromanilii/olympic-logo-in-swiftui-dee37cbd53f1) — SwiftUI Weekly · SwiftUI Weekly - Issue #195 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-08-05T15:18:59.956Z`
  **NeKI brief:** Builds the Olympic logo with SwiftUI shapes and composition. Useful as a concrete exercise in layering, geometry, and reusable vector-style drawing.
- [React-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** React Native Vision Camera provides camera access and frame-processing capabilities for React Native applications. Follow its source for concrete native-module, permission, and frame-pipeline integration, while checking platform support.
- [SwiftConf](https://swiftconf.com/) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** SwiftConf is a conference resource featuring talks on Swift, Apple frameworks, architecture, and engineering practice. Use its programme to find community perspectives and verify technical claims independently.
- [NSSpain XII 2024](https://ti.to/nsspain/2024) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: Graphics, Media & Games
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** NSSpain XII 2024 is a conference event page. It is event promotion rather than technical reading and should normally be excluded from the knowledge index.
- [PragmaConf](https://pragmaconference.com/) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** Provides the Pragmaconference event hub for talks and community sessions about Apple development. Use it to discover practitioner perspectives and verify session details before relying on a conference presentation.
- [Building chat and struggling with state, push notifications, and more? 🤓💬](https://getstream.io/tutorials/ios-chat) — iOS Dev Weekly · Issue 671 — Tutorial · Topics: App Services & Extensions · Graphics, Media & Games
  **Published:** `26th July 2024`
  **NeKI brief:** Walks through integrating Stream's chat SDK into an iOS app, including message UI and networking. Useful as an implementation reference when evaluating managed real-time messaging.
- [but I did](https://www.youtube.com/watch?v=7UXsD7nSfDY) — iOS Dev Weekly · Issue 670 — Video · Topics: Graphics, Media & Games · Hardware & Devices · Product Design
  **Published:** `19th July 2024`
  **NeKI brief:** I didn’t think I’d watch a 20-minute video on building a keyboard, today, but I did! ⌨️
- [Zoom Transitions in SwiftUI](https://www.youtube.com/watch?v=malwmE5fDHw) — SwiftUI Weekly · SwiftUI Weekly - Issue #194 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-15T12:03:07.308Z`
  **NeKI brief:** Demonstrates zoom transitions in SwiftUI navigation. Useful for understanding source identity, destination matching, and when spatial transitions improve orientation in detail flows.
- [Software Engineer, iOS @ amo](https://amo.co/jobs?ashby_jid=eea9ddcc-19e8-4faa-ab03-f0d7b544c2e9) — iOS Dev Weekly · Issue 669 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `12th July 2024`
  **NeKI brief:** Examines Jobs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Laying out views with ContainerRelativeFrame in SwiftUI](https://www.youtube.com/watch?v=DudvesMYAAY) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Demonstrates ContainerRelativeFrame layouts in SwiftUI. Useful for sizing content relative to scroll containers and creating adaptive, platform-aware compositions.
- [watch the sample video](https://youtu.be/pdnPG4BywBQ) — iOS Dev Weekly · Issue 668 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `5th July 2024`
  **NeKI brief:** What a fun idea from Jordan Howlett. Have you ever wanted to make motion graphics for video with SwiftUI? Now you can, with his new library, StreamUI. Read the forum post above for a little background, or watch the sample video to see what it can create.
- [Diffuse reflection UV computation tool](https://www.elkraneo.com/diffuse-reflection-uv-computation-tool) — iOS Dev Weekly · Issue 668 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `5th July 2024`
  **NeKI brief:** The page documents a tool for computing diffuse-reflection UV data and explains its use in a graphics or rendering workflow.
- [My Favorite SwiftUI Updates in iOS 18](https://www.youtube.com/watch?v=aCbh9LmIZTI) — SwiftUI Weekly · SwiftUI Weekly - Issue #192 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-07-02T09:09:59.000Z`
  **NeKI brief:** Reviews notable SwiftUI updates arriving with iOS 18. Useful as a visual overview before drilling into individual API documentation and deployment constraints.
- [Using TextRenderer to create highlighted text](https://alexanderweiss.dev/blog/2024-06-24-using-textrenderer-to-create-highlighted-text) — iOS Dev Weekly · Issue 667 — Article · Topics: Graphics, Media & Games
  **Published:** `28th June 2024`
  **NeKI brief:** Uses TextRenderer to draw highlighted text in SwiftUI. Useful for search results, annotation, or syntax emphasis where attributed-string styling alone is insufficient.
- [Live near WWDC](https://youtu.be/xK4X5Src4oQ?t=1197) — iOS Dev Weekly · Issue 665 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `14th June 2024`
  **NeKI brief:** Examines Continuing a WWDC-week tradition that began in 2012, the annual James Dempsey and the Breakpoints show is back for 2024!Our musical band of nerds, techies, a. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Speculative Spatial Canvas Updates](https://imaginaryinstitute.gumroad.com/l/speculative-spatial-design-canvas?ref=createwithswift.com) — Create with Swift · Issue 15 — Article · Topics: Graphics, Media & Games · Spatial Computing · Swift
  **Published:** `2024-05-31T15:00:03.000Z`
  **NeKI brief:** This pivotal update introduces groundbreaking advancements to the Spatial Enablers Framework and the Spatial Computing Education Matrix, empowering you to unlock new immersive learning and design dimensions.
- [Did you know that Xcode Previews also work with UIKit?](https://www.youtube.com/watch?v=sC0WnigbmJw) — SwiftUI Weekly · SwiftUI Weekly - Issue #187 — Video · Topics: Graphics, Media & Games · UIKit · Xcode
  **Published:** `2024-05-20T22:04:41.287Z`
  **NeKI brief:** Shows UIKit views working inside Xcode Previews. Useful for previewing hybrid screens and validating representable or legacy UIKit components alongside SwiftUI.
- [Developing an Inclusive Mindset](https://david-smith.org/blog/2024/04/22/new-post) — iOS Dev Weekly · Issue 660 — Article · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `10th May 2024`
  **NeKI brief:** The page covers “Developing an Inclusive Mindset” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Flighty in SwiftUI](https://www.youtube.com/watch?v=81FwPLo-1eE) — SwiftUI Weekly · SwiftUI Weekly - Issue #185 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-05-06T13:22:31.904Z`
  **NeKI brief:** Presents a Flighty app implementation in SwiftUI. Useful for seeing a production-style interface assembled from navigation, lists, and custom visual components.
- [How to add a privacy manifest file to your app for required reason API usage?](https://www.donnywals.com/how-to-add-a-privacy-manifest-file-to-your-app-for-required-reason-api-usage?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Tutorial · Topics: Graphics, Media & Games · Security & Privacy
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** Uses How to add a privacy manifest file to your app for required reason API usage? as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [The Curious Case of Apple's Third-Party SDK List for Privacy Manifests](https://www.jessesquires.com/blog/2024/04/29/sdk-privacy-manifests?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Tutorial · Topics: Graphics, Media & Games · Security & Privacy
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** Uses The Curious Case of Apple's Third-Party SDK List for Privacy Manifests as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [SwiftData](https://www.youtube.com/playlist?list=PLlc_rDuPW0Y1X55v_cJlTWomSmHd-MS5r) — iOS Dev Weekly · Issue 659 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `3rd May 2024`
  **NeKI brief:** A nine-part series of videos on SwiftData sounds like a lot to chew through, doesn’t it? What if it was from Daniel Steinberg? Now you’re interested? Well, what if I added that they’re each only about 5 minutes long? Did that trigger your clicking finger? 😂…
- [Swift Server Side Meetup #1](https://www.youtube.com/watch?v=FULMRV3wIKg) — iOS Dev Weekly · Issue 658 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** If you missed Wednesday’s inaugural Swift Server Side Meetup, the good news is that YouTube has archived it! Join members of the Swift Server Workgroup for two presentations and plenty of Q&A. I wasn’t able to attend the live session, but from the look of…
- [Swift Server Workgroup](https://www.swift.org/sswg) — iOS Dev Weekly · Issue 658 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Improve Test Clarity (TDD with SwiftUI)](https://www.youtube.com/watch?v=AF8cCxrJr8M) — SwiftUI Weekly · SwiftUI Weekly - Issue #183 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-04-22T17:42:59.039Z`
  **NeKI brief:** Refactors a SwiftUI microtest so its assertions expose intent while setup and interaction details remain hidden. Useful for test-driven development discussions about readable tests before expanding a suite.
- [📹 Automatically generating release notes using Xcode Cloud](https://www.youtube.com/watch?v=ZBoBCCV5VQ8%3Futm_campaign%3DiOS+CI+Newsletter%26utm_medium%3Dweb%26utm_source%3DiOS+CI+Newsletter+Issue+40%26utm_content%3Dapr_21_24) — iOS CI Newsletter · Issue 40 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Xcode
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Records Automatically generating release notes using Xcode Cloud as a visual walkthrough relevant to Developer Community & Business and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube](https://www.youtube.com/@AppleDeveloper/playlists?ref=ioscodereview.com) — iOS Code Review · Issue 67 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2024-04-03T12:22:37.000Z`
  **NeKI brief:** Records Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube as a visual walkthrough relevant to Apple Platform Ecosystem and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [blog post](https://nixzhu.dev/posts/introducing-ducky) — iOS Dev Tools · iOS Dev tools: Ducky Model Editor, LocalizApp, Brewer X — Article · Topics: Graphics, Media & Games
  **Published:** `2024-03-28T15:43:54.859Z`
  **NeKI brief:** This post explains Ducky’s JSON-to-model workflow and its generated Swift representations. Follow it for concrete model inference and customization details, while verifying generated output against current Codable practices.
- [this video](https://www.youtube.com/watch?v=SKGdZ3H9eyY) — iOS Dev Weekly · Issue 653 — Video · Topics: Graphics, Media & Games
  **Published:** `22nd March 2024`
  **NeKI brief:** The YouTube page provides the publicly viewable video referenced by the newsletter and its associated metadata.
- [Hacking Disneyland’s App to fix a Freeze](https://youtube.com/watch?v=SpHl5_0n3Ps) — iOS Dev Weekly · Issue 652 — Video · Topics: Graphics, Media & Games · Testing
  **Published:** `15th March 2024`
  **NeKI brief:** I really enjoyed Bryce Pauken’s latest video on fixing a bug in the Disney app. I’ve never seen a more straightforward demonstration of the techniques he uses here. 👍
- [Tundsdev channel on YouTube](https://www.youtube.com/@tundsdev/videos?ref=createwithswift.com) — Create with Swift · Issue 3 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2024-03-08T16:00:49.000Z`
  **NeKI brief:** Lately, anytime someone asks us about how to start learning Swift Data the first thing that comes to mind is tundsdev YouTube channel.
- [Exploring visionOS: hoverEffect](https://www.rudrank.com/exploring-visionos-hovereffect) — SwiftUI Weekly · SwiftUI Weekly - Issue #176 — Article · Topics: Graphics, Media & Games · Spatial Computing
  **Published:** `2024-02-12T08:54:16.360Z`
  **NeKI brief:** Explains I am updating my app, Gradient Game for Apple Vision Pro, which looks amazing on a beautiful glass background and a chef kiss interaction when dragging sliders. The goal is to make the interaction with the elements feel Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [sent out only via email](https://mailchi.mp/e1735a8e72df/a-computer-for-the-rest-of-us?e=776be5695e) — iOS Dev Weekly · Issue 645 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th January 2024`
  **NeKI brief:** The page covers “sent out only via email” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [his recent blog post](https://adamwulf.me/2024/01/removing-xcode-simulator-touch-indicators) — iOS Dev Weekly · Issue 645 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `26th January 2024`
  **NeKI brief:** Examines I’ve been working on creating new Muse onboarding and tutorial videos, and I’m using my HandShadows Swift package to show the gestures visually during the …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Stream](https://getstream.io/) — iOS Dev Tools · 🔨 Reveal, Fabula, AnimateText — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2024-01-25T16:38:45.891Z`
  **NeKI brief:** Stream provides developer-facing infrastructure for in-app chat, feeds, and activity experiences. Follow it for concrete integration patterns around real-time social features, while verifying SDK and API versions separately.
- [📝 Platform-specific release notes with Xcode Cloud](https://www.finnvoorhees.com/words/platform-specific-release-notes-with-xcode-cloud) — iOS CI Newsletter · Issue 33 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Xcode
  **Published:** `2024-01-14T00:00:00.000Z`
  **NeKI brief:** Summarises Platform-specific release notes with Xcode Cloud for App Distribution & Store Operations and Apple Platform Ecosystem. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Reading and Writing Spatial Video with AVFoundation](https://www.finnvoorhees.com/words/reading-and-writing-spatial-video-with-avfoundation) — iOS Dev Weekly · Issue 643 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games
  **Published:** `12th January 2024`
  **NeKI brief:** What does MV-HEVC mean to you? I hadn’t heard of it, either, until I read this great post from Finn Voorhees on the additions to AVFoundation that allow reading and writing of spatial video files.
- [MV-HEVC](http://hevc.info/mvhevc) — iOS Dev Weekly · Issue 643 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games
  **Published:** `12th January 2024`
  **NeKI brief:** Examines HEVC Multiview Extension (MV-HEVC) resources. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftData](https://www.youtube.com/playlist?list=PLBn01m5Vbs4Ck-JEF2nkcFTF_2rhGBMKX) — iOS Dev Weekly · Issue 642 — Video · Topics: Developer Community & Business · Swift · SwiftData
  **Published:** `5th January 2024`
  **NeKI brief:** Collects videos around SwiftData in a single playlist. Useful for discovery and grouped learning, while each recording should be checked separately for current API behavior.
- [How to Play Spatial Video On iOS 17.2](https://xreality.zone/zh/posts/how-to-play-spatial-video-on-ios-17-2) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Demonstrates playing spatial video on iOS 17.2 and discusses the media and device prerequisites involved. Use it to investigate immersive-video playback paths while verifying format support and availability against current Apple APIs.
- [App Localizations](https://www.youtube.com/watch?v=kbgNL7VrQPo) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: Graphics, Media & Games · Localization · Swift
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Demonstrates localizing a SwiftUI app with Xcode 15 String Catalogs, including the workflow for translating strings across languages. Useful when replacing scattered localization files with catalog-driven review and export in a modern project.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Shows how to request App Store ratings from an app and frame the timing around user experience. Useful for integrating review prompts deliberately while keeping eligibility, frequency, and platform presentation behavior under app control.
- [Founder/CTO @ XLIO](https://docs.google.com/document/d/1LMWlg7FMzdHyuILgIONjFprE52Onm8GRAgb2nQJRWlI) — iOS Dev Weekly · Issue 639 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `8th December 2023`
  **NeKI brief:** Founder/CTO @ XLIO – An opportunity to lead the development of a greenfield project requiring deep macOS integration (this is not “just another” Swift app) which will be installed on hundreds of thousands of devices worldwide. – Remote (within US timezones)…
- [Videos from SwiftLeeds 2023](https://www.youtube.com/playlist?list=PL-wmxEeX64YRN8dTs88K6jot_NKmemMLb) — iOS Dev Weekly · Issue 637 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `24th November 2023`
  **NeKI brief:** The YouTube playlist collects publicly viewable SwiftLeeds 2023 talks and exposes their developer-session metadata.
- [Inferno](https://github.com/twostraws/Inferno) — Fatbobman’s Swift Weekly · Issue 7 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Inferno is a SwiftUI-focused learning and example repository from Paul Hudson. Useful as a code-reading route for modern view composition, provided examples are checked against the target SDK.
- [creating custom shaders](https://www.youtube.com/watch?v=EgzWwgRpUuw) — Fatbobman’s Swift Weekly · Issue 7 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Builds Metal shaders for SwiftUI effects including recoloring, animated gradients, waves, loupe distortion, and custom transitions. The examples show how fragment shaders receive view-relative data and drive GPU-rendered visual changes.
- [Shader course](https://www.hackingwithswift.com/plus/advanced-swiftui/how-to-create-metal-shaders-for-swiftui-part-1) — Fatbobman’s Swift Weekly · Issue 7 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Introduces a course workflow for creating Metal shaders used by SwiftUI, from shader functions to view integration. Use it to structure GPU-effect experiments while keeping parameter flow, performance, and fallback behavior testable.
- [best README file](https://github.com/twostraws/Inferno/blob/main/README.md) — iOS Dev Weekly · Issue 636 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th November 2023`
  **NeKI brief:** Seriously, though, this is a fantastic video that takes a genuinely approachable look at Metal fragment shaders for someone without prior Metal knowledge. Even better, it’s accompanied by a blog post and GitHub repository with possibly the best README file…
- [Stream](https://getstream.io/chat/sdk/swiftui) — iOS Dev Weekly · Issue 635 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `10th November 2023`
  **NeKI brief:** Presents stream for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Check out this tool!](https://github.com/GetStream/effects-library/tree/main) — iOS Dev Tools · 🔨 ASO, ToDoBar, EffectsLibrary — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `2023-11-09T14:17:10.440Z`
  **NeKI brief:** This EffectsLibrary tree link points to the repository’s main source branch and examples. Follow it to inspect the concrete effect implementations, while treating the directory landing page itself as navigation rather than independent reading.
- [Building Complex Scroll Animations With New iOS 17 API's](https://www.youtube.com/watch?v=ytRim2TSdyY) — SwiftUI Weekly · SwiftUI Weekly - Issue #167 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-11-06T09:00:48.537Z`
  **NeKI brief:** Builds complex scroll animations with the new iOS 17 SwiftUI scrolling APIs. Useful for studying how scroll position, geometry, and phase changes can drive coordinated effects without relying on fragile offset preferences.
- [A Comprehensive Guide to App Accessibility](https://getstream.io/blog/app-accessibility-guide) — Fatbobman’s Swift Weekly · Issue 4 — Article · Topics: Accessibility · Graphics, Media & Games · Performance
  **Published:** `2023-10-30T15:20:20.330Z`
  **NeKI brief:** Presents an app accessibility guide spanning semantic labeling, contrast, and assistive-technology interaction. Use it as a broad review checklist before drilling into platform-specific VoiceOver or Dynamic Type fixes.
- [Videos from Swift Connection 2023](https://www.youtube.com/playlist?list=PLZsRQnRG-mlI4T7gALW4_aK85dSTIooGd) — iOS Dev Weekly · Issue 633 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `27th October 2023`
  **NeKI brief:** What a great selection of talks from Swift Connection 2023. It’s so great to see conferences return with such high quality. 👍
- [SwiftHub](https://apps.apple.com/us/app/swifthub-learn-build-share/id1539940969) — iOS Dev Tools · 🔨 SwiftHub, WishKit, Presentify — Podcast · Topics: Developer Community & Business · Swift · Testing
  **Published:** `2023-10-26T14:13:35.621Z`
  **NeKI brief:** SwiftHub aggregates Swift articles, books, podcasts, documentation, videos, and community questions in one discovery app. Use it as a curated learning index, not as authoritative framework documentation.
- [Presentify](https://presentify.compzets.com/) — iOS Dev Tools · 🔨 SwiftHub, WishKit, Presentify — Tutorial · Topics: Graphics, Media & Games
  **Published:** `2023-10-26T14:13:35.621Z`
  **NeKI brief:** Presentify turns a Mac screen into a presentation or annotation surface. Follow it for concrete pointer, drawing, and screen-sharing interactions during demos or technical reviews.
- [On Launching your Indie App: Part 1](https://www.swiftjectivec.com/on-launching-your-indie-app) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Reflects on launching an independent app, including product scope, marketing, and release realities. Use it as practitioner context when planning an indie product beyond implementation alone.
- [Running Stable Diffusion with Core ML on iOS smoothly](https://zenn.dev/shu223/articles/coreml-stable-diffusion) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: Graphics, Media & Games · Personal Essays
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Describes running Stable Diffusion with Core ML on iOS and the optimization constraints involved in local inference. Use it to investigate model conversion, memory pressure, and device performance before adopting generative image features.
- [📹 [NSSpain] Why CI/CD won’t save your mobile team](https://vimeo.com/865678854) — iOS CI Newsletter · Issue 27 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `2023-10-22T00:00:00.000Z`
  **NeKI brief:** Records NSSpain] Why CI/CD won’t save your mobile team as a visual walkthrough relevant to CI/CD & Automation and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Videos from NSSpain 2023](https://vimeo.com/showcase/10672108) — iOS Dev Weekly · Issue 631 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `13th October 2023`
  **NeKI brief:** Records all other talk recordings from NSSpain 2023 on Vimeo as a visual walkthrough relevant to Apple-platform engineering. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Take the 6-question Health Check](https://bitrise.io/learn/modas-health-check) — iOS Code Review · Issue 57 — Article · Topics: Code Quality · Developer Community & Business · Graphics, Media & Games
  **Published:** `2023-10-12T11:48:38.000Z`
  **NeKI brief:** Examines Take the 6-question Health Check in the context of Code Quality and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [iPhone 15 Pro / Apple Vision Pro 上的空间视频，到底是什么？](https://xreality.zone/zh/posts/what-is-spatial-video-on-iphone-15-pro-and-apple-vision-pro) — Fatbobman’s Swift Weekly · Issue 1 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Introduces spatial video captured on iPhone 15 Pro and viewed on Apple Vision Pro, covering the format's stereoscopic intent. Use it to orient media-pipeline decisions while validating capture, playback, and conversion support in current frameworks.
- [Daniel Steinberg - SwiftUI to destroy the Publishing Industry](https://www.youtube.com/watch?v=rhqASksgJu0) — SwiftUI Weekly · SwiftUI Weekly - Issue #163 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T12:59:37.492Z`
  **NeKI brief:** Discusses the shift from ObservableObject and @Published toward the @Observable macro, using SwiftUI refresh behavior as the concrete case. Useful for understanding observation changes before choosing a migration strategy for existing view models.
- [Chris Eidhof - A Day in the Life of a SwiftUI View](https://www.youtube.com/watch?v=MRY3UCUVv98) — SwiftUI Weekly · SwiftUI Weekly - Issue #163 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-10-09T12:59:37.492Z`
  **NeKI brief:** Walks through how a SwiftUI view is rendered, laid out, and updated over its lifetime. Useful as a conceptual debugging aid when body recomputation, identity, or layout behavior seems surprising.
- [Introducing a Memory-Safe Successor Language in Large C++ Code Bases](https://www.youtube.com/watch?v=lgivCGdmFrw) — iOS Dev Weekly · Issue 626 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `8th September 2023`
  **NeKI brief:** Explains a memory-safe successor language in the context of large C++ codebases and migration concerns. Useful for comparing ownership and safety strategies, while keeping its language-specific claims separate from Swift guidance.
- [complete YouTube playlist](https://www.youtube.com/playlist?list=PL_AKIMJc4roUIwMsWnA9WPFJdCRfNUWHP) — iOS Dev Weekly · Issue 626 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `8th September 2023`
  **NeKI brief:** Provides a public playlist of talks and demonstrations from the referenced technical event. Useful for following a grouped set of presentations, but individual videos should be assessed separately before treating them as durable technical references.
- [How to implement pagination with SwiftUI's List view](https://tanaschita.com/20230828-pagination-in-swiftui-list) — SwiftUI Weekly · SwiftUI Weekly - Issue #157 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-08-28T11:14:18.626Z`
  **NeKI brief:** Explains Pagination is a common technique when displaying a large set of data in lists or grids allowing users to navigate through the data efficiently. By loading and rendering a limited number of items at a time, pagination min Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [Applying metal shader to text in SwiftUI](https://augmentedcode.io/2023/08/07/applying-metal-shader-to-text-in-swiftui) — iOS Dev Weekly · Issue 622 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Applies a simple Metal shader to SwiftUI text using the shader-related view modifiers introduced with WWDC 2023. A compact first example for learning how ShaderLibrary effects connect SwiftUI views to custom Metal code.
- [How to Easily Persist Data in SwiftUI](https://www.youtube.com/watch?v=CcUgRDLcUmQ) — iOS Dev Weekly · Issue 621 — Video · Topics: Graphics, Media & Games · Persistence & Synchronisation · Swift
  **Published:** `4th August 2023`
  **NeKI brief:** Talking of SwiftData, how about a guide through the basics from Karin Prater? She builds the ultimate example app when you want to play with a persistence framework, a to-do list app!
- [Swift Macros](https://www.youtube.com/playlist?list=PLlc_rDuPW0Y2Z2T1Dv-je_fG1ZQyIhehi) — iOS Dev Weekly · Issue 620 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Swift
  **Published:** `28th July 2023`
  **NeKI brief:** Explores Swift Macros, focusing on if you have 20 minutes free, you could do worse things with it than to join daniel steinberg as he brings his. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI AlignmentGuides](https://www.youtube.com/watch?v=fdSGlCgz1fQ) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Demonstrates SwiftUI alignment guides for positioning views according to custom alignment rules. Useful when stack defaults cannot express a design and geometry-reader measurements would add unnecessary layout coupling.
- [video covering his demo experience](https://youtu.be/n8-wTpiuZwE) — iOS Dev Weekly · Issue 618 — Video · Topics: Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games
  **Published:** `14th July 2023`
  **NeKI brief:** It’s been a few weeks since they were published, but I’ve had two videos on my mind recently, both covering the Vision Pro headset demos from WWDC. First, just a couple of days after the conference ended, Paul Hudson posted a video covering his demo…
- [React Native Vision Camera - Capture the World Differently](https://github.com/daltoniam/Starscream) — iOS Dev Tools · 🔨 Real-time Rendering & Stunning Imagery — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2023-07-13T13:51:39.780Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Build an app using SwiftData](https://www.youtube.com/playlist?list=PLvUWi5tdh92wZ5_iDMcBpenwTgFNan9T7) — iOS Dev Weekly · Issue 617 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Explores Build an app using SwiftData, focusing on it’s a measure of how many new things were announced. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Relationships In SwiftData](https://www.youtube.com/watch?v=_QMalUGTM4E&feature=youtu.be) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Demonstrates adding relationships between SwiftData models in a SwiftUI to-do app. Useful for understanding relationship declaration, editing, and fetch behavior before modeling linked domain objects.
- [SwiftUI Data Flow in iOS 17 - Observation](https://www.youtube.com/watch?v=EK7SthdWV2w) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Introduces iOS 17 Observation and the @Observable macro as a replacement for older SwiftUI object wrappers. Useful for comparing data-flow ownership and update behavior when migrating an existing model layer.
- [In-app purchase updates from WWDC](https://www.revenuecat.com/blog/engineering/wwdc2023-highlights) — iOS Dev Weekly · Issue 615 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `23rd June 2023`
  **NeKI brief:** Examines RevenueCat developer advocate Charlie Chapman shares his first impressions from WWDC 2023, focusing on subscriptions, monetisations, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift-Macros: A curated list of awesome Swift Macros](https://github.com/krzysztofzablocki/Swift-Macros) — iOS Dev Weekly · Issue 614 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `16th June 2023`
  **NeKI brief:** Explores Swift-Macros: A curated list of awesome Swift Macros, focusing on the article discusses want to write something more detailed about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The unofficial WWDC app](https://github.com/insidegui/WWDC) — iOS Dev Weekly · Issue 613 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `9th June 2023`
  **NeKI brief:** The official Developer app is excellent and gets better every year, but I reach for this independently developed app when I want to stream (or download) a WWDC video. So, I’d like to thank Gui Rambo and all the contributors for their work every year in…
- [all the contributors](https://github.com/insidegui/WWDC/graphs/contributors) — iOS Dev Weekly · Issue 613 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `9th June 2023`
  **NeKI brief:** The official Developer app is excellent and gets better every year, but I reach for this independently developed app when I want to stream (or download) a WWDC video. So, I’d like to thank Gui Rambo and all the contributors for their work every year in…
- [Mac & iOS Software Engineer @ Flexibits Inc.](https://flexibits.com/jobs) — iOS Dev Weekly · Issue 613 — Article · Topics: Graphics, Media & Games
  **Published:** `9th June 2023`
  **NeKI brief:** Mac & iOS Software Engineer @ Flexibits Inc. – We make Fantastical and Cardhop, award-winning calendar and contacts apps for Mac and iOS. We were honored to win Apple’s Mac App of the Year in 2020 and we’re looking to make our apps even better! Our team is a…
- [Display Text Like a Pro in SwiftUI](https://youtu.be/AJMycg7Llv0) — iOS Dev Weekly · Issue 610 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `19th May 2023`
  **NeKI brief:** Explores Display Text Like a Pro in SwiftUI, focusing on this video from vincent pradeilles and natalia panferova is excellent.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [scene from Moana](https://disneyanimation.com/resources/moana-island-scene) — iOS Dev Weekly · Issue 610 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `19th May 2023`
  **NeKI brief:** Examines This data set contains everything necessary to render a version of the Motunui island featured in the 2016 film Moana. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [is it](https://gonsoloblog.wordpress.com/2021/01/14/rendering-moana-with-swift) — iOS Dev Weekly · Issue 610 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `19th May 2023`
  **NeKI brief:** Rendering a scene from Moana with a renderer built in less than 10.000 lines of Swift code? That’s surely not possible, is it? 😳
- [SwiftUI Showcase View - Highlight App New Features](https://www.youtube.com/watch?v=I9v-zqrE8gI) — SwiftUI Weekly · SwiftUI Weekly - Issue #142 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-05-15T09:13:45.627Z`
  **NeKI brief:** Builds a reusable SwiftUI showcase flow for presenting newly added app features through paged, visually emphasized content and explicit dismissal state. Useful when release highlights need an in-app presentation rather than static notes.
- [this video](https://www.youtube.com/watch?v=bOMQiMxh5Bc) — iOS Dev Weekly · Issue 609 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `12th May 2023`
  **NeKI brief:** Examines If our vision is to become the "internet computer" of the future, Windows is a pretty important platform. But how we're building Arc for Windows is..... kind. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Why Don’t A/B Tests Add Up?](https://www.lukew.com/ff/entry.asp?2012=) — iOS Dev Weekly · Issue 607 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `28th April 2023`
  **NeKI brief:** Examines LukeW Ideation + Design provides resources for mobile and Web product design and strategy including presentations, workshops, articles, books and more on usability, interaction des. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [whole talk is worth watching](https://youtu.be/mAiNdU1go1A) — iOS Dev Weekly · Issue 607 — Video · Topics: AI Development · Graphics, Media & Games · Testing
  **Published:** `28th April 2023`
  **NeKI brief:** The YouTube page provides the publicly viewable full talk recommended by the newsletter and its associated metadata.
- [Apple Platforms Developer @ Cascable AB](https://cascable.se/jobs) — iOS Dev Weekly · Issue 607 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `28th April 2023`
  **NeKI brief:** Explores Apple Platforms Developer @ Cascable AB, focusing on apple platforms developer @ cascable ab – cascable is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Speedrun Design: Heart Rate Zone View in SwiftUI](https://www.david-smith.org/blog/2023/04/24/design-notes-35) — SwiftUI Weekly · SwiftUI Weekly - Issue #140 — Article · Topics: Graphics, Media & Games · Personal Essays · Swift
  **Published:** `2023-04-25T07:37:25.660Z`
  **NeKI brief:** Builds a SwiftUI heart-rate-zone view as a compact design exercise, exposing the visual decisions behind a data-driven display. It is useful for studying how a constrained, real-world metric can become a readable custom SwiftUI component.
- [SwiftUI rendering pitfalls](https://swiftunwrap.com/article/swiftui-rendering-pitfalls) — SwiftUI Weekly · SwiftUI Weekly - Issue #137 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-04-03T19:16:33.994Z`
  **NeKI brief:** Explains Mastering SwiftUI rendering cycle is not easy and it's common to face issues with it such as having your views rendering too often or not rendering at all while some state changed. In this article we'll focus on the seco Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [How Blither uses the coordinator pattern and SwiftUI together](http://chesstris.com/2023/03/23/how-blither-uses-the-coordinator-pattern-and-swiftui-together) — SwiftUI Weekly · SwiftUI Weekly - Issue #136 — Article · Topics: Graphics, Media & Games · Navigation & Deep Linking · Swift
  **Published:** `2023-03-27T21:57:02.938Z`
  **NeKI brief:** Shows how a coordinator can keep SwiftUI game screens focused by moving navigation and supporting-screen flow out of the view. Useful when a small app needs clearer separation without introducing a heavy architecture.
- [Can ChatGPT write better SwiftUI code than you?](https://www.youtube.com/watch?v=dxxCPdcMcFw) — SwiftUI Weekly · SwiftUI Weekly - Issue #136 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-03-27T21:57:02.938Z`
  **NeKI brief:** Explores Can ChatGPT write better SwiftUI code than you?, focusing on there are a great many blog posts and youtube videos. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The difference between List and LazyVStack](https://dimillian.medium.com/swiftui-the-difference-between-list-and-lazyvstack-3d5eeaccb156) — iOS Dev Weekly · Issue 599 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `3rd March 2023`
  **NeKI brief:** Compares List with LazyVStack through the rendering, scrolling, and interaction behaviour that makes them different despite similar output. Follow it before replacing one with the other in a performance-sensitive screen or a layout needing list-specific capabilities.
- [Arc Coding Chronicles](https://www.youtube.com/watch?v=94asyypYj5c) — SwiftUI Weekly · SwiftUI Weekly - Issue #132 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2023-02-21T07:37:59.536Z`
  **NeKI brief:** Reconstructs Arc Browser's SwiftUI loading indicator and shares the supporting code, showing how a small branded animation was designed and implemented. Useful as a focused animation study rather than a general loading-state pattern.
- [Using JavaScript in a Swift app](https://douglashill.co/javascript-in-swift) — iOS Dev Weekly · Issue 594 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `27th January 2023`
  **NeKI brief:** Explains Using JavaScript in a Swift app, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Douglas Hill](https://micro.blog/douglas) — iOS Dev Weekly · Issue 594 — Article · Topics: Graphics, Media & Games
  **Published:** `27th January 2023`
  **NeKI brief:** Provides Douglas Hill’s public author profile and links to related posts. Useful only as a discovery route; the profile itself is not a durable technical reference.
- [Videos from Do iOS 2022](https://www.youtube.com/playlist?list=PLw-3TTKkn1fM-5kugk9vyJTXZF8B0zHxC) — iOS Dev Weekly · Issue 593 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `20th January 2023`
  **NeKI brief:** Examines These are the recordings of all talks of the Do iOS Conference that was held on 8 and 9 November 2022 in Amsterdam. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Running audio/video UI tests on CI](https://www.kubilayerdogan.net/xctest-fixing-audio-video-ui-tests-on-your-ci-cd) — iOS CI Newsletter · Issue 7 — Article · Topics: Graphics, Media & Games · Personal Essays · Testing
  **Published:** `2023-01-15T00:00:00.000Z`
  **NeKI brief:** Examines Running audio/video UI tests on CI in the context of Graphics, Media & Games and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Mocking up iOS Control Center using SwiftUI](https://www.youtube.com/watch?v=k0mm-Dh9C9U) — iOS Dev Weekly · Issue 591 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `6th January 2023`
  **NeKI brief:** Examines Hello Guys 🖐🖐🖐In this Video I'm going to teach how to re-create iOS famous Control Center Volume Control Slider With Animations Using SwiftUI 4.0 | SwiftU. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — SwiftUI Weekly · SwiftUI Weekly - Issue #121 — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **Published:** `2022-11-21T12:42:39.000Z`
  **NeKI brief:** Explains Composable Architecture composition through Scope, Combine, and Pullback operators. Follow the concrete reducer composition to understand how child state and actions are routed while preserving testable feature boundaries in a SwiftUI application.
- [Codelime](https://onmyway133.com/codelime?ref=ioscodereview.com) — iOS Code Review · Issue 37 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `2022-11-18T11:51:59.000Z`
  **NeKI brief:** Examines Codelime in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Top Three iOS Mobile App Security Myths](https://www.guardsquare.com/video/misconceptions-about-ios-mobile-app-security) — iOS Dev Weekly · Issue 583 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **Published:** `4th November 2022`
  **NeKI brief:** It’s easy to get caught up in the myths surrounding mobile app security. But the biggest misconception may just be that iOS security is better than Android. Watch this video to learn about the most common misconceptions of iOS mobile app security and how you…
- [Collecting project’s metrics](https://vimeo.com/showcase/9831667/video/751286701) — iOS CI Newsletter · Issue 1 — Video · Topics: Graphics, Media & Games
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Records Collecting project’s metrics as a visual walkthrough relevant to Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Women Who Code Mobile Summit 2022](https://www.youtube.com/playlist?list=PLVcEZG2JPVhf_iA733UhMxPS0H8iCoouj) — iOS Dev Weekly · Issue 580 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `14th October 2022`
  **NeKI brief:** Explores Women Who Code Mobile Summit 2022, focusing on the article discusses missed this when women who code first. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift 5.7 Released](https://www.swift.org/blog/swift-5.7-released) — iOS Dev Weekly · Issue 576 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `16th September 2022`
  **NeKI brief:** Summarises the full list of evolution proposals released in 5.7 for Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Visualize sorting in Swift Charts](https://www.youtube.com/watch?v=UCSXF741iHI) — iOS Dev Weekly · Issue 572 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `19th August 2022`
  **NeKI brief:** Sure, you can use Swift Charts to build data visualisations, but how about using it to visualise algorithms over time? Mike Mikina takes a detailed and well-produced walkthrough using the framework to visualise sort algorithms.
- [Cliffhanger](https://www.youtube.com/watch?v=2j18n9shdw8) — iOS Dev Weekly · Issue 570 — Video · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `5th August 2022`
  **NeKI brief:** I’m no rock climber, but if Cliffhanger taught me anything, I know that climbing is a lot like using git! 😂 Every commit is a piton hammered into the rock face, and no matter how tricky your next move is, the rope attached to that last metal spike will catch…
- [Shaders Explained - Gradients](https://mtldoc.com/metal/2022/08/04/shaders-explained-gradients.html) — iOS Dev Weekly · Issue 570 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `5th August 2022`
  **NeKI brief:** Examines Shaders Explained: Gradients | MTLDoc. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Extracting Views Into Components in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9Rkk0WXJtR2VncWciLCJwb3N0X2lkIjoiZmM1Y2I3MDEtMzdkNy00YTFjLWI1ZmUtMGY3NjAzYzcxNDVmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhNWVmMDA2LWIzZWMtNDcyZi1iNDgxLTIyMzdlYjE4NmZjNyIsImlhdCI6MTY3NDA2MjU1Ny45ODUsImlzcyI6Im9yY2hpZCJ9.gTL9x1122ggPRSt8rIVlwZE8wGlOmIW2f0Z_J-RWaso) — SwiftUI Weekly · SwiftUI Weekly - Issue #111 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-08-01T20:26:06.000Z`
  **NeKI brief:** Shows extracting SwiftUI view components from a larger screen. Follow the refactoring steps to separate layout responsibilities and identify stable inputs, while checking that component boundaries do not obscure state ownership or accessibility behavior.
- [Mastering NavigationStack in SwiftUI. Navigator Pattern.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA2LzE1L21hc3RlcmluZy1uYXZpZ2F0aW9uc3RhY2staW4tc3dpZnR1aS1uYXZpZ2F0b3ItcGF0dGVybi8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.-tZb7r5BXvSxhCgyx7-7lMYTg9-uqRno78zJ8Lvvbjs) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Explains a navigator pattern around NavigationStack, turning destinations and routing decisions into explicit state. Useful for testing deep links, centralizing navigation mutations, and keeping feature views independent of presentation mechanics.
- [Build a 3D Bar Chart in SceneKit With SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2JldHRlcnByb2dyYW1taW5nLnB1Yi9idWlsZC1hLTNkLWJhci1jaGFydC1pbi1zY2VuZWtpdC13aXRoLXN3aWZ0dWktNzg5YTI2MzFlZjZmP2dpPTg1YzdjMDE1YTk1JnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZThjMmRiMDAtOWNjYy00ZDliLWJiOTYtZDFlNjA1NzYxYTk3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhOGIyNTg0LTJhM2MtNDlkNS04ZTc5LTUzNTY3ZTQyNTk2NiIsImlhdCI6MTY3NDA2MjU1OC44NzMsImlzcyI6Im9yY2hpZCJ9.oERc-pJ7HTDhbqnjYoyFf6zEXGXSuMjroDQDR8UEYh8) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Combines SceneKit’s 3D bar geometry with SwiftUI presentation to visualize data interactively. Useful when a chart needs depth, rotation, or custom scene rendering beyond native SwiftUI charts.
- [The Layout Protocol](https://talk.objc.io/episodes/S01E308-the-layout-protocol) — iOS Dev Weekly · Issue 563 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `17th June 2022`
  **NeKI brief:** A new layout system in SwiftUI? I’d be curious to hear what Chris Eidhof and Florian Kugler have to say about that! What’s that? There’s a free 20-minute video on the topic available on their Swift Talk site? That’s handy! 🥰
- [Get More Done Faster with a New Mac Studio Hosted by MacStadium](https://www.macstadium.com/blog/the-new-mac-studio-is-coming-to-macstadium) — iOS Dev Weekly · Issue 562 — Article · Topics: Graphics, Media & Games
  **Published:** `10th June 2022`
  **NeKI brief:** Presents Get More Done Faster with a New Mac Studio Hosted by MacStadium, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [The Talk Show Live From WWDC 2022](https://www.youtube.com/watch?v=WfnvsepVJC0) — iOS Dev Weekly · Issue 562 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `10th June 2022`
  **NeKI brief:** I’ve not watched this as it was only published an hour ago, but it’ll be great, as always! Unless things have changed significantly, it’ll be John Gruber, Craig Federighi, and Greg Joswiak with 90 minutes of additional context about this week.
- [How to Make a Game Like Wordle in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8zMTY2MTI2My1ob3ctdG8tbWFrZS1hLWdhbWUtbGlrZS13b3JkbGUtaW4tc3dpZnR1aS1wYXJ0LW9uZT9oc3NfY2hhbm5lbD10dy04MDg0MzI2MiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fY29udGVudD0yMDg5OTg0MjUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyIiwicG9zdF9pZCI6ImRhYmRkNzEwLWM0MDgtNGFmYS04NDI4LTRlZGUxNWIzMmM3NSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJiOGViODljMC02MGFkLTQ2MjYtODY4Zi1mZWJkNDAzYTdhNzkiLCJpYXQiOjE2NzQwNjI1NTkuMTI5LCJpc3MiOiJvcmNoaWQifQ.hnLhTIeWgfOZ5bBnbKNbq0UhoAvhtPpAB7w93UZfYns) — SwiftUI Weekly · SwiftUI Weekly - Issue #104 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-05-23T22:33:49.000Z`
  **NeKI brief:** Builds a Wordle-style game in SwiftUI, covering tile state, guesses, keyboard input, and feedback. Useful as a concrete exercise in modeling transient game state and composing grid-based UI.
- [Build an Onboarding Flow in SwiftUI with @AppStorage, Transition, Login & Logout](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9eGk5VDhqZjdSWFkiLCJwb3N0X2lkIjoiZGFiZGQ3MTAtYzQwOC00YWZhLTg0MjgtNGVkZTE1YjMyYzc1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImI4ZWI4OWMwLTYwYWQtNDYyNi04NjhmLWZlYmQ0MDNhN2E3OSIsImlhdCI6MTY3NDA2MjU1OS4xMjksImlzcyI6Im9yY2hpZCJ9.akbcSLgLlU5s2GXo_iu6cFB4rQrMCYzqJZjyvqmRbTI) — SwiftUI Weekly · SwiftUI Weekly - Issue #104 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2022-05-23T22:33:49.000Z`
  **NeKI brief:** Constructs an onboarding and authentication flow using @AppStorage, transitions, and login/logout state. Useful for separating persisted session decisions from view presentation while keeping first-run navigation predictable.
- [Running games in the browser with SwiftWasm](https://pyrus.io/2021/05/15/gaming-with-swiftwasm.html) — iOS Dev Weekly · Issue 559 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `20th May 2022`
  **NeKI brief:** Explains Running games in the browser with SwiftWasm, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Sydney CocoaHeads Accessibility Spectacular](https://youtu.be/SKuWLHNHF28?t=2198) — iOS Dev Weekly · Issue 559 — Video · Topics: Accessibility · Developer Community & Business · Objective-C & Cocoa
  **Published:** `20th May 2022`
  **NeKI brief:** Examines This month it’s all about Accessibility. CocoaHeads falls on the same day as Global Accessibility Awareness Day (GAAD). We have 4 amazing speakers lined up:?. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [write your next game for](https://nick.zoic.org/art/writing-an-apple-2-game-in-2021-1) — iOS Dev Weekly · Issue 559 — Article · Topics: Graphics, Media & Games
  **Published:** `20th May 2022`
  **NeKI brief:** write your next game for. This link is retained as a technical reading lead for Apple-platform development.
- [Leveling Up with Progressive Delivery and Observability within Mobile Gaming](https://smartbear.com/resources/white-papers/winning-the-customer-experience-game) — iOS Dev Weekly · Issue 558 — Article · Topics: Graphics, Media & Games
  **Published:** `13th May 2022`
  **NeKI brief:** Examines Get the resources and knowledge you need for all your Software Quality needs in API, Dev, Test, and Ops. Start improving your applications today. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this article from Ariel Michaeli](https://appfigures.com/resources/insights/20220429?f=3) — iOS Dev Weekly · Issue 556 — Article · Topics: Graphics, Media & Games
  **Published:** `29th April 2022`
  **NeKI brief:** Examines News emerged last week that Apple has been emailing developers who haven. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [making YouTube videos](https://www.youtube.com/c/tundsdev) — iOS Dev Weekly · Issue 552 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `1st April 2022`
  **NeKI brief:** Tunde Adegoroye has been making YouTube videos covering Swift development for a while now, and I like his approach in this playlist. Each video covers a single technique, and he’s adding to it daily. Check out some recent ones on button styles or loading…
- [button styles](https://www.youtube.com/watch?v=4AZSLatG2EA) — iOS Dev Weekly · Issue 552 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `1st April 2022`
  **NeKI brief:** Tunde Adegoroye has been making YouTube videos covering Swift development for a while now, and I like his approach in this playlist. Each video covers a single technique, and he’s adding to it daily. Check out some recent ones on button styles or loading…
- [loading spinners](https://www.youtube.com/watch?v=mw8ZRWmhK9E) — iOS Dev Weekly · Issue 552 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `1st April 2022`
  **NeKI brief:** Examines Custom Loading Spinner In SwiftUI with ProgressView And ProgressViewStyle (ProgressView)🤙🏾 Subscribe to the tundsdev YouTube channelhttps://www.youtube.com. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Better performance with canvas in SwiftUI](https://swdevnotes.com/swift/2022/better-performance-with-canvas-in-swiftui) — iOS Dev Weekly · Issue 548 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `4th March 2022`
  **NeKI brief:** Explores Better performance with canvas in SwiftUI, focusing on the article discusses enjoyed this article from eric callanan on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Filtering with the Searchable Modifier](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD90PThzJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj13em9YV2haVUI1byIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.MIRHY06NAcrGpIiXhmfgyOFumNl-UFq7Q2nKMIMwGeY) — SwiftUI Weekly · SwiftUI Weekly - Issue #94 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2022-02-28T09:54:32.000Z`
  **NeKI brief:** Demonstrates searchable-based filtering in SwiftUI, connecting query text to collection results. Useful for building discoverable list search while deciding where normalization, debouncing, and empty-state handling belong.
- [Streaming Coppice Development](https://coppiceapp.com/blog/streaming_coppice_development) — iOS Dev Weekly · Issue 546 — Podcast · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `18th February 2022`
  **NeKI brief:** Examines Streaming Coppice Development - Blog - M Cubed Software. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [swift-add](https://github.com/subdigital/swift-add) — iOS Dev Weekly · Issue 546 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `18th February 2022`
  **NeKI brief:** While I’m on the subject, I believe that Ben Scheirman is also streaming the development of swift-add (amongst other things) on Twitch.
- [Videos from iOS Conf SG 2022](https://www.youtube.com/playlist?list=PLED4k3CZkY9R9mhRW5V74gS9cVTp28CbK) — iOS Dev Weekly · Issue 544 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `4th February 2022`
  **NeKI brief:** Examines iOS Conf SG is the largest iOS developer conference in Southeast Asia. Every year the event is attended by hundreds of developers around the world. 2022 was. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building a Better Blur](https://www.youtube.com/watch?v=ymCXsPwg8G8) — iOS Dev Weekly · Issue 540 — Video · Topics: Graphics, Media & Games
  **Published:** `7th January 2022`
  **NeKI brief:** This video from Ben Sandofsky is a must-watch. Concise and extremely well explained.
- [Building a Camera App With SwiftUI and Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8yNjI0NDc5My1idWlsZGluZy1hLWNhbWVyYS1hcHAtd2l0aC1zd2lmdHVpLWFuZC1jb21iaW5lP3V0bV9jYW1wYWlnbj1idWZmZXImdXRtX2NvbnRlbnQ9YnVmZmVyZDA5NDUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyLmNvbSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.EYtjzcEt9k9qHn7Q5bQvobwNg9NVsUag7xF3x7v0QKc) — SwiftUI Weekly · SwiftUI Weekly - Issue #83 — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `2021-11-15T14:19:45.000Z`
  **NeKI brief:** Builds a camera experience by bridging capture APIs into SwiftUI with Combine-backed state. Useful for understanding preview integration, authorization, capture events, and lifecycle management around UIKit services.
- [Getting Started with Swift Concurrency](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1VNmxRdXN0aVRHRSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.b6NKewbwPA4mJtumWudUDdzfNgnrnE7GRvN53k3htnk) — SwiftUI Weekly · SwiftUI Weekly - Issue #83 — Tutorial · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `2021-11-15T14:19:45.000Z`
  **NeKI brief:** Introduces Swift concurrency concepts and basic async code through practical examples. Useful for understanding async/await, task structure, and the migration mindset before applying concurrency to SwiftUI features.
- [Refactoring an app to use the latest SwiftUI and async/await](https://www.youtube.com/watch?v=U3tKbUX_UVA) — iOS Dev Weekly · Issue 532 — Video · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `5th November 2021`
  **NeKI brief:** Examines In this video, we are going to update the MovieDB App that we have built last year with the initial release of SwiftUI on iOS 13.#swiftui #ios15 #iosdevelopm. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How does Homebrew work with Rosetta on M1 machines?](https://www.youtube.com/watch?v=EG-K5n20_HQ) — iOS Dev Weekly · Issue 531 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `29th October 2021`
  **NeKI brief:** You probably don’t need as elaborate a brew setup as Josh Holtz does, being the lead maintainer of fastlane, but that doesn’t mean you won’t learn plenty from this half-hour video and associated blog post. I learned plenty about Rosetta from watching this…
- [associated blog post](https://www.joshholtz.com/blog/2021/10/27/joshs-m1-development-environemnt.html) — iOS Dev Weekly · Issue 531 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `29th October 2021`
  **NeKI brief:** Examines This is the setup I’m using on my M1 Mac (and Rosetta) to handle homebrew, zsh, Ruby and python version managers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Keeping WWDC videos and sample code current](https://dimsumthinking.com/Blog/2021/08/30-KeepingCurrent.html) — iOS Dev Weekly · Issue 523 — Article · Topics: Apple Platform Ecosystem · Concurrency · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Keeping WWDC videos and sample code current, focusing on here’s another advantage of not having on-stage presentations at wwdc.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Beauty of Bézier Curves](https://www.youtube.com/watch?v=aVwxzDHniEw) — iOS Dev Weekly · Issue 522 — Video · Topics: Graphics, Media & Games
  **Published:** `27th August 2021`
  **NeKI brief:** This video from Freya Holmér is wonderful and explains everything you could ever need to know about Bézier curves. It’s also part of the reason today’s newsletter is so late! 😅
- [infinite edge](https://youtu.be/E3gS9tjACwU?t=323) — iOS Dev Weekly · Issue 521 — Video · Topics: Graphics, Media & Games
  **Published:** `20th August 2021`
  **NeKI brief:** The YouTube video presents the referenced infinite-edge topic and is publicly viewable at the linked timestamp.
- [Why TikTok Is a Great Place for Marketing Your App](https://www.youtube.com/watch?v=hhSRx2p2COQ) — iOS Dev Weekly · Issue 520 — Video · Topics: Graphics, Media & Games
  **Published:** `13th August 2021`
  **NeKI brief:** When someone says “social media marketing”, if you’re anything like me, you think about Twitter and then stop. What about Instagram? Spanchat? TikTok!? 😅 I found this conversation with Maddie Kirby interesting where she talks about social media marketing for…
- [Watch full video on Youtube (6 min)](https://www.youtube.com/watch?v=YeGVrZJj-Mg&ref=ioscodereview.com) — iOS Code Review · Issue 4 — Video · Topics: Graphics, Media & Games
  **Published:** `2021-08-05T14:19:35.000Z`
  **NeKI brief:** Records Watch full video on Youtube (6 min) as a visual walkthrough relevant to Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Testing your mobile app internally isn’t enough to ensure its quality](https://instabug.com/product/app-performance-monitoring) — iOS Dev Weekly · Issue 517 — Article · Topics: Graphics, Media & Games · Performance · Testing
  **Published:** `23rd July 2021`
  **NeKI brief:** Explores Testing your mobile app internally isn’t enough to ensure its quality, focusing on whether it’s a crash, slow screen transitions, slow network calls. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Protocols in Gradient and Chroma Game](https://rudrank.blog/protocols-in-gradient-game) — iOS Dev Weekly · Issue 515 — Article · Topics: Concurrency · Graphics, Media & Games
  **Published:** `9th July 2021`
  **NeKI brief:** Explores Protocols in Gradient and Chroma Game, focusing on the article discusses really liked this story of refactoring an. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Xcode 13 vim Mode](https://nsscreencast.com/episodes/491-xcode-13-vim) — iOS Dev Weekly · Issue 512 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `18th June 2021`
  **NeKI brief:** Presents Xcode 13 vim Mode, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [NukeUI and LazyImage](https://kean.blog/post/lazy-image) — iOS Dev Weekly · Issue 510 — Article · Topics: Graphics, Media & Games
  **Published:** `4th June 2021`
  **NeKI brief:** I’ve linked to Nuke in the past, and now Alex Grebenyuk is following it up with a UI library. You might think that a control called LazyImage would be only about images, but it also supports videos! If you care about loading resources in a performant way…
- [AASA File Identifiers](https://lickability.com/blog/insidious-bugs-number-3-apple-app-site-association-file) — iOS Dev Weekly · Issue 509 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `28th May 2021`
  **NeKI brief:** We recently struggled with AASA while trying to make the SPI Playgrounds app respond to URLs. Documentation is sparse and spread over multiple WWDC videos, and we eventually decided not to implement it. So, I read this story from Michael Amundsen with…
- [Gradient Meshes in SceneKit](https://movingparts.io/gradient-meshes) — iOS Dev Weekly · Issue 508 — Article
  **Published:** `21st May 2021`
  **NeKI brief:** Presents Gradient Meshes in SceneKit, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [this YouTube channel](https://www.youtube.com/channel/UCOYNV2EifmBprMdSESVEu9g/videos) — iOS Dev Weekly · Issue 505 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `30th April 2021`
  **NeKI brief:** Explores this YouTube channel, focusing on the article discusses lost about two hours yesterday to this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [this video introducing Project Builder](https://www.youtube.com/watch?v=EQC9vXEFWkM) — iOS Dev Weekly · Issue 505 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `30th April 2021`
  **NeKI brief:** I lost about two hours yesterday to this tweet from Davide Di Stefano. Xcode 2 was the first version I used, but this video of Xcode 3 from Kevin Vinck took me on a delightful trip down memory lane, which ended in finding this YouTube channel and this video…
- [the video](https://vimeo.com/366398) — iOS Dev Weekly · Issue 505 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `30th April 2021`
  **NeKI brief:** By the way, my favourite parts of the video were the warning about forgetting to save the IB file before building in Xcode and being tripped up by the text field cell inside the text field. Ah, memories!
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Introduces Combine publishers, subscribers, and operators through practical examples. Follow it when maintaining pre-concurrency SwiftUI code or bridging publisher pipelines into newer async/await boundaries.
- [in video form](https://vimeo.com/536908653) — iOS Dev Weekly · Issue 504 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `23rd April 2021`
  **NeKI brief:** Explores in video form, focusing on i’m not sure i know anyone who cares quite as. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How to Design a Great App Icon](https://www.shopify.ie/partners/blog/app-icon) — iOS Dev Weekly · Issue 504 — Article · Topics: Graphics, Media & Games
  **Published:** `23rd April 2021`
  **NeKI brief:** If you read one article this week, let it be this one from Michael Flarup. It’s a masterclass on both process and technique. I especially enjoyed this video that’s squeezed in half way through the article. There’s so much good stuff here.
- [More Efficient/Faster Average Color of Image](https://christianselig.com/2021/04/efficient-average-color) — iOS Dev Weekly · Issue 502 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `9th April 2021`
  **NeKI brief:** Examines Calculating the average color for an image has lots of uses, this post goes over ways you can do this. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Figma design](https://www.figma.com/file/8DwfJi51F88IW1xNVrDMP4/Clubapartment) — iOS Dev Weekly · Issue 497 — Article · Topics: Graphics, Media & Games
  **Published:** `5th March 2021`
  **NeKI brief:** Links to a public Figma design file for inspecting the referenced interface concepts. Useful for visual design review and handoff discussion, subject to current sharing permissions.
- [source code](https://github.com/FranckNdame/swiftui.builds/tree/master/clubhouse) — iOS Dev Weekly · Issue 497 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `5th March 2021`
  **NeKI brief:** Examines building cool stuff with swiftui. Contribute to FranckNdame/swiftui.builds development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Build Complete Apple Watch Tasks App Clone in WatchOS, SwiftUI with CoreData](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9OVFxdzU5NXFkY0UiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.WcabseSQh2BOGdp0_x6eltLYiVZeTSCbK1h_Kcxqhs4) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Tutorial · Topics: Core Data · Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Builds a watchOS task app clone using SwiftUI and Core Data. Follow it for compact-device navigation, persistence modeling, and the differences between watch extension UI constraints and iPhone screens.
- [Using UIKit Components in SwiftUI (Coordinators)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9V29KdHJsREJseVkiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.61EuLk6HarMsg30D45ewI7xYWDhIoZOmzg6CjyKYvDE) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Demonstrates using UIKit components from SwiftUI through representable wrappers and coordinators. Use it when incrementally migrating screens while preserving delegate-driven controls and imperative lifecycle behavior.
- [AutomaticSettings](https://github.com/krzysztofzablocki/AutomaticSettings) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Examines AutomaticSettings, focusing on this new library from krzysztof zabłocki is interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [intro video](https://www.youtube.com/watch?v=MTY9m2--tiA) — iOS Dev Weekly · Issue 489 — Video · Topics: Foundation & Data Formats · Graphics, Media & Games · Swift
  **Published:** `8th January 2021`
  **NeKI brief:** Provides the linked introductory technical video referenced by the issue. Useful as audiovisual context for the surrounding topic, while any API or implementation claims should be verified against primary documentation.
- [this fascinating video](https://www.youtube.com/watch?v=YGVfwEEjRfs) — iOS Dev Weekly · Issue 489 — Video · Topics: Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Links to the issue’s referenced technical video and preserves its original presentation context. Useful for following a demonstration that is difficult to capture in a short newsletter note, with details checked independently before implementation.
- [Yes, it’s the full thing. I’m sorry](https://github.com/felixrieseberg/macintosh.js) — iOS Dev Weekly · Issue 488 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `1st January 2021`
  **NeKI brief:** Examines Yes, it’s the full thing. I’m sorry, focusing on how do you record videos of your apple watch apps? you have the watch on your wrist, tap the screen with your other hand,…. Use it as a focused research reference for related Apple-platform work.
- [the video](https://www.youtube.com/watch?v=EMQwm5E1xfE) — iOS Dev Weekly · Issue 488 — Video · Topics: Graphics, Media & Games
  **Published:** `1st January 2021`
  **NeKI brief:** the video. This link is retained as a technical reading lead for Apple-platform development.
- [SwiftCamera: The source project for the SwiftCamera tutorial](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vcm9yb2RyaWd1ZXoxMTYvU3dpZnRDYW1lcmE_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjN2YyODU5OC04ODgxLTRiOTQtYTM0MC00MDkyYTA5NzI4NDAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNmQzODZmMTYtMDc2Zi00YjNkLWE4OWQtNTFmZWUwMDQ2NmM2IiwiaWF0IjoxNjc0MDYyNzM2LjgxNiwiaXNzIjoib3JjaGlkIn0.NmimYkKoustjVoU5_ZFzajEkdlaWS9ctJUv9ZJ8dgmI) — SwiftUI Weekly · SwiftUI Weekly - Issue #33 — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2020-10-27T16:57:07.000Z`
  **NeKI brief:** Provides source for a SwiftCamera tutorial project. Use it to inspect camera-session setup, preview integration, and capture flow as a concrete UIKit or SwiftUI interoperability reference.
- [the marketing page for Phoenix2](https://www.firigames.com/phoenix2) — iOS Dev Weekly · Issue 479 — Article · Topics: Graphics, Media & Games
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines Phoenix 2 is a blistering arcade shoot'em up where you battle waves of Invaders in daily new missions. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building GitHub Mobile](https://www.youtube.com/watch?v=nBsa5N1LZPk) — iOS Dev Weekly · Issue 479 — Video · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines Ryan Nystrom is a Director of Engineering at GitHub where he's supporting several teams building mobile and desktop apps. In this episode we discussed a broa. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [new YouTube channel](https://www.youtube.com/channel/UCN0yF6AaJmqiPYXDz0CDfxA) — iOS Dev Weekly · Issue 479 — Video · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `23rd October 2020`
  **NeKI brief:** This new YouTube channel from Sash Zats is great. It’s interviews with app builders, telling their stories. I enjoyed this episode with Ryan Nystrom talking about GitHub Mobile, and of course, GitHawk!
- [GitHawk](https://github.com/GitHawkApp/GitHawk) — iOS Dev Weekly · Issue 479 — Source repository · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines The (second) best iOS app for GitHub. Contribute to GitHawkApp/GitHawk development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Parma](https://github.com/dasautoooo/Parma) — iOS Dev Weekly · Issue 470 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `21st August 2020`
  **NeKI brief:** Examines Parma, focusing on markdown rendering engine, using swiftui views? that sounds interesting! that’s what leonard chan has created here. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [What’s New in Unit Testing?](https://qualitycoding.org/wwdc20-unit-testing) — iOS Dev Weekly · Issue 464 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `10th July 2020`
  **NeKI brief:** Reviews the unit-testing changes presented at WWDC 2020 and connects them to practical Xcode test workflows. Follow it when maintaining older XCTest infrastructure and checking which release-era features can simplify test organization or diagnostics.
- [SwiftUI Grids](https://nsscreencast.com/episodes/445-swiftui-grids) — iOS Dev Weekly · Issue 462 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines SwiftUI Grids, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [short video showing how it works](https://www.youtube.com/watch?v=LGCcIsCDGkU) — iOS Dev Weekly · Issue 460 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th June 2020`
  **NeKI brief:** There are plenty of apps (both native, and web) that’ll help you dress up your app’s screenshots for your App Store listing, but not many that’ll do the same for your preview video. The best way to get up to speed here is to watch this short video showing…
- [Building a view debugger using SceneKit](https://www.youtube.com/watch?v=S6YN2Bsde_Q) — iOS Dev Weekly · Issue 459 — Video · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2020`
  **NeKI brief:** Examines Building a view debugger using SceneKit, focusing on at first glance, you might think the title of this talk from indragie karunaratne is a mistake… scenekit!? to build a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [Parsing natural languages in Swift](https://www.youtube.com/watch?v=BPEJ8Nif12E) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `5th June 2020`
  **NeKI brief:** Examines try! Swift NYC Conference 2019 - try! Swift is an immersive community gathering about Apple Technologies, Swift Language Best Practices, Application Developm. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift Techniques for Testing](https://www.youtube.com/watch?v=Or6xjaCUCd4) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games · Swift · Testing
  **Published:** `5th June 2020`
  **NeKI brief:** Examines Swift Techniques for Testing, focusing on the author’s note that liked the testing techniques in this video from kaya thomas. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Bring me to life](https://www.youtube.com/watch?v=p-dvAOHlLEc) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games
  **Published:** `5th June 2020`
  **NeKI brief:** The YouTube page provides the publicly viewable video Bring me to life together with its video metadata.
- [Integrating SwiftUI & UIKit](https://www.youtube.com/watch?v=ssz02HMEoR0) — iOS Dev Weekly · Issue 459 — Video · Topics: Swift · SwiftUI · UIKit
  **Published:** `5th June 2020`
  **NeKI brief:** Examines Integrating SwiftUI & UIKit, focusing on what happens when you hit the edge of what swiftui is capable of? uikit saves the day! or, what happens when you’ve got…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [Advanced Colors](https://www.youtube.com/watch?v=r67wKzRViio) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games
  **Published:** `5th June 2020`
  **NeKI brief:** We should talk more about colour, UIColor! 😂 Listen to Neha Kulkarni teach you everything from why you should think carefully about colours, how to standardise them across your app, and even why you might want to update them dynamically.
- [Swift Without Screens - Powering Connected Devices](https://www.youtube.com/watch?v=VILUaec-sCs) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `5th June 2020`
  **NeKI brief:** Let’s finish with Marc Aupont taking Swift off the devices made by the company in California, and on to a computer that’s so small and widely available it can go almost anywhere. The Raspberry Pi.
- [Dealing with memory limits in iOS app extensions](https://blog.kulman.sk/dealing-with-memory-limits-in-app-extensions) — iOS Dev Weekly · Issue 458 — Article · Topics: App Services & Extensions · Graphics, Media & Games · Personal Essays
  **Published:** `29th May 2020`
  **NeKI brief:** Examines In the iOS app I currently work on there is a Notification Service Extension and a Share Extension. Both extensions have been implemented quite some time age and have been working. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Videos from App Builders 2020](https://www.youtube.com/playlist?list=PLLcE3DL3f5ByDAucPjzNRG_hPtYDvYlIA) — iOS Dev Weekly · Issue 457 — Video · Topics: Accessibility · Developer Community & Business · Graphics, Media & Games
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines App Builders 2020 - YouTube. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Lea Marolt Sonnenschein](https://www.youtube.com/watch?v=t5UYlyYSf60) — iOS Dev Weekly · Issue 457 — Video · Topics: Accessibility · Developer Community & Business · Graphics, Media & Games
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Auf YouTube findest du die angesagtesten Videos und Tracks. Außerdem kannst du eigene Inhalte hochladen und mit Freunden oder gleich der ganzen Welt teilen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [John Fox](https://www.youtube.com/watch?v=N_QjBc_Zuts) — iOS Dev Weekly · Issue 457 — Video · Topics: Accessibility · Developer Community & Business · Graphics, Media & Games
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Auf YouTube findest du die angesagtesten Videos und Tracks. Außerdem kannst du eigene Inhalte hochladen und mit Freunden oder gleich der ganzen Welt teilen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Matthew Bischoff](https://www.youtube.com/watch?v=1g78NWM_GIM) — iOS Dev Weekly · Issue 457 — Video · Topics: Accessibility · Developer Community & Business · Graphics, Media & Games
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Auf YouTube findest du die angesagtesten Videos und Tracks. Außerdem kannst du eigene Inhalte hochladen und mit Freunden oder gleich der ganzen Welt teilen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [spoke on this subject recently](https://engineers.sg/video/designing-your-app-to-be-discoverable-ios-conf-sg-2020--3930) — iOS Dev Weekly · Issue 456 — Article · Topics: Graphics, Media & Games
  **Published:** `15th May 2020`
  **NeKI brief:** Explains spoke on this subject recently, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [this walkthrough video](https://www.pointfree.co/episodes/ep100-a-tour-of-the-composable-architecture-part-1) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** A free tour of the newly open-sourced Composable Architecture that builds an application while introducing its state-management model. Useful for assessing the framework from a concrete implementation rather than only its API surface or architectural claims.
- [this article from John Gruber](https://daringfireball.net/2020/04/amazon_apple_prime_video) — iOS Dev Weekly · Issue 450 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd April 2020`
  **NeKI brief:** Discusses this article from John Gruber, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Getting Started with Combine and SwiftUI in iOS](https://www.youtube.com/watch?v=fwXv7y2XkDQ) — iOS Dev Weekly · Issue 449 — Video · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `27th March 2020`
  **NeKI brief:** Join Scott Gardner for a few hours with a recording of the workshop he was due to give at the postponed AppDevCon, which was instead streamed it to a small online audience. Or, if you don’t quite have that amount of time, you might enjoy the talk he had…
- [talk he had planned](https://www.youtube.com/watch?v=r7ef2W3kevY) — iOS Dev Weekly · Issue 449 — Video · Topics: Graphics, Media & Games
  **Published:** `27th March 2020`
  **NeKI brief:** Join Scott Gardner for a few hours with a recording of the workshop he was due to give at the postponed AppDevCon, which was instead streamed it to a small online audience. Or, if you don’t quite have that amount of time, you might enjoy the talk he had…
- [Videos from dotSwift 2020](https://www.dotconferences.com/conference/dotswift-2020) — iOS Dev Weekly · Issue 443 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `14th February 2020`
  **NeKI brief:** Examines Are you looking to attend, speak or sponsor a tech conference in Europe ? You. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Videos from SwiftConf 2019](https://www.youtube.com/playlist?list=PLgUjQUYKwG_jZ27Ian38aeDu5wHjx95vt) — iOS Dev Weekly · Issue 443 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `14th February 2020`
  **NeKI brief:** More videos! This time from SwiftConf back in August last year.
- [Upsampling in Core ML](https://machinethink.net/blog/coreml-upsampling) — iOS Dev Weekly · Issue 442 — Article · Topics: Graphics, Media & Games
  **Published:** `7th February 2020`
  **NeKI brief:** In these days where even videos from 1896 can be upscaled successfully it might be worth knowing a bit more about how it’s done. Honestly, this article from Matthijs Hollemans is probably a bit niche, but I really enjoyed it so here it is!
- [videos from 1896 can be upscaled successfully](https://arstechnica.com/science/2020/02/someone-used-neural-networks-to-upscale-a-famous-1896-video-to-4k-quality) — iOS Dev Weekly · Issue 442 — Article · Topics: Graphics, Media & Games
  **Published:** `7th February 2020`
  **NeKI brief:** Examines Machine-learning software fills in missing details to produce realistic images. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Re-creating Instagram in SwiftUI](https://www.youtube.com/watch?v=APxrtnxRzwI) — iOS Dev Weekly · Issue 441 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `31st January 2020`
  **NeKI brief:** Examines CocoaHeads Utah ValleyDave DeLongSwiftUIJanuary 16, 2020venue sponsor: DevMountain Coding Bootcampmedia sponsor: ClearVision Reservesponsor: utahdevelopers.o. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [part 2](https://www.youtube.com/watch?v=BiNYCvL1m94) — iOS Dev Weekly · Issue 441 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `31st January 2020`
  **NeKI brief:** The YouTube page provides the publicly viewable second part of the referenced developer talk and its video metadata.
- [this piece](https://www.polygon.com/2020/1/13/21064100/vvvvvv-source-code-game-development-terry-cavanagh-release) — iOS Dev Weekly · Issue 439 — Article · Topics: Graphics, Media & Games
  **Published:** `17th January 2020`
  **NeKI brief:** The article covers the release of VVVVVV's source code and discusses Terry Cavanagh's game-development process and open-source decision.
- [Exploring SwiftUI Apple Watch Performance](https://david-smith.org/blog/2020/01/07/exploring-swiftui-apple-watch-performance) — iOS Dev Weekly · Issue 438 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `10th January 2020`
  **NeKI brief:** Examines Exploring SwiftUI Apple Watch Performance, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Videos from ServerSide.swift 2019](https://www.serversideswift.info/2019/videos) — iOS Dev Weekly · Issue 435 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** After my comment today, it might be the perfect time to dive into learning some server-side Swift. How about doing that with these videos from the Server-side Swift conference.
- [Server-side Swift conference](https://www.serversideswift.info/2019) — iOS Dev Weekly · Issue 435 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** After my comment today, it might be the perfect time to dive into learning some server-side Swift. How about doing that with these videos from the Server-side Swift conference.
- [Videos from iOSDevCampDC 2019](https://www.youtube.com/playlist?list=PLhZ07fUym-oVMUC3G-0YwyZHa0ESiXIZs) — iOS Dev Weekly · Issue 434 — Video · Topics: Graphics, Media & Games
  **Published:** `13th December 2019`
  **NeKI brief:** Examines iOSDevCampDC 2019 - YouTube. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Saliency Analysis with the Vision framework](https://www.raywenderlich.com/5807038-saliency-analysis-in-ios-using-vision) — iOS Dev Weekly · Issue 433 — Article · Topics: Graphics, Media & Games
  **Published:** `6th December 2019`
  **NeKI brief:** Covers Saliency Analysis with the Vision framework, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Videos from Mobile Era 2019](https://www.youtube.com/playlist?list=PL2zqcEUyHqWjqzWHBQQl_78IvDyhqZ9Ir) — iOS Dev Weekly · Issue 432 — Video · Topics: Graphics, Media & Games
  **Published:** `29th November 2019`
  **NeKI brief:** Were you in Oslo at the start of November for Mobile Era? If, like me, you were not lucky enough to be there, at least you get to catch up with the videos! 🙌
- [1](https://www.pointfree.co/episodes/ep80-the-combine-framework-and-effects-part-1) — iOS Dev Weekly · Issue 431 — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `22nd November 2019`
  **NeKI brief:** The Point-Free episode introduces effects in the Combine framework and discusses modeling asynchronous work in Swift applications.
- [2](https://www.pointfree.co/episodes/ep81-the-combine-framework-and-effects-part-2) — iOS Dev Weekly · Issue 431 — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `22nd November 2019`
  **NeKI brief:** I really liked this free two-part (1, 2) video from Brandon Williams and Stephen Celis where they demonstrate and explain Combine. There’s also links to their free series (1, 2, 3) of videos on SwiftUI as well! 👍
- [3](https://www.pointfree.co/episodes/ep67-swiftui-and-state-management-part-3) — iOS Dev Weekly · Issue 431 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `22nd November 2019`
  **NeKI brief:** The Point-Free episode discusses SwiftUI state management and provides a concrete third-part tutorial on modeling state in Swift applications.
- [Swift 5’s Result Type](https://nsscreencast.com/episodes/417-swift-5-result-type) — iOS Dev Weekly · Issue 430 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `15th November 2019`
  **NeKI brief:** Ben Scheirman with the clearest walk through of Swift’s Result type that I’ve ever seen. 👍
- [Videos from MobileOptimized 2019](https://www.youtube.com/playlist?list=PLpVeA1tdgfCDNHTdDiHaX1enGUTtPWxbA) — iOS Dev Weekly · Issue 430 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `15th November 2019`
  **NeKI brief:** The YouTube playlist collects publicly viewable MobileOptimized 2019 talks and their associated session information.
- [A class-dump in 2019](https://www.youtube.com/watch?v=KCxXPhu3S7o) — iOS Dev Weekly · Issue 429 — Video · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `8th November 2019`
  **NeKI brief:** Presents a class-dump workflow from 2019, useful for understanding how developers inspect compiled Apple-platform interfaces and runtime information. Treat the historical tooling details as version-specific and validate current alternatives before applying them.
- [Advanced Apple Debugging & Reverse Engineering](https://store.raywenderlich.com/products/advanced-apple-debugging-and-reverse-engineering) — iOS Dev Weekly · Issue 429 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `8th November 2019`
  **NeKI brief:** Introduces a practical book on Apple-platform debugging and reverse engineering, covering inspection techniques beyond ordinary source-level debugging. Useful as a structured learning route when diagnosing frameworks, binaries, and runtime behavior.
- [a talk of mine](https://www.youtube.com/watch?v=HbQVY2hfAEY) — iOS Dev Weekly · Issue 427 — Video · Topics: Graphics, Media & Games
  **Published:** `25th October 2019`
  **NeKI brief:** There’s even a talk of mine in here if you look carefully. 🙈
- [How to build a UICollectionView like the App Store](https://www.youtube.com/watch?v=SR7DtcT61tA) — iOS Dev Weekly · Issue 426 — Video · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `18th October 2019`
  **NeKI brief:** Paul Hudson doing a video that isn’t about SwiftUI? Oh yes! This is a fantastic guide to the new collection view APIs introduced at this year’s WWDC. If you haven’t looked at the changes yet, this is a great way to catch up.
- [Videos from NSSpain 2019](https://vimeo.com/nsspain) — iOS Dev Weekly · Issue 425 — Video · Topics: Graphics, Media & Games
  **Published:** `11th October 2019`
  **NeKI brief:** The Vimeo profile collects publicly viewable NSSpain conference recordings and exposes their video descriptions without authentication.
- [SwiftUI by Example](https://www.hackingwithswift.com/quick-start/swiftui) — iOS Dev Weekly · Issue 422 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `20th September 2019`
  **NeKI brief:** Covers SwiftUI by Example, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [new set of 14 videos](https://www.youtube.com/playlist?list=PLuoeXyslFTubw4NtepDCis5tTqK37zT3Q) — iOS Dev Weekly · Issue 422 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `20th September 2019`
  **NeKI brief:** Examines new set of 14 videos, focusing on the author’s discussion of linked to this before, but since paul hudson has been through it and updated every bit of it for the xcode 11 gm seed,…. Use it as a focused research reference for related Apple-platform work, and.
- [by conference](https://learntalks.com/categories) — iOS Dev Weekly · Issue 422 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `20th September 2019`
  **NeKI brief:** There’s conference talks, meetup talks, and presentations of all kinds covering iOS development here. List talks by year, by conference or just search for something specific.
- [Videos from Swift TO](https://vimeo.com/showcase/swiftto-conf-2019) — iOS Dev Weekly · Issue 418 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `23rd August 2019`
  **NeKI brief:** Conference videos time! This set is from the Swift TO conference that happened just last week in Toronto! I saw plenty of tweets about it as it was happening, now it’s time to catch up with the content. 🚀
- [Learn how to create custom UIs and animations in SwiftUI](https://designcode.io/swiftui?promo=learnswiftui) — iOS Dev Weekly · Issue 417 — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `16th August 2019`
  **NeKI brief:** Examines Learn how to create custom UIs and animations in SwiftUI, focusing on 6-hour video course teaching design, coding custom user interfaces and animated interactions for ios 13. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [An Illustrated History of Easter Eggs](https://www.youtube.com/watch?v=fAaqSr-yShc) — iOS Dev Weekly · Issue 415 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `2nd August 2019`
  **NeKI brief:** If you didn’t spot this in and amongst the videos from Hacking with Swift Live a couple of weeks ago, it felt like such a great fit for a link by itself right here. 👍
- [Hacking with Swift Live](https://www.hackingwithswift.com/live) — iOS Dev Weekly · Issue 413 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `19th July 2019`
  **NeKI brief:** Covers Hacking with Swift Live, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Ive had enough of this place!](http://scoopland.wpengine.com/jony-ive-i-had-it-up-to-here-with-this-place) — iOS Dev Weekly · Issue 412 — Article · Topics: Graphics, Media & Games
  **Published:** `12th July 2019`
  **NeKI brief:** Examines Cupertino — First came frustration. Then mind-numbing boredom. And finally, excruciating torture. According to the legendary recently-resigned Chief of Design, 27 years inside Appl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Auto Layout: WTF to FTW](https://www.rightpoint.com/rplabs/2019/06/wtf-auto-layout-for-ios-in-swift) — iOS Dev Weekly · Issue 411 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `5th July 2019`
  **NeKI brief:** The historical Auto Layout article now redirects to a general Rightpoint thought page. Useful as a destination-change record, not as verified standalone Auto Layout guidance.
- [RetroRampage](https://github.com/nicklockwood/RetroRampage) — iOS Dev Weekly · Issue 411 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `5th July 2019`
  **NeKI brief:** Examines RetroRampage, focusing on finally with a welcome break from swiftui hot takes is this tutorial series from nick lockwood on how to implement a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AltConf 2019 Videos](https://www.youtube.com/playlist?list=PLljEvxF6pJBBSQXDRnQvACukLJGybS17O) — iOS Dev Weekly · Issue 411 — Video · Topics: Graphics, Media & Games
  **Published:** `5th July 2019`
  **NeKI brief:** I’m not sure this is every session video from this year’s AltConf, but it’s certainly enough to get you started. There’s 29 sessions already uploaded at the time of writing. 📺
- [YouTube playlist](https://www.youtube.com/playlist?list=PLdr22uU_wISr-FYeKblv3LMe_kHFzRFBw) — iOS Dev Weekly · Issue 409 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `21st June 2019`
  **NeKI brief:** Examines UIKonf 2019 - YouTube. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [publishing videos](https://www.youtube.com/channel/UC18tEI7YdUtg4bL9yxv1Xjg/videos) — iOS Dev Weekly · Issue 409 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `21st June 2019`
  **NeKI brief:** I only recently realised that the San Francisco Swift Language User Group were still publishing videos after the hosting and publishing situation changed a bit. Here’s a great reminder from J.P. Simard that they exist.
- [interview with me](https://wwdcbysundell.com/2019/interviews/dave-verwer) — iOS Dev Weekly · Issue 406 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `31st May 2019`
  **NeKI brief:** Or, maybe none of that is possible this year and you’re going to be following along completely remotely. There will be plenty coverage from the session videos, and on Twitter, but one site that I’ll call out specifically is WWDC by Sundell. Yes, that’s a new…
- [Senator Hawley announces bill banning loot boxes, pay-to-win mechanics](https://arstechnica.com/gaming/2019/05/senator-hawley-announces-bill-banning-loot-boxes-pay-to-win-mechanics) — iOS Dev Weekly · Issue 403 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `10th May 2019`
  **NeKI brief:** Examines Game developers shouldn’t be allowed to monetize addiction," Mo. Republican says. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Free weekend at raywenderlich.com](https://www.raywenderlich.com/3068730-free-weekend-at-raywenderlich-com-until-sunday-may-5) — iOS Dev Weekly · Issue 402 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `3rd May 2019`
  **NeKI brief:** Presents Free weekend at raywenderlich.com, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Designing App Icons](https://applypixels.com/class/designing-app-icons) — iOS Dev Weekly · Issue 402 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `3rd May 2019`
  **NeKI brief:** Examines ## About This Class Join designer Michael Flarup on a journey of how to create the single most important visual aspect of your product: ***the app icon***. A beautiful, identifiabl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [squircle](https://en.wikipedia.org/wiki/Squircle) — iOS Dev Weekly · Issue 402 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `3rd May 2019`
  **NeKI brief:** Designing app icons is different from designing web sites, logos, and almost every other type of design. Making your app stand out in a squircle shaped package is a unique skill so Michael Flarup has put together almost 2 hours of video tutorials on how to…
- [Rightpoint is hiring iOS Developers at all levels](http://app.jobvite.com/m?3VFFokws=) — iOS Dev Weekly · Issue 401 — Article · Topics: Developer Career & Practice · Graphics, Media & Games
  **Published:** `26th April 2019`
  **NeKI brief:** Examines Genpact Careers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Designing APIs](https://www.swiftbysundell.com/posts/designing-swift-apis) — iOS Dev Weekly · Issue 400 — Article · Topics: Code Quality · Objective-C & Cocoa · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** Explains Designing APIs, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Videos from CodeMobile 2019](https://www.youtube.com/playlist?list=PLmEZjI7vcqES-hEaDBXVFtyJ_5mUa0umr) — iOS Dev Weekly · Issue 399 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `12th April 2019`
  **NeKI brief:** Last week saw the third edition of the CodeMobile conference, and already we have all of the videos published and ready to watch! 👍
- [Core Image Filter Reference](https://noahgilmore.com/blog/cifilterio) — iOS Dev Weekly · Issue 398 — Article · Topics: Graphics, Media & Games
  **Published:** `5th April 2019`
  **NeKI brief:** Presents Core Image Filter Reference, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Conferences.digital](https://github.com/zagahr/Conferences.digital) — iOS Dev Weekly · Issue 395 — Source repository · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `15th March 2019`
  **NeKI brief:** Examines 👨‍💻Watch the latest and greatest conference videos on your Mac - GitHub - zagahr/Conferences.digital: 👨‍💻Watch the latest and greatest conference videos on your Mac. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Nintendo Asks Mobile Developers to Curb Microtransactions](https://variety.com/2019/gaming/news/nintendo-mobile-microtransactions-1203156557) — iOS Dev Weekly · Issue 394 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `8th March 2019`
  **NeKI brief:** Reports Nintendo’s approach to mobile-game monetization and its request to curb aggressive microtransactions. Useful product context for discussing revenue design and user trust, not as an implementation guide.
- [Videos from ServerSide.swift](https://www.serversideswift.info/videos) — iOS Dev Weekly · Issue 394 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Covers Videos from ServerSide.swift, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [dotSwift 2019 Videos](https://www.dotconferences.com/conference/dotswift-2019) — iOS Dev Weekly · Issue 393 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `1st March 2019`
  **NeKI brief:** Explains dotSwift 2019 Videos, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Part 1](https://www.youtube.com/watch?v=7HgbcTqxoN4) — iOS Dev Weekly · Issue 391 — Video · Topics: Graphics, Media & Games · Navigation & Deep Linking
  **Published:** `15th February 2019`
  **NeKI brief:** Paul Hudson on a topic that comes up quite regularly, the coordinator pattern. Presented both as a blog post, and as a two part video (Part 1, Part 2), this is really everything you’ll need to know on the subject.
- [Part 2](https://www.youtube.com/watch?v=ueByb0MBMQ4) — iOS Dev Weekly · Issue 391 — Video · Topics: Graphics, Media & Games · Navigation & Deep Linking
  **Published:** `15th February 2019`
  **NeKI brief:** Paul Hudson on a topic that comes up quite regularly, the coordinator pattern. Presented both as a blog post, and as a two part video (Part 1, Part 2), this is really everything you’ll need to know on the subject.
- [Xcode in 20 Seconds](https://www.youtube.com/playlist?list=PLuoeXyslFTuYQ9Hoh42Bw8sPYMlTOV0V7) — iOS Dev Weekly · Issue 389 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `1st February 2019`
  **NeKI brief:** Examines Xcode in 20 Seconds, focusing on paul hudson has been posting a new xcode tip every day throughout january. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Experienced iOS Developer at SportPesa (Liverpool, England)](https://sportpesa.bamboohr.co.uk/jobs/view.php?id=24) — iOS Dev Weekly · Issue 389 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `1st February 2019`
  **NeKI brief:** Examines BambooHR makes it easy to simplify HR, with award-winning solutions for everything from hire to retire. Learn more with a free demo today. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Designing a Modern Swift Network Stack](http://mikezornek.com/posts/2019/1/designing-a-modern-swift-network-stack-video-and-slides) — iOS Dev Weekly · Issue 387 — Article · Topics: Graphics, Media & Games · Networking · Swift
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Designing a Modern Swift Network Stack, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Quickly record video from the iOS Simulator](https://github.com/alexp2ad/record-ios-simulator) — iOS Dev Weekly · Issue 386 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Hardware & Devices
  **Published:** `11th January 2019`
  **NeKI brief:** The GitHub repository provides a tool for quickly recording video from the iOS Simulator, with publicly inspectable implementation and usage instructions.
- [Videos from try! Swift NYC 2018](https://www.youtube.com/playlist?list=PLCl5NM4qD3u8NyOjK0deNu4AQk2hgyhjS) — iOS Dev Weekly · Issue 380 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `30th November 2018`
  **NeKI brief:** Check out this fantastic set of videos from the wonderful try! Swift conference held in New York just a couple of months ago in September! 📺
- [Swift Heroes 2018](https://www.youtube.com/playlist?list=PLfCiO1zYKkASAdaBB92r6Ii6tdU8TJN-_) — iOS Dev Weekly · Issue 379 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `23rd November 2018`
  **NeKI brief:** The full set of videos from Swift Heroes which took place in Italy just a couple of weeks ago. This should keep you busy for the weekend!
- [Picking and Hit-Testing in Metal](http://metalbyexample.com/picking-hit-testing) — iOS Dev Weekly · Issue 377 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `9th November 2018`
  **NeKI brief:** Examines Picking and Hit-Testing in Metal, offering practical guidance on test design and automation strategy. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Instabug](https://try.instabug.com/product/ios) — iOS Dev Weekly · Issue 376 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `2nd November 2018`
  **NeKI brief:** Examines Receive Detailed Feedback and Debug your iOS App 10x Faster, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Implementing Support for Continuity Camera](https://thomas.zoechling.me/journal/2018/10/Continuity.html) — iOS Dev Weekly · Issue 375 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `26th October 2018`
  **NeKI brief:** Examines Build and Run: Implementing Support for Continuity Camera. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [watch face project](https://github.com/steventroughtonsmith/SpriteKitWatchFace) — iOS Dev Weekly · Issue 374 — Source repository · Topics: Developer Tools
  **Published:** `19th October 2018`
  **NeKI brief:** Examines SpriteKit-based faux analog watch face example for watchOS - steventroughtonsmith/SpriteKitWatchFace. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this post by Becky Hansmeyer](https://beckyhansmeyer.com/2018/09/30/i-forgot-to-take-videos) — iOS Dev Weekly · Issue 372 — Article · Topics: Graphics, Media & Games
  **Published:** `5th October 2018`
  **NeKI brief:** Presents this post by Becky Hansmeyer, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [40% off ALL books and video courses from Manning](http://mng.bz/V7N0) — iOS Dev Weekly · Issue 372 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `5th October 2018`
  **NeKI brief:** Examines iOS Dev Weekly | Manning Deals. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to choose what app to make next](http://greyaliengames.com/blog/how-to-choose-what-game-to-make-next) — iOS Dev Weekly · Issue 372 — Article · Topics: Graphics, Media & Games
  **Published:** `5th October 2018`
  **NeKI brief:** Offers a framework for choosing the next app idea by balancing scope, interest, and execution risk. Useful for prioritization discussions in small independent product teams.
- [Videos from SwiftConf 2018](https://www.youtube.com/playlist?list=PLgUjQUYKwG_hkD2ZcfAs7bTZwbEtAnNFs) — iOS Dev Weekly · Issue 372 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `5th October 2018`
  **NeKI brief:** Examines SwiftConf '18 - YouTube. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift & Fika 2018 Videos](https://www.youtube.com/playlist?list=PLKNt6c4Ajv2tgrX4wVgoHLSMuP-3sC2M9) — iOS Dev Weekly · Issue 371 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `28th September 2018`
  **NeKI brief:** The YouTube playlist collects publicly viewable Swift & Fika 2018 videos and exposes the associated developer-talk metadata.
- [NSFWDetector: A NSFW detector with CoreML](https://github.com/lovoo/NSFWDetector) — iOS Dev Weekly · Issue 370 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `21st September 2018`
  **NeKI brief:** As you might imagine, this was nearly the “And Finally…” link fo this week, but I can actually see this being potentially useful in all sorts of projects. As someone who once built an iOS game which allowed user uploaded photos, I wish this had existed…
- [four hours of video](https://talk.objc.io/collections/building-a-form-library) — iOS Dev Weekly · Issue 369 — Article · Topics: Graphics, Media & Games
  **Published:** `14th September 2018`
  **NeKI brief:** Examines We build a reusable, declarative form library by refactoring the specific code of a settings screen. The library automatically keeps the data backing the form in sync with the form. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
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
- [The Aqua Screenshot Library](https://512pixels.net/projects/aqua-screenshot-library) — iOS Dev Weekly · Issue 366 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `24th August 2018`
  **NeKI brief:** A browsable reference library of Mac screenshots spanning Aqua, pinstripes, brushed metal, linen, translucency, and vibrancy. It is useful for visual-history research and design comparison.
- [Videos from ADDC 2018](https://www.youtube.com/playlist?list=PLwR4QwnnbBuLHBfsD0Spj6hAcI4yT3uib) — iOS Dev Weekly · Issue 363 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `3rd August 2018`
  **NeKI brief:** ADDC was only a couple of weeks ago in Barcelona, but already there’s a full selection of conference videos from it. As you might imagine from the title of the conference there’s a good mix of design/development talks here.
- [Writing a Modern Metal App from Scratch](http://metalbyexample.com/modern-metal-1) — iOS Dev Weekly · Issue 362 — Article · Topics: Graphics, Media & Games
  **Published:** `27th July 2018`
  **NeKI brief:** Examines Metal is a little bit too low level for me to dabble in (I did do some OpenGL training once, and it convinced me I was happier in higher level APIs) but if you’ve always wanted to get started with Metal this two part (1, Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [2](http://metalbyexample.com/modern-metal-2) — iOS Dev Weekly · Issue 362 — Article · Topics: Graphics, Media & Games
  **Published:** `27th July 2018`
  **NeKI brief:** Examines Metal is a little bit too low level for me to dabble in (I did do some OpenGL training once, and it convinced me I was happier in higher level APIs) but if you’ve always wanted to get started with Metal this two part (1, Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Appdevcon](http://appdevcon.nl/schedule) — iOS Dev Weekly · Issue 362 — Article · Topics: Graphics, Media & Games
  **Published:** `27th July 2018`
  **NeKI brief:** Examines Schedule. Your Appdevcon Conference 2025 ticket gives you access to several days and areas. Find out here where to go!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [his talk](https://ashfurrow.com/blog/building-better-software-by-building-better-teams) — iOS Dev Weekly · Issue 362 — Article · Topics: Graphics, Media & Games
  **Published:** `27th July 2018`
  **NeKI brief:** Examines On March 16, 2018, I delivered the opening keynote for [Appdevcon][], which was titled Building Better Software by Building Better Teams. Slides are [here][slides]. This post serve. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Senior iOS Engineer at mkodo (London or Newcastle, UK)](https://www.mkodo.com/s/careers?jobId=14552) — iOS Dev Weekly · Issue 360 — Article · Topics: Developer Career & Practice · Graphics, Media & Games
  **Published:** `13th July 2018`
  **NeKI brief:** Senior iOS Engineer at mkodo (London or Newcastle, UK). This link is retained as a technical reading lead for Apple-platform development.
- [this bit](https://youtu.be/XUvZFX5jAGc?t=42) — iOS Dev Weekly · Issue 356 — Video · Topics: Graphics, Media & Games
  **Published:** `15th June 2018`
  **NeKI brief:** Examines IT´S ROADTRIP. Keynote presentation. 17th october 2014. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [fixed it before publishing the official video](https://youtu.be/sBfvJn-fpnc?t=3410) — iOS Dev Weekly · Issue 356 — Video · Topics: Graphics, Media & Games
  **Published:** `15th June 2018`
  **NeKI brief:** Examines Get a first look at iMac with Retina 5K display and iPad Air 2. Learn about the release of OS X Yosemite. And follow every moment of the special event at Tow. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS Messenger SDK](https://github.com/intercom/intercom-ios) — iOS Dev Weekly · Issue 355 — Source repository · Topics: Developer Career & Practice · Developer Tools · Graphics, Media & Games
  **Published:** `8th June 2018`
  **NeKI brief:** Hiring talented mobile engineers to develop our iOS Messenger SDK. Be part of the journey!
- [WWDC 97 Videos](http://bslabs.net/2018/05/28/wwdc-1997-videos) — iOS Dev Weekly · Issue 354 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Want something to watch on the flight to San Jose this weekend? These are fantastic. 🥇 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [UIKonf 2018 Videos](https://www.youtube.com/playlist?list=PLdr22uU_wISohI7PIhzq0gotGfKZl1lGo) — iOS Dev Weekly · Issue 353 — Video · Topics: Graphics, Media & Games
  **Published:** `25th May 2018`
  **NeKI brief:** UIKonf may only have finished a week ago but that hasn’t stopped the organisers from already publishing these videos though! Enjoy 📺
- [Retrobatch](http://shapeof.com/archives/2018/5/retrobatch_public_beta.html) — iOS Dev Weekly · Issue 351 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `11th May 2018`
  **NeKI brief:** This is a new tool from Gus Mueller (creator of Acorn) looks very cool. Think of it like Automator for image processing. If you’re regularly processing assets for your apps, you’ll want to check out this public beta.
- [Acorn](http://flyingmeat.com/acorn) — iOS Dev Weekly · Issue 351 — Article · Topics: Graphics, Media & Games
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Acorn is an awesome image editor for the Mac. Use Acorn to edit photos, add filters, retouch pictures, paint, crop, add text, create new images, and much more!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Capture video of the iOS Simulator with simctl](http://www.avanderlee.com/workflow/capture-ios-simulator-video-app-preview) — iOS Dev Weekly · Issue 351 — Article · Topics: CI/CD & Automation · Graphics, Media & Games · Xcode
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Create App Preview videos using App Store Connect's required specifications without the need of conversions using tools like ffmpeg. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [second YouTube channel](https://www.youtube.com/playlist?list=PLCl5NM4qD3u9ZPBWDSgt2mt6moVLi4dp9) — iOS Dev Weekly · Issue 348 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `20th April 2018`
  **NeKI brief:** The try! Swift series of conferences had their most recent outing to Tokyo just over a month ago and all the session videos are now available! There’s also a second YouTube channel from the conference showing the lighter side of things that happened there!
- [Tools](https://www.youtube.com/watch?v=RWotEyTeJhc) — iOS Dev Weekly · Issue 345 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `30th March 2018`
  **NeKI brief:** Examines try! Swift Tokyo Conference 2018 - try! Swift is an immersive community gathering about Apple Technologies, Swift Language Best Practices, Application Develo. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [introduction](https://www.hackingwithswift.com/sixty/0/1/introduction) — iOS Dev Weekly · Issue 340 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `23rd February 2018`
  **NeKI brief:** No, you won’t learn Swift in 60 seconds 😂 but you’ll certainly learn something for each minute you put into this new series of videos by Paul Hudson. If you’re new to Swift, don’t miss this. Here’s the introduction, and you can go on from there.
- [2017 #Pragma Conference Videos](https://www.youtube.com/playlist?list=PLAVm70iJlMuvrV8Ut6fDQN-_X5AhPFtux) — iOS Dev Weekly · Issue 335 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Product Design
  **Published:** `19th January 2018`
  **NeKI brief:** Examines #Pragma Conference 2017 - YouTube. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Senior iOS Engineer, Memrise, London (we can help you relocate)](https://memrise.workable.com/jobs/628010) — iOS Dev Weekly · Issue 335 — Article · Topics: Graphics, Media & Games
  **Published:** `19th January 2018`
  **NeKI brief:** Join our joyful team and help millions of people learn a new language!
- [Metal Programming Guide: Tutorial and Reference via Swift](https://www.amazon.com/dp/0134668944) — iOS Dev Weekly · Issue 333 — Tutorial · Topics: Graphics, Media & Games · Swift
  **Published:** `5th January 2018`
  **NeKI brief:** Examines Metal Programming Guide: Tutorial and Reference via Swift, focusing on janie clayton’s long-awaited book on metal programming is now available for pre-order! with topics ranging from the most…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [My Transition from Swift to Kotlin](https://m.youtube.com/watch?v=cYZ3UJAGCew) — iOS Dev Weekly · Issue 332 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `22nd December 2017`
  **NeKI brief:** Examines Note: Unfortunately due to an issue, the camera recording the speaker feed was not picked up during this session. We apologise for this. As a Sr. iOS Develop. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Ease](https://github.com/roberthein/Ease) — iOS Dev Weekly · Issue 331 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `15th December 2017`
  **NeKI brief:** Examines Ease, focusing on robert-hein hooijmans just released this animation framework which makes adding spring animations a breeze. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [reviews are good](https://daringfireball.net/linked/2017/11/30/app-the-human-story) — iOS Dev Weekly · Issue 330 — Article · Topics: Graphics, Media & Games
  **Published:** `8th December 2017`
  **NeKI brief:** The linked post comments on the App: The Human Story story and argues that thoughtful reviews are useful signals for understanding a product.
- [on Github](https://github.com/malcommac/UIWindowTransitions) — iOS Dev Weekly · Issue 328 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `24th November 2017`
  **NeKI brief:** Presents on Github, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Videos from iOS Conf SG 2017](https://engineers.sg/conference/iosconfsg-2017) — iOS Dev Weekly · Issue 328 — Article · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `24th November 2017`
  **NeKI brief:** Videos from the recent iOS Conf SG in Singapore. There’s a nice selection of topics here.
- [Automating Your App’s Release Process Using fastlane](https://m.youtube.com/watch?v=scfOk5SgrKU) — iOS Dev Weekly · Issue 325 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `3rd November 2017`
  **NeKI brief:** I have not used fastlane for my own projects yet, but I don’t know why – it seems to make things better in so many ways. In this talk, Felix Krause and Josh Liebowitz discuss how to use fastlane to make releasing new app versions a breeze.
- [Free Mobile App Testing on Real iOS Devices with Kobiton](http://www.kobiton.com/freetrial) — iOS Dev Weekly · Issue 321 — Article · Topics: Graphics, Media & Games · Testing
  **Published:** `6th October 2017`
  **NeKI brief:** Kobiton is a mobile device cloud that lets you test mobile, Web and hybrid apps on real iOS devices. Test your way with manual and automation testing. Automatically generated activity logs help you track your progress. Supports Appium 1.6.4. Sign up for a no…
- [NSSpain 2017](https://vimeo.com/album/4786409) — iOS Dev Weekly · Issue 320 — Video · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `29th September 2017`
  **NeKI brief:** The Vimeo showcase collects publicly viewable NSSpain 2017 conference recordings and exposes their session metadata.
- [iOS Engineer - mid level / senior at ottonova in Munich - Germany](https://www.ottonova.de/jobs/ios-engineer) — iOS Dev Weekly · Issue 320 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `29th September 2017`
  **NeKI brief:** Explains iOS Engineer - mid level / senior at ottonova in Munich - Germany, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [AudioKit 4](https://github.com/AudioKit/AudioKit/releases/tag/v4.0) — iOS Dev Weekly · Issue 319 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd September 2017`
  **NeKI brief:** Examines AudioKit 4, focusing on the author’s discussion of don’t think we’ve ever actually directly linked to audiokit before (although there was a video about it in issue 241)…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AudioKit](https://github.com/AudioKit/AudioKit) — iOS Dev Weekly · Issue 319 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd September 2017`
  **NeKI brief:** Provides the public source repository for AudioKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Using SpriteKit to create custom watchOS loading animations](http://martiancraft.com/blog/2017/09/spritekit-tutorial) — iOS Dev Weekly · Issue 317 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `8th September 2017`
  **NeKI brief:** In the first two versions of watchOS, animations were limited to cycling through images like a flip book. Then, watchOS 3 added SpriteKit and SceneKit support allowing more complex, dynamic animations. Cory Bohon demonstrates how SpriteKit and the scene…
- [Lottie](https://github.com/airbnb/lottie-ios) — iOS Dev Weekly · Issue 316 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `1st September 2017`
  **NeKI brief:** Lottie iOS renders JSON-based vector animations in Apple-platform applications. Follow its source for concrete animation loading, playback, and rendering integration, then verify performance and format compatibility for the target app.
- [Managing Temporary Files in Swift](https://medium.com/@victor.pavlychko/managing-temporary-files-in-swift-b076e1444c76) — iOS Dev Weekly · Issue 313 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `11th August 2017`
  **NeKI brief:** Examines Managing Temporary Files in Swift, focusing on temporary files are a pain to deal with, and if you don’t take care of them correctly you can end up with gigabytes of…. Use it as a focused research reference for related Apple-platform work, and verify.
- [I’m an Idiot](https://www.raywenderlich.com/165042/rwdevcon-2017-inspiration-talk-im-idiot-richard-turton) — iOS Dev Weekly · Issue 313 — Article · Topics: Graphics, Media & Games
  **Published:** `11th August 2017`
  **NeKI brief:** Examines Rich is a professional idiot. In this talk from RWDevCon 2017, he talks about how to leverage your inner idiot to make you a better coder, writer and communicator. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using the Vision Framework for Text Detection](http://www.appcoda.com/vision-framework-introduction) — iOS Dev Weekly · Issue 311 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `28th July 2017`
  **NeKI brief:** Examines Among many of the powerful frameworks Apple released at this year’s WWDC, the Vision framework was one of them. With the Vision framework, you can easily implement computer vision. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ADDC 2017 Videos](https://www.youtube.com/playlist?list=PLwR4QwnnbBuJ9BqCGGCt07Ot65BCiA0r5) — iOS Dev Weekly · Issue 311 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `28th July 2017`
  **NeKI brief:** A wonderful set of videos from the ADD conference which was held last month in the beautiful city of Barcelona.
- [Cracking the code behind Apple’s App Store promo card design](http://blog.equinux.com/2017/07/cracking-the-code-behind-apples-app-store-promo-card-design) — iOS Dev Weekly · Issue 311 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `28th July 2017`
  **NeKI brief:** A wonderful set of videos from the ADD conference which was held last month in the beautiful city of Barcelona.
- [Embed in-app support with the Zendesk kit on Fabric](https://www.fabric.io/kits/ios/zendesk) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Embed in-app support with the Zendesk kit on Fabric in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Using SpriteKit to create animations in Swift](https://www.swiftbysundell.com/posts/using-spritekit-to-create-animations-in-swift) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Using SpriteKit to create animations in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Dealing With Asynchrony in a Synchronous Swift World](https://news.realm.io/news/greg-heo-dealing-asynchrous-synchronous-swift-swift-language-user-group-2017) — iOS Dev Weekly · Issue 308 — Article · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `7th July 2017`
  **NeKI brief:** Explores Dealing With Asynchrony in a Synchronous Swift World in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [iOS Developers and Tech Lead @ Hotels.com in London, UK](https://hcomios.github.io/jobs) — iOS Dev Weekly · Issue 308 — Article · Topics: Developer Tools · Graphics, Media & Games · Personal Essays
  **Published:** `7th July 2017`
  **NeKI brief:** Travel and tech. Swift and speed. Solving at scale. Join Hotels.com - voted best place to work in the UK.
- [Why App Preview Videos Are Vital in iOS 11](https://applaunchmap.com/2017/06/23/why-app-preview-videos-are-vital-in-ios-11) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th June 2017`
  **NeKI brief:** Examines Your guide to launching and updating iOS and Mac apps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Want To be Happier at Work?](https://hired.com/join) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th June 2017`
  **NeKI brief:** Hired brings job offers to you, so you can stop wasting your time applying. Apply to 6,000+ companies at once on the platform. 🤖
- [Swift panel discussion](https://news.realm.io/news/wwdc-2017-swift-panel) — iOS Dev Weekly · Issue 306 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **Published:** `23rd June 2017`
  **NeKI brief:** Explores panel discussion in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Machine Learning for everyone](http://machinethink.net/blog/ios-11-machine-learning-for-everyone) — iOS Dev Weekly · Issue 305 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `16th June 2017`
  **NeKI brief:** Explores Machine Learning for everyone in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [why CoreML is such a big deal](http://deepdojo.com/apple-introduces-core-ml) — iOS Dev Weekly · Issue 305 — Article · Topics: Graphics, Media & Games
  **Published:** `16th June 2017`
  **NeKI brief:** Examines Apple rolls out a meticulously crafted red carpet for machine learning models that are already trained. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [UIKonf 2017 videos](https://www.youtube.com/playlist?list=PLdr22uU_wISqntV4tQmx9H6sj9gMtj7nG) — iOS Dev Weekly · Issue 303 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `2nd June 2017`
  **NeKI brief:** Examines All full-length talks from UIKonf 2017. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS 11 concept video](https://www.macstories.net/stories/ios-11-ipad-wishes-and-concept-video) — iOS Dev Weekly · Issue 302 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `26th May 2017`
  **NeKI brief:** Examines (Full-res) Once heralded as a promising sign of Apple's renewed commitment to the iPad, iOS 9 has begun to feel like a one-hit wonder. iOS 9 represented a profound change for. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [“Super. Computer.”](https://web.archive.org/web/20170521182751/https://www.apple.com/ipad-pro) — iOS Dev Weekly · Issue 302 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th May 2017`
  **NeKI brief:** Examines iPad Pro delivers epic power, in 12.9-inch and 9.7-inch sizes. Discover the A9X Chip, Advanced Retina display, 12MP iSight camera, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Writing your UI Swiftly](https://news.realm.io/news/sommer-panage-writing-your-ui-swiftly) — iOS Dev Weekly · Issue 298 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `28th April 2017`
  **NeKI brief:** Explores Writing your UI Swiftly in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Engineering Manager @ Sprout Social. Located in Chicago, IL](http://sproutsocial.applytojob.com/apply/jkJxjm/Engineering-Manager-IOS?source=iosdevweekly) — iOS Dev Weekly · Issue 298 — Article · Topics: Developer Career & Practice · Graphics, Media & Games
  **Published:** `28th April 2017`
  **NeKI brief:** Individual Contributor meets People Management. Cross-functional mobile team. Engineering and design focused Product company.
- [fastlane](https://github.com/fastlane/fastlane) — iOS Dev Weekly · Issue 294 — Source repository · Topics: CI/CD & Automation · Developer Tools · Graphics, Media & Games
  **Published:** `31st March 2017`
  **NeKI brief:** Felix Krause, the creator of fastlane, on what he has learned from working on a massively successful open source project. Nobody creates a new repository on Github expecting it to grow in the way Felix’s has, but before you realize it, this talk may help you…
- [A Gameboy Emulator for the Apple Watch](https://github.com/gabrieloc/GIOVANNI) — iOS Dev Weekly · Issue 293 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `24th March 2017`
  **NeKI brief:** Examines A Gameboy Emulator for the Apple Watch. Contribute to gabrieloc/GIOVANNI development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Indie Game Promotion Takes Over App Store](https://www.macstories.net/news/indie-game-promotion-takes-over-app-store) — iOS Dev Weekly · Issue 292 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `17th March 2017`
  **NeKI brief:** I was happy to see this promotion for independent game developers on the App Store recently. I’d love them give the same privilege to independent apps next!
- [NextLevel: Rad Media Capture in Swift](https://github.com/NextLevel/NextLevel) — iOS Dev Weekly · Issue 289 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** The page covers “NextLevel: Rad Media Capture in Swift” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Learning From Our Elders](https://vimeo.com/204897590) — iOS Dev Weekly · Issue 289 — Video · Topics: Functional Programming · Graphics, Media & Games · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** The Vimeo page provides the publicly readable video titled Learning From Our Elders and its associated description.
- [Free video: Natural Swift](https://gumroad.com/l/natural-swift) — iOS Dev Weekly · Issue 286 — Article · Topics: Functional Programming · Graphics, Media & Games · Swift
  **Published:** `3rd February 2017`
  **NeKI brief:** Examines Free video: Natural Swift, focusing on what makes “swifty” swift? paul hudson from hacking with swift has produced a free video that teaches you how to use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Castaway: Build screencasts and video presentations](https://github.com/jamis/castaway) — iOS Dev Weekly · Issue 284 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `20th January 2017`
  **NeKI brief:** Examines System for building screencasts and video presentations - jamis/castaway. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Zendesk: save $177 with coupon “DEV280”](https://www.zendesk.com/in-app-customer-service) — iOS Dev Weekly · Issue 280 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `9th December 2016`
  **NeKI brief:** Profiles Zendesk’s in-app customer-support tooling for embedding help and issue reporting inside an iOS product. Evaluate SDK integration, privacy and data handling, operational ownership, and user-experience trade-offs before adopting a vendor support channel.
- [Snowflake](https://github.com/onmyway133/Snowflake) — iOS Dev Weekly · Issue 279 — Source repository · Topics: Combine & Reactive Programming · Developer Community & Business · Developer Tools
  **Published:** `2nd December 2016`
  **NeKI brief:** The page covers “Snowflake” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Videos from Mobile Era](https://vimeo.com/mobileera/videos) — iOS Dev Weekly · Issue 279 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `2nd December 2016`
  **NeKI brief:** Videos from the Mobile Era conference which happened last month in Norway. There’s a wide mix of subjects from a great set of speakers here.
- [swiftgd](https://github.com/twostraws/swiftgd) — iOS Dev Weekly · Issue 278 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `25th November 2016`
  **NeKI brief:** If you’ve been doing any work the server with Swift you might be missing Core Graphics which is not available outside of macOS. Of course, there are other graphics libraries available, such as libgd and to help you out, Paul Hudson has wrapped this library…
- [libgd](https://libgd.github.io/manuals/2.2.3/files/preamble-txt.html) — iOS Dev Weekly · Issue 278 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `25th November 2016`
  **NeKI brief:** The page covers “libgd” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [data published by Sensor Tower](https://sensortower.com/blog/app-store-purge) — iOS Dev Weekly · Issue 277 — Article · Topics: Graphics, Media & Games
  **Published:** `18th November 2016`
  **NeKI brief:** Discusses data published by Sensor Tower, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [The Touch Bar on your iPad](https://github.com/bikkelbroeders/TouchBarDemoApp) — iOS Dev Weekly · Issue 276 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Testing
  **Published:** `11th November 2016`
  **NeKI brief:** Examines Allows you to use your macOS Touch Bar from an iPad (through USB connection) or on-screen by pressing the Fn-key. - bikkelbroeders/TouchBarDemoApp. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [demo video](https://www.youtube.com/watch?v=RZLx03OPpUU) — iOS Dev Weekly · Issue 276 — Video · Topics: Graphics, Media & Games · Testing
  **Published:** `11th November 2016`
  **NeKI brief:** Want to develop for the touch bar on-device, but don’t have a shiny new MacBook? Andreas Verhoeven and Robbert Klarenbeek have just the thing for you. I haven’t tested this myself as I still haven’t upgraded to Sierra but it looks good from the demo video.
- [Video App Feedback](https://www.youtube.com/playlist?list=PLm5nKVoMBy49B-u868rgRCOMLVgUwskdT) — iOS Dev Weekly · Issue 273 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `21st October 2016`
  **NeKI brief:** Examines Matt’s feedback on iOS app design captured on video. 📋 Submit your app: https://bit.ly/appcritique 🐦 Follow Matt on Twitter: @mb 👅 Hire Lickability to improv. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Real World Swift Performance](https://realm.io/news/real-world-swift-performance) — iOS Dev Weekly · Issue 273 — Article · Topics: Graphics, Media & Games · Performance · Swift
  **Published:** `21st October 2016`
  **NeKI brief:** Explores Real World Swift Performance in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [video recorded recently](https://realm.io/news/tryswift-ryan-nystrom-refactoring-at-scale-lessons-learned-rewriting-instagram-feed) — iOS Dev Weekly · Issue 272 — Article · Topics: Concurrency · Graphics, Media & Games · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Examines video recorded recently, focusing on iglistkit is a new open source library focused on splitting up your massive collection view controllers, and also being…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Lead iOS Engineer, Target Corporation, Minneapolis, MN](https://jobs.target.com/job/minneapolis/lead-ios-engineer/1118/3182255) — iOS Dev Weekly · Issue 272 — Article · Topics: Graphics, Media & Games
  **Published:** `14th October 2016`
  **NeKI brief:** Examines As a Lead iOS Engineer you’ll build a new registry native app from ground up. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Say It Ain’t So: Implementing Speech Recognition in Your App](https://realm.io/news/tryswift-marc-brown-say-it-aint-so-implementing-speech-recognition) — iOS Dev Weekly · Issue 270 — Article · Topics: App Intents & System Surfaces · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `30th September 2016`
  **NeKI brief:** Explores Say It Ain’t So: Implementing Speech Recognition in Your App in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Senior Entwickler (m/w) iOS, Arvato Systems S4M GmbH, Rheda-Wiedenbrück](https://myjobs-de.becruiter.net/jobagent/search/job_details.aspx?jobid=262414&jb=cyoc) — iOS Dev Weekly · Issue 268 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** We are working for media companies. Join us to make our Apps even more successful!
- [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines) — iOS Dev Weekly · Issue 266 — Article · Topics: Apple Platform Ecosystem · Code Quality · Swift
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Relayout](https://github.com/stevestreza/Relayout) — iOS Dev Weekly · Issue 265 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th August 2016`
  **NeKI brief:** The page covers “Relayout” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Amazing Physically Based Rendering Using the New iOS 10 SceneKit](https://medium.com/@avihay/amazing-physically-based-rendering-using-the-new-ios-10-scenekit-2489e43f7021) — iOS Dev Weekly · Issue 262 — Article · Topics: Graphics, Media & Games
  **Published:** `5th August 2016`
  **NeKI brief:** Examines Amazing Physically Based Rendering Using the New iOS 10 SceneKit, focusing on not being involved with anything which has needed scenekit, i wasn’t aware of exactly what it was capable of these days. Use it as a focused research reference for related Apple-platform work.
- [Interactive Messages in iOS 10](https://medium.com/@prianka.kariat/interactive-messages-in-ios-10-4cea542fbd9a) — iOS Dev Weekly · Issue 262 — Article · Topics: Graphics, Media & Games
  **Published:** `5th August 2016`
  **NeKI brief:** Examines Interactive Messages in iOS 10, focusing on talking of imessage apps, prianka liz kariat gives us a walkthrough of creating a tic tac toe game inside messages. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [ReactiveKit](https://github.com/ReactiveKit/ReactiveKit) — iOS Dev Weekly · Issue 262 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `5th August 2016`
  **NeKI brief:** Examines A Swift Reactive Programming Kit. Contribute to DeclarativeHub/ReactiveKit development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Neural Networks in iOS 10 and macOS](https://www.bignerdranch.com/blog/neural-networks-in-ios-10-and-macos) — iOS Dev Weekly · Issue 257 — Article · Topics: Graphics, Media & Games · macOS & AppKit · Networking
  **Published:** `1st July 2016`
  **NeKI brief:** Explores Neural Networks in iOS 10 and macOS in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Videos from Release Notes](https://releasenotes.tv/videos) — iOS Dev Weekly · Issue 257 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Examines Videos | Release Notes. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Release Notes](https://releasenotes.tv/conference) — iOS Dev Weekly · Issue 257 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Great set of videos from the Release Notes conference. Focused on the business side of the App Store rather than the technical, you’ll certainly find something to educate or inspire you here.
- [robot building](http://slideslive.com/38897350/how-i-built-open-hardware-robot-cz) — iOS Dev Weekly · Issue 257 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Examines Tomáš Jukin · How I built Open Hardware robot [CZ] · SlidesLive. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SaveTheDot](https://github.com/JakeLin/SaveTheDot) — iOS Dev Weekly · Issue 256 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `24th June 2016`
  **NeKI brief:** Examines Want a practical example of using the new UIViewPropertyAnimator API in iOS 10? Jake Lin has you covered with this small game based on it. 👾 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Senior iOS Engineer at Book Creator, South-West England](http://www.bookcreator.com/jobs) — iOS Dev Weekly · Issue 256 — Article · Topics: Graphics, Media & Games
  **Published:** `24th June 2016`
  **NeKI brief:** This Book Creator page advertises a senior iOS engineering role. It is recruitment material rather than technical reading and should normally be excluded from the knowledge index.
- [official iOS app](https://itunes.apple.com/us/app/wwdc/id640199958?mt=8) — iOS Dev Weekly · Issue 255 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `17th June 2016`
  **NeKI brief:** Stream or download the videos from the main site, with the official iOS app. If you’re reading this on Friday then you might even still catch some of the live stream. There’s also the (unofficial) WWDC Mac app if you want to organize your downloads better on…
- [UIKonf 2016 Videos](https://www.youtube.com/playlist?list=PLdr22uU_wISqm9QbnczWxXs9qyuWpSU4k) — iOS Dev Weekly · Issue 254 — Video · Topics: Graphics, Media & Games
  **Published:** `10th June 2016`
  **NeKI brief:** Examines The talks from UIKonf 2016, in full!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Larry Ellison plans to save Apple with Steve Jobs](http://www.iclarified.com/55198/larry-ellison-recounts-making-plan-with-steve-jobs-to-save-apple-video) — iOS Dev Weekly · Issue 252 — Article · Topics: Graphics, Media & Games
  **Published:** `27th May 2016`
  **NeKI brief:** Discusses Larry Ellison plans to save Apple with Steve Jobs, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [African mobile game rewarded its top players with a real cow](http://www.engadget.com/2016/05/08/tunisian-bagra-cow-mobile-game) — iOS Dev Weekly · Issue 250 — Article · Topics: Graphics, Media & Games
  **Published:** `13th May 2016`
  **NeKI brief:** African mobile game rewarded its top players with a real cow. This link is retained as a technical reading lead for Apple-platform development.
- [ImageButter](https://github.com/dollarshaveclub/ImageButter) — iOS Dev Weekly · Issue 247 — Source repository · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `22nd April 2016`
  **NeKI brief:** Provides the ImageButter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Blackbox](https://itunes.apple.com/gb/app/blackbox-think-outside-box/id962969578?mt=8) — iOS Dev Weekly · Issue 246 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `15th April 2016`
  **NeKI brief:** Examines Download Blackbox by Shapes and Stories LLC on the App Store. See screenshots, ratings and reviews, user tips and more games like Blackbox. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The Design of Everyday Things](https://en.wikipedia.org/wiki/The_Design_of_Everyday_Things) — iOS Dev Weekly · Issue 244 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `1st April 2016`
  **NeKI brief:** The page covers “The Design of Everyday Things” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Retro Flappy Bird](https://www.youtube.com/watch?v=hB6eY73sLV0) — iOS Dev Weekly · Issue 244 — Video · Topics: Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `1st April 2016`
  **NeKI brief:** Who knows how many hours of planning combined with 53 long painful minutes to enter the code, and the reward is to play Flappy Bird? The most frustrating game ever! That’s a special kind of masochism! 🤕
- [experience of speaking with a live translator](http://www.jessesquires.com/contributing-to-swift) — iOS Dev Weekly · Issue 243 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `25th March 2016`
  **NeKI brief:** Examines Jesse Squires with a great talk from the recent try! Swift conference. He covers the daunting task of how you’d actually get started, and what skills you’ll need to contribute to the project. He also wrote up his experie Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Code Injection for Xcode](http://artsy.github.io/blog/2016/03/05/iOS-Code-Injection) — iOS Dev Weekly · Issue 241 — Article · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `11th March 2016`
  **NeKI brief:** Explains Code Injection for Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Injection for Xcode](https://github.com/johnno1962/injectionforxcode) — iOS Dev Weekly · Issue 241 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `11th March 2016`
  **NeKI brief:** Provides the Injection for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Core Image for Swift](https://itunes.apple.com/us/book/core-image-for-swift/id1073029980?mt=11) — iOS Dev Weekly · Issue 241 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `11th March 2016`
  **NeKI brief:** Core Image is just for doing blurs, right? 😌 What’s this book all about then? I get the feeling that CI is one of those frameworks that many people underestimate. Luckily, this new book by Simon Gladman does a great job of really showcasing the full power of…
- [help with that](https://github.com/azzoor/WWDCTV) — iOS Dev Weekly · Issue 239 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `26th February 2016`
  **NeKI brief:** The page covers “help with that” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [The Care and Feeding of Gesture Systems](https://www.youtube.com/watch?v=uBYPqb83C7k) — iOS Dev Weekly · Issue 239 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `26th February 2016`
  **NeKI brief:** Fantastic lightning talk from Andy Matuschak on the touch and gesture system on iOS from last week’s React.js conference.
- [iOS Developer, Monitise Create, London, UK](http://www.monitisecreate.com/job/Technical/Permanent/Senior+iOS+Developer/56b47328275b244866000001) — iOS Dev Weekly · Issue 238 — Article · Topics: Graphics, Media & Games
  **Published:** `19th February 2016`
  **NeKI brief:** Examines Challenge expectations. Reinvent. Create the future of customer experiences. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Videos from CocoaLove 2015](https://vimeo.com/channels/cocoalove2015) — iOS Dev Weekly · Issue 237 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** CocoaLove describes itself as a conference which “focuses on talks that aren’t deprecated at the next WWDC”. This means you’re not going to find much, if any code here but what you will find is a great set of inspirational and interesting presentations.
- [Fix Issue](https://vimeo.com/154148473) — iOS Dev Weekly · Issue 236 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Xcode
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the linked Fix Issue video recording. Useful for following the original demonstration and speaker context, while treating it as supplementary material rather than maintained documentation.
- [Tips for Success on Google Play](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_ElGrEtiEXc83m1SeYu3-Q) — iOS Dev Weekly · Issue 235 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `29th January 2016`
  **NeKI brief:** Yes, you read that correctly. Don’t stop reading! It’s true that this set of videos are completely about Google Play and Android apps, but that doesn’t mean that they aren’t worth watching. Clearly you can skip the ones specifically about the Play Store, but…
- [Introducing CoreDragon: cross-application drag’n’drop for iPad](http://overooped.com/post/137230555162/introducing-coredragon-cross-application) — iOS Dev Weekly · Issue 233 — Article · Topics: Graphics, Media & Games
  **Published:** `15th January 2016`
  **NeKI brief:** Nevyn Bengtsson with a video and introductory post on his CoreDragon library. It really feels like this is something that might be introduced to the iOS 10 API as split screen multitasking matures, but why wait until (if!) that happens when you can implement…
- [CoreDragon](https://github.com/nevyn/CoreDragon) — iOS Dev Weekly · Issue 233 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `15th January 2016`
  **NeKI brief:** Examines [iOS/deprecated!] Stop using context menus. Drag and drop instead, even between apps! - nevyn/CoreDragon. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [couple of demo apps](https://github.com/nevyn/CoreDragon/tree/master/Examples) — iOS Dev Weekly · Issue 233 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `15th January 2016`
  **NeKI brief:** Discusses couple of demo apps, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Filterpedia](https://github.com/FlexMonkey/Filterpedia) — iOS Dev Weekly · Issue 231 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `1st January 2016`
  **NeKI brief:** The page covers “Filterpedia” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [contribute more](https://github.com/chriseidhof/pomotv) — iOS Dev Weekly · Issue 231 — Source repository · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `1st January 2016`
  **NeKI brief:** Examines New site dedicated to indexing conference talks and other videos from around the iOS and OS X development community. There’s already ~500 videos there, and you can contribute more to help build it into something even bet Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Awesome Swift Education](https://github.com/hsavit1/Awesome-Swift-Education) — iOS Dev Weekly · Issue 229 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `18th December 2015`
  **NeKI brief:** An extremely comprehensive list of everything you could possibly want to know about Swift. Blogs, books, quick references, presentations, videos, and a whole load of specific, categorised blog posts.
- [video on the same subject](https://youtu.be/ifozUqqC0TY?t=11m5s) — iOS Dev Weekly · Issue 226 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `27th November 2015`
  **NeKI brief:** Examines This talk will cover some of the innovative tooling Facebook developed to monitor the CPU consumption during scrolling, some of the team's larger strategies. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [#Pragma Conference 2015](https://www.youtube.com/playlist?list=PLAVm70iJlMusekZaxufRPS4OjNOs7L7zi) — iOS Dev Weekly · Issue 226 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `27th November 2015`
  **NeKI brief:** This week’s instalment of wonderful conference talks comes from the #Pragma conference from a few weeks ago in Florence. Enjoy!
- [LLVM Developers’ Meeting Videos](https://www.youtube.com/playlist?list=PL_R5A0lGi1AA4Lv2bBFSwhgDaHvvpVU21) — iOS Dev Weekly · Issue 224 — Video · Topics: Graphics, Media & Games · Swift · Systems Programming
  **Published:** `13th November 2015`
  **NeKI brief:** Videos from the recent LLVM Developers’ Meeting. These are all predictably low level talks, but there’s sure to be something in here to catch your interest if you’re interested in the Swift compiler. I must admit, this goes way over my head though, I swim in…
- [How to take a screenshot or record video on your Apple TV](http://imore.com/how-take-screenshot-or-record-video-your-apple-tv) — iOS Dev Weekly · Issue 222 — Article · Topics: Graphics, Media & Games
  **Published:** `30th October 2015`
  **NeKI brief:** Examines Whether you want to preserve a picture of your epic battlefield results or want to build an app walkthrough for your mother, the fourth-generation Apple TV has you covered: You can. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [UIDynamics, UIKit or OpenGL? 3 Types of iOS Animations for Star Wars](https://yalantis.com/blog/uidynamics-uikit-or-opengl-3-types-of-ios-animations-for-the-star-wars) — iOS Dev Weekly · Issue 221 — Article · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `23rd October 2015`
  **NeKI brief:** Explains UIDynamics UIKit or OpenGL 3 Types of iOS Animations for Star Wars with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is.
- [HorizonSDK](https://github.com/HorizonCamera/HorizonSDK-iOS) — iOS Dev Weekly · Issue 221 — Source repository · Topics: Developer Community & Business · Developer Tools · Graphics, Media & Games
  **Published:** `23rd October 2015`
  **NeKI brief:** Remember Horizon? It had a noble goal of eliminating vertical video syndrome. Great news is that now your app can also do the same as they’ve released their technology as an SDK. Of course it can record always horizontal video but also includes support for…
- [vertical video syndrome](https://www.youtube.com/watch?v=Bt9zSfinwFA) — iOS Dev Weekly · Issue 221 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `23rd October 2015`
  **NeKI brief:** Remember Horizon? It had a noble goal of eliminating vertical video syndrome. Great news is that now your app can also do the same as they’ve released their technology as an SDK. Of course it can record always horizontal video but also includes support for…
- [Senior iOS Developer at Ticketmaster Mobile Studio - Durham, NC](https://www.smartrecruiters.com/TicketmasterMobileStudio/82678823-senior-mobile-engineer-ios) — iOS Dev Weekly · Issue 220 — Article · Topics: Graphics, Media & Games
  **Published:** `16th October 2015`
  **NeKI brief:** Explains Senior iOS Developer at Ticketmaster Mobile Studio - Durham, NC, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [BonMot](https://github.com/Raizlabs/BonMot) — iOS Dev Weekly · Issue 213 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `28th August 2015`
  **NeKI brief:** We have amazing control over typography on iOS and this talk by Zev Eisenberg is a great high level overview of what’s possible and how to implement it. He’s also working on BonMot which makes putting together attributed strings much easier, and that can…
- [tutorials](http://principleformac.com/tutorial.html) — iOS Dev Weekly · Issue 212 — Tutorial · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st August 2015`
  **NeKI brief:** This looks great. It’s a combination of a prototyping and timeline based animation tool. There’s some really nice touches though, like automatic animations between layers which have the same name on different artboards. You should check out the video on the…
- [Crafting Icons](http://www.elischiff.com/blog/2015/8/4/crafting-icons) — iOS Dev Weekly · Issue 210 — Article · Topics: Graphics, Media & Games
  **Published:** `7th August 2015`
  **NeKI brief:** The page covers “Crafting Icons” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Half-Assed](http://furbo.org/2015/07/22/half-assed) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Discusses Half-Assed, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [worth a read](http://bitsplitting.org/2015/07/23/six-in-one) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Craig Hockenberry's "Half-Assed" calls out the disparity between Apple's Mac and iOS App Stores with respect to app analytics, limiting customer reviews from be. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [NotificationExtensionTest](https://github.com/hamzasood/NotificationExtensionTest) — iOS Dev Weekly · Issue 206 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Testing
  **Published:** `10th July 2015`
  **NeKI brief:** Animated GIF notifications for everyone! Hamza Sood has been digging around with an undocumented feature in El Capitan. Check out the demo video for a quick look at what’s possible. Note: This may never make it as a feature we can use, but it’s interesting…
- [Playing with UIDynamics in iOS 9](http://fancypixel.github.io/blog/2015/06/19/playing-with-uidynamics-in-ios-9) — iOS Dev Weekly · Issue 205 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd July 2015`
  **NeKI brief:** Explains Playing with UIDynamics in iOS 9, focusing on concrete animation mechanics and the implementation choices that shape UIKit interaction behavior.
- [UIKonf 2015 Videos](https://www.youtube.com/playlist?list=PLdr22uU_wISpW6XI1J0S7Lp-X8Km-HaQW) — iOS Dev Weekly · Issue 202 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `12th June 2015`
  **NeKI brief:** Just in case the WWDC videos weren’t enough for you this week. Here’s the full set of videos from this year’s UIKonf in Berlin. Enjoy!
- [Add Google to your iOS Apps with CocoaPods](http://googledevelopers.blogspot.com/2015/05/add-google-to-your-ios-apps-with.html) — iOS Dev Weekly · Issue 201 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Google IO last week saw an interesting iOS announcement from Google. CocoaPods will be the preferred method for installation for all Google iOS libraries. It made the IO keynote and Google also put together a cute introduction video. Congratulations to the…
- [cute introduction video](https://youtube.com/watch?v=iEAjvNRdZa0) — iOS Dev Weekly · Issue 201 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** The YouTube page provides a publicly viewable introduction video and its associated metadata without authentication.
- [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit) — iOS Dev Weekly · Issue 199 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd May 2015`
  **NeKI brief:** I do love Core Animation, but it can be a little… long-winded. This library provides a shorthand syntax for many common animations along with the ability to chain them together. I hadn’t come across JHChainableAnimations before but this is a Swift port of…
- [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) — iOS Dev Weekly · Issue 199 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd May 2015`
  **NeKI brief:** Examines Easy to read and write chainable animations in Objective-C and Swift - jhurray/JHChainableAnimations. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The early days of Apple](http://www.loopinsight.com/2015/05/20/the-early-days-of-apple) — iOS Dev Weekly · Issue 199 — Article · Topics: Graphics, Media & Games
  **Published:** `22nd May 2015`
  **NeKI brief:** The early days of Apple. This link is retained as a technical reading lead for Apple-platform development.
- [Bringing Clang to Windows](http://blogs.msdn.com/b/vcblog/archive/2015/05/01/bringing-clang-to-windows.aspx) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Examines As you may know, Visual Studio now supports building Android and iOS applications using Clang. We realize the need of our users to write cross-platform. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [video from the Build conference](http://channel9.msdn.com/events/Build/2015/3-610) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Interesting post by the Microsoft Visual C++ team on the process of compiling iOS and Android code to Windows via Clang. It’s also worth checking out this video from the Build conference if you want to learn more. Think back a few years, would you have…
- [NSConference 7 Videos](https://vimeo.com/channels/nsconf7) — iOS Dev Weekly · Issue 197 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Provides a channel of NSConference 7 recordings for browsing the event’s technical talks. Useful as a discovery index for concrete sessions; individual recordings should be evaluated separately from the conference wrapper.
- [Senior iOS Developer, NYT Cooking](http://developers.nytimes.com/careers) — iOS Dev Weekly · Issue 195 — Article · Topics: Developer Career & Practice · Graphics, Media & Games
  **Published:** `24th April 2015`
  **NeKI brief:** Examines In 1896, Adolf S. Ochs pledged The New York Times to a principle that still guides our mission today: “To give the news impartially, without fear or favor.”…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS Engineer - Expensify, San Francisco](http://we.are.expensify.com/why-work-here) — iOS Dev Weekly · Issue 193 — Article · Topics: Graphics, Media & Games
  **Published:** `10th April 2015`
  **NeKI brief:** iOS engineer & generalist? Help us make expense reports better!
- [The Plying Game](http://www.macworld.com/article/2905352/the-plying-game-an-inside-look-at-the-voracious-and-insatiable-world-of-app-store-reviews.html) — iOS Dev Weekly · Issue 192 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `3rd April 2015`
  **NeKI brief:** Examines Michael Simon with a look at the ups and downs (OK, mainly downs) of the rating and review system on the App Store. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Here’s a run down of what’s new by Brian Moakley](http://www.raywenderlich.com/97546/whats-new-unity-5) — iOS Dev Weekly · Issue 188 — Article · Topics: Graphics, Media & Games
  **Published:** `6th March 2015`
  **NeKI brief:** Examines In this article, you’ll give an overview of some of the new shiny features in Unity 5. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Senior iOS Engineer, NYC @ Spotify](https://www.spotify.com/us/jobs/opportunities/technology/mobile/new-york-ny-united-states) — iOS Dev Weekly · Issue 188 — Article · Topics: Graphics, Media & Games
  **Published:** `6th March 2015`
  **NeKI brief:** Help build cutting-edge iOS apps that bring music to millions of users.
- [First Impressions using React Native](http://jlongster.com/First-Impressions-using-React-Native) — iOS Dev Weekly · Issue 185 — Article · Topics: Cross-Platform & Web
  **Published:** `13th February 2015`
  **NeKI brief:** The page is an archived first-impressions article about using React Native, describing the author's early experience and implementation observations.
- [Tips and Tricks for Getting Started in the App World](https://www.youtube.com/watch?v=6rd1lgcejAI) — iOS Dev Weekly · Issue 185 — Video · Topics: AI Development · Graphics, Media & Games · Personal Essays
  **Published:** `13th February 2015`
  **NeKI brief:** Great talk by Joe Cieplinski which he gave at a meet up held at the Academy of Fine Arts in Warsaw last week. He talks about on starting and running a small app company.
- [Sprite Illuminator](https://www.codeandweb.com/spriteilluminator) — iOS Dev Weekly · Issue 184 — Article · Topics: Graphics, Media & Games
  **Published:** `6th February 2015`
  **NeKI brief:** Examines Enhance your sprites with normal maps to create stunning light effects in your 2d games. Supports algorithmic and hand-painted normal maps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [As I Learn WatchKit](http://david-smith.org/watchkit) — iOS Dev Weekly · Issue 181 — Article · Topics: Graphics, Media & Games
  **Published:** `16th January 2015`
  **NeKI brief:** Explains As I Learn WatchKit, focusing on Apple Watch interface or lifecycle decisions that developers can apply when building watchOS experiences.
- [Watch-a-palooza](http://vimeo.com/album/3212507) — iOS Dev Weekly · Issue 181 — Video · Topics: Graphics, Media & Games
  **Published:** `16th January 2015`
  **NeKI brief:** More WATCH videos, this time from David Hoang and Curt Clifton speaking at Seattle Coders a couple of weeks ago. Three videos here, one on the design side of the watch, one on the code side and then a Q&A. Worth a watch (pun intended 😎).
- [Bezel](http://infinitapps.com/bezel) — iOS Dev Weekly · Issue 180 — Article · Topics: Graphics, Media & Games
  **Published:** `9th January 2015`
  **NeKI brief:** The WATCH simulator is functional, but it doesn’t really look much like the device. Troy Gaul has the answer with this app that grabs the output from the simulator and projects it onto a rendering of the watch. Once that’s done, it’s xScope to the rescue to…
- [xScope to the rescue](http://furbo.org/2015/01/06/bezel-and-xscope) — iOS Dev Weekly · Issue 180 — Article · Topics: Graphics, Media & Games
  **Published:** `9th January 2015`
  **NeKI brief:** Examines Look at your wrist: notice something missing? Yeah, it’s “Early 2015” and you still don’t have an Apple Watch. Damn! Luckily, my colleague Troy Gaul has jus. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [HLSpriteKit](https://github.com/hilogames/HLSpriteKit) — iOS Dev Weekly · Issue 177 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `19th December 2014`
  **NeKI brief:** Examines SpriteKit scene and node subclasses, plus various utilities. - hilogames/HLSpriteKit. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SmudgeKit](https://github.com/Ideon/SmudgeKit) — iOS Dev Weekly · Issue 172 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `14th November 2014`
  **NeKI brief:** Presents SmudgeKit, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `24th October 2014`
  **NeKI brief:** The page covers “KZPlayground” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Check out the video too](http://vimeo.com/109757619) — iOS Dev Weekly · Issue 169 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `24th October 2014`
  **NeKI brief:** I really don’t need to say anything about this except this is playgrounds, for Objective-C, by Krzysztof Zabłocki. Check out the video too, super cool.
- [videos](https://www.youtube.com/watch?v=-IPMNWqA638) — iOS Dev Weekly · Issue 168 — Video · Topics: Concurrency · Graphics, Media & Games
  **Published:** `17th October 2014`
  **NeKI brief:** Explains the engineering behind Facebook Paper's AsyncDisplayKit, particularly asynchronous UI rendering used to keep interaction and animation smooth. Valuable historical context for Texture-style architectures and off-main-thread display work.
- [Size Matters](http://www.smashingmagazine.com/2014/09/29/balancing-line-length-font-size-responsive-web-design) — iOS Dev Weekly · Issue 166 — Article · Topics: Graphics, Media & Games
  **Published:** `3rd October 2014`
  **NeKI brief:** Laura Franz digs into the science of how font size and line length affect readability on smaller screens. This fascinating article is talking about mobile web design but is just as relevant for native as it’s purely concerned with rendering text on small…
- [Facebook’s iOS Infrastructure](https://www.youtube.com/watch?v=XhXC4SKOGfQ) — iOS Dev Weekly · Issue 165 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `26th September 2014`
  **NeKI brief:** Fascinating video from the @Scale conference recently of various Facebook engineers talking about the internals of their various apps. It’s hard to imagine the challenges of working with datasets that are as big as Facebook’s so this is a rare chance to take…
- [Using Vector Images in Xcode 6](http://martiancraft.com/blog/2014/09/vector-images-xcode6) — iOS Dev Weekly · Issue 164 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `19th September 2014`
  **NeKI brief:** Use vector PDFs in Xcode asset handling to reduce manually exported device-size variants. Verify which asset types and OS versions preserve vector fidelity, since vector source input does not mean every runtime use remains resolution independent.
- [Getting Started with Metal in Swift](http://www.raywenderlich.com/77488/ios-8-metal-tutorial-swift-getting-started) — iOS Dev Weekly · Issue 163 — Tutorial · Topics: Graphics, Media & Games · Swift
  **Published:** `12th September 2014`
  **NeKI brief:** Explains Getting Started with Metal in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Designing Monument Valley: Less Game, More Experience](http://www.gdcvault.com/play/1020878/Designing-Monument-Valley-Less-Game) — iOS Dev Weekly · Issue 163 — Article · Topics: Graphics, Media & Games
  **Published:** `12th September 2014`
  **NeKI brief:** Fascinating video from this year’s GDC. Ken Wong, lead designer of Monument Valley talking about the inspiration for the game, a look at all of the concept art, level design and concentrating on the play experience. Such a great talk about a wonderful product.
- [App Bundles](http://blog.appfigures.com/the-road-to-ios-8-app-bundles) — iOS Dev Weekly · Issue 162 — Article · Topics: Graphics, Media & Games
  **Published:** `5th September 2014`
  **NeKI brief:** This Appfigures article explains the introduction and implications of App Bundles in the App Store. Follow it for historical packaging and storefront context, while checking current App Store Connect behavior independently.
- [new iTunes Connect](http://www.macstories.net/news/apple-updates-itunes-connect-design-rolls-out-testflight-app) — iOS Dev Weekly · Issue 162 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `5th September 2014`
  **NeKI brief:** Discusses new iTunes Connect, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Introducing the 1Password App Extension](http://blog.agilebits.com/2014/07/30/introducing-the-1password-app-extension-for-ios-8-apps) — iOS Dev Weekly · Issue 157 — Article · Topics: App Services & Extensions · Apple Platform Ecosystem · Security & Privacy
  **Published:** `1st August 2014`
  **NeKI brief:** Explains Introducing the 1Password App Extension, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [Want to experience the San Francisco startup scene?](https://gametime.co/jobs/a863b6f9-1b49-4288-babd-75e84e4690df) — iOS Dev Weekly · Issue 157 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `1st August 2014`
  **NeKI brief:** Examines <p>Our team is on a mission to connect people through incredible shared experiences. We build technology that gets people out into the real world to enjoy their favorite even. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [UIKonf 2014 Videos](https://www.youtube.com/playlist?list=PLdr22uU_wISq-xmSdu1QQ4OJxr68qnJ54) — iOS Dev Weekly · Issue 156 — Video · Topics: Graphics, Media & Games
  **Published:** `25th July 2014`
  **NeKI brief:** Examines The talks from UIKonf 2014, in full!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [TaskRabbit Mobile Engineer, San Francisco](http://boards.greenhouse.io/taskrabbit/jobs/17874) — iOS Dev Weekly · Issue 156 — Article · Topics: Graphics, Media & Games
  **Published:** `25th July 2014`
  **NeKI brief:** Presents TaskRabbit Mobile Engineer, San Francisco, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Coursera iOS Software Engineer - Mountain View, CA](https://www.coursera.org/about/careers/96aecab7-9cb9-424a-b95c-002842a792e8) — iOS Dev Weekly · Issue 156 — Tutorial · Topics: Architecture · Developer Career & Practice · Developer Community & Business
  **Published:** `25th July 2014`
  **NeKI brief:** Explains Coursera iOS Software Engineer Mountain View CA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [SkipCasts](https://www.youtube.com/user/SkipCasts/videos) — iOS Dev Weekly · Issue 155 — Video · Topics: Graphics, Media & Games · Swift
  **Published:** `18th July 2014`
  **NeKI brief:** Explains SkipCasts with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Nodes Denmark is looking for an experienced iOS developer.](http://www.nodesagency.com/nodes-is-hiring-experienced-ios-developer-to-join-our-awesome-dev-team) — iOS Dev Weekly · Issue 155 — Article · Topics: Developer Career & Practice · Graphics, Media & Games
  **Published:** `18th July 2014`
  **NeKI brief:** We are looking for a kick-ass developer to join our awesome team in Copenhagen. You’ll be developing some of the most ambitious apps on the Danish market for both our Danish and international customers, as well as contributing to the internal frameworks that…
- [Mobile Designers who Code](http://www.meetup.com/Mobile-Designers-Code/events/186929152) — iOS Dev Weekly · Issue 152 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `27th June 2014`
  **NeKI brief:** Explains Mobile Designers who Code with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Screenshot](http://xkcd.com/1373) — iOS Dev Weekly · Issue 148 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `30th May 2014`
  **NeKI brief:** Examines xkcd: Screenshot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Dark Room](https://itunes.apple.com/us/app/a-dark-room/id736683061?mt=8) — iOS Dev Weekly · Issue 145 — Article · Topics: Graphics, Media & Games
  **Published:** `9th May 2014`
  **NeKI brief:** Barrett Sheridan interviewing Michael Townsend and Amir Rajan about A Dark Room which is a game written with very little attention paid to visuals or UI design. Instead, the narrative makes it compelling and even though I find the UI uncomfortable, I find…
- [Mobile Software Engineer: SDKs for iOS (Boston)](https://hire.jobvite.com/j?cj=ou7CYfwV&s=iOS_Dev_Weekly) — iOS Dev Weekly · Issue 145 — Article · Topics: Graphics, Media & Games
  **Published:** `9th May 2014`
  **NeKI brief:** The mission of Brightcove’s SDK team is to build libraries, frameworks, and developer tools that help Brightcove’s customers build the best possible video and media app experiences on a wide range of devices. We’re looking to bring on a developer with…
- [Three20](https://github.com/facebook/three20) — iOS Dev Weekly · Issue 144 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `2nd May 2014`
  **NeKI brief:** Examines Three20 is an Objective-C library for iPhone developers - facebookarchive/three20. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Procedural Level Generation in Games using a Cellular Automaton](http://www.raywenderlich.com/66062/procedural-level-generation-games-using-cellular-automaton-part-1) — iOS Dev Weekly · Issue 144 — Article · Topics: Graphics, Media & Games
  **Published:** `2nd May 2014`
  **NeKI brief:** Examines A tutorial on procedural level generation using a cellular automaton to create cave-like levels in games. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Part 2](http://www.raywenderlich.com/70610/procedural-level-generation-games-using-cellular-automaton-part-2) — iOS Dev Weekly · Issue 144 — Article · Topics: Graphics, Media & Games
  **Published:** `2nd May 2014`
  **NeKI brief:** Kim Pedersen with a fascinating article on automatic generation of level data. This isn’t going to be the kind of thing you get to use every day but I found the article a really interesting read. You will also want to check out Part 2 when you’re done.
- [Building Paper](https://www.youtube.com/watch?v=OiY1cheLpmI&feature=youtu.be) — iOS Dev Weekly · Issue 143 — Video · Topics: Graphics, Media & Games · Performance
  **Published:** `25th April 2014`
  **NeKI brief:** Collects Facebook Paper engineering sessions on contextual tutorials, maintainable UI code, spring animation, advanced gestures, and asynchronous interfaces. Useful historical context for the techniques used to keep a highly interactive app responsive.
- [Free-to-play games don’t have to suck](http://theverge.com/2014/4/9/5597072/free-to-play-games-dont-have-to-suck) — iOS Dev Weekly · Issue 141 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `11th April 2014`
  **NeKI brief:** I’ve recently been talking about Hearthstone quite a lot as a perfect example of a free to play game which doesn’t suck. It’s Blizzard’s first crack at the iOS platform (or any mobile platform) and so of course it’s very polished but the key thing is that…
- [John Chaffee also talked at the same meeting about the Mac App Store](http://vimeo.com/91584758) — iOS Dev Weekly · Issue 141 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Xcode
  **Published:** `11th April 2014`
  **NeKI brief:** Ken Case talking at the Seattle Xcoders meeting from earlier this year about all aspects of upgrade pricing. The talk focuses on the Mac App Store specifically but much of it is relevant in a wider context of App Store pricing in general. John Chaffee also…
- [BRFlabbyTable](https://github.com/brocoo/BRFlabbyTable) — iOS Dev Weekly · Issue 140 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `4th April 2014`
  **NeKI brief:** Provides the BRFlabbyTable source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Part two of the talk is also online here](http://vimeo.com/90642682) — iOS Dev Weekly · Issue 140 — Video · Topics: Concurrency · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `4th April 2014`
  **NeKI brief:** Chris Eidhof with a collection of tips and tricks on asynchronous programming from Cocoaheads Kiev recently. Part two of the talk is also online here.
- [Senior iOS Developer - Engineer Apps You’ll Love](http://raizlabs.theresumator.com/apply/ApvQjq/Senior-Mobile-Developer-IPhone-And-Android.html) — iOS Dev Weekly · Issue 140 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `4th April 2014`
  **NeKI brief:** Examines Trying to apply for a job? JazzHR is an applicant tracking system (ATS) used by businesses to organize hiring — not a job board. Here's how to find the roles you're looki. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A tiny puzzle that grows on you.](http://asherv.com/threes/threemails) — iOS Dev Weekly · Issue 139 — Article · Topics: Graphics, Media & Games
  **Published:** `28th March 2014`
  **NeKI brief:** Examines THREES - A tiny puzzle that grows on you.. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [announced a very similar deal](http://www.cryengine.com/news/crytek-announces-its-cryengine-as-a-service-program) — iOS Dev Weekly · Issue 138 — Article · Topics: Graphics, Media & Games
  **Published:** `21st March 2014`
  **NeKI brief:** There has been a gradual trend towards top end game engines transitioning from six-figure licensing costs to lower costs plus a share of revenue but this week everything turned a little upside down with Unreal Engine 4 pricing model going to a very cheap…
- [Carpet Mesh](http://marcus-experiments.tumblr.com/post/79283666129/so-here-is-a-more-in-depth-video-about-this) — iOS Dev Weekly · Issue 138 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `21st March 2014`
  **NeKI brief:** Explores a carpet-mesh rendering experiment with interactive graphics. Follow it for concrete geometry and rendering ideas, while verifying implementation details against current graphics frameworks.
- [“Free-to-play” misleading advertising](http://www.gamesindustry.biz/articles/2014-02-27-free-to-play-misleading-advertising-in-europe) — iOS Dev Weekly · Issue 136 — Article · Topics: Graphics, Media & Games
  **Published:** `7th March 2014`
  **NeKI brief:** Seems ridiculous to me that “Free to play” games should be free to… Oh wait a minute, no it doesn’t. It appears that it’s recommendations rather than actual legislation being discussed here but everything they are proposing seems sensible. I hope this gets…
- [Threes gives you cuteness where you least expect it](http://www.avclub.com/article/the-iphone-hit-threes-gives-you-cuteness-where-you-201293) — iOS Dev Weekly · Issue 134 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `21st February 2014`
  **NeKI brief:** Examines The A.V. Club digs deep into film, TV, music, games, books and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Cocos2D V3 - Release Candidate 1](http://www.cocos2d-iphone.org/cocos2d-v3-rc1-release) — iOS Dev Weekly · Issue 130 — Article · Topics: Cross-Platform & Web
  **Published:** `24th January 2014`
  **NeKI brief:** The release post announces Cocos2D version 3 release candidate 1 and describes the changes for iOS game developers.
- [UIImageView+FaceAwareFill](https://github.com/Julioacarrettoni/UIImageView_FaceAwareFill) — iOS Dev Weekly · Issue 129 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th January 2014`
  **NeKI brief:** Provides the UIImageView+FaceAwareFill source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [2013 LLVM Developers’ Meeting](http://llvm.org/devmtg/2013-11) — iOS Dev Weekly · Issue 125 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `20th December 2013`
  **NeKI brief:** Examines The videos and slides have been published from the most recent LLVM compiler conference which was held in November. Naturally this is all very low level content but is always worth a look even if compilers aren’t necessa Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Çingleton 3 Conference Videos](http://vimeo.com/m/channels/637623) — iOS Dev Weekly · Issue 123 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `6th December 2013`
  **NeKI brief:** The Vimeo channel collects publicly viewable Çingleton 3 conference recordings and exposes their session metadata.
- [iOS Courses on Code School](https://www.codeschool.com/courses/core-ios-7) — iOS Dev Weekly · Issue 122 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `29th November 2013`
  **NeKI brief:** Explains iOS Courses on Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Video Trailers Debut On The App Store With ‘Clumsy Ninja’](http://www.macstories.net/news/video-trailers-debut-on-the-app-store-with-clumsy-ninja) — iOS Dev Weekly · Issue 121 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `22nd November 2013`
  **NeKI brief:** Looks like it’s a special case and is only enabled for this one app right now but Apple have to be looking to roll this out for everyone in the future. This is a huge deal for App Store listings.
- [Unity Survival Game Tutorial](http://www.youtube.com/playlist?list=PLPV2KyIb3jR7F_B4p8X3YwHPaExh0R9Kk) — iOS Dev Weekly · Issue 121 — Video · Topics: Graphics, Media & Games
  **Published:** `22nd November 2013`
  **NeKI brief:** A long-form Unity survival-game course split into focused installments, progressing from project setup toward gameplay systems. It is useful as historical cross-platform game-development training, not as guidance for native Apple UI frameworks.
- [The Mobile 2D Game Engine Popularity Index – November 2013](http://www.learn-cocos2d.com/2013/11/mobile-game-engine-popularity-index) — iOS Dev Weekly · Issue 120 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `15th November 2013`
  **NeKI brief:** The article compares the popularity of mobile 2D game engines in November 2013 and provides a concrete snapshot of the development-tool landscape.
- [Cocos2d Version 3 Preview](http://www.cocos2d-iphone.org/cocos2d-version-3-preview) — iOS Dev Weekly · Issue 119 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `8th November 2013`
  **NeKI brief:** The article previews Cocos2D version 3 and discusses the framework features and migration context for iOS game development.
- [MoarFonts](http://pitaya.ch/moarfonts) — iOS Dev Weekly · Issue 119 — Article · Topics: Graphics, Media & Games · Xcode
  **Published:** `8th November 2013`
  **NeKI brief:** Explains MoarFonts with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Demonstrates compiling an Objective-C iOS game for Android with Apportable and SpriteBuilder, including platform-framework mapping. Treat it as historical cross-platform tooling context rather than a current deployment recommendation.
- [Why You Don’t Burn Out on Candy Crush Saga](http://www.psychologyofgames.com/2013/10/why-you-dont-burn-out-on-candy-crush-saga) — iOS Dev Weekly · Issue 115 — Article · Topics: Graphics, Media & Games
  **Published:** `11th October 2013`
  **NeKI brief:** Why You Don’t Burn Out on Candy Crush Saga. This link is retained as a technical reading lead for Apple-platform development.
- [Unleashing Genetic Algorithms on the iOS 7 Icon](http://blog.mikeswanson.com/post/62341902567/unleashing-genetic-algorithms-on-the-ios-7-icon) — iOS Dev Weekly · Issue 114 — Article · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `4th October 2013`
  **NeKI brief:** Explains Unleashing Genetic Algorithms on the iOS 7 Icon, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [Behold The World’s Smallest Working Macintosh](http://www.cultofmac.com/242234/smallest-working-macintosh) — iOS Dev Weekly · Issue 109 — Article · Topics: Graphics, Media & Games
  **Published:** `30th August 2013`
  **NeKI brief:** The article showcases the world's smallest working Macintosh and describes the compact hardware project.
- [Why Using A Physics Engine For A 2D Platformer Is A Terrible Idea](http://www.learn-cocos2d.com/2013/08/physics-engine-platformer-terrible-idea) — iOS Dev Weekly · Issue 106 — Article · Topics: Graphics, Media & Games
  **Published:** `9th August 2013`
  **NeKI brief:** I am not a game developer so I hadn’t really given this topic much thought but I really enjoyed Steffen Itterheim’s analysis of why a physics engine is a bad choice for a 2D platform game. All of the reasons make sense, I guess I just hadn’t thought about it…
- [Bugshot](http://www.marco.org/bugshot) — iOS Dev Weekly · Issue 103 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Examines Presenting PinpointKit – Lickability. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [WWDC Sample Code Downloader](https://github.com/jfahrenkrug/WWDC-Downloader) — iOS Dev Weekly · Issue 100 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `28th June 2013`
  **NeKI brief:** Provides the WWDC Sample Code Downloader source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIRefreshControl Fun and Games](http://useyourloaf.com/blog/2013/06/18/uirefreshcontrol-fun-and-games.html) — iOS Dev Weekly · Issue 99 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st June 2013`
  **NeKI brief:** Explains UIRefreshControl Fun and Games with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why Apple Created Sprite Kit And What It Means For Cocos2D](http://www.learn-cocos2d.com/2013/06/apple-create-spritekit) — iOS Dev Weekly · Issue 98 — Article · Topics: Graphics, Media & Games
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Why Apple Created Sprite Kit And What It Means For Cocos2D with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Drawing Dynamic Visualizations](http://vimeo.com/66085662) — iOS Dev Weekly · Issue 95 — Video · Topics: Graphics, Media & Games
  **Published:** `24th May 2013`
  **NeKI brief:** The Vimeo page provides the publicly viewable Drawing Dynamic Visualizations video and its associated presentation metadata.
- [2013 European LLVM Conference](http://llvm.org/devmtg/2013-04) — iOS Dev Weekly · Issue 93 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `10th May 2013`
  **NeKI brief:** Examines The LLVM Compiler Infrastructure Project. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [PHFComposeBarView](https://github.com/fphilipe/PHFComposeBarView) — iOS Dev Weekly · Issue 93 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `10th May 2013`
  **NeKI brief:** Provides the PHFComposeBarView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [In-App Purchase Education](http://www.pocketgamer.biz/r/PG.Biz/App+Store/news.asp?c=50444) — iOS Dev Weekly · Issue 92 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `3rd May 2013`
  **NeKI brief:** Discusses In-App Purchase Education, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Trigonometry for Game Programming](http://www.raywenderlich.com/35866/trigonometry-for-game-programming-part-1) — iOS Dev Weekly · Issue 91 — Article · Topics: Graphics, Media & Games · UIKit
  **Published:** `26th April 2013`
  **NeKI brief:** Explains Trigonometry for Game Programming with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Building Facebook Home with Quartz Composer](http://vimeo.com/user5164093/videos) — iOS Dev Weekly · Issue 90 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `19th April 2013`
  **NeKI brief:** Facebook Home is obviously it is only available on Android but something interesting came out in the media coverage of the recent launch, prototypes of Home were created in Quartz Composer. David O Brien has put together a great set of video tutorials…
- [Designing for iOS: Blending modes](http://robots.thoughtbot.com/post/46668544473/designing-for-ios-blending-modes) — iOS Dev Weekly · Issue 88 — Article · Topics: Graphics, Media & Games
  **Published:** `5th April 2013`
  **NeKI brief:** Core Graphics blending modes can be a little confusing if you are coming at them for the first time. If you are in this camp then Gordon Fontenot has an article taking you through the basics of blending drawing code with grayscale images to produce tinted…
- [Glimpse](https://github.com/wess/Glimpse) — iOS Dev Weekly · Issue 87 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `29th March 2013`
  **NeKI brief:** Examines UIView recording library. Contribute to wess/Glimpse development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Typography for Developers on Vimeo](http://vimeo.com/62084061) — iOS Dev Weekly · Issue 86 — Video · Topics: Graphics, Media & Games
  **Published:** `22nd March 2013`
  **NeKI brief:** If you don’t know your leading from your kerning or your ligatures from your point sizes, this short video from Jeff Heaton will set you down the right track. We are lucky to have a platform with fantastic support for beautiful typography, the least we can…
- [iOSVideoCameraMultiStitch](https://github.com/carsonmcdonald/iOSVideoCameraMultiStitchExample) — iOS Dev Weekly · Issue 85 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `15th March 2013`
  **NeKI brief:** Carson McDonald with some code for recording a “Vine” style multi-section video clip including an asset stitching class which could come in useful for all sorts of stuff. Let the Vine clones flow.
- [Making a Hit Tower Defense Game: A Top App Dev Interview](http://www.raywenderlich.com/30636/top-developer-interviews-ironhide-game-studio) — iOS Dev Weekly · Issue 83 — Article · Topics: Graphics, Media & Games
  **Published:** `1st March 2013`
  **NeKI brief:** The interview discusses how Ironhide built a successful tower-defense game and covers concrete decisions in mobile game development.
- [Xamarin Studio](http://blog.xamarin.com/announcing-xamarin-2.0) — iOS Dev Weekly · Issue 82 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `22nd February 2013`
  **NeKI brief:** Explains Xamarin Studio with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Vitamins](http://ashfurrow.com/blog/objective-c-vitamins) — iOS Dev Weekly · Issue 79 — Article · Topics: Accessibility · Objective-C & Cocoa · Testing
  **Published:** `1st February 2013`
  **NeKI brief:** Explains Objective-C Vitamins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [RETrimControl](https://github.com/romaonthego/RETrimControl) — iOS Dev Weekly · Issue 78 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `25th January 2013`
  **NeKI brief:** Examines iOS audio trim control, similar to the one seen in default iPhone Voice Memos app. - romaonthego/RETrimControl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [RecordMyScreen](https://github.com/coolstar/RecordMyScreen) — iOS Dev Weekly · Issue 75 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `4th January 2013`
  **NeKI brief:** Examines Record the display even on non-jailbroken iPhones. - coolstar/RecordMyScreen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Saturday Soapbox: It just worked?](http://www.eurogamer.net/articles/2012-11-23-saturday-soapbox-it-just-worked) — iOS Dev Weekly · Issue 70 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th November 2012`
  **NeKI brief:** The page covers “Saturday Soapbox: It just worked?” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Fun with Face Detection](http://www.panic.com/blog/2012/11/fun-with-face-recognition) — iOS Dev Weekly · Issue 69 — Article · Topics: Graphics, Media & Games
  **Published:** `23rd November 2012`
  **NeKI brief:** Examines Panic Blog » Fun with Face Detection. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [MSCachedAsyncViewDrawing](https://github.com/mindsnacks/MSCachedAsyncViewDrawing) — iOS Dev Weekly · Issue 68 — Source repository · Topics: Concurrency · Developer Tools · Graphics, Media & Games
  **Published:** `16th November 2012`
  **NeKI brief:** Provides the MSCachedAsyncViewDrawing source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [What I Do With My iPad Part 2: Write With a Keyboard](http://prolost.com/ipadkeyboard) — iOS Dev Weekly · Issue 68 — Article · Topics: Graphics, Media & Games · Hardware & Devices
  **Published:** `16th November 2012`
  **NeKI brief:** Stu Maschwitz shows off his proof of concept video for how app switching could work on iOS when an external keyboard is in use. As iOS makes moves towards being a desktop replacement for more users I would love to see more attention paid to how it works with…
- [Seven Psychological Sins of SimCity Social](http://www.psychologyofgames.com/2012/07/seven-psychological-sins-of-simcity-social) — iOS Dev Weekly · Issue 64 — Article · Topics: Graphics, Media & Games
  **Published:** `19th October 2012`
  **NeKI brief:** Examines I have recently been hearing a lot about SimCity Social, the “Farmville with a candy coating of SimCity” game from Bigfish and EA. Mostly I’ve heard about how the. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SKBounceAnimation](https://github.com/khanlou/SKBounceAnimation) — iOS Dev Weekly · Issue 61 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `28th September 2012`
  **NeKI brief:** Provides the SKBounceAnimation source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Everything that’s wrong with the App Store in iOS 6](http://www.lightwoodgames.com/blog/2012/09/everything-thats-wrong-with-the-app-store-in-ios-6) — iOS Dev Weekly · Issue 61 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `28th September 2012`
  **NeKI brief:** Chris Newman on the new App Store in iOS 6 which really do make apps more difficult to discover. I was pleasantly surprised when I first used the iOS 6 store during the beta (ooh, new shiny) but the flaws quickly became apparent. I really hope there are some…
- [John Carmack on Software Development](http://www.youtube.com/watch?v=wt-iVFxgFWk&t=30m30s) — iOS Dev Weekly · Issue 56 — Video · Topics: Graphics, Media & Games
  **Published:** `24th August 2012`
  **NeKI brief:** The always fascinating John Carmack giving the Keynote at QuakeCon 2012 talking not about games but about the practicalities of software development. He does talk a little about iOS later but not enough to make it into a main section above. Fascinating talk…
- [Security, Sandboxing on OS X and App Development](http://www.infoq.com/interviews/lee-security) — iOS Dev Weekly · Issue 55 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Security & Privacy
  **Published:** `17th August 2012`
  **NeKI brief:** This video of the always entertaining and knowledgable Graham Lee being interviewed earlier this year at the goto conference in Copenhagen is worth a watch if you have even as passing interest in iOS security.
- [Collision Detection Using the Separating Axis Theorem](http://gamedev.tutsplus.com/tutorials/implementation/collision-detection-with-the-separating-axis-theorem) — iOS Dev Weekly · Issue 54 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `10th August 2012`
  **NeKI brief:** Explains Collision Detection Using the Separating Axis Theorem with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Zyngapocalypse Now (And What Comes Next?)](http://techcrunch.com/2012/08/04/zyngapocalypse-now-and-what-comes-next) — iOS Dev Weekly · Issue 54 — Article · Topics: Graphics, Media & Games
  **Published:** `10th August 2012`
  **NeKI brief:** Examines Editor's note: Tadhg Kelly is a game designer with 20 years experience. He is the creator of leading game design blog What Games Are, and consults for many companies on design. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [FutureFolio - Design of a Content Creation Tool](http://www.youtube.com/watch?v=ajgM9ZE0wGc) — iOS Dev Weekly · Issue 53 — Video · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd August 2012`
  **NeKI brief:** Paul Hudson of Future publishing talks about their iPad app which they use to build their digital publications. This is a slightly unusual link for here as this is pretty much a training video on how to use this app but I found it a fascinating look at how…
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Cocos2d v2.0 released](http://www.cocos2d-iphone.org/cocos2d-v2-0-released) — iOS Dev Weekly · Issue 50 — Article · Topics: Graphics, Media & Games
  **Published:** `13th July 2012`
  **NeKI brief:** OpenGL ES 2.0, better Retina display compatibility, integration of the Chipmunk and Box 2D physics engines and a whole load of other features. What’s not to like about this major new release of the most popular iOS 2D game framework?
- [WWDC Videos 2004-2008](http://oleb.net/blog/2012/07/wwdc-videos-2004-2008) — iOS Dev Weekly · Issue 50 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `13th July 2012`
  **NeKI brief:** Collects older WWDC videos from 2004 through 2008. Follow individual sessions for historical Apple-platform context, while using current documentation for supported APIs and behavior.
- [SCOtutor for ScreenFlow](http://www.screencastsonline.com/appstore) — iOS Dev Weekly · Issue 43 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `25th May 2012`
  **NeKI brief:** Explains SCOtutor for ScreenFlow with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Distributing 3000+ copies of an iOS game](http://sixtostart.com/onetoread/2012/distributing-3000-copies-of-an-ios-game) — iOS Dev Weekly · Issue 42 — Article · Topics: Graphics, Media & Games
  **Published:** `18th May 2012`
  **NeKI brief:** So how did Six to Start recently distribute 3000+ copies of their Kickstarter funded iOS game to the project backers? I am quite surprised Apple were OK with this, especially allowing pre-orders to continue outside of the Kickstarter project and as they say…
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
- [New Videos at developer.apple.com](http://oleb.net/blog/2012/01/new-videos-at-developer-apple-com) — iOS Dev Weekly · Issue 27 — Article · Topics: Graphics, Media & Games
  **Published:** `3rd February 2012`
  **NeKI brief:** I hadn’t noticed these new videos inspired by the recent Apple tech talks go online, great if you were one of the many who were not lucky enough to get a ticket.
- [FTCoreText](https://github.com/FuerteInternational/FTCoreText) — iOS Dev Weekly · Issue 27 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd February 2012`
  **NeKI brief:** Provides the FTCoreText source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Smart E-Book Interface Prototype Demo](http://www.youtube.com/watch?v=rVyBwz1-AiE) — iOS Dev Weekly · Issue 26 — Video · Topics: AI Development · Graphics, Media & Games
  **Published:** `27th January 2012`
  **NeKI brief:** Examines Smart E-Book Interface PrototypeContacts info: Sangtae Kim (expanne@gmail.com). Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Update 2011 Conference Videos](http://www.youtube.com/playlist?list=PL4850B9F46ADEFBE2) — iOS Dev Weekly · Issue 23 — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **Published:** `6th January 2012`
  **NeKI brief:** The YouTube playlist collects publicly viewable 2011 conference videos and exposes their session metadata without authentication.
- [Who Will Survive the Digital Tsunami?](http://www.gamesbrief.com/2011/11/who-will-survive-the-digital-tsunami) — iOS Dev Weekly · Issue 17 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `25th November 2011`
  **NeKI brief:** Nicholas Lovell with a look at the iOS games market and I can’t help but agree with his conclusions.
- [Beginning Core Image in iOS 5](http://www.raywenderlich.com/5689/beginning-core-image-in-ios-5) — iOS Dev Weekly · Issue 16 — Article · Topics: Graphics, Media & Games
  **Published:** `18th November 2011`
  **NeKI brief:** Explains Beginning Core Image in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS 5 Tech Talk: Allan Schaffer on OpenGL ES with GLKit](http://oleb.net/blog/2011/11/ios5-tech-talk-allan-schaffer-opengl-es-glkit) — iOS Dev Weekly · Issue 15 — Article · Topics: Graphics, Media & Games
  **Published:** `11th November 2011`
  **NeKI brief:** Explains iOS 5 Tech Talk Allan Schaffer on OpenGL ES with GLKit with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Beginning OpenGL ES 2.0 with GLKit Part 1](http://www.raywenderlich.com/5223/beginning-opengl-es-2-0-with-glkit-part-1) — iOS Dev Weekly · Issue 12 — Article · Topics: Graphics, Media & Games
  **Published:** `21st October 2011`
  **NeKI brief:** The page covers “Beginning OpenGL ES 2.0 with GLKit Part 1” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Creating an iTunes store style “jump” animation](http://stackoverflow.com/questions/6915702/creating-itunes-store-style-jump-animation) — iOS Dev Weekly · Issue 11 — Article · Topics: Graphics, Media & Games
  **Published:** `14th October 2011`
  **NeKI brief:** Explains Creating an iTunes store style jump animation with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Analytics For iOS Games](http://gamesfromwithin.com/analytics-for-ios-games) — iOS Dev Weekly · Issue 5 — Article · Topics: Graphics, Media & Games
  **Published:** `2nd September 2011`
  **NeKI brief:** Examines Noel Llopis with a great round up of analytics options for iOS apps. Plenty of options and I must admit that I hadn’t noticed Flurry was adding such a huge amount of weight to my app binaries! Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Core Animation Demos](https://github.com/bobmccune/Core-Animation-Demos) — iOS Dev Weekly · Issue 4 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th August 2011`
  **NeKI brief:** Presents Core Animation Demos, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Where to begin](http://mur.mu.rs/page6) — iOS Dev Weekly · Issue 3 — Article · Topics: Graphics, Media & Games
  **Published:** `19th August 2011`
  **NeKI brief:** The page is a publicly readable archive page containing the author's earlier posts and provides navigation into the site's technical writing.
- [Play](https://youtube.com/watch?v=qx5QWrKhxM8) — Not only Swift · Issue 98 — Video · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Demonstrates a Firebase bridge that makes Gemini models available through Apple’s Foundation Models-style API. Use it to compare a cloud-model fallback with on-device sessions while keeping authentication, privacy, latency, and API compatibility explicit.
- [Play](https://youtube.com/watch?v=Y_Ov-ddMb24) — Not only Swift · Issue 97 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Presents Natalia Panferova's five SwiftUI mental-model principles and associated anti-patterns, connecting structural choices to predictable updates, performance, and maintainability. Useful as architectural guidance for reasoning about complex view hierarchies.
- [The SwiftUI Way](https://books.nilcoalescing.com/the-swiftui-way) — Not only Swift · Issue 97 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** The SwiftUI Way targets experienced developers with production patterns and anti-patterns informed by SwiftUI framework experience. Use it when evaluating a complex view architecture rather than looking up an isolated control API.
- [The Firebase API Council](https://go.peterfriese.dev/the-firebase-api-council?s=newsletter&t=ext) — Not only Swift · Issue 97 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Introduces the Firebase API Council and its role in shaping Firebase APIs through community feedback. It provides ecosystem context for developers evaluating Firebase integration and API direction.
- [Understanding Firebase API Keys and how to restrict them](https://firebase.google.com/docs/projects/api-keys) — Not only Swift · Issue 95 — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Documents Firebase API keys, their intended identification role, and the controls developers should use to restrict exposure. It is a practical reference for configuring API-key restrictions in an Apple-platform Firebase project.
- [Get started with Firebase App Check for Apple Platforms](https://firebase.google.com/docs/app-check/ios) — Not only Swift · Issue 95 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Explains how to configure Firebase App Check for Apple platforms so backend resources can distinguish traffic from authentic app instances. Use it when adding app-attestation protections around Firebase services.
- [VecturaKit](https://github.com/rryam/VecturaKit) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Graphics, Media & Games
  **NeKI brief:** Provides the public source repository for VecturaKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Flexible rich text rendering in SwiftUI](https://github.com/gonzalezreal/textual) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers rich attributed-text rendering in SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers the maintenance status and migration path from Swift Markdown UI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [I highly recommend it](https://youtu.be/GD0Z4YzVVkg?si=07NykgSrrPCqNUyF&t=2375) — Not only Swift · Issue 89 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This recorded segment demonstrates rich Markdown rendering in SwiftUI with Guille Gonzalez's swift-markdown-ui library. It is useful for evaluating how Markdown content can be converted into native SwiftUI views and integrated into an application UI.
- [Second Brain app](https://www.youtube.com/playlist?list=PLsnLd2esiGRTmfGZcZMnEy6hkBHXBH_en) — Not only Swift · Issue 85 — Video · Topics: Graphics, Media & Games · Liquid Glass · Swift
  **NeKI brief:** Follows a SwiftUI second-brain app built with Firestore sync, Gemini summaries and questions, Genkit integration, and Siri access. The playlist shows those services evolving together inside a real project.
- [this first video](https://www.youtube.com/watch?v=ukyUxcXlwaI) — Not only Swift · Issue 85 — Video · Topics: AI Development · Graphics, Media & Games · Product Design
  **NeKI brief:** This episode of the Building a Second Brain app series explores strategies for implementing Firebase AI Logic on iOS. The recording provides a concrete discussion of integrating model-backed features into a Swift application and the design choices around those strategies.
- [this repository](https://github.com/FirebaseExtended/firebase-video-samples/tree/main/firebase-ai-friendly-meals/apple) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **NeKI brief:** Contains the Apple client sample for Firebase AI Friendly Meals, showing practical integration boundaries around Firebase services and SwiftUI. Inspect it for a runnable reference, then check current SDK setup and security guidance.
- [Foundation Models Playgrounds: Comprehensive Examples for Apple's AI Framework](https://github.com/IvanCampos/Foundation-Models-Playgrounds) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers Foundation Models Framework examples for Apple-platform development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [way they made hard copies](https://youtu.be/_FlvwC1dkzc?si=Ugf_cIr3sWEoNNIX&t=285) — Not only Swift · Issue 85 — Video · Topics: Graphics, Media & Games
  **NeKI brief:** This historical recording documents telecommunications work associated with the Post Office Research Station in Dollis Hill. It provides technical and institutional context for the research station referenced by the source, rather than being a current product or event listing.
- [working from home](https://youtu.be/_FlvwC1dkzc?si=40UFFkeKRircJe8t&t=468) — Not only Swift · Issue 85 — Video · Topics: Graphics, Media & Games
  **NeKI brief:** This historical recording documents telecommunications work associated with the Post Office Research Station in Dollis Hill. It provides technical and institutional context for the research station referenced by the source, rather than being a current product or event listing.
- [Olleh: Ollama-compatible CLI for Apple's Foundation Models](https://github.com/loopwork/olleh) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers an Ollama-compatible command-line interface for Apple Foundation Models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [write-up](https://wwdcnotes.com/documentation/wwdcnotes/wwdc21-10022-demystify-swiftui) — Not only Swift · Issue 76 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** This article covers the WWDC session Demystify SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [RenderMeThis: SwiftUI Debugging Tool](https://github.com/Aeastr/RenderMeThis) — Not only Swift · Issue 76 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers visualizing SwiftUI rendering, layouts, and measurements with Loupe. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
