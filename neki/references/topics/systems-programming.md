# Systems Programming

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** C/C++, assembly, linking, allocators, memory layout, and systems tooling relevant to Apple platforms.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **70**

## Direct-source reading

- [Cocos2D-X Tutorial for iOS and Android: Getting Started | Kodeco](https://www.kodeco.com/2726-cocos2d-x-tutorial-for-ios-and-android-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Cocos2d-x for sharing 2D game code across iOS and Android. Useful for evaluating engine-level portability against platform-native integration costs.
- [iOS Assembly Tutorial: Understanding ARM | Kodeco](https://www.kodeco.com/2705-ios-assembly-tutorial-understanding-arm) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces ARM calling conventions, examines generated Objective-C messaging, and steps through simple functions at assembly level. Useful when crash traces, performance work, or reverse engineering require reading below Swift and Objective-C source abstractions.
- [Introduction to C++ for iOS Developers: Part 1 | Kodeco](https://www.kodeco.com/2484-introduction-to-c-for-ios-developers-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces C++ classes, namespaces, stack and heap allocation, references, member functions, and inheritance for Apple developers. Useful when bridging to a C++ library requires understanding its ownership and type model instead of treating Objective-C++ as syntax glue.
- [Introduction to C++ for iOS Developers: Part 2 | Kodeco](https://www.kodeco.com/2483-introduction-to-c-for-ios-developers-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Covers virtual dispatch, constructors, destructors, templates, STL containers, shared pointers, and Objective-C++. Useful for evaluating interoperability risks when a Swift or Objective-C app adopts C++ code with its own polymorphism and lifetime rules.
- [Farewell to Portable Assembly - I've Been Running Swift on MCUs for Seven Years](https://fatbobman.com/en/posts/running-swift-on-mcu) — Fatbobman · article catalogue
  **Published:** `2026-01-07T14:12:00.000Z`
  **NeKI brief:** Traces seven years of bringing Swift to microcontrollers through MadMachine, including toolchain evolution and the case for memory-safe embedded code. It supplies historical constraints and practical evidence beyond Apple's newer official MCU support.
- [mikeash.com: Hacking C++ From C](https://www.mikeash.com/pyblog/hacking-c-from-c.html) — Mike Ash · article catalogue
  **NeKI brief:** Calling C++ from C requires an ABI and linkage boundary, commonly handled with extern C wrappers around mangled C++ symbols. The article is a concrete guide to separating language interoperability from ordinary header inclusion.
- [mikeash.com: Friday Q&A 2014-05-23: A Heartbleed-Inspired Paranoid Memory Allocator](https://www.mikeash.com/pyblog/friday-qa-2014-05-23-a-heartbleed-inspired-paranoid-memory-allocator.html) — Mike Ash · article catalogue
  **NeKI brief:** A paranoid allocator adds guard behavior around allocations to expose overreads and misuse near the fault. The technique trades speed and memory for a clearer diagnostic signal during security-sensitive debugging.
- [mikeash.com: Friday Q&A 2014-01-24: Introduction to libclang](https://www.mikeash.com/pyblog/friday-qa-2014-01-24-introduction-to-libclang.html) — Mike Ash · article catalogue
  **NeKI brief:** libclang exposes compiler parsing and AST information for tools without reimplementing C or Objective-C syntax. The API enables source analysis, while versioning and incomplete semantic coverage remain integration concerns.
- [mikeash.com: Friday Q&A 2012-11-09: dyld: Dynamic Linking On OS X](https://www.mikeash.com/pyblog/friday-qa-2012-11-09-dyld-dynamic-linking-on-os-x.html) — Mike Ash · article catalogue
  **NeKI brief:** dyld resolves dynamic-library dependencies, symbol bindings, and load commands before application code runs. The article provides a diagnostic model for launch failures and missing-symbol problems.
- [mikeash.com: Friday Q&A 2011-12-30: Disassembling the Assembly, Part 3: ARM edition](https://www.mikeash.com/pyblog/friday-qa-2011-12-30-disassembling-the-assembly-part-3-arm-edition.html) — Mike Ash · article catalogue
  **NeKI brief:** ARM disassembly requires platform-specific calling and register conventions; interpret instructions in that ABI context before drawing conclusions about argument passing, return values, or memory access.
- [mikeash.com: Friday Q&A 2011-12-23: Disassembling the Assembly, Part 2](https://www.mikeash.com/pyblog/friday-qa-2011-12-23-disassembling-the-assembly-part-2.html) — Mike Ash · article catalogue
  **NeKI brief:** Disassembly becomes useful when machine instructions are related back to data flow and control flow; label blocks, follow values through registers, and separate compiler scaffolding from application logic.
- [mikeash.com: Friday Q&A 2011-12-16: Disassembling the Assembly, Part 1](https://www.mikeash.com/pyblog/friday-qa-2011-12-16-disassembling-the-assembly-part-1.html) — Mike Ash · article catalogue
  **NeKI brief:** Assembly inspection begins by mapping instructions to calling conventions, registers, stack frames, and branches; use it to validate compiler output or crash behavior rather than replacing source-level diagnosis prematurely.
- [mikeash.com: Friday Q&A 2011-06-03: Objective-C Blocks vs. C++0x Lambdas: Fight!](https://www.mikeash.com/pyblog/friday-qa-2011-06-03-objective-c-blocks-vs-c0x-lambdas-fight.html) — Mike Ash · article catalogue
  **NeKI brief:** Blocks and lambdas both capture context, but their ownership, mutability, conversion, and language-integration rules differ; choose the construct from the host ABI and callback lifecycle rather than surface syntax.
- [mikeash.com: Friday Q&A 2010-01-15: Stack and Heap Objects in Objective-C](https://www.mikeash.com/pyblog/friday-qa-2010-01-15-stack-and-heap-objects-in-objective-c.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C values can have stack, heap, static, or tagged representations with different lifetimes; retain or copy based on ownership semantics rather than assuming every object originated from `alloc`.
- [mikeash.com: Friday Q&A 2009-11-06: Linking and Install Names](https://www.mikeash.com/pyblog/friday-qa-2009-11-06-linking-and-install-names.html) — Mike Ash · article catalogue
  **NeKI brief:** A dynamic library’s install name guides runtime lookup; use loader-relative paths intentionally and inspect dependency metadata when a framework builds successfully but fails to load after relocation.
- [mikeash.com: Friday Q&A 2009-03-06: Using the Clang Static Analyzer](https://www.mikeash.com/pyblog/friday-qa-2009-03-06-using-the-clang-static-analyzer.html) — Mike Ash · article catalogue
  **NeKI brief:** Static analysis explores code paths without executing them to expose leaks, null dereferences, and ownership mistakes; treat warnings as hypotheses to investigate, then add the analyzer to a repeatable review workflow.

## Newsletter and related leads

- [tswift: A Lightweight Swift Runtime Built with Rust](https://l.fatbobman.com/w0146-06) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Dependency Injection · Objective-C & Cocoa · Swift
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** The tswift repository experiments with a lightweight Swift environment for the browser backed by Rust. Use it to inspect which language and runtime pieces are required for portable execution, without assuming parity with Apple’s production toolchain.
- [must be buildable using only a C++ host toolchain](https://forums.swift.org/t/dropping-the-requirement-for-c-only-bootstrapping/87739/3) — Fatbobman’s Swift Weekly · Issue 142 — Article · Topics: Swift · Systems Programming
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** Provides the announcement and context for retiring C++-only bootstrapping of the Swift compiler. Use it when tracking the staged migration of parser, AST, type-checker, and mandatory optimization infrastructure.
- [patch-swift](https://github.com/patch-release/patch-swift) — Fatbobman’s Swift Weekly · Issue 142 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** patch-swift explores compiling Swift to WebAssembly and hot-updating views through dynamic replacement and serializable descriptions. Use it to study the toolchain and runtime constraints behind a SwiftUI-like web update model.
- [必须能够仅使用 C++ 宿主工具链构建编译器](https://forums.swift.org/t/dropping-the-requirement-for-c-only-bootstrapping) — Fatbobman’s Swift Weekly · Issue 142 — Article · Topics: Swift · Systems Programming
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** Discusses removing Swift's requirement for a compiler that bootstraps solely from a C++ host toolchain. Follow it for compiler-development implications, including the possibility of moving formerly C++-constrained subsystems into Swift.
- [What’s New In Swift: May 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-may-2026) — Those Who Swift · Issue 270 — Article · Topics: Swift · Systems Programming
  **Published:** `2026-06-10`
  **NeKI brief:** Reviews What’s New In Swift: May 2026 Edition. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Hot Reloading a Bazel-Based iOS App with InjectionNext](https://adincebic.com/2026/05/17/hot-reloading-a-bazelbased-ios.html) — iOS Dev Weekly · Issue 751 — Article · Topics: Cross-Platform & Web · Systems Programming · Testing
  **Published:** `22nd May 2026`
  **NeKI brief:** Presents hot reloading a bazel-based ios app with injectionnext for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Linker](https://linker.appmac.fr/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: Hardware & Devices · Systems Programming
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Linker is a macOS utility for working with links or navigation. Follow its page for concrete URL-handling and menu-bar behavior, while checking supported workflows and current platform compatibility.
- [MachScope](https://github.com/sadopc/machscope) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** MachScope inspects Mach or low-level process information on Apple platforms. Follow its source for concrete diagnostics and system interfaces, while treating private APIs, permissions, and OS-version behavior as constraints.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [lldb-dap](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.lldb-dap) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Article · Topics: Developer Tools · Swift · Systems Programming
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** The lldb-dap extension integrates LLDB’s Debug Adapter Protocol with Visual Studio Code. Follow it for concrete debugger and editor integration, while checking compiler, extension, and platform setup requirements.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 99 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-25T12:03:32.117Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [Assembler for Swift Developers — Part 2](https://arturgruchala.com/assembler-for-swift-developers-part-2) — Those Who Swift · Issue 227 — Article · Topics: Swift · Systems Programming
  **Published:** `2025-08-13`
  **NeKI brief:** Introduces assembler concepts for Swift developers in a second practical installment. Useful for relating low-level instructions to compiler output and performance investigation without treating assembly as a substitute for measurement.
- [Assembler for Swift Developers](https://arturgruchala.com/assembler-for-swift-developers) — Those Who Swift · Issue 225 — Article · Topics: Swift · Systems Programming
  **Published:** `2025-08-07`
  **NeKI brief:** This article covers assembly-language concepts explained for Swift developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Swift and C++ interoperability in practice](https://arturgruchala.com/swift-and-c-interoperability-in-practice) — iOS Dev Weekly · Issue 718 — Article · Topics: Developer Community & Business · Personal Essays · Swift
  **Published:** `18th July 2025`
  **NeKI brief:** Examines Swift’s new C++ interoperability is a game-changer, letting you tap into mature C++ libraries from Swift’s safe, expressive syntax. In this post, I’ll guide you through the languag. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AcceptedSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — SwiftLee Weekly · Issue 256 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **Published:** `2025-01-28T15:11:34.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [platform channels](https://docs.flutter.dev/platform-integration/platform-channels) — iOS Dev Weekly · Issue 691 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `13th December 2024`
  **NeKI brief:** “One thing I really want to drive home is that this is not rocket science. I’ve not done anything half as clever as the Swift team has with C++ and Java interoperability. FlutterSwift is just a few thousand lines of structured concurrency glue around Flutter…
- [Getting started with Embedded Swift](https://blog.supereasyapps.com/embedded-swift-tutorial-getting-started-everything-you-need-to-know) — iOS Dev Weekly · Issue 673 — Tutorial · Topics: Swift · Systems Programming
  **Published:** `9th August 2024`
  **NeKI brief:** Interested in Embedded Swift? Paul Solt is, too, and he decided to record the first hour of his experiments with it. Why would you use C or C++ for this if you didn’t have to!
- [the name CellLVM or what it does](https://belkadan.com/blog/2023/12/CellLVM) — iOS Dev Weekly · Issue 642 — Article
  **Published:** `5th January 2024`
  **NeKI brief:** I can’t decide what I like more between the name CellLVM or what it does! ❤️
- [Maintaining Seamless Compatibility with Apple and LLVM Compiler Technology](https://www.guardsquare.com/blog/maintaining-seamless-compatibility-with-apple-llvm-compiler-technology) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: Performance · Systems Programming
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** Discusses maintaining compatibility with Apple's LLVM-based compiler technology across toolchain changes. Follow it when assessing compiler-sensitive build or protection tooling and planning validation across Xcode, SDK, and optimization updates.
- [Read the blog post to see what's new.](https://www.swift.org/blog/swift-5.9-released?ref=ioscodereview.com) — iOS Code Review · Issue 55 — Article · Topics: Macros & Metaprogramming · Swift · Systems Programming
  **Published:** `2023-09-19T13:32:36.000Z`
  **NeKI brief:** Summarises Read the blog post to see what's new for Macros & Metaprogramming and Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Introducing a Memory-Safe Successor Language in Large C++ Code Bases](https://www.youtube.com/watch?v=lgivCGdmFrw) — iOS Dev Weekly · Issue 626 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `8th September 2023`
  **NeKI brief:** Explains a memory-safe successor language in the context of large C++ codebases and migration concerns. Useful for comparing ownership and safety strategies, while keeping its language-specific claims separate from Swift guidance.
- [🤯 Using the -why_load linker flag to reduce app size](https://asifmohd.github.io/ios/2023/03/30/reducing-ios-app-size-using-linker.html) — iOS CI Newsletter · Issue 13 — Article · Topics: Cross-Platform & Web · Developer Tools · Systems Programming
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Examines Using the -why_load linker flag to reduce app size in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Faster Apple Builds with the lld Linker](https://eisel.me/lld) — iOS Dev Weekly · Issue 591 — Article · Topics: Systems Programming
  **Published:** `6th January 2023`
  **NeKI brief:** Discusses Faster Apple Builds with the lld Linker, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Find Problematic Auto Layout Constraints](https://xcode.tips/find-problematic-constraint) — iOS Dev Weekly · Issue 591 — Article · Topics: Systems Programming · Xcode
  **Published:** `6th January 2023`
  **NeKI brief:** If you’re anything like me, you probably don’t spend much time thinking about linkers anymore, but that doesn’t mean there’s no innovation happening in this essential part of every build! I enjoyed reading Michael Eisel’s words about lld as a nice change of…
- [Code signing and XCFrameworks](https://mtldoc.com/swift/2022/12/23/xcframework-code-signing) — iOS CI Newsletter · Issue 6 — Article · Topics: App Distribution & Store Operations · Swift · Systems Programming
  **Published:** `2023-01-01T00:00:00.000Z`
  **NeKI brief:** Examines Code signing and XCFrameworks in the context of App Distribution & Store Operations and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [listed community projects](https://opensource.apple.com/projects) — iOS Dev Weekly · Issue 537 — Article · Topics: Developer Community & Business · Systems Programming
  **Published:** `10th December 2021`
  **NeKI brief:** This week saw Apple re-launch their open-source site, highlighting how they’re involved with various projects. I had no idea they were helping with any of the listed community projects apart from LLVM/Clang. I’d love to see them expand on how they’re…
- [this recent announcement](https://www.blender.org/press/apple-joins-blender-development-fund) — iOS Dev Weekly · Issue 537 — Article · Topics: Developer Community & Business · Systems Programming
  **Published:** `10th December 2021`
  **NeKI brief:** This week saw Apple re-launch their open-source site, highlighting how they’re involved with various projects. I had no idea they were helping with any of the listed community projects apart from LLVM/Clang. I’d love to see them expand on how they’re…
- [The state of Swift for WebAssembly in 2020 (and earlier)](https://desiatov.com/swift-webassembly-2020) — iOS Dev Weekly · Issue 474 — Article · Topics: Swift · Systems Programming
  **Published:** `18th September 2020`
  **NeKI brief:** Covers The state of Swift for WebAssembly in 2020 (and earlier), focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [zld](https://github.com/michaeleisel/zld) — iOS Dev Weekly · Issue 460 — Source repository · Topics: Developer Tools · Systems Programming
  **Published:** `12th June 2020`
  **NeKI brief:** Presents zld, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Daniel Dunbar’s thoughts on swift-llbuild2](https://forums.swift.org/t/llbuild2/36896) — iOS Dev Weekly · Issue 460 — Article · Topics: Swift · Systems Programming
  **Published:** `12th June 2020`
  **NeKI brief:** Examines I first came across zld a few weeks ago but seeing Peter Steinberger show the potential improvements to a real-world project convinced me I should link it here. Honestly, I would only ever consider replacing the default Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Kotlin/Objective-C Interoperability](https://blog.jetbrains.com/kotlin/2017/11/kotlinnative-v0-4-released-objective-c-interop-webassembly-and-more) — iOS Dev Weekly · Issue 328 — Article · Topics: Objective-C & Cocoa · Systems Programming · Testing
  **Published:** `24th November 2017`
  **NeKI brief:** Examines We’re happy to announce the release of Kotlin/Native v0.4, KotlinConf 2017 edition! This release adds support for accessing Objective-C APIs on iOS and macOS, WebAssembly target pl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Refactor Swift, Objective-C and C++ with AppCode](https://www.jetbrains.com/objc/whatsnew) — iOS Dev Weekly · Issue 288 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** Explores Refactor Swift, Objective-C and C++ with AppCode in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Unsafe Swift: Using Pointers And Interacting With C](https://www.raywenderlich.com/148569/unsafe-swift) — iOS Dev Weekly · Issue 283 — Article · Topics: Swift · Systems Programming
  **Published:** `13th January 2017`
  **NeKI brief:** The tutorial explains unsafe Swift pointers and interoperability with C, including the trade-offs and APIs involved in low-level memory access.
- [Swifty Responder Chain](http://roopc.net/posts/2016/swifty-responder-chain) — iOS Dev Weekly · Issue 254 — Article · Topics: Swift · Systems Programming
  **Published:** `10th June 2016`
  **NeKI brief:** Following up on all the talk recently about dynamic language features and Swift, this post by Roopesh Chander explores how to implement a responder chain using Swift protocols. He’s come up with an interesting implementation, and has a couple of suggestions…
- [Swifty Objective-C](https://pspdfkit.com/blog/2016/swifty-objective-c) — iOS Dev Weekly · Issue 253 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `3rd June 2016`
  **NeKI brief:** Explores Swifty Objective-C in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Code Coverage From the Command Line With Clang](https://alastairs-place.net/blog/2016/05/20/code-coverage-from-the-command-line-with-clang) — iOS Dev Weekly · Issue 252 — Article · Topics: Developer Tools · Systems Programming
  **Published:** `27th May 2016`
  **NeKI brief:** Examines Having searched the Internet several times to find out how to get coverage information out of clang, I ended up feeling rather confused. I’m sure I’m …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [LLVM Developers’ Meeting Videos](https://www.youtube.com/playlist?list=PL_R5A0lGi1AA4Lv2bBFSwhgDaHvvpVU21) — iOS Dev Weekly · Issue 224 — Video · Topics: Graphics, Media & Games · Swift · Systems Programming
  **Published:** `13th November 2015`
  **NeKI brief:** Videos from the recent LLVM Developers’ Meeting. These are all predictably low level talks, but there’s sure to be something in here to catch your interest if you’re interested in the Swift compiler. I must admit, this goes way over my head though, I swim in…
- [Bringing Clang to Windows](http://blogs.msdn.com/b/vcblog/archive/2015/05/01/bringing-clang-to-windows.aspx) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Examines As you may know, Visual Studio now supports building Android and iOS applications using Clang. We realize the need of our users to write cross-platform. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [video from the Build conference](http://channel9.msdn.com/events/Build/2015/3-610) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Interesting post by the Microsoft Visual C++ team on the process of compiling iOS and Android code to Windows via Clang. It’s also worth checking out this video from the Build conference if you want to learn more. Think back a few years, would you have…
- [Objective-C’s Designated Secret](http://timekl.com/blog/2014/12/09/objective-cs-designated-secret) — iOS Dev Weekly · Issue 176 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Objective-C’s Designated Secret with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Using Static Analysis And Clang To Find Heartbleed](http://blog.trailofbits.com/2014/04/27/using-static-analysis-and-clang-to-find-heartbleed) — iOS Dev Weekly · Issue 144 — Article · Topics: Developer Career & Practice · Systems Programming
  **Published:** `2nd May 2014`
  **NeKI brief:** Explains Using Static Analysis And Clang To Find Heartbleed with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [2013 LLVM Developers’ Meeting](http://llvm.org/devmtg/2013-11) — iOS Dev Weekly · Issue 125 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `20th December 2013`
  **NeKI brief:** Examines The videos and slides have been published from the most recent LLVM compiler conference which was held in November. Naturally this is all very low level content but is always worth a look even if compilers aren’t necessa Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Understanding ARM](http://www.raywenderlich.com/37181/ios-assembly-tutorial) — iOS Dev Weekly · Issue 98 — Tutorial · Topics: Systems Programming
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Understanding ARM with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple’s new Objective-C to Javascript Bridge](http://www.steamclock.com/blog/2013/05/apple-objective-c-javascript-bridge) — iOS Dev Weekly · Issue 94 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `17th May 2013`
  **NeKI brief:** Explains Apple’s new Objective-C to Javascript Bridge with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [2013 European LLVM Conference](http://llvm.org/devmtg/2013-04) — iOS Dev Weekly · Issue 93 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Systems Programming
  **Published:** `10th May 2013`
  **NeKI brief:** Examines The LLVM Compiler Infrastructure Project. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [All the C You Need to Know](https://itunes.apple.com/us/book/all-the-c-you-need-to-know/id581989356?mt=11) — iOS Dev Weekly · Issue 77 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `18th January 2013`
  **NeKI brief:** I think many people who started writing Objective-C without previously having written much or any C have a slight fear of the C language. Bill Dudney has decided to try and fix this problem by writing this book. If you have been secretly afraid of the C in…
- [Release the Kraken](http://kearwood.com/content/ios-development-release-kraken) — iOS Dev Weekly · Issue 54 — Article · Topics: Systems Programming
  **Published:** `10th August 2012`
  **NeKI brief:** Explains Release the Kraken with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C, Unversioned](http://mjtsai.com/blog/2012/03/12/objective-c-unversioned) — iOS Dev Weekly · Issue 33 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `16th March 2012`
  **NeKI brief:** I guess we all knew this deep down but Chris Lattner makes it official with a post to the Objective-C language mailing list. No more version numbers for the Objective-C language.
- [LLVM 4.0 Compiler](http://cocoaheads.tumblr.com/post/18002019974/llvm-4-0-compiler) — iOS Dev Weekly · Issue 30 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `24th February 2012`
  **NeKI brief:** Examines Such tasty treats coming down the line with LLVM 4.0 which was included with the Mountain Lion developer preview release. Thanks to whoever runs this tumblr for breaking the NDA so I can link to this. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [LLVM 3.0 Release Notes](http://llvm.org/releases/3.0/docs/ReleaseNotes.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Systems Programming · Xcode
  **Published:** `9th December 2011`
  **NeKI brief:** Explains LLVM 3.0 Release Notes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ARC](http://clang.llvm.org/docs/AutomaticReferenceCounting.html) — iOS Dev Weekly · Issue 2 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `12th August 2011`
  **NeKI brief:** This Clang specification defines the semantics and compiler rules of Objective-C Automatic Reference Counting. It is the authoritative technical reference for understanding ownership qualifiers, retain and release insertion, and ARC edge cases in mixed-language Apple code.
- [MiniSwift Studio](https://go.peterfriese.dev/miniswift-studio?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: Swift · Systems Programming
  **NeKI brief:** Provides a browser-based Swift environment with live SwiftUI previews, breakpoints, console output, and a SwiftData inspector. Follow it when evaluating zero-install teaching or prototyping workflows and their differences from the real Xcode toolchain.
- [Google Workspace CLI: One tool for everything](https://github.com/googleworkspace/cli) — Not only Swift · Issue 95 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **NeKI brief:** This source repository covers a unified Google Workspace command-line interface with agent skills. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
