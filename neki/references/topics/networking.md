# Networking

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** URLSession, HTTP, GraphQL, WebSockets, API clients, and network reliability.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **238**

## Direct-source reading

- [Elasticsearch in Vapor: Getting Started | Kodeco](https://www.kodeco.com/9813028-elasticsearch-in-vapor-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Vapor example connects a server to a locally Dockerized Elasticsearch instance and indexes recipe documents, useful for understanding the boundary between request handling and search storage.
- [Alamofire | Kodeco](https://www.kodeco.com/9261385-alamofire) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Alamofire 5 course spans request construction, response serialization, uploads and certificate pinning. It is useful for comparing a mature networking abstraction’s ergonomics with URLSession, especially where authentication and transport hardening meet.
- [Vapor 4 Authentication: Getting Started | Kodeco](https://www.kodeco.com/9191035-vapor-4-authentication-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Vapor 4 starter implements both bearer-token and basic-header authentication, making the API boundary and credential transport choices concrete.
- [WebSockets on iOS with Starscream | Kodeco](https://www.kodeco.com/861-websockets-on-ios-with-starscream) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Starscream to establish WebSocket communication from iOS. Follow it when bidirectional updates need connection lifecycle, message parsing, and reconnect behavior beyond ordinary request-response networking.
- [Combine: Getting Started | Kodeco](https://www.kodeco.com/7864801-combine-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combine’s Publisher and Subscriber model is introduced through event streams and composition. Follow it to understand cancellation and backpressure boundaries before migrating callback-heavy code, rather than treating operators as interchangeable syntax for async work.
- [TCP Server With the SwiftNIO Networking Framework | Kodeco](https://www.kodeco.com/76-tcp-server-with-the-swiftnio-networking-framework) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a TCP server with SwiftNIO’s low-level networking primitives. Follow it to understand event loops, channel handlers, and byte-oriented protocols before relying on higher-level REST abstractions.
- [Networking With URLSession Course Updated for iOS 10, Xcode 8 and Swift 3 | Kodeco](https://www.kodeco.com/705-networking-with-urlsession-course-updated-for-ios-10-xcode-8-and-swift-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Describes a URLSession course spanning JSON GET and POST requests, authentication, client architecture, and testing in the Swift 3 era.
- [Alamofire 5 Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/6587213-alamofire-5-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A focused Alamofire 5 walkthrough builds an API client that encodes parameters and decodes responses. Follow it to see the boundary between concise request APIs and the explicit error, cancellation and data-validation work production clients still need.
- [Reachability in iOS | Kodeco](https://www.kodeco.com/5963-reachability-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses reachability information to react to changing network availability in an iOS app. Useful for treating connectivity as a changing condition around requests, rather than assuming a preflight boolean can guarantee that a network operation succeeds.
- [Alamofire: Uploading Files | Kodeco](https://www.kodeco.com/5745-alamofire-uploading-files) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uploads files with Alamofire and configures multipart request behavior. Useful for distinguishing file transfer construction, progress reporting, and server response handling in a media-upload feature.
- [Moya Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/5121-moya-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Models endpoints as Moya targets and layers authorization, providers, and response handling over Alamofire. Useful for seeing how a type-defined API surface can centralize request construction and make multiple services less repetitive and easier to test.
- [Alamofire Tutorial: Getting Started | Kodeco](https://www.kodeco.com/35-alamofire-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Alamofire with the Imagga API to upload and analyze photos. Useful for following a complete request flow that combines multipart networking, remote processing, and app-facing results.
- [Real-Time Communication with Streams Tutorial for iOS | Kodeco](https://www.kodeco.com/3437391-real-time-communication-with-streams-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a chat client around input/output streams, a message protocol, delegate callbacks, and connection cleanup. Useful for understanding the event-driven mechanics beneath a persistent socket before choosing a higher-level WebSocket or messaging library.
- [Advanced PostgreSQL With Vapor | Kodeco](https://www.kodeco.com/34237834-advanced-postgresql-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Advanced PostgreSQL features are used from Vapor for joins, views, indexes and full-text search. It is valuable when deciding which query work belongs in the database, where indexing and migration costs become part of the API design.
- [Running a Web Server on iOS with Vapor | Kodeco](https://www.kodeco.com/31498014-running-a-web-server-on-ios-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Runs a Vapor server inside an iOS app, adds file routes and upload/download handling, then exposes it beyond the device. Useful for examining the lifecycle and network implications of a local embedded server rather than assuming iOS is only a client.
- [Top 10 Libraries for iOS Developers in 2017 | Kodeco](https://www.kodeco.com/259-top-10-libraries-for-ios-developers-in-2017) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Surveys notable iOS libraries from its period. Useful only as historical discovery material; validate each library's maintenance and platform fit independently.
- [AWS AppSync for iOS | Kodeco](https://www.kodeco.com/21959081-aws-appsync-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** AWS AppSync for iOS demonstrates a GraphQL client backed by generated operations and synchronization services. Follow it to assess managed caching and offline behavior against the complexity of operating an API stack yourself.
- [GraphQL Tutorial for Server-Side Swift with Vapor: Getting Started | Kodeco](https://www.kodeco.com/21148796-graphql-tutorial-for-server-side-swift-with-vapor-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** GraphQL is added to a Vapor server through a typed schema and resolver layer. Follow it to compare client-selected fields with REST endpoints, while keeping resolver authorization and N+1 query costs visible.
- [Lessons Learned from Running an iOS Consultancy: Part 2 | Kodeco](https://www.kodeco.com/2099-lessons-learned-from-running-an-ios-consultancy-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Continues the consultancy reflection with scaling, communication, and networking lessons. Useful for considering operational constraints around an iOS practice alongside the implementation work itself.
- [Vapor and Job Queues: Getting Started | Kodeco](https://www.kodeco.com/18510630-vapor-and-job-queues-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds job queues to a Vapor service for deferred work. Useful for separating request latency from retryable background processing such as notifications or media tasks.
- [Getting Started with AWS AppSync for iOS | Kodeco](https://www.kodeco.com/16681770-getting-started-with-aws-appsync-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** AWS AppSync introduces typed GraphQL consumption in a SwiftUI client. Follow it to evaluate generated models and cache behavior against a hand-written URLSession layer, especially when schema evolution and offline reads matter.
- [SMS User Authentication With Vapor and AWS | Kodeco](https://www.kodeco.com/13508424-sms-user-authentication-with-vapor-and-aws) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements phone-number authentication by connecting Vapor to AWS SNS for verification messages. Use it to trace the security boundary between one-time-code delivery, server-side identity state, and the abuse controls an actual service still needs.
- [Alamofire Tutorial for iOS: Advanced Usage | Kodeco](https://www.kodeco.com/11668143-alamofire-tutorial-for-ios-advanced-usage) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Advanced Alamofire examples cover OAuth, network logging, and reachability, useful when a simple request wrapper grows into a diagnosable networking layer.
- [Getting Started With Server-Side Swift and Amazon Smoke | Kodeco](https://www.kodeco.com/11488641-getting-started-with-server-side-swift-and-amazon-smoke) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Amazon Smoke builds a server-side Swift REST API with typed routing and request handling. It is useful for comparing framework ergonomics with Vapor while keeping deployment and middleware responsibilities visible.
- [Sign in with Apple Using Vapor 4 | Kodeco](https://www.kodeco.com/11436647-sign-in-with-apple-using-vapor-4) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements Sign in with Apple across a Vapor backend, website, and iOS companion. It clarifies the token exchange and account-linking boundary so client presentation does not get confused with server-side credential validation.
- [Sending Push Notifications With Vapor | Kodeco](https://www.kodeco.com/11238593-sending-push-notifications-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows a Vapor server sending APNs push notifications to registered devices. It is useful for tracing device-token storage, payload construction, and delivery failures, while keeping notification triggering separate from the iOS app’s presentation policy.
- [AsyncImage improvements in iOS 27](https://nilcoalescing.com/blog/AsyncImageImprovementsInSwiftUIOnIOS27) — Nil Coalescing · article catalogue
  **Published:** `2026-06-22`
  **NeKI brief:** Covers iOS 27 AsyncImage improvements for loading behavior and presentation. Useful when replacing custom image loaders, while checking cache, cancellation, and failure semantics against the deployment target.
- [URLSession to Electrons: How Networking works on iOS](https://blog.jacobstechtavern.com/p/urlsession-to-electrons) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-04-28T15:03:29.486Z`
  **NeKI brief:** A layered networking deep dive that follows URLSession requests down through the Internet stack to the underlying hardware.
- [Network Requests Optimization using Xcode's Simulator & Agents - SwiftLee](https://www.avanderlee.com/ai-development/network-requests-optimization-using-xcodes-simulator-agents) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-04-14T09:06:47+00:00`
  **NeKI brief:** Combines simulator observation with agent-assisted profiling to inspect slow network requests, identify repeated work, and verify improvements. It provides a concrete loop for measuring request behavior rather than trusting perceived UI responsiveness.
- [VoiceOver Navigator & 120 FPS Recordings for Xcode's Simulator](https://www.avanderlee.com/xcode/voiceover-navigator-120-fps-recordings-for-xcode-simulator) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-02-24T11:11:21+00:00`
  **NeKI brief:** Shows simulator VoiceOver navigation and 120-FPS recording workflows for inspecting accessibility and animation details. The combination provides more diagnostic fidelity than screenshots when reporting focus order or motion regressions.
- [Replay - NSHipster](https://nshipster.com/replay) — NSHipster · article catalogue
  **Published:** `2025-12-31T00:00:00-08:00`
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.
- [The Great Connection Pool Meltdown](https://blog.jacobstechtavern.com/p/the-great-connection-pool-meltdown) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-11-06T16:02:23.569Z`
  **NeKI brief:** Analyses a production connection-pool failure and the cascading effects of saturation, retries, and recovery. Follow it for distributed-systems failure signals that can inform networking diagnostics in mobile backends.
- [Real-time systems with Combine and WebSockets](https://blog.jacobstechtavern.com/p/combine-vs-websockets) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-06-16T14:02:50.719Z`
  **NeKI brief:** Model a WebSocket feed as a stream with explicit connection, decoding, error, cancellation, and reconnection behavior, then compose downstream updates through Combine. Keep transport lifetime separate from UI subscriptions so reconnect policy and backpressure do not become accidental view-state behavior.
- [Should you use network connectivity checks in Swift? – Donny Wals](https://www.donnywals.com/should-you-use-network-connectivity-checks-in-swift) — Donny Wals · article catalogue
  **Published:** `2025-05-16T09:21:44+00:00`
  **NeKI brief:** Examines whether explicit network connectivity checks are useful in Swift apps. Use it to distinguish reachability hints from actual request outcomes and avoid blocking networking on unreliable preflight state.
- [WebSocket demo server in Node.js](https://nilcoalescing.com/blog/WebSocketDemoServerInNodeJS) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** A small Node.js WebSocket server exposes connection lifecycle, message framing, and broadcast behavior behind a minimal demo. Follow it to validate a Swift client protocol before introducing production authentication and reconnection policy.
- [Subscribe to Django ORM changes over a WebSocket connection](https://nilcoalescing.com/blog/DjangoChannelsRestFrameworkSubscribingToModels) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** Subscribing to Django ORM changes over a WebSocket turns model events into a live client stream, but requires explicit filtering and lifecycle handling. Follow it when designing server push beyond request-response APIs.
- [Expose Django REST-like API over a WebSocket connection](https://nilcoalescing.com/blog/DjangoChannelsRestFramework) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** Exposing a REST-like API over Django Channels demonstrates routing WebSocket messages into database-backed actions. The example helps compare persistent connections with HTTP while keeping serialization and authorization boundaries visible.
- [Managing WebSocket messages concurrently with detached actions](https://nilcoalescing.com/blog/DetachedActionsInDjangoChannelsRestFramework) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** Detached actions let concurrent WebSocket handlers perform work without blocking the receive loop, but introduce ordering and cancellation concerns. The article is useful for diagnosing races in message-driven async services.
- [Build a realtime social network using Django Channels](https://nilcoalescing.com/blog/BuildingARealtimeSocialNetworkUsingDjangoChannels) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** A realtime social network combines Django models, Channels consumers, and WebSocket fan-out, making event ownership explicit. Follow it for an end-to-end reference while evaluating presence, ordering, and reconnect behavior.
- [Network Link Conditioner: Simulating Slow Networking](https://www.avanderlee.com/debugging/network-link-conditioner-utility) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-01-27T10:02:13+00:00`
  **NeKI brief:** Shows how Network Link Conditioner profiles latency, bandwidth, and packet loss on Apple platforms. The workflow helps reproduce loading and retry failures under controlled conditions instead of relying on an engineer’s fast local connection.
- [Mocking a network connection in your Swift Tests – Donny Wals](https://www.donnywals.com/mocking-a-network-connection-in-your-swift-tests) — Donny Wals · article catalogue
  **Published:** `2024-12-12T09:56:48+00:00`
  **NeKI brief:** Injecting a controllable network connection keeps Swift tests deterministic and offline, letting failures assert request and response behavior without relying on a live server.
- [URLSession async await: API Requests & JSON Decoding](https://www.avanderlee.com/concurrency/urlsession-async-await-network-requests-in-swift) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-11-05T00:00:00+00:00`
  **NeKI brief:** Builds URLSession requests with async/await, HTTP validation, decoding, and typed error handling without third-party networking frameworks. The sequence provides a concrete baseline for deciding where retries and cancellation belong.
- [Getting ready for iOS 14 local network privacy restrictions](https://nilcoalescing.com/blog/GettingReadyForNewiOS14LocalNetworkPrivacyRestrictions) — Nil Coalescing · article catalogue
  **Published:** `2024-07-14`
  **NeKI brief:** iOS local-network privacy requires declaring usage and handling authorization before device discovery or LAN connections. Follow it when debugging connections that work in development but fail after privacy enforcement.
- [Network Path Monitoring](https://useyourloaf.com/blog/network-path-monitoring) — Use Your Loaf · article catalogue
  **Published:** `2023-05-29T13:01:12+01:00`
  **NeKI brief:** Uses NWPathMonitor to observe network-interface and connectivity changes. Useful for UI hints and retry policy, while keeping the server response authoritative about request success.
- [Accessing Security Scoped Files](https://useyourloaf.com/blog/accessing-security-scoped-files) — Use Your Loaf · article catalogue
  **Published:** `2023-05-08T11:26:43+01:00`
  **NeKI brief:** Explains why URLs returned by the system file picker need startAccessingSecurityScopedResource and a balanced stop call before reading outside the app container. The pattern makes iCloud and Files-provider access reliable instead of treating the URL as ordinary local storage.
- [Optimizing your app for Network Reachability - SwiftLee](https://www.avanderlee.com/swift/optimizing-network-reachability) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-04-25T07:45:16+00:00`
  **NeKI brief:** Uses NWPathMonitor to observe connectivity without treating reachability as proof that a request will succeed. Useful for gating retries or UI hints while keeping the server response authoritative.
- [How to Get Push Notification while iOS App is in Foreground | Sarunw](https://sarunw.com/posts/notification-in-foreground) — Sarunw · article catalogue
  **Published:** `2022-10-30`
  **NeKI brief:** Handles foreground notifications through the notification-center delegate, explicitly choosing whether alerts, sounds, or badges remain visible to the current user.
- [URLSessionConfiguration: Exploring opt-in configurations - SwiftLee](https://www.avanderlee.com/swift/urlsessionconfiguration) — Antoine van der Lee articles · article catalogue
  **Published:** `2022-07-19T08:05:51+00:00`
  **NeKI brief:** Compares URLSessionConfiguration choices for default, ephemeral, and background sessions, including caching, credentials, connectivity, and timeout behavior. The option-by-option examples help match transport policy to the app's privacy and reliability requirements.
- [Debugging Network Traffic With Proxyman – Donny Wals](https://www.donnywals.com/debugging-network-traffic-with-proxyman) — Donny Wals · article catalogue
  **Published:** `2022-05-12T09:21:21+00:00`
  **NeKI brief:** A proxy inspector exposes actual requests, headers, and responses, making network failures observable while requiring careful treatment of credentials and personal data.
- [Performing POST and file upload requests using URLSession | Swift by Sundell](https://www.swiftbysundell.com/articles/http-post-and-file-upload-requests-using-urlsession) — Swift by Sundell · article catalogue
  **Published:** `2022-05-07`
  **NeKI brief:** Constructs POST requests and multipart file uploads directly with URLSession, including headers, body encoding, and response handling. It clarifies when Foundation is sufficient and where request-format details become the real complexity.
- [How to reset push notification permission on macOS | Sarunw](https://sarunw.com/posts/how-to-reset-push-notification-permission-on-macos) — Sarunw · article catalogue
  **Published:** `2022-02-24`
  **NeKI brief:** Reset macOS notification authorization during development with the platform-specific permission reset workflow, then relaunch to retest first-run behavior. Treat this as test-environment maintenance; production apps cannot programmatically force the permission prompt to reappear.
- [How to reset push notification permission on iOS | Sarunw](https://sarunw.com/posts/how-to-reset-push-notification-permission-on-ios) — Sarunw · article catalogue
  **Published:** `2022-02-03`
  **NeKI brief:** Reset iOS notification permission only through the development environment's app or simulator state, then launch again to test the initial authorization path. Design the app to explain denied permission because production code cannot re-display the system prompt.
- [Combine: Networking and the dataTaskPublisher](https://www.createwithswift.com/reference-combine-networking-and-the-datataskpublisher) — Create with Swift · article catalogue
  **Published:** `2022-01-14T15:15:00.000Z`
  **NeKI brief:** Explains using Combine's URLSession dataTaskPublisher for networking, response validation, decoding, and error propagation. Keep transport, decoding, and UI state transformations separate for testability.
- [Unobtrusive runtime warnings for libraries](https://www.pointfree.co/blog/posts/70-unobtrusive-runtime-warnings-for-libraries) — Point-Free · article catalogue
  **Published:** `2022-01-03T06:00:00Z`
  **NeKI brief:** Runtime warnings can surface library misuse without crashing production, then become test failures in controlled contexts. The pattern balances observability with resilience and gives teams a migration path from warning to enforcement.
- [Task-based concurrency in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/task-based-concurrency-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2022-01-03`
  **NeKI brief:** Frames Tasks as a focused abstraction for asynchronous work, distinct from futures and Operation. Their lifetime and cancellation model make them suitable for scoped operations, but not automatically a replacement for every queue or workflow.
- [SceneStorage For Custom Types](https://useyourloaf.com/blog/scenestorage-for-custom-types) — Use Your Loaf · article catalogue
  **Published:** `2021-12-13T10:40:02+00:00`
  **NeKI brief:** Extends SceneStorage-style restoration to custom values, highlighting codability and scope constraints when scene state is richer than primitive URL or Boolean fields.
- [Lightweight dependency injection and unit testing using async functions | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-and-unit-testing-using-async-await) — Swift by Sundell · article catalogue
  **Published:** `2021-12-09`
  **NeKI brief:** Builds lightweight async tests by injecting a networking dependency and replacing it with protocol-based mocks. The pattern keeps asynchronous production code intact while making response timing and failure paths deterministic enough to test.
- [Mastering ProgressView in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2021/11/25/mastering-progressview-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2021-11-25T00:00:00+00:00`
  **NeKI brief:** Configures ProgressView styles and values for determinate or indeterminate progress. Style customization can match brand visuals, while accurate progress semantics matter more than decorative animation.
- [Referring to overloaded functions | Swift by Sundell](https://www.swiftbysundell.com/tips/referring-to-overloaded-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Shows how explicit function types or labels select one overload when passing a method as a value. Clarifying the expected signature helps the compiler and prevents accidental capture of a similarly named variant.
- [Functional networking | Swift by Sundell](https://www.swiftbysundell.com/tips/functional-networking) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Separates networking request construction and response decoding into composable functions, making each stage testable. The approach clarifies error translation, while retries and scheduling remain policy decisions above the functions.
- [Conditional conformances | Swift by Sundell](https://www.swiftbysundell.com/tips/conditional-conformances) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses conditional conformances so generic containers adopt protocols only when their elements qualify. This preserves type safety and avoids runtime checks, while constraints should remain simple enough for compiler diagnostics.
- [Combining values with functions | Swift by Sundell](https://www.swiftbysundell.com/tips/combining-values-with-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses function composition to combine value transformations without temporary variables. Composition clarifies pipelines when types line up, but named intermediate steps are preferable when diagnosing failures or branching.
- [Calling functions as closures with a tuple as parameters | Swift by Sundell](https://www.swiftbysundell.com/tips/calling-functions-as-closures-with-a-tuple-as-parameters) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Adapts function calls to tuple-shaped parameters for functional pipelines. Tuple adapters can reduce glue code, but named values often communicate intent better than positional elements.
- [Networking | Swift by Sundell](https://www.swiftbysundell.com/basics/networking) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Introduces networking as request construction, asynchronous transport, decoding, and error handling. Separate these stages to make retries, caching, and tests depend on clear policies.
- [Writing unit tests in Swift playgrounds | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-unit-tests-in-a-swift-playground) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses a Swift playground to experiment with lightweight unit tests and isolated behavior. It supports fast learning, but package or app tests remain necessary for build settings and integration coverage.
- [Writing end-to-end JSON mapping tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-end-to-end-json-mapping-tests-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Tests JSON mapping end-to-end from fixture data through decoding to domain assertions. These tests catch schema drift, while focused unit tests still help isolate individual decoding failures.
- [Using tokens to handle async Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/using-tokens-to-handle-async-swift-code) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses tokens to associate asynchronous callbacks with the current request and ignore stale results. Tokens prevent out-of-order UI updates, while cancellation should still stop unnecessary work where possible.
- [Useful APIs when writing scripts and tools in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/useful-apis-when-writing-scripts-and-tools-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Collects Foundation and process APIs useful for Swift command-line tools, such as paths and arguments. Tooling code still needs explicit error output and stable exit statuses for automation.
- [Under the hood of Futures and Promises in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/under-the-hood-of-futures-and-promises-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Explains futures and promises as abstractions for values delivered later and the state transitions they manage. They can organize callbacks, but cancellation and error propagation need explicit semantics.
- [Testing networking logic in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/testing-networking-logic-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Separates networking logic from URLSession by injecting a request-performing abstraction, then tests success and failure paths with deterministic stubs; the archived article remains useful for dependency boundaries and response decoding.
- [Published properties in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/published-properties-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses published properties to expose observable state changes to Combine or UI subscribers. Define ownership and scheduling so updates are consistent and subscriptions do not outlive their consumers.
- [Mocking in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/mocking-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses mocks selectively to observe collaborations in tests while avoiding replication of implementation details. Favor fakes or values when behavior can be tested without interaction-count assertions.
- [Generalizing Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/generalizing-swift-code) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Generalizes Swift code by extracting the true variable parts into parameters or generic constraints. Abstraction should follow repeated stable behavior, not anticipated reuse without evidence.
- [Functional networking in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/functional-networking-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Builds networking from composable pure request and response transformations, isolating side effects at the transport edge. This improves tests while authentication and retry policy stay explicit.
- [Extending Combine with convenience APIs | Swift by Sundell](https://www.swiftbysundell.com/articles/extending-combine-with-convenience-apis) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Extends Combine with domain-focused operators or helpers to remove repeated pipeline glue. Keep cancellation, scheduling, and error behavior visible so convenience does not obscure reactive lifecycle.
- [Defining testing data in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/defining-testing-data-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Separate test input construction from verification and define reusable stubs for values that are irrelevant to each assertion. Focused fixture builders reduce duplication, while explicit expected output keeps tests readable when models gain new fields.
- [Creating generic networking APIs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/creating-generic-networking-apis-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Creates generic networking APIs around typed requests and decoded responses. Keep transport, authentication, retries, and error mapping configurable rather than embedding all policy in one generic layer.
- [Constructing URLs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/constructing-urls-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Constructs URLs from components so paths, queries, and percent encoding remain structurally correct. Avoid concatenating raw strings, especially when user input supplies query values.
- [Building a token refresh flow using async await in Swift](https://www.donnywals.com/building-a-token-refresh-flow-with-async-await-and-swift-concurrency) — Donny Wals · article catalogue
  **Published:** `2021-08-16T06:45:32+00:00`
  **NeKI brief:** A token-refresh actor can serialize credential renewal so concurrent requests await one refresh, preventing duplicate network work and inconsistent authentication state.
- [URLSession: Common pitfalls with background download & upload tasks](https://www.avanderlee.com/swift/urlsession-common-pitfalls-with-background-download-upload-tasks) — Antoine van der Lee articles · article catalogue
  **Published:** `2021-05-04T07:39:17+00:00`
  **NeKI brief:** Details background URLSession constraints, including delegate ownership, identifiers, relaunch handling, and file-based transfer requirements. Foreground request code cannot simply be reused for reliable background transfers.
- [GraphQL in Swift | Swift with Majid](https://swiftwithmajid.com/2021/02/24/graphql-in-swift) — Swift with Majid · article catalogue
  **Published:** `2021-02-24T00:00:00+00:00`
  **NeKI brief:** GraphQL lets a client request an explicit response shape from an API. Use it when typed query composition and controlled payloads outweigh schema tooling costs, while handling partial errors separately from transport failure.
- [URLSessionConfiguration Quick Guide](https://useyourloaf.com/blog/urlsessionconfiguration-quick-guide) — Use Your Loaf · article catalogue
  **Published:** `2021-02-15T16:02:13+00:00`
  **NeKI brief:** Explains URLSessionConfiguration choices for cache, timeout, connectivity, and background transfers. Use it when networking policy must be configured deliberately rather than accepting the shared session defaults.
- [Building type-safe networking in Swift | Swift with Majid](https://swiftwithmajid.com/2021/02/10/building-type-safe-networking-in-swift) — Swift with Majid · article catalogue
  **Published:** `2021-02-10T00:00:00+00:00`
  **NeKI brief:** A type-safe networking layer represents endpoints, requests and decoded results with Swift types. Use it to move invalid combinations to compile time, while preserving clear error handling and testable transport seams.
- [Building a concurrency-proof token refresh flow in Combine – Donny Wals](https://www.donnywals.com/building-a-concurrency-proof-token-refresh-flow-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-11-09T08:30:48+00:00`
  **NeKI brief:** Builds a Combine token-refresh flow that prevents overlapping refresh requests. Use it when concurrent API failures must share one authentication renewal and retry safely.
- [Building a simple remote configuration loader for your apps – Donny Wals](https://www.donnywals.com/building-a-simple-remote-configuration-for-your-apps) — Donny Wals · article catalogue
  **Published:** `2020-10-26T21:01:31+00:00`
  **NeKI brief:** Remote configuration separates app behavior from a binary release, but fetched values need defaults, validation, caching, and an owner for rollout safety.
- [Launching iOS Apps with a Custom URL Scheme](https://useyourloaf.com/blog/launching-ios-apps-with-a-custom-url-scheme) — Use Your Loaf · article catalogue
  **Published:** `2020-09-21T13:30:33+01:00`
  **NeKI brief:** Launches an app with a custom URL scheme, clarifying registration, parsing, and scene handoff responsibilities for deep-link behavior.
- [Implementing a one-way sync strategy with Core Data, URLSession and Combine](https://www.donnywals.com/implementing-a-one-way-sync-strategy-with-core-data-urlsession-and-combine) — Donny Wals · article catalogue
  **Published:** `2020-08-24T10:40:45+00:00`
  **NeKI brief:** A one-way sync pipeline fetches remote data, maps it, and persists it into Core Data, requiring conflict and offline-refresh policy at the boundary.
- [HTTP in Swift, Part 12: Retrying | Dave DeLong](https://davedelong.com/blog/2020/07/23/http-in-swift-part-12-retrying) — Dave DeLong · article catalogue
  **Published:** `2020-07-23T00:00:00+00:00`
  **NeKI brief:** Retries are modeled as a loader policy rather than embedded in endpoints, so response suitability and retry limits stay configurable; careless policies can amplify server load.
- [HTTP in Swift, Part 10: Cancellation | Dave DeLong](https://davedelong.com/blog/2020/07/19/http-in-swift-part-10-cancellation) — Dave DeLong · article catalogue
  **Published:** `2020-07-19T00:00:00+00:00`
  **NeKI brief:** Cancellation is propagated through the loader chain so in-flight work can stop without changing request construction; every loader must honor that signal or cancellation becomes partial.
- [Understanding the importance of abstractions – Donny Wals](https://www.donnywals.com/understanding-the-importance-of-abstractions) — Donny Wals · article catalogue
  **Published:** `2020-07-13T07:00:05+00:00`
  **NeKI brief:** Abstractions hide volatile implementation details behind stable intent, but an unnecessary layer can make behavior harder to trace than the dependency it replaces.
- [Recursively execute a paginated network call with Combine – Donny Wals](https://www.donnywals.com/recursively-execute-a-paginated-network-call-with-combine) — Donny Wals · article catalogue
  **Published:** `2020-06-15T07:15:40+00:00`
  **NeKI brief:** Recursive pagination chains each response into the next request until exhaustion, requiring cancellation, error propagation, and termination conditions to remain centralized.
- [Retrying a network request with a delay in Combine – Donny Wals](https://www.donnywals.com/retrying-a-network-request-with-a-delay-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-05-25T07:00:01+00:00`
  **NeKI brief:** Delayed retries combine failure handling with scheduling, reducing immediate repeat traffic while requiring a bounded policy for persistent server errors.
- [Throttle network speeds for a specific host in Charles – Donny Wals](https://www.donnywals.com/throttle-network-speeds-for-a-specific-host-in-charles) — Donny Wals · article catalogue
  **Published:** `2020-05-21T10:32:26+00:00`
  **NeKI brief:** Host-specific network throttling simulates constrained backend conditions without slowing unrelated traffic, making latency and failure behavior testable during development.
- [Decode an array with a corrupted element | Sarunw](https://sarunw.com/posts/decode-array-with-corrupted-element) — Sarunw · article catalogue
  **Published:** `2020-05-15`
  **NeKI brief:** Codable normally fails an entire array when one element violates its schema, which is the right default for controlled APIs. For legacy or third-party data, decode elements through a lossy optional wrapper, discard failures deliberately, and log the data-quality trade-off.
- [How to mock Alamofire and URLSession requests in Swift](https://www.avanderlee.com/swift/mocking-alamofire-urlsession-requests) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-03-10T08:00:00+00:00`
  **NeKI brief:** Introduces protocol abstraction and URLProtocol interception for mocking Alamofire or URLSession responses. Tests exercise decoding and error paths deterministically without real network calls.
- [Authentication with signed requests in Alamofire 5 - SwiftLee](https://www.avanderlee.com/swift/authentication-alamofire-request-adapter) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-02-25T08:00:00+00:00`
  **NeKI brief:** Uses Alamofire's RequestAdapter to attach signed authentication data consistently, centralizing credential preparation and retry behavior. Endpoint code stays focused on payloads.
- [Debugging network traffic with Charles – Donny Wals](https://www.donnywals.com/debugging-network-traffic-with-charles) — Donny Wals · article catalogue
  **Published:** `2020-01-22T08:00:03+00:00`
  **NeKI brief:** Charles exposes live HTTP requests and responses from simulator or device traffic, making transport failures inspectable while demanding careful credential handling.
- [Refactoring a networking layer to use Combine – Donny Wals](https://www.donnywals.com/refactoring-a-networking-layer-to-use-combine) — Donny Wals · article catalogue
  **Published:** `2020-01-20T08:00:13+00:00`
  **NeKI brief:** A Combine networking layer expresses requests, decoding, errors, and cancellation as one pipeline, but scheduler and lifetime choices become part of the API contract.
- [The magic of view preferences in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2020/01/15/the-magic-of-view-preferences-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2020-01-15T00:00:00+00:00`
  **NeKI brief:** SwiftUI preferences propagate child-produced values upward through the view tree. They are useful for layout and metadata communication without references, provided preference reduction remains deterministic.
- [Building networking layer using functions | Swift with Majid](https://swiftwithmajid.com/2020/01/08/building-networking-layer-using-functions) — Swift with Majid · article catalogue
  **Published:** `2020-01-08T00:00:00+00:00`
  **NeKI brief:** A functional networking layer composes request-building and response-decoding functions. Follow it to keep transport concerns testable and replaceable, while retaining explicit error and cancellation behavior.
- [URLSession.DataTaskPublisher’s failure type – Ole Begemann](https://oleb.net/2020/urlsession-publisher) — Ole Begemann · article catalogue
  **Published:** `2020-01-07T17:47:02Z`
  **NeKI brief:** URLSession.DataTaskPublisher chooses a failure type that separates transport errors from HTTP status handling, leaving response validation to the pipeline. The article is a useful reminder to model status-code policy explicitly instead of assuming publisher failure means a bad response.
- [Wrapping Third Party APIs · objc.io](https://www.objc.io/blog/2019/03/19/wrapping-third-party-apis) — objc.io · article catalogue
  **Published:** `2019-3-19`
  **NeKI brief:** Wrapping a third-party API behind a local protocol isolates vendor types, error semantics, and replacement cost from the application. The boundary improves testing, but adds an adapter that must track upstream behavior deliberately.
- [Fetching and displaying data from the network – Donny Wals](https://www.donnywals.com/fetching-and-displaying-data-from-the-network) — Donny Wals · article catalogue
  **Published:** `2019-12-20T08:00:52+00:00`
  **NeKI brief:** Fetching remote data for UI requires separating transport, decoding, loading state, and presentation so failures and retries do not become view-controller side effects.
- [Architecting a robust networking layer with protocols – Donny Wals](https://www.donnywals.com/architecting-a-robust-networking-layer-with-protocols) — Donny Wals · article catalogue
  **Published:** `2019-12-19T08:00:01+00:00`
  **NeKI brief:** Protocol-based networking boundaries let endpoints and transports be replaced in tests, while error mapping and request ownership remain explicit application policy.
- [Efficiently loading images in table views and collection views – Donny Wals](https://www.donnywals.com/efficiently-loading-images-in-table-views-and-collection-views) — Donny Wals · article catalogue
  **Published:** `2019-12-04T07:30:20+00:00`
  **NeKI brief:** Efficient scrolling image loading combines caching, cancellation, and cell-identity checks so reused cells do not display stale network results.
- [Real time data exchange using web sockets in iOS 13 – Donny Wals](https://www.donnywals.com/real-time-data-exchange-using-web-sockets-in-ios-13) — Donny Wals · article catalogue
  **Published:** `2019-11-18T07:00:07+00:00`
  **NeKI brief:** WebSockets maintain a bidirectional connection for live events, requiring reconnect, ordering, and lifecycle policy beyond the basic receive loop.
- [Uploading images and forms to a server using URLSession – Donny Wals](https://www.donnywals.com/uploading-images-and-forms-to-a-server-using-urlsession) — Donny Wals · article catalogue
  **Published:** `2019-10-30T07:30:13+00:00`
  **NeKI brief:** Multipart URLSession uploads assemble fields and binary data with a boundary, requiring correct content type, streaming policy, and error handling for large files.
- [Supporting Low Data Mode in your app – Donny Wals](https://www.donnywals.com/supporting-low-data-mode-in-your-app) — Donny Wals · article catalogue
  **Published:** `2019-09-23T00:00:11+00:00`
  **NeKI brief:** Shows responding to the system Low Data Mode preference when scheduling network work. Use it to reduce image quality, defer refreshes, or alter downloads without treating connectivity as simply online or offline.
- [Apple Push Notification Device Tokens - NSHipster](https://nshipster.com/apns-device-tokens) — NSHipster · article catalogue
  **Published:** `2019-09-16T00:00:00-07:00`
  **NeKI brief:** Explains APNs device-token registration and the lifecycle of token values. Follow it when designing push-token upload, refresh handling, and server association without assuming a token is permanent per installation.
- [Dark Mode on iOS 13 - NSHipster](https://nshipster.com/dark-mode) — NSHipster · article catalogue
  **Published:** `2019-09-02T00:00:00-07:00`
  **NeKI brief:** Dark Mode adoption spans asset colors, semantic system colors, and trait-driven UI updates; hard-coded RGB values bypass that adaptation. The migration guidance keeps contrast and appearance changes coherent across UIKit views.
- [MapKit JS - NSHipster](https://nshipster.com/mapkit-js) — NSHipster · article catalogue
  **Published:** `2019-03-11T00:00:00-07:00`
  **NeKI brief:** MapKit JS moves Apple's map rendering and search model into web clients, with token configuration and browser lifecycle replacing native delegates. The article highlights the integration trade-off between shared map capabilities and web-specific authentication and performance.
- [Alamofire vs URLSession: a comparison for networking in Swift - SwiftLee](https://www.avanderlee.com/swift/alamofire-vs-urlsession) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-01-29T14:22:55+00:00`
  **NeKI brief:** Compares Foundation URLSession with Alamofire across API ergonomics, dependency cost, and built-in request features. Useful for making a networking choice based on project needs instead of assuming an external abstraction is automatically better.
- [Faster App Setup For Unit Tests](https://useyourloaf.com/blog/faster-app-setup-for-unit-tests) — Use Your Loaf · article catalogue
  **Published:** `2019-01-28T10:34:42+00:00`
  **NeKI brief:** Describes reducing application launch overhead for unit tests by separating test setup from full app initialization. Follow it when test suites are slow because production composition runs unnecessarily for isolated cases.
- [Swift Tip: Networking with Codable · objc.io](https://www.objc.io/blog/2018/02/06/networking-with-codable) — objc.io · article catalogue
  **Published:** `2018-2-6`
  **NeKI brief:** Codable can decode network payloads directly into domain-adjacent Swift types. Use dedicated transport models when wire formats are unstable, mapping and validating at the boundary rather than leaking decoding details across the app.
- [Roy Fielding’s REST dissertation – Ole Begemann](https://oleb.net/2018/rest) — Ole Begemann · article catalogue
  **Published:** `2018-10-31T22:49:07Z`
  **NeKI brief:** Roy Fielding's REST dissertation distinguishes resources, representations, and uniform interface constraints from the looser meaning of HTTP API. The summary is useful when evaluating whether a service actually benefits from REST semantics or merely uses JSON endpoints.
- [iOS 12 - NSHipster](https://nshipster.com/ios-12) — NSHipster · article catalogue
  **Published:** `2018-09-17T00:00:00-07:00`
  **NeKI brief:** Provides a version-scoped overview of iOS 12 APIs and platform behavior. Follow it for legacy maintenance or deployment-target migration, not as current guidance without checking modern SDK replacements.
- [NSDataAsset - NSHipster](https://nshipster.com/nsdataasset) — NSHipster · article catalogue
  **Published:** `2018-08-26T00:00:00-07:00`
  **NeKI brief:** Shows packaging binary data in asset catalogs with NSDataAsset and loading it by name. Follow it when bundling configuration, certificates, or other data resources while keeping target membership and lookup explicit.
- [Making illegal states unrepresentable – Ole Begemann](https://oleb.net/blog/2018/03/making-illegal-states-unrepresentable) — Ole Begemann · article catalogue
  **Published:** `2018-03-26T14:50:00Z`
  **NeKI brief:** Applies sum types and constrained value models to prevent invalid combinations from compiling. Follow it when domain state has mutually exclusive cases and runtime validation is becoming repetitive or incomplete.
- [Apple Networking Feedback | Dave DeLong](https://davedelong.com/blog/2018/03/02/apple-networking-feedback) — Dave DeLong · article catalogue
  **Published:** `2018-03-02T00:00:00+00:00`
  **NeKI brief:** Presents developer feedback on Apple's networking APIs and their ergonomics. Use it as historical API-design discussion when comparing URLSession abstractions and current networking guidance.
- [URLSession Waiting For Connectivity](https://useyourloaf.com/blog/urlsession-waiting-for-connectivity) — Use Your Loaf · article catalogue
  **Published:** `2017-11-27T11:23:28+00:00`
  **NeKI brief:** Explains URLSession's wait-for-connectivity behavior for requests made without immediate network access. Follow it when deciding whether retries should be delegated to the system or modeled explicitly in app state.
- [openURL Deprecated in iOS10](https://useyourloaf.com/blog/openurl-deprecated-in-ios10) — Use Your Loaf · article catalogue
  **Published:** `2016-09-19T12:07:50+01:00`
  **NeKI brief:** Migrates deprecated openURL calls to options-based APIs with completion reporting. Treat launch success as a request outcome, not proof the destination completed the desired user flow.
- [WWDC 2016 Viewing Guide](https://useyourloaf.com/blog/wwdc-2016-viewing-guide) — Use Your Loaf · article catalogue
  **Published:** `2016-06-20T12:39:29+01:00`
  **NeKI brief:** Indexes WWDC16 sessions for focused discovery of platform changes. It is a historical routing aid; linked material must be checked for API deprecation and current availability.
- [Open Settings URL](https://useyourloaf.com/blog/open-settings-url) — Use Your Loaf · article catalogue
  **Published:** `2014-08-28T16:06:01+01:00`
  **NeKI brief:** Uses the Settings URL to route a user to an app's privacy settings after access was denied. Explain why the change is needed and handle return-to-app state rather than assuming permission changed.
- [iOS 8 - NSHipster](https://nshipster.com/ios8) — NSHipster · article catalogue
  **Published:** `2014-06-09T00:00:00-07:00`
  **NeKI brief:** This iOS 8 API tour examines LocalAuthentication, WKWebView, NSQualityOfService, HealthKit statistics, motion data and Foundation formatter additions. Use it to decode legacy code paths, verifying modern availability and privacy requirements before reuse.
- [NSURL /NSURLComponents - NSHipster](https://nshipster.com/nsurl) — NSHipster · article catalogue
  **Published:** `2014-03-24T00:00:00-07:00`
  **NeKI brief:** Explains URL parsing and construction with NSURL and NSURLComponents. Useful for keeping scheme, host, path, and query manipulation structured instead of assembling fragile URL strings.
- [Multipeer Connectivity - NSHipster](https://nshipster.com/multipeer-connectivity) — NSHipster · article catalogue
  **Published:** `2013-12-09T00:00:00-08:00`
  **NeKI brief:** Multipeer Connectivity discovers nearby peers and exchanges data over local transports. Follow it to model invitations, sessions and unreliable proximity, rather than assuming cloud-style connectivity or identity guarantees.
- [NSNotification &NSNotificationCenter - NSHipster](https://nshipster.com/nsnotification-and-nsnotificationcenter) — NSHipster · article catalogue
  **Published:** `2013-12-02T00:00:00-08:00`
  **NeKI brief:** NotificationCenter broadcasts decoupled events without direct object references. The article is useful for system-wide signals, while emphasizing observer lifetime and avoiding notifications as an untraceable substitute for ownership.
- [FileManager - NSHipster](https://nshipster.com/filemanager) — NSHipster · article catalogue
  **Published:** `2013-11-18T00:00:00-08:00`
  **NeKI brief:** FileManager handles file creation, moves, copies and directory traversal through URL-based APIs. Follow it when implementing storage features, with sandbox locations, coordination and errors treated as part of the design.
- [NSError - NSHipster](https://nshipster.com/nserror) — NSHipster · article catalogue
  **Published:** `2013-10-14T00:00:00-07:00`
  **NeKI brief:** NSError carries domain, code and userInfo context across Objective-C APIs. The article is useful when bridging to Swift Error, preserving recoverable information instead of flattening failures into display strings.
- [Network Link Conditioner - NSHipster](https://nshipster.com/network-link-conditioner) — NSHipster · article catalogue
  **Published:** `2013-09-09T00:00:00-07:00`
  **NeKI brief:** Network Link Conditioner simulates bandwidth, latency and packet loss on Apple platforms. Follow it to test failure and loading states under realistic conditions instead of assuming simulator or office Wi-Fi behavior.
- [On NSURLConnection API Design – Ole Begemann](https://oleb.net/blog/2013/07/nsurlconnection-api-design) — Ole Begemann · article catalogue
  **Published:** `2013-07-08T21:48:00Z`
  **NeKI brief:** Explains why NSURLConnection's browser-oriented delegate design differs from typical web-service needs, providing historical context when migrating legacy networking code to modern URLSession abstractions.
- [Migrating to the new Twitter search API](https://useyourloaf.com/blog/migrating-to-the-new-twitter-search-api) — Use Your Loaf · article catalogue
  **Published:** `2013-06-24T17:00:00+00:00`
  **NeKI brief:** Describes migrating an external Twitter search integration to a changed API. The durable lesson is isolating vendor clients behind an adapter so authentication and payload changes remain contained.
- [Restoration Classes and UIWebViews](https://useyourloaf.com/blog/restoration-classes-and-uiwebviews) — Use Your Loaf · article catalogue
  **Published:** `2013-05-23T21:10:00+00:00`
  **NeKI brief:** Explains state-restoration classes and web-view restoration as historical UIKit patterns. Restored content must validate URLs and user context; unsupported web-view APIs should be replaced in current code.
- [NSURLCache - NSHipster](https://nshipster.com/nsurlcache) — NSHipster · article catalogue
  **Published:** `2013-02-11T00:00:00-08:00`
  **NeKI brief:** URLCache stores HTTP responses according to cache policy and headers. Use it to reduce repeat network work, validating cache-control behavior and privacy expectations before persisting authenticated or sensitive responses.
- [Type Encodings - NSHipster](https://nshipster.com/type-encodings) — NSHipster · article catalogue
  **Published:** `2013-02-04T00:00:00-08:00`
  **NeKI brief:** Explains Objective-C type-encoding strings as compact runtime metadata for method signatures, properties, and invocation. Use it when bridging reflection or generated interfaces, while treating the legacy syntax as version-sensitive implementation detail.
- [NSURLProtocol - NSHipster](https://nshipster.com/nsurlprotocol) — NSHipster · article catalogue
  **Published:** `2012-11-05T00:00:00-08:00`
  **NeKI brief:** Explains NSURLProtocol as an interception point in Foundation's URL loading system. Useful for controlled request stubbing, custom schemes, or diagnostics where global interception behavior must be bounded carefully.
- [UILocalizedIndexedCollation - NSHipster](https://nshipster.com/uilocalizedindexedcollation) — NSHipster · article catalogue
  **Published:** `2012-10-29T00:00:00-07:00`
  **NeKI brief:** Uses UILocalizedIndexedCollation to build locale-aware section indexes for large table views. Follow it when supporting legacy contact or catalog screens, verifying collation titles, section ordering, and modern list alternatives.
- [An RSS-feed and location-based iOS application | Cocoa with Love](https://www.cocoawithlove.com/2011/06/process-of-writing-ios-application.html) — Cocoa with Love · article catalogue
  **Published:** `2011-06-19`
  **NeKI brief:** An RSS and location-based app is decomposed around network parsing, persistence, and UI updates, showing where asynchronous data flow creates coordination pressure.
- [Classes for fetching and parsing XML or JSON via HTTP | Cocoa with Love](https://www.cocoawithlove.com/2011/05/classes-for-fetching-and-parsing-xml-or.html) — Cocoa with Love · article catalogue
  **Published:** `2011-05-30`
  **NeKI brief:** Reusable fetch-and-parse classes separate transport from XML or JSON decoding, allowing format changes without rewriting request lifecycle and error handling.
- [Using the Mac OS X automounter](https://useyourloaf.com/blog/using-the-mac-os-x-automounter) — Use Your Loaf · article catalogue
  **Published:** `2011-01-24T21:02:00+00:00`
  **NeKI brief:** Uses macOS automounter configuration as development-environment infrastructure context. Network-mounted resources require failure handling and should not be an implicit build dependency.
- [Checking RSS Feeds for New Posts](https://useyourloaf.com/blog/checking-rss-feeds-for-new-posts) — Use Your Loaf · article catalogue
  **Published:** `2010-10-25T19:36:00+00:00`
  **NeKI brief:** Checks RSS feeds for new entries by comparing stable identifiers or timestamps rather than page appearance. Feed polling needs duplicate handling, network failure policy, and respectful refresh intervals.
- [Parsing an RSS Feed using NSXMLParser](https://useyourloaf.com/blog/parsing-an-rss-feed-using-nsxmlparser) — Use Your Loaf · article catalogue
  **Published:** `2010-10-16T00:26:00+00:00`
  **NeKI brief:** Parses RSS XML with NSXMLParser as historical streaming-parser context. XML parsing requires state management and malformed-input handling; modern feeds may be better handled through dedicated decoders.
- [Reading an RSS Feed](https://useyourloaf.com/blog/reading-an-rss-feed) — Use Your Loaf · article catalogue
  **Published:** `2010-10-14T21:09:00+00:00`
  **NeKI brief:** Reads RSS feed data as a network-and-parsing pipeline with caching and failure behavior. Treat remote feed content as untrusted input and preserve a useful offline or empty state.
- [Substituting local data for remote UIWebView requests | Cocoa with Love](https://www.cocoawithlove.com/2010/09/substituting-local-data-for-remote.html) — Cocoa with Love · article catalogue
  **Published:** `2010-09-06`
  **NeKI brief:** Substituting local data for remote UIWebView requests uses URL interception and a local response path, enabling deterministic offline rendering. The pattern helps test web-backed screens without relying on network timing.
- [Reachability Updates](https://useyourloaf.com/blog/reachability-updates) — Use Your Loaf · article catalogue
  **Published:** `2010-08-09T19:26:00+00:00`
  **NeKI brief:** Covers reachability updates for detecting network path changes. Reachability indicates transport conditions, not application-level success, so requests still need error handling and retry policy.
- [Checking network connectivity when displaying iPhone iAds](https://useyourloaf.com/blog/checking-network-connectivity-when-displaying-iphone-iads) — Use Your Loaf · article catalogue
  **Published:** `2010-08-08T20:06:00+00:00`
  **NeKI brief:** React to connectivity changes around an ad banner instead of assuming a previously loaded ad remains actionable. Hide or refresh unavailable content when the app returns from background, so a network loss does not leave a misleading interactive surface.
- [Signing up for iAds](https://useyourloaf.com/blog/signing-up-for-iads) — Use Your Loaf · article catalogue
  **Published:** `2010-07-19T18:59:00+00:00`
  **NeKI brief:** Complete the historical iAd setup by accepting the iAd Network contract in iTunes Connect, enabling the app, and supplying required banking details. Treat this as retired-platform context, not current App Store guidance.
- [Network data requirements on iPhone OS devices | Cocoa with Love](https://www.cocoawithlove.com/2010/04/network-data-requirements-on-iphone-os.html) — Cocoa with Love · article catalogue
  **Published:** `2010-04-07`
  **NeKI brief:** Early iPhone networking constraints include bandwidth, latency, radio energy, and intermittent connectivity. The analysis helps frame request batching and caching as product behavior, not only transport optimization.
- [Streaming MP3/AAC audio again | Cocoa with Love](https://www.cocoawithlove.com/2010/03/streaming-mp3aac-audio-again.html) — Cocoa with Love · article catalogue
  **Published:** `2010-03-29`
  **NeKI brief:** Streaming compressed audio requires buffering, format negotiation, and interruption handling in addition to decoding. Follow it for diagnosing underruns and designing playback that remains responsive on variable networks.
- [Safe, threaded design and inter-thread communication | Cocoa with Love](https://www.cocoawithlove.com/2009/08/safe-threaded-design-and-inter-thread.html) — Cocoa with Love · article catalogue
  **Published:** `2009-08-09`
  **NeKI brief:** Safe threaded design makes message ownership, queue crossing, and handoff timing explicit instead of sharing mutable state. The article provides a diagnostic model for intermittent cross-thread UI and data races.
- [A simple, extensible HTTP server in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/07/simple-extensible-http-server-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2009-07-13`
  **NeKI brief:** A small extensible HTTP server in Cocoa separates parsing, routing, and connection handling behind configurable request logic. Follow it for understanding embedded-server boundaries before exposing application state over a network.
- [Revisiting an old post: Streaming and playing an MP3 stream | Cocoa with Love](https://www.cocoawithlove.com/2009/06/revisiting-old-post-streaming-and.html) — Cocoa with Love · article catalogue
  **Published:** `2009-06-17`
  **NeKI brief:** Revisiting audio streaming exposes how earlier buffering and transport assumptions aged with platform APIs. Follow it when maintaining historical playback code and deciding which compatibility behaviors still warrant support.
- [Serving an NSManagedObjectContext over an NSConnection | Cocoa with Love](https://www.cocoawithlove.com/2009/01/serving-nsmanagedobjectcontext-over.html) — Cocoa with Love · article catalogue
  **Published:** `2009-01-05`
  **NeKI brief:** Serving an NSManagedObjectContext over a boundary exposes why contexts are not thread-safe data services. Follow it when designing a persistence interface that must pass IDs or values instead of live managed objects.
- [Using libxml2 for XML parsing and XPath queries in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2008/10/using-libxml2-for-parsing-and-xpath.html) — Cocoa with Love · article catalogue
  **Published:** `2008-10-31`
  **NeKI brief:** Wrap libxml2's C tree and XPath APIs in Cocoa-oriented objects when NSXMLDocument is unavailable or too heavyweight. The approach preserves tree querying while making ownership, project linking, and libxml2's awkward documentation explicit integration concerns.
- [Streaming and playing an MP3 stream | Cocoa with Love](https://www.cocoawithlove.com/2008/09/streaming-and-playing-live-mp3-stream.html) — Cocoa with Love · article catalogue
  **Published:** `2008-09-28`
  **NeKI brief:** Extend AudioFileStreamExample into a Cocoa app that incrementally receives, parses, queues, and plays remote MP3 data. The implementation documents stream-buffer boundaries and a crash workaround, showing that live audio needs defensive handling beyond a local-file player.
- [A Cocoa application driven by HTTP data | Cocoa with Love](https://www.cocoawithlove.com/2008/09/cocoa-application-driven-by-http-data.html) — Cocoa with Love · article catalogue
  **Published:** `2008-09-20`
  **NeKI brief:** Structure a small Cocoa client as fetch, parse/search, format, then present: each HTTP response stage has one transformation responsibility. Keeping transport, HTML extraction, and UI output separate makes a dashboard-style data application easier to diagnose and replace.
- [mikeash.com: Friday Q&A 2013-06-14: Reachability](https://www.mikeash.com/pyblog/friday-qa-2013-06-14-reachability.html) — Mike Ash · article catalogue
  **NeKI brief:** Reachability indicates whether a network path is currently plausible, not whether a remote request will succeed. The distinction prevents using a reachability callback as a substitute for real request error handling.
- [mikeash.com: Friday Q&A 2009-12-11: A GCD Case Study: Building an HTTP Server](https://www.mikeash.com/pyblog/friday-qa-2009-12-11-a-gcd-case-study-building-an-http-server.html) — Mike Ash · article catalogue
  **NeKI brief:** An event-driven HTTP server can assign connection I/O and parsing to queues, but must retain per-client state, apply backpressure, and serialize each connection’s protocol transitions.
- [Manipulating networking requests and responses with Charles](https://tanaschita.com/tools-charles-proxy-manipulating-network-requests-and-responses) — Tanaschita · article catalogue
  **NeKI brief:** Uses Charles Breakpoints to intercept a matched request or response, edit its payload, and release the modified data to the app. This creates deterministic tests for malformed, missing, or unexpected server values without changing the production endpoint.
- [GraphQL essentials for iOS development](https://tanaschita.com/graphql-essentials-for-ios) — Tanaschita · article catalogue
  **NeKI brief:** GraphQL essentials frames schema, queries and selected fields from an iOS client perspective. The key trade-off is flexible payload shape versus client and server schema coordination, especially as queries become feature-specific.
- [Getting started with Apollo iOS for GraphQL in Swift](https://tanaschita.com/graphql-apollo-for-ios) — Tanaschita · article catalogue
  **NeKI brief:** Apollo iOS generates Swift models and operations from a GraphQL schema and integrates through Swift Package Manager. Follow it to assess generated-code benefits against cache invalidation and schema evolution costs.
- [Developer guide on the App Store Connect API](https://tanaschita.com/20221128-app-store-connect-api-quide) — Tanaschita · article catalogue
  **NeKI brief:** The App Store Connect API automates metadata and release operations through authenticated requests. Follow it to identify which manual portal tasks can become repeatable jobs, while respecting rate limits and role permissions.
- [Understanding different cache policies when working with URLRequest in Swift](https://tanaschita.com/20221031-managing-cache-when-working-with-urlsession-in-ios) — Tanaschita · article catalogue
  **NeKI brief:** URLRequest cache policies control reuse, validation and network freshness. The comparison is useful for choosing per-request behavior rather than applying a global cache assumption to every endpoint.
- [Using URLSession with async/await in Swift](https://tanaschita.com/20221017-using-urlsession-with-async-await) — Tanaschita · article catalogue
  **NeKI brief:** URLSession async APIs turn HTTP responses into structured suspension and typed decoding. The guide is useful for cancellation and error propagation, especially where a view task should not outlive its request context.
- [Quick guide on Proxyman for iOS development](https://tanaschita.com/20220704-quick-guide-on-proxyman) — Tanaschita · article catalogue
  **NeKI brief:** Introduces Proxyman for inspecting iOS network traffic. Use it when HTTPS requests, payloads, and response failures need external debugging evidence.
- [Networking with Combine and SwiftUI](https://peterfriese.dev/blog/2022/swiftui-combine-networking-gettingstarted) — Peter Friese articles · article catalogue
  **NeKI brief:** Connects a Combine URL-loading pipeline to SwiftUI state, covering publisher composition and delivery before rendering remote results. It is historical Combine guidance that helps maintain older code while planning an async/await migration.
- [Error Handling with Combine and SwiftUI](https://peterfriese.dev/blog/2022/swiftui-combine-networking-errorhandling) — Peter Friese articles · article catalogue
  **NeKI brief:** A Combine networking pipeline can map transport, decoding, and domain failures into one UI-facing error model before publishing state to SwiftUI. The workflow keeps retry and presentation decisions out of low-level URLSession callbacks.
- [Optimise your networking layer with Combine](https://peterfriese.dev/blog/2022/swiftui-combine-networking-efficient) — Peter Friese articles · article catalogue
  **NeKI brief:** A Combine networking layer becomes more efficient by sharing work and avoiding duplicate subscriptions for the same request. The article turns request lifetime, replay, and cancellation into explicit pipeline choices rather than accidental publisher behavior.
- [Getting Started with async/await in SwiftUI](https://peterfriese.dev/blog/2021/swiftui-concurrency-essentials-part1) — Peter Friese articles · article catalogue
  **NeKI brief:** Introduces async/await in SwiftUI by moving asynchronous work into task-aware view code and awaiting results directly. It clarifies the lifecycle boundary that cancels work when the associated view disappears.
- [A tiny networking library — Chris Eidhof](https://chris.eidhof.nl/post/tiny-networking-in-swift) — Chris Eidhof · article catalogue
  **NeKI brief:** Derives a small networking layer by composing focused Swift functions instead of adopting a full-featured library. Use it to study lightweight API wrapping and functional composition, while accounting for its older platform context.

## Newsletter and related leads

- [AsyncImage improvements in iOS 27](https://nilcoalescing.com/blog/AsyncImageImprovementsInSwiftUIOnIOS27?ref=createwithswift.com) — Create with Swift · Issue 113 — Article · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2026-06-27T18:12:28.000Z`
  **NeKI brief:** Covers iOS 27 AsyncImage improvements for loading behavior and presentation. Useful when replacing custom image loaders, while checking cache, cancellation, and failure semantics against the deployment target.
- [Announcing The Networking Workgroup](https://www.swift.org/blog/announcing-networking-workgroup) — Those Who Swift · Issue 270 — Article · Topics: Networking · Swift
  **Published:** `2026-06-10`
  **NeKI brief:** Announces Swift's Networking Workgroup and its role in coordinating networking APIs and ecosystem direction. Use it for project discovery and community context, not as a substitute for the concrete package or API documentation used in implementation.
- [A Vision for Networking in Swift](https://github.com/swiftlang/swift-evolution/blob/main/visions/networking.md) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** Swift's networking vision analyzes overlapping responsibilities among URLSession, Network.framework, SwiftNIO, and related clients. Follow it when designing an abstraction that should align with the language ecosystem's planned consolidation.
- [Swift HTTP API Proposal](https://github.com/apple/swift-http-api-proposal) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** The Swift HTTP API proposal explores a common foundation for HTTP types and behavior across client and server libraries. Use it to track interoperable networking direction before committing a new cross-library adapter.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Those Who Swift · Issue 266 — Article · Topics: Architecture · Networking · Performance
  **Published:** `2026-05-13`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Those Who Swift · Issue 266 — Video · Topics: Architecture · Concurrency · Networking
  **Published:** `2026-05-13`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [participate here](https://forums.swift.org/t/prospective-vision-networking) — Fatbobman’s Swift Weekly · Issue 128 — Article · Topics: Developer Community & Business · Networking · Swift
  **Published:** `2026-03-23T12:02:22.360Z`
  **NeKI brief:** The Swift networking vision discussion collects community feedback on simplifying overlapping APIs across URLSession, Network.framework, SwiftNIO, and HTTP clients. Follow it when a networking abstraction decision depends on the ecosystem's future direction.
- [Building a Reusable Network Manager in Swift](https://www.youtube.com/watch?v=zEzIxdA8zLQ) — Those Who Swift · Issue 256 — Video · Topics: Concurrency · Networking · Swift
  **Published:** `2026-03-06`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Mobile Engineers, You’re All Full-Stack](https://newsletter.mobileengineer.io/p/mobile-engineers-youre-all-full-stack?r=g891u&triedRedirect=true) — Those Who Swift · Issue 248 — Article · Topics: Code Quality · Networking · Persistence & Synchronisation
  **Published:** `2026-01-08`
  **NeKI brief:** Examines Mobile Engineers, You’re All Full-Stack, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Reserve Your Spot](https://pragmaconference.com/) — iOS Dev Tools · iOS Dev Tools: Picasso, YoutubeTranscript, Applite — Article · Topics: Developer Community & Business · Networking · Swift
  **Published:** `2025-07-17T18:57:30.320Z`
  **NeKI brief:** Provides the Pragmaconference event hub for talks and community sessions about Apple development. Use it to discover practitioner perspectives and verify session details before relying on a conference presentation.
- [Swift GraphQL Codegen](https://github.com/pm-dev/swift-graphql-codegen) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** Swift GraphQL Codegen generates Swift types and operations from a GraphQL schema, emphasizing correctness and flexible output. Useful for keeping API models synchronized with schema changes without hand-maintaining request and response structs.
- [iPhone Apps 101 - SwiftUI App Development Course](https://paulsolt.teachable.com/p/iphoneapps101?affcode=1123_hyqyixcy) — SwiftLee Weekly · Issue 254 — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Introduces iPhone Apps 101 - SwiftUI App Development Course as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [How to Use URLSession with Async/Await for Network Requests in Swift](https://www.avanderlee.com/concurrency/urlsession-async-await-network-requests-in-swift?ref=createwithswift.com) — Create with Swift · Issue 35 — Article · Topics: Concurrency · Networking · Swift
  **Published:** `2024-11-08T16:05:59.000Z`
  **NeKI brief:** Builds URLSession requests with async/await, HTTP validation, decoding, and typed error handling without third-party networking frameworks. The sequence provides a concrete baseline for deciding where retries and cancellation belong.
- [Apollo iOS](https://github.com/apollographql/apollo-ios) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** Apollo iOS generates typed Swift GraphQL operations from a schema and manages normalized caching, networking, and code generation. Use it when GraphQL responses should be compiler-checked rather than manually decoded from generic JSON.
- [Alamofire](https://github.com/Alamofire/Alamofire) — iOS Dev Tools · iOS Dev Tools: R.swift, Alamofire, SwiftFormat — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2024-09-05T15:57:02.879Z`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
- [Starscream](https://github.com/daltoniam/Starscream) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Hummingbird](https://github.com/hummingbird-project/hummingbird) — Fatbobman’s Swift Weekly · Issue 38 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `2024-07-01T12:02:31.531Z`
  **NeKI brief:** Hummingbird is a modular server framework built on SwiftNIO, offering routing, request handling, and optional server components. Use it when a Swift backend needs a smaller, composable alternative to a more opinionated web framework.
- [AsyncImage in SwiftUI: Loading Images from URLs](https://matteomanferdini.com/swiftui-asyncimage) — SwiftUI Weekly · SwiftUI Weekly - Issue #189 — Article · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2024-06-04T09:49:38.933Z`
  **NeKI brief:** Explains AsyncImage loading phases, placeholders, and failures in SwiftUI. Useful for simple remote-image screens while clarifying when caching or a dedicated loader is still required.
- [Pulse](https://github.com/kean/Pulse) — iOS Dev Tools · iOS Dev Tools: Pow, Maccy, Pulse — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Networking
  **Published:** `2024-04-25T13:41:52.260Z`
  **NeKI brief:** Provides the public source repository for Pulse. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Quicktype](https://quicktype.io/) — iOS Dev Tools · 🔨 Quicktype, RapidAPI, Kintsugi — Article
  **Published:** `2023-12-28T14:58:37.485Z`
  **NeKI brief:** Quicktype converts JSON, schemas, or GraphQL into typed models and serializers for many languages. Use it to bootstrap data-model code from representative payloads, then review naming, optionality, validation, and generated-code ownership before committing it.
- [RapidAPI](https://paw.cloud/) — iOS Dev Tools · 🔨 Quicktype, RapidAPI, Kintsugi — Article · Topics: Networking · Testing
  **Published:** `2023-12-28T14:58:37.485Z`
  **NeKI brief:** Paw is a macOS REST client for composing, testing, and documenting HTTP requests. Use it as historical API-workflow context and compare with maintained tooling before adoption.
- [Introducing Swift HTTP Types](https://www.swift.org/blog/introducing-swift-http-types) — iOS Dev Weekly · Issue 618 — Article · Topics: Networking · Swift
  **Published:** `14th July 2023`
  **NeKI brief:** Explores Introducing Swift HTTP Types, focusing on what an excellent idea this is. i hope this becomes the last ever swift implementation of these core networking types!. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Download Progress With Awaited Network Tasks](https://khanlou.com/2021/10/download-progress-with-awaited-network-tasks) — iOS Dev Weekly · Issue 529 — Article · Topics: Concurrency · Networking
  **Published:** `15th October 2021`
  **NeKI brief:** Explores Download Progress With Awaited Network Tasks, focusing on so, if you no longer need to deal with urlsessiondatatask. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [AFNetworking](https://github.com/AFNetworking/AFNetworking) — iOS Dev Weekly · Issue 528 — Source repository · Topics: Developer Tools · Networking
  **Published:** `8th October 2021`
  **NeKI brief:** Provides the AFNetworking 2.0 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [What thread should your code run on?](https://inessential.com/2021/03/20/how_netnewswire_handles_threading) — iOS Dev Weekly · Issue 500 — Article · Topics: Concurrency · Networking
  **Published:** `26th March 2021`
  **NeKI brief:** Examines What thread should your code run on?, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [follow-up post](https://inessential.com/2021/03/21/benefits_of_netnewswires_threading_model) — iOS Dev Weekly · Issue 500 — Article · Topics: Concurrency · Networking
  **Published:** `26th March 2021`
  **NeKI brief:** Explores the benefits of NetNewsWire's threading model, connecting queue choices with responsive UI and safe data access. Use it to review actor or dispatch boundaries, then verify historical SDK assumptions before production use.
- [URLSession’s Delegate Queue Should Be the Main Queue](https://inessential.com/2021/01/27/urlsession_delegate_main_queue) — iOS Dev Weekly · Issue 493 — Article · Topics: Concurrency · Networking
  **Published:** `5th February 2021`
  **NeKI brief:** Examines URLSession's Delegate Queue Should Be the Main Queue, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [GraphQL Interfaces, Unions, and Fragments In SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9SE5rc2lxTXVQMUkiLCJwb3N0X2lkIjoiMjRiMzQ3YmQtZTA2NS00ZGJmLThjMTAtMzJhZjQ4ZTM1MTZmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6Ijk4ZDliYTZjLWE2NjAtNDdiOC1iZjg1LTQwZmU4ODY2OGViOCIsImlhdCI6MTY3NDA2MjczNi43OTMsImlzcyI6Im9yY2hpZCJ9.teolY23pM5QygzOT8FIwGcxuhQfPjdSLMQLZxLbATNo) — SwiftUI Weekly · SwiftUI Weekly - Issue #29 — Article · Topics: Swift · SwiftUI
  **Published:** `2020-09-28T20:44:06.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [full details here](https://forums.swift.org/t/alamofire-5-one-year-in-the-making-now-in-beta/18865) — iOS Dev Weekly · Issue 444 — Article · Topics: Networking · Swift
  **Published:** `21st February 2020`
  **NeKI brief:** Examines Alamofire 5: One Year in the Making, Now in Beta!, focusing on it struck me as i read this announcement of a major new version of alamofire how it feels like we’re way less dependent…. Use it as a focused research reference for related.
- [Alley, automatic retries for any URLSessionDataTask](https://aplus.rs/2019/alley-automatic-network-retries) — iOS Dev Weekly · Issue 434 — Article · Topics: Networking
  **Published:** `13th December 2019`
  **NeKI brief:** Covers Alley, automatic retries for any URLSessionDataTask, focusing on networking and asynchronous reliability. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Alley](https://github.com/radianttap/Alley) — iOS Dev Weekly · Issue 434 — Source repository · Topics: Developer Tools · Networking
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Alley, focusing on aleksandar vacić talking about his new micro-framework, alley. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using GraphQL in iOS with Swift](https://kristaps.me/graphql-ios-swift) — iOS Dev Weekly · Issue 419 — Article · Topics: Networking · Swift
  **Published:** `30th August 2019`
  **NeKI brief:** Examines Using GraphQL in iOS with Swift, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [simple playground example](https://github.com/timothymiko/swift-networking-examples) — iOS Dev Weekly · Issue 398 — Source repository · Topics: Dependency Injection · Developer Tools · Networking
  **Published:** `5th April 2019`
  **NeKI brief:** Examines simple playground example, focusing on i’ve said this a few times over the years but the reasons for using a third party networking library get fewer and fewer…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Designing a Modern Swift Network Stack](http://mikezornek.com/posts/2019/1/designing-a-modern-swift-network-stack-video-and-slides) — iOS Dev Weekly · Issue 387 — Article · Topics: Graphics, Media & Games · Networking · Swift
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Designing a Modern Swift Network Stack, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Finally, a complete course on advanced iOS architecture](http://matteomanferdini.com/ios-architect) — iOS Dev Weekly · Issue 374 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `19th October 2018`
  **NeKI brief:** Walks through Finally, a complete course on advanced iOS architecture with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [battle tested networking library](https://github.com/twitter/ios-twitter-network-layer) — iOS Dev Weekly · Issue 361 — Source repository · Topics: Developer Community & Business · Networking · Testing
  **Published:** `20th July 2018`
  **NeKI brief:** Examines battle tested networking library, focusing on is this a networking library where every request only returns the first 280 characters of data? 🤣 no, of course it isn’t. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [networking news](https://forums.swift.org/t/niotransportservices-swiftnio-and-network-framework/14567) — iOS Dev Weekly · Issue 361 — Article · Topics: Networking · Swift
  **Published:** `20th July 2018`
  **NeKI brief:** Examines networking news, focusing on oh and, also in networking news this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Apple Networking Feedback Survey](https://forums.developer.apple.com/thread/97662) — iOS Dev Weekly · Issue 342 — Article · Topics: Apple Platform Ecosystem · Networking
  **Published:** `9th March 2018`
  **NeKI brief:** Examines Apple Networking Feedback Survey, focusing on interesting, quinn “the eskimo!” (who you may have met if you’ve ever found yourself in the labs at wwdc) is asking for…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [SwiftNIO - Event-driven network application framework](https://github.com/apple/swift-nio) — iOS Dev Weekly · Issue 341 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd March 2018`
  **NeKI brief:** Examines SwiftNIO, focusing on it’s great to see this major release from the vapor team and it’s encouraging to see that it’s been built on top of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Loading Images in iOS Without Dependencies](https://medium.com/@matthew_healy/loading-images-in-ios-without-dependencies-aff1555dbf1e) — iOS Dev Weekly · Issue 299 — Article · Topics: Dependency Injection · Networking
  **Published:** `5th May 2017`
  **NeKI brief:** Examines Loading Images in iOS Without Dependencies, focusing on matthew liam healy answers the age-old question, “how do i download resources from a server?” i love this article because…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [PMHTTP](https://github.com/postmates/PMHTTP) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `18th August 2016`
  **NeKI brief:** Examines PMHTTP, focusing on kevin ballard with a new networking library written in swift but compatible with objective-c, pmhttp. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [only 11%](https://medium.com/@ryanolsonk/are-the-top-apps-using-swift-42e880e7727f) — iOS Dev Weekly · Issue 259 — Article · Topics: Networking · Objective-C & Cocoa · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Explains Are the Top Apps Using Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Neural Networks in iOS 10 and macOS](https://www.bignerdranch.com/blog/neural-networks-in-ios-10-and-macos) — iOS Dev Weekly · Issue 257 — Article · Topics: Graphics, Media & Games · macOS & AppKit · Networking
  **Published:** `1st July 2016`
  **NeKI brief:** Explores Neural Networks in iOS 10 and macOS in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Networking](https://github.com/3lvis/Networking) — iOS Dev Weekly · Issue 251 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `20th May 2016`
  **NeKI brief:** Examines Networking, focusing on new networking library from elvis nuñez which shipped a 1.0 this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [GitHub repository](https://github.com/joemasilotti/TestingNSURLSession) — iOS Dev Weekly · Issue 242 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `18th March 2016`
  **NeKI brief:** Provides the GitHub repository source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AFNetworking 3](https://github.com/AFNetworking/AFNetworking/releases/tag/3.0.0) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Networking
  **Published:** `11th December 2015`
  **NeKI brief:** Provides the AFNetworking 3 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Migration Guide](https://github.com/AFNetworking/AFNetworking/wiki/AFNetworking-3.0-Migration-Guide) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Networking
  **Published:** `11th December 2015`
  **NeKI brief:** Provides the Migration Guide source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ResponseDetective](https://github.com/netguru/ResponseDetective) — iOS Dev Weekly · Issue 208 — Source repository · Topics: Developer Tools · Networking
  **Published:** `24th July 2015`
  **NeKI brief:** Provides the ResponseDetective source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [associated blog post](https://netguru.co/blog/response-detective-ios-open-source) — iOS Dev Weekly · Issue 208 — Article · Topics: Networking
  **Published:** `24th July 2015`
  **NeKI brief:** Explains associated blog post with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Practical and efficient WatchKit tables with view model diffing](http://radex.io/watch/diffing) — iOS Dev Weekly · Issue 201 — Article · Topics: Networking
  **Published:** `5th June 2015`
  **NeKI brief:** Explains Practical and efficient WatchKit tables with view model diffing with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [this article](http://techblog.thescore.com/2015/05/20/reducing-watchkit-traffic-with-view-models) — iOS Dev Weekly · Issue 201 — Article · Topics: Networking
  **Published:** `5th June 2015`
  **NeKI brief:** Explains Reducing WatchKit Traffic With View Models with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sync](https://github.com/hyperoslo/Sync) — iOS Dev Weekly · Issue 193 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `10th April 2015`
  **NeKI brief:** Provides the Sync source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Easier File Networking with Carrierwave-iOS](https://netguru.co/blog/carrierwave-ios-in-open-source) — iOS Dev Weekly · Issue 190 — Article · Topics: Networking
  **Published:** `20th March 2015`
  **NeKI brief:** Explains Easier File Networking with Carrierwave-iOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Treehouse: Level Up at Swift Development](http://teamtreehouse.com/learn-swift) — iOS Dev Weekly · Issue 189 — Tutorial · Topics: Networking · Swift
  **Published:** `13th March 2015`
  **NeKI brief:** Explains Treehouse Level Up at Swift Development with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Treehouse: Level Up at Swift Development](http://teamtreehouse.com/learn-swift?cid=2672) — iOS Dev Weekly · Issue 184 — Tutorial · Topics: Networking · Swift
  **Published:** `6th February 2015`
  **NeKI brief:** Explains Treehouse Level Up at Swift Development with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Same Tests, Different Class](http://indiestack.com/2015/01/same-tests-different-class) — iOS Dev Weekly · Issue 182 — Article · Topics: Concurrency · Networking · Testing
  **Published:** `23rd January 2015`
  **NeKI brief:** Explains Same Tests Different Class with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [follow up discussion](http://indiestack.com/2015/01/brents-feedback) — iOS Dev Weekly · Issue 182 — Article · Topics: Concurrency · Networking · Testing
  **Published:** `23rd January 2015`
  **NeKI brief:** Explains follow up discussion with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [BigBrother](https://github.com/marcelofabri/BigBrother) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Networking · Objective-C & Cocoa
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the BigBrother source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Treehouse: Code Better iOS Apps](http://teamtreehouse.com/join/ios-development?cid=2672) — iOS Dev Weekly · Issue 159 — Tutorial · Topics: Core Data · Networking · Persistence & Synchronisation
  **Published:** `15th August 2014`
  **NeKI brief:** Explains Treehouse Code Better iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Swift & AFNetworking](http://tech.ustwo.com/2014/06/05/ios-swift-afnetworking-issue) — iOS Dev Weekly · Issue 149 — Article · Topics: Networking · Swift
  **Published:** `6th June 2014`
  **NeKI brief:** Explains Swift AFNetworking with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [check out the follow up post for a better solution to the original problem](http://tech.ustwo.com/2014/06/05/ios-swift-afnetworking-issue-part-ii) — iOS Dev Weekly · Issue 149 — Article · Topics: Networking · Swift
  **Published:** `6th June 2014`
  **NeKI brief:** Explains check out the follow up post for a better solution to the original problem with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because.
- [Haneke](https://github.com/hpique/Haneke) — iOS Dev Weekly · Issue 136 — Source repository · Topics: Developer Tools · Networking · UIKit
  **Published:** `7th March 2014`
  **NeKI brief:** Provides the Haneke source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [NSURLProtocol](http://www.raywenderlich.com/59982/nsurlprotocol-tutorial) — iOS Dev Weekly · Issue 135 — Tutorial · Topics: Foundation & Data Formats · Networking
  **Published:** `28th February 2014`
  **NeKI brief:** Explains NSURLProtocol with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [APIClient](https://github.com/klaaspieter/APIClient) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Dependency Injection · Developer Tools · Navigation & Deep Linking
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the APIClient source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Nocilla](https://github.com/luisobo/Nocilla) — iOS Dev Weekly · Issue 67 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `9th November 2012`
  **NeKI brief:** Provides the Nocilla source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Introducing SocketRocket](http://corner.squareup.com/2012/02/socketrocket-websockets.html) — iOS Dev Weekly · Issue 28 — Article · Topics: Cross-Platform & Web · Networking
  **Published:** `10th February 2012`
  **NeKI brief:** Explains Introducing SocketRocket with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [AFNetworking](https://github.com/gowalla/AFNetworking) — iOS Dev Weekly · Issue 4 — Source repository · Topics: Developer Tools · Networking
  **Published:** `26th August 2011`
  **NeKI brief:** Provides the AFNetworking source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
