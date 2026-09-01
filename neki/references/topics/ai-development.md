# AI Development

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Apple Intelligence, Foundation Models, ML, generative-AI workflows, and developer tooling.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **416**

## Direct-source reading

- [From Using AI to Delegating Work to AI (Part 2) - What I Mean by Delegability](https://fatbobman.com/en/posts/from-using-ai-to-delegating-work-to-ai-2) — Fatbobman · article catalogue
  **Published:** `2026-08-19T14:00:00.000Z`
  **NeKI brief:** Defines delegability through a deterministic runtime, durable task records, isolated contexts, and explicit handoffs. It clarifies why models may assess actions but cannot infer authorization, and where policy should constrain state-changing work.
- [From Using AI to Delegating Work to AI (Part 1) - Why I No Longer Wait for Stronger Models](https://fatbobman.com/en/posts/from-using-ai-to-delegating-work-to-ai) — Fatbobman · article catalogue
  **Published:** `2026-08-19T14:00:00.000Z`
  **NeKI brief:** Frames delegation as a systems problem rather than a model-capability race, identifying context drift, rule decay, and ambiguous authority. Useful for moving stable facts and enforceable checks into external tools while reserving intent and approvals for people.
- [The Skills Conundrum | Swiftjective-C](https://swiftjectivec.com/The-Skills-Conundrum) — Swiftjective-C · article catalogue
  **Published:** `2026-08-10T00:00:00-05:00`
  **NeKI brief:** Describes a Git-repository workflow for synchronizing personal and third-party agent skills across harnesses and multiple Macs through dedicated push, pull and npx-update skills.
- [How to free up Xcode disk space safely with an AI Agent - SwiftLee](https://www.avanderlee.com/ai-development/how-to-free-up-xcode-disk-space-safely-with-an-ai-agent) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-07-27T08:34:16+00:00`
  **NeKI brief:** Presents an audit-first Xcode cleanup skill that inventories Derived Data, simulators, runtimes, archives, and caches with stable evidence before itemised approval. It preserves distributed archives, revalidates candidates, and separates recoverable trash moves from irreversible simulator operations.
- [Core ML and Vision Tutorial: On-device training on iOS | Kodeco](https://www.kodeco.com/7960296-core-ml-and-vision-tutorial-on-device-training-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combines Core ML model integration with Vision image handling and on-device fine-tuning. Use it to trace the boundary between a bundled model, camera or image preprocessing, and personalization performed locally on an iOS device.
- [Natural Language Processing on iOS with Turi Create | Kodeco](https://www.kodeco.com/5213-natural-language-processing-on-ios-with-turi-create) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Walks from a text dataset through Turi Create training and Core ML export into an iOS classifier. Follow it when evaluating the older train-on-Mac, infer-on-device workflow for sentiment or other text labels.
- [iOS 11: NLP with Core ML | Kodeco](https://www.kodeco.com/5038-ios-11-nlp-with-core-ml) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates sentiment classification of movie reviews with the original iOS 11 Core ML NLP stack. It is useful for understanding the historical accessibility of text inference, while checking model and tokenizer APIs against current SDKs.
- [Getting Started with iOS App Observability | Kodeco](https://www.kodeco.com/49535198-getting-started-with-ios-app-observability) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Despite its misleading catalogue title, the saved page describes Foundation Models integration with structured generation and OpenTelemetry setup. Use it to separate model-feature instrumentation from generic app observability before relying on the tutorial.
- [CreateML Tutorial for iOS: Creating a Customized Image Filter using Style Transfer | Kodeco](https://www.kodeco.com/34375110-createml-tutorial-for-ios-creating-a-customized-image-filter-using-style-transfer) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows the style-transfer pipeline from preparing representative image data to training a Create ML model and applying it on-device. Follow it when prototyping custom visual filters and assessing dataset effort before runtime integration.
- [Machine Learning in iOS | Kodeco](https://www.kodeco.com/1320561-machine-learning-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Surveys an older end-to-end Core ML and Create ML course, including Turi Create and model use for data analysis. Use it as a broad map of the training-versus-inference workflow, not current API documentation.
- [Using Cursor in Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Pol Piella · article catalogue
  **Published:** `2026-06-26T00:00:00.000Z`
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [Training an LLM in Swift, Part 2: macOS built-in frameworks | Cocoa with Love](https://www.cocoawithlove.com/blog/macos-ml-frameworks.html) — Cocoa with Love · article catalogue
  **Published:** `2026-06-08`
  **NeKI brief:** Benchmarks Accelerate, BNNS, Core ML, and MPSGraph while implementing GPT-2 components on macOS. The comparison shows which built-in framework fits matrix math, neural-network kernels, or model execution when building Swift ML experiments.
- [WWDC 2026: My predictions and wishes](https://www.avanderlee.com/wwdc/wwdc-2026-my-predictions-and-wishes) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-06-02T08:36:35+00:00`
  **NeKI brief:** Previews possible WWDC directions around Xcode agentic development, App Store Connect MCP, App Intents, and official agent tooling. Use it as a hypothesis checklist before validating announced capabilities in primary Apple sessions.
- [Training an LLM in Swift, Part 1: Taking matrix multiplication from Gflop/s to Tflop/s | Cocoa with Love](https://www.cocoawithlove.com/blog/matrix-multiplications-swift.html) — Cocoa with Love · article catalogue
  **Published:** `2026-04-18`
  **NeKI brief:** Implements matrix multiplication ten ways, moving from straightforward C and Swift loops to vectorized Accelerate and Metal kernels. The measurements make optimization costs visible and provide a useful baseline for deciding when GPU work is justified.
- [The "One More Prompt" risk of agentic coding](https://www.avanderlee.com/ai-development/the-one-more-prompt-risk-of-agentic-coding) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-03-23T10:48:10+00:00`
  **NeKI brief:** Examines how repeated follow-up prompts can expand an agentic coding task beyond its original scope, increasing churn and regressions. The discussion offers a useful boundary-setting heuristic for deciding when to stop prompting and review the diff.
- [Agentic Development: Multi-Project Challenges - SwiftLee](https://www.avanderlee.com/ai-development/agentic-development-multi-project-challenges) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-03-16T13:11:45+00:00`
  **NeKI brief:** Describes the coordination problems agents encounter across multiple repositories, such as context switching, inconsistent conventions, and shared tooling. The proposed workflow helps structure project boundaries before delegating changes that span codebases.
- [Using an MCP to perform product optimizations - SwiftLee](https://www.avanderlee.com/ai-development/using-an-mcp-to-perform-product-optimizations) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-03-02T13:56:03+00:00`
  **NeKI brief:** Illustrates using an MCP server to connect product data with an optimization workflow, from querying evidence to evaluating an intervention. The article helps distinguish tool integration that improves decisions from automation that merely adds another interface.
- [Setting up a delivery pipeline for your agentic iOS projects – Donny Wals](https://www.donnywals.com/setting-up-a-delivery-pipeline-for-your-agentic-ios-projects) — Donny Wals · article catalogue
  **Published:** `2026-02-16T07:00:39+00:00`
  **NeKI brief:** Connects agentic planning and local setup with BugBot pull-request review, Bitrise builds, and rapid TestFlight feedback. Use it to design a delivery loop where generated changes meet automated gates before human device validation.
- [Agentic coding in Xcode | Swift with Majid](https://swiftwithmajid.com/2026/02/10/agentic-coding-in-xcode) — Swift with Majid · article catalogue
  **Published:** `2026-02-10T00:00:00+00:00`
  **NeKI brief:** Details configuring Xcode 26.3’s agentic coding support and practical habits for delegating Apple-platform work. Follow it when establishing project context, reviewing generated diffs, and keeping Xcode’s agent actions inside an auditable workflow.
- [Agentic AI Engineering Workflows for iOS in 2026](https://blog.jacobstechtavern.com/p/agentic-ai-2026) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-02-09T16:02:05.965Z`
  **NeKI brief:** Frames agentic iOS workflows around bounded tool access, reviewable changes, and feedback loops, helping teams distinguish useful automation from uncontrolled code generation and retain ownership of architecture, testing, and release decisions.
- [Xcode 26.3 + Claude Agent - Model Swapping,MCP, Skills, and Adaptive Configuration](https://fatbobman.com/en/posts/xcode-263-claude) — Fatbobman · article catalogue
  **Published:** `2026-02-06T02:30:00.000Z`
  **NeKI brief:** Experiments with Claude inside Xcode 26.3 through model substitution, injected MCP tools, shared skill symlinks, environment setup, and adaptive CLAUDE.md guidance. The article distinguishes supported integration from brittle configuration techniques.
- [Agentic Coding in Xcode 26.3 with Claude Code and Codex | Swiftjective-C](https://swiftjectivec.com/Agentic-Coding-Codex-Claude-Code-in-Xcode) — Swiftjective-C · article catalogue
  **Published:** `2026-02-04T00:00:00-06:00`
  **NeKI brief:** Introduces Xcode 26.3’s built-in agent support through Claude Code and Codex. Use it for a tool-oriented comparison of in-editor conversations, command execution, and the review boundaries needed when agents modify an existing project.
- [Have LLMs improved for Swift coding in the last 12 months? | Cocoa with Love](https://www.cocoawithlove.com/blog/llms-twelve-months-later.html) — Cocoa with Love · article catalogue
  **Published:** `2025-12-29`
  **NeKI brief:** Re-tests several hosted and local LLMs on Swift tasks, including prompting an entire app and comparing model-specific behavior. Follow it for qualitative workflow evidence, not a stable benchmark, and reproduce tests on your own codebase.
- [Building AI features using Foundation Models. Streaming. | Swift with Majid](https://swiftwithmajid.com/2025/10/08/building-ai-features-using-foundation-models-streaming) — Swift with Majid · article catalogue
  **Published:** `2025-10-08T00:00:00+00:00`
  **NeKI brief:** Shows how Foundation Models streams partial generated results rather than waiting for one completed response. Use it when designing incremental SwiftUI updates, cancellation behavior, and UI state for model output that arrives over time.
- [Building AI features using Foundation Models. Structured Content. | Swift with Majid](https://swiftwithmajid.com/2025/08/26/building-ai-features-using-foundation-models-structured-content) — Swift with Majid · article catalogue
  **Published:** `2025-08-26T00:00:00+00:00`
  **NeKI brief:** Uses Foundation Models to generate structured Swift content instead of unconstrained text. Useful for reliable AI-driven UI or data flows where decoding and validation must remain deterministic.
- [Building AI features using Foundation Models | Swift with Majid](https://swiftwithmajid.com/2025/08/19/building-ai-features-using-foundation-models) — Swift with Majid · article catalogue
  **Published:** `2025-08-19T00:00:00+00:00`
  **NeKI brief:** Builds application features with Apple's Foundation Models framework, covering model sessions and generated responses. Useful for evaluating on-device intelligence while keeping availability and privacy boundaries explicit.
- [Exploring the Foundation Models framework](https://www.createwithswift.com/exploring-the-foundation-models-framework) — Create with Swift · article catalogue
  **Published:** `2025-08-07T13:00:24.000Z`
  **NeKI brief:** Introduces Apple's Foundation Models framework and its on-device language-model capabilities. Useful for mapping model sessions, availability, and structured generation before integrating AI into an app.
- [AI Git Narrator: Explain Your Code’s Journey With AI Narration - iOS Dev Tools](https://iosdev.tools/blog/aigitnarrator) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T14:26:38+00:00`
  **NeKI brief:** Profiles AI Git Narrator as explain Your Code’s Journey With AI Narration. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Dancing with AI - My Month with Claude Code](https://fatbobman.com/en/posts/dancing-with-ai-my-month-with-claude-code) — Fatbobman · article catalogue
  **Published:** `2025-07-02T14:12:00.000Z`
  **NeKI brief:** Reflects on a month using Claude Code while emphasizing active programming judgment and the risk of becoming a spectator. Use it to evaluate where agent speed supports learning versus where it erodes technical understanding.
- [WWDC 2025: What's new for the Apple community?](https://www.createwithswift.com/wwdc-2025-whats-new-for-the-apple-community) — Create with Swift · article catalogue
  **Published:** `2025-06-13T13:57:48.000Z`
  **NeKI brief:** Surveys WWDC 2025 changes across Liquid Glass, Icon Composer, accessibility, Apple Intelligence, Xcode, Swift, and SwiftUI. Use the cross-topic index to identify follow-up implementation areas, then consult authoritative session documentation.
- [WWDC 2025 First Impressions - As Expected, Yet Unexpected](https://fatbobman.com/en/posts/wwdc-2025-first-impressions) — Fatbobman · article catalogue
  **Published:** `2025-06-11T00:12:00.000Z`
  **NeKI brief:** Offers first impressions of WWDC 2025 through Liquid Glass, SwiftUI, SwiftData, Foundation Models, and macros. Follow it for ecosystem-level context and competing priorities, not as a substitute for API-level migration guidance.
- [I trapped your soul in a trading card (with client-side AI)](https://blog.jacobstechtavern.com/p/i-turned-you-into-a-trading-card) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-06-02T15:02:23.930Z`
  **NeKI brief:** Builds a client-side AI trading-card experience by combining user input, image or model generation, and local presentation, highlighting privacy, prompt handling, and capability constraints when inference occurs on device.
- [Designing for Apple Intelligence: Extending your app features to the system](https://www.createwithswift.com/designing-for-apple-intelligence-enabling-your-app-features-beyond-the-app) — Create with Swift · article catalogue
  **Published:** `2025-03-25T14:03:24.000Z`
  **NeKI brief:** Explains extending app capabilities into system surfaces through Apple Intelligence-era integrations. Use it to reason about which user actions belong in the app versus discoverable system experiences, then verify supported App Intents APIs.
- [Track the horizon angle in an image with the Vision framework](https://www.createwithswift.com/track-the-horizon-angle-in-an-image-with-the-vision-framework) — Create with Swift · article catalogue
  **Published:** `2025-03-11T14:00:12.000Z`
  **NeKI brief:** Builds a SwiftUI feature that detects an image’s horizon angle with Vision. Follow it when routing image analysis results into view state, while checking orientation and coordinate conventions for camera or imported-image inputs.
- [Creating App Intents using Assistant Schemas](https://www.createwithswift.com/creating-app-intents-using-assistant-schemas) — Create with Swift · article catalogue
  **Published:** `2025-03-07T14:08:58.000Z`
  **NeKI brief:** Uses @AssistantSchema to declare App Intents that can integrate with system and Apple Intelligence experiences. Follow it when deciding how intent parameters and metadata should expose an existing feature without duplicating business logic.
- [Model Context Protocol (MCP) - NSHipster](https://nshipster.com/model-context-protocol) — NSHipster · article catalogue
  **Published:** `2025-03-07T00:00:00-08:00`
  **NeKI brief:** Introduces Model Context Protocol as a standardized way for AI clients to discover tools and context providers, analogous to LSP's role for language tooling. Follow it for architectural vocabulary, then verify security and capability details against current protocol documentation.
- [Ollama - NSHipster](https://nshipster.com/ollama) — NSHipster · article catalogue
  **Published:** `2025-02-14T00:00:00-08:00`
  **NeKI brief:** Shows how Ollama runs local language models on a Mac and exposes them to developer workflows without sending prompts to a hosted service. The trade-off is a concrete starting point for evaluating privacy, hardware, and model-quality constraints.
- [How I Stole Your ChatGPT API Keys](https://blog.jacobstechtavern.com/p/how-i-stole-your-api-keys) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-01-27T17:15:45.206Z`
  **NeKI brief:** Demonstrates how client-shipped AI API keys can be extracted and abused, motivating server-side credential custody, scoped tokens, usage controls, and threat modeling rather than treating mobile application binaries as secret storage.
- [Take on Apple Intelligence at Unwrap Live 2025 – Hacking with Swift](https://www.hackingwithswift.com/articles/274/take-on-apple-intelligence-at-unwrap-live-2025) — Hacking with Swift articles · article catalogue
  **Published:** `2025-01-09T12:14:22+00:00`
  **NeKI brief:** Summarizes Unwrap Live material on App Intents, Image Playground, and Apple Intelligence app integration. Use it as an event-oriented route into feature possibilities, then validate platform availability and entitlement requirements in Apple documentation.
- [Using Copilot to write a raindrop audio synthesizer using AVAudioEngine | Cocoa with Love](https://www.cocoawithlove.com/blog/copilot-raindrop-generator.html) — Cocoa with Love · article catalogue
  **Published:** `2024-12-25`
  **NeKI brief:** Uses Copilot to build an AVAudioEngine raindrop synthesizer, chart its waveform, add noise, and repair thread-safety issues. Follow it to study AI-assisted iteration where generated code still needs audio-domain validation and concurrency cleanup.
- [Bringing Image Playground to your app](https://www.createwithswift.com/bringing-image-playground-to-your-app) — Create with Swift · article catalogue
  **Published:** `2024-12-12T14:49:30.000Z`
  **NeKI brief:** Shows the integration steps for invoking Image Playground from an app and generating images with Apple Intelligence. Follow it when designing the system handoff, user controls, and availability fallback around image creation.
- [Exploring Apple Intelligence: Image Generation](https://www.createwithswift.com/exploring-apple-intelligence-image-generation) — Create with Swift · article catalogue
  **Published:** `2024-12-05T14:30:11.000Z`
  **NeKI brief:** Compares Image Playground, Image Wand, and Genmoji as Apple Intelligence image-generation surfaces. Use it to distinguish system experiences and choose the appropriate entry point before implementing app-specific creative workflows.
- [Exploring Apple Intelligence: Talking with Siri](https://www.createwithswift.com/exploring-apple-intelligence-talking-with-siri) — Create with Swift · article catalogue
  **Published:** `2024-11-15T14:28:23.000Z`
  **NeKI brief:** Explores the redesigned Siri experience and extending app features into Siri interactions. Follow it when mapping conversational entry points to App Intents while preserving clear, non-conversational fallbacks inside the app.
- [Exploring Apple Intelligence: Writing Tools](https://www.createwithswift.com/exploring-apple-intelligence-writing-tools) — Create with Swift · article catalogue
  **Published:** `2024-11-01T19:17:12.000Z`
  **NeKI brief:** Covers Writing Tools across SwiftUI and UIKit, including intelligent animation and ecosystem integration. Use it to compare framework-specific adoption paths and identify where text-editing controls can inherit system writing assistance.
- [WWDC 2024: What's new in the Swift community?](https://www.createwithswift.com/wwdc-2024-whats-new-in-the-swift-community) — Create with Swift · article catalogue
  **Published:** `2024-06-14T15:02:34.000Z`
  **NeKI brief:** Indexes WWDC 2024 highlights across Swift language changes, Apple Intelligence, spatial computing, accessibility, and SwiftUI. Follow the relevant sections to prioritize deeper migration research instead of treating the roundup as API reference.
- [ChatGPT for Swift: Top 5 code generation prompts](https://www.avanderlee.com/swift/chatgpt-code-generation-prompts) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-05-28T07:00:00+00:00`
  **NeKI brief:** Presents five prompt patterns for generating Swift code, then stresses supplying context, constraints, and tests so output can be reviewed. Useful as a practical checklist for making AI-assisted coding reproducible rather than speculative.
- [Using server-side Swift for machine learning processing](https://www.createwithswift.com/using-server-side-swift-machine-learning-processing) — Create with Swift · article catalogue
  **Published:** `2024-04-18T14:00:32.000Z`
  **NeKI brief:** Builds a Vapor server route that loads a Core ML model, performs classification, and serves a Swift client. Follow it when deciding whether inference belongs on-device or behind a Swift backend boundary.
- [Pair Programming with AI](https://fatbobman.com/en/posts/pari-programming-with-ai) — Fatbobman · article catalogue
  **Published:** `2023-11-23T00:12:00.000Z`
  **NeKI brief:** Describes rebuilding a blog with ChatGPT, Copilot, and Claude as collaborative programming tools while learning unfamiliar technologies. Use it to examine task decomposition and verification habits, not to infer production-level model reliability.
- [Welcome to Jacob’s Tech Tavern! 🍺](https://blog.jacobstechtavern.com/p/aviator-demo-video) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-10-14T14:29:06.846Z`
  **NeKI brief:** Introduces a newsletter focused on Swift concurrency, agentic engineering, SwiftUI, and iOS performance. Follow it as a routing point for future deep-dive articles rather than as evidence for a specific implementation decision.
- [The Machine Learning Landscape on iOS | Swiftjective-C](https://swiftjectivec.com/Machine-Learning-on-iOS-API-Surface-Area) — Swiftjective-C · article catalogue
  **Published:** `2023-07-26T00:00:00-05:00`
  **NeKI brief:** Surveys the breadth of iOS machine-learning APIs beyond Core ML, framing the platform as a large selection surface. Use it to identify candidate frameworks before narrowing a feature to Vision, Natural Language, Create ML, or related tools.
- [Using TabularData to Dump Model Data | Swiftjective-C](https://swiftjectivec.com/Using-the-TabularData-Framework-to-Dump-json-or-csv-Data-in-Swift) — Swiftjective-C · article catalogue
  **Published:** `2023-05-04T00:00:00-05:00`
  **NeKI brief:** Repurposes TabularData to inspect model data and emit JSON or CSV-style debug output. Follow it when structured tabular dumps are more useful than Mirror or print for diagnosing ML inputs and intermediate results.
- [AI Services that I am Currently Using](https://fatbobman.com/en/posts/ai-services-i-am-currently-using) — Fatbobman · article catalogue
  **Published:** `2023-04-11T00:12:00.000Z`
  **NeKI brief:** Reviews a personal mix of Copilot for Xcode, Notion AI, Warp AI, MidJourney, and ChatGPT. Use it to compare tool roles across coding, writing, terminal work, and media, while treating preferences as anecdotal.
- [Creating a SwiftUI App to interact with the OpenAI ChatGPT API](https://www.createwithswift.com/building-a-swiftui-app-to-interact-with-the-openai-chatgpt-api) — Create with Swift · article catalogue
  **Published:** `2023-02-14T09:44:19.000Z`
  **NeKI brief:** Builds a small SwiftUI client around a Swift OpenAI package and a test interface for ChatGPT requests. Follow it to trace request-to-view-state wiring, while replacing exposed-key patterns with a secure service boundary.
- [ForEach Thought: Volume 1 | Swiftjective-C](https://swiftjectivec.com/ForEachThoughtVolume1) — Swiftjective-C · article catalogue
  **Published:** `2023-02-12T00:00:00-06:00`
  **NeKI brief:** Uses ChatGPT as a coding companion for a SwiftUI typewriter effect, alongside Xcode key mapping and bar-button observations. Follow it as an early example of targeted assistance that still requires developer-directed review.
- [Prototyping SwiftUI interfaces with OpenAI's ChatGPT](https://www.createwithswift.com/prototyping-swiftui-interfaces-with-openais-chatgpt) — Create with Swift · article catalogue
  **Published:** `2022-12-03T18:00:18.000Z`
  **NeKI brief:** Demonstrates using conversational prompts to scaffold SwiftUI code, making the gap between an idea and a runnable prototype smaller. Follow it to assess where generated UI accelerates exploration and where compile-time review remains essential.
- [Leveraging Sound Analysis to the Tune of 300 Sounds | Swiftjective-C](https://swiftjectivec.com/Sound-Analysis-Framework-Built-In-Model) — Swiftjective-C · article catalogue
  **Published:** `2022-04-11T00:00:00-05:00`
  **NeKI brief:** Introduces SoundAnalysis's built-in classifier for recognizing hundreds of sound categories, including live-stream analysis with SNAudioStreamAnalyzer. Use it when choosing between Apple's ready-made acoustic model and training a narrower custom detector.
- [Create with Swift at Swift Heroes 2021](https://www.createwithswift.com/create-with-swift-at-swift-heroes-2021) — Create with Swift · article catalogue
  **Published:** `2021-06-18T06:53:00.000Z`
  **NeKI brief:** Condenses a Core ML workshop covering Vision, Natural Language, Speech, Sound Analysis, and Create ML object detection. Use it as a map of Apple's older high-level ML APIs before selecting the framework matching a particular input modality.
- [Using an Object Detection Machine Learning Model in an iOS App](https://www.createwithswift.com/tutorial-core-ml-using-an-object-detection-machine-learning-model-in-an-ios-app) — Create with Swift · article catalogue
  **Published:** `2021-06-16T09:23:43.000Z`
  **NeKI brief:** Walks from a bundled object-detection model through Vision requests and camera or image inputs, including bounding-box results. Follow it to understand the application-side pipeline before swapping in a custom .mlmodel.
- [Using an Image Classification Machine Learning Model in an iOS App with SwiftUI](https://www.createwithswift.com/tutorial-core-ml-using-an-image-classification-machine-learning-model-in-an-ios-app-with-swiftui) — Create with Swift · article catalogue
  **Published:** `2021-06-16T09:23:10.000Z`
  **NeKI brief:** Connects an Apple image-classification model to a SwiftUI app, including image preparation and prediction display. Use it to trace the boundary between model input conversion, Core ML inference, and view state updates.
- [Using an Image Classification Machine Learning Model in Swift Playgrounds](https://www.createwithswift.com/using-an-image-classification-machine-learning-model-in-swift-playgrounds) — Create with Swift · article catalogue
  **Published:** `2021-06-16T09:22:42.000Z`
  **NeKI brief:** Shows image classification in a Swift Playground using a compiled MobileNet-style model and the required pixel dimensions and image types. Follow it for a lightweight, inspectable experiment before integrating inference into an app target.
- [Using an Object Detection Machine Learning Model in Swift Playgrounds](https://www.createwithswift.com/using-an-object-detection-machine-learning-model-in-swift-playgrounds) — Create with Swift · article catalogue
  **Published:** `2021-06-16T09:22:00.000Z`
  **NeKI brief:** Adapts object detection to Swift Playgrounds with YOLOv3 and Vision, including conversion to pixel-buffer inputs and observation handling. Use it to isolate model-and-request behavior without first building camera UI or app architecture.
- [Creating an Object Detection Machine Learning Model with Create ML](https://www.createwithswift.com/creating-an-object-detection-machine-learning-model-with-create-ml) — Create with Swift · article catalogue
  **Published:** `2021-06-16T08:21:42.000Z`
  **NeKI brief:** Covers assembling an object-detection dataset in Create ML, evaluating the trained model, and exporting a Core ML artifact. Follow it when the key question is data preparation and validation rather than runtime Vision code.
- [Create ML Explained: Apple's Toolchain to Build and Train Machine Learning Models](https://www.createwithswift.com/create-ml-explained-apples-toolchain-to-build-and-train-machine-learning-models) — Create with Swift · article catalogue
  **Published:** `2021-06-16T07:51:28.000Z`
  **NeKI brief:** Surveys Create ML templates, the macOS app workflow, and computer-vision model types. Use it to compare supported training tasks and decide whether a problem fits Create ML before writing a custom training pipeline.
- [Core ML Explained: Apple's Machine Learning Framework](https://www.createwithswift.com/core-ml-explained-apples-machine-learning-framework) — Create with Swift · article catalogue
  **Published:** `2021-06-16T07:50:35.000Z`
  **NeKI brief:** Explains Core ML's model execution path, conversion options, and integration features for on-device inference. Follow it to separate model packaging and runtime constraints from the higher-level Vision or Natural Language APIs around them.
- [How to perform regression analysis using Create ML – Hacking with Swift](https://www.hackingwithswift.com/articles/145/how-to-perform-regression-analysis-using-create-ml) — Hacking with Swift articles · article catalogue
  **Published:** `2018-12-29T10:46:04+00:00`
  **NeKI brief:** Uses Create ML's tabular-regression workflow to train a predictor with relatively little code. Follow it for a concrete introduction to preparing numeric training data and evaluating predictions before considering more elaborate ML tooling.
- [NLLanguageRecognizer - NSHipster](https://nshipster.com/nllanguagerecognizer) — NSHipster · article catalogue
  **Published:** `2018-08-06T00:00:00-07:00`
  **NeKI brief:** Explores NLLanguageRecognizer for identifying the language of text, alongside neighboring Natural Language and speech-related APIs. Use it when routing multilingual input or deciding which lightweight Apple NLP capability fits a text-processing step.
- [Getting started with Apple's Foundation Models framework](https://tanaschita.com/foundation-models-getting-started) — Tanaschita · article catalogue
  **NeKI brief:** Introduces Apple's Foundation Models framework, its on-device model context, and when it differs from other AI approaches. Follow it for an initial API and capability orientation, then verify deployment requirements against current Apple documentation.
- [Get started with Create ML to train a machine learning model in iOS](https://tanaschita.com/20230403-train-ml-model-with-create-ml-ios) — Tanaschita · article catalogue
  **NeKI brief:** Shows training a Create ML model and integrating its output into an iOS app. Follow it when routing dataset preparation, model export, and on-device inference responsibilities across the development workflow.
- [Developer guide on machine learning for iOS with Core ML](https://tanaschita.com/20230313-machine-learning-ios-core-ml) — Tanaschita · article catalogue
  **NeKI brief:** Provides an introductory path from basic machine-learning concepts to loading and using Core ML models in iOS. Follow it when onboarding to the model-consumption boundary, but treat current API and deployment details as version-sensitive.
- [Apple Foundation Models: Hybrid AI with Dynamic Profiles](https://peterfriese.dev/blog/2026/hybrid-ai-apple-foundation-models-gemini) — Peter Friese articles · article catalogue
  **NeKI brief:** Uses Foundation Models dynamic profiles to choose between an on-device model and Gemini through Firebase AI Logic. The design makes privacy, capability, availability, and network trade-offs explicit at the request-routing boundary.
- [Agentic Coding in Xcode with Gemini CLI](https://peterfriese.dev/blog/2026/agentic-coding-xcode-geminicli) — Peter Friese articles · article catalogue
  **NeKI brief:** Connects Gemini CLI to Xcode 26.3 through Apple's MCP bridge and walks through an emoji physics example. The setup highlights version and response-format requirements that matter when using agents other than Xcode's built-in integrations.
- [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://peterfriese.dev/blog/2025/gemini-genkit-pdf-structured-data) — Peter Friese articles · article catalogue
  **NeKI brief:** Demonstrates extracting structured data from PDFs with Gemini 2.0 and Genkit. Useful for assessing document-ingestion workflows, schema validation, and error handling before integrating model-produced fields into an app's trusted domain model.
- [Vibe Coding vs. Engineering](https://martiancraft.com/blog/2026/07/vibe-coding-vs-engineering) — MartianCraft · article catalogue
  **NeKI brief:** Contrasts fast AI-assisted prototyping with the engineering work needed to understand, secure, and maintain the resulting system. The article is a useful checklist for deciding where review, testing, and human ownership remain essential.
- [WWDC26 Recap: Siri Grows Up, Apple Intelligence Goes Everywhere, and Agents Move into Xcode](https://martiancraft.com/blog/2026/06/wwdc-26-recap-siri-grows-up-apple-intelligence-goes-everywhere-and-agents-move-Into-xcode) — MartianCraft · article catalogue
  **NeKI brief:** Summarizes WWDC26 changes across Siri, Apple Intelligence, and agentic Xcode workflows, connecting platform announcements to practical development consequences. Use it as a map of topics to verify in the corresponding Apple sessions and documentation.
- [MartianCraft on WWDC26: What Caught Our Eye](https://martiancraft.com/blog/2026/06/mc-on-wwdc26) — MartianCraft · article catalogue
  **NeKI brief:** Collects MartianCraft's WWDC26 implementation observations, including SwiftData and design changes that can be easy to miss in keynote coverage. It helps prioritize follow-up experiments while keeping the team's perspective separate from Apple API guidance.
- [What we are looking forward to from WWDC 26](https://martiancraft.com/blog/2026/06/looking-forward-to-wwdc-26) — MartianCraft · article catalogue
  **NeKI brief:** Records pre-WWDC expectations that a more capable Siri and App Intents orchestration could make cross-app actions a major developer surface. Use it as historical context for comparing predictions with the eventual platform direction.
- [Xcode 26.3: What are MCP and Agentic Development, and How Do You Get Started?](https://martiancraft.com/blog/2026/03/xcode26-3-what-is-mcp-and-agentic-development) — MartianCraft · article catalogue
  **NeKI brief:** Explains how Xcode 26.3 exposes project context to coding agents through MCP and frames the workflow beyond copy-and-paste prompts. Follow it to understand setup and trust boundaries before enabling agent access in a production project.
- [What is Vibe Coding and Should You Do It?](https://martiancraft.com/blog/2026/03/what-is-vibe-coding) — MartianCraft · article catalogue
  **NeKI brief:** Defines vibe coding as an AI-led development loop and weighs its speed against reviewability, correctness, and maintainability. The discussion is useful when establishing team rules for experiments versus code that ships.
- [How Senior iOS Engineers Are Using AI in App Development](https://martiancraft.com/blog/2026/03/how-senior-ios-engineers-are-using-ai) — MartianCraft · article catalogue
  **NeKI brief:** Contrasts productive AI uses for senior iOS engineers with unsuitable delegation, emphasizing review and engineering judgment. Follow it when defining guardrails for generated code, maintenance work, and tasks where context matters more than speed.
- [What Excites Us About 2026: A MartianCraft Perspective on the Future of iOS Development](https://martiancraft.com/blog/2026/02/what-excites-us-about-2026) — MartianCraft · article catalogue
  **NeKI brief:** Highlights Apple Intelligence, Siri, and Claude Code or other LLM agents alongside platform design changes. Use it as a forward-looking shortlist of AI-related Apple development themes, not as authoritative capability documentation.
- [MartianCraft on WWDC 2025 - What Caught Our Eye](https://martiancraft.com/blog/2025/06/wwdc-what-caught) — MartianCraft · article catalogue
  **NeKI brief:** Summarizes WWDC25 observations spanning on-device AI, Xcode LLM tooling, SwiftUI, and Liquid Glass refinements. Follow it for an experienced triage of announcements, then replace impressions with current SDK and session details.
- [AI Can Write Code, It Can’t Understand People](https://martiancraft.com/blog/2025/05/ai-understanding) — MartianCraft · article catalogue
  **NeKI brief:** AI-generated code cannot replace understanding users, requirements, or product context. Follow this perspective when setting human review boundaries for code generation and deciding what accountability must remain with the team.
- [Automatic, for the machines](https://martiancraft.com/blog/2018/09/automatic-for-the-machines) — MartianCraft · article catalogue
  **NeKI brief:** Uses Turi Create examples such as linear regression and k-nearest neighbors to discuss data aggregation, project expectations, and beginner ML experimentation. Follow it for historical intuition about dataset work, not current framework setup.
- [Migrating from iOS to Mac — Part II: Build an macOS app in Swift](https://martiancraft.com/blog/2018/07/ios-to-mac-2) — MartianCraft · article catalogue
  **NeKI brief:** Builds a macOS Reminderz app from an iOS developer's perspective, covering data management, view controllers, keyboard shortcuts, responder-chain behavior, and local notifications. Use it to compare platform boundaries when porting an app architecture.
- [A Shift In Tech: Machine Learning and AI](https://martiancraft.com/blog/2018/07/a-shift-in-tech-machine-learning-and-ai) — MartianCraft · article catalogue
  **NeKI brief:** Discusses machine learning for distributing medical information while stressing algorithmic limits and the need for human interpretation. Use it as a domain-risk perspective on AI-assisted decisions, not as a clinical or model-implementation guide.
- [Creating a Corporate Directory App with SAP's Cloud Platform SDK for iOS - Part 3](https://martiancraft.com/blog/2018/06/corporate-directory-app-with-SAP-cloud-platform-part3) — MartianCraft · article catalogue
  **NeKI brief:** Details customizing SAP Fiori Components in an iOS corporate-directory app, from the first screen through list and detail views. Follow it for historical SDK integration and UI customization patterns, with modern SAP APIs verified separately.
- [Self-Forking Agents — Chris Eidhof](https://chris.eidhof.nl/post/self-forking-agents) — Chris Eidhof · article catalogue
  **NeKI brief:** Experiments with an agent that can create variants of itself and use tools to improve its own approach. Use it as an exploratory agent-architecture idea, with independent evaluation of safety, cost, and reproducibility.
- [LLMs for "Real Projects" — Chris Eidhof](https://chris.eidhof.nl/post/llms-real-code) — Chris Eidhof · article catalogue
  **NeKI brief:** Distinguishes high-level prompting for disposable prototypes from the tighter context and implementation control needed in established codebases. Use it when adapting an LLM workflow to real project constraints rather than one-shot demos.
- [Food Assistant — Chris Eidhof](https://chris.eidhof.nl/post/llm-month-food-assistant) — Chris Eidhof · article catalogue
  **NeKI brief:** A project diary about building a food assistant as a deliberate exercise in learning LLM-assisted development. It offers an example problem and workflow for experimentation, not a validated production architecture.
- [Learning in the age of LLMs — Chris Eidhof](https://chris.eidhof.nl/post/learning-in-the-age-of-llms) — Chris Eidhof · article catalogue
  **NeKI brief:** A personal perspective on the understanding gained by implementing a difficult system by hand, contrasted with the speed of AI-assisted construction. It is useful when deciding whether a task's goal is delivery, learning, or both.
- [Integrating Dependencies into LLM-Assisted Projects — Chris Eidhof](https://chris.eidhof.nl/post/integrating-dependencies-into-llm-assistant-projects) — Chris Eidhof · article catalogue
  **NeKI brief:** Discusses vendoring dependency source into an LLM-assisted codebase so the agent can inspect and adapt it as part of the project. It is useful for evaluating agent visibility and maintenance trade-offs, with licensing and update costs considered separately.
- [Deep Understanding while using LLMs — Chris Eidhof](https://chris.eidhof.nl/post/deep-understanding-while-using-llms) — Chris Eidhof · article catalogue
  **NeKI brief:** Argues that using an LLM can accelerate delivery while also bypassing the struggle needed to build a durable mental model. Use it when designing learning or workshop workflows where understanding matters as much as output.
- [Agentic Coding — Chris Eidhof](https://chris.eidhof.nl/post/agentic-coding) — Chris Eidhof · article catalogue
  **NeKI brief:** Reports experiments using coding agents for SwiftUI work, including productive feedback loops, surprising failures, and tasks that still require a strong mental model. Use it to shape an agent-assisted workflow without treating the observations as universal benchmarks.

## Newsletter and related leads

- [agentic skill](https://youtu.be/rAvlt9Dvgbo?si=SUHzOy3YLZ3m-N-j&t=855) — iOS Dev Weekly · Issue 765 — Video · Topics: AI Development · Xcode
  **Published:** `28th August 2026`
  **NeKI brief:** Links to a video segment about Apple-platform agentic skills. Treat it as a discovery lead and verify tool behaviour against current primary documentation.
- [Headless Xcode: From Prompt to Simulator with MCP](https://artemnovichkov.com/blog/headless-xcode-from-prompt-to-simulator-with-mcp) — iOS Dev Weekly · Issue 765 — Article · Topics: AI Development · Xcode
  **Published:** `28th August 2026`
  **NeKI brief:** Walks through Xcode 27's xcrun mcp-server, its separate service and project permission gates, exported Apple agent skills, headless previews, and simulator verification. It also identifies the beta tooling and administrator-account constraints.
- [Running iOS Background Tasks Reliably, Part 1](https://calcopilot.app/blog/posts/running-ios-background-tasks-reliably-part1) — Those Who Swift · Issue 281 — Article · Topics: AI Development · App Services & Extensions · Personal Essays
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Documents lessons learned while pursuing reliable iOS background-task execution in iOS 26. The article focuses on the practical reliability gap between scheduling background work and getting it to run consistently, which is useful when designing refresh and deferred-processing workflows.
- [Headless Xcode: From Prompt to Simulator with MCP](https://l.fatbobman.com/w0149-01) — Fatbobman’s Swift Weekly · Issue 149 — Article · Topics: AI Development · Xcode
  **Published:** `2026-08-17T12:03:38.576Z`
  **NeKI brief:** Walks through Xcode 27's xcrun mcp-server, its separate service and project permission gates, exported Apple agent skills, headless previews, and simulator verification. It also identifies the beta tooling and administrator-account constraints.
- [FoundationModelsKit](https://github.com/divyaravitech/FoundationModelsKit) — iOS Dev Tools · iOS Dev Tools: ConsentBus, FoundationModelsKit, Agent Island — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2026-08-06T16:00:49.980Z`
  **NeKI brief:** Provides protocol-based model routing, actor-isolated conversation compaction, evaluation hooks and regional availability for mixing on-device, private-cloud and third-party model implementations.
- [getting-started walkthrough](https://www.kodeco.com/53631607-getting-started-with-apple-s-foundation-models?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Builds a minimal SwiftUI chat around SystemLanguageModel and LanguageModelSession, including availability checks, failure-state testing, prompting, and response display. Useful as an on-device Foundation Models starting point before adding structured generation or tools.
- [Apple Just Opened the Foundation Models Framework to Any LLM Provider](https://dev.to/arshtechpro/wwdc-2026-apple-just-opened-the-foundation-models-framework-to-any-llm-provider-5ejn?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: AI Development · Architecture · Security & Privacy
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Explains iOS 27’s provider protocol for running on-device, Private Cloud Compute, local, or third-party models behind LanguageModelSession. It frames provider choice around privacy, latency, capability, offline behavior, and cost instead of duplicated feature logic.
- [Core AI](https://lushbinary.com/blog/apple-foundation-models-framework-swift-guide?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: AI Development · Architecture · Security & Privacy · Swift
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Surveys the iOS 27 Foundation Models expansion: provider routing across on-device, Private Cloud Compute, Claude, and Gemini; image input; tool calling; and Dynamic Profiles. Use it as orientation, then verify beta API names in Apple documentation.
- [how he used AI to make MessagePack decoding about 20% faster](https://pfandrade.me/blog/message-packable?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: AI Development · Foundation & Data Formats · Performance · Swift
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Describes using Codex to integrate Swift Binary Parsing into a MessagePack decoder, then independently validating nearly 20% faster decoding and more than 60% fewer allocations. It is a human-in-the-loop optimization workflow grounded in Instruments and reproducible benchmarks.
- [The iOS Testing Strategy Agent Skill](https://livsycode.com/best-practices/the-ios-testing-strategy-agent-skill) — Those Who Swift · Issue 278 — Article · Topics: AI Development · Code Quality · Testing
  **Published:** `2026-08-05T20:00:46.292Z`
  **NeKI brief:** Presents an agent skill that starts test design from behavior, risk, and observable outcomes rather than one test file per type. It chooses boundaries and doubles by determinism, execution time, maintenance cost, and the confidence each layer adds.
- [A Sol's Work: Shipping with GPT-5.6 Sol](https://rudrank.com/a-sols-work-shipping-with-gpt-5-6-sol) — Those Who Swift · Issue 278 — Article · Topics: AI Development · Developer Tools · Personal Essays
  **Published:** `2026-08-05T20:00:46.292Z`
  **NeKI brief:** Describes a walk-away test for long-running coding agents: survive changing branches, review feedback, CI failures, and retries, then report verified reality. Production examples show increased autonomy while preserving explicit human review before shipping.
- [AI Broke Code Review. Here’s How to Rebuild It.](https://swiftandmemes.com/ai-broke-code-review-heres-how-to-rebuild-it) — iOS Dev Weekly · Issue 761 — Article · Topics: AI Development · Code Quality · Developer Community & Business
  **Published:** `31st July 2026`
  **NeKI brief:** Proposes a layered review pipeline for AI-generated changes, combining deterministic checks, focused automated reviewers, architectural scrutiny, and human judgment. The structure is useful when increased code volume overwhelms a traditional single-pass pull-request review.
- [Bridging Gemini Video with Foundation Models and CustomSegment](https://rudrank.com/exploring-foundation-models-bridging-gemini-video-with-customsegment) — Those Who Swift · Issue 277 — Article · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `2026-07-29T20:01:55.196Z`
  **NeKI brief:** Bridges unsupported video input through a custom Transcript segment and LanguageModelExecutor that delegates analysis to Gemini. The layered verification is useful when extending Foundation Models-style sessions beyond the on-device model’s native modalities.
- [📈 New Pull Request Metrics in the GitHub API](https://github.blog/changelog/2026-07-07-add-review-cycles-and-time-to-adoption-phases-in-the-usage-api) — iOS CI Newsletter · Issue 91 — Article · Topics: AI Development · Code Quality · Developer Tools
  **Published:** `2026-07-28T00:00:00.000Z`
  **NeKI brief:** Examines New Pull Request Metrics in the GitHub API in the context of AI Development and Code Quality. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Foundation Models Utilities](https://livsycode.com/swift/foundation-models-utilities?ref=createwithswift.com) — Create with Swift · Issue 117 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `2026-07-24T15:00:34.000Z`
  **NeKI brief:** Surveys Apple's experimental Foundation Models Utilities package: hosted Chat Completions models, transcript dropping, rolling windows, summarisation, and runtime-loaded skills. It also makes the context-loss and platform-version trade-offs explicit before these patterns stabilise.
- [Building a custom DynamicProfileModifier in Foundation Models](https://artemnovichkov.com/blog/building-a-custom-dynamic-profile-modifier-in-foundation-models?ref=createwithswift.com) — Create with Swift · Issue 117 — Article · Topics: AI Development · Performance · Swift
  **Published:** `2026-07-24T15:00:34.000Z`
  **NeKI brief:** Builds a DynamicProfileModifier that switches to the on-device model, lowers temperature, caps output, and trims visible history. The article also explains modifier precedence, beta requirements, incomplete-output risk, and safe handling of commercial provider credentials.
- [Test iOS apps in the simulator with Claude Code Desktop [Beta]](https://code.claude.com/docs/en/desktop-ios-simulator) — iOS Dev Weekly · Issue 760 — Article · Topics: AI Development · Developer Tools · Testing · Xcode
  **Published:** `24th July 2026`
  **NeKI brief:** Documents Claude Code Desktop's session-specific iOS Simulator pane, including requirements, manual device control, permissions, captures, policy switches, and troubleshooting. Use it to evaluate the current beta workflow and its device-isolation boundaries.
- [Make AI talk without human social patterns](https://swiftrocks.com/a-system-prompt-to-get-ai-to-stop-pretending-to-be-human) — iOS Dev Weekly · Issue 760 — Article · Topics: AI Development · Developer Tools
  **Published:** `24th July 2026`
  **NeKI brief:** Offers a concrete system prompt that removes conversational filler and asks a model to describe its computational role directly. The author reports subjective improvement but no evaluations, making it a prompt experiment rather than validated guidance.
- [Foundation Models Is Now a Hybrid Platform — and Picking the Tier Is the New Design Decision](https://www.wesleymatlock.com/foundation-models-hybrid-platform) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats · Navigation & Deep Linking
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Frames model-tier selection as a feature-level architectural decision, with session creation and graceful fallback kept behind a focused boundary. Useful when designing a Foundation Models feature that may choose on-device, cloud, or frontier capability paths.
- [Rendering SwiftUI Previews with Xcode's MCP Server](https://cuteios.dev/2026/07/14/previews-and-mcp) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Graphics, Media & Games · Xcode
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Builds a SwiftUI preview gallery by combining Xcode’s MCP server, project context, and generated preview metadata. The article maps the moving parts and current limitations, making it useful when evaluating agent-assisted preview tooling.
- [Apple Foundation Models in iOS 27: The Complete Builder Guide](https://chatforest.com/builders-log/apple-foundation-models-ios-27-on-device-llm-api-builder-guide) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Maps an on-device Foundation Models stack from model capability through app logic, tool calls, availability, and optional fine-tuning. Follow it when scoping a local AI feature, while validating beta hardware, privacy, and storage constraints independently.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-07-15`
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Those Who Swift · Issue 275 — Article · Topics: Apple Platform Ecosystem · Foundation & Data Formats · Swift
  **Published:** `2026-07-15`
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [Getting Started with Apple’s Foundation Models](https://artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-07-15`
  **NeKI brief:** Demonstrates rendering Markdown in SwiftUI. Useful for choosing a rendering pipeline, handling attributed content, and deciding where links and styling should remain controlled by the app.
- [The Platform for Agentic macOS Development](https://go.macstadium.com/build-faster-with-orka) — iOS Dev Weekly · Issue 758 — Article · Topics: AI Development · CI/CD & Automation · Testing
  **Published:** `10th July 2026`
  **NeKI brief:** MacStadium's Orka overview describes API- and CLI-driven Apple-silicon virtual machines for CI, testing, and agent workflows. Use it to evaluate elastic macOS capacity against cost, isolation, Kubernetes integration, and reproducible build requirements.
- [SwiftUI Performance](https://livsycode.com/swiftui/the-swiftui-performance-skill) — iOS Dev Weekly · Issue 758 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `10th July 2026`
  **NeKI brief:** Introduces an agent skill for investigating SwiftUI performance through view lifecycle, rendering behavior, and measurement-oriented workflows. Follow it when giving coding agents repeatable performance diagnostics, while validating conclusions with Instruments and real app traces.
- [Control the Simulator with AI](https://www.rocketsim.app/docs/features/agentic-development) — iOS Dev Weekly · Issue 758 — Article · Topics: AI Development · Testing
  **Published:** `10th July 2026`
  **NeKI brief:** The documentation explains RocketSim's agentic-development feature for controlling the iOS Simulator with AI-assisted workflows.
- [Introducing the Safari MCP server for web developers](https://webkit.org/blog/18136/introducing-the-safari-mcp-server-for-web-developers) — SwiftLee Weekly · Issue 331 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `2026-07-07T14:05:55.000Z`
  **NeKI brief:** Examines Safari now has an MCP! in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [How To (Not) Spend $10k/wk on Coding Agents](https://allenpike.com/2026/how-to-not-spend-10k-on-coding-agents) — SwiftLee Weekly · Issue 331 — Article · Topics: AI Development
  **Published:** `2026-07-07T14:05:55.000Z`
  **NeKI brief:** This field report describes progressively automating coding loops while adding tests, guardrails, review automation, and UX evidence as new bottlenecks appear. It is useful for evaluating where agent automation needs human checks instead of assuming productivity scales for free.
- [Swift Algorithms & Data Structures](https://waynewbishop.github.io/swift-algorithms) — Fatbobman’s Swift Weekly · Issue 143 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-06T12:03:13.020Z`
  **NeKI brief:** Collects Swift algorithms and data-structure examples in runnable form, making it useful for comparing standard-library techniques, complexity trade-offs, and interview-style implementations before introducing custom utilities.
- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) — Those Who Swift · Issue 273 — Article · Topics: AI Development
  **Published:** `2026-07-01`
  **NeKI brief:** Reviews Introducing Claude Sonnet 5. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [A Community Agent Skill for Swift Testing](https://github.com/twostraws/Swift-Testing-Agent-Skill?ref=ioscodereview.com) — iOS Code Review · Issue 81 — Source repository · Topics: Developer Community & Business · Swift · Testing
  **Published:** `2026-06-30T16:31:22.000Z`
  **NeKI brief:** Provides the source and change history for A Community Agent Skill for Swift Testing, relevant to Developer Community & Business and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Testing Foundation Models: Code That Won’t Give The Same Answer Twice](https://www.wesleymatlock.com/testing-on-device-ai-swift-testing) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2026-06-18`
  **NeKI brief:** Discusses testing nondeterministic Foundation Models output with Swift Testing. Use it when designing assertions for on-device AI, focusing on stable structure, bounded behavior, and controlled inputs instead of brittle exact-text comparisons.
- [WWDC26 Group Labs: The Real Story Isn’t Foundation Models. It’s Evaluation.](https://divyaravidev.substack.com/p/wwdc26-group-labs-the-real-story) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Reports on WWDC26 group labs and evaluation around Foundation Models. Useful for understanding model assessment as an engineering concern rather than relying on demo quality alone.
- [Using Claude With Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Artem shows how Claude can be used into Apple’s Foundation Models framework on iOS 27, using the same LanguageModelSessionAPI to switch between on-device models and Claude.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — SwiftLee Weekly · Issue 328 — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [Foundation Models can now swap providers](https://www.techtimes.com/articles/318039/20260609/wwdc-2026-developer-tools-foundation-models-now-swaps-ai-providers-without-code-changes.htm?ref=ioscodereview.com) — iOS Code Review · Issue 80 — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **Published:** `2026-06-15T17:08:20.000Z`
  **NeKI brief:** Examines Foundation Models can now swap providers in the context of AI Development and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Offsend](https://github.com/Offsend/Offsend) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** Offsend is a GitHub project for sending or transferring content. Follow its README and source to inspect the concrete workflow, protocol, and platform assumptions before treating it as a maintained dependency.
- [Michael Tsai](https://mjtsai.com/blog/2026/06/03/wwdc-2026-wish-lists) — iOS Dev Weekly · Issue 753 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `5th June 2026`
  **NeKI brief:** Examines Michael Tsai - Blog - WWDC 2026 Wish Lists. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Tokens4Breakfast](https://www.tokens4breakfast.app/) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Article · Topics: AI Development · App Distribution & Store Operations · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Tokens4Breakfast presents a developer or AI-oriented product workflow. Follow it for concrete token or usage-management behavior, while verifying service integrations, limits, and privacy before adoption.
- [Vibedock](https://vibedock.dev/) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Article · Topics: AI Development · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Vibedock is a developer-oriented product for organizing AI-assisted coding workflows. Use it as a discovery lead when comparing agent workspaces, and verify supported providers, project isolation, and data-handling policies before relying on it.
- [Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding](https://medium.com/@wesleymatlock/enter-sandman-mode-three-months-inside-xcode-26-3s-agentic-coding-cbe67ce46df9) — Those Who Swift · Issue 269 — Article · Topics: AI Development · Concurrency · Xcode
  **Published:** `2026-06-04`
  **NeKI brief:** Examines Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel](https://www.youtube.com/watch?v=KlCqHP32c8M) — Those Who Swift · Issue 269 — Video · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2026-06-04`
  **NeKI brief:** Reviews Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [A Recipe to Custom Instructions for GitHub Copilot](https://www.ioscoffeebreak.com/issue/issue72) — SwiftLee Weekly · Issue 325 — Article · Topics: AI Development · Developer Tools
  **Published:** `2026-05-26T14:06:24.000Z`
  **NeKI brief:** Explains A Recipe to Custom Instructions for GitHub Copilot, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Using Xcode MCP With Claude Code](https://danielsaidi.com/blog/2026/04/30/using-xcode-mcp-with-claude-code) — Those Who Swift · Issue 267 — Article · Topics: AI Development · Swift · Xcode
  **Published:** `2026-05-21`
  **NeKI brief:** Describes connecting Claude Code to Xcode through Model Context Protocol. Follow it when evaluating agent-assisted build and debugging workflows, paying attention to permissions, simulator boundaries, generated changes, and human review checkpoints.
- [How Claude Code Works In Large Codebases: Best Practices And Where To Start](https://claude.com/blog/how-claude-code-works-in-large-codebases-best-practices-and-where-to-start) — Those Who Swift · Issue 267 — Article · Topics: AI Development
  **Published:** `2026-05-21`
  **NeKI brief:** Explains how Claude Code works in large codebases. Useful for understanding repository context, navigation, and staged agent changes before trusting automation on a complex project.
- [Cupertino v1.1.0: my Apple docs index was 30% lies and I didn't know](https://aleahim.com/blog/cupertino-v1-1-0-poison-cleanup) — SwiftLee Weekly · Issue 324 — Article · Topics: AI Development
  **Published:** `2026-05-19T14:04:54.000Z`
  **NeKI brief:** This post audits Cupertino's Apple-documentation database and shows how stale or erroneous rows can survive a green health check. It provides a concrete upgrade, database-rebuild, and verification workflow for maintaining local documentation indexes.
- [Swift Student Challenge winners](https://9to5mac.com/2026/05/07/apple-highlights-four-swift-student-challenge-apps-ahead-of-wwdc-2026?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Swift Student Challenge winners in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 135 — Tutorial · Topics: AI Development · Swift · SwiftUI
  **Published:** `2026-05-11T12:02:41.178Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Cupertino v1.0.0 “First Light”](https://aleahim.com/blog/cupertino-first-light) — iOS Dev Weekly · Issue 750 — Article · Topics: AI Development
  **Published:** `8th May 2026`
  **NeKI brief:** Presents cupertino v1.0.0 “first light” for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [openclick](https://openclick.sh/) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Article · Topics: Accessibility · AI Development
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** openclick presents a tool for automating or triggering clicks. Follow it for concrete scheduled-input behavior, while reviewing accessibility permissions, safeguards, and appropriate use before adoption.
- [Apple Foundation Models With Mohammad Azam](https://www.youtube.com/watch?v=UeZfiKBHUCs&list=PL2iZPZus2bhSl3CDE_vs2851UMgix285u) — Those Who Swift · Issue 265 — Video · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-05-06`
  **NeKI brief:** Reviews Apple Foundation Models With Mohammad Azam. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [CLI](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — SwiftLee Weekly · Issue 322 — Article · Topics: AI Development · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Agent Skill](https://www.rocketsim.app/docs/features/agentic-development/agent-skill) — SwiftLee Weekly · Issue 322 — Article · Topics: AI Development · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Documents Agent Skill, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [overwhelmed with AI slop to the point of shutting down bug bounties](https://daniel.haxx.se/blog/2026/01/26/the-end-of-the-curl-bug-bounty) — iOS Dev Weekly · Issue 748 — Article · Topics: AI Development
  **Published:** `17th April 2026`
  **NeKI brief:** The post explains why the curl project ended its bug bounty programme in response to overwhelming low-quality AI-generated reports.
- [writing retaliatory blog posts when their pull requests get closed](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me) — iOS Dev Weekly · Issue 748 — Article · Topics: AI Development
  **Published:** `17th April 2026`
  **NeKI brief:** Examines Summary: An AI agent of unknown ownership autonomously wrote and published a personalized hit piece about me after I rejected its code, attempting to damage my reputation and shame. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftZilla](https://swiftzilla.dev/) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** SwiftZilla indexes a Swift project to expose dependency graphs, semantic search, impact analysis, and convention-aware code review through an AI workflow. It is useful for evaluating whether architectural onboarding can be automated without losing project-specific context.
- [Console logs showing up in the Network Monitor](https://www.rocketsim.app/docs/features/networking/network-traffic-monitoring) — SwiftLee Weekly · Issue 319 — Article · Topics: Networking
  **Published:** `2026-04-14T14:07:31.000Z`
  **NeKI brief:** Documents Console logs showing up in the Network Monitor, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Launching deeplinks with dynamic arguments](https://www.rocketsim.app/docs/features/app-actions/deeplinks-universal-links) — SwiftLee Weekly · Issue 319 — Article · Topics: Navigation & Deep Linking
  **Published:** `2026-04-14T14:07:31.000Z`
  **NeKI brief:** Documents Launching deeplinks with dynamic arguments, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Pinch support for recordings](https://www.rocketsim.app/docs/features/capturing/post-editor) — SwiftLee Weekly · Issue 319 — Article
  **Published:** `2026-04-14T14:07:31.000Z`
  **NeKI brief:** Documents Pinch support for recordings, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Quick minimize of the side window](https://www.rocketsim.app/docs/settings/side-window) — SwiftLee Weekly · Issue 319 — Article
  **Published:** `2026-04-14T14:07:31.000Z`
  **NeKI brief:** Documents Quick minimize of the side window, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [Audio-mcp](https://github.com/BugorBN/audio-mcp) — iOS Dev Tools · iOS Dev Tools: Audio-mcp, Remodex, Pippin — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-04-09T17:01:21.324Z`
  **NeKI brief:** Audio-mcp is a GitHub project connecting audio capabilities to an MCP-style tool interface. Follow its source and README to inspect the concrete command surface and integration boundaries before adopting it in an AI-assisted workflow.
- [Silkwave Voice](https://www.silkwave.ai/silkwave-voice) — iOS Dev Tools · iOS Dev Tools: Audio-mcp, Remodex, Pippin — Podcast · Topics: AI Development · App Distribution & Store Operations · Developer Community & Business
  **Published:** `2026-04-09T17:01:21.324Z`
  **NeKI brief:** Silkwave Voice provides voice generation or speech-processing functionality. Follow it for concrete audio-generation and integration workflows, while checking model, licensing, privacy, and export constraints.
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More](https://www.youtube.com/watch?v=VU-NiioUpxg&t=237s) — Those Who Swift · Issue 260 — Video · Topics: AI Development · App Distribution & Store Operations · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Reviews iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Package Traits in Xcode](https://www.massicotte.org/blog/package-traits-in-xcode) — SwiftLee Weekly · Issue 317 — Article · Topics: AI Development · Xcode
  **Published:** `2026-03-31T14:07:14.000Z`
  **NeKI brief:** Introduces Swift package traits in Xcode and shows how conditional package features can avoid maintaining multiple package variants.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [Apple Foundation Models In Practice: Building On-Device AI Features In Swift](https://medium.com/@wesleymatlock/apple-foundation-models-in-practice-building-on-device-ai-features-in-swift-b6243976af4f) — Those Who Swift · Issue 259 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2026-03-26`
  **NeKI brief:** Examines Apple Foundation Models In Practice: Building On-Device AI Features In Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Review your own AI-generated code](https://www.scottberrevoets.com/2026/03/20/review-your-own-ai-generated-code) — SwiftLee Weekly · Issue 316 — Article · Topics: AI Development
  **Published:** `2026-03-24T15:03:10.000Z`
  **NeKI brief:** Discusses Review your own AI-generated code, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [ASC CLI](https://github.com/rudrankriyam/App-Store-Connect-CLI) — Fatbobman’s Swift Weekly · Issue 127 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-03-16T12:04:00.245Z`
  **NeKI brief:** App-Store-Connect-CLI automates App Store Connect tasks from the command line, including subscription-related setup. Use it to replace repetitive portal configuration with reviewable scripts, while treating credentials and destructive commands carefully.
- [A Month With OpenAI’s Codex](https://www.highcaffeinecontent.com/blog/20260301-A-Month-With-OpenAIs-Codex) — iOS Dev Weekly · Issue 745 — Article · Topics: AI Development
  **Published:** `13th March 2026`
  **NeKI brief:** Examines A Month With OpenAI's Codex. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.0.0) — SwiftLee Weekly · Issue 313 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Tracking token usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — iOS Dev Weekly · Issue 744 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `27th February 2026`
  **NeKI brief:** Artem explains how to measure the tokens Foundation Models consume for instructions, prompts, tools, and full session transcripts, helping you understand context limits and optimize prompt design.
- [LLM Checker](https://github.com/Pavelevich/llm-checker) — iOS Dev Tools · iOS Dev Tools: FRTMProxy, LLM Checker, PicoClaw — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-02-19T20:00:59.741Z`
  **NeKI brief:** LLM Checker evaluates or checks large-language-model output. Follow its source for concrete validation rules and command-line workflow, while reviewing its supported providers, failure modes, and privacy implications.
- [stating that much of its code is now written by LLMs](https://techcrunch.com/2026/02/12/spotify-says-its-best-developers-havent-written-a-line-of-code-since-december-thanks-to-ai) — Those Who Swift · Issue 254 — Article · Topics: AI Development
  **Published:** `2026-02-18`
  **NeKI brief:** Reviews stating that much of its code is now written by LLMs. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [AcceptedSE-0504Task Cancellation Shields](https://github.com/apple/swift-evolution/blob/main/proposals/0504-task-cancellation-shields.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0504Task Cancellation Shields. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0506Advanced Observation Tracking](https://github.com/apple/swift-evolution/blob/main/proposals/0506-advanced-observation-tracking.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0506Advanced Observation Tracking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Let’s end open source together with this one simple trick](https://fosdem.org/2026/schedule/event/SUVS7G-lets_end_open_source_together_with_this_one_simple_trick) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Examines FOSDEM 2026 - Let's end open source together with this one simple trick. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift talks at this year’s FOSDEM](https://fosdem.org/2026/schedule/events) — iOS Dev Weekly · Issue 743 — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **Published:** `13th February 2026`
  **NeKI brief:** Yes, there were Swift talks at this year’s FOSDEM, but this one by Dylan Ayrey and Mike Nolan was the one that caught my eye. They ask the question of whether open source is doomed in the age of LLMs, and it’s really a fantastic talk.
- [Agentic Coding in Xcode 26.3 with Claude Code and Codex](https://www.swiftjectivec.com/agentic-coding-codex-claude-code-in-xcode) — Those Who Swift · Issue 253 — Article · Topics: AI Development · Swift · Xcode
  **Published:** `2026-02-12`
  **NeKI brief:** Examines Agentic Coding in Xcode 26.3 with Claude Code and Codex, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex](https://rudrank.com/exploring-xcode-using-mcp-tools-cursor-external-clients) — SwiftLee Weekly · Issue 310 — Article · Topics: AI Development · Xcode
  **Published:** `2026-02-10T15:14:11.000Z`
  **NeKI brief:** Describes Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Five ways we’ve been using our MCP server](https://www.sketch.com/blog/mcp-server-use-cases) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** The Sketch article presents five concrete MCP server use cases and explains how the team applies them in its design-tool workflow.
- [Sketch added MCP support](https://www.sketch.com/docs/mcp-server) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** Examines Learn how to connect your AI tools with Sketch’s MCP Server. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Freddie Harrison](https://social.lol/@freddiewrites) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** The public social.lol profile identifies Freddie Harrison and exposes the author's profile and published posts without authentication.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Those Who Swift · Issue 250 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-01-21`
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [instructions for the agent in the form of a skill](https://github.com/mikker/steve/blob/main/skills/steve/SKILL.md) — iOS Dev Weekly · Issue 739 — Source repository · Topics: AI Development · Developer Tools · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** The page covers “instructions for the agent in the form of a skill” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Microsoft renaming Office 365 to the Copilot app](https://support.microsoft.com/en-us/office/the-microsoft-365-app-transition-to-the-microsoft-365-copilot-app-22eac811-08d6-4df3-92dd-77f193e354a5) — Those Who Swift · Issue 248 — Article · Topics: AI Development · Product Design
  **Published:** `2026-01-08`
  **NeKI brief:** Reviews Microsoft renaming Office 365 to the Copilot app. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Stop Getting Average Code from Your LLM | Krzysztof Zabłocki](https://merowing.info/posts/stop-getting-average-code-from-your-llm) — SwiftLee Weekly · Issue 303 — Article · Topics: AI Development · Code Quality
  **Published:** `2025-12-23T15:06:56.000Z`
  **NeKI brief:** Discusses Stop Getting Average Code from Your LLM | Krzysztof Zabłocki, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [list of tips in Paul’s AGENTS.md](https://github.com/twostraws/SwiftAgents/blob/main/AGENTS.md) — iOS Dev Weekly · Issue 737 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `19th December 2025`
  **NeKI brief:** Presents list of tips in paul’s agents.md for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [VibeProxy](https://github.com/automazeio/vibeproxy) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools · macOS & AppKit
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** VibeProxy presents a proxy-oriented developer tool. Follow its source and README for concrete traffic-routing or integration behavior, while verifying protocol support, credentials, and security implications before use.
- [Agentic AI Foundation](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation) — Those Who Swift · Issue 244 — Article · Topics: AI Development · Foundation & Data Formats · Product Design
  **Published:** `2025-12-11`
  **NeKI brief:** Announces the Agentic AI Foundation. Useful for tracking ecosystem governance and interoperability efforts around agent tooling, while separating foundation announcements from concrete APIs.
- [Journey to Swift 6 and Strict Concurrency](https://calcopilot.app/blog/posts/swift-6-and-strict-concurrency) — Those Who Swift · Issue 244 — Article · Topics: AI Development · Concurrency · Swift
  **Published:** `2025-12-11`
  **NeKI brief:** Examines Journey to Swift 6 and Strict Concurrency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Vectorizing Images With LLMs — Image Search & Semantic Matching](https://robkerr.com/vectorizing-images-with-llms) — Those Who Swift · Issue 243 — Article · Topics: AI Development · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `2025-12-10`
  **NeKI brief:** Explains vectorizing images with LLMs for semantic search. Useful for designing embedding pipelines, similarity retrieval, and the evaluation needed before using visual search in a product.
- [GenUI](https://pub.dev/packages/genui) — iOS Dev Weekly · Issue 736 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `21st November 2025`
  **NeKI brief:** Examines Generates and displays generative user interfaces (GenUI) in Flutter using AI. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [demo video](https://youtu.be/nWr6eZKM6no) — iOS Dev Weekly · Issue 736 — Video · Topics: AI Development · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st November 2025`
  **NeKI brief:** Yes, it’s about a Flutter package, GenUI, but it was the idea that caught my attention. It takes the idea of using LLMs inside an app one step further than having the model return text or structured data. Instead, it returns UI widgets that also contain the…
- [this 30-second slice](https://www.youtube.com/watch?v=nWr6eZKM6no&t=563s) — iOS Dev Weekly · Issue 736 — Video · Topics: AI Development · Cross-Platform & Web
  **Published:** `21st November 2025`
  **NeKI brief:** Yes, it’s about a Flutter package, GenUI, but it was the idea that caught my attention. It takes the idea of using LLMs inside an app one step further than having the model return text or structured data. Instead, it returns UI widgets that also contain the…
- [Homebrew had released version 5.0](https://brew.sh/2025/11/12/homebrew-5.0.0) — Fatbobman’s Swift Weekly · Issue 111 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Homebrew 5.0 documents the package manager's new parallel download behavior and release changes. Use it when diagnosing changed brew-upgrade behavior or evaluating how local developer-tool installations may become faster and more concurrent.
- [LlamaBarn](https://github.com/ggml-org/LlamaBarn) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** LlamaBarn is an Apple-platform project related to running or managing Llama models. Follow its source for concrete local-inference workflows, while verifying model formats, hardware requirements, and current API boundaries.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Those Who Swift · Issue 240 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Builds an on-device travel chatbot from a Foundation Models LanguageModelSession transcript, rendering user and model messages with thinking, scrolling, availability, guardrail, and error states. Useful for connecting session history to SwiftUI presentation.
- [AnyLanguageModel](https://github.com/mattt/AnyLanguageModel) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** AnyLanguageModel mirrors Apple's Foundation Models API while allowing alternative language-model providers, presenting a compatible abstraction for application code. Useful for testing provider substitution and keeping model integration behind a stable Swift interface.
- [ChatGPT in Xcode 26: There’s a Hidden Prompt!](https://youtu.be/e75mdQL-I8o) — Those Who Swift · Issue 239 — Video · Topics: Xcode
  **Published:** `2025-11-05`
  **NeKI brief:** Demonstrates ChatGPT integration in Xcode 26. Useful for examining AI-assisted editor workflows while keeping generated changes subject to repository review and platform verification.
- [Guided Generation with Foundation Models in Swift](https://www.youtube.com/watch?v=kBwwztRY1FQ) — Those Who Swift · Issue 239 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Uses Foundation Models @Generable and @Guide macros for structured workout and title responses, including partial streaming and guardrail errors. Useful for comparing schema-guided output with parsing unconstrained model text.
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — SwiftLee Weekly · Issue 296 — Video · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-11-04T08:02:52.000Z`
  **NeKI brief:** Summarizes a Meet with Apple performance session spanning power use, Foundation Models response latency, SwiftUI responsiveness, and Snap's diagnostic tools. Useful as a map of optimization areas before consulting the corresponding primary guidance.
- [AI Agents Comparison from iOS Developer Perspective](https://brightinventions.pl/blog/ai-agents-comparison-from-ios-dev-perspective) — Those Who Swift · Issue 238 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-10-29`
  **NeKI brief:** Compares AI agents from an iOS developer perspective. Useful for assessing where agents help with coding workflows and where review, context, and platform verification remain necessary.
- [Foundation Models Framework in Swift Getting Started with On Device AI](https://www.youtube.com/watch?v=p17HrjVQKOQ) — Those Who Swift · Issue 238 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-10-29`
  **NeKI brief:** Reviews Foundation Models Framework in Swift Getting Started with On Device AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Generative AI for Beginners – Microsoft GitHub Course](https://github.com/microsoft/generative-ai-for-beginners) — Those Who Swift · Issue 237 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-10-22`
  **NeKI brief:** Offers a practical course on generative AI concepts. Useful for engineers building AI-enabled features who need a structured path through models, prompting, evaluation, and application integration.
- [Introducing ChatGPT Atlas](https://www.youtube.com/watch?v=8UWKxJbjriY) — Those Who Swift · Issue 237 — Video · Topics: AI Development · Cross-Platform & Web
  **Published:** `2025-10-22`
  **NeKI brief:** Reviews Introducing ChatGPT Atlas. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Just Talk To It - the no-bs Way of Agentic Engineering](https://steipete.me/posts/just-talk-to-it) — SwiftLee Weekly · Issue 294 — Article · Topics: AI Development · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents Just Talk To It - the no-bs Way of Agentic Engineering, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Foundation Models profiling with Xcode Instruments](https://artemnovichkov.com/blog/foundation-models-profiling-with-xcode-instruments) — iOS Dev Weekly · Issue 731 — Article · Topics: Foundation & Data Formats · Performance · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Artem shows how to profile and optimize Foundation Models performance using Xcode Instruments, tracking response time, token usage and tool calls to help developers improve performance on real devices.
- [Foundation Models Playgrounds](https://l.fatbobman.com/w0106-08) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Collects playground examples for Apple’s Foundation Models framework. Follow it when quickly exploring model APIs and isolating sample behavior before integrating the framework into a production feature.
- [An Apple Intelligence-Style Glow Effect in SwiftUI](https://livsycode.com/swiftui/an-apple-intelligence-style-glow-effect-in-swiftui) — iOS Dev Weekly · Issue 730 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `10th October 2025`
  **NeKI brief:** Artem demonstrates how to create an “Apple Intelligence” style glow effect in SwiftUI by applying visual effects (like blurs and overlays) to achieve a glowing UI appearance.
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://antongubarenko.substack.com/p/ios-26-foundation-model-framework-f6d) — Those Who Swift · Issue 235 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2025-10-08`
  **NeKI brief:** Examines iOS 26: Foundation Model Framework - Code-Along Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Foundation Models Profiling with Xcode Instruments](https://l.fatbobman.com/w0105-05) — Fatbobman’s Swift Weekly · Issue 105 — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** Shows how to profile and optimize Foundation Models performance with Xcode Instruments. Follow it when measuring model latency, resource use, and bottlenecks instead of tuning an on-device AI feature from subjective responsiveness alone.
- [TranscriptDebugMenu](https://github.com/artemnovichkov/TranscriptDebugMenu) — Fatbobman’s Swift Weekly · Issue 105 — Source repository · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** TranscriptDebugMenu is a debug surface for inspecting Foundation Models conversations and related app state. Use it alongside Xcode Instruments when testing session prewarming, tool calls, and model-output performance in development builds.
- [🐙 Use GitHub Copilot directly from the Terminal](https://github.blog/changelog/2025-09-25-github-copilot-cli-is-now-in-public-preview) — iOS CI Newsletter · Issue 77 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** Examines Use GitHub Copilot directly from the Terminal in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Anthropic’s very popular Claude Code](https://www.claude.com/product/claude-code) — iOS CI Newsletter · Issue 77 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** Examines Anthropic’s very popular Claude Code in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Stop Wasting Context on Build Output](https://ldomaradzki.com/blog/stop-wasting-context-build-output) — iOS Dev Weekly · Issue 729 — Article · Topics: AI Development
  **Published:** `3rd October 2025`
  **NeKI brief:** Examines Start formatting your CI/CD output with AI in mind in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [All about Swift Package Manager Traits](https://theswiftdev.com/2025/all-about-swift-package-manager-traits) — iOS Dev Weekly · Issue 729 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `3rd October 2025`
  **NeKI brief:** Presents All about Swift Package Manager Traits, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Package Traits](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — iOS Dev Weekly · Issue 729 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `3rd October 2025`
  **NeKI brief:** Defines Swift Package Manager package traits for expressing optional dependency features. Study the proposal when designing modular packages, then verify accepted syntax and toolchain support before adopting it.
- [Claude Sonnet 4.5 Released](https://www.anthropic.com/news/claude-sonnet-4-5) — Those Who Swift · Issue 234 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-10-01`
  **NeKI brief:** Reviews Claude Sonnet 4.5 Released. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [9TO5Mac’s report](https://9to5mac.com/2025/09/22/macos-tahoe-26-1-beta-1-mcp-integration) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Reports beta evidence of MCP-related integration in macOS Tahoe. Use it only as an early signal for system-level agent support, then validate actual APIs, availability, and permissions against Apple's released documentation.
- [available on GitHub](https://github.com/NSHipster/sosumi.ai) — SwiftLee Weekly · Issue 290 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2025-09-23T14:09:24.000Z`
  **NeKI brief:** Points to available on GitHub, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [LLM Interactive Guide](https://bbycroft.net/llm) — Those Who Swift · Issue 231 — Article · Topics: AI Development
  **Published:** `2025-09-10`
  **NeKI brief:** This article covers a visual, comprehensive introduction to large language models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ChatGPT in Xcode 26: is it as good as Cursor or Claude Code?](https://www.youtube.com/watch?v=BCUjW0TkaUY) — Those Who Swift · Issue 229 — Video · Topics: AI Development · Xcode
  **Published:** `2025-08-27`
  **NeKI brief:** Compares Xcode 26's integrated ChatGPT workflow with Cursor and Claude Code from an iOS developer's perspective. Use it to identify editor-integration trade-offs and limitations rather than as a definitive tool ranking.
- [UICoder: Fine-tuning Large Language Models to Generate User Interface Code through Automated Feedback](https://machinelearning.apple.com/research/uicoder) — iOS Dev Weekly · Issue 723 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `22nd August 2025`
  **NeKI brief:** I remember being amazed when I read Simon Willison’s 2024 LLM wrap-up post when he reported that training LLMs on generated content works well:
- [2024 LLM wrap-up](https://simonwillison.net/2024/Dec/31/llms-in-2024) — iOS Dev Weekly · Issue 723 — Article · Topics: AI Development
  **Published:** `22nd August 2025`
  **NeKI brief:** I remember being amazed when I read Simon Willison’s 2024 LLM wrap-up post when he reported that training LLMs on generated content works well:
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP) — iOS Dev Tools · iOS Dev Tools: Votice, SwiftMCP, NetworkKit — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-08-21T17:28:34.537Z`
  **NeKI brief:** SwiftMCP provides Swift-oriented MCP implementation code. Follow its repository for concrete transport, tool, and model abstractions, then verify protocol compatibility and maintenance status before integrating it into an application.
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Those Who Swift · Issue 228 — Article · Topics: AI Development · Swift · SwiftData
  **Published:** `2025-08-20`
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Those Who Swift · Issue 228 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-08-20`
  **NeKI brief:** Configures Apple's Foundation Models GenerationOptions for greedy decoding so identical inputs produce more repeatable output. Useful for debugging and tests that need reduced sampling variance while recognizing model behavior is not universally deterministic.
- [SwiftAgent](https://forums.swift.org/t/swiftagent-a-swift-native-agent-sdk-inspired-by-foundationmodels-and-using-its-tools/81634) — iOS Dev Weekly · Issue 722 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `15th August 2025`
  **NeKI brief:** Presents swiftagent for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Tuist’s AI Whitepaper](https://tuist.dev/blog/2025/08/11/tuist-ai-whitepaper) — Those Who Swift · Issue 227 — Article · Topics: AI Development · Swift · Testing
  **Published:** `2025-08-13`
  **NeKI brief:** Examines Tuist’s AI Whitepaper, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Using Foundation Models Framework to Stream from External LLM Providers](https://www.natashatherobot.com/p/foundationmodels-streaming-external-llm) — Those Who Swift · Issue 226 — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **Published:** `2025-08-06`
  **NeKI brief:** Examines Using Foundation Models Framework to Stream from External LLM Providers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [AI Use Cases](https://github.com/Engineer1999/A-Curated-List-of-ML-System-Design-Case-Studies) — Those Who Swift · Issue 226 — Source repository · Topics: AI Development · Architecture · Developer Tools
  **Published:** `2025-08-06`
  **NeKI brief:** Collects machine-learning system-design case studies. Useful for broadening architecture review vocabulary around data, models, serving, and operational trade-offs.
- [Horoscope](https://github.com/artemnovichkov/horoscope) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** Horoscope generates developer-oriented output with Apple's Foundation Models, making it a compact example of on-device model integration. Useful for inspecting prompt-to-result plumbing and the availability assumptions of current Apple AI APIs.
- [Foundation Models Framework Example](https://github.com/rudrankriyam/Foundation-Models-Framework-Example) — iOS Dev Weekly · Issue 719 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `25th July 2025`
  **NeKI brief:** This source repository covers a practical lab for building, testing, and evaluating Apple Foundation Models apps. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ChatGPT in Xcode 26: there’s a hidden prompt!](https://www.swiftwithvincent.com/blog/chatgpt-in-xcode-26-theres-a-hidden-prompt) — SwiftLee Weekly · Issue 281 — Article · Topics: AI Development · Swift · Xcode
  **Published:** `2025-07-22T14:08:43.000Z`
  **NeKI brief:** Presents ChatGPT in Xcode 26: there’s a hidden prompt!, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing Kiro: Agentic IDE for Spec‑Driven Development](https://kiro.dev/blog/introducing-kiro) — Those Who Swift · Issue 223 — Article · Topics: AI Development · Product Design
  **Published:** `2025-07-16`
  **NeKI brief:** Introduces Kiro as a spec-driven agentic IDE. Useful for evaluating requirements-first development, generated changes, and the review boundaries needed around AI-assisted coding.
- [FoundationModels: Basic Prompting for an iOS Reader App](https://destiner.io/blog/post/foundation-models-basic-prompting-ios-reader-app) — Those Who Swift · Issue 223 — Article · Topics: AI Development · Foundation & Data Formats · Security & Privacy
  **Published:** `2025-07-16`
  **NeKI brief:** Introduces basic Foundation Models prompting in an iOS reader app. Useful for connecting on-device model requests to app context, prompt design, and user-visible failure handling.
- [CalcGPT.io](https://github.com/Calvin-LL/CalcGPT.io) — Those Who Swift · Issue 223 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2025-07-16`
  **NeKI brief:** Provides a small SwiftUI app for exploring calculator behavior. Useful for inspecting a concrete Apple-platform codebase and evaluating how UI state, calculation logic, and project structure are organized.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — SwiftLee Weekly · Issue 280 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to use Google Gemini in Xcode 26 beta](https://zottmann.org/2025/06/13/how-to-use-google-gemini.html) — iOS Dev Weekly · Issue 717 — Article · Topics: AI Development · Cross-Platform & Web · Xcode
  **Published:** `11th July 2025`
  **NeKI brief:** Explains using Google Gemini from a developer workflow, including request setup and practical integration considerations. Use it to compare hosted-model tooling, then verify current authentication, quotas, and data-handling terms.
- [Getting Started with Apple's Foundation Models](https://www.artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Those Who Swift · Issue 221 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Artem walks through using Apple’s new on-device Foundation Models framework to integrate Apple Intelligence’s LLMs into SwiftUI apps.
- [Copilot Open Source AI Editor: First Milestone](https://code.visualstudio.com/blogs/2025/06/30/openSourceAIEditorFirstMilestone) — Those Who Swift · Issue 221 — Article · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-07-02`
  **NeKI brief:** Describes an early milestone of an open-source AI editor based on VS Code. Useful for comparing editor extensibility, agent integration, and the operational trade-offs of adopting an evolving toolchain.
- [Machine Learning Q and AI](https://sebastianraschka.com/books/ml-q-and-ai) — Those Who Swift · Issue 221 — Article · Topics: AI Development
  **Published:** `2025-07-02`
  **NeKI brief:** Reviews Machine Learning Q and AI. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [late February](https://devclass.com/2025/02/27/anthropic-previews-claude-code-agentic-coding-capable-but-costly) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `27th June 2025`
  **NeKI brief:** Examines ¹ Claude Code entered “research preview” in late February and GitHub talked about the Copilot agent just a month ago. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [just a month ago](https://github.blog/news-insights/product-news/github-copilot-meet-the-new-coding-agent) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `27th June 2025`
  **NeKI brief:** The GitHub Blog article introduces GitHub Copilot's coding agent and explains its workflow for delegating software-engineering tasks.
- [AI Coding Assistant Benchmarks: Who Fixes iOS Crashes Best?](https://www.instabug.com/blog/benchmarking-ai-coding-assistants-for-mobile-app-crash-resolution) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `27th June 2025`
  **NeKI brief:** Examines Benchmarking AI Coding Assistants for Mobile App Crash Resolution | Luciq. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AI sceptic in LLM adventure land](https://aplus.rs/2025/ai-sceptic-in-llm-adventure-land) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Testing
  **Published:** `27th June 2025`
  **NeKI brief:** Presents ai sceptic in llm adventure land for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
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
- [Apple Intelligence APIs](https://alexanderlogan.co.uk/blog/wwdc25/01-apple-intelligence) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: AI Development · Apple Platform Ecosystem · Concurrency
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** The first part of a Foundation Models overview maps Apple Intelligence APIs relevant to app developers. Use it to orient implementation research, then cross-check model availability, privacy, and entitlement details against current Apple material.
- [parts here](https://alexanderlogan.co.uk/blog/wwdc25/02-apple-intelligence-tools) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Alex explains how developers can enhance on-device large language models with custom Swift tools letting their apps invoke system APIs or services (like HealthKit or network calls) and feed the real results back into the AI for richer responses.
- [Vibe Xcoding your apps](https://tuist.dev/blog/2025/05/13/vibe-xcoding) — iOS Dev Weekly · Issue 712 — Article · Topics: AI Development · Developer Community & Business
  **Published:** `16th May 2025`
  **NeKI brief:** Presents vibe xcoding your apps for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Using Model Context Protocol in iOS Apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Those Who Swift · Issue 214 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2025-05-15`
  **NeKI brief:** Artem continues exploring the Model Context Protocol (MCP) to facilitate interaction between AI models and external tools or data sources, this time showing how to access HealthKit data through the Claude API.
- [XcodeBuild MCP](https://github.com/cameroncooke/XcodeBuildMCP) — iOS Dev Tools · iOS Dev Tools: GrowASO, XcodeBuild MCP, Compot — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2025-05-01T14:50:23.226Z`
  **NeKI brief:** XcodeBuildMCP exposes Xcode build and simulator workflows through an MCP tool interface. Follow its repository for concrete automation commands and environment boundaries, while checking permission and tool-version requirements before use.
- [Creating MCP Servers in Swift](https://www.artemnovichkov.com/blog/creating-mcp-servers-in-swift) — SwiftLee Weekly · Issue 268 — Article · Topics: AI Development · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Artem explains how to create an MCP server (Model Context Protocol) that can be used to connect LLMs model with the tools that we use everyday using the Swift programming language.
- [the Model Context Protocol, a new standard for providing context to LLMs](https://www.anthropic.com/news/model-context-protocol) — iOS CI Newsletter · Issue 66 — Article · Topics: AI Development
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Discusses Model Context Protocol in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [ready-to-use MCP Servers](https://github.com/modelcontextprotocol/servers) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for ready-to-use MCP Servers, relevant to AI Development and Developer Community & Business. Inspect its implementation, open issues, and release state before adopting the approach.
- [Linear](https://github.com/jerhadf/linear-mcp-server) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Linear, relevant to AI Development and Developer Community & Business. Inspect its implementation, open issues, and release state before adopting the approach.
- [Filesystem](https://github.com/modelcontextprotocol/servers/blob/main/src/filesystem) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Filesystem, relevant to AI Development and Developer Community & Business. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub](https://github.com/modelcontextprotocol/servers/blob/main/src/github) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for GitHub, relevant to AI Development and Developer Community & Business. Inspect its implementation, open issues, and release state before adopting the approach.
- [Slack](https://github.com/modelcontextprotocol/servers/blob/main/src/slack) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Slack, relevant to AI Development and Developer Community & Business. Inspect its implementation, open issues, and release state before adopting the approach.
- [🤖 Interacting with GitHub Actions from an AI Assistant](https://github.com/ko1ynnky/github-actions-mcp-server) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Interacting with GitHub Actions from an AI Assistant, relevant to AI Development and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [🤖 Interacting with Bitrise from an AI Assistant](https://bitrise.io/blog/post/chat-with-your-builds-ci-and-more-introducing-the-bitrise-mcp-server) — iOS CI Newsletter · Issue 66 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Examines Interacting with Bitrise from an AI Assistant in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🍎 Can your AI Assistant help you with App Store Connect issues?](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Can your AI Assistant help you with App Store Connect issues?, relevant to AI Development and App Distribution & Store Operations. Inspect its implementation, open issues, and release state before adopting the approach.
- [Creating MCP Servers in SwiftLearn how to create a Model Context Protocol server in SwiftArtem Novichkov](https://www.artemnovichkov.com/blog/creating-mcp-servers-in-swift?ref=createwithswift.com) — Create with Swift · Issue 57 — Article · Topics: AI Development · Swift
  **Published:** `2025-04-18T15:00:48.000Z`
  **NeKI brief:** Artem explains how to create an MCP server (Model Context Protocol) that can be used to connect LLMs model with the tools that we use everyday using the Swift programming language.
- [🐙 GitHub Copilot code review now has Swift support](https://github.blog/changelog/2025-04-04-copilot-code-review-now-generally-available) — iOS CI Newsletter · Issue 65 — Article · Topics: AI Development · Code Quality · Developer Tools
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Copilot code review now has Swift support in the context of AI Development and Code Quality. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [integrated ChatGPT with Xcode](https://techcrunch.com/2024/11/14/chatgpt-can-now-read-some-of-your-macs-desktop-apps) — iOS Dev Weekly · Issue 706 — Article · Topics: AI Development · Xcode
  **Published:** `4th April 2025`
  **NeKI brief:** Examines OpenAI's ChatGPT is starting to work with other apps on your computer. On Thursday, the startup announced the ChatGPT desktop app for macOS can now read. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AppleAI](https://github.com/bunnysayzz/AppleAI) — iOS Dev Tools · iOS Dev Tools: WinWinKit, ASO.dev, NeoBrutalism — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-04-03T14:55:54.485Z`
  **NeKI brief:** AppleAI is a GitHub project exploring Apple-platform AI capabilities. Follow its source for concrete framework calls and integration experiments, while verifying availability, privacy boundaries, and current Apple API contracts independently.
- [How We Used LLMs to Help Us Find the Perfect Piece of Land for Our Future Home](https://krausefx.com//blog/how-we-used-llms-to-help-us-find-the-perfect-piece-of-land-for-our-future-home) — Those Who Swift · Issue 207 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2025-03-28`
  **NeKI brief:** Describes using LLMs to search for a property. Useful as an automation case study for tool orchestration and human review boundaries.
- [mcp-swift-sdk](https://github.com/loopwork-ai/mcp-swift-sdk) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** mcp-swift-sdk implements Model Context Protocol server and client concepts in Swift. Use it when exposing Apple-platform data or app capabilities to an agent through typed tools rather than maintaining a bespoke JSON protocol.
- [iMCP](https://github.com/loopwork-ai/iMCP) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** iMCP is a macOS MCP server that brokers access to local calendar, contacts, messages, reminders, and weather data. Use it to inspect permission-aware system-data tool design before connecting an agent to personal information.
- [Not all AI-assisted programming is vibe coding (but vibe coding rocks)](https://simonwillison.net/2025/Mar/19/vibe-coding) — iOS Dev Weekly · Issue 704 — Article · Topics: AI Development · Testing
  **Published:** `21st March 2025`
  **NeKI brief:** Distinguishes exploratory AI-assisted programming from the engineering work required to understand, test, and maintain generated code. It is useful for teams setting expectations around where rapid prompting helps and where conventional review and ownership remain necessary.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Those Who Swift · Issue 206 — Article · Topics: AI Development · Swift
  **Published:** `2025-03-19`
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Peek](https://prateekkeshari.gumroad.com/l/peek) — iOS Dev Tools · iOS Dev Tools: Statused, Compot, FreemiumKit — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-03-06T18:01:47.698Z`
  **NeKI brief:** Peek is a paid developer resource or utility distributed through Gumroad. Use the page to inspect its stated workflow and scope, verifying ownership, licensing, updates, and whether it solves a concrete development problem before purchase.
- [👨‍✈️ GitHub Copilot for Xcode is now generally available](https://github.blog/changelog/2025-02-14-code-completion-in-github-copilot-for-xcode-is-now-generally-available) — iOS CI Newsletter · Issue 62 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Copilot for Xcode is now generally available in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [AcceptedSE-0453InlineArray, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — SwiftLee Weekly · Issue 259 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-02-18T15:10:59.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [MLX Swift](https://github.com/ml-explore/mlx-swift) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** MLX Swift exposes Apple's MLX machine-learning array and model APIs to Swift applications on Apple Silicon. Useful for evaluating local inference pipelines that need native Swift integration rather than a Python-only runtime.
- [MLX-Outil project](https://github.com/rudrankriyam/MLX-Outil) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** MLX-Outil provides utilities around Apple's MLX machine-learning ecosystem for Swift or Apple-platform experiments. Follow it when evaluating local model tooling, checking supported models, performance, and API stability before production adoption.
- [SwiftUI Image Playground](https://www.youtube.com/watch?v=fjtWpQGs5lU) — Those Who Swift · Issue 200 — Video · Topics: AI Development · Swift · SwiftUI
  **Published:** `2025-02-05`
  **NeKI brief:** Integrates Image Playground into SwiftUI so users can generate images from concepts or an existing source image. The walkthrough covers availability requirements, presentation, generated-image handling, and fallback-aware application structure.
- [👨‍✈️ Give Copilot context about your repository](https://github.blog/changelog/2025-01-21-custom-repository-instructions-are-now-available-for-copilot-on-github-com-public-preview) — iOS CI Newsletter · Issue 60 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-01-28T00:00:00.000Z`
  **NeKI brief:** Examines Give Copilot context about your repository in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Active ReviewSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — SwiftLee Weekly · Issue 255 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2025-01-21T15:04:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — SwiftLee Weekly · Issue 255 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2025-01-21T15:04:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — SwiftLee Weekly · Issue 255 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2025-01-21T15:04:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Bringing App Intents to your SwiftUI App](https://tiagohenriques.vercel.app/blog/bringing-app-intents-to-your-swiftui-app) — iOS Dev Weekly · Issue 695 — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **Published:** `17th January 2025`
  **NeKI brief:** Presents bringing app intents to your swiftui app for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Translating an iOS/Mac app with AI and humans](https://adamwulf.me/2024/12/translating-an-ios-mac-app-with-ai-and-humans) — iOS Dev Weekly · Issue 694 — Article · Topics: AI Development
  **Published:** `10th January 2025`
  **NeKI brief:** Presents translating an ios/mac app with ai and humans for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Build High-Performance Chat Experiences Without the Hassle 🛠️](https://getstream.io/tutorials/ios-chat) — iOS CI Newsletter · Issue 58 — Tutorial · Topics: AI Development · Performance
  **Published:** `2024-12-29T00:00:00.000Z`
  **NeKI brief:** Walks through integrating Stream's chat SDK into an iOS app, including message UI and networking. Useful as an implementation reference when evaluating managed real-time messaging.
- [Exploring MLX Swift: Adding On-Device Inference to your App](https://www.rudrank.com/exploring-mlx-swift-adding-on-device-inference-to-your-app) — SwiftLee Weekly · Issue 250 — Article · Topics: AI Development · Swift
  **Published:** `2024-12-17T10:30:53.000Z`
  **NeKI brief:** Presents Exploring MLX Swift: Adding On-Device Inference to your App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating ML models with Create ML](https://www.artemnovichkov.com/blog/create-ml?ref=createwithswift.com) — Create with Swift · Issue 40 — Article · Topics: AI Development · Swift
  **Published:** `2024-12-13T16:30:39.000Z`
  **NeKI brief:** Artem show how to build custom machine learning models for iOS using Create ML, with a practical example of creating a multilingual sentiment analyzer with no extensive coding required.
- [ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube](https://youtube.com/playlist?list=PLvHc56e5L-7xgZsgvF2yL7P13lmTwNcoh&ref=ioscodereview.com) — iOS Code Review · Issue 74 — Video · Topics: Graphics, Media & Games · Xcode
  **Published:** `2024-12-04T11:30:50.000Z`
  **NeKI brief:** Records ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube as a visual walkthrough relevant to Graphics, Media & Games and Xcode. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Should we use Apple Intelligence for Text and Inputs in SwiftUI using writingToolsBehavior](https://medium.com/@jpmtech/should-we-use-apple-intelligence-for-text-and-inputs-in-swiftui-using-writingtoolsbehavior-49d662ce5ede) — SwiftLee Weekly · Issue 247 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2024-11-26T15:01:34.000Z`
  **NeKI brief:** Evaluates writingToolsBehavior for Apple Intelligence text assistance in SwiftUI inputs. Use it when deciding whether system writing tools fit an editor, checking availability, privacy expectations, and user-control requirements.
- [Exploring Apple Intelligence: Writing ToolsUnderstand Writing Tools, powered by Apple Intelligence.Create with SwiftAntonella Giugliano](https://www.createwithswift.com/exploring-apple-intelligence-writing-tools?ref=ioscodereview.com) — iOS Code Review · Issue 73 — Article · Topics: AI Development · Swift · UIKit
  **Published:** `2024-11-20T11:14:23.000Z`
  **NeKI brief:** Covers Writing Tools across SwiftUI and UIKit, including intelligent animation and ecosystem integration. Use it to compare framework-specific adoption paths and identify where text-editing controls can inherit system writing assistance.
- [Copilot is now available in Xcode (and it’s good!)](https://www.swiftwithvincent.com/blog/copilot-is-available-in-xcode) — SwiftLee Weekly · Issue 246 — Article · Topics: AI Development · Swift · Xcode
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Presents Copilot is now available in Xcode (and it’s good!), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ChatGPT for macOS can now work with Xcode](https://dimillian.medium.com/chatgpt-for-macos-can-now-work-with-xcode-28cecc9decf7) — SwiftLee Weekly · Issue 246 — Article · Topics: AI Development · macOS & AppKit · Xcode
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Presents ChatGPT for macOS can now work with Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [announcement of a new Xcode plug-in](https://github.blog/changelog/2024-10-29-github-copilot-code-completion-in-xcode-is-now-available-in-public-preview) — iOS Dev Weekly · Issue 686 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `8th November 2024`
  **NeKI brief:** Word??. This link is retained as a technical reading lead for Apple-platform development.
- [Shx Guo’s plugin](https://github.com/intitni/CopilotForXcode) — iOS Dev Weekly · Issue 686 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `8th November 2024`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Visual Studio Code Swift plugin](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang) — iOS Dev Weekly · Issue 686 — Tutorial · Topics: AI Development · Developer Community & Business · Swift
  **Published:** `8th November 2024`
  **NeKI brief:** Provides the Swift language extension for Visual Studio Code. Follow it when setting up language-server completion, diagnostics, and package workflows outside Xcode, while validating debugger and SDK limitations separately.
- [Testing the Untestable](https://allenpike.com/2024/testing-automated-evals) — iOS Dev Weekly · Issue 686 — Article · Topics: AI Development · Testing
  **Published:** `8th November 2024`
  **NeKI brief:** Presents four phases for automated evaluation of LLM-powered features, moving beyond a convincing demo toward repeatable quality checks. Follow it when defining fixtures, evaluation criteria, and release confidence for output whose correctness is probabilistic rather than binary.
- [a talk at Infer Vancouver](https://www.youtube.com/watch?v=ZwcN-APT_gE) — iOS Dev Weekly · Issue 686 — Video · Topics: AI Development · Testing
  **Published:** `8th November 2024`
  **NeKI brief:** Captures a technical talk presented at Infer Vancouver, providing a recorded explanation that can be followed alongside the speaker’s examples. Useful as supplemental learning material when the talk’s concrete subject matches the surrounding issue context.
- [GitHub Copilot for XcodeMicrosoft released an Xcode extension in a surprising turn of eventMediumThomas Ricouard](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173?ref=ioscodereview.com) — iOS Code Review · Issue 72 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2024-11-06T11:00:17.000Z`
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub Copilot for Xcode](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173) — SwiftLee Weekly · Issue 244 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2024-11-05T21:06:10.000Z`
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [the full event recap with a list of all announced features on GitHub’s website](https://github.blog/news-insights/product-news/universe-2024-previews-releases) — iOS CI Newsletter · Issue 54 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2024-11-03T00:00:00.000Z`
  **NeKI brief:** Summarises the full event recap with a list of all announced features on GitHub’s website for AI Development and Developer Tools. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Word??](https://github.blog/changelog/2024-10-29-github-copilot-code-completion-in-xcode-is-now-available-in-public-preview?ref=createwithswift.com) — Create with Swift · Issue 34 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `2024-11-01T19:30:40.000Z`
  **NeKI brief:** Word??. This link is retained as a technical reading lead for Apple-platform development.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [impossible](https://arxiv.org/abs/2401.11817) — iOS Dev Weekly · Issue 677 — Tutorial · Topics: AI Development · Developer Community & Business
  **Published:** `6th September 2024`
  **NeKI brief:** Examines Abstract page for arXiv paper 2401.11817: Hallucination is Inevitable: An Innate Limitation of Large Language Models. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Pieces Copilot+](https://pieces.app/) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI, Swinject, Pieces Copilot+ — Article · Topics: AI Development
  **Published:** `2024-07-11T14:52:09.603Z`
  **NeKI brief:** Pieces Copilot+ provides AI-assisted developer context and snippet workflows. Follow it for concrete capture, search, and code-assistance behavior, while reviewing privacy, local storage, and provider boundaries.
- [Jogo](https://www.avanderlee.com/swift/chatgpt-code-generation-prompts?ref=createwithswift.com) — Create with Swift · Issue 15 — Article · Topics: AI Development · Swift
  **Published:** `2024-05-31T15:00:03.000Z`
  **NeKI brief:** Presents five prompt patterns for generating Swift code, then stresses supplying context, constraints, and tests so output can be reviewed. Useful as a practical checklist for making AI-assisted coding reproducible rather than speculative.
- [the competition took a huge step forward earlier this week](https://www.youtube.com/live/DQacCB9tDaw) — iOS Dev Weekly · Issue 661 — Video · Topics: AI Development · App Intents & System Surfaces
  **Published:** `17th May 2024`
  **NeKI brief:** Examines OpenAI Spring Update – streamed live on Monday, May 13, 2024. Introducing GPT-4o, updates to ChatGPT, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to train your first machine learning model and run it inside your iOS app via CoreML](https://krausefx.com/blog/how-to-train-your-first-machine-learning-model-and-run-it-inside-your-ios-app-via-coreml?issue=031) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: AI Development · Developer Community & Business
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Walks through training a first machine-learning model with Create ML and embedding it in an iOS app through Core ML. Follow it to understand the model-conversion, packaging, and on-device inference workflow.
- [Turning AirPods into a Fitness Tracker to Fight Cancer](https://richarddas.com/blog/turning-airpods-into-fitness-trackers-to-fight-cancer?issue=031) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: AI Development
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Describes an experimental health-research project using AirPods-derived signals for fitness or cancer-related analysis. Use it as interdisciplinary product and sensing context, not as validated medical guidance or a ready-made HealthKit design.
- [Converting Local LLMs to Core ML Models - How to Use 🤗 Exporters](https://zenn.dev/shu223/articles/coreml-exporters) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: AI Development · Dependency Injection · Xcode
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Introduces exporting machine-learning models for Core ML, with attention to conversion tooling and deployment constraints. Use it to understand an end-to-end model-export workflow, verifying supported operators and runtime requirements for the target device.
- [Exporters](https://github.com/huggingface/exporters) — Fatbobman’s Swift Weekly · Issue 31 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Hugging Face Exporters converts trained models into deployment-oriented formats and artifacts. Follow it when an iOS ML pipeline needs a reproducible handoff from training output to Core ML or other runtime packaging.
- [MLX](https://github.com/ml-explore/mlx) — Fatbobman’s Swift Weekly · Issue 29 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** MLX is Apple's research-oriented array and machine-learning framework for Apple Silicon, exposing unified CPU/GPU memory concepts. Useful for evaluating local model experiments outside a Python-only workflow.
- [The Engineering Challenges of Scaling ChatGPT](https://newsletter.pragmaticengineer.com/p/scaling-chatgpt) — iOS Dev Weekly · Issue 658 — Tutorial · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `26th April 2024`
  **NeKI brief:** Presents the engineering challenges of scaling chatgpt for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) — Fatbobman’s Swift Weekly · Issue 27 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2024-04-15T22:00:50.399Z`
  **NeKI brief:** Ferret-UI studies grounded mobile-interface understanding with multimodal language models. Follow it for research context on extracting actionable UI structure from screenshots and interaction traces, distinct from ordinary OCR.
- [Let's VisionOS 2024](https://letsvisionos24.swiftgg.team/en) — Fatbobman’s Swift Weekly · Issue 26 — Article · Topics: AI Development · Spatial Computing · Swift
  **Published:** `2024-04-08T22:00:36.243Z`
  **NeKI brief:** Let’s VisionOS 2024 is a Beijing event focused on visionOS and Apple-platform development. Use it to find historical conference material and community perspectives, not as current API documentation or a direct implementation tutorial.
- [Mobile UI testing with Maestro (Swift version)](https://paul-samuels.com/blog/2023/12/13/mobile-ui-testing-with-maestro-swift) — Fatbobman’s Swift Weekly · Issue 11 — Article · Topics: AI Development · Swift · Testing
  **Published:** `2023-12-18T22:00:30.856Z`
  **NeKI brief:** Introduces Maestro-based mobile UI testing for Swift applications, using declarative flows to exercise screens and interactions. Use it when comparing black-box coverage and setup cost with XCTest or XCUITest in a CI pipeline.
- [Questions about the data to create LLMs for embeddings](https://rhonabwy.com/2023/11/15/questions-about-the-data-to-create-llms-for-embeddings) — Fatbobman’s Swift Weekly · Issue 7 — Article · Topics: AI Development · Architecture · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Raises practical questions about collecting and preparing data for embedding-oriented language models. Follow it when designing retrieval datasets and evaluating provenance, chunking, quality, and privacy rather than treating embeddings as a drop-in search feature.
- [ObservationBP](https://github.com/winddpan/ObservationBP) — Fatbobman’s Swift Weekly · Issue 7 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** ObservationBP back-ports Swift's Observation model for projects that cannot yet use the native deployment baseline. Follow it when weighing compatibility against maintenance and behavioral differences from the current framework implementation.
- [GitHub Universe keynote](https://youtu.be/NrQkdDVupQE) — iOS Dev Weekly · Issue 636 — Video · Topics: AI Development · Developer Tools
  **Published:** `17th November 2023`
  **NeKI brief:** Examines It’s a new age for GitHub. Join our CEO Thomas Dohmke and special guests for a stirring, high velocity keynote as we fundamentally redefine what it means to. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Copilot Workspace](https://youtu.be/NrQkdDVupQE?t=2627) — iOS Dev Weekly · Issue 636 — Video · Topics: AI Development · Developer Tools
  **Published:** `17th November 2023`
  **NeKI brief:** Examines It’s a new age for GitHub. Join our CEO Thomas Dohmke and special guests for a stirring, high velocity keynote as we fundamentally redefine what it means to. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Link to GitHub.](https://github.com/nsmet/omniprompt-gpt-mac-app) — iOS Dev Tools · 🔨 Introducing OmniPrompt, Xcodes, Rollbar — Source repository · Topics: Developer Tools
  **Published:** `2023-08-24T13:00:52.825Z`
  **NeKI brief:** Omniprompt GPT is a macOS application project for prompt or AI interaction. Follow its source for concrete UI, request, and provider integration, while verifying credentials, privacy, and current API assumptions.
- [Swift Transformers: Run On-Device LLMs on Apple Devices](https://huggingface.co/blog/swift-coreml-llm) — iOS Dev Weekly · Issue 622 — Article · Topics: AI Development · Personal Essays · Swift
  **Published:** `11th August 2023`
  **NeKI brief:** Explores Swift Transformers: Run On-Device LLMs on Apple Devices, focusing on there are a few different methods to get an llm. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Llama 2](https://ai.meta.com/llama) — iOS Dev Weekly · Issue 622 — Article · Topics: AI Development · Personal Essays · Swift
  **Published:** `11th August 2023`
  **NeKI brief:** Explores Llama 2, focusing on there are a few different methods to get an llm model, such as llama 2 running locally on your mac or ios. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [chat app](https://github.com/huggingface/swift-chat) — iOS Dev Weekly · Issue 622 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `11th August 2023`
  **NeKI brief:** Provides a macOS demonstration app for swift-transformers, showing how the project can host local language-model interactions. It is a concrete repository to inspect when evaluating a Swift-native prototype for on-device or desktop model experimentation.
- [Copilot for Xcode - Integrated AI Code Assistance](https://github.com/pointfreeco/swiftui-navigation) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Provides the source and change history for GitHub - pointfreeco/swiftui-navigation: Tools for making SwiftUI navigation simpler, more ergonomic and more…, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Apple Intelligence](https://bitsplitting.org/2023/05/25/apple-intelligence) — iOS Dev Weekly · Issue 611 — Article · Topics: AI Development · Xcode
  **Published:** `26th May 2023`
  **NeKI brief:** Explores Apple Intelligence, focusing on if, and it’s a huge if, apple announces anything related to ai in xcode, this is how they’ll do it. i’d also. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Using TabularData to Dump Model Data](https://www.swiftjectivec.com/using-the-tabulardata-framework-to-dump-json-or-csv-data-in-swift) — iOS Dev Weekly · Issue 608 — Article · Topics: AI Development · Swift
  **Published:** `5th May 2023`
  **NeKI brief:** Explores Using TabularData to Dump Model Data, focusing on if you read the framework description for tabulardata, you might. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [are not unheard of](https://gpl-violations.org/news/20060922-dlink-judgement_frankfurt) — iOS Dev Weekly · Issue 605 — Article · Topics: AI Development
  **Published:** `14th April 2023`
  **NeKI brief:** Examines Before I get into it, I’ll clarify the problem. It relates to the implications of using code licensed under “copyleft” and GPL-style licenses in the training data for tools like Copilot and other software based on OpenAI Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Copilot for Xcode Works Okay](https://christiantietze.de/posts/2023/04/copilot-for-xcode-works) — iOS Dev Weekly · Issue 605 — Article · Topics: AI Development · Xcode
  **Published:** `14th April 2023`
  **NeKI brief:** Explores Copilot for Xcode Works Okay, focusing on talking of copilot, christian tietze tried it, too. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Can ChatGPT write better SwiftUI code than you?](https://www.youtube.com/watch?v=dxxCPdcMcFw) — SwiftUI Weekly · SwiftUI Weekly - Issue #136 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2023-03-27T21:57:02.938Z`
  **NeKI brief:** Explores Can ChatGPT write better SwiftUI code than you?, focusing on there are a great many blog posts and youtube videos. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [use ChatGPT](https://www.digitaltrends.com/mobile/how-to-replace-siri-with-chatgpt-iphone) — iOS Dev Weekly · Issue 601 — Article · Topics: AI Development · App Intents & System Surfaces · Developer Tools
  **Published:** `17th March 2023`
  **NeKI brief:** Presents use ChatGPT, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [documentation search look like](https://github.com/arc53/docsgpt) — iOS Dev Weekly · Issue 600 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th March 2023`
  **NeKI brief:** Examines Private AI platform for agents, assistants and enterprise search. Built-in Agent Builder, Deep research, Document analysis, Multi-model support, and API connectivity for agents. -. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using ChatGPT to Help Write SwiftUI Code](https://crunchybagel.com/using-chatgpt-to-help-write-swiftui-code-in-streaks) — iOS Dev Weekly · Issue 596 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `10th February 2023`
  **NeKI brief:** Explores Using ChatGPT to Help Write SwiftUI Code, focusing on there have been so many blog posts on using chatgpt. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Glorp](https://maximumeffort.substack.com/p/i-taught-chatgpt-to-invent-a-language) — iOS Dev Weekly · Issue 588 — Article · Topics: AI Development
  **Published:** `9th December 2022`
  **NeKI brief:** Do you have any open positions at your company? You can post them for free over at iOS Dev Jobs. There’s really nothing to lose!
- [Prototyping SwiftUI interfaces with OpenAI's ChatGPT](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5jcmVhdGV3aXRoc3dpZnQuY29tL3Byb3RvdHlwaW5nLXN3aWZ0dWktaW50ZXJmYWNlcy13aXRoLW9wZW5haXMtY2hhdGdwdC8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkNTBhNTkyYy02YjBmLTQ4ZDQtODhhMS1jNjE1ZGE1NmVhMjQiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZTVkY2QxZmUtNjFmMC00YzNkLTk4MGYtODFhNTRiZTczYzk1IiwiaWF0IjoxNjc0MDYyNTU2Ljg4NiwiaXNzIjoib3JjaGlkIn0.--3_tX3nFerJI79NxG55TYekWMImzuRNPY5f2bXzyAs) — SwiftUI Weekly · SwiftUI Weekly - Issue #123 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2022-12-04T21:25:23.000Z`
  **NeKI brief:** Demonstrates using conversational prompts to scaffold SwiftUI code, making the gap between an idea and a runnable prototype smaller. Follow it to assess where generated UI accelerates exploration and where compile-time review remains essential.
- [Machine Learning](https://yono.ai/articles/wwdc22-machine-learning-digital-lounge) — iOS Dev Weekly · Issue 566 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Tools
  **Published:** `8th July 2022`
  **NeKI brief:** Summarizes the WWDC22 machine-learning digital-lounge material and its demonstrations. Useful as a compact orientation to the session topics before consulting Apple’s current machine-learning frameworks and documentation.
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
- [How to use GitHub Copilot with Swift](https://antran.app/2021/github_copilot_swift) — iOS Dev Weekly · Issue 532 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `5th November 2021`
  **NeKI brief:** Explores How to use GitHub Copilot with Swift, focusing on i’ve not thought much about github copilot since i wrote. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [playground with four improvement iterations](https://github.com/hybridcattt/remix-copilot-swift-playground/blob/main/RemixCopilot.playground/Contents.swift?ref=ioscodereview.com) — iOS Code Review · Issue 4 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2021-08-05T14:19:35.000Z`
  **NeKI brief:** Provides the source and change history for playground with four improvement iterations, relevant to AI Development and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Spokestack - AutoML tools that put custom voice into software](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zcG9rZXN0YWNrLmlvLz91dG1fY2FtcGFpZ249bWFrZXJfbGF1bmNoX1BBSUQmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPXN3aWZ0dWlfd2Vla2x5IiwicG9zdF9pZCI6Ijk4NTQyZmUzLTllOWYtNGZmOC05OWMwLTQ0ODc1NzNiZDY0MiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlMGQxNjc5Mi0xZmY1LTRhMjEtOTg0Yy00ZTk0MThiOWEzOWUiLCJpYXQiOjE2NzQwNjI2NzcuMDEsImlzcyI6Im9yY2hpZCJ9.atUK69hH2ROd-1KMu7E8qDPRvdFtWbAB5xcDUbJ8hiU) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Presents Spokestack tools for adding custom voice interfaces and models to software. Use it as a discovery lead when evaluating speech-triggered features, model training workflow, and service dependencies.
- [Apple machine learning in 2020](https://machinethink.net/blog/new-in-apple-machine-learning-2020) — iOS Dev Weekly · Issue 463 — Article · Topics: AI Development · Apple Platform Ecosystem
  **Published:** `3rd July 2020`
  **NeKI brief:** Covers Apple machine learning in 2020, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Can Users Control and Understand a UI Driven by Machine Learning?](https://www.nngroup.com/articles/machine-learning-ux) — iOS Dev Weekly · Issue 383 — Article · Topics: AI Development · Product Design
  **Published:** `21st December 2018`
  **NeKI brief:** The article examines whether users can understand and control machine-learning-driven interfaces and presents UX principles for explainability and control.
- [Apple open-sources Turi Create](https://github.com/apple/turicreate) — iOS Dev Weekly · Issue 331 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `15th December 2017`
  **NeKI brief:** Examines Apple open-sources Turi Create, focusing on by releasing turi create to the public, apple is making is easier than ever for people without a machine learning…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Learning with Privacy at Scale](https://machinelearning.apple.com/2017/12/06/learning-with-privacy-at-scale.html) — iOS Dev Weekly · Issue 330 — Article · Topics: AI Development · Cross-Platform & Web · Security & Privacy
  **Published:** `8th December 2017`
  **NeKI brief:** Despite all of the other posts on analytics this week 😀 this is the one that you should read. Differential privacy is a fascinating subject and like with any posts on Apple’s machine learning blog, while I don’t understand most of it, the results are really…
- [posts on analytics](http://chris.eidhof.nl/post/swift-analytics) — iOS Dev Weekly · Issue 330 — Article · Topics: AI Development · Security & Privacy · Swift
  **Published:** `8th December 2017`
  **NeKI brief:** Chris Eidhof’s Swift analytics post explores collecting and reasoning about application measurements. Follow it for concrete instrumentation ideas, while verifying privacy and modern telemetry constraints independently.
- [Deep Learning for Siri’s Voice](https://machinelearning.apple.com/2017/08/06/siri-voices.html) — iOS Dev Weekly · Issue 315 — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `25th August 2017`
  **NeKI brief:** Examines Siri is a personal assistant that communicates using speech synthesis. Starting in iOS 10 and continuing with new features in iOS 11, we…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Why Core ML will not work for your app (most likely)](http://alexsosn.github.io/ml/2017/06/09/Core-ML-will-not-Work-for-Your-App.html) — iOS Dev Weekly · Issue 307 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `30th June 2017`
  **NeKI brief:** Explores Why Core ML will not work for your app (most likely) in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Machine Learning for everyone](http://machinethink.net/blog/ios-11-machine-learning-for-everyone) — iOS Dev Weekly · Issue 305 — Article · Topics: AI Development · Graphics, Media & Games
  **Published:** `16th June 2017`
  **NeKI brief:** Explores Machine Learning for everyone in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [iOSDevUK](https://go.peterfriese.dev/iosdevuk-2026-issue-103?s=web&t=ext) — Not only Swift · Issue 103 — Tutorial · Topics: AI Development · Developer Community & Business · Swift
  **NeKI brief:** Routes to the iOSDevUK conference and workshop programme. Treat it as community-event discovery rather than technical implementation guidance.
- [Headless Xcode: From Prompt to Simulator with MCP](https://go.peterfriese.dev/ai-headless-xcode-from-prompt-to-simulator-with-mcp?s=web&t=ext) — Not only Swift · Issue 102 — Article · Topics: AI Development · Xcode
  **NeKI brief:** Shows how Xcode 27’s headless MCP server can be enabled, registered per project, and combined with exported Xcode skills. The walkthrough creates files, builds, renders SwiftUI previews, and verifies simulator interaction while retaining per-agent permission approval.
- [XcodeBuildMCP](https://go.peterfriese.dev/xcodebuildmcp?s=web&t=ext) — Not only Swift · Issue 102 — Article · Topics: AI Development · Xcode
  **NeKI brief:** Open-source MCP server and CLI that exposes Xcode build, test, simulator, and project operations to coding agents. Its client configuration and direct CLI modes make it useful for comparing scripted automation with agent-mediated tool calls.
- [Missing Xcode Tools Documentation](https://go.peterfriese.dev/ai-xcode-tools-docs?s=web&t=ext) — Not only Swift · Issue 102 — Article · Topics: AI Development · Xcode
  **NeKI brief:** Community-maintained reference for Xcode’s MCP tool surface, covering bridge registration, windowed and headless workspace identifiers, schemas, recipes, and individual tool behavior. Useful for discovering available build, run, test, preview, and project-edit operations in Xcode 27 beta.
- [Apple Foundation Models: Hybrid AI with Dynamic Profiles](https://go.peterfriese.dev/what-i-am-working-on-hybrid-ai-apple-foundation-models-gemini?s=web&t=ext) — Not only Swift · Issue 101 — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Demonstrates a LanguageModelSession.DynamicProfile router that measures prompt token requirements before choosing the on-device system model or Firebase Gemini. It includes a fallback path and illustrates keeping one session API while varying provider, context capacity, and inference cost.
- [Setting up a delivery pipeline for your agentic iOS projects](https://go.peterfriese.dev/tools-setting-up-a-delivery-pipeline-for-your-agentic-ios-projects?s=web&t=ext) — Not only Swift · Issue 100 — Article · Topics: AI Development
  **NeKI brief:** Describes an agentic iOS delivery pipeline built around repository instructions, planning, automated review, CI builds and tests, and rapid TestFlight feedback while retaining human code review.
- [AgenticSwift — AI Macros for Swift](https://go.peterfriese.dev/ai-agenticswift-macros?s=web&t=ext) — Not only Swift · Issue 99 — Article · Topics: AI Development · Macros & Metaprogramming · Swift
  **NeKI brief:** AgenticSwift experiments with a macro that asks a model to generate Swift implementation code. Inspect it to understand compile-time generation mechanics and the reproducibility, review, security, and build-dependency risks of placing an AI call in macro expansion.
- [this prompt](https://go.peterfriese.dev/agenticswift-macro-prompt?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: AI Development · Macros & Metaprogramming · Swift
  **NeKI brief:** Links directly to AgenticSwift’s macro implementation and embedded generation prompt. Use the source to audit what context is sent, how output becomes syntax, and where validation or deterministic fallbacks would be required.
- [From code breaking to code making](https://go.peterfriese.dev/from-code-breaking-to?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: AI Development
  **NeKI brief:** Traces a historical line from Bletchley Park code breaking to contemporary generative systems. Use the talk as computing-history framing for agentic development, not as current evidence about Apple APIs or model capabilities.
- [presented](https://go.peterfriese.dev/keynote-presentation-at-tnmoc?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: AI Development
  **NeKI brief:** Connects historical code breaking with modern code generation in a Bletchley Park keynote. It provides computing-history context for the issue’s ELIZA material rather than current Apple API guidance.
- [Play](https://youtube.com/watch?v=qx5QWrKhxM8) — Not only Swift · Issue 98 — Video · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Demonstrates a Firebase bridge that makes Gemini models available through Apple’s Foundation Models-style API. Use it to compare a cloud-model fallback with on-device sessions while keeping authentication, privacy, latency, and API compatibility explicit.
- [Claude](https://github.com/anthropics/ClaudeForFoundationModels) — Not only Swift · Issue 98 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Provides an adapter that exposes Claude through APIs shaped like Apple’s Foundation Models framework. Use the source to compare provider substitution and compatibility boundaries while accounting separately for cloud authentication, data transfer, latency, and cost.
- [Google](https://firebase.blog/posts/2026/06/apple-foundation-models-gemini) — Not only Swift · Issue 98 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Shows how Firebase can route Gemini through an interface compatible with Apple’s Foundation Models framework. It is useful for designing a cloud fallback, provided privacy, authentication, offline behavior, and model-capability differences remain explicit.
- [Foundation Models framework utilities](https://github.com/apple/foundation-models-utilities) — Not only Swift · Issue 98 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Apple’s experimental utilities repository collects emerging patterns for Foundation Models applications. Use it to inspect concrete helpers and examples, while treating the package as exploratory material whose APIs and production guarantees may still change.
- [Is the IDE dead?](https://go.peterfriese.dev/is-the-ide-dead?s=newsletter&t=ext) — Not only Swift · Issue 97 — Article · Topics: AI Development
  **NeKI brief:** Examines whether modern agent and editor workflows make the traditional IDE less central. The piece offers a tooling trade-off perspective for developers deciding how Xcode, editors, and agents should share responsibility.
- [Alt-Tab window switching for macOS](https://go.peterfriese.dev/alt-tab-window-switching?s=newsletter&t=ext) — Not only Swift · Issue 97 — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Covers a macOS utility for switching between windows rather than only applications. It is useful as a small productivity-tool reference for developers working across Xcode, simulators, terminals, and documentation.
- [How Generative and Agentic AI shift concern from technical debt to cognitive debt](http://margaretstorey.com/blog/2026/02/09/cognitive-debt) — Not only Swift · Issue 96 — Article · Topics: AI Development · Testing
  **NeKI brief:** This article covers how generative and agentic AI can shift technical debt into cognitive debt. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MCP is dead. Long live the CLI](https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html) — Not only Swift · Issue 95 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **NeKI brief:** This article covers the case for durable command-line interfaces over MCP-only tooling. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Perspective-Server: OpenAI-compatible API for Apple Foundation Models](https://github.com/Techopolis/Perspective-Server) — Not only Swift · Issue 95 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers exposing Apple Foundation Models through an OpenAI-compatible local API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Play](https://youtube.com/watch?v=bCz3Pc041ME) — Not only Swift · Issue 94 — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Coordinates multiple Antigravity agents through Git worktrees while refactoring a SwiftUI tagging interface and adding batched Firestore deletion. The session exposes planning, parallel review, merge, and compatibility decisions in a real codebase.
- [Xcode’s responses weren’t compatible with the MCP protocol](https://github.com/google-gemini/gemini-cli/issues/18371) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Describes Xcode’s responses weren’t compatible with the MCP protocol, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [fix on our end](https://github.com/google-gemini/gemini-cli/pull/18376) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Provides the public source repository for fix on our end. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [VecturaKit](https://github.com/rryam/VecturaKit) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Graphics, Media & Games
  **NeKI brief:** Provides the public source repository for VecturaKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Apple Docs MCP](https://github.com/kimsungwhee/apple-docs-mcp) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** This source repository covers an MCP server for searching Apple developer documentation. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [catch the replay](https://www.youtube.com/watch?v=bCz3Pc041ME) — Not only Swift · Issue 93 — Video · Topics: AI Development · Swift
  **NeKI brief:** Coordinates multiple Antigravity agents through Git worktrees while refactoring a SwiftUI tagging interface and adding batched Firestore deletion. The session exposes planning, parallel review, merge, and compatibility decisions in a real codebase.
- [agent-device](https://github.com/callstackincubator/agent-device) — Not only Swift · Issue 93 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** This source repository covers controlling iOS and Android devices from AI agents. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MCP CLI + Skill](https://github.com/philschmid/mcp-cli) — Not only Swift · Issue 92 — Source repository · Topics: AI Development · Developer Tools · Product Design
  **NeKI brief:** This source repository covers a lightweight CLI and skill for interacting with MCP servers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Improving Coding Agents with Help from Science](https://danicat.dev/posts/20260120-improving-agentic-coding-with-science) — Not only Swift · Issue 92 — Article · Topics: AI Development
  **NeKI brief:** This article covers applying scientific methods to improve coding agents. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [The Humbling Math of Health AI: Why ChatGPT Can’t Grade Your Heart Yet](https://be-curious-not-judgmental.com/2026/01/26/the-humbling-math-of-health-ai-why-chatgpt-cant-grade-your-heart-yet) — Not only Swift · Issue 92 — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** This article covers why health-AI answers require statistical humility and evidence. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Function calling: The missing piece for agentic apps](https://www.youtube.com/watch?v=d69KP1iFg5E) — Not only Swift · Issue 91 — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Implements Firebase AI Logic function calling in an iOS meal-planning app so the model can set and inspect timers. The five-step workflow covers declarations, tool requests, results, reliability settings, and safety boundaries.
- [Local MCP Development with Gemini CLI and Swift](https://dev.to/gde/local-mcp-development-with-gemini-cli-and-swift-1058) — Not only Swift · Issue 90 — Article · Topics: AI Development · Swift
  **NeKI brief:** This article covers local MCP development using Gemini CLI and Swift. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Intercepting SwiftUI Sheet Dismissal](https://livsycode.com/swiftui/intercepting-swiftui-sheet-dismissal) — Not only Swift · Issue 90 — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Artem shows how to intercept and control sheet dismissal in SwiftUI to detect when a presented sheet is being dismissed, letting you run custom logic or block the dismissal when needed.
- [Firebase After Hours #21: Agentic coding with Gemini Skills](https://youtube.com/live/9CwXD9rJnQQ) — Not only Swift · Issue 90 — Video · Topics: AI Development
  **NeKI brief:** This Firebase After Hours episode builds a custom Gemini CLI skill live. It demonstrates the skill authoring process and the practical shape of an agentic coding workflow while exploring how Firebase-related tasks can be exposed to an agent.
- [Firebase After Hours](https://www.youtube.com/playlist?list=PLl-K7zZEsYLk807wutFVVKom8HsB1H9m_) — Not only Swift · Issue 90 — Video · Topics: AI Development
  **NeKI brief:** This Firebase After Hours playlist collects the show's developer sessions, including the Gemini CLI skills walkthrough. It provides a durable video index for following the concrete agentic-coding and Firebase demonstrations referenced by the newsletter.
- [A Complete Guide To AGENTS.md](https://www.aihero.dev/a-complete-guide-to-agents-md) — Not only Swift · Issue 90 — Article · Topics: AI Development
  **NeKI brief:** This guide explains how to organize AGENTS.md files so coding agents receive scoped, maintainable repository instructions. It covers instruction hierarchy, placement, and practical authoring patterns for keeping project guidance discoverable without making every task context unwieldy.
- [A new Swift concurrency skill for AI agents](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Not only Swift · Issue 89 — Source repository · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [why LLMs actually can’t keep conversation history](https://www.youtube.com/watch?v=AZ_JYSYUmg4&t=118s) — Not only Swift · Issue 88 — Video · Topics: AI Development
  **NeKI brief:** Builds a SwiftUI chat with Firebase AI Logic, using its Chat API for conversation history, system instructions, multimodal messages, and streamed responses. Useful for separating model context management from the interface's incremental updates.
- [bjesus/pipet: Swiss-army tool for scraping and extracting data from online assets, made for hackers](https://github.com/bjesus/pipet) — Not only Swift · Issue 88 — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** This source repository covers a command-line scraper for extracting online assets. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [creating a slide deck for me](https://www.youtube.com/watch?v=ax6t6mvawXE&t=3469s) — Not only Swift · Issue 87 — Video · Topics: AI Development · Swift
  **NeKI brief:** Live-builds a Swift MCP server that controls Keynote, registers it with Claude Desktop, and generates a conference slide deck from a title and abstract. Useful for seeing desktop automation progress from tool definition to real artifact.
- [AI_dev](https://aideveu2025.sched.com/event/25TtL/beyond-prompts-building-intelligent-applications-with-genkit-and-the-model-context-protocol-peter-friese-google) — Not only Swift · Issue 87 — Article · Topics: AI Development · Swift
  **NeKI brief:** Lists a conference session on building intelligent applications with Genkit and the Model Context Protocol. Use it for architectural context around tool calling and orchestration, then validate implementation details in primary SDK documentation.
- [sneak preview of the new macros they’re working on](https://www.youtube.com/live/sfWYh-oxk8k?si=NLmSS8NcHtEUadXe&t=4877) — Not only Swift · Issue 87 — Video · Topics: AI Development · Macros & Metaprogramming · Swift
  **NeKI brief:** Live-codes Firebase AI Logic features in Swift, including JSON-schema structured output and Imagen-based image generation. The session also discusses API security, quota management, pricing choices, and forthcoming schema-annotation tooling.
- [How to build with Nano Banana: Complete Developer Tutorial](https://dev.to/googleai/how-to-build-with-nano-banana-complete-developer-tutorial-646) — Not only Swift · Issue 87 — Tutorial · Topics: AI Development
  **NeKI brief:** This article covers building with Nano Banana through a developer tutorial. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Some thoughts on LLMs and Software Development](https://martinfowler.com/articles/202508-ai-thoughts.html) — Not only Swift · Issue 87 — Article · Topics: AI Development · Cross-Platform & Web
  **NeKI brief:** Martin Fowler examines how generative AI is changing software-development practice, including the effects on programming tasks, review, design, and engineering judgment. The article is useful for evaluating where AI assistance changes development workflows while retaining responsibility for technical outcomes.
- [facade pattern](https://en.wikipedia.org/wiki/Facade_pattern) — Not only Swift · Issue 87 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** This reference entry covers the Facade design pattern and its interface boundary. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Creating MCP Servers in Swift](https://artemnovichkov.com/blog/creating-mcp-servers-in-swift) — Not only Swift · Issue 87 — Article · Topics: AI Development · Swift
  **NeKI brief:** This article explains how to create Model Context Protocol servers in Swift. It connects the protocol's tool-oriented model to Swift implementation details and shows how a server can expose useful capabilities to AI clients.
- [recording here](https://www.youtube.com/watch?v=ax6t6mvawXE) — Not only Swift · Issue 87 — Video · Topics: AI Development · Swift
  **NeKI brief:** Live-builds a Swift MCP server that controls Keynote, registers it with Claude Desktop, and generates a conference slide deck from a title and abstract. Useful for seeing desktop automation progress from tool definition to real artifact.
- [Rules for Rules: Writing Docs for LLMs](https://mbleigh.dev/posts/rules-for-rules) — Not only Swift · Issue 85 — Article · Topics: AI Development · Liquid Glass
  **NeKI brief:** This article covers writing effective rules and instructions for LLMs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Foundation Models Playgrounds: Comprehensive Examples for Apple's AI Framework](https://github.com/IvanCampos/Foundation-Models-Playgrounds) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers Foundation Models Framework examples for Apple-platform development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [17 Xcode Hacks Every iOS Developer Should Know in 2025](https://swift-pal.com/17-xcode-hacks-every-ios-developer-should-know-in-2025-1f0edb5119b8) — Not only Swift · Issue 85 — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Describes 17 Xcode Hacks Every iOS Developer Should Know in 2025, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [tool calling implementation](https://genkit.dev/go/docs/tool-calling) — Not only Swift · Issue 84 — Article · Topics: AI Development
  **NeKI brief:** This technical resource covers implementing tool calls with Genkit for Go. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Olleh: Ollama-compatible CLI for Apple's Foundation Models](https://github.com/loopwork/olleh) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers an Ollama-compatible command-line interface for Apple Foundation Models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [example with your Genkit flows](https://genkit.dev/docs/plugins/ollama) — Not only Swift · Issue 83 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** This technical resource covers connecting local Ollama models to Genkit flows. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [An OpenAI-compatible server for Apple's Foundation Models](https://github.com/gety-ai/apple-on-device-openai) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers serving Apple on-device models through an OpenAI-compatible API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Ice Cubes](https://github.com/Dimillian/IceCubesApp) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Provides the public source repository for Ice Cubes. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Play](https://youtube.com/watch?v=Xf0JO1sEnFw) — Not only Swift · Issue 81 — Video · Topics: AI Development · Personal Essays
  **NeKI brief:** This recording explains streaming Cloud Functions and the implementation considerations for delivering incremental results from a server-side function. It is useful for developers evaluating event-driven or streamed Firebase interactions in an application.
- [generate an entire slide deck by just talking to a model](https://www.youtube.com/live/ax6t6mvawXE?si=Dkov2LYiAYDcLwrl&t=6775) — Not only Swift · Issue 81 — Video · Topics: AI Development
  **NeKI brief:** Live-builds a Swift MCP server that controls Keynote, registers it with Claude Desktop, and generates a conference slide deck from a title and abstract. Useful for seeing desktop automation progress from tool definition to real artifact.
- [this tutorial](https://www.youtube.com/watch?v=lCyQ717DuzQ) — Not only Swift · Issue 79 — Video · Topics: AI Development
  **NeKI brief:** This tutorial demonstrates how a local API can expand the capabilities of LLM workflows, using an MCP server for Blender as a concrete example. It shows how tool access can let a model perform domain-specific operations without requiring the user to master the underlying application.
- [Building Your First Model Context Protocol Server](https://thenewstack.io/building-your-first-model-context-protocol-server) — Not only Swift · Issue 79 — Article · Topics: AI Development · Swift
  **NeKI brief:** This article covers building a first Model Context Protocol server. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Using MCP servers in VS Code](https://code.visualstudio.com/docs/copilot/chat/mcp-servers) — Not only Swift · Issue 79 — Article · Topics: AI Development
  **NeKI brief:** This technical resource covers adding and managing MCP servers in Visual Studio Code. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [official MCP Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) — Not only Swift · Issue 78 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Describes official MCP Swift SDK, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Understanding Temperature and Top-K in Language Models](https://bandarra.me/posts/understand-temperature-topk) — Not only Swift · Issue 78 — Article · Topics: AI Development
  **NeKI brief:** This article covers how temperature and top-k affect language-model output. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Here's how I use LLMs to help me write code](https://simonwillison.net/2025/Mar/11/using-llms-for-code) — Not only Swift · Issue 77 — Article · Topics: AI Development
  **NeKI brief:** This article covers a practitioner's workflow for using LLMs while writing code. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [recently said](https://newsletter.pragmaticengineer.com/p/ai-tools-for-software-engineers-simon-willison) — Not only Swift · Issue 77 — Article · Topics: AI Development
  **NeKI brief:** This interview and analysis examines Simon Willison's practical use of LLM tools for software engineering. It discusses concrete coding workflows, tool selection, and the need to evaluate AI-generated results rather than treating model output as automatically reliable.
- [How I use LLMs](https://www.youtube.com/watch?v=EWvNQjAaOHw) — Not only Swift · Issue 77 — Video · Topics: AI Development
  **NeKI brief:** This video explains how Simon Willison uses LLMs to write code and get more value from them. It presents practical prompting and workflow techniques alongside the engineering judgment needed to review and validate generated code.
