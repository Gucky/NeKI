# Systems Programming

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** C/C++, assembly, linking, allocators, memory layout, and systems tooling relevant to Apple platforms.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **35**

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

- [must be buildable using only a C++ host toolchain](https://forums.swift.org/t/dropping-the-requirement-for-c-only-bootstrapping/87739/3) — Fatbobman’s Swift Weekly · Issue 142 — Article · Topics: Swift · Systems Programming
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** Provides the announcement and context for retiring C++-only bootstrapping of the Swift compiler. Use it when tracking the staged migration of parser, AST, type-checker, and mandatory optimization infrastructure.
- [patch-swift](https://github.com/patch-release/patch-swift) — Fatbobman’s Swift Weekly · Issue 142 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** patch-swift explores compiling Swift to WebAssembly and hot-updating views through dynamic replacement and serializable descriptions. Use it to study the toolchain and runtime constraints behind a SwiftUI-like web update model.
- [必须能够仅使用 C++ 宿主工具链构建编译器](https://forums.swift.org/t/dropping-the-requirement-for-c-only-bootstrapping) — Fatbobman’s Swift Weekly · Issue 142 — Article · Topics: Swift · Systems Programming
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** Discusses removing Swift's requirement for a compiler that bootstraps solely from a C++ host toolchain. Follow it for compiler-development implications, including the possibility of moving formerly C++-constrained subsystems into Swift.
- [Hot Reloading a Bazel-Based iOS App with InjectionNext](https://adincebic.com/2026/05/17/hot-reloading-a-bazelbased-ios.html) — iOS Dev Weekly · Issue 751 — Article · Topics: Cross-Platform & Web · Systems Programming · Testing
  **Published:** `22nd May 2026`
  **NeKI brief:** Presents hot reloading a bazel-based ios app with injectionnext for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 99 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-25T12:03:32.117Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [Assembler for Swift Developers](https://arturgruchala.com/assembler-for-swift-developers) — Those Who Swift · Issue 225 — Article · Topics: Swift · Systems Programming
  **Published:** `2025-08-07`
  **NeKI brief:** This article covers assembly-language concepts explained for Swift developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [AcceptedSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — SwiftLee Weekly · Issue 256 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **Published:** `2025-01-28T15:11:34.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Maintaining Seamless Compatibility with Apple and LLVM Compiler Technology](https://www.guardsquare.com/blog/maintaining-seamless-compatibility-with-apple-llvm-compiler-technology) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: Performance · Systems Programming
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** Discusses maintaining compatibility with Apple's LLVM-based compiler technology across toolchain changes. Follow it when assessing compiler-sensitive build or protection tooling and planning validation across Xcode, SDK, and optimization updates.
- [The state of Swift for WebAssembly in 2020 (and earlier)](https://desiatov.com/swift-webassembly-2020) — iOS Dev Weekly · Issue 474 — Article · Topics: Swift · Systems Programming
  **Published:** `18th September 2020`
  **NeKI brief:** Covers The state of Swift for WebAssembly in 2020 (and earlier), focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Refactor Swift, Objective-C and C++ with AppCode](https://www.jetbrains.com/objc/whatsnew) — iOS Dev Weekly · Issue 288 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** Explores Refactor Swift, Objective-C and C++ with AppCode in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swifty Objective-C](https://pspdfkit.com/blog/2016/swifty-objective-c) — iOS Dev Weekly · Issue 253 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `3rd June 2016`
  **NeKI brief:** Explores Swifty Objective-C in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Objective-C’s Designated Secret](http://timekl.com/blog/2014/12/09/objective-cs-designated-secret) — iOS Dev Weekly · Issue 176 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Objective-C’s Designated Secret with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Using Static Analysis And Clang To Find Heartbleed](http://blog.trailofbits.com/2014/04/27/using-static-analysis-and-clang-to-find-heartbleed) — iOS Dev Weekly · Issue 144 — Article · Topics: Developer Career & Practice · Systems Programming
  **Published:** `2nd May 2014`
  **NeKI brief:** Explains Using Static Analysis And Clang To Find Heartbleed with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Understanding ARM](http://www.raywenderlich.com/37181/ios-assembly-tutorial) — iOS Dev Weekly · Issue 98 — Tutorial · Topics: Systems Programming
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Understanding ARM with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple’s new Objective-C to Javascript Bridge](http://www.steamclock.com/blog/2013/05/apple-objective-c-javascript-bridge) — iOS Dev Weekly · Issue 94 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `17th May 2013`
  **NeKI brief:** Explains Apple’s new Objective-C to Javascript Bridge with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Release the Kraken](http://kearwood.com/content/ios-development-release-kraken) — iOS Dev Weekly · Issue 54 — Article · Topics: Systems Programming
  **Published:** `10th August 2012`
  **NeKI brief:** Explains Release the Kraken with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLVM 3.0 Release Notes](http://llvm.org/releases/3.0/docs/ReleaseNotes.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Systems Programming · Xcode
  **Published:** `9th December 2011`
  **NeKI brief:** Explains LLVM 3.0 Release Notes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Google Workspace CLI: One tool for everything](https://github.com/googleworkspace/cli) — Not only Swift · Issue 95 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **NeKI brief:** This source repository covers a unified Google Workspace command-line interface with agent skills. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
