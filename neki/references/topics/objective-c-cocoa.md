# Objective-C & Cocoa

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Objective-C language/runtime, Cocoa and Foundation-era APIs, and historical Mac/iOS implementation techniques.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **1137**

## Direct-source reading

- [Elasticsearch in Vapor: Getting Started | Kodeco](https://www.kodeco.com/9813028-elasticsearch-in-vapor-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Vapor example connects a server to a locally Dockerized Elasticsearch instance and indexes recipe documents, useful for understanding the boundary between request handling and search storage.
- [NSCoding Tutorial for iOS: How to Permanently Save App Data | Kodeco](https://www.kodeco.com/6733-nscoding-tutorial-for-ios-how-to-permanently-save-app-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements NSCoding and NSSecureCoding for disk persistence, including object initialization, deletion, and image storage. Useful for understanding archive-based persistence boundaries in legacy code before deciding whether a modern Codable or database migration is warranted.
- [iOS 10: Taking Photos | Kodeco](https://www.kodeco.com/4994-ios-10-taking-photos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a photo capture flow around the iOS camera APIs. Useful for identifying the distinct responsibilities of session configuration, capture requests, output processing, and UI state in a camera screen.
- [iOS 10: Measurements & Units | Kodeco](https://www.kodeco.com/4982-ios-10-measurements-units) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Foundation measurement and unit types to represent values with conversion semantics. Useful for avoiding scattered conversion constants when a feature accepts, stores, or displays quantities in more than one unit system.
- [iOS 10: Custom Units | Kodeco](https://www.kodeco.com/4966-ios-10-custom-units) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Defines custom units and conversions with Foundation's measurement APIs. Useful when a domain quantity is not represented by the built-in unit catalog but still needs safe conversion and locale-aware display behavior.
- [iOS 10: Measurement Formatter | Kodeco](https://www.kodeco.com/4953-ios-10-measurement-formatter) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Formats Foundation measurement values for display in the user's locale and preferred units. Useful for keeping conversion and presentation separate so domain values remain stable while UI conventions vary by region.
- [iOS 10: Introducing DateInterval | Kodeco](https://www.kodeco.com/4951-ios-10-introducing-dateinterval) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses DateInterval to model a bounded period and reason about containment or overlap. Useful for replacing scattered start/end comparisons with a value that makes temporal range logic explicit.
- [NSCoding Tutorial for iOS: How To Save Your App Data | Kodeco](https://www.kodeco.com/3111-nscoding-tutorial-for-ios-how-to-save-your-app-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Archives a model with NSCoding, restores it from disk, and persists associated images. Useful for maintaining an older UIKit codebase where file-backed object archives still define its data format and must be understood before migration.
- [Beginning ARC in iOS 5 Tutorial Part 2 | Kodeco](https://www.kodeco.com/2991-beginning-arc-in-ios-5-tutorial-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This ARC continuation focuses on weak and unowned references in practical object graphs. Follow it for migration debugging, but verify every unowned assumption because modern concurrency and asynchronous callbacks widen lifetime gaps.
- [Objectively Speaking: A Crash Course in Objective-C for iOS 6 | Kodeco](https://www.kodeco.com/2829-objectively-speaking-a-crash-course-in-objective-c-for-ios-6) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds an Objective-C quiz with outlets, actions, property-list data, predicates, strings, arrays, and segues. Useful when maintaining legacy source that combines language constructs with Interface Builder wiring and simple data-driven UI logic.
- [Objectively Speaking 2: A Crash Course in Objective-C for iOS 6 | Kodeco](https://www.kodeco.com/2735-objectively-speaking-2-a-crash-course-in-objective-c-for-ios-6) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds an Objective-C quiz UI with properties, actions, property-list data, iteration, feedback, and segues. Useful for decoding the language and UIKit patterns common in older projects before attempting a piecemeal Swift modernization.
- [What’s New in Objective-C and Foundation in iOS 7 | Kodeco](https://www.kodeco.com/2647-what-s-new-in-objective-c-and-foundation-in-ios-7) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Reviews Objective-C and Foundation changes around iOS 7. Useful historical context when maintaining older platform code and migration assumptions.
- [CocoaPods Tech Talk Video | Kodeco](https://www.kodeco.com/2549-cocoapods-tech-talk-video) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains practical CocoaPods usage and common dependency-management questions. Useful historical context for repositories that still use Pods and need to separate package integration from application code.
- [Units & Measurement in iOS | Kodeco](https://www.kodeco.com/20656790-units-measurement-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Foundation Measurement and Unit types to model physical quantities and conversions safely. Follow it when displaying user-entered values across units, avoiding ambiguous numeric fields and hand-written conversion factors.
- [Vision Framework Tutorial for iOS: Scanning Barcodes | Kodeco](https://www.kodeco.com/12663654-vision-framework-tutorial-for-ios-scanning-barcodes) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a camera-based barcode scanner with Vision and routes recognized payloads into URL handling. The workflow highlights separating capture-session lifecycle, request processing, and user confirmation before opening data supplied by a code.
- [Why Does Passing NSManagedObjectContext Across Isolation Domains No Longer Error in Swift 6.2? The Real Change Isn't in the Compiler](https://fatbobman.com/en/posts/sendable-nsmanagedobjectcontext) — Fatbobman · article catalogue
  **Published:** `2026-03-04T14:00:00.000Z`
  **NeKI brief:** Explains why NSManagedObjectContext crossing isolation domains no longer errors in Swift 6.2. Use it to review Core Data concurrency assumptions and verify the behavior against the active compiler and SDK.
- [op run - NSHipster](https://nshipster.com/1password-cli) — NSHipster · article catalogue
  **Published:** `2025-01-01T00:00:00-08:00`
  **NeKI brief:** The 1Password CLI can materialize secrets at command time, keeping credentials out of committed .env files. The useful workflow is wiring `op run` into development scripts while preserving reproducible configuration for teammates and CI.
- [Default property attributes with ARC](https://useyourloaf.com/blog/default-property-attributes-with-arc) — Use Your Loaf · article catalogue
  **Published:** `2015-05-04T15:04:19+01:00`
  **NeKI brief:** Explains ARC property ownership defaults in Objective-C and why explicit weak, strong, or copy semantics still matter. Property attributes define lifetime behavior, not merely syntax.
- [NSUndoManager - NSHipster](https://nshipster.com/nsundomanager) — NSHipster · article catalogue
  **Published:** `2014-12-15T00:00:00-08:00`
  **NeKI brief:** UndoManager groups reversible user operations into commands that can be undone and redone. Use explicit grouping around meaningful edits, defining inverse operations carefully so undo restores a valid model state.
- [MKGeodesicPolyline - NSHipster](https://nshipster.com/mkgeodesicpolyline) — NSHipster · article catalogue
  **Published:** `2014-04-28T00:00:00-07:00`
  **NeKI brief:** MKGeodesicPolyline draws a curved route that follows the earth's surface between coordinates. Use it for long-distance map visualization, choosing a different overlay when users need road routing or locally accurate paths.
- [Effective Objective-C 2.0](https://useyourloaf.com/blog/effective-objective-c-2-dot-0) — Use Your Loaf · article catalogue
  **Published:** `2014-03-19T21:27:00+00:00`
  **NeKI brief:** Routes to Objective-C best-practice material as historical interoperability context. Concepts such as ownership and API design remain relevant, but language and framework guidance should be verified currently.
- [How I Learned to Stop Worrying and Love Cocoa Auto Layout – Ole Begemann](https://oleb.net/blog/2014/03/how-i-learned-to-stop-worrying-and-love-auto-layout) — Ole Begemann · article catalogue
  **Published:** `2014-03-03T19:10:00Z`
  **NeKI brief:** Shows where Auto Layout can coexist with manual frame calculation, using constraints for adaptable structure while retaining explicit layout code where constraint systems would add unnecessary complexity.
- [An Observation on Objective-C | Dave DeLong](https://davedelong.com/blog/2013/08/16/an-observation-on-objective-c) — Dave DeLong · article catalogue
  **Published:** `2013-08-16T00:00:00+00:00`
  **NeKI brief:** This archived Objective-C observation preserves historical language context. Use it only when interpreting legacy Cocoa code, validating any interoperability or runtime conclusion against the current Objective-C and Swift toolchains.
- [MKLocalSearch - NSHipster](https://nshipster.com/mklocalsearch) — NSHipster · article catalogue
  **Published:** `2013-04-29T00:00:00-07:00`
  **NeKI brief:** MKLocalSearch queries MapKit's local place index for user-entered search terms. Use debouncing, cancellation and result presentation that distinguishes search suggestions from authoritative navigation or address validation.
- [10 Things You Need to Know About Cocoa Auto Layout – Ole Begemann](https://oleb.net/blog/2013/03/things-you-need-to-know-about-cocoa-autolayout) — Ole Begemann · article catalogue
  **Published:** `2013-03-31T19:08:00Z`
  **NeKI brief:** Distills Auto Layout into constraint sufficiency, priorities, and intrinsic content size, helping developers reason about ambiguous or unsatisfiable layouts instead of treating constraints as fixed frame assignments.
- [Tutorial: How to Sort and Group UITableView by Date – Ole Begemann](https://oleb.net/blog/2011/12/tutorial-how-to-sort-and-group-uitableview-by-date) — Ole Begemann · article catalogue
  **Published:** `2011-12-02T17:40:00Z`
  **NeKI brief:** Groups table-view records by calendar date after normalizing timestamps with an explicit calendar and time zone, separating sort keys from localized section-title presentation.
- [Date and Time Handling in Cocoa Cheat Sheet – Ole Begemann](https://oleb.net/blog/2011/11/date-and-time-in-cocoa-cheat-sheet) — Ole Begemann · article catalogue
  **Published:** `2011-11-23T18:00:00Z`
  **NeKI brief:** Collects Cocoa date and time API distinctions, useful for checking formatter, calendar, time-zone, and locale responsibilities before treating a Date as a user-facing value.
- [Working with Date and Time in Cocoa (Part 2) – Ole Begemann](https://oleb.net/blog/2011/11/working-with-date-and-time-in-cocoa-part-2) — Ole Begemann · article catalogue
  **Published:** `2011-11-22T21:58:00Z`
  **NeKI brief:** Continues Cocoa date handling with calendar calculations and formatter choices, stressing that human calendar concepts require explicit locale, calendar, and time-zone context.
- [Dealing with Failure in Objective-C initializers](https://useyourloaf.com/blog/dealing-with-failure-in-objective-c-initializers) — Use Your Loaf · article catalogue
  **Published:** `2011-05-17T21:41:00+00:00`
  **NeKI brief:** Models initializer failure in Objective-C so partially constructed objects do not escape. Translate equivalent Swift initialization rules into explicit validation and clear ownership of cleanup.
- [Faking Instance Variables in Objective-C Categories With Associative References – Ole Begemann](https://oleb.net/blog/2011/05/faking-ivars-in-objc-categories-with-associative-references) — Ole Begemann · article catalogue
  **Published:** `2011-05-15T20:55:00Z`
  **NeKI brief:** Shows how Objective-C associated objects can back category properties without subclassing or global maps. Use it when extending legacy objects, while keeping ownership policy, key uniqueness, and the inability to add real ivars explicit.
- [Using Cocoa to Convert Images From RGB to CMYK – Ole Begemann](https://oleb.net/blog/2011/05/using-cocoa-to-convert-images-from-rgb-to-cmyk) — Ole Begemann · article catalogue
  **Published:** `2011-05-12T20:02:00Z`
  **NeKI brief:** Converts RGB images to CMYK by loading bitmap representations, changing color space, and writing output files while enumerating inputs concurrently. Useful for macOS batch utilities, though current color-management and ImageIO APIs should be verified.
- [Private ivars](https://useyourloaf.com/blog/private-ivars) — Use Your Loaf · article catalogue
  **Published:** `2011-04-22T16:25:00+00:00`
  **NeKI brief:** Explains private ivar usage in Objective-C as historical encapsulation context. Prefer property and access-control boundaries that express ownership clearly, without exposing storage details unnecessarily.
- [Objective-C Fundamentals](https://useyourloaf.com/blog/objective-c-fundamentals) — Use Your Loaf · article catalogue
  **Published:** `2011-04-09T22:36:00+00:00`
  **NeKI brief:** Introduces Objective-C fundamentals useful for maintaining interoperable or legacy iOS code. Concepts such as messaging and ownership explain behavior, but modern Swift-first APIs may be preferable for new work.
- [Understanding your (Objective-C) self](https://useyourloaf.com/blog/understanding-your-objective-c-self) — Use Your Loaf · article catalogue
  **Published:** `2011-02-08T21:46:00+00:00`
  **NeKI brief:** Explains Objective-C self as the current receiver and its role in method dispatch and property access. Understanding receiver semantics helps when maintaining legacy interop code and avoiding accidental shadowing.
- [My Wish: Syntax Additions to Objective-C for Object Literals – Ole Begemann](https://oleb.net/blog/2010/12/syntax-additions-for-object-literals-to-objective-c) — Ole Begemann · article catalogue
  **Published:** `2010-12-22T11:07:00Z`
  **NeKI brief:** Motivates Objective-C number, array, and dictionary literals by mapping concise syntax to their verbose factory-method equivalents, including Core Animation configuration. It provides useful historical context for reading legacy code that predates the literal syntax later adopted by the language.
- [Method Names in Objective-C – Ole Begemann](https://oleb.net/blog/2010/12/method-names-in-objective-c) — Ole Begemann · article catalogue
  **Published:** `2010-12-17T14:56:00Z`
  **NeKI brief:** Explains that every keyword segment is part of an Objective-C selector and demonstrates that unlabeled later parameters are legal but harmful. Use it as a concise rationale for descriptive selector pieces when maintaining Objective-C APIs alongside modern Swift interfaces.
- [Searching arrays with NSPredicate and blocks](https://useyourloaf.com/blog/searching-arrays-with-nspredicate-and-blocks) — Use Your Loaf · article catalogue
  **Published:** `2010-10-19T21:06:00+00:00`
  **NeKI brief:** Uses NSPredicate and block-based filtering to query arrays with explicit conditions. Predicate strings are flexible but need careful key validation; typed Swift closures are often safer for new code.
- [Adding Booleans to Objective-C Arrays and Dictionaries](https://useyourloaf.com/blog/adding-booleans-to-objective-c-arrays-and-dictionaries) — Use Your Loaf · article catalogue
  **Published:** `2010-09-23T20:38:00+00:00`
  **NeKI brief:** Objective-C collections store objects, so box BOOL and other primitive C values in NSNumber before inserting them. Unbox on retrieval with the matching accessor; treating primitive bits as object pointers causes invalid memory behavior.
- [Objective C anonymous categories](https://useyourloaf.com/blog/objective-c-anonymous-categories) — Use Your Loaf · article catalogue
  **Published:** `2010-09-14T22:23:00+00:00`
  **NeKI brief:** Uses anonymous Objective-C categories for class extensions and private declarations. Extensions can hide implementation details, but they should not obscure lifecycle-critical state from maintainers.
- [The design of every Mac application | Cocoa with Love](https://www.cocoawithlove.com/2010/06/design-of-every-mac-application.html) — Cocoa with Love · article catalogue
  **Published:** `2010-06-22`
  **NeKI brief:** Mac application design is decomposed into document, event, window, and responder responsibilities rather than one monolithic controller. The model helps diagnose lifecycle bugs in AppKit applications that mix UI and persistence.
- [Options for porting Objective-C/Cocoa apps to Windows | Cocoa with Love](https://www.cocoawithlove.com/2010/04/options-for-porting-objective-ccocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2010-04-15`
  **NeKI brief:** Porting Objective-C/Cocoa applications to Windows compares compatibility frameworks, rewrites, and platform abstractions. It is useful for weighing code reuse against build, UI, and runtime behavior that cannot be shared.
- [Cocoa Naming Conventions for Memory Allocation](https://useyourloaf.com/blog/cocoa-naming-conventions-for-memory-allocation) — Use Your Loaf · article catalogue
  **Published:** `2010-04-13T20:53:00+00:00`
  **NeKI brief:** Cocoa method names signal ownership: alloc, new, copy, and mutableCopy transfer responsibility, while other factory-style methods generally return autoreleased values. Follow that convention mechanically in manual-memory code to prevent leaks and over-release crashes.
- [Invoking other processes in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/05/invoking-other-processes-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2009-05-04`
  **NeKI brief:** Invoking another process from Cocoa requires controlled arguments, environment, output capture, and termination handling. The workflow helps avoid shell-injection and lifecycle bugs in desktop automation features.
- [In defense of Objective-C 2.0 Properties | Cocoa with Love](https://www.cocoawithlove.com/2008/08/in-defense-of-objective-c-20-properties.html) — Cocoa with Love · article catalogue
  **Published:** `2008-08-16`
  **NeKI brief:** Objective-C properties define an interface-level access contract, not merely generated accessors or dot syntax. Declaring that contract lets callers use a stable abstraction while implementations retain freedom over storage, validation, and derived values.
- [Open the previous document on application startup | Cocoa with Love](https://www.cocoawithlove.com/2008/05/open-previous-document-on-application.html) — Cocoa with Love · article catalogue
  **Published:** `2008-05-02`
  **NeKI brief:** Use the application delegate and recent-document support to reopen the last document at launch rather than presenting a blank untitled window. Make startup restoration conditional so an explicit user-open request is not overridden by automatic document selection.
- [Cocoa Application Startup | Cocoa with Love](https://www.cocoawithlove.com/2008/03/cocoa-application-startup.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-14`
  **NeKI brief:** Cocoa startup proceeds through Objective-C runtime initialization, NSApplication setup, nib loading, and document loading. Put initialization in the phase matching its dependencies; code that touches outlets or documents too early creates lifecycle-order failures.
- [mikeash.com: XBolo is Out!](https://www.mikeash.com/pyblog/xbolo-is-out.html) — Mike Ash · article catalogue
  **NeKI brief:** XBolo's release note offers a concrete example of shipping a small Mac game, including the engineering and distribution decisions around a complete product. Follow it for historical context on scope and platform trade-offs.
- [mikeash.com: WWDC 2008](https://www.mikeash.com/pyblog/wwdc-.html) — Mike Ash · article catalogue
  **NeKI brief:** The WWDC 2008 report records early platform announcements and their immediate developer consequences. It is useful historical routing for understanding how Cocoa, iPhone APIs, and tooling expectations evolved.
- [mikeash.com: WWDC 08 Followup](https://www.mikeash.com/pyblog/wwdc--followup.html) — Mike Ash · article catalogue
  **NeKI brief:** WWDC follow-up turns announcements into implementation questions by comparing new APIs with existing runtime constraints. The historical notes are useful for separating marketing names from the lifecycle and performance behavior developers must test.
- [mikeash.com: Writing the Complete Friday Q&A](https://www.mikeash.com/pyblog/writing-the-complete-friday-qa.html) — Mike Ash · article catalogue
  **NeKI brief:** Writing a technical Q&A requires isolating one language or runtime question, testing the smallest example, and documenting counterexamples. The workflow is a useful model for producing durable engineering notes instead of anecdotal fixes.
- [mikeash.com: Why CoreAudio is Hard](https://www.mikeash.com/pyblog/why-coreaudio-is-hard.html) — Mike Ash · article catalogue
  **NeKI brief:** Core Audio's difficulty comes from low-level, real-time constraints, opaque graph state, and APIs that expose implementation details rather than app-level concepts. The essay is valuable context when diagnosing glitches that ordinary object-oriented debugging misses.
- [mikeash.com: What Every Programmer Should Know](https://www.mikeash.com/pyblog/what-every-programmer-should-know.html) — Mike Ash · article catalogue
  **NeKI brief:** The essay separates durable programming fundamentals from fashionable tools, emphasizing representation, complexity, and failure analysis. It is useful as a compact diagnostic lens before blaming a framework for a performance or correctness problem.
- [mikeash.com: Welcome to iPhone: Your Crappy Mac of Tomorrow, Today!](https://www.mikeash.com/pyblog/welcome-to-iphone-your-crappy-mac-of-tomorrow-today.html) — Mike Ash · article catalogue
  **NeKI brief:** The early iPhone architecture reused familiar Mac concepts under tighter memory, input, and sandbox constraints. The historical analysis is useful for understanding why platform APIs prioritize lifecycle and resource discipline over desktop assumptions.
- [mikeash.com: VoodooPad Acquisition](https://www.mikeash.com/pyblog/voodoopad-acquisition.html) — Mike Ash · article catalogue
  **NeKI brief:** An acquisition changes a software project's ownership, roadmap, and support assumptions even when the codebase remains unchanged. The announcement is useful context for evaluating product continuity and dependency risk around third-party tools.
- [mikeash.com: Using FileMerge with subversion](https://www.mikeash.com/pyblog/using-filemerge-with-subversion.html) — Mike Ash · article catalogue
  **NeKI brief:** FileMerge can make textual and structural version-control conflicts easier to inspect, but the tool does not understand every generated artifact's semantics. Follow it for a focused review workflow around conflict resolution and verification.
- [mikeash.com: Using Evil for Good](https://www.mikeash.com/pyblog/using-evil-for-good.html) — Mike Ash · article catalogue
  **NeKI brief:** The essay repurposes a normally destructive technique toward controlled debugging or automation, emphasizing boundaries and reversibility. Follow it when evaluating whether a sharp systems tool can be made safe in development workflows.
- [mikeash.com: Unicode Comments Support](https://www.mikeash.com/pyblog/unicode-comments-support.html) — Mike Ash · article catalogue
  **NeKI brief:** Unicode comment support touches source encoding, compiler lexing, and editor display independently. The note helps distinguish a text-rendering problem from a parser limitation when non-ASCII documentation breaks an older toolchain.
- [mikeash.com: The Mac Toolbox: Followup](https://www.mikeash.com/pyblog/the-mac-toolbox-followup.html) — Mike Ash · article catalogue
  **NeKI brief:** The Mac Toolbox follow-up compares platform APIs by behavior and lifecycle rather than surface naming. Its diagnostic value is in identifying which framework owns state, cleanup, and event delivery before adding wrappers.
- [mikeash.com: The iPhone Development Story](https://www.mikeash.com/pyblog/the-iphone-development-story.html) — Mike Ash · article catalogue
  **NeKI brief:** The iPhone development story traces constraints that shaped early SDK and hardware decisions, including limited resources and unfamiliar interaction patterns. It provides useful context for why certain UIKit conventions exist.
- [mikeash.com: The iPhone Development Story: One Year Later](https://www.mikeash.com/pyblog/the-iphone-development-story-one-year-later.html) — Mike Ash · article catalogue
  **NeKI brief:** A year of iPhone development exposed practical limits in tooling, distribution, and device debugging that were not obvious from the SDK surface. The retrospective is a diagnostic source for separating API gaps from workflow failures.
- [mikeash.com: The How and Why of Cocoa Initializers](https://www.mikeash.com/pyblog/the-how-and-why-of-cocoa-initializers.html) — Mike Ash · article catalogue
  **NeKI brief:** Cocoa initialization separates allocation, designated initialization, convenience paths, and nib unarchiving, so overriding the wrong method can silently skip invariants. This explanation is a durable reference for debugging partially initialized Objective-C objects.
- [mikeash.com: The Cults of Programming](https://www.mikeash.com/pyblog/the-cults-of-programming.html) — Mike Ash · article catalogue
  **NeKI brief:** Programming communities can turn tools and paradigms into identity commitments, obscuring measurable trade-offs. The essay is useful review context when evaluating architecture choices by evidence rather than allegiance.
- [mikeash.com: The Complete Friday Q&A Volumes II and III Are Out!](https://www.mikeash.com/pyblog/the-complete-friday-qa-volumes-ii-and-iii-are-out.html) — Mike Ash · article catalogue
  **NeKI brief:** A curated Q&A archive preserves tested explanations of runtime and language behavior, making historical solutions searchable by mechanism. It is a routing lead for original experiments rather than a promise that old APIs remain current.
- [mikeash.com: Tales From The Crash Mines: Issue #1](https://www.mikeash.com/pyblog/tales-from-the-crash-mines-issue-1.html) — Mike Ash · article catalogue
  **NeKI brief:** Crash investigations improve when stack traces are reduced to a reproducible trigger and the failing ownership or synchronization assumption. This case-study format is useful for turning production crash reports into targeted diagnostic experiments.
- [mikeash.com: Summary of the Current State of my Publications](https://www.mikeash.com/pyblog/summary-of-the-current-state-of-my-publications.html) — Mike Ash · article catalogue
  **NeKI brief:** Maintaining a technical publication requires tracking which examples, books, and articles remain accurate as runtimes evolve. The summary is useful for routing readers to maintained material and recognizing when historical code needs revalidation.
- [mikeash.com: Subtle Bugs](https://www.mikeash.com/pyblog/subtle-bugs.html) — Mike Ash · article catalogue
  **NeKI brief:** Subtle bugs often arise from valid-looking assumptions about ownership, evaluation order, or API defaults. The examples are useful as a debugging reminder to reduce a symptom to a falsifiable mechanism.
- [mikeash.com: Some Light Reading](https://www.mikeash.com/pyblog/some-light-reading.html) — Mike Ash · article catalogue
  **NeKI brief:** A technical reading list can expose alternative solutions and historical context before implementation begins. Its value is discovery and comparison; each selected source still needs independent verification for current SDK behavior.
- [mikeash.com: Solving Simulator Bootstrap Errors](https://www.mikeash.com/pyblog/solving-simulator-bootstrap-errors.html) — Mike Ash · article catalogue
  **NeKI brief:** Simulator bootstrap failures are approached as environment and launchd state problems rather than app crashes. The troubleshooting sequence narrows device runtime, service, and cache causes before resorting to destructive simulator resets.
- [mikeash.com: Score!](https://www.mikeash.com/pyblog/score.html) — Mike Ash · article catalogue
  **NeKI brief:** A small scoring utility is a useful case study in separating input parsing, state updates, and presentation. Keeping those layers independent makes a toy program easier to extend and exposes assumptions that would otherwise remain implicit.
- [mikeash.com: Reading Between the Lines of Apple's FCC Reply](https://www.mikeash.com/pyblog/reading-between-the-lines-of-apples-fcc-reply.html) — Mike Ash · article catalogue
  **NeKI brief:** Interpreting an FCC filing requires separating disclosed constraints from speculation about product behavior. The analysis models evidence extraction as a technical research workflow, useful when public regulatory documents inform engineering assumptions.
- [mikeash.com: Perform Better With Garbage Collection](https://www.mikeash.com/pyblog/perform_better_with_garbage_collection.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C garbage collection changes ownership and reclamation costs, but does not remove retain-cycle or resource-lifetime design issues. The article helps distinguish collector behavior from deterministic cleanup requirements in Cocoa code.
- [mikeash.com: Open Source](https://www.mikeash.com/pyblog/open-source.html) — Mike Ash · article catalogue
  **NeKI brief:** The open-source notes explain how publishing reusable code exposes API stability, documentation, and maintenance costs that private projects can postpone. Follow it when preparing a library for external consumers.
- [mikeash.com: objc_msgSend's New Prototype](https://www.mikeash.com/pyblog/objc_msgsends-new-prototype.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains the changed objc_msgSend prototype and why the compiler now needs an explicitly typed function pointer before calling it. The low-level examples are useful when bridging Objective-C messaging or diagnosing ABI-related warnings.
- [mikeash.com: NetAwake](https://www.mikeash.com/pyblog/netawake.html) — Mike Ash · article catalogue
  **NeKI brief:** NetAwake keeps a network connection active through controlled traffic and timers, exposing the battery trade-off of preventing idle sleep. The project is a concrete case study in balancing reachability against radio and background execution cost.
- [mikeash.com: Nanogolf](https://www.mikeash.com/pyblog/nanogolf.html) — Mike Ash · article catalogue
  **NeKI brief:** A compact programming challenge exposes how representation, algorithm choice, and language syntax affect code size independently of maintainability. The example is a useful reminder to separate recreational constraints from production engineering goals.
- [mikeash.com: Name/comment conflict](https://www.mikeash.com/pyblog/namecomment-conflict.html) — Mike Ash · article catalogue
  **NeKI brief:** A name/comment conflict in Objective-C demonstrates how compiler metadata and human-readable diagnostics can diverge. The small case is useful for understanding symbol naming constraints before introducing generated declarations or macros.
- [mikeash.com: More Fun With Autorelease](https://www.mikeash.com/pyblog/more-fun-with-autorelease.html) — Mike Ash · article catalogue
  **NeKI brief:** Autorelease pools defer Objective-C object destruction and can cause large transient memory spikes in loops or worker threads. The examples show where explicit pool scopes are a diagnostic and performance tool.
- [mikeash.com: Link: Implementing imp_implementationWithBlock](https://www.mikeash.com/pyblog/link-implementing-imp_implementationwithblock.html) — Mike Ash · article catalogue
  **NeKI brief:** Implementing imp_implementationWithBlock bridges a closure to an Objective-C method implementation, with ABI and lifetime constraints hidden behind the convenience API. Follow it for a precise runtime-level route from block to IMP.
- [mikeash.com: Lesson of the Day](https://www.mikeash.com/pyblog/lesson-of-the-day.html) — Mike Ash · article catalogue
  **NeKI brief:** A focused programming lesson is most reusable when it shows the failing assumption, a minimal experiment, and the corrected rule. This format turns a one-off debugging discovery into a checkable reference for later work.
- [mikeash.com: Leopard: First Impressions](https://www.mikeash.com/pyblog/leopard-first-impressions.html) — Mike Ash · article catalogue
  **NeKI brief:** Early macOS releases expose compatibility changes through concrete framework and tool behavior, not version numbers alone. The field report is useful when distinguishing OS migration work from assumptions inherited from an older SDK.
- [mikeash.com: Key-Value Observing Done Right](https://www.mikeash.com/pyblog/key-value-observing-done-right.html) — Mike Ash · article catalogue
  **NeKI brief:** Correct KVO requires matching registration, automatic versus manual notifications, context handling, and observer teardown. The article's edge cases explain why seemingly harmless observation code produces duplicate callbacks or crashes during deallocation.
- [mikeash.com: IOCCC 2006 Winners](https://www.mikeash.com/pyblog/ioccc2006.html) — Mike Ash · article catalogue
  **NeKI brief:** The IOCCC winners use extreme C techniques where parsing, undefined-behavior risks, and compressed representation become part of the program's mechanism. It is useful as a boundary case for readability and language-lawyer diagnostics.
- [mikeash.com: Introducing PLWeakCompatibility](https://www.mikeash.com/pyblog/introducing-plweakcompatibility.html) — Mike Ash · article catalogue
  **NeKI brief:** PLWeakCompatibility backports weak-reference behavior for runtimes without native support, relying on runtime hooks and careful lifecycle handling. It is valuable historical context for mixed deployment targets and compatibility shims.
- [mikeash.com: Introducing MAZeroingWeakRef](https://www.mikeash.com/pyblog/introducing-mazeroingweakref.html) — Mike Ash · article catalogue
  **NeKI brief:** MAZeroingWeakRef implements weak-reference semantics for environments that lacked native zeroing weak references, clearing the pointer when its target deallocates. It is useful historical context for understanding retain-cycle workarounds.
- [mikeash.com: I Do Not Agree To Your Terms](https://www.mikeash.com/pyblog/i-do-not-agree-to-your-terms.html) — Mike Ash · article catalogue
  **NeKI brief:** The terms discussion highlights how platform contracts and legal text constrain technical distribution choices. Follow it when a dependency or service agreement changes what an app may store, process, or ship.
- [mikeash.com: Goodbye, Nibs](https://www.mikeash.com/pyblog/goodbye-nibs.html) — Mike Ash · article catalogue
  **NeKI brief:** Moving away from nibs changes object construction, outlet wiring, and view lifecycle responsibilities. This discussion helps evaluate programmatic UI as a trade-off between explicit code, tooling, and serialization convenience.
- [mikeash.com: Getting Answers](https://www.mikeash.com/pyblog/getting-answers.html) — Mike Ash · article catalogue
  **NeKI brief:** Reliable technical answers come from narrowing a question, reproducing behavior, and checking primary evidence rather than collecting confident opinions. The workflow is reusable for debugging unfamiliar APIs.
- [mikeash.com: GCD Is Not Blocks, Blocks Are Not GCD](https://www.mikeash.com/pyblog/gcd-is-not-blocks-blocks-are-not-gcd.html) — Mike Ash · article catalogue
  **NeKI brief:** Blocks are closures and GCD is a scheduling API; conflating them obscures capture, queue, and lifetime behavior. Separating those mechanisms clarifies retain cycles, synchronous waits, and why moving work to a block does not itself make it concurrent.
- [mikeash.com: Fun With Beowulf Clusters](https://www.mikeash.com/pyblog/fun-with-beowulf-clusters.html) — Mike Ash · article catalogue
  **NeKI brief:** A Beowulf cluster demonstrates how parallel workloads trade coordination overhead and network latency for aggregate throughput. The project is a concrete reminder to measure task granularity before distributing work.
- [mikeash.com: Friday Q&A](https://www.mikeash.com/pyblog/friday-qa.html) — Mike Ash · article catalogue
  **NeKI brief:** A recurring technical Q&A benefits from a stable format: isolate one mechanism, test a minimal case, and preserve the result for later readers. The workflow turns experiments into searchable engineering knowledge.
- [mikeash.com: Friday Q&A 2018-06-29: Debugging with C-Reduce](https://www.mikeash.com/pyblog/friday-qa-2018-06-29-debugging-with-c-reduce.html) — Mike Ash · article catalogue
  **NeKI brief:** C-Reduce minimizes a failing compiler test case by repeatedly applying semantics-preserving reductions. This turns an enormous reproducer into a small diagnostic artifact that makes compiler bugs and language edge cases actionable.
- [mikeash.com: Friday Q&A 2017-11-10: Observing the A11's Heterogenous Cores](https://www.mikeash.com/pyblog/friday-qa-2017-11-10-observing-the-a11s-heterogenous-cores.html) — Mike Ash · article catalogue
  **NeKI brief:** Let’s kick this week’s code section off in the most hardcore way possible. The A11 is an amazing chip and Mike Ash is going to give you a wonderful tour of the heterogeneous cores in the new processor. 🚀
- [mikeash.com: Friday Q&A 2017-10-06: Type-Safe User Defaults](https://www.mikeash.com/pyblog/friday-qa-2017-10-06-type-safe-user-defaults.html) — Mike Ash · article catalogue
  **NeKI brief:** A type-safe UserDefaults layer centralizes keys and serialization so callers cannot silently mismatch value types or names. The pattern improves migration and testability while retaining the simple defaults store underneath.
- [mikeash.com: Friday Q&A 2017-06-30: Dissecting objc_msgSend on ARM64](https://www.mikeash.com/pyblog/friday-qa-2017-06-30-dissecting-objc_msgsend-on-arm64.html) — Mike Ash · article catalogue
  **NeKI brief:** Dissecting objc_msgSend on ARM64 exposes register conventions and runtime dispatch steps that ordinary Objective-C calls hide. The analysis is useful when diagnosing ABI-sensitive hooks or understanding why message dispatch cannot be treated as a normal function call.
- [mikeash.com: Friday Q&A 2016-02-19: What Is the Secure Enclave?](https://www.mikeash.com/pyblog/friday-qa-2016-02-19-what-is-the-secure-enclave.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains the Secure Enclave’s isolated processor, key-generation model, and cryptographic operations, while separating it from generic Keychain storage. It provides useful boundaries for deciding what secrets can be protected and what the enclave cannot do.
- [mikeash.com: Friday Q&A 2015-11-20: Covariance and Contravariance](https://www.mikeash.com/pyblog/friday-qa-2015-11-20-covariance-and-contravariance.html) — Mike Ash · article catalogue
  **NeKI brief:** Covariance and contravariance describe which generic type substitutions preserve safe input and output variance. The explanation is a routing reference for designing Swift protocols and closures without relying on unsound casts.
- [mikeash.com: Friday Q&A 2015-09-18: Building a Gear Warning System](https://www.mikeash.com/pyblog/friday-qa-2015-09-18-building-a-gear-warning-system.html) — Mike Ash · article catalogue
  **NeKI brief:** A gear-warning system combines sensor thresholds, hysteresis, and timely user feedback to avoid noisy alerts. The example is a practical state-machine exercise where filtering decisions matter more than the UI notification itself.
- [mikeash.com: Friday Q&A 2015-09-04: Let's Build dispatch_queue](https://www.mikeash.com/pyblog/friday-qa-2015-09-04-lets-build-dispatch_queue.html) — Mike Ash · article catalogue
  **NeKI brief:** Building a dispatch queue from first principles exposes worker coordination, synchronization, and shutdown semantics that GCD normally hides. Follow it to understand queue guarantees before diagnosing deadlocks or assuming FIFO behavior.
- [mikeash.com: Friday Q&A 2015-07-31: Tagged Pointer Strings](https://www.mikeash.com/pyblog/friday-qa-2015-07-31-tagged-pointer-strings.html) — Mike Ash · article catalogue
  **NeKI brief:** Tagged pointer strings store small values directly in the pointer representation, avoiding allocation while preserving object-like APIs. The runtime trick illustrates the ABI and lifetime assumptions that make such optimizations fragile.
- [mikeash.com: Friday Q&A 2015-07-03: Address Sanitizer](https://www.mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) — Mike Ash · article catalogue
  **NeKI brief:** Address Sanitizer instruments memory accesses to catch use-after-free and out-of-bounds errors near their cause. The workflow turns intermittent corruption into a diagnosable test failure, with runtime overhead accepted during debugging.
- [mikeash.com: Friday Q&A 2015-05-29: Concurrent Memory Deallocation in the Objective-C Runtime](https://www.mikeash.com/pyblog/friday-qa-2015-05-29-concurrent-memory-deallocation-in-the-objective-c-runtime.html) — Mike Ash · article catalogue
  **NeKI brief:** The article examines how Objective-C runtime deallocation can race under concurrency; saved technical context supports a concrete ownership and synchronization brief in a later source-specific override batch.
- [mikeash.com: Friday Q&A 2015-05-01: Fuzzing with afl-fuzz](https://www.mikeash.com/pyblog/friday-qa-2015-05-01-fuzzing-with-afl-fuzz.html) — Mike Ash · article catalogue
  **NeKI brief:** AFL fuzzing mutates inputs while tracking coverage to discover parser and memory-safety failures that hand-written tests miss. The workflow requires a small deterministic harness and interpretable crash artifacts.
- [mikeash.com: Friday Q&A 2015-03-20: Preprocessor Abuse and Optional Parentheses](https://www.mikeash.com/pyblog/friday-qa-2015-03-20-preprocessor-abuse-and-optional-parentheses.html) — Mike Ash · article catalogue
  **NeKI brief:** Preprocessor tricks can support optional syntactic forms, but token-level parsing is fragile and opaque; prefer ordinary language constructs unless the compile-time ergonomics justify the maintenance and diagnostics cost.
- [mikeash.com: Friday Q&A 2015-02-20: Let's Build @synchronized](https://www.mikeash.com/pyblog/friday-qa-2015-02-20-lets-build-synchronized.html) — Mike Ash · article catalogue
  **NeKI brief:** Recreating @synchronized exposes lock acquisition, exception-safe release, and object-based lock identity. The exercise demonstrates why synchronization primitives need a precise ownership and reentrancy policy.
- [mikeash.com: Friday Q&A 2014-11-07: Let's Build NSZombie](https://www.mikeash.com/pyblog/friday-qa-2014-11-07-lets-build-nszombie.html) — Mike Ash · article catalogue
  **NeKI brief:** An NSZombie-style tool replaces deallocated objects with sentinels so later messages identify a use-after-free. The diagnostic technique trades memory reclamation for a precise crash signature during debugging.
- [mikeash.com: Friday Q&A 2014-06-06: Secrets of dispatch_once](https://www.mikeash.com/pyblog/friday-qa-2014-06-06-secrets-of-dispatch_once.html) — Mike Ash · article catalogue
  **NeKI brief:** dispatch_once provides thread-safe one-time initialization with ordering guarantees that ad-hoc Boolean guards lack. The analysis explains why initialization ownership and reentrancy still matter around a singleton boundary.
- [mikeash.com: Friday Q&A 2014-05-09: When an Autorelease Isn't](https://www.mikeash.com/pyblog/friday-qa-2014-05-09-when-an-autorelease-isnt.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Objective-C autorelease behavior and cases that do not follow the expected pool lifetime. Use it for low-level ARC and bridging diagnosis in legacy mixed-language code, not modern Swift-only architecture.
- [mikeash.com: Friday Q&A 2014-03-14: Introduction to the Sockets API](https://www.mikeash.com/pyblog/friday-qa-2014-03-14-introduction-to-the-sockets-api.html) — Mike Ash · article catalogue
  **NeKI brief:** Socket APIs separate connection setup, byte transport, framing, and error handling, so protocol design cannot be delegated to a single read call. The introduction grounds network code in those explicit boundaries.
- [mikeash.com: Friday Q&A 2013-12-06: Network Protocol Design](https://www.mikeash.com/pyblog/friday-qa-2013-12-06-network-protocol-design.html) — Mike Ash · article catalogue
  **NeKI brief:** Network protocol design starts with framing, versioning, failure modes, and compatibility before bytes are sent. The article is useful for making protocol evolution a deliberate contract rather than a by-product of messages.
- [mikeash.com: Friday Q&A 2013-10-25: NSObject: the Class and the Protocol](https://www.mikeash.com/pyblog/friday-qa-2013-10-25-nsobject-the-class-and-the-protocol.html) — Mike Ash · article catalogue
  **NeKI brief:** `NSObject` is both a root-class implementation and a protocol-shaped capability set; distinguish required runtime behavior from inherited convenience methods when designing lightweight Objective-C types or interoperability boundaries.
- [mikeash.com: Friday Q&A 2013-10-11: Why Registers Are Fast and RAM Is Slow](https://www.mikeash.com/pyblog/friday-qa-2013-10-11-why-registers-are-fast-and-ram-is-slow.html) — Mike Ash · article catalogue
  **NeKI brief:** Registers, caches, and RAM have radically different latency and bandwidth characteristics, so data locality shapes performance more than isolated instruction counts. This helps interpret profiling results.
- [mikeash.com: Friday Q&A 2013-09-27: ARM64 and You](https://www.mikeash.com/pyblog/friday-qa-2013-09-27-arm64-and-you.html) — Mike Ash · article catalogue
  **NeKI brief:** ARM64 changes calling conventions, pointer width, and assembly assumptions, making old 32-bit code and binary hooks unsafe by default. The overview identifies migration surfaces that require architecture-specific validation.
- [mikeash.com: Friday Q&A 2013-08-30: Model Serialization With Property Lists](https://www.mikeash.com/pyblog/friday-qa-2013-08-30-model-serialization-with-property-lists.html) — Mike Ash · article catalogue
  **NeKI brief:** Property-list serialization supports only a restricted value graph, so model conversion should validate types, preserve schema compatibility, and distinguish absent, null-like, and malformed input before constructing domain values.
- [mikeash.com: Friday Q&A 2013-08-16: Let's Build Dispatch Groups](https://www.mikeash.com/pyblog/friday-qa-2013-08-16-lets-build-dispatch-groups.html) — Mike Ash · article catalogue
  **NeKI brief:** Dispatch groups coordinate completion of several asynchronous operations without prescribing how each task runs. The example highlights balanced enter and leave calls, notification queues, and the risk of waiting on the wrong thread.
- [mikeash.com: Friday Q&A 2013-08-02: Type-Safe Scalars with Single-Field Structs](https://www.mikeash.com/pyblog/friday-qa-2013-08-02-type-safe-scalars-with-single-field-structs.html) — Mike Ash · article catalogue
  **NeKI brief:** Single-field structs create distinct types for values that share a primitive representation, preventing accidental mixing of IDs, coordinates, or units. The pattern gains compiler checks with minimal runtime overhead.
- [mikeash.com: Friday Q&A 2013-06-28: Anatomy of a Compiler Bug](https://www.mikeash.com/pyblog/friday-qa-2013-06-28-anatomy-of-a-compiler-bug.html) — Mike Ash · article catalogue
  **NeKI brief:** A compiler-bug investigation begins with a minimal reproducer, isolates the triggering construct, and records expected versus generated behavior. That evidence supports a useful report and a safe local workaround.
- [mikeash.com: Friday Q&A 2013-05-17: Let's Build stringWithFormat:](https://www.mikeash.com/pyblog/friday-qa-2013-05-17-lets-build-stringwithformat.html) — Mike Ash · article catalogue
  **NeKI brief:** Rebuilding stringWithFormat exposes format parsing, argument promotion, and type conversion rules hidden by variadic APIs. The exercise clarifies why format strings are a boundary requiring validation and tests.
- [mikeash.com: Friday Q&A 2013-05-03: Proper Use of Asserts](https://www.mikeash.com/pyblog/friday-qa-2013-05-03-proper-use-of-asserts.html) — Mike Ash · article catalogue
  **NeKI brief:** Assertions document programmer invariants and fail early in development, while recoverable user or network errors need normal control flow. The article helps keep diagnostic checks from becoming production error handling.
- [mikeash.com: Friday Q&A 2013-04-05: Windows and Window Controllers](https://www.mikeash.com/pyblog/friday-qa-2013-04-05-windows-and-window-controllers.html) — Mike Ash · article catalogue
  **NeKI brief:** Window controllers own window lifecycle and coordination, while views should not become global presentation managers. The article explains how that ownership boundary prevents leaks and tangled document behavior.
- [mikeash.com: Friday Q&A 2013-03-22: Let's Build NSInvocation, Part II](https://www.mikeash.com/pyblog/friday-qa-2013-03-22-lets-build-nsinvocation-part-ii.html) — Mike Ash · article catalogue
  **NeKI brief:** NSInvocation packages a target message and arguments for deferred dispatch, requiring careful type encodings and ownership. The implementation details show why dynamic invocation is powerful but fragile.
- [mikeash.com: Friday Q&A 2013-03-08: Let's Build NSInvocation, Part I](https://www.mikeash.com/pyblog/friday-qa-2013-03-08-lets-build-nsinvocation-part-i.html) — Mike Ash · article catalogue
  **NeKI brief:** Building NSInvocation reveals Objective-C method signatures, argument buffers, and message dispatch as distinct runtime layers. The exercise gives useful diagnostic context for reflection-heavy legacy code.
- [mikeash.com: Friday Q&A 2013-02-22: Let's Build UITableView](https://www.mikeash.com/pyblog/friday-qa-2013-02-22-lets-build-uitableview.html) — Mike Ash · article catalogue
  **NeKI brief:** Matthew Elton takes the reins for the Friday Q&A this week with a look at implementing UITableView from scratch. The sample code provided has options to toggle the cell reuse optimisation which gives a glimpse of how life could have been without the reuse…
- [mikeash.com: Friday Q&A 2013-02-08: Let's Build Key-Value Coding](https://www.mikeash.com/pyblog/friday-qa-2013-02-08-lets-build-key-value-coding.html) — Mike Ash · article catalogue
  **NeKI brief:** Key-value coding resolves property paths dynamically, requiring well-defined lookup, conversion, and failure behavior. Rebuilding it exposes the runtime assumptions hidden by a string-based API.
- [mikeash.com: Friday Q&A 2013-01-25: Let's Build NSObject](https://www.mikeash.com/pyblog/friday-qa-2013-01-25-lets-build-nsobject.html) — Mike Ash · article catalogue
  **NeKI brief:** Rebuilding NSObject exposes identity, dynamic dispatch hooks, and reference semantics that higher-level Cocoa APIs assume. The exercise makes runtime responsibilities visible when debugging Objective-C interoperability.
- [mikeash.com: Friday Q&A 2013-01-11: Mach Exception Handlers](https://www.mikeash.com/pyblog/friday-qa-2013-01-11-mach-exception-handlers.html) — Mike Ash · article catalogue
  **NeKI brief:** Mach exception handlers receive low-level faults before higher-level crash reporting, making thread state and forwarding policy explicit. The technique is powerful diagnostic infrastructure with substantial safety risk.
- [mikeash.com: Friday Q&A 2012-12-28: What Happens When You Load a Byte of Memory](https://www.mikeash.com/pyblog/friday-qa-2012-12-28-what-happens-when-you-load-a-byte-of-memory.html) — Mike Ash · article catalogue
  **NeKI brief:** Loading one byte of memory travels through address translation, caches, and physical storage, each with distinct latency. The explanation gives a concrete mental model for locality-driven performance behavior.
- [mikeash.com: Friday Q&A 2012-12-14: Objective-C Pitfalls](https://www.mikeash.com/pyblog/friday-qa-2012-12-14-objective-c-pitfalls.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C pitfalls often arise from dynamic dispatch, nil messaging, ownership conventions, and type erasure interacting unexpectedly. The review is useful for locating boundaries where static Swift assumptions do not apply.
- [mikeash.com: Friday Q&A 2012-11-30: Let's Build A Mach-O Executable](https://www.mikeash.com/pyblog/friday-qa-2012-11-30-lets-build-a-mach-o-executable.html) — Mike Ash · article catalogue
  **NeKI brief:** Building a Mach-O executable exposes headers, load commands, segments, and entry-point setup as explicit binary-format decisions. The exercise provides diagnostic context for linker and loader failures.
- [mikeash.com: Friday Q&A 2012-11-16: Let's Build objc_msgSend](https://www.mikeash.com/pyblog/friday-qa-2012-11-16-lets-build-objc_msgsend.html) — Mike Ash · article catalogue
  **NeKI brief:** Rebuilding objc_msgSend exposes selector lookup, receiver dispatch, and calling-convention constraints at the Objective-C runtime boundary. The experiment explains why dynamic messaging cannot be replaced with an arbitrary function pointer.
- [mikeash.com: Friday Q&A 2012-11-02: Building the FFT](https://www.mikeash.com/pyblog/friday-qa-2012-11-02-building-the-fft.html) — Mike Ash · article catalogue
  **NeKI brief:** Building an FFT shows how divide-and-conquer transforms reduce repeated frequency calculations from quadratic work. The implementation makes input size, complex arithmetic, and numerical trade-offs explicit.
- [mikeash.com: Friday Q&A 2012-10-12: Obtaining and Interpreting Audio Data](https://www.mikeash.com/pyblog/friday-qa-2012-10-12-obtaining-and-interpreting-audio-data.html) — Mike Ash · article catalogue
  **NeKI brief:** Audio data handling requires knowing sample format, channel layout, interleaving, and frame timing before processing bytes. The article provides a foundation for avoiding incorrect assumptions in signal pipelines.
- [mikeash.com: Friday Q&A 2012-09-28: Optimizing Flood Fill](https://www.mikeash.com/pyblog/friday-qa-2012-09-28-optimizing-flood-fill.html) — Mike Ash · article catalogue
  **NeKI brief:** Flood-fill optimization depends on minimizing repeated pixel visits and choosing data structures that match image locality. The article connects an algorithmic change to measurable graphics performance.
- [mikeash.com: Friday Q&A 2012-09-14: Implementing a Flood Fill](https://www.mikeash.com/pyblog/friday-qa-2012-09-14-implementing-a-flood-fill.html) — Mike Ash · article catalogue
  **NeKI brief:** Flood fill explores connected pixels from a seed using explicit bounds and visited-state rules. The implementation makes connectivity and stack or queue choice visible before later optimization.
- [mikeash.com: Friday Q&A 2012-08-24: Things You Never Wanted To Know About C](https://www.mikeash.com/pyblog/friday-qa-2012-08-24-things-you-never-wanted-to-know-about-c.html) — Mike Ash · article catalogue
  **NeKI brief:** C exposes layout, integer conversion, pointer, and undefined-behavior rules that higher-level languages often hide. The tour is useful when diagnosing failures at an FFI or systems boundary.
- [mikeash.com: Friday Q&A 2012-08-10: A Tour of CommonCrypto](https://www.mikeash.com/pyblog/friday-qa-2012-08-10-a-tour-of-commoncrypto.html) — Mike Ash · article catalogue
  **NeKI brief:** The Friday Q&A article gives a technical tour of Apple's CommonCrypto APIs and explains their use from application code.
- [mikeash.com: Friday Q&A 2012-07-27: Let's Build Tagged Pointers](https://www.mikeash.com/pyblog/friday-qa-2012-07-27-lets-build-tagged-pointers.html) — Mike Ash · article catalogue
  **NeKI brief:** Tagged pointers encode small values in pointer bits, avoiding allocation while retaining object-like interfaces. The runtime technique is ABI-sensitive and belongs in framework internals, not ordinary application code.
- [mikeash.com: Friday Q&A 2012-07-06: Let's Build NSNumber](https://www.mikeash.com/pyblog/friday-qa-2012-07-06-lets-build-nsnumber.html) — Mike Ash · article catalogue
  **NeKI brief:** NSNumber bridges scalar values through an object representation with conversion and equality semantics that can surprise typed code. Rebuilding it exposes the runtime compromises behind boxed numbers.
- [mikeash.com: Friday Q&A 2012-06-22: Objective-C Literals](https://www.mikeash.com/pyblog/friday-qa-2012-06-22-objective-c-literals.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C literals provide concise syntax for boxed numbers, arrays, dictionaries, and subscripting while retaining runtime collection semantics. The overview helps spot where literal convenience masks mutability or nullability concerns.
- [mikeash.com: Friday Q&A 2012-06-01: A Tour of PLWeakCompatibility: Part II](https://www.mikeash.com/pyblog/friday-qa-2012-06-01-a-tour-of-plweakcompatibility-part-ii.html) — Mike Ash · article catalogue
  **NeKI brief:** Weak-reference compatibility layers emulate zeroing weak behavior where runtimes lack it, requiring careful deallocation and thread-safety semantics. The implementation illustrates why ownership features are runtime contracts.
- [mikeash.com: Friday Q&A 2012-05-18: A Tour of PLWeakCompatibility: Part I](https://www.mikeash.com/pyblog/friday-qa-2012-05-18-a-tour-of-plweakcompatibility-part-i.html) — Mike Ash · article catalogue
  **NeKI brief:** Weak-reference emulation needs a registry that tracks object lifetime without retaining the target. The first part explains the ownership bookkeeping required before exposing a weak-like API.
- [mikeash.com: Friday Q&A 2012-05-04: PLCrashReporter and Unwinding the Stack With DWARF, Part 2](https://www.mikeash.com/pyblog/friday-qa-2012-05-04-plcrashreporter-and-unwinding-the-stack-with-dwarf-part-2.html) — Mike Ash · article catalogue
  **NeKI brief:** DWARF stack unwinding reconstructs call frames from saved register and debug information after a crash. The technique explains how crash reporters produce symbols when ordinary runtime state is incomplete.
- [mikeash.com: Friday Q&A 2012-04-27: PLCrashReporter and Unwinding the Stack With DWARF](https://www.mikeash.com/pyblog/friday-qa-2012-04-27-plcrashreporter-and-unwinding-the-stack-with-dwarf.html) — Mike Ash · article catalogue
  **NeKI brief:** DWARF unwind metadata describes how to recover caller registers from a frame, allowing crash tools to walk stacks without frame pointers. The foundation explains why corrupted stacks can still resist symbolication.
- [mikeash.com: Friday Q&A 2012-04-13: Nib Memory Management](https://www.mikeash.com/pyblog/friday-qa-2012-04-13-nib-memory-management.html) — Mike Ash · article catalogue
  **NeKI brief:** Nib loading creates object graphs whose top-level ownership and outlet retention must be understood to avoid leaks or premature deallocation. The article makes Interface Builder lifecycle assumptions explicit.
- [mikeash.com: Friday Q&A 2012-03-16: Let's Build NSMutableDictionary](https://www.mikeash.com/pyblog/friday-qa-2012-03-16-lets-build-nsmutabledictionary.html) — Mike Ash · article catalogue
  **NeKI brief:** A mutable dictionary couples hashing, equality, collision handling, resizing, and mutation semantics; preserve these invariants as entries are inserted or removed rather than optimizing buckets in isolation.
- [mikeash.com: Friday Q&A 2012-03-09: Let's Build NSMutableArray](https://www.mikeash.com/pyblog/friday-qa-2012-03-09-lets-build-nsmutablearray.html) — Mike Ash · article catalogue
  **NeKI brief:** Presents Let’s Build NSMutableArray, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [mikeash.com: Friday Q&A 2012-03-02: Key-Value Observing Done Right: Take 2](https://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [mikeash.com: Friday Q&A 2012-02-17: Ring Buffers and Mirrored Memory: Part II](https://www.mikeash.com/pyblog/friday-qa-2012-02-17-ring-buffers-and-mirrored-memory-part-ii.html) — Mike Ash · article catalogue
  **NeKI brief:** Mirrored virtual-memory mapping lets a ring buffer’s logical wraparound occupy contiguous address space, simplifying bulk reads and writes while trading implementation complexity and platform-specific virtual-memory setup.
- [mikeash.com: Friday Q&A 2012-02-03: Ring Buffers and Mirrored Memory: Part I](https://www.mikeash.com/pyblog/friday-qa-2012-02-03-ring-buffers-and-mirrored-memory-part-i.html) — Mike Ash · article catalogue
  **NeKI brief:** A ring buffer separates producer and consumer progress with bounded storage; keep index updates atomic and distinguish full from empty without forcing either side to copy or block unnecessarily.
- [mikeash.com: Friday Q&A 2012-01-20: Fork Safety](https://www.mikeash.com/pyblog/friday-qa-2012-01-20-fork-safety.html) — Mike Ash · article catalogue
  **NeKI brief:** After `fork`, a multithreaded process retains only the calling thread while locks may remain held by vanished threads; do minimal async-safe work before `exec` and avoid ordinary framework calls.
- [mikeash.com: Friday Q&A 2011-12-02: Object File Inspection Tools](https://www.mikeash.com/pyblog/friday-qa-2011-12-02-object-file-inspection-tools.html) — Mike Ash · article catalogue
  **NeKI brief:** I have been trying not to link to Mike Ash every week (you really should be subscribed!) but I couldn’t let this one pass unnoticed. This week takes a look at otool, nm, otx and class-dump.
- [mikeash.com: Friday Q&A 2011-11-11: Building a Memoizing Block Proxy](https://www.mikeash.com/pyblog/friday-qa-2011-11-11-building-a-memoizing-block-proxy.html) — Mike Ash · article catalogue
  **NeKI brief:** Memoization caches a function result by its input identity, reducing repeated work only when the function is pure enough; bound cache lifetime and define invalidation for mutable data or resource-heavy results.
- [mikeash.com: Friday Q&A 2011-10-28: Generic Block Proxying](https://www.mikeash.com/pyblog/friday-qa-2011-10-28-generic-block-proxying.html) — Mike Ash · article catalogue
  **NeKI brief:** A generic block proxy can interpose before or after arbitrary callback execution, enabling instrumentation or adaptation; preserve the original signature, ownership, return behavior, and error propagation at the proxy boundary.
- [mikeash.com: Friday Q&A 2011-09-30: Automatic Reference Counting](https://www.mikeash.com/pyblog/friday-qa-2011-09-30-automatic-reference-counting.html) — Mike Ash · article catalogue
  **NeKI brief:** Simply the clearest and best explanation of ARC that I have seen so far. Fascinating.
- [mikeash.com: Friday Q&A 2011-09-16: Let's Build Reference Counting](https://www.mikeash.com/pyblog/friday-qa-2011-09-16-lets-build-reference-counting.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Let’s Build Reference Counting with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [mikeash.com: Friday Q&A 2011-09-02: Let's Build NSAutoreleasePool](https://www.mikeash.com/pyblog/friday-qa-2011-09-02-lets-build-nsautoreleasepool.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Friday Q A Let’s Build NSAutoreleasePool with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [mikeash.com: Friday Q&A 2011-08-19: Namespaced Constants and Functions](https://www.mikeash.com/pyblog/friday-qa-2011-08-19-namespaced-constants-and-functions.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Friday Q A Namespaced Constants and Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [mikeash.com: Friday Q&A 2011-08-05: Method Signature Mismatches](https://www.mikeash.com/pyblog/friday-qa-2011-08-05-method-signature-mismatches.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C selector names do not encode full parameter or return types, so incompatible declarations can compile yet corrupt calls at runtime; keep declarations consistent across headers, implementations, and dynamic invocation.
- [mikeash.com: Friday Q&A 2011-07-08: Let's Build NSNotificationCenter](https://www.mikeash.com/pyblog/friday-qa-2011-07-08-lets-build-nsnotificationcenter.html) — Mike Ash · article catalogue
  **NeKI brief:** A notification center maps names and senders to observer registrations, then must define delivery order, mutation during dispatch, and observer lifetime to avoid leaks, missed events, or reentrant surprises.
- [mikeash.com: Friday Q&A 2011-06-03: Objective-C Blocks vs. C++0x Lambdas: Fight!](https://www.mikeash.com/pyblog/friday-qa-2011-06-03-objective-c-blocks-vs-c0x-lambdas-fight.html) — Mike Ash · article catalogue
  **NeKI brief:** Blocks and lambdas both capture context, but their ownership, mutability, conversion, and language-integration rules differ; choose the construct from the host ABI and callback lifecycle rather than surface syntax.
- [mikeash.com: Friday Q&A 2011-05-20: The Inner Life of Zombies](https://www.mikeash.com/pyblog/friday-qa-2011-05-20-the-inner-life-of-zombies.html) — Mike Ash · article catalogue
  **NeKI brief:** Zombie objects preserve deallocated instances long enough to reveal use-after-free messaging; enable them for focused diagnosis, then turn them off because their altered lifetime and memory cost invalidate normal behavior.
- [mikeash.com: Friday Q&A 2011-04-15: Compile-Time Tips and Tricks](https://www.mikeash.com/pyblog/friday-qa-2011-04-15-compile-time-tips-and-tricks.html) — Mike Ash · article catalogue
  **NeKI brief:** Compile-time checks and generated declarations can reject invalid combinations before runtime, but should encode clear invariants rather than hide ordinary control flow behind preprocessor complexity.
- [mikeash.com: Friday Q&A 2011-04-01: Signal Handling](https://www.mikeash.com/pyblog/friday-qa-2011-04-01-signal-handling.html) — Mike Ash · article catalogue
  **NeKI brief:** Signal handlers run under severe async-safety constraints, so do minimal work, communicate through safe primitives, and move ordinary cleanup or allocation back to normal execution context.
- [mikeash.com: Friday Q&A 2011-03-18: Random Numbers](https://www.mikeash.com/pyblog/friday-qa-2011-03-18-random-numbers.html) — Mike Ash · article catalogue
  **NeKI brief:** Randomness requirements differ between simulation, sampling, and security; select a generator for the threat model, avoid modulo bias when mapping ranges, and make seeded tests reproducible.
- [mikeash.com: Friday Q&A 2011-02-18: Compound Literals](https://www.mikeash.com/pyblog/friday-qa-2011-02-18-compound-literals.html) — Mike Ash · article catalogue
  **NeKI brief:** C compound literals create an unnamed initialized value with block or static lifetime depending on context; use them for concise local data, but do not return pointers whose storage expires at scope exit.
- [mikeash.com: Friday Q&A 2011-01-04: Practical Floating Point](https://www.mikeash.com/pyblog/friday-qa-2011-01-04-practical-floating-point.html) — Mike Ash · article catalogue
  **NeKI brief:** Floating-point arithmetic has rounding, non-associativity, and exceptional values; compare with a domain tolerance, choose a stable accumulation order, and never treat binary fractions as exact decimal quantities.
- [mikeash.com: Friday Q&A 2010-11-19: Creating Classes at Runtime for Fun and Profit](https://www.mikeash.com/pyblog/friday-qa-2010-11-19-creating-classes-at-runtime-for-fun-and-profit.html) — Mike Ash · article catalogue
  **NeKI brief:** Runtime class creation can attach methods and ivars dynamically for proxies or generated behavior, but names, layouts, and lifecycle rules become global runtime state that requires strict isolation and tests.
- [mikeash.com: Friday Q&A 2010-08-27: Defensive Programming in Cocoa](https://www.mikeash.com/pyblog/friday-qa-2010-08-27-defensive-programming-in-cocoa.html) — Mike Ash · article catalogue
  **NeKI brief:** Cocoa APIs expose failure through errors, exceptions, nil, and asynchronous state; normalize assumptions at boundaries, check documented preconditions, and preserve invariants before invoking framework behavior.
- [mikeash.com: Friday Q&A 2010-08-12: Implementing NSCoding](https://www.mikeash.com/pyblog/friday-qa-2010-08-12-implementing-nscoding.html) — Mike Ash · article catalogue
  **NeKI brief:** Archiving types should encode a stable schema, decode defensively, and evolve optional fields compatibly; validate classes and values before reconstructing object graphs from untrusted or old archives.
- [mikeash.com: Friday Q&A 2010-07-02: Background Timers](https://www.mikeash.com/pyblog/friday-qa-2010-07-02-background-timers.html) — Mike Ash · article catalogue
  **NeKI brief:** A timer requires an active run loop on the thread that owns it; background scheduling therefore needs a retained loop, explicit mode management, and a shutdown path rather than a fire-and-forget thread.
- [mikeash.com: Friday Q&A 2010-06-18: Implementing Equality and Hashing](https://www.mikeash.com/pyblog/friday-qa-2010-06-18-implementing-equality-and-hashing.html) — Mike Ash · article catalogue
  **NeKI brief:** Equal values must produce the same hash and remain stable while used as dictionary keys or set members; implement both operations from the same identity fields and test collision behavior.
- [mikeash.com: Friday Q&A 2010-04-30: Dealing with Retain Cycles](https://www.mikeash.com/pyblog/friday-qa-2010-04-30-dealing-with-retain-cycles.html) — Mike Ash · article catalogue
  **NeKI brief:** Reference cycles keep all participating objects alive; identify ownership graphs, make one edge weak or explicit, and verify that callbacks, delegates, and closures release the intended lifecycle boundary.
- [mikeash.com: Friday Q&A 2010-04-16: Implementing Fast Enumeration](https://www.mikeash.com/pyblog/friday-qa-2010-04-16-implementing-fast-enumeration.html) — Mike Ash · article catalogue
  **NeKI brief:** A custom Objective-C collection supports fast enumeration by returning batches, mutation state, and storage references that let callers iterate efficiently while detecting unsafe collection mutation.
- [mikeash.com: Friday Q&A 2010-04-09: Comparison of Objective-C Enumeration Techniques](https://www.mikeash.com/pyblog/friday-qa-2010-04-09-comparison-of-objective-c-enumeration-techniques.html) — Mike Ash · article catalogue
  **NeKI brief:** Enumeration choices trade syntax, allocation, message-send overhead, mutation behavior, and collection-specific complexity; select the API from the collection’s guarantees and measured work rather than assuming all loops cost alike.
- [mikeash.com: Friday Q&A 2010-03-12: Subclassing Class Clusters](https://www.mikeash.com/pyblog/friday-qa-2010-03-12-subclassing-class-clusters.html) — Mike Ash · article catalogue
  **NeKI brief:** Class clusters hide concrete storage behind a public abstraction, so subclasses must implement the designated primitive methods and respect initialization substitution rather than assuming the allocated class remains the final instance.
- [mikeash.com: Friday Q&A 2010-02-19: Character Encodings](https://www.mikeash.com/pyblog/friday-qa-2010-02-19-character-encodings.html) — Mike Ash · article catalogue
  **NeKI brief:** Text bytes acquire meaning only through an agreed encoding; retain the encoding at I/O boundaries, reject invalid data deliberately, and avoid treating byte length, Unicode scalars, and user-visible characters as interchangeable.
- [mikeash.com: Friday Q&A 2010-02-05: Error Returns with Continuation Passing Style](https://www.mikeash.com/pyblog/friday-qa-2010-02-05-error-returns-with-continuation-passing-style.html) — Mike Ash · article catalogue
  **NeKI brief:** Continuation-passing style sends success and error values to blocks rather than returning through `NSError **`; it can centralize propagation, but changes control flow and needs deliberate error-handling conventions.
- [mikeash.com: Friday Q&A 2010-01-29: Method Replacement for Fun and Profit](https://www.mikeash.com/pyblog/friday-qa-2010-01-29-method-replacement-for-fun-and-profit.html) — Mike Ash · article catalogue
  **NeKI brief:** Method replacement can intercept or alter selector behavior at runtime for diagnostics or adaptation, but it changes global dispatch; constrain scope, preserve the original implementation, and test interaction order.
- [mikeash.com: Friday Q&A 2010-01-22: Toll Free Bridging Internals](https://www.mikeash.com/pyblog/friday-qa-2010-01-22-toll-free-bridging-internals.html) — Mike Ash · article catalogue
  **NeKI brief:** Toll-free bridged Core Foundation and Foundation values share compatible runtime representation, but ownership transfer remains explicit; make bridging casts and retain/release responsibility visible at API boundaries.
- [mikeash.com: Friday Q&A 2010-01-15: Stack and Heap Objects in Objective-C](https://www.mikeash.com/pyblog/friday-qa-2010-01-15-stack-and-heap-objects-in-objective-c.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C values can have stack, heap, static, or tagged representations with different lifetimes; retain or copy based on ownership semantics rather than assuming every object originated from `alloc`.
- [mikeash.com: Friday Q&A 2010-01-08: NSNotificationQueue](https://www.mikeash.com/pyblog/friday-qa-2010-01-08-nsnotificationqueue.html) — Mike Ash · article catalogue
  **NeKI brief:** `NSNotificationQueue` can coalesce or defer deliveries by posting style and run-loop mode; use it when batching reduces churn, while ensuring consumers tolerate delayed or merged updates.
- [mikeash.com: Friday Q&A 2010-01-01: NSRunLoop Internals](https://www.mikeash.com/pyblog/friday-qa-2010-01-01-nsrunloop-internals.html) — Mike Ash · article catalogue
  **NeKI brief:** Run loops repeatedly process input sources, timers, and queued work in modes; blocked modes, nested loops, and implicit scheduling can explain callbacks that arrive late or never run.
- [mikeash.com: Friday Q&A 2009-11-27: Using Accessors in Init and Dealloc](https://www.mikeash.com/pyblog/friday-qa-2009-11-27-using-accessors-in-init-and-dealloc.html) — Mike Ash · article catalogue
  **NeKI brief:** Initializers and deinitializers should establish and tear down stored state directly when accessors may trigger side effects, notifications, subclass overrides, or dependencies that are not yet valid.
- [mikeash.com: Friday Q&A 2009-11-20: Probing Cocoa With PyObjC](https://www.mikeash.com/pyblog/friday-qa-2009-11-20-probing-cocoa-with-pyobjc.html) — Mike Ash · article catalogue
  **NeKI brief:** A dynamic bridge such as PyObjC can quickly inspect Cocoa classes, selectors, and runtime behavior; use exploratory scripts to form hypotheses, then verify production assumptions against documented APIs and tests.
- [mikeash.com: Friday Q&A 2009-11-13: Dangerous Cocoa Calls](https://www.mikeash.com/pyblog/friday-qa-2009-11-13-dangerous-cocoa-calls.html) — Mike Ash · article catalogue
  **NeKI brief:** APIs that launch processes, wait synchronously, or invoke callbacks can fail, block, or re-enter unexpectedly; establish error, cancellation, and thread-affinity handling before treating them as simple utility calls.
- [mikeash.com: Friday Q&A 2009-10-30: Generators in Objective-C](https://www.mikeash.com/pyblog/friday-qa-2009-10-30-generators-in-objective-c.html) — Mike Ash · article catalogue
  **NeKI brief:** A generator preserves local state between yields so callers pull successive values on demand; model that state and termination explicitly when adapting pull-based iteration to callback-oriented Objective-C code.
- [mikeash.com: Friday Q&A 2009-10-09: Defensive Programming](https://www.mikeash.com/pyblog/friday-qa-2009-10-09-defensive-programming.html) — Mike Ash · article catalogue
  **NeKI brief:** Defensive code anticipates malformed input, failed assumptions, partial work, and future misuse; validate boundaries, preserve invariants, and make failures diagnosable instead of merely preventing the immediate crash.
- [mikeash.com: Friday Q&A 2009-10-02: Care and Feeding of Singletons](https://www.mikeash.com/pyblog/friday-qa-2009-10-02-care-and-feeding-of-singletons.html) — Mike Ash · article catalogue
  **NeKI brief:** Singletons suit process-wide, inherently singular coordination, but global access hides dependencies and complicates tests; prefer explicit injection unless shared lifetime and ownership are genuinely part of the domain.
- [mikeash.com: Friday Q&A 2009-08-14: Practical Blocks](https://www.mikeash.com/pyblog/friday-qa-2009-08-14-practical-blocks.html) — Mike Ash · article catalogue
  **NeKI brief:** Escaping Objective-C blocks must be copied from their stack lifetime, and capture semantics determine mutability and ownership; the article is historically bounded but still explains why stored callbacks need lifetime design.
- [mikeash.com: Friday Q&A 2009-07-17: Format Strings Tips and Tricks](https://www.mikeash.com/pyblog/friday-qa-2009-07-17-format-strings-tips-and-tricks.html) — Mike Ash · article catalogue
  **NeKI brief:** Format strings encode an argument contract: conversion, width, precision, length, and positional arguments must match the supplied values, or output and memory safety can fail in non-obvious ways.
- [mikeash.com: Friday Q&A 2009-07-10: Type Specifiers in C, Part 3](https://www.mikeash.com/pyblog/friday-qa-2009-07-10-type-specifiers-in-c-part-3.html) — Mike Ash · article catalogue
  **NeKI brief:** C aggregate, enum, and typedef declarations model layout and naming separately; choose representation from value range, memory layout, and interoperability requirements rather than syntax convenience.
- [mikeash.com: Friday Q&A 2009-07-03: Type Specifiers in C, Part 2](https://www.mikeash.com/pyblog/friday-qa-2009-07-03-type-specifiers-in-c-part-2.html) — Mike Ash · article catalogue
  **NeKI brief:** C declarations combine specifiers, declarators, pointers, arrays, and functions according to precedence rules; simplify complex signatures with typedefs only after understanding the underlying type and ABI intent.
- [mikeash.com: Friday Q&A 2009-06-26: Type Qualifiers in C, Part 1](https://www.mikeash.com/pyblog/friday-qa-2009-06-26-type-qualifiers-in-c-part-1.html) — Mike Ash · article catalogue
  **NeKI brief:** C type qualifiers such as `const`, `volatile`, and `restrict` describe how values may be accessed, enabling compiler assumptions but never replacing synchronization or a clear ownership contract.
- [mikeash.com: Friday Q&A 2009-06-19: Mac OS X Process Memory Statistics](https://www.mikeash.com/pyblog/friday-qa-2009-06-19-mac-os-x-process-memory-statistics.html) — Mike Ash · article catalogue
  **NeKI brief:** Process memory diagnosis distinguishes virtual size, resident pages, faults, and shared mappings; collect the right metric over time before attributing growth to a leak or allocator behavior.
- [mikeash.com: Friday Q&A 2009-05-22: Objective-C Class Loading and Initialization](https://www.mikeash.com/pyblog/friday-qa-2009-05-22-objective-c-class-loading-and-initialization.html) — Mike Ash · article catalogue
  **NeKI brief:** `+load` runs during image loading, whereas `+initialize` is deferred until first class use; keep either hook minimal because ordering, locks, and dependencies make early initialization fragile.
- [mikeash.com: Friday Q&A 2009-03-27: Objective-C Message Forwarding](https://www.mikeash.com/pyblog/friday-qa-2009-03-27-objective-c-message-forwarding.html) — Mike Ash · article catalogue
  **NeKI brief:** When normal selector lookup fails, Objective-C can redirect or package the invocation for forwarding; use this runtime escape hatch deliberately because dynamic proxies and `@dynamic` properties obscure ordinary method contracts.
- [mikeash.com: Friday Q&A 2009-03-20: Objective-C Messaging](https://www.mikeash.com/pyblog/friday-qa-2009-03-20-objective-c-messaging.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C message sending resolves a selector against an object’s class at runtime before invoking an implementation; selectors name behavior, while methods are the concrete code chosen by lookup.
- [mikeash.com: Friday Q&A 2009-03-13: Intro to the Objective-C Runtime](https://www.mikeash.com/pyblog/friday-qa-2009-03-13-intro-to-the-objective-c-runtime.html) — Mike Ash · article catalogue
  **NeKI brief:** Objective-C objects carry runtime class metadata that supports allocation, method lookup, and introspection; understanding that boundary helps explain dynamic behavior without relying on undocumented structure layouts.
- [mikeash.com: Friday Q&A 2009-01-23](https://www.mikeash.com/pyblog/friday-qa-2009-01-23.html) — Mike Ash · article catalogue
  **NeKI brief:** KVO works by dynamically intercepting observed property changes, so manual notifications and direct ivar mutation can bypass expectations; design observation boundaries around documented mutation paths and lifetimes.
- [mikeash.com: Friday Q&A 2009-01-09](https://www.mikeash.com/pyblog/friday-qa-2009-01-09.html) — Mike Ash · article catalogue
  **NeKI brief:** Thread safety is a contract, not a property of a type name: distinguish safe independent access from safe shared mutation, then state synchronization, reentrancy, and callback assumptions explicitly.
- [mikeash.com: Friday Q&A 2008-12-19](https://www.mikeash.com/pyblog/friday-qa-2008-12-19.html) — Mike Ash · article catalogue
  **NeKI brief:** Parallel work can be divided by independent tasks, data partitions, pipelines, or recursive decomposition; choose a model whose communication and scheduling overhead stays smaller than the work it exposes.
- [mikeash.com: Fluid Simulation for Dummies](https://www.mikeash.com/pyblog/fluid-simulation-for-dummies.html) — Mike Ash · article catalogue
  **NeKI brief:** A real-time fluid approximation discretizes velocity and density into neighboring cells, then iteratively applies source, diffusion, advection, and projection steps; grid resolution and iteration count trade fidelity for runtime cost.
- [mikeash.com: Bug Reversal](https://www.mikeash.com/pyblog/bug-reversal.html) — Mike Ash · article catalogue
  **NeKI brief:** Diagnose apparent character-order defects by separating encoded values from rendered glyph order: bidirectional scripts can display a correct logical string right-to-left even when interpolation and format arguments are correct.
- [mikeash.com: Friday Q&A 2010-04-09: Comparison of Objective-C Enumeration Techniques](http://www.mikeash.com/pyblog/friday-qa-2010-04-09-comparison-of-objective-c-enumeration-techniques.html) — Mike Ash · article catalogue
  **NeKI brief:** Enumeration choices trade syntax, allocation, message-send overhead, mutation behavior, and collection-specific complexity; select the API from the collection’s guarantees and measured work rather than assuming all loops cost alike.
- [mikeash.com: Friday Q&A 2009-08-14: Practical Blocks](http://www.mikeash.com/pyblog/friday-qa-2009-08-14-practical-blocks.html) — Mike Ash · article catalogue
  **NeKI brief:** Escaping Objective-C blocks must be copied from their stack lifetime, and capture semantics determine mutability and ownership; the article is historically bounded but still explains why stored callbacks need lifetime design.
- [mikeash.com: Friday Q&A 2010-02-05: Error Returns with Continuation Passing Style](http://mikeash.com/pyblog/friday-qa-2010-02-05-error-returns-with-continuation-passing-style.html) — Mike Ash · article catalogue
  **NeKI brief:** Continuation-passing style sends success and error values to blocks rather than returning through `NSError **`; it can centralize propagation, but changes control flow and needs deliberate error-handling conventions.

## Newsletter and related leads

- [A Framework to Make Decisions Faster as a Lead Software Engineer](https://mfaani.com/posts/career/a-framework-to-make-decisions-faster-as-a-lead-software-engineer) — Those Who Swift · Issue 281 — Article · Topics: Developer Career & Practice · Objective-C & Cocoa
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Presents a decision-making framework for lead software engineers who must act quickly under pressure. Its focus is on structuring incomplete information and trade-offs so technical leadership decisions become faster and more deliberate.
- [Empty States in SwiftUI with ContentUnavailableView](https://kylebrowning.com/posts/swiftui-empty-states-contentunavailableview) — Those Who Swift · Issue 281 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Compares the ContentUnavailableView initializers and shows how to build reusable SwiftUI empty states for search, errors, and offline conditions. The approach reduces repeated per-screen placeholder logic while keeping each state understandable to users.
- [Preventing Transitive Swift Imports with Bazel](https://adincebic.com/2026/08/23/preventing-transitive-swift-imports-with.html) — Those Who Swift · Issue 281 — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Explains how permissive transitive Swift imports let a module use dependencies it did not declare directly, and presents Bazel-oriented ways to prevent that leakage. Explicit dependency ownership improves build reasoning and reduces accidental coupling between modules.
- [ArcBLEKit](https://github.com/ilawsonlu/ArcBLEKit) — Fatbobman’s Swift Weekly · Issue 150 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Provides a zero-dependency Swift Concurrency package for BLE central apps on iOS 14 and macOS 11 onward. Its cancellable scanning, connection, GATT, notification, timeout, reconnect, and write-backpressure APIs show how to contain CoreBluetooth delegate complexity.
- [Appllama](https://appllama.io/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Lets teams inspect onboarding, paywall, and other UI flows from top-grossing iOS apps through a large screen library. Use it for product and UX research while treating observed competitor behaviour as context, not a product prescription.
- [Abendrot](https://abendrot.app/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: Objective-C & Cocoa
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Open-source macOS screen warmer for night work with external-display support and no app telemetry. Its menu-bar controls and evidence-linked privacy posture are useful reference points for a small native utility.
- [July digest](https://www.swift.org/blog/whats-new-in-swift-july-2026?ref=ioscodereview.com) — iOS Code Review · Issue 84 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2026-08-20T05:35:08.000Z`
  **NeKI brief:** Summarizes July activity across Swift releases, evolution, tooling and community workgroups, providing a routing overview rather than a single API tutorial.
- [IP and DNS Leaks in WebKit Affecting Proxy Browsers and Apple iCloud Private Relay](https://mysk.blog/2026/08/04/webkit-proxy-icloud-private-relay-ip-leak) — Those Who Swift · Issue 280 — Article · Topics: Developer Tools · Objective-C & Cocoa · Security & Privacy
  **Published:** `2026-08-19T20:31:22.272Z`
  **NeKI brief:** Demonstrates three WebKit paths—DNS prefetching, WebAuthn related-origin requests, and WebTransport—that can bypass configured proxies and expose a device's network. It distinguishes affected proxy and Private Relay setups from system-level VPN tunnels.
- [Using Top Functions Mode in Instruments to Quickly Find the Slowest Code](https://swiftdevjournal.com/posts/top-functions) — iOS Dev Weekly · Issue 763 — Article · Topics: Objective-C & Cocoa · Performance · Swift
  **Published:** `14th August 2026`
  **NeKI brief:** Shows how Instruments' Top Functions mode reorders Time Profiler or CPU Profiler samples by self weight, then relates the result to the flame graph. It offers a faster first pass for locating genuinely expensive functions.
- [SwiftUI @ContentBuilder - Faster Type Checking in Xcode 27](https://www.sagarunagar.com/blog/swiftui-contentbuilder-xcode-27?ref=createwithswift.com) — Create with Swift · Issue 118 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `2026-08-01T15:00:04.000Z`
  **NeKI brief:** Sagar explores SwiftUI’s ContentBuilder, showing how its unified builder model reduces type-checking overhead, improves compiler performance for complex view hierarchies, and simplifies building reusable SwiftUI APIs.
- [Revisiting the JET iOS Modular Architecture in 2026](https://albertodebortoli.com/2026/07/15/revisiting-the-jet-ios-modular-architecture-in-2026) — iOS Dev Weekly · Issue 761 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `31st July 2026`
  **NeKI brief:** Revisits Just Eat’s 2019 modular iOS model, retaining useful domain boundaries while refining module vocabulary and cross-domain dependencies for current Swift tooling. Use it to test whether an inherited architecture still matches team and build constraints.
- [original article](https://albertodebortoli.com/2019/12/19/modular-ios-architecture-at-just-eat) — iOS Dev Weekly · Issue 761 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `31st July 2026`
  **NeKI brief:** Documents Just Eat’s original journey toward a modular iOS architecture, including holistic design and staged adoption. Read it as the baseline for the 2026 reassessment and distinguish historical tooling constraints from enduring boundary decisions.
- [Working with Xcode on CI](https://l.fatbobman.com/w0146-02) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** Explains provisioning Xcode on macOS CI, selecting versions with DEVELOPER_DIR, running first-launch setup, and installing simulator or Metal components. It also documents authentication and stale-toolchain trade-offs that prevent a completely hands-off installer.
- [tswift: A Lightweight Swift Runtime Built with Rust](https://l.fatbobman.com/w0146-06) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Dependency Injection · Objective-C & Cocoa · Swift
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** The tswift repository experiments with a lightweight Swift environment for the browser backed by Rust. Use it to inspect which language and runtime pieces are required for portable execution, without assuming parity with Apple’s production toolchain.
- [ImplementedSE-0522Source-Level Control Over Compiler Warnings](https://github.com/apple/swift-evolution/blob/main/proposals/0522-source-warning-control.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Records ImplementedSE-0522Source-Level Control Over Compiler Warnings, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [RejectedSE-0533Generating synchronous overloads of `async` functions with a macro](https://github.com/apple/swift-evolution/blob/main/proposals/0533-reasync-macros.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Concurrency · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Records RejectedSE-0533Generating synchronous overloads of `async` functions with a macro, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0537Section Placement Control for Functions](https://github.com/apple/swift-evolution/blob/main/proposals/0537-function-sections.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Extends Swift's section placement attribute from stored data to functions, initializers, deinitializers, closures, and accessors, while adding a default-section override. The motivation is precise linker placement for firmware entry points and embedded startup code.
- [Active ReviewSE-0538Disconnected](https://github.com/apple/swift-evolution/blob/main/proposals/0538-disconnected.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Records Active ReviewSE-0538Disconnected, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Swift Scribe](https://github.com/FluidInference/swift-scribe) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux - iOS Dev Tools — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Swift Scribe combines local microphone transcription with on-device summarization on current Apple OS releases, without external dependencies. Useful for evaluating a privacy-preserving speech pipeline and its deployment-version constraints.
- [Mimer](https://mimer.hasanjafri.com/) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux - iOS Dev Tools — Article · Topics: Objective-C & Cocoa · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Mimer is a macOS utility or developer tool. Follow its page and source for the concrete workflow and integration surface it provides, while verifying supported platforms and maintenance.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-07-15`
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [Active ReviewSE-0536Package Registry Search](https://github.com/apple/swift-evolution/blob/main/proposals/0536-registry-search.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2026-07-14T14:06:22.000Z`
  **NeKI brief:** Records Active ReviewSE-0536Package Registry Search, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [The iOS Core Engineering Series — Volume 1](https://anubhav52.gumroad.com/l/txbtwg?layout=discover&recommended_by=search&_gl=1%2A1e2sg2v%2A_ga%2AMTAxODg0NTgzOC4xNzgzNTE0MDA0%2A_ga_6LJN6D94N6%2AczE3ODM1MTQwMDQkbzEkZzEkdDE3ODM1MTQwMjckajM3JGwwJGgw) — Those Who Swift · Issue 274 — Article · Topics: Objective-C & Cocoa
  **Published:** `2026-07-08`
  **NeKI brief:** Reviews The iOS Core Engineering Series — Volume 1. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Apple App Store Scraper](https://apify.com/maximedupre/apple-app-store-scraper) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Apify's Apple App Store Scraper extracts app metadata, ratings, reviews, rankings, and related store information into structured datasets. Use it for repeatable App Store research, while respecting platform terms and rate limits.
- [Claude Science, An AI Workbench For Scientists, Is Now Available](https://www.anthropic.com/news/claude-science-ai-workbench) — Those Who Swift · Issue 273 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2026-07-01`
  **NeKI brief:** Reviews Claude Science, An AI Workbench For Scientists, Is Now Available. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [What’s New In SwiftUI For iOS 27?](https://www.youtube.com/watch?v=tNxEqyUVGck) — Those Who Swift · Issue 273 — Video · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-07-01`
  **NeKI brief:** Surveys iOS 27 SwiftUI changes including lazy @State creation, compile-time improvements, reorderable containers, swipe actions outside List, and the Document protocol. Useful as a migration map before checking final SDK semantics.
- [All new frameworks presented at WWDC26](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc26) — SwiftLee Weekly · Issue 330 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** This reference inventories the 14 frameworks introduced at WWDC26 and pairs each name with its Apple-platform purpose. It is useful as a compact discovery map before following the relevant primary documentation for App Intents, AI, routing, graphics, or testing work.
- [_UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots?ref=createwithswift.com) — Create with Swift · Issue 113 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-27T18:12:28.000Z`
  **NeKI brief:** Artem dives deep on how the private UIKit _UIPortalView mirrors live view content without duplicating view hierarchies or taking snapshots, using it as a window into how UIKit, Core Animation, and Liquid Glass-style effects compose live UI at the rendering…
- [Liquid Glass In SwiftUI: How To Modernize An iOS App Template](https://iosapptemplates.com/blog/liquid-glass-swiftui-app-template-modernization) — Those Who Swift · Issue 272 — Article · Topics: Liquid Glass · Swift · SwiftUI
  **Published:** `2026-06-24`
  **NeKI brief:** Walks through modernizing a SwiftUI template with Liquid Glass styling. Use it to identify migration touchpoints in an existing UI, then validate visual hierarchy, accessibility, and API availability rather than applying the template wholesale.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — SwiftUI Weekly · SwiftUI Weekly - Issue #236 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-06-22T10:29:00.171Z`
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [SolidLikeARock](https://github.com/nenadvulic/solid-like-a-rock) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** SolidLikeARock is a GitHub project for Swift or Apple-platform development. Follow its source for the concrete problem, API shape, and examples, while verifying supported versions before using it.
- [Fatbobman](https://fatbobman.com/en/about) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Presents fatbobman for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [BarDict](https://github.com/TokinoyuushaLink/BarDict) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI - iOS Dev Tools — Source repository · Topics: Developer Tools · Hardware & Devices · Objective-C & Cocoa
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** BarDict is a macOS menu-bar dictionary application supporting MDX and MDD resources. Useful for evaluating offline dictionary lookup and packaged language assets in a compact AppKit-style utility.
- [MacRumors + 2](https://www.macrumors.com/2026/05/18/apple-design-award-finalists-2026?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Architecture · Composable Architecture · Testing
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines MacRumors + 2 in the context of Architecture and Composable Architecture. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Modern Isn’t A Value. Fit Is.](https://www.swiftdifferently.com/blog/system-desgin/modern-isnot-a-value-fit-Is) — Those Who Swift · Issue 268 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-05-27`
  **NeKI brief:** Argues that modern APIs are not automatically the right fit for every product or codebase. Use it as an architecture prompt: weigh compatibility, team understanding, migration cost, and user value before adopting a newer framework pattern.
- [SwiftScript](https://github.com/Cocoanetics/SwiftScript) — Fatbobman’s Swift Weekly · Issue 137 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-05-25T12:03:50.192Z`
  **NeKI brief:** SwiftScript is an experimental embeddable interpreter that parses and executes Swift ASTs with SwiftSyntax rather than invoking swiftc. Use it to study interpreter architecture and dynamic scripting trade-offs in a Swift-hosted environment.
- [A Feature Flags System In Swift](https://livsycode.com/best-practices/a-feature-flags-system-in-swift) — Those Who Swift · Issue 267 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-05-21`
  **NeKI brief:** Presents a Swift feature-flags design with centralized evaluation and rollout control. Use it to compare configuration models and testing seams, while ensuring flag ownership, expiration, and failure defaults are explicit in production.
- [Install Swift 6.3.1 — Swift.org](https://www.swift.org/install?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Install Swift 6.3.1 — Swift.org in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.](https://www.swift.org/install/windows?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance… in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Artem walks through iOS performance as a layered system covering metrics, architecture, UI rendering, networking, caching, memory, and CPU behavior.
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Those Who Swift · Issue 266 — Article · Topics: Architecture · Networking · Performance
  **Published:** `2026-05-13`
  **NeKI brief:** Artem walks through iOS performance as a layered system covering metrics, architecture, UI rendering, networking, caching, memory, and CPU behavior.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Those Who Swift · Issue 266 — Video · Topics: Architecture · Concurrency · Networking
  **Published:** `2026-05-13`
  **NeKI brief:** Builds a protocol-driven SwiftUI networking stack with a Sendable API client, typed errors, endpoints, services, dependency injection, and preview mocks. The architectural discussion clarifies boundaries between view models, services, and concurrency isolation.
- [Swift ARC: From Zombie Objects to Side Tables](https://livsycode.com/swift/swift-arc-from-zombie-objects-to-side-tables) — SwiftLee Weekly · Issue 323 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2026-05-12T14:05:49.000Z`
  **NeKI brief:** Explains Swift ARC through zombie objects, reference counting, and side tables. Use it as a low-level diagnostic aid when investigating unexpected retention or weak-reference behavior, especially in mixed Swift and Objective-C code.
- [Swift Concurrency: One await, Two Actors: A Runtime Trace](https://adjoe.io/company/engineer-blog/swift-concurrency-await-runtime-trace-executor-hops) — Those Who Swift · Issue 265 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2026-05-06`
  **NeKI brief:** Traces how an await can move execution between actors and executors at runtime. Follow it when diagnosing latency or unexpected scheduling, using Instruments or logs to validate hops instead of inferring behavior from source order alone.
- [Apple Foundation Models With Mohammad Azam](https://www.youtube.com/watch?v=UeZfiKBHUCs&list=PL2iZPZus2bhSl3CDE_vs2851UMgix285u) — Those Who Swift · Issue 265 — Video · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-05-06`
  **NeKI brief:** Reviews Apple Foundation Models With Mohammad Azam. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Saying goodbye to CocoaPods: SwiftPM will soon be the default in Flutter!](https://blog.flutter.dev/saying-goodbye-to-cocoapods-swift-package-manager-is-soon-the-default-in-flutter-645a92714a57) — iOS Dev Weekly · Issue 749 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `1st May 2026`
  **NeKI brief:** Does this deserve a “Finally” comment? It’s good to see it happen, regardless. That CocoaPods read-only trunk deadline will come around sooner than we think. As far as I can tell, React Native still currently requires pod, but it appears that they are also…
- [also almost there](https://github.com/react-native-community/discussions-and-proposals/issues/587) — iOS Dev Weekly · Issue 749 — Source repository · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `1st May 2026`
  **NeKI brief:** Does this deserve a “Finally” comment? It’s good to see it happen, regardless. That CocoaPods read-only trunk deadline will come around sooner than we think. As far as I can tell, React Native still currently requires pod, but it appears that they are also…
- [When SwiftUI Modifiers Hold Onto Memory Longer Than Expected](https://livsycode.com/swiftui/when-swiftui-modifiers-hold-onto-memory-longer-than-expected) — Those Who Swift · Issue 264 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2026-04-29`
  **NeKI brief:** Explains when SwiftUI modifiers retain memory longer than expected. Useful for diagnosing ownership and lifetime surprises in view composition and validating suspected leaks with measurement.
- [Q&A: Swift Concurrency - Formatted](https://antongubarenko.substack.com/p/q-and-a-swift-concurrency-formatted) — Those Who Swift · Issue 264 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2026-04-29`
  **NeKI brief:** Answers practical Swift concurrency questions with formatted examples. Useful for comparing isolation, task structure, and compiler behavior against a concrete implementation rather than applying concurrency rules without checking their context.
- [Enums. Swift’s Secret Superpower.](https://lumley.io/blogs/swift-enums) — Those Who Swift · Issue 264 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2026-04-29`
  **NeKI brief:** Explains Swift enums and their expressive modeling role. Useful for choosing between cases, associated values, and alternative representations when designing domain state.
- [Appearance Mode Changer](https://www.createchsol.com/blog/2026-04-28-appearance-mode-changer.html) — Those Who Swift · Issue 264 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-04-29`
  **NeKI brief:** Introduces OAuth with illustrated explanations. Useful for understanding authorization roles, redirects, and token boundaries before integrating an OAuth flow into an app or service.
- [Lessons Learned from Security Incidents in Mobile Apps](https://hubs.la/Q049VR2g0) — SwiftLee Weekly · Issue 320 — Article · Topics: Objective-C & Cocoa · Security & Privacy · Testing
  **Published:** `2026-04-21T14:11:27.000Z`
  **NeKI brief:** Discusses Lessons Learned from Security Incidents in Mobile Apps, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [DanceUI](https://github.com/bytedance/DanceUI) — Fatbobman’s Swift Weekly · Issue 132 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** DanceUI is ByteDance's open-source exploration of reimplementing SwiftUI concepts. Use it to inspect alternative declarative-UI architecture and rendering decisions, without assuming behavior matches Apple's private implementation.
- [Modern Swift Library Architecture](https://coenttb.com/en/blog/4-1-the-swift-package) — Fatbobman’s Swift Weekly · Issue 132 — Article · Topics: Architecture · Foundation & Data Formats · Swift
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** Describes a layered Swift package ecosystem spanning primitives, standards, and foundations. Use it to study package-boundary design and dependency layering when a growing library family needs more than one monolithic module.
- [SwiftZilla](https://swiftzilla.dev/) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** SwiftZilla indexes a Swift project to expose dependency graphs, semantic search, impact analysis, and convention-aware code review through an AI workflow. It is useful for evaluating whether architectural onboarding can be automated without losing project-specific context.
- [Project Glasswing](https://www.anthropic.com/glasswing) — Those Who Swift · Issue 262 — Article · Topics: Objective-C & Cocoa · Security & Privacy · Testing
  **Published:** `2026-04-15`
  **NeKI brief:** Reviews Project Glasswing. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [RejectedSE-0246Generic Math(s) Functions](https://github.com/apple/swift-evolution/blob/main/proposals/0246-mathable.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Records RejectedSE-0246Generic Math(s) Functions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Returned For RevisionSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Awaiting ReviewSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [presentation repository](https://github.com/onevcat/2026-let-s-vision) — Fatbobman’s Swift Weekly · Issue 130 — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `2026-04-06T12:03:03.974Z`
  **NeKI brief:** Hosts WWDC-related Slidev material together with raw research and AI collaboration traces. Use it to inspect how a technical talk's claims were assembled and how agent-assisted research can remain reviewable.
- [What’s New In Swift: March 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-march-2026) — Those Who Swift · Issue 260 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2026-04-01`
  **NeKI brief:** Summarizes Swift changes released or highlighted in March 2026. Use it to locate language and tooling updates relevant to a project, then read the linked proposals and release notes before changing source or compiler settings.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [Codex-history](https://github.com/nishantdesai/codex-history) — iOS Dev Tools · iOS Dev Tools: Dispatched, Codex-history, Axe — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2026-03-26T19:26:01.777Z`
  **NeKI brief:** Codex-history stores or exposes history from Codex-related workflows. Follow its source for concrete persistence, search, and presentation behavior, while reviewing privacy and local-data boundaries before use.
- [SwiftUI Architecture Lessons I Wish I Knew Earlier](https://azamsharp.com/2026/02/18/swiftui-architecture-tips.html) — Those Who Swift · Issue 259 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-03-26`
  **NeKI brief:** Collects practical SwiftUI architecture lessons around state, boundaries, and maintainability. Useful for reviewing ownership and dependency confusion in a view hierarchy before introducing another abstraction.
- [I Refactored 3 Apps In A Year. Here’s What I Actually Learned](https://kubamilcarz.medium.com/i-refactored-3-apps-in-a-year-heres-what-i-actually-learned-bc519ba33bb1?source=rss-b30973e2bd56------2) — Those Who Swift · Issue 259 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-03-26`
  **NeKI brief:** Examines I Refactored 3 Apps In A Year. Here’s What I Actually Learned, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Some Vs Any: Understanding Opaque Types And Existential Types](https://www.sagarunagar.com/blog/swift-some-vs-any-opaque-existential-types) — Those Who Swift · Issue 258 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2026-03-18`
  **NeKI brief:** Reviews Swift Some Vs Any: Understanding Opaque Types And Existential Types. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [SwiftUI Under The Hood: What’s Really Happening When You Update View](https://www.youtube.com/watch?v=_zmQnn7Ki1E&t=28s) — Those Who Swift · Issue 258 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Reviews SwiftUI Under The Hood: What’s Really Happening When You Update View. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Those Who Swift · Issue 258 — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Turns a large SwiftUI list into a searchable, dynamically sortable browser, then adds a Contacts-style section index and draggable scrubber. Useful for coordinating section identifiers with programmatic scrolling and live drag feedback.
- [add it to the directory](https://iosdevdirectory.com/contributing) — iOS Dev Weekly · Issue 746 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th March 2026`
  **NeKI brief:** Explores add their site for them, focusing on so, whether you’ve fully migrated to mastodon or now split. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Those Who Swift · Issue 257 — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Builds a project-root CLAUDE.md for Swift, SwiftUI, and Xcode agents, covering architecture, build, test, and style instructions plus nested or shared configurations. Useful for comparing repository guidance loaded automatically by coding agents.
- [Borrowing from Kotlin/Android to Architect Scalable iOS Apps in SwiftUI](https://www.infoq.com/articles/kotlin-scalable-swiftui-patterns) — SwiftUI Weekly · SwiftUI Weekly - Issue #230 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-09T13:33:31.501Z`
  **NeKI brief:** Translates scalable architecture ideas from Kotlin and Android into SwiftUI patterns, with emphasis on boundaries and composition. Useful for comparing cross-platform architectural trade-offs before adopting abstractions in a growing iOS codebase.
- [Developers Are Safe… Thanks to Corporate Red Tape](https://azamsharp.com/2026/02/26/developers-are-safe.html) — Those Who Swift · Issue 256 — Article · Topics: AI Development · Architecture · Cross-Platform & Web
  **Published:** `2026-03-06`
  **NeKI brief:** Discusses how corporate process and red tape affect developer safety. Useful as organizational context for evaluating engineering controls and decision friction, not as an API reference.
- [Importing Memory into Claude](https://claude.com/import-memory) — Those Who Swift · Issue 256 — Article · Topics: Objective-C & Cocoa
  **Published:** `2026-03-06`
  **NeKI brief:** Describes importing persistent memory into Claude. Useful for evaluating retained context while separating durable preferences from task-specific evidence and security-sensitive data.
- [ListKit](https://github.com/Iron-Ham/Lists) — Fatbobman’s Swift Weekly · Issue 125 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** Lists investigates UIKit diffable-data-source stalls caused by snapshot internals, then offers an alternative list approach. Use it when frequent updates cause measurable collection-view hitches and profiling points to diffing overhead.
- [latest article](https://shapeof.com/archives/2026/2/greg_knauss_is_losing_himself.html) — iOS Dev Weekly · Issue 744 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `27th February 2026`
  **NeKI brief:** It was Gus Mueller’s latest article that prompted me to write about this topic again this week:
- [Wax](https://github.com/christopherkarani/Wax) — iOS Dev Tools · iOS Dev Tools: Wax, RespectASO, ThemeKit — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `2026-02-26T17:30:30.625Z`
  **NeKI brief:** Wax is a Swift or Apple-platform library with reusable application functionality. Follow its README and source to identify the concrete API and supported workflow, then assess maintenance and dependency risk.
- [RespectASO](https://github.com/respectlytics/respectaso) — iOS Dev Tools · iOS Dev Tools: Wax, RespectASO, ThemeKit — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2026-02-26T17:30:30.625Z`
  **NeKI brief:** RespectASO provides App Store Optimization tooling or metadata workflows. Follow its source for concrete keyword and listing-analysis behavior, while treating market data as time-sensitive and vendor-specific.
- [VoxTap](https://voxtap.app/) — iOS Dev Tools · iOS Dev Tools: Wax, RespectASO, ThemeKit — Article · Topics: Objective-C & Cocoa
  **Published:** `2026-02-26T17:30:30.625Z`
  **NeKI brief:** VoxTap provides voice or audio input functionality in a focused app workflow. Follow its page for concrete capture and transcription behavior, while verifying permissions, processing location, and supported languages.
- [PicoClaw](https://github.com/sipeed/picoclaw) — iOS Dev Tools · iOS Dev Tools: FRTMProxy, LLM Checker, PicoClaw — Source repository · Topics: AI Development · Concurrency · Developer Tools
  **Published:** `2026-02-19T20:00:59.741Z`
  **NeKI brief:** PicoClaw is a compact project for AI or edge-device workflows. Follow its source for concrete model, tool, and runtime integration, while verifying hardware, provider, and privacy requirements before adoption.
- [nanobot](https://github.com/HKUDS/nanobot) — iOS Dev Tools · iOS Dev Tools: FRTMProxy, LLM Checker, PicoClaw — Source repository · Topics: AI Development · Concurrency · Developer Tools
  **Published:** `2026-02-19T20:00:59.741Z`
  **NeKI brief:** nanobot is a compact project for building an AI or automation bot. Follow its source and README to inspect the concrete agent loop, tool integration, and runtime assumptions before relying on it.
- [SwiftUI Foundations: Build Great Apps Q&A](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — Those Who Swift · Issue 254 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2026-02-18`
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ARCtic Conference](https://arcticonference.com/) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** ARCtic Conference is an Apple-platform developer event covering iOS, visionOS, iPadOS, macOS, and watchOS. This page is an event listing rather than technical reading and should normally remain excluded from the knowledge index.
- [Add an Open Recent Menu to a SwiftUI app](https://swiftdevjournal.com/posts/open-recent-menu) — SwiftUI Weekly · SwiftUI Weekly - Issue #228 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-02-09T10:51:28.125Z`
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [open source](https://github.com/cocoatype/barc-generator) — iOS Dev Weekly · Issue 742 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** Also on the Wasm side, Geoff Pado’s Barcode Generator for his Barc app uses Wasm to generate the barcode images. The project is even open source if you fancy learning from a real-world example.
- [Five ways we’ve been using our MCP server](https://www.sketch.com/blog/mcp-server-use-cases) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** The Sketch article presents five concrete MCP server use cases and explains how the team applies them in its design-tool workflow.
- [Sketch added MCP support](https://www.sketch.com/docs/mcp-server) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** Examines Learn how to connect your AI tools with Sketch’s MCP Server. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Freddie Harrison](https://social.lol/@freddiewrites) — iOS Dev Weekly · Issue 742 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `6th February 2026`
  **NeKI brief:** The public social.lol profile identifies Freddie Harrison and exposes the author's profile and published posts without authentication.
- [How Apple Hooks Fifty Thousand Methods](https://www.youtube.com/watch?v=SuQGQ1vh9k0&t=1s) — Those Who Swift · Issue 252 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2026-02-04`
  **NeKI brief:** Reviews How Apple Hooks Fifty Thousand Methods. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [From Objective-C to Swift 6: What We Gained](https://slicker.me/swift/swift-evolution.html) — Those Who Swift · Issue 252 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2026-02-04`
  **NeKI brief:** Summarizes the evolution from Objective-C to Swift 6. Useful for historical context when reviewing language migration decisions and the capabilities gained across modern Swift releases.
- [its discontinuation](https://browsercompany.substack.com/p/letter-to-arc-members-2025) — iOS Dev Weekly · Issue 741 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th January 2026`
  **NeKI brief:** Explains the Browser Company's 2025 decision and communication to Arc members. Useful historical context for assessing product continuity, migration expectations, and risks when relying on a fast-changing developer tool.
- [rolling out changes to App Store search ads](https://www.macrumors.com/2026/01/23/more-app-store-ads-coming-soon) — Those Who Swift · Issue 251 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2026-01-28`
  **NeKI brief:** Reviews rolling out changes to App Store search ads. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Understanding Memory in iOS](https://anubhav52.gumroad.com/l/ios-memory) — Those Who Swift · Issue 251 — Tutorial · Topics: Developer Career & Practice · Developer Community & Business · Developer Tools
  **Published:** `2026-01-28`
  **NeKI brief:** Offers an iOS memory guide. Useful for reviewing allocation, lifetime, and profiling concepts when investigating memory pressure in shipped apps.
- [Skip Is Now Free and Open Source](https://skip.dev/blog/skip-is-free) — iOS Dev Weekly · Issue 740 — Article · Topics: Objective-C & Cocoa · Product Design
  **Published:** `23rd January 2026`
  **NeKI brief:** Announces Skip as free and open source, enabling shared Swift and SwiftUI code to target additional platforms through translation. Useful for evaluating cross-platform reach, with platform-specific behavior still requiring verification.
- [CocoaPods announced a staged move toward read-only mode](https://blog.cocoapods.org/CocoaPods-Specs-Repo) — Those Who Swift · Issue 250 — Article · Topics: AI Development · Objective-C & Cocoa · Swift Package Manager
  **Published:** `2026-01-21`
  **NeKI brief:** Announces the CocoaPods Specs repository move toward read-only operation. Useful for assessing dependency-resolution and supply-chain implications in projects that still rely on CocoaPods.
- [The complete guide to high-converting paywalls](https://www.revenuecat.com/blog/growth/paywalls-study-guide) — iOS Dev Weekly · Issue 739 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `16th January 2026`
  **NeKI brief:** What actually makes a paywall convert? We analyzed real-world subscription data and design patterns to break down what works, what doesn’t, and why. This study guide pulls together research, examples, and practical takeaways to help you design paywalls that…
- [MVVM and Reducer Pattern in Swift](https://www.fractal-dev.com/blog/mvvm-and-reducer-pattern?lang=en) — Those Who Swift · Issue 249 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2026-01-14`
  **NeKI brief:** Examines MVVM and Reducer Pattern in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Anthropic Expands AI Tools for Healthcare & Life Sciences](https://www.anthropic.com/news/healthcare-life-sciences?_bhlid=38bb3f9c085605c8e8d60092d5eb7912ac47b036) — Those Who Swift · Issue 249 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2026-01-14`
  **NeKI brief:** Reviews Anthropic Expands AI Tools for Healthcare & Life Sciences. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [🐙 GitHub’s Platform fee explained](https://cloud.namespace.so/pd3382pdfrpeq/updates/github-pricing-dec16-2025) — iOS CI Newsletter · Issue 84 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Examines GitHub’s Platform fee explained in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [Non-Sendable-First Design](https://www.massicotte.org/blog/non-sendable-first-design) — Those Who Swift · Issue 245 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2025-12-17`
  **NeKI brief:** Matt argues for designing Swift code around non-Sendable types by default, introducing Sendable and actors only when crossing isolation boundaries to keep concurrency simpler and more intentional.
- [Mastering SwiftUI — Free Guide](https://psimas.gumroad.com/l/swiftui?layout=discover&recommended_by=search&_gl=1%2A10g751b%2A_ga%2AODYxNDkzMDQzLjE3NjU2NDU4NjM.%2A_ga_6LJN6D94N6%2AczE3NjU2NDU4NjIkbzEkZzAkdDE3NjU2NDU4NjIkajYwJGwwJGgw) — Those Who Swift · Issue 245 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines Mastering SwiftUI — Free Guide, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Protocols as Existential Types vs. Generic Constraints](https://www.youtube.com/watch?v=-e8Ey6oTI24&t=320s) — Those Who Swift · Issue 245 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2025-12-17`
  **NeKI brief:** Reviews Swift Protocols as Existential Types vs. Generic Constraints. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Organizing SwiftUI Views with TabContent and TabContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Those Who Swift · Issue 243 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-12-10`
  **NeKI brief:** Artem explains how to organize a SwiftUI project by using a custom @TabContentBuilder to cleanly structure and manage tab-based navigation/components making your code more modular and easier to maintain.
- [Vectorizing Images With LLMs — Image Search & Semantic Matching](https://robkerr.com/vectorizing-images-with-llms) — Those Who Swift · Issue 243 — Article · Topics: AI Development · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `2025-12-10`
  **NeKI brief:** Explains vectorizing images with LLMs for semantic search. Useful for designing embedding pipelines, similarity retrieval, and the evaluation needed before using visual search in a product.
- [Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`](https://github.com/apple/swift-evolution/blob/main/proposals/0283-tuples-are-equatable-comparable-hashable.md) — SwiftLee Weekly · Issue 301 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-12-09T15:08:23.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 301 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-12-09T15:08:23.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [on-device vector search](https://docs.objectbox.io/on-device-ann-vector-search) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** ObjectBox documents on-device approximate nearest-neighbor vector search for local data. Follow it for a concrete persistence and similarity-search workflow, including the trade-off between local latency, index configuration, and storage.
- [RIB](https://github.com/son-iOS/SwiftUI-RIB) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SwiftUI-RIB adapts Uber's Router–Interactor–Builder architecture with dependency structs, Combine communication, and state/view containers. It is useful for comparing explicit parent-child lifecycle and navigation boundaries with coordinator or environment-driven SwiftUI designs.
- [Uber’s official documentation](https://github.com/uber/RIBs) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** Uber's RIBs framework structures mobile features around Router, Interactor, and Builder components with explicit lifecycles and parent-child ownership. Useful as an architectural comparison point for navigation-heavy applications and SwiftUI coordinators.
- [SwiftUI Popover](https://github.com/qusc/SwiftUI-Popover) — iOS Dev Tools · iOS Dev Tools: RequestSpec, SwiftUI Popover, Sourcekit-bazel-bsp — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-11-27T20:00:44.130Z`
  **NeKI brief:** SwiftUI Popover provides popover presentation components for SwiftUI. Follow its source for concrete anchoring, dismissal, and platform-specific behavior, then compare its API with current native presentation tools.
- [SettingsKit](https://github.com/Aeastr/SettingsKit) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI 2.0, SettingsKit, SwiftCache — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-11-20T16:50:33.113Z`
  **NeKI brief:** SettingsKit is a GitHub library for constructing or managing application settings interfaces. Follow its source to inspect the concrete model and view integration, while checking platform and lifecycle assumptions before adoption.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Those Who Swift · Issue 241 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-11-20`
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [From Swift to Mojo and high-performance AI Engineering with Chris Lattner](https://newsletter.pragmaticengineer.com/p/from-swift-to-mojo-and-high-performance) — SwiftLee Weekly · Issue 297 — Podcast · Topics: AI Development · Performance · Swift
  **Published:** `2025-11-11T15:06:31.000Z`
  **NeKI brief:** Presents From Swift to Mojo and high-performance AI Engineering with Chris Lattner, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0498Expose demangle function in Runtime module](https://github.com/apple/swift-evolution/blob/main/proposals/0498-runtime-demangle.md) — SwiftLee Weekly · Issue 297 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-11-11T15:06:31.000Z`
  **NeKI brief:** Records Active ReviewSE-0498Expose demangle function in Runtime module, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Combine Annotations and Swift Concurrency](https://www.massicotte.org/combine-annotations) — Those Who Swift · Issue 239 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Organizing SwiftUI Views With ToolbarContent and ToolbarContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-toolbarcontent-and-toolbarcontentbuilder) — Those Who Swift · Issue 239 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-11-05`
  **NeKI brief:** Artem explains how to clean up and modularize toolbar code, making your toolbar items reusable, easier to reason about, and better aligned with view architecture.
- [MacPacker](https://github.com/sarensw/MacPacker) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** MacPacker creates and packages macOS applications from project inputs, automating repeatable archive, signing, and distribution steps. It is useful for examining a small focused alternative to hand-written packaging scripts in local or CI release workflows.
- [porting to the Android platform](https://github.com/OpenSwiftUIProject/OpenSwiftUI/issues?q=is%3Aissue+label%3A%22platform%3A+Android%22) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** This OpenSwiftUI issue view tracks Android-platform work and compatibility questions in an open-source SwiftUI reimplementation. Follow it to assess cross-platform progress and limitations, not as evidence about Apple's private SwiftUI implementation.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — SwiftLee Weekly · Issue 294 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Refactors a large SwiftUI view into reusable components, modifiers, extensions, and a small UI library. It explains why computed view properties alone do not provide the isolation or reuse of genuine component boundaries.
- [Build, run, debug, and test your Swift apps in Zed](https://luxmentis.org/blog/ios-and-mac-apps-in-zed) — iOS Dev Weekly · Issue 731 — Article · Topics: Objective-C & Cocoa · Performance · Product Design
  **Published:** `17th October 2025`
  **NeKI brief:** Presents build, run, debug, and test your swift apps in zed for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Meeting Mind](https://meetingmind-website.web.app/) — iOS Dev Tools · iOS Dev Tools: col.or, iOS Image Optimizer, LaunchPad — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2025-10-16T18:35:25.053Z`
  **NeKI brief:** Meeting Mind provides a workflow for capturing or summarizing meeting information. Follow it for concrete note, transcription, or organization behavior, while checking privacy and processing boundaries.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 293 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-10-14T14:14:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [How to Integrate OpenSwiftUI into Your Project](https://l.fatbobman.com/w0106-02) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Documents integration steps for OpenSwiftUI, an open-source implementation of Apple’s SwiftUI concepts. Follow it when exploring compatibility boundaries and understanding which framework assumptions a non-Apple implementation must reproduce.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 106 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [Performing Search with SwiftData in a SwiftUI app](https://l.fatbobman.com/w0106-04) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Objective-C & Cocoa · Swift · SwiftData
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Demonstrates combining SwiftData queries with SwiftUI’s searchable modifier to implement app search. Follow it when connecting query predicates, search state, and result presentation without duplicating a second in-memory data source.
- [Darling](https://github.com/darlinghq/darling) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Darling provides a macOS runtime environment on Linux, including DPREFIX-style environments, package and DMG handling, and support for compiling with Apple's toolchain and SDKs. It is useful for understanding the practical limits of cross-platform macOS compatibility.
- [Accessing Swift Package Manager dependency versions at runtime](https://annema.me/blog/accessing-swift-package-manager-dependency-versions-at-runtime) — SwiftLee Weekly · Issue 291 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2025-09-30T13:58:29.000Z`
  **NeKI brief:** This article solves runtime dependency-version display by copying Package.resolved during the build and parsing it in the app. It explains why a cross-platform Xcode run-script approach can collide with code signing and offers a practical debug-screen alternative.
- [ProjectNavigator - SwiftUI File Navigation Component](https://l.fatbobman.com/w0104-08) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Provides a SwiftUI project-navigation view for macOS and iOS. Follow it when evaluating reusable navigation components and the trade-offs of introducing a custom hierarchy browser instead of relying solely on platform containers.
- [Is MVVM a bad architecture for SwiftUI?](https://www.youtube.com/watch?v=KY4jvbrlzMM) — Those Who Swift · Issue 233 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-09-24`
  **NeKI brief:** Questions MVVM's fit with SwiftUI, traces why it became popular, and separates framework habits from broader architectural goals before giving a personal recommendation. Useful when evaluating state ownership and maintainability.
- [The Northern Stars of Liquid Glass](https://l.fatbobman.com/w0103-04) — Fatbobman’s Swift Weekly · Issue 103 — Article · Topics: Liquid Glass · Objective-C & Cocoa
  **Published:** `2025-09-22T12:03:29.428Z`
  **NeKI brief:** Summarizes Liquid Glass guidance around hierarchy, harmony, and consistency from Apple’s Human Interface Guidelines. Follow it when evaluating whether a visual treatment supports structure and usability rather than merely adding translucency.
- [edge-agent: A Swift Runtime Platform for Edge Computing](https://l.fatbobman.com/w0103-07) — Fatbobman’s Swift Weekly · Issue 103 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-09-22T12:03:29.428Z`
  **NeKI brief:** Provides infrastructure for deploying robotics and edge-AI workloads with Swift-oriented tooling. Follow it when evaluating Swift beyond conventional app targets and considering deployment, device, and operational constraints for edge systems.
- [Swift Protocol Oriented Design: Build a Pluggable Data Source](https://blog.stackademic.com/swift-protocol-oriented-design-build-a-pluggable-data-source-57e7937312aa) — Those Who Swift · Issue 232 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2025-09-17`
  **NeKI brief:** Examines Swift Protocol Oriented Design: Build a Pluggable Data Source, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Northern Stars of Liquid Glass](https://captainswiftui.substack.com/p/the-northern-stars-of-liquid-glass) — Those Who Swift · Issue 232 — Article · Topics: Liquid Glass · Objective-C & Cocoa · Swift
  **Published:** `2025-09-17`
  **NeKI brief:** Danny breaks down Apple’s three core Liquid Glass principles (Hierarchy, Harmony and Consistency) showing how they guide layering, rhythm and predictability in modern SwiftUI apps and how to apply them in real-world designs.
- [Big O](https://samwho.dev/big-o) — Those Who Swift · Issue 232 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-09-17`
  **NeKI brief:** Explains Big O notation and algorithmic growth. Useful for comparing performance trade-offs and communicating complexity before choosing an implementation or data structure.
- [SwiftUI is Stifling your App’s Maintainability and Testability](https://l.fatbobman.com/w0101-02) — Fatbobman’s Swift Weekly · Issue 101 — Article · Topics: Code Quality · Swift · SwiftUI
  **Published:** `2025-09-08T12:03:42.721Z`
  **NeKI brief:** Argues for separating SwiftUI view responsibilities from oversized view models and connects that choice to maintainability and testability. Follow it when revisiting feature boundaries, dependency flow, and preview-friendly state ownership.
- [The Great Shift in Apple Development](https://captainswiftui.substack.com/p/the-great-shift-in-apple-development) — Those Who Swift · Issue 230 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-09-03`
  **NeKI brief:** Examines The Great Shift in Apple Development, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adapting Toolbar Elements to the Liquid Glass Design System](https://l.fatbobman.com/w0100-07) — Fatbobman’s Swift Weekly · Issue 100 — Article · Topics: Liquid Glass · Objective-C & Cocoa
  **Published:** `2025-09-01T12:03:36.183Z`
  **NeKI brief:** Shows how to adapt toolbar elements to the Liquid Glass design system in iOS 26. Follow it when reviewing toolbar hierarchy, material treatment, and compatibility decisions for updated Apple-platform navigation chrome.
- [Pearcleaner](https://github.com/alienator88/Pearcleaner) — iOS Dev Tools · iOS Dev Tools: WhisperKit, Swiftfin, Pearcleaner — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-08-29T06:38:01.785Z`
  **NeKI brief:** Pearcleaner is a macOS application uninstaller that identifies related support files for removal. Follow its source for concrete filesystem discovery and cleanup safeguards, while treating deletion behavior as security-sensitive.
- [UITabAccessory Backward Compatibility](https://furbo.org/2025/08/21/uitabaccessory-backward-compatibility) — Those Who Swift · Issue 229 — Article
  **Published:** `2025-08-27`
  **NeKI brief:** Discusses UITabAccessory backward compatibility. Useful for planning availability fallbacks when adopting newer UIKit tab-bar APIs across supported iOS versions.
- [FoundationModels: Tool Calling for an Assistant App](https://destiner.io/blog/post/foundation-models-tool-calling-search-app) — Those Who Swift · Issue 229 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-08-27`
  **NeKI brief:** Applies Foundation Models tool calling to an assistant-style search app. Useful for examining tool schemas, model-controlled actions, and the validation boundary before executing search operations.
- [UICoder: Fine-tuning Large Language Models to Generate User Interface Code through Automated Feedback](https://machinelearning.apple.com/research/uicoder) — iOS Dev Weekly · Issue 723 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `22nd August 2025`
  **NeKI brief:** I remember being amazed when I read Simon Willison’s 2024 LLM wrap-up post when he reported that training LLMs on generated content works well:
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP) — iOS Dev Tools · iOS Dev Tools: Votice, SwiftMCP, NetworkKit — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-08-21T17:28:34.537Z`
  **NeKI brief:** SwiftMCP provides Swift-oriented MCP implementation code. Follow its repository for concrete transport, tool, and model abstractions, then verify protocol compatibility and maintenance status before integrating it into an application.
- [Remote’s Global Life-Work Balance Index 2025](https://remote.com/resources/research/global-life-work-balance-index) — Those Who Swift · Issue 228 — Article · Topics: Concurrency · Objective-C & Cocoa
  **Published:** `2025-08-20`
  **NeKI brief:** Presents a global work-life balance index. Useful as organizational context, not as a technical Apple-platform source.
- [TextKit 2 - the promised land](https://blog.krzyzanowskim.com/2025/08/14/textkit-2-the-promised-land) — SwiftLee Weekly · Issue 285 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-08-19T14:12:01.000Z`
  **NeKI brief:** Based on years building STTextView, this critique explains where TextKit 2 improves on TextKit 1 and where it is not a silver bullet. It provides practical caution about text-layout complexity before committing an iOS or macOS editor to the newer engine.
- [STTextView](https://github.com/krzyzanowskim/STTextView) — Fatbobman’s Swift Weekly · Issue 98 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-08-18T12:03:30.201Z`
  **NeKI brief:** STTextView is a TextKit 2-based text editor that exposes the practical gaps encountered in Apple's newer text system. Use it when building editor-like macOS UI and needing a tested reference for selection, layout, and editing behavior.
- [more Swift and SwiftUI](https://blog.timac.org/2024/1208-state-of-swift-and-swiftui-ios18) — iOS Dev Weekly · Issue 722 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `15th August 2025`
  **NeKI brief:** Surveys how Apple used Swift and SwiftUI in iOS 18, connecting framework capabilities to production features. Useful for identifying platform-supported patterns before designing equivalent app architecture.
- [What’s New in the Lambda V2 Runtime](https://swifttoolkit.dev/posts/lambda-v2) — iOS Dev Weekly · Issue 722 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `15th August 2025`
  **NeKI brief:** A couple of weeks ago, the SWWG announced this, and there are some nice new features, including streaming responses and spawning background workers. This week, I saw that Natan Rolnik has also put together a quick guide on how to use it, including a section…
- [announced](https://forums.swift.org/t/swift-aws-lambda-runtime-v2-0-0-beta-1-is-available/81445) — iOS Dev Weekly · Issue 722 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `15th August 2025`
  **NeKI brief:** The page covers “announced” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [NavigationStack Deep Linking in Large SwiftUI Apps](https://medium.com/@wesleymatlock/%EF%B8%8F-navigationstack-deep-linking-in-large-swiftui-apps-439a1ce77337) — Those Who Swift · Issue 227 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2025-08-13`
  **NeKI brief:** Examines NavigationStack Deep Linking in Large SwiftUI Apps, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [AI Use Cases](https://github.com/Engineer1999/A-Curated-List-of-ML-System-Design-Case-Studies) — Those Who Swift · Issue 226 — Source repository · Topics: AI Development · Architecture · Developer Tools
  **Published:** `2025-08-06`
  **NeKI brief:** Collects machine-learning system-design case studies. Useful for broadening architecture review vocabulary around data, models, serving, and operational trade-offs.
- [Flux pattern in Swift](https://swiftandpizza.wpcomstaging.com/flux-in-swift) — SwiftLee Weekly · Issue 282 — Article · Topics: Objective-C & Cocoa · Product Design · Swift
  **Published:** `2025-07-29T14:14:45.000Z`
  **NeKI brief:** Presents Flux pattern in Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — SwiftLee Weekly · Issue 280 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Reaper: An open-source SDK for finding dead code](https://blog.sentry.io/an-open-source-sdk-for-finding-dead-code) — iOS Dev Weekly · Issue 717 — Article · Topics: Objective-C & Cocoa
  **Published:** `11th July 2025`
  **NeKI brief:** Examines How Duolingo deleted 1% of their code using this Open Source tool in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [FluidAudio](https://github.com/FluidInference/FluidAudio) — iOS Dev Tools · iOS Dev Tools: FluidAudio, PlayCover, FlashSpace — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2025-07-10T20:12:55.159Z`
  **NeKI brief:** FluidAudio provides Swift audio and speech-processing components. Follow its source for concrete local inference or signal-processing workflows, while checking model requirements, performance characteristics, and supported Apple platforms.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 92 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-07-07T12:01:56.119Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 278 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Xcode
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Rewriting a 12 Year Old Objective-C iOS App with Claude Code](https://twocentstudios.com/2025/06/22/vinylogue-swift-rewrite) — iOS Dev Weekly · Issue 716 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `27th June 2025`
  **NeKI brief:** Examines Rewriting a 12 Year Old Objective-C iOS App with Claude Code, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [late February](https://devclass.com/2025/02/27/anthropic-previews-claude-code-agentic-coding-capable-but-costly) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `27th June 2025`
  **NeKI brief:** Examines ¹ Claude Code entered “research preview” in late February and GitHub talked about the Copilot agent just a month ago. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [just a month ago](https://github.blog/news-insights/product-news/github-copilot-meet-the-new-coding-agent) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `27th June 2025`
  **NeKI brief:** The GitHub Blog article introduces GitHub Copilot's coding agent and explains its workflow for delegating software-engineering tasks.
- [MoPromoteKit](https://github.com/mkhasson97/MoPromoteKit) — iOS Dev Tools · iOS Dev Tools: Create Custom Symbols, MoPromoteKit, SyntaxKit — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-06-26T19:24:23.404Z`
  **NeKI brief:** MoPromoteKit provides promotion or marketing integration for mobile applications. Follow its repository for concrete API and campaign workflows, while verifying supported providers, privacy, and maintenance before adoption.
- [Firecrawl](https://www.firecrawl.dev/) — iOS Dev Tools · iOS Dev Tools: Create Custom Symbols, MoPromoteKit, SyntaxKit — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2025-06-26T19:24:23.404Z`
  **NeKI brief:** Firecrawl provides web-crawling and content-extraction APIs. Follow its documentation for concrete crawling, scraping, and structured-output workflows, while reviewing robots, privacy, and rate-limit boundaries.
- [Memory Efficiency in iOS: Reducing footprint and beyond](https://open.substack.com/pub/antongubarenko/p/memory-efficiency-in-ios-reducing?r=21t43r&showWelcomeOnShare=false) — Those Who Swift · Issue 220 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `2025-06-25`
  **NeKI brief:** Examines memory efficiency in iOS. Useful for connecting allocation, object lifetime, and workload measurement to practical footprint reduction rather than optimizing by guesswork.
- [WWDC25: Highlights as an iOS Developer](https://www.youtube.com/watch?v=__RoIeqfrSY) — Those Who Swift · Issue 219 — Video · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-19`
  **NeKI brief:** Reviews WWDC25: Highlights as an iOS Developer. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Bandit - Online Security (or Not) Game](https://overthewire.org/wargames/bandit/bandit0.html) — Those Who Swift · Issue 217 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **Published:** `2025-06-18`
  **NeKI brief:** Provides the Bandit security wargame. Useful for learning command-line security concepts through progressive exercises, while keeping its intentionally vulnerable environment separate from production systems.
- [Essential xcodebuild Commands for iOS Developers](https://medium.com/@awasthi027.ashish/essential-xcodebuild-commands-for-ios-developers-9ff101783ce2) — Those Who Swift · Issue 195 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Xcode
  **Published:** `2025-06-18`
  **NeKI brief:** Examines Essential xcodebuild Commands for iOS Developers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [App Store SEO Algorithm Change](https://appfigures.com/resources/guides/app-store-algorithm-update-2025) — iOS Dev Weekly · Issue 714 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `13th June 2025`
  **NeKI brief:** Examines We reverse engineered a BIG change to the App Store that. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [OAuthKit](https://github.com/codefiesta/OAuthKit) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: Architecture · Combine & Reactive Programming · Swift
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** OAuthKit provides an observable Swift framework for OAuth 2.0 authorization flows, centralizing state and callback handling. Useful for comparing a reusable authentication boundary with endpoint-specific browser-session code.
- [Updates to Apple’s On-Device and Server Foundation Language Models](https://machinelearning.apple.com/research/apple-foundation-models-2025-updates) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Apple's research update describes the Foundation Models family and 2025 model changes. Use it for technical model context and capability boundaries, while relying on platform documentation for app-facing APIs and availability.
- [All New Frameworks Presented at WWDC 25](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc25) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Catalogues frameworks introduced at WWDC 2025. Use it as a broad inventory for technology scouting, then prioritize a concrete use case and consult the corresponding primary API documentation.
- [Marco Eidinger](https://hashnode.com/@MarcoEidinger) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Marco Eidinger's Hashnode profile collects articles and experiments around developer tooling and Apple-platform technologies. Use it as an author index for related posts, evaluating each individual article rather than treating the profile as a single technical source.
- [The evolution of native engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — SwiftUI Weekly · SwiftUI Weekly - Issue #217 — Article · Topics: Architecture · Composable Architecture · Concurrency
  **Published:** `2025-06-02T12:56:10.176Z`
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [Harmonize](https://github.com/perrystreetsoftware/Harmonize) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Architecture · Swift · Testing
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Harmonize coordinates shared state and communication across SwiftUI views, addressing the friction of passing bindings and environment values through deeper hierarchies. Its implementation is a concrete reference for reducing view wiring while keeping data flow explicit.
- [AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: App Services & Extensions · Swift · Testing
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [MenuWithAView](https://github.com/Aeastr/MenuWithAView) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** MenuWithAView adds custom accessory content to SwiftUI context menus based on public implementation techniques. Use it when menu actions need richer inline visual context, while testing behavior across menu presentation environments.
- [LogUI](https://eclecticlight.co/2025/03/14/browse-your-macs-log-with-logui) — Fatbobman’s Swift Weekly · Issue 83 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-05-12T12:02:48.422Z`
  **NeKI brief:** Shows how LogUI opens multiple views over unified macOS logs with independent searches and filters. Use it when application launch noise makes Console difficult to navigate and parallel focused log queries speed diagnosis.
- [Product for Engineers: Helping engineers flex their product muscles](https://go.posthog.com/tws-may8) — Those Who Swift · Issue 213 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-05-07`
  **NeKI brief:** Promotes product-engineering content. Useful as a discovery lead, but the landing page itself is not a focused technical article.
- [SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-colours-and-images-in-a-swift-package) — Those Who Swift · Issue 213 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-05-07`
  **NeKI brief:** Examines SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Enforce Your Architecture in Swift with Harmonize](https://itnext.io/goodbye-code-reviews-hello-harmonize-0a49e2872b5a) — iOS Dev Weekly · Issue 710 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2nd May 2025`
  **NeKI brief:** Presents enforce your architecture in swift with harmonize for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [GrowASO](https://www.growaso.com/) — iOS Dev Tools · iOS Dev Tools: GrowASO, XcodeBuild MCP, Compot — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2025-05-01T14:50:23.226Z`
  **NeKI brief:** GrowASO provides App Store Optimization and growth tooling. Follow it for concrete keyword, listing, and performance-analysis workflows, while treating market data as time-sensitive commercial context.
- [ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — SwiftLee Weekly · Issue 269 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-04-29T14:18:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ErrorKit](https://github.com/FlineDev/ErrorKit) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** ErrorKit is an Apple-platform error presentation layer that turns failures into user-facing alerts, sheets, or notifications while keeping error handling composable. The source helps evaluate a centralized approach to reporting errors across SwiftUI and UIKit flows.
- [The first newsletter for product engineers](https://go.posthog.com/idt-apr24) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** This PostHog resource link leads to product analytics material shared with iOS Dev Tools. Use it to investigate event instrumentation and product insights, verifying the linked content, SDK behavior, consent model, and data-retention settings.
- [Apple Rebrands Search Ads as Apple Ads](https://searchengineland.com/apple-search-ads-apple-ads-454356) — Those Who Swift · Issue 211 — Article · Topics: App Distribution & Store Operations · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-04-24`
  **NeKI brief:** Reports Apple’s rebranding of Search Ads. Useful for App Store acquisition context, while current campaign behavior requires official documentation.
- [Crafting Effective SwiftUI ViewModifiers](https://www.youtube.com/watch?v=XU7wdjPCXLw) — Those Who Swift · Issue 210 — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-04-16`
  **NeKI brief:** Reviews Crafting Effective SwiftUI ViewModifiers. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [26th March 2005](https://en.wikipedia.org/wiki/GNU_Bazaar) — iOS Dev Weekly · Issue 707 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th April 2025`
  **NeKI brief:** Examines GNU Bazaar - Wikipedia. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [7th April](https://en.wikipedia.org/wiki/Git) — iOS Dev Weekly · Issue 707 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th April 2025`
  **NeKI brief:** The page covers “7th April” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [19th April](https://en.wikipedia.org/wiki/Mercurial) — iOS Dev Weekly · Issue 707 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th April 2025`
  **NeKI brief:** Presents 19th April, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Complexity 0: Introduction](https://dmtopolog.com/complexity-0-introduction) — Those Who Swift · Issue 209 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `2025-04-09`
  **NeKI brief:** Introduces a series on software complexity. Useful for establishing shared vocabulary before diagnosing complexity in a codebase or assuming abstraction alone will reduce it.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [Swift 6.1 Released](https://www.swift.org/blog/swift-6.1-released) — iOS Dev Weekly · Issue 706 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `4th April 2025`
  **NeKI brief:** The community has already shared some excellent insights. If you’re looking to dive deeper, we highly recommend checking out this video by Vincent!
- [The first newsletter for product engineers](https://go.posthog.com/tws-mar27) — Those Who Swift · Issue 208 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-04-02`
  **NeKI brief:** Promotes a product-engineering newsletter. Useful only as a discovery lead; specific implementation claims should be followed to their original technical source.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [How We Used LLMs to Help Us Find the Perfect Piece of Land for Our Future Home](https://krausefx.com//blog/how-we-used-llms-to-help-us-find-the-perfect-piece-of-land-for-our-future-home) — Those Who Swift · Issue 207 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2025-03-28`
  **NeKI brief:** Describes using LLMs to search for a property. Useful as an automation case study for tool orchestration and human review boundaries.
- [The Composable Architecture: How Architectural Design Decisions Influence Performance](https://www.swiftyplace.com/blog/the-composable-architecture-performance) — SwiftUI Weekly · SwiftUI Weekly - Issue #211 — Article · Topics: Architecture · Objective-C & Cocoa · Performance
  **Published:** `2025-03-25T13:30:35.672Z`
  **NeKI brief:** Examines performance implications of The Composable Architecture in SwiftUI, including reducer and view update costs. Useful for measuring architectural overhead in realistic workloads rather than assuming framework use is free or prohibitive.
- [📦 FREE Webinar: CI/CD for Swift Packages](https://streamyard.com/watch/62AzM2xGJ2hB) — iOS CI Newsletter · Issue 64 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `2025-03-23T00:00:00.000Z`
  **NeKI brief:** Examines FREE Webinar: CI/CD for Swift Packages in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Hex](https://github.com/kitlangton/Hex) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Architecture · Composable Architecture · Developer Tools
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Hex provides Swift utilities or UI for hexadecimal data and representation. Follow its source for concrete conversion and formatting behavior, while checking byte-order, validation, and platform integration details.
- [Keep It Shot](https://keepitshot.com/) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Keep It Shot provides a screenshot-oriented capture or organization workflow. Follow it for concrete image-capture and sharing behavior, while treating promotional claims as contextual rather than technical guidance.
- [Viz](https://github.com/alienator88/Viz) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Developer Tools · Graphics, Media & Games · macOS & AppKit
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Viz is a GitHub project for visualizing or inspecting data on Apple platforms. Follow its source and examples for concrete rendering and interaction patterns, while verifying the project’s supported frameworks and current maintenance.
- [Let’s Vision](https://letsvision.swiftgg.team/) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Let’s Vision is an Apple-platform developer event in Shanghai, listed with its March dates. Use it to locate conference talks and community material around iOS and visionOS, not as a normative implementation source.
- [InjectionIII](https://apps.apple.com/us/app/injectioniii/id1380446739) — iOS Dev Tools · iOS Dev Tools: TranslateKit, SwiftSoup, InjectionIII — Article · Topics: Objective-C & Cocoa · Personal Essays · Swift
  **Published:** `2025-02-20T19:09:31.201Z`
  **NeKI brief:** InjectionIII adds hot reloading to Swift and Objective-C iOS, tvOS, and macOS projects, allowing implementation and SwiftUI body changes without restarting. Follow it for rapid iteration during UI and behavior development.
- [Swift on Android Community Workgroup](https://forums.swift.org/t/swift-on-android-working-group/77780) — Fatbobman’s Swift Weekly · Issue 71 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** Tracks the Swift on Android working group's scope and coordination. Use it to distinguish language/runtime portability from UIKit availability when assessing a shared Swift codebase for Android targets.
- [Starview](https://indiegoodies.com/starview) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy - iOS Dev Tools — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Starview is a developer-oriented utility or product page. Follow it for the concrete workflow it presents, while verifying supported platforms, implementation details, and maintenance before treating it as technical reading.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy - iOS Dev Tools — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [🍎 Running Xcode in unsupported macOS versions](https://marcelvoss.com/2025/tricking-xcode-into-running-on-an-unsupported-macos) — iOS CI Newsletter · Issue 61 — Article · Topics: Apple Platform Ecosystem · Personal Essays · Xcode
  **Published:** `2025-02-09T00:00:00.000Z`
  **NeKI brief:** Examines Running Xcode in unsupported macOS versions in the context of Apple Platform Ecosystem and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [How to Do Apple Search Ads (ASA) Right and Grow Your Downloads](https://www.youtube.com/watch?v=W6_bN3AZo_s) — iOS Dev Weekly · Issue 698 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `7th February 2025`
  **NeKI brief:** Examines ► Search Ads Insights: https://appfigures.com/reports/competitor-search-ads► Keyword Inspector: https://appfigures.com/reports/keyword-inspector► Start a FRE. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ELEGNT](https://machinelearning.apple.com/research/elegnt-expressive-functional-movement) — iOS Dev Weekly · Issue 698 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `7th February 2025`
  **NeKI brief:** Staff iOS Engineer @ Outsmart College, Inc. – Team up with former Duolingo execs to tackle long-standing challenges in higher education! Outsmart is looking for a self-organized Staff iOS Engineer with a strong background in UIKit and SwiftUI development…
- [ZIP Foundation](https://github.com/weichsel/ZIPFoundation) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Provides the public source repository for ZIP Foundation. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [DevCleaner](https://github.com/vashpan/xcode-dev-cleaner) — iOS Dev Tools · iOS Dev Tools: SwiftUIX, Vapor, DevCleaner — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2025-01-30T15:53:21.682Z`
  **NeKI brief:** DevCleaner is a macOS tool for finding and removing development artifacts. Follow its source for concrete path discovery and cleanup rules, while verifying exactly which Xcode, simulator, and build files it can delete.
- [📦 The Tuist Swift Package Manager Registry](https://tuist.dev/blog/2025/01/22/announcing-tuist-registry) — iOS CI Newsletter · Issue 60 — Article · Topics: Apple Platform Ecosystem · Swift · Swift Package Manager
  **Published:** `2025-01-28T00:00:00.000Z`
  **NeKI brief:** Examines The Tuist Swift Package Manager Registry in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SE-0292](https://forums.swift.org/t/se-0292-package-registry-service/42623) — Fatbobman’s Swift Weekly · Issue 68 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-01-27T01:05:46.208Z`
  **NeKI brief:** SE-0292 defines a package-registry protocol and service model for SwiftPM dependencies. Follow it when designing package distribution, authentication, and version-resolution infrastructure beyond Git URL fetching.
- [Mogenerator](https://github.com/rentzsch/mogenerator) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Core Data · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** mogenerator reads a Core Data model and generates separate machine and human subclasses for managed objects. Use it in legacy Core Data projects that need repeatable typed accessors while preserving hand-written behavior across model regeneration.
- [project](https://github.com/arrinal/ios-clean-architecture-project) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Offers a concrete iOS Clean Architecture project layout rather than a conceptual diagram. Follow it to inspect boundaries between presentation, domain, and data layers and judge the ceremony against a real app.
- [backend service](https://github.com/arrinal/sample-service-swift-vapor) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Pairs a Swift service example with Vapor, making the repository useful for tracing request handling and application-layer separation. Follow it when comparing server-side Swift structure with client architecture conventions.
- [Creating a debounced search context for performant SwiftUI searches](https://danielsaidi.com/blog/2025/01/08/creating-a-debounced-search-context-for-performant-swiftui-searches) — SwiftLee Weekly · Issue 254 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Presents Creating a debounced search context for performant SwiftUI searches, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — SwiftLee Weekly · Issue 254 — Source repository · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0455SwiftPM @testable build setting](https://github.com/apple/swift-evolution/blob/main/proposals/0455-swiftpm-testable-build-setting.md) — SwiftLee Weekly · Issue 254 — Source repository · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0455SwiftPM @testable build setting. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Nimble](https://github.com/Quick/Nimble) — iOS Dev Tools · iOS Dev Tools: Finch, Swift-mod, Nimble — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-01-02T17:37:26.914Z`
  **NeKI brief:** Provides the public source repository for Nimble. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [The latest research results announced by Professor Chen Gang's team in China](https://www.stdaily.com/web/gdxw/2024-11/29/content_266525.html) — Fatbobman’s Swift Weekly · Issue 63 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `2024-12-23T12:01:34.355Z`
  **NeKI brief:** Provides contextual background on The latest research results announced by Professor Chen Gang's team in China, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [They paid me sixty dollars, so I wore a tie](https://stevejobsarchive.com/exhibits/objects-of-our-life) — iOS Dev Weekly · Issue 692 — Article · Topics: Objective-C & Cocoa
  **Published:** `20th December 2024`
  **NeKI brief:** Presents they paid me sixty dollars, so i wore a tie for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [Orta Therox](https://m.webtoo.ls/@orta) — iOS Dev Weekly · Issue 690 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th December 2024`
  **NeKI brief:** Here’s Orta Therox with an update on the team’s plans for maintaining the project. This may be the beginning of the end for CocoaPods, but we’re still two years away from the end, so you have plenty of time to prepare. It’s also worth noting that the project…
- [Working with Natural Language frameworkLearn how to use the Natural Language framework to analyze text in real time.Artem Novichkov](https://www.artemnovichkov.com/blog/working-with-natural-language-framework?ref=ioscodereview.com) — iOS Code Review · Issue 74 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-12-04T11:30:50.000Z`
  **NeKI brief:** Examines Working with Natural Language frameworkLearn how to use the Natural Language framework to analyze text in real… in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [CoreData Studio](https://apps.apple.com/us/app/coredata-studio/id6670322925) — iOS Dev Tools · iOS Dev Tools: CoreData Studio, Swift Crypto, StatusBuddy — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `2024-11-28T18:43:21.075Z`
  **NeKI brief:** CoreData Studio is a native SQLite viewer, editor, and inspector for Core Data and SwiftData stores. Follow it for a concrete debugging workflow around locating, examining, and modifying local persistence data.
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** Mohammad describes in detail the SwiftUI’s environment explaining how it facilitates the sharing of state across views. It begins by exploring the scope and injection of environment objects within the view hierarchy, delves into their behavior during view…
- [Security research on Private Cloud Compute](https://security.apple.com/blog/pcc-security-research) — iOS Dev Weekly · Issue 686 — Article · Topics: Objective-C & Cocoa · Security & Privacy
  **Published:** `8th November 2024`
  **NeKI brief:** Documents Apple security research findings and analysis around Private Cloud Compute. Useful for understanding the threat-model and verification questions behind cloud-assisted privacy features, with current platform claims checked against Apple’s latest security documentation.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** A configurable logging framework for Apple platforms that routes messages to destinations such as console, files, or remote servers. Its filtering and low-overhead logging model is useful when designing diagnostics that remain practical in production builds.
- [Siamak (Ash) Ashrafi](https://sessionize.com/Ash) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents Siamak (Ash) Ashrafi, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents guide to app architecture for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [learning pathway](https://developer.android.com/courses/pathways/android-architecture) — iOS Dev Weekly · Issue 685 — Tutorial · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents learning pathway for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Carthage](https://github.com/Carthage/Carthage) — iOS Dev Tools · iOS Dev Tools: FeaturesKit, SwipeActions, Carthage — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-10-24T17:09:28.334Z`
  **NeKI brief:** Carthage resolves and builds Cocoa dependencies as frameworks without modifying the Xcode project file. Use it when comparing decentralized binary/framework integration with Swift Package Manager, especially for older projects with explicit dependency wiring.
- [Modular Navigation in SwiftUI: A Comprehensive Guide](https://ericsspace.com/articles/modular-navigation-in-swiftui-a-comprehensive-guide) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Presents a modular navigation architecture for SwiftUI with separated route and feature concerns. Useful when deep links and navigation flows outgrow a single view's path handling.
- [Mango Baby](https://machinelearning.apple.com/research/depth-pro?ref=createwithswift.com) — Create with Swift · Issue 32 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2024-10-18T15:00:03.000Z`
  **NeKI brief:** Mango Baby. This link is retained as a technical reading lead for Apple-platform development.
- [Parchment](https://github.com/rechsteiner/Parchment) — iOS Dev Tools · iOS Dev Tools: AboutKit, Swift Async Algorithms, Parchment — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-10-17T15:13:39.704Z`
  **NeKI brief:** Parchment provides a customizable paging or segmented navigation component for iOS. Follow its source for concrete page-controller, layout, and gesture behavior, while checking UIKit and Swift compatibility.
- [PragmaConf](https://pragmaconference.com/) — iOS Dev Tools · iOS Dev Tools: AboutKit, Swift Async Algorithms, Parchment — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `2024-10-17T15:13:39.704Z`
  **NeKI brief:** Provides the Pragmaconference event hub for talks and community sessions about Apple development. Use it to discover practitioner perspectives and verify session details before relying on a conference presentation.
- [Quick](https://github.com/Quick/Quick) — iOS Dev Tools · iOS Dev Tools: Jazzy, Concentric Onboarding, Quick — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-10-10T16:40:59.907Z`
  **NeKI brief:** Quick adds a behavior-driven testing DSL for Swift and Objective-C, organizing examples with describe/context blocks and readable expectations. Its companion Nimble matcher style is useful when comparing specification-oriented tests with XCTest assertions.
- [Building Large Scale Apps SwiftuiBuilding Large-Scale Apps with SwiftUI: A Guide to Modular ArchitectureAzamSharpMohammad Azam](https://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html?ref=ioscodereview.com) — iOS Code Review · Issue 71 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-09-24T10:08:19.000Z`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [📱 Install older simulator runtimes on CI/CD](https://testableapple.com/install-ios-simulator-runtimes) — iOS CI Newsletter · Issue 51 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Testing
  **Published:** `2024-09-23T00:00:00.000Z`
  **NeKI brief:** Examines Install older simulator runtimes on CI/CD in the context of CI/CD & Automation and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 GitHub-hosted Linux and Windows ARM64 runners are now available](https://github.blog/changelog/2024-09-03-github-actions-arm64-linux-and-windows-runners-are-now-generally-available) — iOS CI Newsletter · Issue 50 — Article · Topics: Architecture · Developer Tools · Product Design
  **Published:** `2024-09-08T00:00:00.000Z`
  **NeKI brief:** Examines GitHub-hosted Linux and Windows ARM64 runners are now available in the context of Architecture and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Orta Therox announcing that CocoaPods is in maintenance mode](https://blog.cocoapods.org/CocoaPods-Support-Plans) — iOS Dev Weekly · Issue 676 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th August 2024`
  **NeKI brief:** Examines I don’t know how I missed Orta Therox announcing that CocoaPods is in maintenance mode a couple of weeks ago, but I did! Or, to be accurate, the post clarifies that CocoaPods has been in maintenance for a while now: Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Further research from Peking University in 2018 explored the correlation between update frequency and app ratings in the Google Play Store](https://arxiv.org/pdf/1707.06022) — iOS CI Newsletter · Issue 49 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines Further research from Peking University in 2018 explored the correlation between update frequency and app… in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SwiftDeps](https://swiftdeps.com/) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** SwiftDeps visualizes and manages dependencies among Xcode project components, helping teams inspect architectural connections. Use it when reviewing modularization or dependency direction and when generated project structure needs a more navigable map.
- [😱 Vulnerabilities found in CocoaPods](https://www.evasec.io/blog/eva-discovered-supply-chain-vulnerabities-in-cocoapods) — iOS CI Newsletter · Issue 46 — Article · Topics: Concurrency · Objective-C & Cocoa · Security & Privacy
  **Published:** `2024-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Vulnerabilities found in CocoaPods in the context of Concurrency and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Orta’s blog post explaining the patches](http://blog.cocoapods.org/CocoaPods-Trunk-RCEs-2023) — iOS CI Newsletter · Issue 46 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Orta’s blog post explaining the patches in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [StuVision](https://buttondown.email/varrall/archive) — iOS Dev Weekly · Issue 669 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `12th July 2024`
  **NeKI brief:** So the million (or billion) dollar question is, will third-party developers choose to invest that time and effort? I’ve been keeping a close eye on the community since the US launch, and have noticed that the number of people writing about development in…
- [Rand Fishkin](https://sparktoro.com/blog/author/rand) — Fatbobman’s Swift Weekly · Issue 39 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `2024-07-08T12:00:38.197Z`
  **NeKI brief:** Provides contextual background on Rand Fishkin, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [fixed quickly](https://blog.cocoapods.org/CocoaPods-Trunk-RCEs-2023) — iOS Dev Weekly · Issue 668 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th July 2024`
  **NeKI brief:** Examines Orta’s blog post explaining the patches in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧐 How GitHub reduced testing time for iOS apps with new runner features](https://github.blog/2024-06-03-how-github-reduced-testing-time-for-ios-apps-with-new-runner-features) — iOS CI Newsletter · Issue 44 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2024-06-16T00:00:00.000Z`
  **NeKI brief:** Examines How GitHub reduced testing time for iOS apps with new runner features in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [this article on Private Cloud Compute](https://security.apple.com/blog/private-cloud-compute) — iOS Dev Weekly · Issue 665 — Article · Topics: Objective-C & Cocoa · Security & Privacy
  **Published:** `14th June 2024`
  **NeKI brief:** Explains Apple’s Private Cloud Compute security model and the design principles used to keep cloud processing verifiable and privacy-preserving. Useful for grounding discussions of on-device versus server-assisted intelligence in Apple’s own security rationale.
- [and others](https://machinelearning.apple.com/research/introducing-apple-foundation-models) — iOS Dev Weekly · Issue 665 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Security & Privacy
  **Published:** `14th June 2024`
  **NeKI brief:** We are constantly challenged to give up aspects of privacy with each cookie permission click-through and every pundit saying that privacy is dead. Apple’s first job is to show that it doesn’t need to be that way. Once that’s done, it must prove that Apple…
- [✂️ Find and remove unused code with Periphery](https://samwize.com/2024/05/30/remove-unused-code-with-periphery) — iOS CI Newsletter · Issue 43 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Examines Find and remove unused code with Periphery in the context of AI Development and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Periphery](https://github.com/peripheryapp/periphery) — iOS CI Newsletter · Issue 43 — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Periphery statically analyzes Swift projects to find unused declarations and code paths. Use its report to drive cleanup reviews in large codebases, but validate dynamic dispatch, reflection, and externally referenced symbols before removal.
- [Sw!ftalyzer](https://swiftalyzer.com/) — iOS Dev Tools · iOS Dev Tools: Sw!ftalyzer, Invoice Maker, SQLite.swift — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-05-30T15:20:30.896Z`
  **NeKI brief:** Swiftalyzer is a Swift code-analysis tool intended to surface project structure or quality signals. Use it as a discovery lead for static analysis, verifying rule coverage, false-positive handling, performance, and integration with the project’s review pipeline.
- [15th of March, the Swift language team created the release branch for Swift 6](https://forums.swift.org/t/swift-6-0-release-process/70220) — iOS CI Newsletter · Issue 42 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** post. This link is retained as a technical reading lead for Apple-platform development.
- [making snapshots from this branch regularly available for download](https://www.swift.org/download) — iOS CI Newsletter · Issue 42 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** Examines making snapshots from this branch regularly available for download in the context of Objective-C & Cocoa and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Pointfree's SyncUps App: A Great Example Architecture for a SwiftUI App](https://rodschmidt.com/posts/syncups) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Analyses Point-Free's SyncUps sample architecture and feature boundaries. Useful for studying a complete SwiftUI application structure before adapting its patterns selectively.
- [SyncUps](https://github.com/pointfreeco/syncups) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Source repository · Topics: Architecture · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Provides the SyncUps sample repository with SwiftUI architecture, persistence, and tests. Useful for inspecting concrete implementation trade-offs rather than relying on abstract diagrams.
- [100 Push-Ups a Day Challenge](https://www.cancerresearchuk.org/get-involved/find-an-event/100-push-ups-a-day-challenge) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Provides contextual background on 100 Push-Ups a Day Challenge, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [Migrating from CocoaPods to Tuist at Playtomic](https://dev.to/playtomic/migrating-from-cocoapods-to-tuist-at-playtomic-26ed?issue=031) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Describes a production migration from CocoaPods to Tuist, including project-generation and dependency-management implications. Follow it when planning a build-system transition and identifying CI or target-configuration risks.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience) — SwiftUI Weekly · SwiftUI Weekly - Issue #185 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T13:22:31.904Z`
  **NeKI brief:** Reflects on three years using TCA at team scale, emphasizing its learning curve, release churn, migration cost, reducer growth, and platform impedance. Useful when weighing TCA's testing and composition benefits against organizational complexity.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [✂️ Finding and deleting dead code using ReaperAI](https://www.emergetools.com/reaperai) — iOS CI Newsletter · Issue 41 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2024-05-05T00:00:00.000Z`
  **NeKI brief:** Examines Finding and deleting dead code using ReaperAI in the context of AI Development and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [fully developed using the Swift](https://www.theverge.com/2024/4/30/24144183/arc-browser-windows-launch-features-availability?ref=createwithswift.com) — Create with Swift · Issue 11 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-05-03T15:00:23.000Z`
  **NeKI brief:** On another interesting turn of events, the browser Arc, fully developed using the Swift language, released its Windows version this week. What makes it interesting is that the tools they used are fully open-source and available on GitHub. Why not take a look…
- [fully open-source and available on GitHub](https://github.com/thebrowsercompany/swift-winrt?ref=createwithswift.com) — Create with Swift · Issue 11 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-05-03T15:00:23.000Z`
  **NeKI brief:** On another interesting turn of events, the browser Arc, fully developed using the Swift language, released its Windows version this week. What makes it interesting is that the tools they used are fully open-source and available on GitHub. Why not take a look…
- [Swift Server Side Meetup #1](https://www.youtube.com/watch?v=FULMRV3wIKg) — iOS Dev Weekly · Issue 658 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** If you missed Wednesday’s inaugural Swift Server Side Meetup, the good news is that YouTube has archived it! Join members of the Swift Server Workgroup for two presentations and plenty of Q&A. I wasn’t able to attend the live session, but from the look of…
- [Swift Server Workgroup](https://www.swift.org/sswg) — iOS Dev Weekly · Issue 658 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Professional Grade Application Protection for Swift and Objective-C iOS Apps](https://www.vpdae.com/redirect/e9xwl532e60eyhhks87um6yabmy) — SwiftUI Weekly · SwiftUI Weekly - Issue #183 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2024-04-22T17:42:59.039Z`
  **NeKI brief:** Promotes application protection for Swift and Objective-C binaries. Useful only as security-product context when assessing threat models and tooling claims for shipped apps.
- [📱 A comparison of top iOS beta app distribution](https://www.instabug.com/blog/comparison-between-top-beta-app-distribution-tools) — iOS CI Newsletter · Issue 40 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Examines A comparison of top iOS beta app distribution in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [distribution service AppCenter is scheduled for retirement on the 31st of March of 2025](https://learn.microsoft.com/en-gb/appcenter/retirement) — iOS CI Newsletter · Issue 40 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Examines distribution service is scheduled for retirement on the 31st of March of 2025 in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) — Fatbobman’s Swift Weekly · Issue 27 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2024-04-15T22:00:50.399Z`
  **NeKI brief:** Ferret-UI studies grounded mobile-interface understanding with multimodal language models. Follow it for research context on extracting actionable UI structure from screenshots and interaction traces, distinct from ordinary OCR.
- [In Search of a Smooth Scroll](https://byla.lt/posts/in-search-of-smooth-scroll) — SwiftUI Weekly · SwiftUI Weekly - Issue #181 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-04-09T05:33:14.059Z`
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind In Search of a Smooth Scroll. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Recreating Apple’s beautiful visionOS search bar](https://christianselig.com/2024/03/recreating-visionos-search-bar) — iOS Dev Weekly · Issue 654 — Article · Topics: Objective-C & Cocoa · Spatial Computing · Swift
  **Published:** `29th March 2024`
  **NeKI brief:** Presents recreating apple’s beautiful visionos search bar for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Tooling on Windows](https://speakinginswift.substack.com/p/swift-tooling-windows-edition) — iOS Dev Weekly · Issue 652 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `15th March 2024`
  **NeKI brief:** Examines Productivity on every platform - a deep dive on the ways we're writing Swift code on Windows, and improving the developer experience along the way. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🚨 Errors while archiving an app with Firebase and Xcode 15.3](https://github.com/firebase/firebase-ios-sdk/issues/12441) — iOS CI Newsletter · Issue 37 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2024-03-10T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Errors while archiving an app with Firebase and Xcode 15.3, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [this awesome article](https://blog.eidinger.info/why-and-how-to-adopt-actionscheckoutv3-in-your-github-action-workflow) — iOS CI Newsletter · Issue 36 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Examines actions/checkout GitHub action updated! in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift 6.0 Release Process](https://forums.swift.org/t/70220) — iOS Dev Weekly · Issue 649 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `23rd February 2024`
  **NeKI brief:** Examines Swift 6.0 Release Process This post describes the release process, and estimated schedule for Swift 6.0. Snapshots of Swift 6.0 Downloadable snapshots of the Swift 6.0 release bran. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [On-device ML research with MLX and Swift](https://www.swift.org/blog/mlx-swift) — iOS Dev Weekly · Issue 649 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `23rd February 2024`
  **NeKI brief:** Presents on-device ml research with mlx and swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Pastepal](https://apps.apple.com/us/app/clipboard-manager-pastepal/id1503446680) — iOS Dev Tools · iOS Dev tools: Haptics, CodeEdit, Pastepal — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-02-22T14:00:50.078Z`
  **NeKI brief:** PastePal stores and searches clipboard history locally, with optional iCloud synchronization and filters by type, collection, and date. Its page offers a concrete reference for privacy-aware cross-device clipboard workflows.
- [🧰 Compile and distribute your iOS SDK as a pre-compiled xcframework](https://krausefx.com/blog/how-to-automaticallycompile-and-distribute-your-ios-sdk-as-a-pre-compiled-xcframework) — iOS CI Newsletter · Issue 35 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa
  **Published:** `2024-02-11T00:00:00.000Z`
  **NeKI brief:** Examines Compile and distribute your iOS SDK as a pre-compiled xcframework in the context of CI/CD & Automation and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Stuart Varrall’s recent article on Inspiring Apple Vision Pro Apps](https://buttondown.email/varrall/archive/inspiring-apple-vision-pro-apps) — iOS Dev Weekly · Issue 647 — Article · Topics: Objective-C & Cocoa · Spatial Computing
  **Published:** `9th February 2024`
  **NeKI brief:** Collects examples of Apple Vision Pro apps and interaction ideas that illustrate spatial computing possibilities. Useful for surveying product patterns and inspiration, while treating the examples as design leads rather than API guidance.
- [sent out only via email](https://mailchi.mp/e1735a8e72df/a-computer-for-the-rest-of-us?e=776be5695e) — iOS Dev Weekly · Issue 645 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th January 2024`
  **NeKI brief:** The page covers “sent out only via email” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [A new access modifier in Swift: package](https://blog.eidinger.info/a-new-access-modifier-in-swift-package) — iOS Dev Weekly · Issue 645 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `26th January 2024`
  **NeKI brief:** I had missed this feature of Swift 5.9. It’s rare that the existing levels of visibility don’t give you enough control, but I can see situations where a package level would be useful. Thanks to Marco Eidinger for reminding me this exists!
- [Reveal](https://revealapp.com/) — iOS Dev Tools · 🔨 Reveal, Fabula, AnimateText — Article · Topics: Accessibility · Objective-C & Cocoa
  **Published:** `2024-01-25T16:38:45.891Z`
  **NeKI brief:** Reveal is a macOS app for inspecting or presenting application interfaces. Follow its page for concrete UI-debugging or presentation workflows, while checking supported project formats and current platform compatibility.
- [Let's visionOS 2024](https://letsvisionos24.swiftgg.team/en) — Fatbobman’s Swift Weekly · Issue 16 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `2024-01-22T22:00:38.257Z`
  **NeKI brief:** Let’s VisionOS 2024 is a Beijing event focused on visionOS and Apple-platform development. Use it to find historical conference material and community perspectives, not as current API documentation or a direct implementation tutorial.
- [Vision Pro Apps look boring](https://buttondown.email/varrall/archive/vision-pro-apps-look-boring) — iOS Dev Weekly · Issue 644 — Article · Topics: Objective-C & Cocoa · Spatial Computing
  **Published:** `19th January 2024`
  **NeKI brief:** Stuart Varrall observes something about the visionOS apps that he has seen so far:
- [it depends](https://www.jviotti.com/2024/01/05/is-objective-c-bool-a-boolean-type-it-depends.html) — iOS Dev Weekly · Issue 643 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `12th January 2024`
  **NeKI brief:** As with the answer to most questions, the answer is it depends…
- [Setting](https://github.com/aheze/Setting) — iOS Dev Tools · 🔨 Setting, Core Data Lab, MonitorControl — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-01-11T16:12:03.171Z`
  **NeKI brief:** Setting is a SwiftUI-oriented settings component or library. Follow its source for concrete preference modeling and settings-screen composition, while checking persistence and platform behavior before adoption.
- [Quick Search with SwiftUI Searchable](https://danielsaidi.com/blog/2023/12/20/quick-search-with-swiftui-searchable) — Fatbobman’s Swift Weekly · Issue 12 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Shows a compact searchable SwiftUI flow with query state and filtering. Follow it when adding search to a list and deciding where debouncing, predicate construction, or empty-query behavior belongs.
- [Design tool canvas handles](https://bjango.com/articles/designtoolcanvashandles) — iOS Dev Weekly · Issue 640 — Article · Topics: Objective-C & Cocoa
  **Published:** `15th December 2023`
  **NeKI brief:** Examines Design tools often pack a lot of functionality around the bounding box of selected objects. Some of this functionality is represented by handles or icons, but a lot of it is hidden. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Shows how to request App Store ratings from an app and frame the timing around user experience. Useful for integrating review prompts deliberately while keeping eligibility, frequency, and platform presentation behavior under app control.
- [new mlx repository](https://github.com/ml-explore/mlx) — iOS Dev Weekly · Issue 639 — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `8th December 2023`
  **NeKI brief:** MLX is Apple's research-oriented array and machine-learning framework for Apple Silicon, exposing unified CPU/GPU memory concepts. Useful for evaluating local model experiments outside a Python-only workflow.
- [UIViewController viewIsAppearing](https://ohmyswift.com/blog/2023/12/01/from-viewwillappear-to-viewisappearing-perfecting-your-ios-view-transitions?ref=ioscodereview.com) — iOS Code Review · Issue 61 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2023-12-07T13:38:43.000Z`
  **NeKI brief:** Explains the transition from viewWillAppear to viewIsAppearing and the timing differences relevant to layout and appearance updates. Follow it when modernizing UIKit lifecycle code that depends on final geometry or trait state.
- [Apple’s use of languages and technologies in macOS Sonoma](https://blog.timac.org/2023/1128-state-of-appkit-catalyst-swift-swiftui-mac) — iOS Dev Weekly · Issue 638 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `1st December 2023`
  **NeKI brief:** Surveys AppKit, Catalyst, Swift, and SwiftUI capabilities on macOS, highlighting interoperability boundaries. Useful for choosing a platform strategy when an app spans native macOS and shared UI code.
- [Apple’s use of Swift and SwiftUI in iOS 17](https://blog.timac.org/2023/1019-state-of-swift-and-swiftui-ios17) — iOS Dev Weekly · Issue 638 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `1st December 2023`
  **NeKI brief:** Reviews Swift and SwiftUI changes around iOS 17 with implementation context. Use it to orient migration work and identify which new APIs affect deployment targets or existing view architecture.
- [Swift JSON/Model Library Research](https://juejin.cn/post/7303741790674731045) — Fatbobman’s Swift Weekly · Issue 8 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2023-11-27T22:10:19.997Z`
  **NeKI brief:** Researches Swift JSON and model libraries, comparing approaches to decoding, mapping, and model generation. Use it as an ecosystem survey before selecting a serialization dependency, then verify maintenance, performance, and API compatibility directly.
- [Questions about the data to create LLMs for embeddings](https://rhonabwy.com/2023/11/15/questions-about-the-data-to-create-llms-for-embeddings) — Fatbobman’s Swift Weekly · Issue 7 — Article · Topics: AI Development · Architecture · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Raises practical questions about collecting and preparing data for embedding-oriented language models. Follow it when designing retrieval datasets and evaluating provenance, chunking, quality, and privacy rather than treating embeddings as a drop-in search feature.
- [PEP 730 – Adding iOS as a supported platform](https://peps.python.org/pep-0730) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: App Distribution & Store Operations · Architecture · Objective-C & Cocoa
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** PEP 730 proposes adding iOS as a supported Python platform and outlines packaging and runtime considerations. Follow it when evaluating Python components in an iOS toolchain, distinguishing language support from native framework and App Store constraints.
- [https://github.com/thebrowsercompany/swift-winrt](https://github.com/thebrowsercompany/swift-winrt) — Fatbobman’s Swift Weekly · Issue 5 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** On another interesting turn of events, the browser Arc, fully developed using the Swift language, released its Windows version this week. What makes it interesting is that the tools they used are fully open-source and available on GitHub. Why not take a look…
- [example](https://github.com/thebrowsercompany/windows-samples) — Fatbobman’s Swift Weekly · Issue 5 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Collects Windows sample projects that accompany experiments with Swift and WinRT interoperability. Follow it for concrete API-binding and build examples, while keeping platform-specific assumptions isolated from portable Swift package code.
- [OpenSwiftUI](https://github.com/Kyle-Ye/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Kyle Ye's OpenSwiftUI work offers a research implementation for studying SwiftUI and AttributeGraph-like behavior. Follow it for comparative experiments and internals-oriented learning, not as a compatibility promise for production Apple-platform code.
- [ASO](https://aso.dev/) — iOS Dev Tools · 🔨 Introducing ClyAppIcon, Keyboard Cowboy, ASO — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2023-10-05T14:01:05.650Z`
  **NeKI brief:** ASO.dev combines App Store Optimization tools with metadata editing for iOS apps. Follow it for a concrete workflow around preparing and comparing store listing text and keywords.
- [Generated Asset Catalog Symbols in Objective-C](https://www.swiftjectivec.com/generated-asset-symbols-objective-c) — iOS Dev Weekly · Issue 627 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `15th September 2023`
  **NeKI brief:** Examines Swift gets all the new toys, and rightfully so. Though, I was happy to see Objective-C still gets some love with Xcode 15. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Arkana](https://github.com/rogerluan/arkana) — iOS Dev Tools · Introducing iOS Security Suite, AspirinShot, Arkana — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2023-09-14T12:30:13.346Z`
  **NeKI brief:** Arkana generates or manages secrets and configuration for Swift projects. Follow its source for concrete build-time generation and storage behavior, while reviewing secret exposure and CI integration boundaries.
- [iOS Mobile Developer at Globant](https://career.globant.com/job/Barcelona-IOS-Mobile-Developer-Barc/540106917) — iOS Dev Tools · Introducing iOS Security Suite, AspirinShot, Arkana — Article · Topics: Developer Career & Practice · Objective-C & Cocoa · Testing
  **Published:** `2023-09-14T12:30:13.346Z`
  **NeKI brief:** This Globant page advertises an iOS mobile developer position in Barcelona. It is a career listing rather than technical reading and should normally be excluded from the knowledge index.
- [their blog](https://www.emergetools.com/blog) — iOS Dev Tools · 🔨 Introducing Snapshots, BuildSwitcher, SwiftFormat — Article · Topics: Objective-C & Cocoa
  **Published:** `2023-09-07T13:05:06.561Z`
  **NeKI brief:** Emerge Tools publishes mobile-performance and developer-tooling material. Follow individual technical posts for concrete optimization workflows, while treating the blog index itself as navigation rather than a separate article.
- [Premature Optimization: Universally Misunderstood](https://milen.me/writings/premature-optimization-universally-misunderstood?ref=ioscodereview.com) — iOS Code Review · Issue 54 — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **Published:** `2023-08-31T14:20:05.000Z`
  **NeKI brief:** Examines Premature Optimization: Universally Misunderstood in the context of Architecture and Code Quality. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [NYSwifty 2023: Getting started with Xcode Cloud](https://www.youtube.com/watch?v=5Xf5ihKvogs%3Futm_campaign%3DiOS+CI+Newsletter%26utm_medium%3Dweb%26utm_source%3DiOS+CI+Newsletter+Issue+23%26utm_content%3Daug_27_23) — iOS CI Newsletter · Issue 23 — Video · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `2023-08-27T00:00:00.000Z`
  **NeKI brief:** Records NYSwifty 2023: Getting started with Xcode Cloud as a visual walkthrough relevant to Objective-C & Cocoa and Swift. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Dash 7](https://blog.kapeli.com/dash-7) — iOS Dev Weekly · Issue 624 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th August 2023`
  **NeKI brief:** Presents Dash 7, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [How to check if you use a required reason API](https://blog.eidinger.info/how-to-check-if-you-use-a-required-reason-api) — iOS Dev Weekly · Issue 624 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th August 2023`
  **NeKI brief:** Examines Learn about Apple's required reason APIs (which need to be declared in your app's privacy manifest) and use a shell script helping you to identity such APIs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [5 iOS job opportunities at Orange Quarter](https://orange-quarter.com/jobs?_search=ios%3Futm_source%3Diosdevtools.substack.com) — iOS Dev Tools · 🔨 Introducing SnapKit, SwiftyJSON, RxSwift — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `2023-08-10T11:11:05.792Z`
  **NeKI brief:** This Orange Quarter page aggregates iOS job opportunities. It is recruitment material rather than technical reading and should normally be excluded from the knowledge index.
- [Xcode Search Scopes](https://xcode.tips/search-scopes) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `4th August 2023`
  **NeKI brief:** Explores Xcode Search Scopes, focusing on i’m a fan of the xcode feature in this latest. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Objective-C Internals](https://alwaysprocessing.blog/series/objc-internals) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa
  **Published:** `4th August 2023`
  **NeKI brief:** Examines Get ready to dive deep into the inner workings of the Objective-C language and runtime! Each post delves into a specific aspect of the language and explores the details of its impl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🧰 How to create a binary framework from a Swift Package](https://blog.eidinger.info/why-is-it-so-damn-difficult-to-create-a-binary-framework-for-your-swift-package) — iOS CI Newsletter · Issue 21 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2023-07-31T00:00:00.000Z`
  **NeKI brief:** Walks through how to create a binary framework from a Swift Package, with practical context for Objective-C & Cocoa and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [this spoke to me](https://thoughtbot.com/blog/a-love-letter-to-objective-c) — iOS Dev Weekly · Issue 619 — Article · Topics: Objective-C & Cocoa
  **Published:** `21st July 2023`
  **NeKI brief:** As someone who discovered both Ruby and Objective-C at about the same time, this spoke to me. ❤️
- [☁️ Xcode Cloud: Using swift packages that require authentication](https://blog.eidinger.info/using-swift-packages-with-authentication-in-xcode-cloud) — iOS CI Newsletter · Issue 20 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines Xcode Cloud: Using swift packages that require authentication in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [an article last year](https://blog.eidinger.info/xcode-133-supports-spm-binary-dependency-in-private-github-release) — iOS CI Newsletter · Issue 20 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines an article last year in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [osstatus.com](https://www.osstatus.com/search/results?platform=all&framework=all&search=12&ref=ioscodereview.com) — iOS Code Review · Issue 52 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `2023-07-06T18:35:01.000Z`
  **NeKI brief:** Examines osstatus.com in the context of Objective-C & Cocoa and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [LocationSimulator - Your On-Demand iOS Location Testing Suite](https://github.com/utmapp/UTM) — iOS Dev Tools · 🔨 Audio Alchemy & Virtual Ventures! — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2023-07-06T14:06:48.701Z`
  **NeKI brief:** UTM virtualizes or emulates operating systems on Apple platforms. Follow its source for concrete virtual-machine configuration, hardware acceleration, and device integration, while checking performance and supported guest systems.
- [📦 This GitHub Action helps you keep SPM dependencies up to date!](https://github.com/MarcoEidinger/swift-package-dependencies-check) — iOS CI Newsletter · Issue 19 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `2023-07-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for This GitHub Action helps you keep SPM dependencies up to date!, relevant to Dependency Injection and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [📱 An insight into ETTrace’s Cocoapods to SPM migration](https://www.emergetools.com/blog/posts/moving-from-cocoapods-to-swift-package-manager) — iOS CI Newsletter · Issue 19 — Article · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2023-07-02T00:00:00.000Z`
  **NeKI brief:** Examines An insight into ETTrace’s Cocoapods to SPM migration in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [ETTrace](https://github.com/EmergeTools/ETTrace) — iOS CI Newsletter · Issue 19 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2023-07-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for ETTrace, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [MVC Isn’t MVC](https://collindonnell.com/mvc-isnt-mvc) — iOS Dev Weekly · Issue 615 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `23rd June 2023`
  **NeKI brief:** One thing I dislike about architecture blog posts is that they sometimes attempt to come to a conclusion. This post from Collin Donnell is the exact opposite of that. It felt like a gentle discussion and history lesson on MVC and was a pleasure to read. If…
- [Mirador](https://github.com/HyperARCo/Mirador) — iOS Dev Tools · 🔨 AR Madness with Some Mac Sprinkled in — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2023-06-15T12:01:05.754Z`
  **NeKI brief:** Mirador is an Apple-platform project for inspecting or presenting augmented-reality content. Follow its repository for concrete rendering and interaction code, while verifying device and framework requirements before adoption.
- [All new frameworks presented at WWDC23](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc23) — iOS Dev Weekly · Issue 613 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `9th June 2023`
  **NeKI brief:** Catalogues the new frameworks presented at WWDC23 and provides a compact map of the platform additions introduced that year. Useful as historical orientation before consulting the current SDK documentation for each framework.
- [Introspect for SwiftUI - Unleashing the Power of UIKit and AppKit in SwiftUI](https://github.com/intitni/CopilotForXcode) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [A Layered Approach to Mobile App Security](https://www.guardsquare.com/defense-in-depth-layered-approach-to-mobile-app-security) — iOS Dev Weekly · Issue 612 — Article · Topics: Architecture · Objective-C & Cocoa · Security & Privacy
  **Published:** `2nd June 2023`
  **NeKI brief:** Explores A Layered Approach to Mobile App Security, focusing on developers are being called on to reevaluate their mobile application. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Shape builder vs pathfinder](https://bjango.com/articles/shapebuildervspathfinder) — iOS Dev Weekly · Issue 611 — Article · Topics: Objective-C & Cocoa
  **Published:** `26th May 2023`
  **NeKI brief:** The article compares Illustrator's Shape Builder and Pathfinder tools and explains when each is useful in icon and interface design.
- [this amazing article](https://bogo.wtf/arm64-to-sim.html) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines this amazing article in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [this video](https://www.youtube.com/watch?v=bOMQiMxh5Bc) — iOS Dev Weekly · Issue 609 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `12th May 2023`
  **NeKI brief:** Examines If our vision is to become the "internet computer" of the future, Windows is a pretty important platform. But how we're building Arc for Windows is..... kind. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🔍 ETTrace: A new tool to profile iOS apps](https://www.emergetools.com/blog/posts/ettrace-reliable-ios-profiling-with-flamecharts) — iOS CI Newsletter · Issue 15 — Article · Topics: Objective-C & Cocoa · Performance · Swift
  **Published:** `2023-05-07T00:00:00.000Z`
  **NeKI brief:** Examines ETTrace: A new tool to profile iOS apps in the context of Objective-C & Cocoa and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🏉 A behind-the-scenes look into Rugby’s latest update](https://swiftyfinch.github.io/en/2023-04-22-rugby-remastered) — iOS CI Newsletter · Issue 14 — Article · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2023-04-23T00:00:00.000Z`
  **NeKI brief:** Examines A behind-the-scenes look into Rugby’s latest update in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [chatty](https://github.com/polpielladev/chatty-cli) — iOS CI Newsletter · Issue 13 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for chatty, relevant to Architecture and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [CoreDataErrors.h as a gist on GitHub](https://gist.github.com/hishma/7cb505f94230ac7d7ed53d52a1e6dab6?ref=ioscodereview.com) — iOS Code Review · Issue 45 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2023-03-16T13:58:41.000Z`
  **NeKI brief:** Provides the source and change history for CoreDataErrors.h as a gist on GitHub, relevant to Core Data and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [documentation search look like](https://github.com/arc53/docsgpt) — iOS Dev Weekly · Issue 600 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th March 2023`
  **NeKI brief:** Examines Private AI platform for agents, assistants and enterprise search. Built-in Agent Builder, Deep research, Document analysis, Multi-model support, and API connectivity for agents. -. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Building Large-Scale Apps with SwiftUI: A Guide to Modular Architecture](https://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #134 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2023-03-06T15:27:12.172Z`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The difference between List and LazyVStack](https://dimillian.medium.com/swiftui-the-difference-between-list-and-lazyvstack-3d5eeaccb156) — SwiftUI Weekly · SwiftUI Weekly - Issue #134 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2023-03-06T15:27:12.172Z`
  **NeKI brief:** Compares List with LazyVStack through the rendering, scrolling, and interaction behaviour that makes them different despite similar output. Follow it before replacing one with the other in a performance-sensitive screen or a layout needing list-specific capabilities.
- [Arc Coding Chronicles](https://www.youtube.com/watch?v=94asyypYj5c) — SwiftUI Weekly · SwiftUI Weekly - Issue #132 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2023-02-21T07:37:59.536Z`
  **NeKI brief:** Reconstructs Arc Browser's SwiftUI loading indicator and shares the supporting code, showing how a small branded animation was designed and implemented. Useful as a focused animation study rather than a general loading-state pattern.
- [Formulas for optical adjustments](https://bjango.com/articles/opticaladjustments) — iOS Dev Weekly · Issue 597 — Article · Topics: Objective-C & Cocoa
  **Published:** `17th February 2023`
  **NeKI brief:** Examines But that also explains why there’s less of this type of content around. Writing about solutions to real-world problems isn’t easy to do regularly because of how much work must happen before you put down a single word. It Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Swift/Objective-C Developer Ecosystem Survey](https://www.jetbrains.com/lp/devecosystem-2022/swift-objc) — iOS Dev Weekly · Issue 596 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `10th February 2023`
  **NeKI brief:** Examines The State of Developer Ecosystem 2022 is a detailed report about the programming community, which covers the latest trends in languages, tools, technologies, and lifestyles of deve. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The evolution of Facebook’s iOS app architecture](https://engineering.fb.com/2023/02/06/ios/facebook-ios-app-architecture) — iOS Dev Weekly · Issue 596 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th February 2023`
  **NeKI brief:** Explores The evolution of Facebook’s iOS app architecture, focusing on i’ve never worked on a huge ios app like facebook,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Embarcadero](https://github.com/social-squircle/Embarcadero) — iOS Dev Weekly · Issue 596 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th February 2023`
  **NeKI brief:** Examines A community resource for finding custom SF Symbols and the people who make them - social-squircle/Embarcadero. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple security features won’t protect your app. Here’s what will.](https://www.guardsquare.com/blog/apple-security-features-wont-protect-your-app-heres-what-will) — iOS Dev Weekly · Issue 595 — Article · Topics: Objective-C & Cocoa · Security & Privacy
  **Published:** `3rd February 2023`
  **NeKI brief:** Examines App developers relying on Apple security features alone are putting their apps at risk. Here’s how to increase your iOS app’s security posture. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [hello](https://hellosystem.github.io/docs) — iOS Dev Weekly · Issue 595 — Article · Topics: Developer Career & Practice · Developer Tools · Objective-C & Cocoa
  **Published:** `3rd February 2023`
  **NeKI brief:** Presents hello, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Search](https://kean.blog/post/pulse-search) — SwiftUI Weekly · SwiftUI Weekly - Issue #129 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2023-01-30T11:20:24.661Z`
  **NeKI brief:** Explains Starting with iOS 15, SwiftUI supports search thanks to the new .searchable modifier. It was also extended with the support for tokens in iOS 16 which was exactly what I was waiting for. For me, it was a perfect opportun Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [Saving money when using GitHub Actions](https://blog.eidinger.info/save-money-when-using-github-actions-for-ios-cicd) — iOS CI Newsletter · Issue 8 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2023-01-29T00:00:00.000Z`
  **NeKI brief:** Examines Saving money when using GitHub Actions in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [using a self-hosted runner](https://docs.github.com/en/actions/hosting-your-own-runners/using-self-hosted-runners-in-a-workflow) — iOS Dev Weekly · Issue 594 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `27th January 2023`
  **NeKI brief:** There are some good tips in this post from Marco Eidinger for keeping costs down when running GitHub Actions on private repositories, but the one I was surprised to see missing was using a self-hosted runner.
- [Testing Swift command-line tools](https://blog.eidinger.info/test-your-command-line-tool-in-xcode) — iOS CI Newsletter · Issue 7 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2023-01-15T00:00:00.000Z`
  **NeKI brief:** Examines Testing Swift command-line tools in the context of Objective-C & Cocoa and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift Enum With Labeled Associated Values](https://blog.eidinger.info/swift-enum-with-labeled-associated-values) — iOS Dev Weekly · Issue 589 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `16th December 2022`
  **NeKI brief:** Examines Adding labels for associated values of enum cases when declaring a Swift enumeration case can improve clarity. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Icon speedrun guides](https://bjango.com/articles/speedrunpushpin) — iOS Dev Weekly · Issue 586 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th November 2022`
  **NeKI brief:** Examines When viewing my vector icon speedruns, it can be difficult to see precisely what’s going on. Everything happens quickly, with many actions triggered via keyboard shortcuts, and Ill. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [flag](https://bjango.com/articles/speedrunflag) — iOS Dev Weekly · Issue 586 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th November 2022`
  **NeKI brief:** I always loved it when Marc Edwards would tweet an icon speedrun, and while I learned a lot from them, I sometimes wished I could understand more of what he was doing. Wouldn’t it be great if he wrote up some guides? 🤯 The one linked above is the pushpin…
- [pen nib](https://bjango.com/articles/speedrunpen) — iOS Dev Weekly · Issue 586 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th November 2022`
  **NeKI brief:** I always loved it when Marc Edwards would tweet an icon speedrun, and while I learned a lot from them, I sometimes wished I could understand more of what he was doing. Wouldn’t it be great if he wrote up some guides? 🤯 The one linked above is the pushpin…
- [fingerprint](https://bjango.com/articles/speedrunfingerprint) — iOS Dev Weekly · Issue 586 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th November 2022`
  **NeKI brief:** I always loved it when Marc Edwards would tweet an icon speedrun, and while I learned a lot from them, I sometimes wished I could understand more of what he was doing. Wouldn’t it be great if he wrote up some guides? 🤯 The one linked above is the pushpin…
- [Swift Snippets](https://forums.swift.org/t/swift-snippets/51947/1) — iOS Dev Weekly · Issue 585 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `18th November 2022`
  **NeKI brief:** Explores Swift Snippets, focusing on like marco eidinger, i was also reminded of the swift snippets feature in swift package manager as i read the post on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [uproar or quick course correction](https://www.macrumors.com/2022/10/26/app-store-gambling-ads-complaints) — iOS Dev Weekly · Issue 583 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Objective-C & Cocoa
  **Published:** `4th November 2022`
  **NeKI brief:** Discusses uproar or quick course correction, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [His latest post covers IOS 16](https://blog.timac.org/2022/1005-state-of-swift-and-swiftui-ios16) — iOS Dev Weekly · Issue 579 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `7th October 2022`
  **NeKI brief:** Explores His latest post covers IOS 16, focusing on his latest post covers ios 16, and the results start. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [history of nil messaging](http://mutable-states.com/message-to-no-one.html) — iOS Dev Weekly · Issue 579 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `7th October 2022`
  **NeKI brief:** It has been a while since Objective-C got a mention in the newsletter. Does that make it a good time to link to this well-researched history of nil messaging? I think it does! 🙇
- [Xcode’s refactoring options for async/await](https://blog.eidinger.info/xcodes-refactoring-options-for-asyncawait) — iOS Dev Weekly · Issue 574 — Article · Topics: Concurrency · Objective-C & Cocoa · Xcode
  **Published:** `2nd September 2022`
  **NeKI brief:** Explores Xcode’s refactoring options for async/await, focusing on is anyone else guilty of only using the xcode refactoring menu for rename…?. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Autocompletion for SPM Commands](https://blog.eidinger.info/autocompletion-for-swift-package-manager-commands) — iOS Dev Weekly · Issue 571 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `12th August 2022`
  **NeKI brief:** Explores Autocompletion for SPM Commands, focusing on here’s a helpful post from marco eidinger on how to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How do 3D transforms of iOS views work under the hood?](https://www.thealexanderlee.com/blog/how-do-3d-transforms-of-ios-views-work-under-the-hood) — iOS Dev Weekly · Issue 570 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th August 2022`
  **NeKI brief:** Explores How do 3D transforms of iOS views work under the hood?, focusing on the article discusses missed this two-part (1, 2) series on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [2](https://www.thealexanderlee.com/blog/3d-transforms-on-ios-under-the-hood-part-2-perspective-shifts) — iOS Dev Weekly · Issue 570 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th August 2022`
  **NeKI brief:** Explores 2, focusing on the article discusses missed this two-part (1, 2) series on 3d transforms from alex lee when it was first published in march.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [View Is The View Model](https://azamsharp.com/2022/07/21/view-is-the-view-model.html) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th July 2022`
  **NeKI brief:** Explores View Is The View Model, focusing on do you need view models if you’re working with swiftui?. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [WPF](https://docs.microsoft.com/en-us/visualstudio/designers/getting-started-with-wpf) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `29th July 2022`
  **NeKI brief:** Explores WPF, focusing on do you need view models if you’re working with swiftui? mohammad azam makes the case in this post that you may not.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Open your terminal from Xcode](https://blog.eidinger.info/open-your-terminal-from-xcode) — iOS Dev Weekly · Issue 567 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `15th July 2022`
  **NeKI brief:** Presents Open your terminal from Xcode, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Jercy’s Awesome Xcode Behaviors repository](https://github.com/JeaSungLEE/Awesome-Xcode-Behaviors) — iOS Dev Weekly · Issue 567 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `15th July 2022`
  **NeKI brief:** I hadn’t ever used a Custom Behaviour before reading this post from Marco Eidinger that covers some useful behaviour scripts from Jercy’s Awesome Xcode Behaviors repository. I instantly wanted to use the “Open in Terminal” script, but it didn’t behave quite…
- [Augmented Reality Digital Lounge from WWDC22](https://yono.ai/articles/wwdc22-arkit-realitykit-usdz-digital-lounge) — iOS Dev Weekly · Issue 566 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Spatial Computing
  **Published:** `8th July 2022`
  **NeKI brief:** Summarizes the WWDC22 ARKit, RealityKit, and USDZ digital-lounge material and points to the related demonstrations. Useful for orienting an augmented-reality exploration before consulting the current ARKit and RealityKit documentation.
- [Machine Learning](https://yono.ai/articles/wwdc22-machine-learning-digital-lounge) — iOS Dev Weekly · Issue 566 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Tools
  **Published:** `8th July 2022`
  **NeKI brief:** Summarizes the WWDC22 machine-learning digital-lounge material and its demonstrations. Useful as a compact orientation to the session topics before consulting Apple’s current machine-learning frameworks and documentation.
- [Building an Accessible Custom Tab Bar | Bas’ Blog](https://www.basbroek.nl/custom-tab-bar-accessibility?ref=ioscodereview.com) — iOS Code Review · Issue 26 — Article · Topics: Accessibility
  **Published:** `2022-06-30T10:52:20.000Z`
  **NeKI brief:** Explores Building an Accessible Custom Tab Bar, focusing on the very best way to ensure that the tab bar. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Digital Lounge archive](https://midnight-beanie-ccb.notion.site/swiftui-lounge-wwdc22-e20094b91f074398ba395c3fa245e63d) — iOS Dev Weekly · Issue 563 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `17th June 2022`
  **NeKI brief:** Explores SwiftUI Digital Lounge archive, focusing on the digital lounges were great again this year, but they. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [some good tips](https://kernelpanic.me/2022/06/06/running-macos-ventura-as-a-vm) — iOS Dev Weekly · Issue 562 — Article · Topics: macOS & AppKit · Objective-C & Cocoa · Personal Essays
  **Published:** `10th June 2022`
  **NeKI brief:** Examines While Xcode 14 runs perfectly well on macOS Monterey, if you want to play with all the features, you’ll need runtime support which is only¹ available if you’re running the new macOS Ventura beta. This Twitter thread from Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Project wide refactoring for if let](https://dev.to/vibrazy/if-let-shorthand-project-wide-refactoring-using-xcode-regex-search-replace-enh) — iOS Dev Weekly · Issue 562 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `10th June 2022`
  **NeKI brief:** Explores Project wide refactoring for if let, focusing on if you’re already fully switched over to swift 5.7. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [CocoaDocs](https://github.com/CocoaPods/cocoadocs.org) — iOS Dev Weekly · Issue 561 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `3rd June 2022`
  **NeKI brief:** The GitHub repository contains CocoaDocs, a project for generating and hosting documentation for Cocoa and Swift packages.
- [Transitioning from Intel to Apple Silicon](https://www.macstadium.com/transitioning-from-intel-to-apple-silicon) — iOS Dev Weekly · Issue 560 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `27th May 2022`
  **NeKI brief:** Explores Transitioning from Intel to Apple Silicon, focusing on not sure how your mac builds or tests will be. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Sydney CocoaHeads Accessibility Spectacular](https://youtu.be/SKuWLHNHF28?t=2198) — iOS Dev Weekly · Issue 559 — Video · Topics: Accessibility · Developer Community & Business · Objective-C & Cocoa
  **Published:** `20th May 2022`
  **NeKI brief:** Examines This month it’s all about Accessibility. CocoaHeads falls on the same day as Global Accessibility Awareness Day (GAAD). We have 4 amazing speakers lined up:?. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [STTextView](https://christiantietze.de/posts/2022/05/sttextview-textkit-2-editor-without-nstextview) — iOS Dev Weekly · Issue 558 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th May 2022`
  **NeKI brief:** Explores STTextView, focusing on talking of textkit 2, in this post, christian tietze talks about marcin krzyzanowski’s syntax highlighting text editor control for macos, sttextview. it’s. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Designing macOS menu bar extras](https://bjango.com/articles/designingmenubarextras) — iOS Dev Weekly · Issue 556 — Article · Topics: macOS & AppKit · Objective-C & Cocoa
  **Published:** `29th April 2022`
  **NeKI brief:** Discusses Designing macOS menu bar extras, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Xcodes.app](https://github.com/RobotsAndPencils/XcodesApp) — iOS Dev Weekly · Issue 552 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st April 2022`
  **NeKI brief:** Explores Xcodes.app, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [latest release](https://github.com/RobotsAndPencils/XcodesApp/releases/tag/v1.3.1b11) — iOS Dev Weekly · Issue 552 — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `1st April 2022`
  **NeKI brief:** Explores latest release, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Filtering with the Searchable Modifier](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD90PThzJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj13em9YV2haVUI1byIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.MIRHY06NAcrGpIiXhmfgyOFumNl-UFq7Q2nKMIMwGeY) — SwiftUI Weekly · SwiftUI Weekly - Issue #94 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2022-02-28T09:54:32.000Z`
  **NeKI brief:** Demonstrates searchable-based filtering in SwiftUI, connecting query text to collection results. Useful for building discoverable list search while deciding where normalization, debouncing, and empty-state handling belong.
- [Three surprises when using Markdown with SwiftUI](https://blog.eidinger.info/3-surprises-when-using-markdown-in-swiftui) — iOS Dev Weekly · Issue 545 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `11th February 2022`
  **NeKI brief:** Explores Three surprises when using Markdown with SwiftUI, focusing on are you using ios 15’s new markdown support? these three. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Automate your dependency updates](https://blog.eidinger.info/automate-the-way-you-keep-up-with-dependency-changes-in-your-swift-package) — iOS Dev Weekly · Issue 543 — Article · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `28th January 2022`
  **NeKI brief:** Explains Automate your dependency updates, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html?ref=ioscodereview.com) — iOS Code Review · Issue 15 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2022-01-27T11:57:44.000Z`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift command-line tools and GitHub workflows](https://blog.eidinger.info/use-a-swift-command-line-tool-in-a-github-workflow) — iOS Dev Weekly · Issue 541 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th January 2022`
  **NeKI brief:** Examines Learn how to execute a Swift command-line tool in your CI/CD workflow for iOS and Swift development and how to cache its CLI to improve workflow speed. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html) — iOS Dev Weekly · Issue 541 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `14th January 2022`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [GitHub - russell-archer/StoreHelper](https://github.com/russell-archer/StoreHelper?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/StoreHelper, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub - russell-archer/IAPDemo](https://github.com/russell-archer/IAPDemo?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/IAPDemo, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [Opacity precision](https://bjango.com/articles/opacityprecision) — iOS Dev Weekly · Issue 537 — Article · Topics: Objective-C & Cocoa
  **Published:** `10th December 2021`
  **NeKI brief:** On one level, this article from Marc Edwards is about setting object/layer opacity in design tools. On another, it’s about thinking through obvious and non-obvious choices in UI design. 🎉
- [#1228](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/1228) — iOS Dev Weekly · Issue 535 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th November 2021`
  **NeKI brief:** That experience permanently aligned me with Russ’s thinking, and I now err on the side of caution when releasing features. For example, there are two enhancements to search in the Swift Package Index (#1228 and #1320 specifically) in progress right now…
- [#1320](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/1320) — iOS Dev Weekly · Issue 535 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th November 2021`
  **NeKI brief:** Examines We’re so close to this feature! @finestructure and I chatted through the last couple of bits this morning and here’s a list: Search should return multiple matches for authors from. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dangerous Logging in Swift](https://indiestack.com/2021/10/dangerous-logging-in-swift) — iOS Dev Weekly · Issue 532 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `5th November 2021`
  **NeKI brief:** The article explains why careless logging in Swift can expose sensitive data and outlines safer logging practices for applications.
- [new extension API](http://github.com/raycast/extensions) — iOS Dev Weekly · Issue 531 — Source repository · Topics: Developer Community & Business · Developer Tools · Xcode
  **Published:** `29th October 2021`
  **NeKI brief:** Imagine being able to search and open recent Xcode projects, manage installed iOS simulators, and access developer documentation from one place. Sven Tiigi’s Raycast Xcode extension uses our new extension API to make all that possible. Of course, Raycast…
- [Evolving our business model to address developer needs](https://android-developers.googleblog.com/2021/10/evolving-business-model.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Evolving our business model to address developer needs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [announced in March](https://android-developers.googleblog.com/2021/03/boosting-dev-success.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Boosting developer success on Google Play. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The SwiftUI Environment](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5maXZlc3RhcnMuYmxvZy9hcnRpY2xlcy9zd2lmdHVpLWVudmlyb25tZW50LXByb3BhZ2F0aW9uLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQwODQ4YzM4LWI2YTQtNDFiZC04Mzg0LTU4YzJlNWRjZjE1MSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJjNTRlMGI4OS0zZmY3LTQxMzQtYmJkYS01NjNhMDU4Y2QyMDkiLCJpYXQiOjE2NzQwNjI2MTcuNzcsImlzcyI6Im9yY2hpZCJ9.HuT9AYMXhtb-Iiu_vZyWQr5EEwI4m_9PWqCDa4hGB-M) — SwiftUI Weekly · SwiftUI Weekly - Issue #78 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2021-10-04T18:21:47.000Z`
  **NeKI brief:** Explains how SwiftUI environment values propagate dependencies and configuration through a view hierarchy. Useful for designing shared settings and services while keeping injection explicit and previews manageable.
- [Getting Started with Resolver for iOS Dependency Injection](https://www.raywenderlich.com/22203552-resolver-for-ios-dependency-injection-getting-started) — iOS Dev Weekly · Issue 516 — Article · Topics: Architecture · Dependency Injection · Objective-C & Cocoa
  **Published:** `16th July 2021`
  **NeKI brief:** The tutorial introduces Resolver and demonstrates getting started with dependency injection in an iOS application.
- [DocC - Archived and Analyzed](http://www.alwaysrightinstitute.com/docz) — iOS Dev Weekly · Issue 515 — Article · Topics: Objective-C & Cocoa
  **Published:** `9th July 2021`
  **NeKI brief:** Examines At WWDC 2021 Apple presented DocC, a way to create Swift documentation and tutorials right within Xcode. We are going to look at the documentation archive produced, the good&ba. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Hosting DocC Archives](https://josephduffy.co.uk/posts/hosting-docc-archives) — iOS Dev Weekly · Issue 512 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th June 2021`
  **NeKI brief:** Examines Talking of DocC, what do you do with the documentation for your framework or library once you’ve built it locally? Joseph Duffy investigates four ways to serve your documentation as a static site. 👍 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [This post from Marco Arment](https://marco.org/2021/06/03/developer-relations) — iOS Dev Weekly · Issue 510 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `4th June 2021`
  **NeKI brief:** Explores This post from Marco Arment, focusing on looking around twitter and the web this week, i see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Introduces Combine publishers, subscribers, and operators through practical examples. Follow it when maintaining pre-concurrency SwiftUI code or bridging publisher pipelines into newer async/await boundaries.
- [SwiftPM Library](https://daveverwer.com/blog/launching-the-swiftpm-library) — iOS Dev Weekly · Issue 503 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `16th April 2021`
  **NeKI brief:** Explores SwiftPM Library, focusing on the original idea for building a package search engine popped into my head around two years before the launch of the index. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Be careful with Obj-C bridging in Swift](https://swiftrocks.com/be-careful-with-objc-bridging-in-swift) — iOS Dev Weekly · Issue 497 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `5th March 2021`
  **NeKI brief:** Explains Be careful with Obj-C bridging in Swift, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Swift (was) for TensorFlow](https://github.com/tensorflow/swift) — iOS Dev Weekly · Issue 495 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `19th February 2021`
  **NeKI brief:** The GitHub repository contains the historical Swift for TensorFlow project and its publicly readable source and documentation.
- [Dash 6](https://blog.kapeli.com/dash-6) — iOS Dev Weekly · Issue 495 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th February 2021`
  **NeKI brief:** Dash remains an essential part of my day-to-day toolkit, and not only for Swift development! This new version comes with experimental support for full-text search, which is a great step forward. There’s a trial available, but if you’re anything like me, this…
- [Dash](https://kapeli.com/dash) — iOS Dev Weekly · Issue 495 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th February 2021`
  **NeKI brief:** The page documents Dash, the offline API documentation browser and code snippet manager, including its developer-oriented documentation workflow.
- [nil-null-mess in Objective-C and Swift](https://www.andyibanez.com/posts/nil-null-mess-objective-c-and-swift) — iOS Dev Weekly · Issue 493 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `5th February 2021`
  **NeKI brief:** Examines Learn the complexities of nullability in Swift and Objective-C, common bugs, and how to work around them. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Brad Cox, Creator of Objective-C, Passes](https://shapeof.com/archives/2021/1/brad_cox_objective-c_creator_passes.html) — iOS Dev Weekly · Issue 492 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th January 2021`
  **NeKI brief:** Presents Brad Cox, Creator of Objective-C, Passes, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Who said we can’t unit test SwiftUI views?](https://nalexn.github.io/swiftui-unit-testing) — iOS Dev Weekly · Issue 492 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines Who said we can't unit test SwiftUI views?, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [snapshot test](https://www.vadimbulavin.com/snapshot-testing-swiftui-views) — iOS Dev Weekly · Issue 492 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Covers snapshot test, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [well documented](https://github.com/nalexn/ViewInspector/blob/master/guide.md) — iOS Dev Weekly · Issue 492 — Source repository · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines well documented, focusing on when i first saw that all swiftui view hierarchy was a function of state stored in structs, i figured it would be ideal…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Tribute](https://github.com/nicklockwood/Tribute) — iOS Dev Weekly · Issue 485 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `4th December 2020`
  **NeKI brief:** Is this new tool from Nick Lockwood the greatest utility in the world, or is it just a … 😂 I was a big fan of how CocoaPods made it easy to keep your open-source attributions in order, but this tool isn’t tied to a specific dependency manager.
- [interoperate with Objective-C](https://forums.swift.org/t/concurrency-interoperability-with-objective-c/41616) — iOS Dev Weekly · Issue 481 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `6th November 2020`
  **NeKI brief:** Discusses the interoperability boundary between Swift concurrency and Objective-C APIs, including the challenges of importing asynchronous behavior. Useful for anticipating migration issues when modern Swift code calls legacy Objective-C interfaces.
- [GoSwifty](https://github.com/rsrbk/GoSwifty) — iOS Dev Weekly · Issue 479 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines GoSwifty, focusing on are you working on an app that’s transitioning from objective-c to swift? do you know what percentage of your code is in…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [App Store Reviews Should be Stricter](https://tirania.org/blog/archive/2020/Sep-24.html) — iOS Dev Weekly · Issue 475 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `25th September 2020`
  **NeKI brief:** This is a very interesting post by Miguel de Icaza talking about the benefits of having a trusted App Store. He argues for some rule amendments, as well as several changes to the purchasing UI and App Store listing pages.
- [In-App Purchase Rules](https://marco.org/2020/09/11/app-review-changes) — iOS Dev Weekly · Issue 474 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `18th September 2020`
  **NeKI brief:** Discusses In-App Purchase Rules, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [implementation of it](https://github.com/crafterm/swiftui-app-switcher) — iOS Dev Weekly · Issue 474 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `18th September 2020`
  **NeKI brief:** Examines implementation of it, focusing on the ios app switcher is a complex ui control but is all driven from a single drag gesture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Linting licenses](https://felginep.github.io/2020-09-09/linting-licenses) — iOS Dev Weekly · Issue 473 — Article · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `11th September 2020`
  **NeKI brief:** Presents Linting licenses, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [ad_licenselint](https://github.com/faberNovel/ad_licenselint) — iOS Dev Weekly · Issue 473 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `11th September 2020`
  **NeKI brief:** Examines Lint the licenses for iOS projects. Contribute to faberNovel/ad_licenselint development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Abusing iOS’ Screenshot Cropping Mechanism](https://bryce.co/screenshot-cropping) — iOS Dev Weekly · Issue 471 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th August 2020`
  **NeKI brief:** This kind of post is my catnip. 😍 Here’s Bryce Pauken with a look at how iOS 13’s view hierarchy inspection works when taking screenshots. He also goes through several methods for customising where iOS will snap to. I’m not sure you should ever go as far as…
- [this post appeared](https://pspdfkit.com/blog/2020/sponsoring-cocoapods) — iOS Dev Weekly · Issue 463 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines PSPDFKit is sponsoring the costs of hosting the CocoaPods CND. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using SVGs in asset catalogs](https://bjango.com/articles/svgassetcatalogs) — iOS Dev Weekly · Issue 463 — Article · Topics: Objective-C & Cocoa
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines SVGs can now be used as assets for iOS, iPadOS, macOS, and watchOS apps. The most exciting part of this new feature is that there’s not much to say — it’s full SVG support, and it. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How SwiftUI can now be used to build entire iOS apps](https://wwdcbysundell.com/2020/building-entire-apps-with-swiftui) — iOS Dev Weekly · Issue 462 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines How SwiftUI can now be used to build entire iOS apps, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Double-Edged Sword](https://mohsen.dev/2020/06/21/swiftui-double-edged-sword.html) — iOS Dev Weekly · Issue 462 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines Double-Edged Sword, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [this new open-source library](https://github.com/swift-server/swift-aws-lambda-runtime) — iOS Dev Weekly · Issue 460 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `12th June 2020`
  **NeKI brief:** I’ve mentioned a few times that if Apple makes any moves towards a first-party Swift on the server framework that it’d make sense to start with “server functions” that run in iCloud somewhere. I’m not sure whether this new open-source library being part of…
- [Building a view debugger using SceneKit](https://www.youtube.com/watch?v=S6YN2Bsde_Q) — iOS Dev Weekly · Issue 459 — Video · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2020`
  **NeKI brief:** Examines Building a view debugger using SceneKit, focusing on at first glance, you might think the title of this talk from indragie karunaratne is a mistake… scenekit!? to build a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [Swift Without Screens - Powering Connected Devices](https://www.youtube.com/watch?v=VILUaec-sCs) — iOS Dev Weekly · Issue 459 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `5th June 2020`
  **NeKI brief:** Let’s finish with Marc Aupont taking Swift off the devices made by the company in California, and on to a computer that’s so small and widely available it can go almost anywhere. The Raspberry Pi.
- [list of blogs](https://github.com/daveverwer/iOSDevDirectory/blob/master/blogs.json) — iOS Dev Weekly · Issue 458 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `29th May 2020`
  **NeKI brief:** Adrian Ross with another project based on the list of blogs that go to make the iOS Dev Directory. He’s exposing all of the content from the RSS feeds as searchable! 🚀 Would you like your content to be indexed by this search? You know what to do!
- [this walkthrough video](https://www.pointfree.co/episodes/ep100-a-tour-of-the-composable-architecture-part-1) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** A free tour of the newly open-sourced Composable Architecture that builds an application while introducing its state-management model. Useful for assessing the framework from a concrete implementation rather than only its API surface or architectural claims.
- [example apps](https://github.com/pointfreeco/swift-composable-architecture/tree/master/Examples) — iOS Dev Weekly · Issue 455 — Source repository · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Examines example apps, focusing on from a first look at this new architecture framework from brandon williams and stephen celis, i like it. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this post from Alejandro Martinez](https://alejandromp.com/blog/pointfree-composable-architecture-showcase) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Collects a hands-on showcase of Point-Free’s Composable Architecture after early access to the library. It is useful for comparing a third-party implementation perspective with the framework’s own materials and identifying concrete patterns before committing an app architecture.
- [MVP and Coordinators in SwiftUI](https://lascorbe.com/posts/2020-04-27-MVPCoordinators-SwiftUI-part1) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `1st May 2020`
  **NeKI brief:** Examines MVP and Coordinators in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [2](https://lascorbe.com/posts/2020-04-28-MVPCoordinators-SwiftUI-part2) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `1st May 2020`
  **NeKI brief:** Continues the MVP-and-coordinators SwiftUI series with navigation composition and dependency flow. Compare the coordinator boundaries with your app's state model, then verify historical SDK assumptions before production use.
- [3](https://lascorbe.com/posts/2020-04-29-MVPCoordinators-SwiftUI-part3) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `1st May 2020`
  **NeKI brief:** Concludes the MVP-and-coordinators SwiftUI series, showing how screen routing and presentation responsibilities fit together. Use it to assess testability and state ownership, then verify historical SDK assumptions before production use.
- [Optionals in Swift Objective-C Interoperability](https://fabiancanas.com/blog/2020/1/9/swift-undefined-behavior.html) — iOS Dev Weekly · Issue 452 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `17th April 2020`
  **NeKI brief:** Examines Optionals in Swift Objective-C Interoperability. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Vadim Bulavin covered the same topic](https://www.vadimbulavin.com/modern-mvvm-ios-app-architecture-with-combine-and-swiftui) — iOS Dev Weekly · Issue 449 — Article · Topics: Architecture · Combine & Reactive Programming · Objective-C & Cocoa
  **Published:** `27th March 2020`
  **NeKI brief:** Explains Vadim Bulavin covered the same topic, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Swift to participate in GSoC 2020!](https://forums.swift.org/t/swift-to-participate-in-gsoc-2020/33971) — iOS Dev Weekly · Issue 445 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `28th February 2020`
  **NeKI brief:** The page covers “Swift to participate in GSoC 2020!” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [My experience replacing CocoaPods with SwiftPM](https://www.jessesquires.com/blog/replacing-cocoapods-with-swiftpm) — iOS Dev Weekly · Issue 445 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `28th February 2020`
  **NeKI brief:** Examines My experience replacing CocoaPods with SwiftPM, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Many View Controllers](https://rambo.codes/posts/2020-02-20-mvc-with-sugar) — iOS Dev Weekly · Issue 445 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `28th February 2020`
  **NeKI brief:** I don’t link to articles on architecture very often, but I am a sucker for a post that tells you not to worry at all about finding, or adopting the perfect app architecture. There’s no such thing, and you’ll waste endless time trying. I agreed with…
- [this talk](https://www.youtube.com/watch?v=ZShE3toDPIk) — iOS Dev Weekly · Issue 445 — Video · Topics: Architecture · Objective-C & Cocoa
  **Published:** `28th February 2020`
  **NeKI brief:** Examines Filmed at https://2020.dotswift.io on February 3, 2020 in Paris. More talks on https://dotconferences.com/talksApp architecture has been a topic of many disc. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Xcode’s Find Navigator & Search Scopes](https://patrickbalestra.com/blog/2020/02/09/xcode-find-navigator.html) — iOS Dev Weekly · Issue 443 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Xcode
  **Published:** `14th February 2020`
  **NeKI brief:** Examines Xcode's Find Navigator & Search Scopes, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [first nightly releases](https://forums.swift.org/t/swift-5-2-nightly-development-snapshots/32356) — iOS Dev Weekly · Issue 438 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `10th January 2020`
  **NeKI brief:** Explains first nightly releases, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [KVO, My Enemy](https://inessential.com/2019/12/30/kvo_my_enemy) — iOS Dev Weekly · Issue 437 — Article · Topics: Objective-C & Cocoa
  **Published:** `3rd January 2020`
  **NeKI brief:** KVO, My Enemy. This link is retained as a technical reading lead for Apple-platform development.
- [CocoaPods 1.9 Beta](http://blog.cocoapods.org/CocoaPods-1.9.0-beta) — iOS Dev Weekly · Issue 435 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `20th December 2019`
  **NeKI brief:** Examines CocoaPods 1.9 Beta, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dash 5](https://blog.kapeli.com/dash-5) — iOS Dev Weekly · Issue 434 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th December 2019`
  **NeKI brief:** The page covers “Dash 5” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [New Search APIs in iOS 13](https://www.andyibanez.com/posts/ios13-new-search-apis) — iOS Dev Weekly · Issue 431 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd November 2019`
  **NeKI brief:** Examines iOS 13 introduced improvements to existing UI search APIs. Learn what. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftPM Catalog](https://zeezide.com/en/products/swiftpmcatalog) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftPM Catalog, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [manually curated packages](https://github.com/ZeeZide/SwiftPMCatalog/blob/develop/catalog-info.json) — iOS Dev Weekly · Issue 430 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th November 2019`
  **NeKI brief:** Explains manually curated packages, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [SwiftUI Architectures: Model-View, Redux & MVVM](https://quickbirdstudios.com/blog/swiftui-architecture-redux-mvvm) — iOS Dev Weekly · Issue 430 — Article · Topics: Architecture · Objective-C & Cocoa · Product Design
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftUI Architectures: Model-View, Redux & MVVM, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [first major iOS app that I created](https://web.archive.org/web/20180124011652/http://shinydevelopment.com/balloons) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa
  **Published:** `15th November 2019`
  **NeKI brief:** Explains first major iOS app that I created, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [xcdiff](https://github.com/bloomberg/xcdiff) — iOS Dev Weekly · Issue 428 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st November 2019`
  **NeKI brief:** Examines Can you imagine a situation where you have two developers working on the same Xcode project file? If you work on a team, you almost certainly can! That’s where this tool from Marcin Iwanicki, Kassem Wridan, and Adam Khaz Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Package Resources Proposal for the Swift Package Manager](https://forums.swift.org/t/draft-proposal-package-resources/29941) — iOS Dev Weekly · Issue 427 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `25th October 2019`
  **NeKI brief:** Explains Package Resources Proposal for the Swift Package Manager, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [only works well for timeline-based apps](https://en.wikipedia.org/wiki/Pull-to-refresh) — iOS Dev Weekly · Issue 427 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th October 2019`
  **NeKI brief:** But if that happens, is it a good thing? Over the last few years, there has definitely been a trend to conform to “standard” iOS UI as much as possible. I’m a fan of that, I think it makes much more usable apps, and we all strive to create those. But I also…
- [A guide to NSButton styles](https://mackuba.eu/2014/10/06/a-guide-to-nsbutton-styles) — iOS Dev Weekly · Issue 426 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th October 2019`
  **NeKI brief:** Examines The NSButton class used for making buttons in Mac apps has as many as 15 different styles, not counting subclasses. But which should be used where? (Updated with new examples and B. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftLibrary](https://github.com/kiliankoe/SwiftLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines SwiftLibrary, focusing on first of all, swiftlibrary from kilian koeltzsch – a command-line search tool built on top of the swiftpm library api. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [by conference](https://learntalks.com/categories) — iOS Dev Weekly · Issue 422 — Article · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `20th September 2019`
  **NeKI brief:** There’s conference talks, meetup talks, and presentations of all kinds covering iOS development here. List talks by year, by conference or just search for something specific.
- [The Shape API in SwiftUI](https://mecid.github.io/2019/08/14/building-barchart-with-shape-api-in-swiftui) — iOS Dev Weekly · Issue 417 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `16th August 2019`
  **NeKI brief:** Examines The Shape API in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [CocoaPods 1.8 Beta is here](http://blog.cocoapods.org/CocoaPods-1.8.0-beta) — iOS Dev Weekly · Issue 416 — Article · Topics: Objective-C & Cocoa
  **Published:** `9th August 2019`
  **NeKI brief:** What I wrote in my comment above doesn’t mean CocoaPods is dead. Far from it! Even if the adoption of SPM exceeds Apple’s wildest dreams, which will be hard when SPM is still missing some critical features, CocoaPods will be around for many, many years. So…
- [SFSymbols Export](https://github.com/davedelong/sfsymbols) — iOS Dev Weekly · Issue 415 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd August 2019`
  **NeKI brief:** Examines Export the shapes in the SF Symbols font. Contribute to davedelong/sfsymbols development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Straighforward Data Snapshots](http://merowing.info/2019/07/straighforward-data-snapshots) — iOS Dev Weekly · Issue 413 — Article · Topics: Objective-C & Cocoa
  **Published:** `19th July 2019`
  **NeKI brief:** Examines If your app has a lot of content, chances are that by the time you get a chance to work on a bug report, the data that the bug appeared on will be long gone. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ASO Keyword Optimization in Practice](https://asostack.com/aso-keyword-optimization-in-practice-part-2-504ccc15b531) — iOS Dev Weekly · Issue 411 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `5th July 2019`
  **NeKI brief:** Examines Now that you’ve had the time to develop your keyword backlog through researching and setting the relevancy in ASO Keyword Optimization in Practice: Part 1, we will be moving on to. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this test](https://gist.github.com/mattgallagher/eaa5d3242d83360a52c45c9706479e34) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `28th June 2019`
  **NeKI brief:** Examines this test, focusing on when i saw this tweet i did wonder whether we were going to find that the true cost of a great api was runtime…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Solving ambiguous constraints without rerunning your app](https://mar.codes/2019-05-28/Solving-ambiguous-constraints-without-rerunning-your-app) — iOS Dev Weekly · Issue 406 — Article · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `31st May 2019`
  **NeKI brief:** Covers Solving ambiguous constraints without rerunning your app, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [this project](https://github.com/tarunon/XCTAssertAutolayout) — iOS Dev Weekly · Issue 406 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `31st May 2019`
  **NeKI brief:** Examines this project, focusing on tweak a constraint, build and run, tweak a constraint, build and run, tweak, build, tweak… there must be a better way?…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Delisted Overnight: A Cautionary Tale for Indie iOS Developers](https://russ.app/2019/05/delisted-overnight) — iOS Dev Weekly · Issue 406 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `31st May 2019`
  **NeKI brief:** Examines Delisted Overnight: A Cautionary Tale for Indie iOS Developers - Russ Shanahan. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [(Don’t Fear) The Reaper](https://www.highcaffeinecontent.com/blog/20190522-(Dont-Fear)-The-Reaper) — iOS Dev Weekly · Issue 405 — Article · Topics: Objective-C & Cocoa · UIKit
  **Published:** `24th May 2019`
  **NeKI brief:** A really interesting question we probably won’t have an answer to for years to come is whether UIKit is the ‘Carbon’ or the ‘Cocoa’ of this transition. I think the only appropriate answer is ‘yes’. UIKit is the present, and the developer ecosystem it will…
- [In App visual debugger](https://github.com/indragiek/InAppViewDebugger) — iOS Dev Weekly · Issue 402 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `3rd May 2019`
  **NeKI brief:** Examines In App visual debugger, focusing on it’s probably not too much of a hassle to have a mac connected to your app so you can use reveal or the built in xcode…. Use it as a focused research reference for related Apple-platform work, and.
- [Improving asset catalogs](https://bjango.com/articles/assetcatalogs) — iOS Dev Weekly · Issue 402 — Article · Topics: Objective-C & Cocoa
  **Published:** `3rd May 2019`
  **NeKI brief:** Asset catalogs are certainly a step forward from how we used to organise our assets, but their structure on disk certainly means it’s harder to work with export automation workflows. Marc Edwards has some thoughts on the subject… Oh and be sure to read all…
- [Designing APIs](https://www.swiftbysundell.com/posts/designing-swift-apis) — iOS Dev Weekly · Issue 400 — Article · Topics: Code Quality · Objective-C & Cocoa · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** Explains Designing APIs, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Down the rabbit hole of iOS design patterns](https://benoitpasquier.com/down-rabbit-hole-ios-design-patterns) — iOS Dev Weekly · Issue 399 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `12th April 2019`
  **NeKI brief:** Compares common iOS design-pattern trade-offs through concrete examples rather than prescribing one architecture. Use it to frame team discussions about responsibilities, coupling, and test seams in an existing app.
- [Swift by Sundell](https://www.swiftbysundell.com/podcast/45) — iOS Dev Weekly · Issue 399 — Podcast · Topics: Architecture · Developer Community & Business · Swift
  **Published:** `12th April 2019`
  **NeKI brief:** Examines Swift by Sundell, focusing on benoit pasquier talks a lot of sense in this article on app architecture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) — iOS Dev Weekly · Issue 397 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `29th March 2019`
  **NeKI brief:** Examines CryptoSwift is a growing collection of standard and secure cryptographic algorithms implemented in Swift - krzyzanowskim/CryptoSwift. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Save $1000s on your development costs with design compromises](https://marcpalmer.net/how-to-save-1000s-on-your-ios-development-costs-by-making-design-compromises) — iOS Dev Weekly · Issue 393 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `1st March 2019`
  **NeKI brief:** Marc Palmer with a post title that should get your attention. 🤑 The best bit is that the design compromises aren’t even that compromisey (is that a word? It is now!). Of course, there’s always times for the rules to be broken but you won’t go far wrong with…
- [UIViewInvaders](https://github.com/JonoFrench/UIViewInvaders) — iOS Dev Weekly · Issue 393 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `1st March 2019`
  **NeKI brief:** Examines Space Invaders, but created entirely out of UIView. - GitHub - JonoFrench/UIViewInvaders: Space Invaders, but created entirely out of UIView. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Evolving Swift On Apple Platforms After ABI Stability](https://swift.org/blog/abi-stability-and-apple) — iOS Dev Weekly · Issue 391 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `15th February 2019`
  **NeKI brief:** Examines With the release of Swift 5.0, Swift is now ABI stable and is delivered as a core component of macOS, iOS, tvOS, and watchOS. ABI stability has been a goal for Swift since its ince. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift 5 Exclusivity Enforcement](https://swift.org/blog/swift-5-exclusivity) — iOS Dev Weekly · Issue 390 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `8th February 2019`
  **NeKI brief:** Describes Swift 5’s exclusivity enforcement and the runtime and compile-time checks protecting overlapping access to memory. Useful for diagnosing exclusivity violations and understanding why code that once ran can now fail or warn.
- [a good recap](https://www.theverge.com/2019/1/31/18206027/apple-facebook-research-app-enterprise-certificate-google) — iOS Dev Weekly · Issue 389 — Article · Topics: Objective-C & Cocoa · Security & Privacy
  **Published:** `1st February 2019`
  **NeKI brief:** I’m not going to go into the details of the enterprise certificate drama that took place this week, you almost certainly know it all already. Here’s a good recap, if you somehow managed to sleep through it!
- [Creating SVGs with Processing](https://bjango.com/articles/processingsvg) — iOS Dev Weekly · Issue 388 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th January 2019`
  **NeKI brief:** The page covers “Creating SVGs with Processing” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [actual documentation for the feature](https://docs.fastlane.tools/actions/capture_ios_screenshots) — iOS Dev Weekly · Issue 387 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa
  **Published:** `18th January 2019`
  **NeKI brief:** Examines capture_ios_screenshots - fastlane docs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Catching layout feedback loops with runtime magic](https://www.appcoda.com/layout-feedback-loop) — iOS Dev Weekly · Issue 387 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Let’s imagine this scenario: you’ve got a successful app with a great number of daily users and 100% crash-free rate. You are happy and your life is amazing. But at some point you. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Designing a Modern Swift Network Stack](http://mikezornek.com/posts/2019/1/designing-a-modern-swift-network-stack-video-and-slides) — iOS Dev Weekly · Issue 387 — Article · Topics: Graphics, Media & Games · Networking · Swift
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Designing a Modern Swift Network Stack, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [MagazineLayout](https://github.com/airbnb/MagazineLayout) — iOS Dev Weekly · Issue 383 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `21st December 2018`
  **NeKI brief:** The page covers “MagazineLayout” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Automate your library releases with Fastlane](https://mar.codes/2018-11-14/Automate-open-source-libraries-releases-with-fastlane) — iOS Dev Weekly · Issue 381 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Objective-C & Cocoa
  **Published:** `7th December 2018`
  **NeKI brief:** It’s easy to forget that fastlane can automate much more than code signing and App Store releases. What about using it to release new versions of open source libraries you maintain to CocoaPods? Marcos Griselli shows us how.
- [snapshot testing library](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 381 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `7th December 2018`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [FloatingPanel](https://github.com/SCENEE/FloatingPanel) — iOS Dev Weekly · Issue 375 — Source repository · Topics: Developer Tools · Maps & Location · Objective-C & Cocoa
  **Published:** `26th October 2018`
  **NeKI brief:** Examines A clean and easy-to-use floating panel UI component for iOS - scenee/FloatingPanel. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Finally, a complete course on advanced iOS architecture](http://matteomanferdini.com/ios-architect) — iOS Dev Weekly · Issue 374 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `19th October 2018`
  **NeKI brief:** Walks through Finally, a complete course on advanced iOS architecture with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [Building iOS dependencies with Carthage](https://blog.kulman.sk/building-ios-depedencies-with-carthage) — iOS Dev Weekly · Issue 374 — Article · Topics: Dependency Injection · Objective-C & Cocoa
  **Published:** `19th October 2018`
  **NeKI brief:** Explores Building iOS dependencies with Carthage in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Sizes](https://github.com/marcosgriselli/Sizes) — iOS Dev Weekly · Issue 373 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `12th October 2018`
  **NeKI brief:** Examines View your app on different device and font sizes . Contribute to marcosgriselli/Sizes development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Migrating to Swift](https://jjrscott.com/migrating-to-swift) — iOS Dev Weekly · Issue 373 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `12th October 2018`
  **NeKI brief:** Examines Migrating a very old project from Object-C to Swift. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift in 2018](https://www.jetbrains.com/research/devecosystem-2018/swift-objc) — iOS Dev Weekly · Issue 372 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `5th October 2018`
  **NeKI brief:** Explores Swift in 2018 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [disabling all warnings](https://guides.cocoapods.org/syntax/podfile.html) — iOS Dev Weekly · Issue 369 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Objective-C & Cocoa
  **Published:** `14th September 2018`
  **NeKI brief:** Examines CocoaPods Guides - Podfile Syntax Reference v1.16.1. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this little hack](https://gist.github.com/arturgrigor/10d25baf362cab984fc8c1093364ccfb) — iOS Dev Weekly · Issue 369 — Source repository · Topics: Developer Community & Business · Developer Tools · Objective-C & Cocoa
  **Published:** `14th September 2018`
  **NeKI brief:** Examines I’ve never been a big fan of disabling all warnings when importing a CocoaPod, so I was interested to see this little hack from Artur Grigor which allows specific warnings to be turned off for a pod. Of course, a better Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Dynamic Features in Swift](https://www.raywenderlich.com/5743-dynamic-features-in-swift) — iOS Dev Weekly · Issue 367 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `31st August 2018`
  **NeKI brief:** Examines In this tutorial, you’ll learn to use dynamic features in Swift to write clean code, create code clarity and resolve unforeseen issues quickly. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Shaun Musgrave](https://github.com/amirrajan/survivingtheappstore/blob/master/manuscript/touch-arcade-interview.md) — iOS Dev Weekly · Issue 367 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Graphics, Media & Games
  **Published:** `31st August 2018`
  **NeKI brief:** This free ebook from Amir Rajan looks great. The first few chapters go through some tips and techniques for running an App Store game business, but then the book switches into transcripts of interviews with popular iOS game developers and others in the…
- [to 13](https://searchads.apple.com/storefronts) — iOS Dev Weekly · Issue 366 — Article · Topics: Objective-C & Cocoa
  **Published:** `24th August 2018`
  **NeKI brief:** The Apple Ads page lists App Store countries and regions, documenting the storefront availability relevant to app marketers and developers.
- [Apple](https://search.developer.apple.com/appsearch-validation-tool) — iOS Dev Weekly · Issue 364 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `10th August 2018`
  **NeKI brief:** Explains App Search API Validation Tool with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [being removed](https://www.macstories.net/news/apple-announces-apps-and-in-app-purchases-will-be-removed-from-its-affiliate-program-october-1st) — iOS Dev Weekly · Issue 363 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `3rd August 2018`
  **NeKI brief:** The article reports Apple's announcement that apps and in-app purchases would be removed from its affiliate programme and explains the change for developers and publishers.
- [Videos from ADDC 2018](https://www.youtube.com/playlist?list=PLwR4QwnnbBuLHBfsD0Spj6hAcI4yT3uib) — iOS Dev Weekly · Issue 363 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `3rd August 2018`
  **NeKI brief:** ADDC was only a couple of weeks ago in Barcelona, but already there’s a full selection of conference videos from it. As you might imagine from the title of the conference there’s a good mix of design/development talks here.
- [ARM based Macs](http://shapeof.com/archives/2018/6/marzipan_to_arm_on_mac.html) — iOS Dev Weekly · Issue 358 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th June 2018`
  **NeKI brief:** The article discusses ARM-based Macs and the possible platform and software consequences of Apple's processor transition.
- [Apple Silently Launched Creative Testing in App Store Search Ads](https://asostack.com/apple-secretly-launched-creative-testing-in-app-store-search-ads-761a9f7b8abb) — iOS Dev Weekly · Issue 354 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Mobile marketers and developers can as of now test different Apple Search Ads assets in the App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [git branch and clean/dirty status](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/daveverwer.zsh-theme) — iOS Dev Weekly · Issue 354 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st June 2018`
  **NeKI brief:** Examines git branch and clean/dirty status, focusing on nice tip from marc palmer on including various information in your terminal prompt. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Trusting Popular SDKs](https://github.com/trusting-sdks/https) — iOS Dev Weekly · Issue 352 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** The page covers “Trusting Popular SDKs” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [dangers of trusting SDKs](https://krausefx.com/blog/trusting-sdks) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** The article explains the security dangers of trusting third-party SDKs and the access those dependencies can have inside an app.
- [Creating Success, Together](https://cate.blog/2018/05/08/creating-success-together) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** Examines This six part series (1, 2, 3, 4, 5, 6) of posts from Cate Huston that wrapped up last week is definitely worth a read. She starts by talking about developer and team success, but then moves on to consider the problem mo Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [1](https://cate.blog/2018/04/03/whose-expectations-are-those-anyway) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** Examines This six part series (1, 2, 3, 4, 5, 6) of posts from Cate Huston that wrapped up last week is definitely worth a read. She starts by talking about developer and team success, but then moves on to consider the problem mo Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [2](https://cate.blog/2018/04/10/how-do-developers-define-success) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** Examines This is part 2 of a series of blog posts based on a talk I prepared called Successfully Derailed Product. It’s about the ways in which we define and talk about “success. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [3](https://cate.blog/2018/04/17/how-do-teams-define-success) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** Presents 3, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [4](https://cate.blog/2018/04/24/how-do-users-define-success) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** This six part series (1, 2, 3, 4, 5, 6) of posts from Cate Huston that wrapped up last week is definitely worth a read. She starts by talking about developer and team success, but then moves on to consider the problem more broadly. I found the research and…
- [5](https://cate.blog/2018/05/01/how-should-we-define-success) — iOS Dev Weekly · Issue 352 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2018`
  **NeKI brief:** The article considers how success should be defined and offers a concrete reflection on evaluating outcomes in professional and creative work.
- [Retrobatch](http://shapeof.com/archives/2018/5/retrobatch_public_beta.html) — iOS Dev Weekly · Issue 351 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `11th May 2018`
  **NeKI brief:** This is a new tool from Gus Mueller (creator of Acorn) looks very cool. Think of it like Automator for image processing. If you’re regularly processing assets for your apps, you’ll want to check out this public beta.
- [The Laws of Core Data](http://davedelong.com/blog/2018/05/09/the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [follow up](http://www.cimgf.com/2018/05/10/response-the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Responds to Core Data design rules with practical clarification about model boundaries, persistence behavior, and application architecture. Use it to compare competing guidance and identify trade-offs, then verify assumptions against current Core Data documentation and project constraints.
- [Overcast: The privacy update](https://marco.org/2018/04/27/overcast42) — iOS Dev Weekly · Issue 350 — Article · Topics: Objective-C & Cocoa · Security & Privacy
  **Published:** `4th May 2018`
  **NeKI brief:** Presents Overcast: The privacy update, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Simplifying Collection View Delegates with Functional Programming](http://danieltull.co.uk/blog/2018/04/13/simplifying-uicollectionviewflowlayout-delegate-method-usage-with-functional-programming) — iOS Dev Weekly · Issue 348 — Article · Topics: Functional Programming · Objective-C & Cocoa · Swift
  **Published:** `20th April 2018`
  **NeKI brief:** Explains Simplifying Collection View Delegates with Functional Programming, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [Level up Your iOS Development Skills - 20% Off!](https://nsscreencast.com/r/iosdevweekly-53152) — iOS Dev Weekly · Issue 347 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th April 2018`
  **NeKI brief:** Explains High Quality Screencasts for iOS Developers, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Swift Static Libraries in CocoaPods 1.5](http://blog.cocoapods.org/CocoaPods-1.5.0) — iOS Dev Weekly · Issue 346 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `6th April 2018`
  **NeKI brief:** Explores Swift Static Libraries in CocoaPods 1.5 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [open source framework](https://github.com/hezi/Storytime) — iOS Dev Weekly · Issue 346 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `6th April 2018`
  **NeKI brief:** Examines Storytime is a framework to parse and render Interface Builder Storyboard files. MIT Licensed - hezi/Storytime. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [last one](https://www.youtube.com/watch?v=0wIiDnjz4X4) — iOS Dev Weekly · Issue 344 — Video · Topics: Objective-C & Cocoa
  **Published:** `23rd March 2018`
  **NeKI brief:** Let’s take a field trip to Chicago next Tuesday? The timing isn’t so strange as there have been March events many times before (the last one was only 2 years ago in 2016) but the location is slightly unusual given they just built a dedicated theatre on their…
- [new framework introduced](https://9to5mac.com/2018/02/06/ios-11-3-beta-2-new-classkit-framework) — iOS Dev Weekly · Issue 344 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd March 2018`
  **NeKI brief:** Reports the introduction of ClassKit in an iOS 11.3 beta and its educational-app context. Useful historical background for Apple’s school-focused APIs, with availability and behavior checked against current SDK references.
- [the documentation](http://researchkit.org/docs/docs/ChartsAndGraphs/ChartsAndGraphs.html) — iOS Dev Weekly · Issue 343 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th March 2018`
  **NeKI brief:** Presents the documentation, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [WatchKit is a sweet solution that will only ever give us baby apps](https://marco.org/2018/02/26/watchkit-baby-apps) — iOS Dev Weekly · Issue 341 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd March 2018`
  **NeKI brief:** Marco Arment with an article on WatchKit never being able to live up to the capabilities of the platform for as long as Apple are not also using it, and therefore feeling the pain of it.
- [Just Controllers](http://khanlou.com/2018/02/just-controllers) — iOS Dev Weekly · Issue 340 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `23rd February 2018`
  **NeKI brief:** Soroush Khanlou continues the discussion on iOS application architecture, specifically the case of not using UIViewController for everything, and instead asks the question whether it’s better to use a simpler controller in some cases?
- [Defending your app from copies and clones](https://marco.org/2018/02/22/your-app-was-copied) — iOS Dev Weekly · Issue 340 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd February 2018`
  **NeKI brief:** Marco Arment on taking a sensible approach to defending your IP and copyright. There’s bad news in here if you’re expecting to be overwhelmed with power and influence by being in the right on a matter of protecting your IP, but everything in this article is…
- [add “Run Script” phases](http://blog.cocoapods.org/CocoaPods-1.4.0) — iOS Dev Weekly · Issue 339 — Article · Topics: Objective-C & Cocoa
  **Published:** `16th February 2018`
  **NeKI brief:** Examines It’s a serious problem, but it’s also worth remembering that including any third party framework in your app presents risk, even without a MITM attack like this. How many of us really look at the internals of a framework Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Serialization - Speed and Size](https://holtwick.de/blog/serialization) — iOS Dev Weekly · Issue 339 — Tutorial · Topics: Developer Community & Business · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `16th February 2018`
  **NeKI brief:** Walks through Serialization - Speed and Size with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [Top-down iOS error architecture](https://medium.com/@londeix/top-down-error-architecture-d8715a28d1ad) — iOS Dev Weekly · Issue 338 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `9th February 2018`
  **NeKI brief:** Examines Top-down iOS error architecture, focusing on what’s the best way to handle non-trivial errors in an app? bartosz polaczyk argues that a system that passes the error…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Some useful URL schemes in Xcode 9](https://cocoaengineering.com/2018/01/01/some-useful-url-schemes-in-xcode-9) — iOS Dev Weekly · Issue 336 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `26th January 2018`
  **NeKI brief:** Explores Some useful URL schemes in Xcode 9 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [AppFolder: 🗂](https://github.com/dreymonde/AppFolder) — iOS Dev Weekly · Issue 336 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `26th January 2018`
  **NeKI brief:** Examines 🗂 Never use NSSearchPathForDirectoriesInDomains again - dreymonde/AppFolder. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [follow up post](https://marco.org/2018/01/17/end-of-conference-era) — iOS Dev Weekly · Issue 335 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `19th January 2018`
  **NeKI brief:** follow up post. This link is retained as a technical reading lead for Apple-platform development.
- [LSAnimator and CoreAnimator](https://github.com/Lision/LSAnimator) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `5th January 2018`
  **NeKI brief:** Provides chained animation utilities for iOS, including reusable animation composition around UIKit-style transitions. Inspect it when comparing abstractions that make sequential or concurrent visual effects easier to express.
- [Kotlin/Objective-C Interoperability](https://blog.jetbrains.com/kotlin/2017/11/kotlinnative-v0-4-released-objective-c-interop-webassembly-and-more) — iOS Dev Weekly · Issue 328 — Article · Topics: Objective-C & Cocoa · Systems Programming · Testing
  **Published:** `24th November 2017`
  **NeKI brief:** Examines We’re happy to announce the release of Kotlin/Native v0.4, KotlinConf 2017 edition! This release adds support for accessing Objective-C APIs on iOS and macOS, WebAssembly target pl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Most Disliked Programming Languages?](https://stackoverflow.blog/2017/10/31/disliked-programming-languages) — iOS Dev Weekly · Issue 328 — Article · Topics: Objective-C & Cocoa
  **Published:** `24th November 2017`
  **NeKI brief:** Examines What are the Most Disliked Programming Languages? - Stack Overflow. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SkeletonView](https://github.com/Juanpe/SkeletonView) — iOS Dev Weekly · Issue 327 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th November 2017`
  **NeKI brief:** SkeletonView adds loading placeholders and skeleton animations to iOS interfaces. Follow its source for concrete table, collection, and view-layout integration patterns, while checking compatibility with current UIKit and Swift versions.
- [The Truth Behind Massive View Controllers](http://aplus.rs/2017/much-ado-about-ios-app-architecture) — iOS Dev Weekly · Issue 326 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th November 2017`
  **NeKI brief:** Explores The Truth Behind Massive View Controllers in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Developing For Apple Watch](http://benjaminmayo.co.uk/developing-for-apple-watch) — iOS Dev Weekly · Issue 324 — Article · Topics: Objective-C & Cocoa
  **Published:** `27th October 2017`
  **NeKI brief:** Explores Developing For Apple Watch in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [A State Container-based iOS Architecture](https://jobandtalent.engineering/ios-architecture-an-state-container-based-approach-4f1a9b00b82e) — iOS Dev Weekly · Issue 323 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `20th October 2017`
  **NeKI brief:** Explores A State Container-based iOS Architecture in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) — iOS Dev Weekly · Issue 323 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `20th October 2017`
  **NeKI brief:** The page covers “ViewAnimator” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Uber’s Secret Permissions to Copy Your Phone Screen](https://gizmodo.com/researchers-uber-s-ios-app-had-secret-permissions-that-1819177235) — iOS Dev Weekly · Issue 322 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th October 2017`
  **NeKI brief:** Examines To improve functionality between Uber’s app and the Apple Watch, Apple allowed Uber to use a powerful tool that could record a user’s iPhone screen, even. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [What we need from Apple to make standalone Apple Watch podcast apps](https://marco.org/2017/09/24/what-watch-podcast-apps-need) — iOS Dev Weekly · Issue 321 — Podcast · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `6th October 2017`
  **NeKI brief:** If you’re a listener of Under the Radar this won’t be a surprising article for you to read as Marco and David have discussed this issue in depth over the last few weeks (especially in this episode). I’m still not super optimistic about watchOS as an app…
- [Under the Radar](https://www.relay.fm/radar) — iOS Dev Weekly · Issue 321 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th October 2017`
  **NeKI brief:** The Under the Radar show page provides publicly readable episode listings and descriptions about software development and independent app businesses.
- [this episode](https://www.relay.fm/radar/98) — iOS Dev Weekly · Issue 321 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th October 2017`
  **NeKI brief:** Presents this episode, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Lifetime Tracker](https://github.com/krzysztofzablocki/LifetimeTracker) — iOS Dev Weekly · Issue 320 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `29th September 2017`
  **NeKI brief:** Examines Find retain cycles / memory leaks sooner. Contribute to krzysztofzablocki/LifetimeTracker development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Crafting Great Reverse-DNS Identifiers 🆔](https://littlebitesofcocoa.com/317-crafting-great-reverse-dns-identifiers) — iOS Dev Weekly · Issue 319 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `22nd September 2017`
  **NeKI brief:** Examines Apple platforms make heavy use of "reverse-DNS" identifiers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Hybrid Architecture](https://m.signalvnoise.com/basecamp-3-for-ios-hybrid-architecture-afc071589c25) — iOS Dev Weekly · Issue 318 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `15th September 2017`
  **NeKI brief:** It’s been a while since we had any articles about hybrid iOS apps, so this article by Zach Waugh is a nice update of how Basecamp have continued to use this technique. It’s an in depth article, and for this kind of app it makes a lot of sense.
- [ARCore being announced yesterday](https://techcrunch.com/2017/08/29/google-shows-off-arcore-its-answer-to-apples-arkit) — iOS Dev Weekly · Issue 316 — Article · Topics: Objective-C & Cocoa · Spatial Computing
  **Published:** `1st September 2017`
  **NeKI brief:** Examines Google has been experimenting with smartphone AR since it first showed off Project Tango in 2014. Three years later the company has some great technology to show off, but very litt. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Codable Dates](https://littlebitesofcocoa.com/316-codable-dates) — iOS Dev Weekly · Issue 315 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Swift
  **Published:** `25th August 2017`
  **NeKI brief:** Examines In Bite 315 (https://littlebitesofcocoa.com/315) we started looking at the new Codable protocol in Swift 4. Today we'll learn how to work with Date types when encoding and deco. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ArcKit](https://github.com/sobri909/ArcKit) — iOS Dev Weekly · Issue 312 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `4th August 2017`
  **NeKI brief:** Examines Location, motion, and activity recording framework for iOS - sobri909/LocoKit. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ADDC 2017 Videos](https://www.youtube.com/playlist?list=PLwR4QwnnbBuJ9BqCGGCt07Ot65BCiA0r5) — iOS Dev Weekly · Issue 311 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `28th July 2017`
  **NeKI brief:** A wonderful set of videos from the ADD conference which was held last month in the beautiful city of Barcelona.
- [Cracking the code behind Apple’s App Store promo card design](http://blog.equinux.com/2017/07/cracking-the-code-behind-apples-app-store-promo-card-design) — iOS Dev Weekly · Issue 311 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `28th July 2017`
  **NeKI brief:** A wonderful set of videos from the ADD conference which was held last month in the beautiful city of Barcelona.
- [Get automatic error reporting for your iOS apps 🚀](https://www.bugsnag.com/platforms/ios-crash-reporting) — iOS Dev Weekly · Issue 310 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `21st July 2017`
  **NeKI brief:** Examines Unlock performance & error monitoring for your application with BugSnag. Monitor, analyze, and optimize in real time to ensure a seamless user experience. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using SpriteKit to create animations in Swift](https://www.swiftbysundell.com/posts/using-spritekit-to-create-animations-in-swift) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Using SpriteKit to create animations in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Xcode Asset Catalog Improvements 🎨](https://littlebitesofcocoa.com/312-asset-catalog-improvements) — iOS Dev Weekly · Issue 306 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `23rd June 2017`
  **NeKI brief:** Examines Asset Catalogs have been around for a few Xcode releases. They're a great way for us to organize and configure graphical assets (among many other things) for our app. Today we&. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Screen Edges in iOS 11](https://littlebitesofcocoa.com/310-screen-edges-in-ios-11) — iOS Dev Weekly · Issue 306 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd June 2017`
  **NeKI brief:** It’s the little features that sometimes make all the difference. I love this!
- [Shouldn’t Companies Apply to You? - Try Hired](https://hired.com/join) — iOS Dev Weekly · Issue 306 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `23rd June 2017`
  **NeKI brief:** Hired brings job offers to you, so you can stop wasting your time applying. Apply to 6,000+ companies at once on the platform. 🤖
- [UIFontMetrics 📐](https://littlebitesofcocoa.com/309-uifontmetrics) — iOS Dev Weekly · Issue 305 — Article · Topics: Accessibility · Objective-C & Cocoa
  **Published:** `16th June 2017`
  **NeKI brief:** Explores UIFontMetrics 📐 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Tiny Crayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) — iOS Dev Weekly · Issue 304 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `9th June 2017`
  **NeKI brief:** If you’re looking for an easy-to-use library for image masking / quick eraser tools, then look no further. Not only is Tiny Crayon completely free, but the documentation is spot on. 👌🏼 You’ll find examples both in Swift and Objective-C. Definitely recommend…
- [UIDebuggingInformationOverlay](http://ryanipete.com/blog/ios/swift/objective-c/uidebugginginformationoverlay) — iOS Dev Weekly · Issue 303 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2nd June 2017`
  **NeKI brief:** Explores UIDebuggingInformationOverlay in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [CocoaDebugKit](https://github.com/Patrick-Kladek/CocoaDebugKit) — iOS Dev Weekly · Issue 303 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2nd June 2017`
  **NeKI brief:** Presents CocoaDebugKit, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [“Super. Computer.”](https://web.archive.org/web/20170521182751/https://www.apple.com/ipad-pro) — iOS Dev Weekly · Issue 302 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th May 2017`
  **NeKI brief:** Examines iPad Pro delivers epic power, in 12.9-inch and 9.7-inch sizes. Discover the A9X Chip, Advanced Retina display, 12MP iSight camera, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Better GitHub Searching 🔎](http://indiestack.com/2017/05/better-github-searching) — iOS Dev Weekly · Issue 301 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `19th May 2017`
  **NeKI brief:** The article presents techniques for improving GitHub searches and finding relevant repositories and code more efficiently.
- [A Simple Undo/Redo Implementation in Swift](http://blog.benjamin-encz.de/post/simple-undo-redo-swift) — iOS Dev Weekly · Issue 301 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th May 2017`
  **NeKI brief:** Explores A Simple Undo/Redo Implementation in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Protocols and MVVM in Swift to avoid repetition](https://sudo.isl.co/swift-mvvm-protocols) — iOS Dev Weekly · Issue 300 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `12th May 2017`
  **NeKI brief:** Explores Protocols and MVVM in Swift to avoid repetition in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [LicensePlist](https://github.com/mono0926/LicensePlist) — iOS Dev Weekly · Issue 300 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `12th May 2017`
  **NeKI brief:** Examines LicensePlist, focusing on most of us use open-source libraries, and most oss asks that a license be included in apps that use them. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [TestDrive](https://github.com/JohnSundell/TestDrive) — iOS Dev Weekly · Issue 298 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `28th April 2017`
  **NeKI brief:** Examines Quickly try out any Swift pod or framework in a playground - JohnSundell/TestDrive. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Using protocol compositon for dependency injection](http://merowing.info/2017/04/using-protocol-compositon-for-dependency-injection) — iOS Dev Weekly · Issue 297 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `21st April 2017`
  **NeKI brief:** Explores Using protocol compositon for dependency injection in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Customizing Collection View Cell Insertion Animations](https://littlebitesofcocoa.com/306-customizing-collection-view-cell-insertion-animations) — iOS Dev Weekly · Issue 295 — Article · Topics: Objective-C & Cocoa
  **Published:** `7th April 2017`
  **NeKI brief:** UICollectionView has always been a powerhouse for supporting rich UI. Custom layouts are pretty well understood by this point, but what about animating cells as they appear? Jake Marsh gives us a handy guide to make sure that our cells look amazing as they…
- [without some of the existing integrations](https://workflow.is/whatsnew) — iOS Dev Weekly · Issue 293 — Article · Topics: Objective-C & Cocoa
  **Published:** `24th March 2017`
  **NeKI brief:** Examines Download Shortcuts by Apple on the App Store. See screenshots, ratings and reviews, user tips, and more apps like Shortcuts. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [System Level Breakpoints in Swift](http://indiestack.com/2017/03/system-level-breakpoints-in-swift) — iOS Dev Weekly · Issue 293 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `24th March 2017`
  **NeKI brief:** Explores System Level Breakpoints in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [CocoaDocs documentation sun-setting](http://blog.cocoapods.org/CocoaDocs-Documentation-Sunsetting) — iOS Dev Weekly · Issue 292 — Article · Topics: Objective-C & Cocoa · Personal Essays
  **Published:** `17th March 2017`
  **NeKI brief:** This announcement explains why hosted CocoaDocs documentation was being retired and what that meant for projects relying on generated pod documentation. It is useful historical context for the fragility and ownership costs of community documentation infrastructure.
- [Swift Ownership Manifesto](https://github.com/apple/swift/blob/master/docs/OwnershipManifesto.md) — iOS Dev Weekly · Issue 289 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** So ARC is baked directly into the core of Swift and I’d imagine we’re all pretty happy with that? I know that as an iOS developer I certainly am. But Swift is not just for writing iOS and macOS apps, it’s also designed as a systems language and that can…
- [Overcast 3: Design walkthrough](https://marco.org/2017/02/20/overcast3) — iOS Dev Weekly · Issue 289 — Article · Topics: Objective-C & Cocoa
  **Published:** `24th February 2017`
  **NeKI brief:** You wouldn’t believe how many customers have asked me to add features that were already there, or couldn’t find basic functions like deleting episodes, because they weren’t apparent enough in the design.
- [Refactor Swift, Objective-C and C++ with AppCode](https://www.jetbrains.com/objc/whatsnew) — iOS Dev Weekly · Issue 288 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** Explores Refactor Swift, Objective-C and C++ with AppCode in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Whither Swift?](http://lapcatsoftware.com/articles/whither-swift.html) — iOS Dev Weekly · Issue 288 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** The article reflects on Swift's direction and development ecosystem, providing a historical technical perspective on the language.
- [My Mac app icon design workflow](https://bjango.com/articles/macappiconworkflow) — iOS Dev Weekly · Issue 286 — Article · Topics: Objective-C & Cocoa
  **Published:** `3rd February 2017`
  **NeKI brief:** The article documents a practical workflow for designing Mac app icons, from initial concept through production assets.
- [Traits](https://github.com/krzysztofzablocki/Traits) — iOS Dev Weekly · Issue 282 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `6th January 2017`
  **NeKI brief:** A new library from Krzysztof Zabłocki for dynamically modifying your app at runtime, even supporting Injection (mentioned earlier in this issue). He’s also put together a blog post with some thoughts on the why and how of how this came to be developed.
- [GlueKit](https://github.com/lorentey/GlueKit) — iOS Dev Weekly · Issue 277 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `18th November 2016`
  **NeKI brief:** Examines GlueKit, focusing on do you miss kvo in swift? well this is going to be worth a look. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [spoke recently about how it works](https://www.youtube.com/watch?v=98jsahDV4ts) — iOS Dev Weekly · Issue 277 — Video · Topics: Objective-C & Cocoa · Swift
  **Published:** `18th November 2016`
  **NeKI brief:** Examines spoke recently about how it works, focusing on do you miss kvo in swift? well this is going to be worth a look. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Our Experience with App Store Search Ads](http://blog.supertop.co/post/153268162187/search-ads) — iOS Dev Weekly · Issue 277 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `18th November 2016`
  **NeKI brief:** Examines Apple started rolling out Search Ads on the U.S. App Store last month, offering developers and marketers an opportunity to promote their apps on the search screen of the iOS App St. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [markdown parsers](https://github.com/indragiek/CocoaMarkdown) — iOS Dev Weekly · Issue 275 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Examines markdown parsers, focusing on loïc lecrenier with a new markdown parser, written in pure swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [How to Use NSTouchBar on macOS](https://www.littlebitesofcocoa.com/281-touch-bar-basics) — iOS Dev Weekly · Issue 275 — Article · Topics: Objective-C & Cocoa
  **Published:** `4th November 2016`
  **NeKI brief:** Examines During yesterday's MacBook Pro event, Apple announced a fantastic new piece of hardware called the Touch Bar. It's a 1085 x 30 point matte-finish Retina screen that sits ab. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [significant thought and effort](http://shapeof.com/archives/2016/11/notes_on_working_with_nstouchbar_apis.html) — iOS Dev Weekly · Issue 275 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `4th November 2016`
  **NeKI brief:** The article records detailed thoughts on working with NSTouchBar APIs and the engineering effort required to integrate them.
- [CocoaPods 1.1](http://blog.cocoapods.org/CocoaPods-1.1.0) — iOS Dev Weekly · Issue 273 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `21st October 2016`
  **NeKI brief:** Explores CocoaPods 1.1 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Video App Feedback](https://www.youtube.com/playlist?list=PLm5nKVoMBy49B-u868rgRCOMLVgUwskdT) — iOS Dev Weekly · Issue 273 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `21st October 2016`
  **NeKI brief:** Examines Matt’s feedback on iOS app design captured on video. 📋 Submit your app: https://bit.ly/appcritique 🐦 Follow Matt on Twitter: @mb 👅 Hire Lickability to improv. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Command Line Swift](http://www.russbishop.net/command-line-swift) — iOS Dev Weekly · Issue 270 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** I think we’re all prone to write ourselves little tools to make our lives easier. In fact, the app I work on these days was a command line Ruby script for many years before it became a web app! I even considered writing it in Objective-C but decided against…
- [Implementing Theming with CostumeKit](https://littlebitesofcocoa.com/270-implementing-theming-with-costumekit) — iOS Dev Weekly · Issue 270 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th September 2016`
  **NeKI brief:** Examines We've looked at protocols in Swift in Bite #232 (https://littlebitesofcocoa.com/232), but we haven't really seen a ton of "real world" examples. Today we'll c. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swifty Delegates](http://khanlou.com/2016/09/swifty-delegates) — iOS Dev Weekly · Issue 270 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** Explores Swifty Delegates in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [HubFramework: Spotify’s component-driven UI framework for iOS](https://github.com/spotify/HubFramework) — iOS Dev Weekly · Issue 270 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** Examines HubFramework: Spotify’s component-driven UI framework for iOS, focusing on talking of component based ui frameworks, this is brand new from spotify. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [demo app](https://github.com/spotify/HubFramework/tree/master/demo) — iOS Dev Weekly · Issue 270 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** Examines demo app, focusing on talking of component based ui frameworks, this is brand new from spotify. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Say It Ain’t So: Implementing Speech Recognition in Your App](https://realm.io/news/tryswift-marc-brown-say-it-aint-so-implementing-speech-recognition) — iOS Dev Weekly · Issue 270 — Article · Topics: App Intents & System Surfaces · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `30th September 2016`
  **NeKI brief:** Explores Say It Ain’t So: Implementing Speech Recognition in Your App in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [The App Store Keyword Algorithm Update Takes Effect](http://incipia.co/post/mobile-app-marketing-industry-updates/the-app-store-keyword-algorithm-update-takes-effect) — iOS Dev Weekly · Issue 268 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** Explains The App Store Keyword Algorithm Update Takes Effect, focusing on the concrete iOS implementation technique and the trade-offs relevant to production applications.
- [Overcast trying ads, dark theme now free](https://marco.org/2016/09/09/overcast-ads) — iOS Dev Weekly · Issue 268 — Article · Topics: Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** The post discusses Overcast experimenting with advertising and making its dark theme available for free.
- [Senior Entwickler (m/w) iOS, Arvato Systems S4M GmbH, Rheda-Wiedenbrück](https://myjobs-de.becruiter.net/jobagent/search/job_details.aspx?jobid=262414&jb=cyoc) — iOS Dev Weekly · Issue 268 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** We are working for media companies. Join us to make our Apps even more successful!
- [Building an Entire iPhone App in an Hour](https://www.youtube.com/watch?v=sA5LKdY4zNk) — iOS Dev Weekly · Issue 268 — Video · Topics: Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** Building an Entire iPhone App in an Hour. This link is retained as a technical reading lead for Apple-platform development.
- [Relayout](https://github.com/stevestreza/Relayout) — iOS Dev Weekly · Issue 265 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th August 2016`
  **NeKI brief:** The page covers “Relayout” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Swift 3 Changes in Beta 6](https://swifting.io/blog/2016/08/17/22-swift-3-access-control-beta-6) — iOS Dev Weekly · Issue 264 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `18th August 2016`
  **NeKI brief:** Explores Swift 3 Changes in Beta 6 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Package.swift Manual](http://blog.krzyzanowskim.com/2016/08/09/package-swift-manual) — iOS Dev Weekly · Issue 264 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `18th August 2016`
  **NeKI brief:** Examines Here is documentation for SPM manifest file Package.swift. I couldn't find a list of possible configuration values for Package.swift, so I created one, for future reference. I. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SPM documentation](https://github.com/apple/swift-package-manager/tree/master/Documentation) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `18th August 2016`
  **NeKI brief:** The page covers “SPM documentation” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [PMHTTP](https://github.com/postmates/PMHTTP) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `18th August 2016`
  **NeKI brief:** Examines PMHTTP, focusing on kevin ballard with a new networking library written in swift but compatible with objective-c, pmhttp. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [StyleKit](https://github.com/146BC/StyleKit) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th August 2016`
  **NeKI brief:** The GitHub repository provides StyleKit source code, a concrete open-source project that can be inspected and reused by developers.
- [reference implementation](https://github.com/tomkowz/NetworkLayerExample) — iOS Dev Weekly · Issue 263 — Source repository · Topics: Architecture · Core Data · Developer Tools
  **Published:** `11th August 2016`
  **NeKI brief:** Examines reference implementation, focusing on tomasz szulc on building network architecture that isn’t dependent on any third party libraries, or any apple provided…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Real World Flux Architecture on iOS](http://blog.benjamin-encz.de/post/real-world-flux-ios) — iOS Dev Weekly · Issue 260 — Article · Topics: Architecture · Objective-C & Cocoa · Product Design
  **Published:** `22nd July 2016`
  **NeKI brief:** Examines I hadn’t come across Flux before reading this detailed article from Benjamin Encz on how they have been adopting it. What I really like is that it’s all explained using a real world app to describe the problems they are Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [SiriKit – Can you outsmart provided Intents?](https://swifting.io/blog/2016/07/18/20-sirikit-can-you-outsmart-provided-intents) — iOS Dev Weekly · Issue 260 — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa · Swift
  **Published:** `22nd July 2016`
  **NeKI brief:** Explores SiriKit – Can you outsmart provided Intents? in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [only 11%](https://medium.com/@ryanolsonk/are-the-top-apps-using-swift-42e880e7727f) — iOS Dev Weekly · Issue 259 — Article · Topics: Networking · Objective-C & Cocoa · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Explains Are the Top Apps Using Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Efficient iOS Version Checking](https://pspdfkit.com/blog/2016/efficient-iOS-version-checking) — iOS Dev Weekly · Issue 259 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** How are you gating code for different OS versions? There have been many techniques for this over the years so it might be worth brushing up on them. Of course, if you’re in Swift it’s easy with #available but things aren’t quite so clean in Objective-C.
- [pre-fetching](https://littlebitesofcocoa.com/241-uicollectionview-cell-pre-fetching) — iOS Dev Weekly · Issue 258 — Article · Topics: Objective-C & Cocoa
  **Published:** `8th July 2016`
  **NeKI brief:** I missed this when it first got released but if you’re looking for an iOS 9 compatible version of the new pre-fetching features of UICollectionView and UITableView, then you’re in luck. Alexander Grebenyuk put together this library which does exactly that.
- [The Great Swift 3 Rename](https://littlebitesofcocoa.com/243-the-great-swift-3-rename) — iOS Dev Weekly · Issue 257 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `1st July 2016`
  **NeKI brief:** Explores The Great Swift 3 Rename in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Nullable Edge Cases](http://indiestack.com/2016/06/nullable-edge-cases) — iOS Dev Weekly · Issue 254 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `10th June 2016`
  **NeKI brief:** Explores Nullable Edge Cases in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [MarsEdit](https://www.red-sweater.com/marsedit) — iOS Dev Weekly · Issue 254 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `10th June 2016`
  **NeKI brief:** Explores MarsEdit in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [“Where’s the App for That?” – Fixing App Store Discovery](https://www.macstories.net/stories/wheres-the-app-for-that-fixing-app-store-discovery) — iOS Dev Weekly · Issue 254 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `10th June 2016`
  **NeKI brief:** Examines When the iPhone debuted in 2007, it was by no means a forgone conclusion that there would ever be an App Store. Steve Jobs reportedly resisted the idea over concerns that it would. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swifty Objective-C](https://pspdfkit.com/blog/2016/swifty-objective-c) — iOS Dev Weekly · Issue 253 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `3rd June 2016`
  **NeKI brief:** Explores Swifty Objective-C in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [relying on those dynamic Objective-C roots](http://furbo.org/2016/05/20/adulterated-swift) — iOS Dev Weekly · Issue 252 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `27th May 2016`
  **NeKI brief:** Explores relying on those dynamic Objective-C roots in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [New Swift, Core Data and Cocoa Books](http://useyourloaf.com/blog/new-swift-core-data-and-cocoa-books) — iOS Dev Weekly · Issue 251 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `20th May 2016`
  **NeKI brief:** Collects book recommendations around Swift, Core Data, and Cocoa as a learning route. Treat editions as historical context and cross-check API guidance against current Apple documentation.
- [CocoaPods 1.0](http://blog.cocoapods.org/CocoaPods-1.0) — iOS Dev Weekly · Issue 250 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th May 2016`
  **NeKI brief:** This release announcement introduces CocoaPods 1.0 and the maturation of dependency management for Apple-platform projects. It provides historical context for the workflows and compatibility expectations that shaped modern Swift and Objective-C package integration.
- [CocoaPods app](http://blog.cocoapods.org/CocoaPods-App-1.0) — iOS Dev Weekly · Issue 250 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th May 2016`
  **NeKI brief:** I first mentioned CocoaPods back in Issue 8 and my comment at the time was that “it has potential” 😄. I think we can safely say that it turned out to have more than just potential! My thanks to everyone who contributed to this project over the years and a…
- [migration guide](https://blog.cocoapods.org/CocoaPods-1.0-Migration-Guide) — iOS Dev Weekly · Issue 250 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th May 2016`
  **NeKI brief:** Examines The blog for CocoaPods.org the Cocoa Dependency Manager. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [search problems](http://techcrunch.com/2016/05/05/apples-app-store-search-is-completely-broken-right-now) — iOS Dev Weekly · Issue 249 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `6th May 2016`
  **NeKI brief:** Analyzes problems with App Store search during an early period. Follow it for historical storefront and ranking context, while treating the reported behavior as version-specific.
- [getting contributions](https://github.com/carekit-apple/CareKit/pulls) — iOS Dev Weekly · Issue 248 — Source repository · Topics: Developer Career & Practice · Developer Tools · Objective-C & Cocoa
  **Published:** `29th April 2016`
  **NeKI brief:** This week saw the release of CareKit, the partner to ResearchKit. While ResearchKit helps researchers gather data and manage content, CareKit is designed more to help patients with active management of their conditions. It’s available on GitHub right now and…
- [Xamarin’s acquisition](http://blogs.microsoft.com/blog/2016/02/24/microsoft-to-acquire-xamarin-and-empower-more-developers-to-build-apps-on-any-device) — iOS Dev Weekly · Issue 248 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `29th April 2016`
  **NeKI brief:** This announcement explains Microsoft's acquisition of Xamarin and its stated goal of making cross-platform app development available across devices. It provides historical context for the tooling, ecosystem, and strategic trade-offs behind Xamarin-based mobile development.
- [Xcode Search: the Hidden Gems](http://holko.pl/2016/04/26/xcode-search) — iOS Dev Weekly · Issue 248 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `29th April 2016`
  **NeKI brief:** Explains Xcode Search the Hidden Gems with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Design debugging](https://bjango.com/articles/designdebugging) — iOS Dev Weekly · Issue 248 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `29th April 2016`
  **NeKI brief:** Debugging is a very familiar concept for developers, but not so much for designers. Marc Edwards gives us some insight into the techniques he’s come up with for debugging his designs. Really interesting.
- [Presenting unanticipated errors to users](http://www.cocoawithlove.com/blog/2016/04/14/error-recovery-attempter.html) — iOS Dev Weekly · Issue 247 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Presenting errors to users is one of the trickiest things to get right in any app. Matt Gallagher follows up his previous article and this time takes a look at what to do when the user needs to be notified.
- [previous article](http://www.cocoawithlove.com/blog/2016/03/17/non-pure-errors.html) — iOS Dev Weekly · Issue 247 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Presenting errors to users is one of the trickiest things to get right in any app. Matt Gallagher follows up his previous article and this time takes a look at what to do when the user needs to be notified.
- [On paid App Store search results](https://marco.org/2016/04/21/paid-app-store-search) — iOS Dev Weekly · Issue 247 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Examines On paid App Store search results – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Paid Search for the App Store?](http://daringfireball.net/linked/2016/04/14/bloomberg-app-store-search) — iOS Dev Weekly · Issue 246 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th April 2016`
  **NeKI brief:** Examines Daring Fireball: Bloomberg: Apple Exploring Google-Like 'Paid Search' for App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Bridges of Siracusa County](http://www.russbishop.net/bridges-of-siracusa-county) — iOS Dev Weekly · Issue 245 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `8th April 2016`
  **NeKI brief:** Uses bridges in Siracusa County as a metaphor or narrative frame for software and engineering concerns. Useful as a reflective developer essay when the surrounding issue needs perspective rather than a direct API recipe.
- [his proposal](https://github.com/apple/swift-evolution/blob/master/proposals/0058-objectivecbridgeable.md) — iOS Dev Weekly · Issue 245 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `8th April 2016`
  **NeKI brief:** Russ Bishop with a post on his proposal for Swift classes to be able to expose an Objective-C friendly interface without having to affect the design of the Swift class. I also really like the notes at the end of the article about taking the time to write up…
- [The best table view controller](http://swiftandpainless.com/the-best-table-view-controller-mar-2016-edition) — iOS Dev Weekly · Issue 244 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `1st April 2016`
  **NeKI brief:** Dominik Hauser with a look at his current thinking about the best way to architect a table view controller. I like posts like this because they take a concept we’re all very familiar with and look at it with the new perspective that Swift gives us. I also…
- [Breaking Swift with reference counted structs](http://www.cocoawithlove.com/blog/2016/03/27/on-delete.html) — iOS Dev Weekly · Issue 244 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `1st April 2016`
  **NeKI brief:** Examines Matt Gallagher digs into the weeds of Swift structs and reference counting. It’s pretty obvious that you should never use some of the techniques in this article, but it makes an interesting read and you’ll definitely lea Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [meltdown of Node dependencies](http://www.theregister.co.uk/2016/03/23/npm_left_pad_chaos) — iOS Dev Weekly · Issue 243 — Tutorial · Topics: Dependency Injection · Developer Community & Business · Objective-C & Cocoa
  **Published:** `25th March 2016`
  **NeKI brief:** The report explains how the npm left-pad incident disrupted Node and Babel dependencies and exposed risks in package ecosystems.
- [Creating Swift Frameworks for iOS, watchOS, and tvOS](http://basememara.com/creating-cross-platform-swift-frameworks-ios-watchos-tvos-via-carthage-cocoapods) — iOS Dev Weekly · Issue 243 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `25th March 2016`
  **NeKI brief:** Explains Creating Swift Frameworks for iOS watchOS and tvOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Interaction density](https://bjango.com/articles/interactiondensity) — iOS Dev Weekly · Issue 242 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th March 2016`
  **NeKI brief:** The article explains interaction density and how interface controls and spacing affect usability in software design.
- [CloudKit Security model](http://blog.krzyzanowskim.com/2016/03/08/cloudkit-security) — iOS Dev Weekly · Issue 241 — Article · Topics: Objective-C & Cocoa · Persistence & Synchronisation · Security & Privacy
  **Published:** `11th March 2016`
  **NeKI brief:** This article examines CloudKit’s security model and the boundaries around shared application data. Follow it for concrete protection and trust considerations, while verifying current CloudKit APIs and entitlement behavior.
- [Over $45,000 is up for grabs in the tvOS App Challenge](https://applovin.com/appchallenge) — iOS Dev Weekly · Issue 240 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `4th March 2016`
  **NeKI brief:** Examines Reach over a billion daily users in mobile games. AppLovin helps consumer brands and gaming apps scale their business profitably. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [presented one of two sets of functionality based on your location](http://researchcenter.paloaltonetworks.com/2016/02/pirated-ios-app-stores-client-successfully-evaded-apple-ios-code-review) — iOS Dev Weekly · Issue 239 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `26th February 2016`
  **NeKI brief:** Analyzes how iOS app-store piracy bypassed code review through location-dependent behavior. Follow it for concrete security and review-evasion lessons, while treating the historical incident as threat context.
- [Being a Good Low Power Mode Citizen](https://littlebitesofcocoa.com/192-being-a-good-low-power-mode-citizen) — iOS Dev Weekly · Issue 238 — Article · Topics: Objective-C & Cocoa
  **Published:** `19th February 2016`
  **NeKI brief:** Explains Being a Good Low Power Mode Citizen with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [sample project](https://github.com/manuelmarcos/ribotTeamiOS-tvOS) — iOS Dev Weekly · Issue 238 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `19th February 2016`
  **NeKI brief:** Examines This project shows how to make the most of an iOS & tvOS App - manuelmarcos/ribotTeamiOS-tvOS. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [official blog](http://researchkit.org/blog.html) — iOS Dev Weekly · Issue 237 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** Examines Develop groundbreaking apps for research studies and patient care with these two open source frameworks. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [community on GitHub](https://github.com/ResearchKit/ResearchKit) — iOS Dev Weekly · Issue 237 — Source repository · Topics: Developer Community & Business · Developer Tools · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** The ResearchKit repository provides Apple's open-source framework for building research and health studies on iOS.
- [Supercharged Search Scopes](http://indiestack.com/2016/02/supercharged-search-scopes) — iOS Dev Weekly · Issue 237 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `12th February 2016`
  **NeKI brief:** Explains Supercharged Search Scopes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CocoaPods plugin and CLI for generating Swift Playgrounds](https://github.com/neonichu/ThisCouldBeUsButYouPlaying) — iOS Dev Weekly · Issue 237 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `12th February 2016`
  **NeKI brief:** Provides the CocoaPods plugin and CLI for generating Swift Playgrounds source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Adding a Top Shelf Extension to a tvOS App](https://littlebitesofcocoa.com/188-adding-a-top-shelf-extension-to-a-tvos-app) — iOS Dev Weekly · Issue 237 — Article · Topics: Objective-C & Cocoa · Personal Essays
  **Published:** `12th February 2016`
  **NeKI brief:** Examines One of the best parts of tvOS is the Top Shelf. It's the bit just above the top row of apps on the home screen that shows previews of each app's content when it's focus. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Videos from CocoaLove 2015](https://vimeo.com/channels/cocoalove2015) — iOS Dev Weekly · Issue 237 — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `12th February 2016`
  **NeKI brief:** CocoaLove describes itself as a conference which “focuses on talks that aren’t deprecated at the next WWDC”. This means you’re not going to find much, if any code here but what you will find is a great set of inspirational and interesting presentations.
- [post on the Swift blog](https://swift.org/blog/swift-api-transformation) — iOS Dev Weekly · Issue 236 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Explains post on the Swift blog with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [1](https://github.com/apple/swift-evolution/blob/master/proposals/0005-objective-c-name-translation.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the 1 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [2](https://github.com/apple/swift-evolution/blob/master/proposals/0006-apply-api-guidelines-to-the-standard-library.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the 2 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [3](https://github.com/apple/swift-evolution/blob/master/proposals/0023-api-guidelines.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Swift Evolution proposal 0023 records the API Design Guidelines that shaped Swift naming and labeling. Use it as historical rationale when reviewing consistency in older Swift code.
- [The Joy of Shortcuts](http://www.allenpike.com/2016/parse-joy-of-shortcuts) — iOS Dev Weekly · Issue 236 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th February 2016`
  **NeKI brief:** Examines Parse teaches us about shipping. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store economics](https://marco.org/2016/02/01/parse-shutdown-neglected-apps) — iOS Dev Weekly · Issue 236 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `5th February 2016`
  **NeKI brief:** Discusses App Store economics, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [sample app](https://github.com/alltheflow/iCopyPasta) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the iCopyPasta sample repository as an implementation reference for clipboard-related app structure. Useful for study, with source age, dependencies, and license checked before reuse.
- [Many Controllers Make Light Work](http://khanlou.com/2016/02/many-controllers) — iOS Dev Weekly · Issue 236 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `5th February 2016`
  **NeKI brief:** The article discusses using many small view controllers in iOS architecture and explains why decomposing responsibilities can make controller-based code easier to manage.
- [Partial functions in Swift, Part 1: Avoidance](http://cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html) — iOS Dev Weekly · Issue 235 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `29th January 2016`
  **NeKI brief:** Explains Partial functions in Swift Part 1 Avoidance with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Typed, yet Flexible Table View Controller](http://holko.pl/2016/01/05/typed-table-view-controller) — iOS Dev Weekly · Issue 232 — Article · Topics: Objective-C & Cocoa
  **Published:** `8th January 2016`
  **NeKI brief:** Arkadiusz Holko with a look at various approaches on how to architect your table view controllers and cells. He ends up with an approach where the view controller with no fragile switch statements, which is type safe and in fact doesn’t need to be modified…
- [Secondary Views in Interface Builder’s Storyboards](http://blog.curtisherbert.com/secondary-views) — iOS Dev Weekly · Issue 231 — Article · Topics: Objective-C & Cocoa
  **Published:** `1st January 2016`
  **NeKI brief:** Discusses Secondary Views in Interface Builder’s Storyboards, connecting the concrete app-design or distribution decision to practical considerations for Apple-platform developers.
- [PMKVObserver](https://github.com/postmates/PMKVObserver) — iOS Dev Weekly · Issue 231 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `1st January 2016`
  **NeKI brief:** Provides the PMKVObserver source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [discovered a bug](https://bugs.swift.org/browse/SR-192) — iOS Dev Weekly · Issue 228 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `11th December 2015`
  **NeKI brief:** Mike Ash with an in depth investigation of how Swift implements weak pointers. For bonus points, he also discovered a bug in Swift while researching this.
- [Flickr’s experience with iOS 9](http://code.flickr.net/2015/11/18/flickrs-experience-with-ios-9) — iOS Dev Weekly · Issue 227 — Article · Topics: App Intents & System Surfaces · Navigation & Deep Linking · Objective-C & Cocoa
  **Published:** `4th December 2015`
  **NeKI brief:** Explains Flickr’s experience with iOS 9 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [A Smarter Search Engine for the App Store](http://techcrunch.com/2015/11/13/app-store-search-just-got-smarter) — iOS Dev Weekly · Issue 225 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `20th November 2015`
  **NeKI brief:** Discusses A Smarter Search Engine for the App Store, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Jazzy](https://github.com/realm/jazzy) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th November 2015`
  **NeKI brief:** Jazzy generates Apple-style API documentation from Swift and Objective-C source, including symbol graphs, declarations, and Markdown comments. The repository is useful when setting up repeatable documentation generation as part of a library or CI release pipeline.
- [added support for Objective-C](https://github.com/realm/jazzy/pull/341) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th November 2015`
  **NeKI brief:** Presents added support for Objective-C, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Where “where” may be used?](http://blog.krzyzanowskim.com/2015/11/13/where-where-may-be-used) — iOS Dev Weekly · Issue 224 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th November 2015`
  **NeKI brief:** The “where” keyword in Swift is very handy, and you’re probably using it at least a little. However, do you know all the different places it can be used? Marcin Krzyżanowski has written up a nice summary.
- [CocoaPods and Capital One](http://blog.cocoapods.org/Capital-One) — iOS Dev Weekly · Issue 222 — Article · Topics: CI/CD & Automation · Developer Community & Business · Objective-C & Cocoa
  **Published:** `30th October 2015`
  **NeKI brief:** This announcement describes Capital One sponsoring CocoaPods development and distinguishes project support from product promotion. It is useful historical context for how critical open-source infrastructure can receive sustainable funding from companies that depend on it.
- [Reachability.swift](https://github.com/ashleymills/Reachability.swift) — iOS Dev Weekly · Issue 222 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Provides the Reachability.swift source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Little Bites of Cocoa](https://littlebitesofcocoa.com/111-reachability-swift) — iOS Dev Weekly · Issue 222 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Explains Little Bites of Cocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Considerations for Choosing 3rd Party Swift Libraries](https://www.andrewcbancroft.com/2015/10/27/considerations-for-choosing-3rd-party-swift-libraries) — iOS Dev Weekly · Issue 222 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Examines While relying on 3rd party dependencies can provide you the benefit of not having to spend time implementing a portion of your app, realize that you’re essentially giving away litt. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [CocoaPods quality index](https://guides.cocoapods.org/making/quality-indexes) — iOS Dev Weekly · Issue 222 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th October 2015`
  **NeKI brief:** Examines There has been plenty written on this subject, but this week Andrew Bancroft summed up some of the pros and cons of bringing that shiny new library into your app. Mentioned in the article, but also deserving of a special Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Sr. Mobile App Developer @ CoStar Group | Apartments.com (Washington, D.C.)](https://costar.wd1.myworkdayjobs.com/en-US/CoStarCareers/job/US-DC-Washington-DC/Senior-Mobile-Developer_4976-3) — iOS Dev Weekly · Issue 222 — Article · Topics: Developer Career & Practice
  **Published:** `30th October 2015`
  **NeKI brief:** The public job page describes the Senior Mobile App Developer role at CoStar Group and its mobile engineering responsibilities.
- [Xcode Swift Snippets](https://github.com/Abizern/xcode-snippets) — iOS Dev Weekly · Issue 220 — Source repository · Topics: Core Data · Developer Tools · Xcode
  **Published:** `16th October 2015`
  **NeKI brief:** Provides the Xcode Swift Snippets source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UI for iOS: Filling Gaps in the UIKit Framework](http://www.telerik.com/ios-ui) — iOS Dev Weekly · Issue 219 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `9th October 2015`
  **NeKI brief:** Explains UI for iOS Filling Gaps in the UIKit Framework with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [XcodeGhost](http://researchcenter.paloaltonetworks.com/2015/09/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store) — iOS Dev Weekly · Issue 217 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** Explains XcodeGhost with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS Software Engineer, Compass NYC](https://www.compass.com/jobs?gh_jid=36335) — iOS Dev Weekly · Issue 215 — Article · Topics: Objective-C & Cocoa
  **Published:** `11th September 2015`
  **NeKI brief:** Explains iOS Software Engineer, Compass NYC, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Interested in a tool that converts Objective-C to Swift?](https://www.myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 214 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `4th September 2015`
  **NeKI brief:** Instantly and automatically convert your iOS source code to be a native Android app. No SDK, no re-coding, no new frameworks & languages, fully editable converted code. Sign-up and get three months free.
- [Compression Resistance & Content Hugging](http://littlebitesofcocoa.tumblr.com/post/127721416059/69-compression-resistance-content-hugging) — iOS Dev Weekly · Issue 213 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Demonstrates how compression resistance and content hugging priorities affect Auto Layout. Follow it for concrete intrinsic-size and constraint-debugging techniques in UIKit interfaces.
- [Acorn 5’s Live Help Search](http://shapeof.com/archives/2015/8/acorn_5_search_index.html) — iOS Dev Weekly · Issue 213 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Presents Acorn 5’s Live Help Search, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Acorn 5](http://flyingmeat.com/acorn) — iOS Dev Weekly · Issue 213 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Examines Acorn is an awesome image editor for the Mac. Use Acorn to edit photos, add filters, retouch pictures, paint, crop, add text, create new images, and much more!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Autolayout breakpoints](http://nshint.io/blog/2015/08/17/autolayout-breakpoints) — iOS Dev Weekly · Issue 212 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `21st August 2015`
  **NeKI brief:** Explains Autolayout breakpoints, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [using identifiers](http://useyourloaf.com/blog/using-identifiers-to-debug-autolayout.html) — iOS Dev Weekly · Issue 212 — Article · Topics: Cross-Platform & Web · Developer Tools · Objective-C & Cocoa
  **Published:** `21st August 2015`
  **NeKI brief:** The article shows how identifiers can be used to debug Auto Layout constraints and locate the relevant views or constraints in an iOS interface.
- [Open Sourcing the Windows Bridge for iOS](http://blogs.windows.com/buildingapps/2015/08/06/open-sourcing-the-windows-bridge-for-ios) — iOS Dev Weekly · Issue 210 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `7th August 2015`
  **NeKI brief:** This announcement describes Microsoft's early open-source Windows Bridge for iOS and its Objective-C portability goals. It provides historical context for cross-platform compilation and the practical trade-offs of targeting iOS code from a Windows development environment.
- [Swift Error Handling and Objective-C Interop in Depth](http://blog.benjamin-encz.de/swift-error-handling-and-objective-c-interop-in-depth) — iOS Dev Weekly · Issue 209 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `31st July 2015`
  **NeKI brief:** Explains Swift Error Handling and Objective-C Interop in Depth with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [UI Testing with Xcode 7](https://medium.com/@larcus94/ui-testing-with-xcode-7-221d16bad276) — iOS Dev Weekly · Issue 204 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `26th June 2015`
  **NeKI brief:** Explains UI Testing with Xcode 7 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ImagePickerSheetController](https://github.com/larcus94/ImagePickerSheetController) — iOS Dev Weekly · Issue 204 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `26th June 2015`
  **NeKI brief:** Examines Replicate of the custom photo action sheet in iMessage - lerboe/ImagePickerSheetController. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple’s Bitcode Telegraphs Future CPU Plans](https://medium.com/@InertialLemon/apple-s-bitcode-telegraphs-future-cpu-plans-a7b90d326228) — iOS Dev Weekly · Issue 203 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `19th June 2015`
  **NeKI brief:** Explains Apple’s Bitcode Telegraphs Future CPU Plans with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [the archive](http://www.objc.io/issues) — iOS Dev Weekly · Issue 203 — Article · Topics: Objective-C & Cocoa
  **Published:** `19th June 2015`
  **NeKI brief:** Examines Issues · objc.io. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift 2 error handling in practice](http://www.sunsetlakesoftware.com/2015/06/12/swift-2-error-handling-practice) — iOS Dev Weekly · Issue 203 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th June 2015`
  **NeKI brief:** Examines Swift 2 error handling in practice - Sunset Lake Software. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [take on the situation](https://gist.github.com/nicklockwood/21495c2015fd2dda56cf) — iOS Dev Weekly · Issue 203 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `19th June 2015`
  **NeKI brief:** Examines Thoughts on Swift 2 Errors. GitHub Gist: instantly share code, notes, and snippets. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [CocoaPods and the Quality Index](http://blog.cocoapods.org/CocoaPods.org-Two-point-Five) — iOS Dev Weekly · Issue 202 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `12th June 2015`
  **NeKI brief:** This CocoaPods post describes the CocoaPods.org quality index and its role in evaluating packages. Follow it for historical package-discovery and metadata context, while treating the scoring model as time-bound.
- [some thoughts on this which are worth reading](http://www.marco.org/2015/06/07/freemium-is-hard) — iOS Dev Weekly · Issue 202 — Article · Topics: Objective-C & Cocoa
  **Published:** `12th June 2015`
  **NeKI brief:** Examines Freemium is hard – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Partial List of Questions About the Native Apple Watch SDK](http://www.marco.org/2015/05/28/watch-sdk-questions) — iOS Dev Weekly · Issue 201 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Examines A Partial List of Questions About the Native Apple Watch SDK – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [confirmed this week](http://9to5mac.com/2015/05/27/live-blog-apple-senior-vp-of-operations-jeff-williams-interview-at-code-conference) — iOS Dev Weekly · Issue 201 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Live coverage of Jeff Williams at the Code Conference, linked in anticipation of the first native Apple Watch SDK preview. It records the launch-period conversation rather than SDK documentation.
- [Add Google to your iOS Apps with CocoaPods](http://googledevelopers.blogspot.com/2015/05/add-google-to-your-ios-apps-with.html) — iOS Dev Weekly · Issue 201 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Google IO last week saw an interesting iOS announcement from Google. CocoaPods will be the preferred method for installation for all Google iOS libraries. It made the IO keynote and Google also put together a cute introduction video. Congratulations to the…
- [cute introduction video](https://youtube.com/watch?v=iEAjvNRdZa0) — iOS Dev Weekly · Issue 201 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** The YouTube page provides a publicly viewable introduction video and its associated metadata without authentication.
- [BugShot](http://www.marco.org/bugshot) — iOS Dev Weekly · Issue 200 — Article · Topics: Objective-C & Cocoa
  **Published:** `29th May 2015`
  **NeKI brief:** Examines Presenting PinpointKit – Lickability. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [new home](http://www.marco.org/2015/05/28/pinpoint) — iOS Dev Weekly · Issue 200 — Article · Topics: Objective-C & Cocoa
  **Published:** `29th May 2015`
  **NeKI brief:** Examines Bugshot becomes Pinpoint, gets big upgrade – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [UIViewController Initialization](http://littlebitesofcocoa.com/post/119286766047/1-uiviewcontroller-initialization-in-swift-so) — iOS Dev Weekly · Issue 199 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `22nd May 2015`
  **NeKI brief:** Explains UIViewController initialization in Swift, including lifecycle ordering and setup boundaries. Follow it for concrete UIKit construction details, while checking current containment and state-restoration behavior.
- [Chainable Methods](http://littlebitesofcocoa.com/post/119369619049/2-chainable-methods-making-functions-chainable) — iOS Dev Weekly · Issue 199 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd May 2015`
  **NeKI brief:** Presents Chainable Methods, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Timepiece Library](http://littlebitesofcocoa.com/post/119451421145/3-timepiece-timepiece-is-a-library-from-naoto) — iOS Dev Weekly · Issue 199 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd May 2015`
  **NeKI brief:** Presents Timepiece Library, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Singletons](http://littlebitesofcocoa.com/post/119531773146/4-singletons-singletons-are-a-design-pattern) — iOS Dev Weekly · Issue 199 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd May 2015`
  **NeKI brief:** Examines Singletons are a design pattern describing globally accessible instances of objects. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [My icon design workflow](http://bjango.com/articles/icondesignworkflow) — iOS Dev Weekly · Issue 199 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd May 2015`
  **NeKI brief:** Marc Edwards with a lesson on how he sets about creating icons. The article covers Illustrator and Photoshop specifically but these are great tips no matter what tool you use to actually do the creation.
- [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) — iOS Dev Weekly · Issue 198 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th May 2015`
  **NeKI brief:** Provides the CleanroomLogger source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Redesigning Overcast’s Apple Watch app](http://www.marco.org/2015/05/08/overcast-apple-watch-redesign) — iOS Dev Weekly · Issue 198 — Article · Topics: Objective-C & Cocoa
  **Published:** `15th May 2015`
  **NeKI brief:** Examines Redesigning Overcast’s Apple Watch app – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [designing Twitterrific for the watch](http://blog.iconfactory.com/2015/04/twitterrific-for-apple-watch) — iOS Dev Weekly · Issue 198 — Article · Topics: Concurrency · Objective-C & Cocoa
  **Published:** `15th May 2015`
  **NeKI brief:** Examines What would a Twitter app look like on the watch? Looks like you’ll be able to find out on the 24th. Ged Maheux explains some of the design decisions that went into the process. Instead of a timeline (the phone is much be Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Bringing Clang to Windows](http://blogs.msdn.com/b/vcblog/archive/2015/05/01/bringing-clang-to-windows.aspx) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games
  **Published:** `8th May 2015`
  **NeKI brief:** Examines As you may know, Visual Studio now supports building Android and iOS applications using Clang. We realize the need of our users to write cross-platform. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Buildasaur](https://github.com/czechboy0/Buildasaur) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Architecture · Developer Tools · Xcode
  **Published:** `8th May 2015`
  **NeKI brief:** Provides the Buildasaur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FLXView](https://github.com/robb/FLXView) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `8th May 2015`
  **NeKI brief:** Like SwiftBox, this is based on the Facebook implementation of flexbox. This time, Robert Böhnke has had a go at bringing this layout technology to Objective-C. Check out the included playground for an example of how it works.
- [SwiftBox](https://github.com/joshaber/SwiftBox) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `8th May 2015`
  **NeKI brief:** Like SwiftBox, this is based on the Facebook implementation of flexbox. This time, Robert Böhnke has had a go at bringing this layout technology to Objective-C. Check out the included playground for an example of how it works.
- [flexbox](https://github.com/facebook/css-layout) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Objective-C & Cocoa
  **Published:** `8th May 2015`
  **NeKI brief:** Like SwiftBox, this is based on the Facebook implementation of flexbox. This time, Robert Böhnke has had a go at bringing this layout technology to Objective-C. Check out the included playground for an example of how it works.
- [compiled and simulated](http://techcrunch.com/2015/04/29/microsoft-makes-it-easier-for-developers-to-bring-their-android-and-ios-apps-to-windows-10) — iOS Dev Weekly · Issue 196 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st May 2015`
  **NeKI brief:** Explains compiled and simulated, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [1 hour of research saves 10 hours of development time](http://bokardo.com/archives/1-hour-of-research-saves-10-hours-of-development-time) — iOS Dev Weekly · Issue 196 — Article · Topics: Objective-C & Cocoa
  **Published:** `1st May 2015`
  **NeKI brief:** Examines An Interface and Product Design blog by Joshua Porter. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A First Look at ReactiveCocoa 3.0](http://blog.scottlogic.com/2015/04/24/first-look-reactive-cocoa-3.html) — iOS Dev Weekly · Issue 195 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `24th April 2015`
  **NeKI brief:** Explains A First Look at ReactiveCocoa 3.0 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [on GitHub](https://github.com/researchkit/researchkit) — iOS Dev Weekly · Issue 194 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th April 2015`
  **NeKI brief:** The ResearchKit repository provides Apple's open-source framework for building research and health studies on iOS.
- [accepting pull requests](https://github.com/ResearchKit/ResearchKit/pulls?q=is%3Apr+is%3Aclosed) — iOS Dev Weekly · Issue 194 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th April 2015`
  **NeKI brief:** Examines ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects. - Pull requests · ResearchKit/ResearchKit. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [real work being done](https://github.com/ResearchKit/ResearchKit/pull/33) — iOS Dev Weekly · Issue 194 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th April 2015`
  **NeKI brief:** Examines This is huge news. ResearchKit was promised as open source and I was amongst those who were a little sarcastic on the chances of it happening. However, it’s happened, and in spectacular style too. Hosted on GitHub and al Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [CocoaPods](https://github.com/ResearchKit/ResearchKit/pull/5) — iOS Dev Weekly · Issue 194 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th April 2015`
  **NeKI brief:** The GitHub pull request documents an early ResearchKit change involving CocoaPods integration and provides publicly readable discussion and code context.
- [Carthage](https://github.com/ResearchKit/ResearchKit/pull/7) — iOS Dev Weekly · Issue 194 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `17th April 2015`
  **NeKI brief:** Examines It even looks like PRs for CocoaPods and Carthage support will be merged. How times have changed… Bravo Apple. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Natalie - Storyboard Code Generator](http://blog.krzyzanowskim.com/2015/04/15/natalie-storyboard-code-generator) — iOS Dev Weekly · Issue 194 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `17th April 2015`
  **NeKI brief:** Explains Natalie Storyboard Code Generator with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why I don’t use PDFs for iOS assets](http://bjango.com/articles/idontusepdfs) — iOS Dev Weekly · Issue 192 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `3rd April 2015`
  **NeKI brief:** Explains Why I don’t use PDFs for iOS assets with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Replacing Photoshop With NSString](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring) — iOS Dev Weekly · Issue 190 — Article · Topics: Objective-C & Cocoa
  **Published:** `20th March 2015`
  **NeKI brief:** Presents Replacing Photoshop With NSString, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Xcode Compromised](http://furbo.org/2015/03/10/xcode-compromised) — iOS Dev Weekly · Issue 189 — Article · Topics: Objective-C & Cocoa · Security & Privacy · Xcode
  **Published:** `13th March 2015`
  **NeKI brief:** Explains Xcode Compromised with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ReactKit](https://github.com/ReactKit/ReactKit) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa/pull/1382) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactiveCocoa source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [March 9th](http://david-smith.org/blog/2015/02/26/ailw-spring-forward-event-announced) — iOS Dev Weekly · Issue 187 — Article · Topics: Objective-C & Cocoa
  **Published:** `27th February 2015`
  **NeKI brief:** The post announces the A Life Well Wasted Spring Forward event and provides publicly readable event context from the author.
- [Updating to the iOS 8 Search Controller](http://useyourloaf.com/blog/2015/02/16/updating-to-the-ios-8-search-controller.html) — iOS Dev Weekly · Issue 186 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `20th February 2015`
  **NeKI brief:** Explains how to update an iOS 8 search controller. Follow it for concrete UIKit search and presentation patterns, while verifying lifecycle details against current APIs.
- [Converting Complex Objective-C Macros to Swift Functions](http://www.andrewcbancroft.com/2015/01/29/converting-complex-objective-c-macros-swift-functions) — iOS Dev Weekly · Issue 183 — Article · Topics: Macros & Metaprogramming · Objective-C & Cocoa · Swift
  **Published:** `30th January 2015`
  **NeKI brief:** Explains Converting Complex Objective-C Macros to Swift Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Luis Ascorbe’s conference list](https://github.com/Lascorbe/CocoaConferences) — iOS Dev Weekly · Issue 182 — Source repository · Topics: Developer Community & Business · Developer Tools · Objective-C & Cocoa
  **Published:** `23rd January 2015`
  **NeKI brief:** The page covers “Cocoa Conferences in 2014” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Real World Swift](http://making.duolingo.com/real-world-swift) — iOS Dev Weekly · Issue 181 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `16th January 2015`
  **NeKI brief:** Examines Chris from Duolingo shares his experience of using Swift for a real shipped app. He lists many good and bad points but concludes that they did gain from choosing Swift over Objective-C for a new app. I know many are feel Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Overcast’s 2014 sales numbers](http://www.marco.org/2015/01/15/overcast-sales-numbers) — iOS Dev Weekly · Issue 181 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `16th January 2015`
  **NeKI brief:** Since the new year there have been several posts with developers publishing their revenue from 2014. Marco Arment (linked above), UsTwo with a Monument Valley revenue infographic and Bogdan Popescu with the revenue for Dash. All of which show that it’s not…
- [revenue for Dash](http://blog.kapeli.com/my-year-in-review-2014) — iOS Dev Weekly · Issue 181 — Article · Topics: Objective-C & Cocoa
  **Published:** `16th January 2015`
  **NeKI brief:** Examines Dash is an API Documentation Browser and Code Snippet Manager for macOS. Dash provides instant offline access to 200+ API documentation sets, code snippets, and cheat sheets. Featu. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [BigBrother](https://github.com/marcelofabri/BigBrother) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Networking · Objective-C & Cocoa
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the BigBrother source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Siren](https://github.com/ArtSabintsev/Siren) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the Siren source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Harpy](https://github.com/ArtSabintsev/Harpy) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the Harpy source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Death of Cocoa](http://nshipster.com/the-death-of-cocoa) — iOS Dev Weekly · Issue 179 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Swift
  **Published:** `2nd January 2015`
  **NeKI brief:** Explains The Death of Cocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CocoaPods, Frameworks and Swift](http://blog.cocoapods.org/Pod-Authors-Guide-to-CocoaPods-Frameworks) — iOS Dev Weekly · Issue 179 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2nd January 2015`
  **NeKI brief:** This guide explains how pod authors package frameworks and support Swift through CocoaPods, including the prerelease workflow available at the time. It is useful for understanding the build and distribution choices behind framework-based dependency integration.
- [Why Triangles?](http://www.joshbarczak.com/blog?p=558) — iOS Dev Weekly · Issue 179 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd January 2015`
  **NeKI brief:** Joshua Barczak with a post that I thoroughly enjoyed on why 3D graphics (generally) uses triangles over any other primitives. Not directly related to iOS development but I found it interesting anyway!
- [How Broken is Discovery on the App Store? This Broken.](http://gedblog.com/2014/12/15/how-broken-is-discovery-on-the-app-store-this-broken) — iOS Dev Weekly · Issue 177 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Product Design
  **Published:** `19th December 2014`
  **NeKI brief:** Examines How Broken is Discovery on the App Store? This Broken. | gedblog. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [not only about search, but app discovery](http://aplus.rs/2014/few-proposal-for-better-app-store) — iOS Dev Weekly · Issue 177 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Product Design
  **Published:** `19th December 2014`
  **NeKI brief:** Examines Few proposals for better App Store · aplus.rs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Objective-C’s Designated Secret](http://timekl.com/blog/2014/12/09/objective-cs-designated-secret) — iOS Dev Weekly · Issue 176 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Objective-C’s Designated Secret with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The QA Mindset](http://randsinrepose.com/archives/the-qa-mindset) — iOS Dev Weekly · Issue 175 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th December 2014`
  **NeKI brief:** Presents The QA Mindset, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [CocoaPods in 2014](http://blog.cocoapods.org/Stats-2014) — iOS Dev Weekly · Issue 174 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th November 2014`
  **NeKI brief:** Explains CocoaPods in 2014 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Developing a Bidding Kiosk for iOS in Swift](http://artsy.github.io/blog/2014/11/13/eidolon-retrospective) — iOS Dev Weekly · Issue 172 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Explains Developing a Bidding Kiosk for iOS in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [app is open source](https://github.com/artsy/eidolon) — iOS Dev Weekly · Issue 172 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Provides the app is open source source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [open source the .NET framework](http://tirania.org/blog/archive/2014/Nov-12.html) — iOS Dev Weekly · Issue 172 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `14th November 2014`
  **NeKI brief:** Examines Miguel de Icaza. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The Trials and Tribulations of Writing a 3rd Party iOS Keyboard](http://nuzzel.com/sharedstory/11082014/beta-blog.archagon/the_trials_and_tribulations_of_writing_a_3rd_party_ios_keyboard) — iOS Dev Weekly · Issue 172 — Article · Topics: Hardware & Devices · Objective-C & Cocoa
  **Published:** `14th November 2014`
  **NeKI brief:** Explains The Trials and Tribulations of Writing a 3rd Party iOS Keyboard with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `24th October 2014`
  **NeKI brief:** The page covers “KZPlayground” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Check out the video too](http://vimeo.com/109757619) — iOS Dev Weekly · Issue 169 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `24th October 2014`
  **NeKI brief:** I really don’t need to say anything about this except this is playgrounds, for Objective-C, by Krzysztof Zabłocki. Check out the video too, super cool.
- [SuperRecord](https://github.com/michaelarmstrong/SuperRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the SuperRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the MagicalRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [My app design workflow](http://bjango.com/articles/appdesignworkflow) — iOS Dev Weekly · Issue 165 — Article · Topics: Objective-C & Cocoa
  **Published:** `26th September 2014`
  **NeKI brief:** This walkthrough describes a detailed app-design workflow covering scale factors, styling effects, and pixel-level adjustments. It is useful for connecting visual design decisions to the practical asset and iteration constraints of Apple-platform interfaces.
- [Overcast is now accidentally an iPad app, too](http://www.marco.org/2014/09/17/overcast-accidentally-universal) — iOS Dev Weekly · Issue 164 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `19th September 2014`
  **NeKI brief:** Explains Overcast is now accidentally an iPad app too with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [tip for replacing launch images with a storyboard](http://oleb.net/blog/2014/08/replacing-launch-images-with-storyboards) — iOS Dev Weekly · Issue 164 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `19th September 2014`
  **NeKI brief:** Launch screen storyboards replace static image variants with adaptive layout, reducing device-specific assets. The migration must avoid app-like initialization work because the system displays the launch screen before the process is ready.
- [mogenerator 1.28](http://rentzsch.tumblr.com/post/97193911940/mogenerator-1-28) — iOS Dev Weekly · Issue 163 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `12th September 2014`
  **NeKI brief:** Examines What's New: [NEW] --v2 argument. I wanted to enable ARC by default, but decided to take it a step further (while not breaking existing scripts). The new --v2 argument is basic. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Is your product a Hafta or Wanna?](http://bokardo.com/archives/behavior-change-hafta-wanna) — iOS Dev Weekly · Issue 161 — Article · Topics: Objective-C & Cocoa
  **Published:** `29th August 2014`
  **NeKI brief:** Examines Joshua Porter talking about Nir Eyal’s recent article Why Behavior Change Apps Don’t Work. I’ve never seen it put into words quite as effectively as Joshua does but this is a very real issue that you almost certainly wil Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Cocoa without the limitations of C compatibility](https://devforums.apple.com/message/1025388) — iOS Dev Weekly · Issue 160 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `22nd August 2014`
  **NeKI brief:** Explains Cocoa without the limitations of C compatibility with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Moya](https://github.com/AshFurrow/Moya) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Functional Programming · Objective-C & Cocoa
  **Published:** `22nd August 2014`
  **NeKI brief:** Examines Network abstraction layer written in Swift. Contribute to Moya/Moya development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AlamoFire](https://github.com/Alamofire/Alamofire) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Functional Programming · Objective-C & Cocoa
  **Published:** `22nd August 2014`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
- [swiftz](https://github.com/maxpow4h/swiftz) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Functional Programming · Swift
  **Published:** `22nd August 2014`
  **NeKI brief:** Examines What do you get if you cross AlamoFire, ReactiveCocoa and functional programming concepts (using swiftz)? Ash Furrow is experimenting. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Shenzhen 0.8](https://github.com/nomad/shenzhen) — iOS Dev Weekly · Issue 158 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `8th August 2014`
  **NeKI brief:** Mattt Thompson released a new version of Shenzhen this week, the utility for creating and uploading IPA archives to various services. The big news is that builds can now be uploaded directly to iTunes Connect using this tool. If you’re new to iOS development…
- [App Store Longevity and Freshness](http://david-smith.org/blog/2014/08/04/app-store-longevity-and-freshness) — iOS Dev Weekly · Issue 158 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `8th August 2014`
  **NeKI brief:** Examines App Store Longevity and Freshness - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Purging the Back Catalog](http://david-smith.org/blog/2013/03/21/purging-the-back-catalog) — iOS Dev Weekly · Issue 158 — Article · Topics: Objective-C & Cocoa
  **Published:** `8th August 2014`
  **NeKI brief:** Examines Purging the Back Catalog - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Objective-Clean](http://objclean.com/index.php) — iOS Dev Weekly · Issue 157 — Article · Topics: Objective-C & Cocoa · Personal Essays
  **Published:** `1st August 2014`
  **NeKI brief:** Objective-Clean provides tooling for cleaning or managing Objective-C project artifacts. Follow it for concrete maintenance behavior, while checking exactly which files it changes before use.
- [Want to experience the San Francisco startup scene?](https://gametime.co/jobs/a863b6f9-1b49-4288-babd-75e84e4690df) — iOS Dev Weekly · Issue 157 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `1st August 2014`
  **NeKI brief:** Examines <p>Our team is on a mission to connect people through incredible shared experiences. We build technology that gets people out into the real world to enjoy their favorite even. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [FLEX](https://github.com/Flipboard/FLEX) — iOS Dev Weekly · Issue 156 — Source repository · Topics: Developer Community & Business · Developer Tools · Objective-C & Cocoa
  **Published:** `25th July 2014`
  **NeKI brief:** I first saw this back at NSConference in 2013 when Evan Doll gave his talk on their internal tools at Flipboard and this week it has been released for everyone to use as an open source library. Get quick access to all sorts of runtime view hierarchy…
- [Prefixes Considered Passé](http://inessential.com/2014/07/24/prefixes_considered_passe) — iOS Dev Weekly · Issue 156 — Article · Topics: Objective-C & Cocoa
  **Published:** `25th July 2014`
  **NeKI brief:** This post examines the arguments for and against naming prefixes in Objective-C code as the ecosystem's conventions changed. It is useful historical guidance for weighing namespace clarity, collision avoidance, and the maintenance cost of legacy naming practices.
- [Coursera iOS Software Engineer - Mountain View, CA](https://www.coursera.org/about/careers/96aecab7-9cb9-424a-b95c-002842a792e8) — iOS Dev Weekly · Issue 156 — Tutorial · Topics: Architecture · Developer Career & Practice · Developer Community & Business
  **Published:** `25th July 2014`
  **NeKI brief:** Explains Coursera iOS Software Engineer Mountain View CA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [fine piece of sarcasm by Russell Ivanovic](http://rustyshelf.org/2014/07/16/de-enterprising-apples-ibm-announcement) — iOS Dev Weekly · Issue 155 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th July 2014`
  **NeKI brief:** Uses satire to comment on Apple’s IBM announcement. Follow it for historical industry context only; it is not a technical implementation resource.
- [Zen and the Art of the Objective-C Craftsmanship](https://github.com/objc-zen/objc-zen-book) — iOS Dev Weekly · Issue 154 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `11th July 2014`
  **NeKI brief:** The page covers “Zen and the Art of the Objective-C Craftsmanship” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [There is no later for your customers](http://bokardo.com/archives/later) — iOS Dev Weekly · Issue 153 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `4th July 2014`
  **NeKI brief:** Examines The web development mantra of “Ship early and ship often” is something that iOS & Mac developers have not been particularly quick to adopt but with automatic app updates now being taken for granted, review times which ar Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The Core Data stack in Swift](http://www.cimgf.com/2014/06/08/the-core-data-stack-in-swift) — iOS Dev Weekly · Issue 152 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `27th June 2014`
  **NeKI brief:** Explains The Core Data stack in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple Software Engineering Author, Cupertino](https://jobs.apple.com/search?job=31081438&openJobId=31081438) — iOS Dev Weekly · Issue 152 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `27th June 2014`
  **NeKI brief:** Like the Swift Programming Language book? Want to get your hands on the latest and greatest technologies early, and change the way developers learn about them? Make your mark by joining the documentation team at Apple. We’re looking for an experienced…
- [Cartography](https://github.com/robb/Cartography) — iOS Dev Weekly · Issue 151 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `20th June 2014`
  **NeKI brief:** Examines A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: - robb/Cartography. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Jay Freeman’s talk from AltConf](https://www.youtube.com/watch?v=Ii-02vhsdVk) — iOS Dev Weekly · Issue 150 — Video · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th June 2014`
  **NeKI brief:** Examines Auf YouTube findest du die angesagtesten Videos und Tracks. Außerdem kannst du eigene Inhalte hochladen und mit Freunden oder gleich der ganzen Welt teilen. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift Language Highlights: An Objective-C Developer’s Perspective](http://www.raywenderlich.com/73997/swift-language-highlights) — iOS Dev Weekly · Issue 149 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `6th June 2014`
  **NeKI brief:** Explains Swift Language Highlights An Objective-C Developer’s Perspective with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [File A Bug](http://bitsplitting.org/2014/05/27/file-a-bug) — iOS Dev Weekly · Issue 148 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th May 2014`
  **NeKI brief:** File A Bug explains how to prepare a useful issue report for software problems. Follow it for concrete reproduction, environment, and diagnostic details that make Apple-platform bug reports easier to act on.
- [Marco Arment’s recent post on the same subject](http://www.marco.org/2014/05/27/file-a-bug) — iOS Dev Weekly · Issue 148 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th May 2014`
  **NeKI brief:** Examines File A Bug – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Flight search engine in your app](http://www.travelpayouts.com/promo/aviasales_ios_sdk) — iOS Dev Weekly · Issue 147 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Personal Essays
  **Published:** `23rd May 2014`
  **NeKI brief:** Explains Flight search engine in your app with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CocoaPods Trunk](http://blog.cocoapods.org/CocoaPods-Trunk) — iOS Dev Weekly · Issue 147 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Examines The blog for CocoaPods.org the Cocoa Dependency Manager. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [getting started guide](http://guides.cocoapods.org/making/getting-setup-with-trunk) — iOS Dev Weekly · Issue 147 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Examines CocoaPods Guides - Getting setup with Trunk. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [claim your existing pods](http://blog.cocoapods.org/Claim-Your-Pods) — iOS Dev Weekly · Issue 147 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Claim Your Pods documents how maintainers can claim existing CocoaPods entries. Follow it for concrete package-ownership and namespace-management workflow details in the CocoaPods ecosystem.
- [GitHub repository](https://github.com/albertodebortoli/ADBActors) — iOS Dev Weekly · Issue 147 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Provides the GitHub repository source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Benchmarking](http://nshipster.com/benchmarking) — iOS Dev Weekly · Issue 147 — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** A useful benchmark controls compiler mode, inputs, warm-up and repetition before comparing implementations. Use it to answer one performance question at a time, corroborating measurements with profiling when a change affects architecture.
- [GCDWebServer](https://github.com/swisspol/GCDWebServer) — iOS Dev Weekly · Issue 142 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th April 2014`
  **NeKI brief:** Provides the GCDWebServer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Joris Kluivers has us covered](http://joris.kluivers.nl/blog/2014/04/08/the-builder-pattern-in-objective-c-foundation) — iOS Dev Weekly · Issue 141 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `11th April 2014`
  **NeKI brief:** Examines In a recent blog post Klaas Pieter Annema wrote about using the builder pattern in Objective-C. Inspired by his post I created two categories that …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Uli Kusterer also has a few things to say on the subject as well](http://orangejuiceliberationfront.com/cocoa-and-the-builder-pattern) — iOS Dev Weekly · Issue 141 — Article · Topics: Objective-C & Cocoa
  **Published:** `11th April 2014`
  **NeKI brief:** Discusses the Cocoa Builder pattern and object-construction trade-offs. Follow it for concrete Objective-C design reasoning, while comparing the pattern with current Swift initialization practices.
- [Part two of the talk is also online here](http://vimeo.com/90642682) — iOS Dev Weekly · Issue 140 — Video · Topics: Concurrency · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `4th April 2014`
  **NeKI brief:** Chris Eidhof with a collection of tips and tricks on asynchronous programming from Cocoaheads Kiev recently. Part two of the talk is also online here.
- [Effective Objective-C 2.0](http://useyourloaf.com/blog/2014/03/19/effective-objective-c-2-dot-0.html) — iOS Dev Weekly · Issue 139 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `28th March 2014`
  **NeKI brief:** The article explains effective Objective-C 2.0 techniques and practical language and API usage guidance for iOS developers.
- [Landing Pages Inside Apps](http://in.tapstream.com/iosdev/14) — iOS Dev Weekly · Issue 138 — Article · Topics: Objective-C & Cocoa
  **Published:** `21st March 2014`
  **NeKI brief:** You can significantly increase user retention by personalizing users’ first-run experience based on where they came from. Imagine a user finding your app through “Hotels in Paris” ad or search, and seeing a list of Parisian hotels on the first run of your…
- [2009 post](http://boredzo.org/blog/archives/2009-11-07/warnings) — iOS Dev Weekly · Issue 138 — Article · Topics: Objective-C & Cocoa
  **Published:** `21st March 2014`
  **NeKI brief:** This post explains which additional compiler warnings the author enables and why they catch useful mistakes without overwhelming a project. It offers a concrete starting point for making warning policy part of an Objective-C or Swift build workflow.
- [Carpet Mesh](http://marcus-experiments.tumblr.com/post/79283666129/so-here-is-a-more-in-depth-video-about-this) — iOS Dev Weekly · Issue 138 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `21st March 2014`
  **NeKI brief:** Explores a carpet-mesh rendering experiment with interactive graphics. Follow it for concrete geometry and rendering ideas, while verifying implementation details against current graphics frameworks.
- [check out the full archive](http://marcus-experiments.tumblr.com/archive) — iOS Dev Weekly · Issue 138 — Article · Topics: Objective-C & Cocoa
  **Published:** `21st March 2014`
  **NeKI brief:** The public archive lists Marcus's interface and software experiments and provides readable links to the individual experiments.
- [objc_designated_initializer](https://gist.github.com/steipete/9482253) — iOS Dev Weekly · Issue 137 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `14th March 2014`
  **NeKI brief:** The concept of designated initialisers in Objective-C has been around forever but there has never been a way to indicate which initialiser was your designated one apart from in documentation (and who reads docs, right?). As Peter Steinberger notes, this…
- [chisel](https://github.com/facebook/chisel) — iOS Dev Weekly · Issue 136 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `7th March 2014`
  **NeKI brief:** Provides the chisel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CocoaPods, or How I Learned to Stop Worrying and Love Objective-C Dependency Management](http://irace.me/cocoapods) — iOS Dev Weekly · Issue 136 — Article · Topics: Developer Career & Practice · Objective-C & Cocoa · Xcode
  **Published:** `7th March 2014`
  **NeKI brief:** Explains CocoaPods or How I Learned to Stop Worrying and Love Objective-C Dependency Management with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this.
- [KVOController](https://github.com/facebook/KVOController) — iOS Dev Weekly · Issue 135 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `28th February 2014`
  **NeKI brief:** Facebook are pushing out all sorts of great open source code recently and this KVO assistant class is no exception. The biggest benefit by far is block based observer callbacks but it also removes the requirement to explicitly remove observers and various…
- [StoryboardLint](https://github.com/jfahrenkrug/StoryboardLint) — iOS Dev Weekly · Issue 134 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `21st February 2014`
  **NeKI brief:** Provides the StoryboardLint source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Using CocoaPods to Modularize an iOS App](http://dev.hubspot.com/blog/architecting-a-large-ios-app-with-cocoapods) — iOS Dev Weekly · Issue 132 — Article · Topics: Architecture · Objective-C & Cocoa · Xcode
  **Published:** `7th February 2014`
  **NeKI brief:** HubSpot describes splitting a large iOS codebase into CocoaPods modules, making dependency boundaries and incremental ownership explicit. Useful when evaluating modularization costs and build-time trade-offs.
- [Replacing the Objective-C “Delegate Pattern” with ReactiveCocoa](http://spin.atomicobject.com/2014/02/03/objective-c-delegate-pattern) — iOS Dev Weekly · Issue 132 — Article · Topics: Objective-C & Cocoa
  **Published:** `7th February 2014`
  **NeKI brief:** Explains Replacing the Objective-C Delegate Pattern with ReactiveCocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Repairing Our Broken CocoaPods Specs Repository](http://blog.cocoapods.org/Repairing-Our-Broken-Specs-Repository) — iOS Dev Weekly · Issue 131 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `31st January 2014`
  **NeKI brief:** Examines This is more of an interesting story about git rather than anything to do with CocoaPods but I found the dilemma interesting. Ultimately, they made exactly the right decision here given the nature of the content in the c Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Bolts](https://github.com/BoltsFramework/Bolts-iOS) — iOS Dev Weekly · Issue 131 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `31st January 2014`
  **NeKI brief:** Provides the Bolts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Structuring Modern Objective-C](http://ashfurrow.com/blog/structuring-modern-objective-c) — iOS Dev Weekly · Issue 130 — Article · Topics: Objective-C & Cocoa
  **Published:** `24th January 2014`
  **NeKI brief:** Examines When learning a new skill, like a programming language, we often just mash together whatever works in order to get it running. Later, we’ll return to these habits and re-evaluate,. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [objc-run](https://github.com/iljaiwas/objc-run) — iOS Dev Weekly · Issue 128 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th January 2014`
  **NeKI brief:** Provides the objc-run source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Cocoa Conferences in 2014](https://github.com/Lascorbe/cocoaconferences) — iOS Dev Weekly · Issue 127 — Source repository · Topics: Developer Community & Business · Developer Tools · Objective-C & Cocoa
  **Published:** `3rd January 2014`
  **NeKI brief:** The page covers “Cocoa Conferences in 2014” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Objective-C RegEx Categories](https://github.com/bendytree/Objective-C-RegEx-Categories) — iOS Dev Weekly · Issue 127 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `3rd January 2014`
  **NeKI brief:** I’m not usually a fan of categories designed to reduce the verbosity of Objective-C but NSRegularExpression is one where I would consider a reduction valuable. These categories by Josh Wright look to be a step in the right direction.
- [My “Doom” 20th Anniversary Stories](http://blog.wilshipley.com/2013/12/my-doom-20th-anniversary-stories.html?m=1) — iOS Dev Weekly · Issue 125 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `20th December 2013`
  **NeKI brief:** Dan Counsell with an excellent article on optimising your app store listing for search and discoverability. This is a tricky subject which attracts lots of misinformation but Dan cuts through it all to give a clear and sensible set of tips on getting your…
- [APIClient](https://github.com/klaaspieter/APIClient) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Dependency Injection · Developer Tools · Navigation & Deep Linking
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the APIClient source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Understanding and using RACCommand](http://codeblog.shape.dk/blog/2013/12/05/reactivecocoa-essentials-understanding-and-using-raccommand) — iOS Dev Weekly · Issue 123 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th December 2013`
  **NeKI brief:** This tutorial explains RACCommand as a ReactiveCocoa abstraction for representing executable work, its inputs, and execution state. It gives legacy Objective-C and Swift reactive codebases a concrete pattern for composing UI actions with success, failure, and activity signals.
- [Why I Don’t Recommend Auto-Renewable Subscriptions](http://www.marco.org/2013/12/02/auto-renewable-subscriptions) — iOS Dev Weekly · Issue 123 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `6th December 2013`
  **NeKI brief:** Marco Arment on the (non-technical) difficulties of Apple’s renewable subscription In-App Purchases. His solution? Just do it yourself, use a single non-renewable subscription and then prompt the user again when it expires. From a purely consumer…
- [What Does The “.m” Extension Stand For?](http://pempek.net/blog/2013/11/30/objective-c-file-extension) — iOS Dev Weekly · Issue 123 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th December 2013`
  **NeKI brief:** What Does The “.m” Extension Stand For?. This link is retained as a technical reading lead for Apple-platform development.
- [SDCAlertView](https://github.com/Scott90/SDCAlertView) — iOS Dev Weekly · Issue 122 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `29th November 2013`
  **NeKI brief:** Provides the SDCAlertView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Podlife](http://davander.com/podlife.html) — iOS Dev Weekly · Issue 121 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains Podlife with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSNotificationCenter with blocks considered harmful](http://sealedabstract.com/code/nsnotificationcenter-with-blocks-considered-harmful) — iOS Dev Weekly · Issue 121 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains NSNotificationCenter with blocks considered harmful with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Mobile 2D Game Engine Popularity Index – November 2013](http://www.learn-cocos2d.com/2013/11/mobile-game-engine-popularity-index) — iOS Dev Weekly · Issue 120 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `15th November 2013`
  **NeKI brief:** The article compares the popularity of mobile 2D game engines in November 2013 and provides a concrete snapshot of the development-tool landscape.
- [Five Years in the App Store](http://david-smith.org/blog/2013/11/08/five-years-in-the-app-store) — iOS Dev Weekly · Issue 120 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th November 2013`
  **NeKI brief:** This retrospective reflects on five years of building and selling apps through the App Store. It offers an experienced independent-developer perspective on product iteration, platform dependence, and the long-term business realities behind iOS software.
- [Cocos2d Version 3 Preview](http://www.cocos2d-iphone.org/cocos2d-version-3-preview) — iOS Dev Weekly · Issue 119 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `8th November 2013`
  **NeKI brief:** The article previews Cocos2D version 3 and discusses the framework features and migration context for iOS game development.
- [Inkpad](https://github.com/sprang/Inkpad) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides the Inkpad source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Apple Advertising System Apps and Features in App Store Search Results](http://www.macstories.net/news/apple-advertising-system-apps-and-features-in-app-store-search-results) — iOS Dev Weekly · Issue 118 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `1st November 2013`
  **NeKI brief:** Seems like there has been a small update to searching on the App Store this week with Apple’s bundled apps now showing up for common search terms. It seems obvious to those of us who use iOS every day as developers that these apps exist but just last week I…
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Demonstrates compiling an Objective-C iOS game for Android with Apportable and SpriteBuilder, including platform-framework mapping. Treat it as historical cross-platform tooling context rather than a current deployment recommendation.
- [Handlebars for Objective-C](https://github.com/fotonauts/handlebars-objc) — iOS Dev Weekly · Issue 116 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th October 2013`
  **NeKI brief:** Provides the Handlebars for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Non-pointer isa](http://www.sealiesoftware.com/blog/archive/2013/09/24/objc_explain_Non-pointer_isa.html) — iOS Dev Weekly · Issue 113 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `27th September 2013`
  **NeKI brief:** Explains Non-pointer isa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [FCModel](https://github.com/marcoarment/FCModel) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the FCModel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ARC vs. MRC Performance](http://mjtsai.com/blog/2013/09/10/arc-vs-mrc-performance) — iOS Dev Weekly · Issue 111 — Article · Topics: Objective-C & Cocoa · Performance
  **Published:** `13th September 2013`
  **NeKI brief:** Explains ARC vs. MRC Performance with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [FMPSD](https://github.com/ccgus/fmpsd) — iOS Dev Weekly · Issue 110 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `6th September 2013`
  **NeKI brief:** Provides the FMPSD source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Extracting colours with alpha](http://bjango.com/articles/extractingcolours) — iOS Dev Weekly · Issue 109 — Article · Topics: Objective-C & Cocoa
  **Published:** `30th August 2013`
  **NeKI brief:** Examines I hadn’t come across the Color Sampler tool in Photoshop before reading this article by Marc Edwards but it gives a nice run down of a clever technique for extracting pure colours from a composite image. I am not sure ho Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [ReactiveCocoa 2](https://github.com/ReactiveCocoa/ReactiveCocoa/blob/master/CHANGELOG.md) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the ReactiveCocoa 2 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Callbacks as our Generations’ Go To Statement](http://tirania.org/blog/archive/2013/Aug-15.html) — iOS Dev Weekly · Issue 107 — Article · Topics: Concurrency · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th August 2013`
  **NeKI brief:** Explains Callbacks as our Generations’ Go To Statement with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Verbal Expressions](https://github.com/VerbalExpressions/JSVerbalExpressions) — iOS Dev Weekly · Issue 106 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `9th August 2013`
  **NeKI brief:** Readable regular expressions? When do we get an Objective-C port?
- [Searching the Curatorium](http://www.allenpike.com/2013/searching-the-curatorium) — iOS Dev Weekly · Issue 105 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Examines We search Twitter on the App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [New thing I do in code](http://cocoa-dom.tumblr.com/post/56517731293/new-thing-i-do-in-code) — iOS Dev Weekly · Issue 105 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Explains New thing I do in code with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [PSD.rb](http://layervault.tumblr.com/post/56891876898/psd-rb) — iOS Dev Weekly · Issue 105 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Explains PSD.rb with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ParcelKit](https://github.com/overcommitted/ParcelKit) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Core Data · Objective-C & Cocoa · Testing
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the ParcelKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Using Soulver for design](http://bjango.com/articles/soulver) — iOS Dev Weekly · Issue 103 — Article · Topics: Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Soulver is one of my favourite tools of any kind on my Mac and I must have used it almost every day since buying it a few years ago. I use it for geometry and dimension calculations all the time but I never thought to do as Marc Edwards has done and define a…
- [Objective-C Generics](https://github.com/tomersh/Objective-C-Generics) — iOS Dev Weekly · Issue 103 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Provides the Objective-C Generics source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Why mobile web apps are slow](http://sealedabstract.com/rants/why-mobile-web-apps-are-slow) — iOS Dev Weekly · Issue 102 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Performance
  **Published:** `12th July 2013`
  **NeKI brief:** The article analyzes performance problems in mobile web applications and explains the technical reasons users experience them as slow.
- [Ruby-like nil messaging in Objective-C](http://ddeville.me/2013/06/ruby-like-nil-messaging-in-objective-c) — iOS Dev Weekly · Issue 101 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th July 2013`
  **NeKI brief:** Explains Ruby-like nil messaging in Objective-C with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Are you breaching Open Source Licenses accidentally?](http://blog.human-friendly.com/are-you-breaching-open-source-licenses-accidentally) — iOS Dev Weekly · Issue 100 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th June 2013`
  **NeKI brief:** This article explains why open-source licenses can require attribution even when a dependency is consumed through a package manager. It points to practical compliance automation, including collecting license files, as part of shipping an iOS app responsibly.
- [Subliminal](https://github.com/inkling/Subliminal) — iOS Dev Weekly · Issue 98 — Source repository · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `14th June 2013`
  **NeKI brief:** Provides the Subliminal source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Apple’s new Objective-C to Javascript Bridge](http://www.steamclock.com/blog/2013/05/apple-objective-c-javascript-bridge) — iOS Dev Weekly · Issue 94 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `17th May 2013`
  **NeKI brief:** Explains Apple’s new Objective-C to Javascript Bridge with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSCoding / NSKeyedArchiver](http://nshipster.com/nscoding) — iOS Dev Weekly · Issue 94 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `17th May 2013`
  **NeKI brief:** Explains NSCoding and keyed archiving for reconstructing persisted object graphs. Useful historical context when maintaining archive-based storage or planning a deliberate migration to a modern persistence format.
- [ArgumentParser](https://github.com/NSError/ArgumentParser) — iOS Dev Weekly · Issue 93 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th May 2013`
  **NeKI brief:** Provides the ArgumentParser source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [We Need A Standard Layered Image Format](http://shapeof.com/archives/2013/4/we_need_a_standard_layered_image_format.html) — iOS Dev Weekly · Issue 92 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `3rd May 2013`
  **NeKI brief:** Explains We Need A Standard Layered Image Format with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [The market for paid iOS apps isn’t dead](http://www.marco.org/2013/04/19/paid-app-market) — iOS Dev Weekly · Issue 91 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `26th April 2013`
  **NeKI brief:** In what might be the conclusion to the App Store pricing discussion that we have seen over the last few weeks Marco Arment says what I was trying hint at in my comments last week in a much more eloquent way. His last sentence sums it all up for me, “The bar…
- [Compiler Warnings for Objective-C Developers](http://oleb.net/blog/2013/04/compiler-warnings-for-objective-c-developers) — iOS Dev Weekly · Issue 91 — Article · Topics: Objective-C & Cocoa
  **Published:** `26th April 2013`
  **NeKI brief:** Treats Clang warnings as a deliberate code-quality tool, explaining how stricter diagnostics catch dangerous but syntactically valid Objective-C patterns and should be enabled incrementally in legacy targets.
- [Common Misconceptions About Touch](http://www.uxmatters.com/mt/archives/2013/03/common-misconceptions-about-touch.php) — iOS Dev Weekly · Issue 91 — Article · Topics: Objective-C & Cocoa · Product Design
  **Published:** `26th April 2013`
  **NeKI brief:** Examines Steven Hoober with a fascinating and well researched article on designing for touch screens, specifically designing tap targets to be big enough (but not too big) and being free of interference with other targets. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Decision tree for...](http://cocoaheads.tumblr.com/post/47525312316/joncrowley-alexcarantza-decision-tree-for) — iOS Dev Weekly · Issue 89 — Article · Topics: Objective-C & Cocoa
  **Published:** `12th April 2013`
  **NeKI brief:** The post presents a decision-tree discussion by CocoaHeads contributors and provides publicly readable software-development context.
- [Streamlining Cocoa Development With CocoaPods](http://mobile.tutsplus.com/tutorials/iphone/streamlining-cocoa-development-with-cocoapods) — iOS Dev Weekly · Issue 88 — Tutorial · Topics: Objective-C & Cocoa
  **Published:** `5th April 2013`
  **NeKI brief:** Explains Streamlining Cocoa Development With CocoaPods with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [10 Things You Need To Know About Cocoa Autolayout](http://oleb.net/blog/2013/03/things-you-need-to-know-about-cocoa-autolayout) — iOS Dev Weekly · Issue 88 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th April 2013`
  **NeKI brief:** Distills Auto Layout into constraint sufficiency, priorities, and intrinsic content size, helping developers reason about ambiguous or unsatisfiable layouts instead of treating constraints as fixed frame assignments.
- [25 iOS App Performance Tips & Tricks](http://www.raywenderlich.com/31166/25-ios-app-performance-tips-tricks) — iOS Dev Weekly · Issue 88 — Article · Topics: Objective-C & Cocoa · Performance
  **Published:** `5th April 2013`
  **NeKI brief:** Explains 25 iOS App Performance Tips Tricks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ADNKit](https://github.com/joeldev/ADNKit) — iOS Dev Weekly · Issue 86 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `22nd March 2013`
  **NeKI brief:** Provides the ADNKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PJTernarySearchTree](https://github.com/peakji/PJTernarySearchTree) — iOS Dev Weekly · Issue 84 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `8th March 2013`
  **NeKI brief:** Yichao Ji with an implementation of a ternary search tree in Objective-C. As mentioned in the readme for the project this makes a great companion to HTAutocompleteTextField which was mentioned back in Issue 79 of iOS Dev Weekly.
- [Nope](http://www.loopinsight.com/2013/02/13/apples-rumored-tv-related-event-in-march) — iOS Dev Weekly · Issue 81 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th February 2013`
  **NeKI brief:** Examines Apple’s rumored TV-related event in March. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS Runtime Headers](https://github.com/nst/iOS-Runtime-Headers) — iOS Dev Weekly · Issue 81 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `15th February 2013`
  **NeKI brief:** I have been aware of this for a little while now but I don’t think I have ever linked to it. Nicolas Seriot keeps a wonderful resource of always up to date exports of the current iOS framework headers, both public and private. This is a useful resource to…
- [Querying Objective-C Data Collections](http://www.cimgf.com/2013/02/05/querying-objective-c-data-collections) — iOS Dev Weekly · Issue 80 — Article · Topics: Objective-C & Cocoa
  **Published:** `8th February 2013`
  **NeKI brief:** Explains Querying Objective-C Data Collections with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Vitamins](http://ashfurrow.com/blog/objective-c-vitamins) — iOS Dev Weekly · Issue 79 — Article · Topics: Accessibility · Objective-C & Cocoa · Testing
  **Published:** `1st February 2013`
  **NeKI brief:** Explains Objective-C Vitamins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [All the C You Need to Know](https://itunes.apple.com/us/book/all-the-c-you-need-to-know/id581989356?mt=11) — iOS Dev Weekly · Issue 77 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `18th January 2013`
  **NeKI brief:** I think many people who started writing Objective-C without previously having written much or any C have a slight fear of the C language. Bill Dudney has decided to try and fix this problem by writing this book. If you have been secretly afraid of the C in…
- [DLIntrospection](https://github.com/garnett/DLIntrospection) — iOS Dev Weekly · Issue 75 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `4th January 2013`
  **NeKI brief:** Provides the DLIntrospection source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Friday Q&A: Objective-C Pitfalls](http://www.mikeash.com/pyblog/friday-qa-2012-12-14-objective-c-pitfalls.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st December 2012`
  **NeKI brief:** Objective-C pitfalls often arise from dynamic dispatch, nil messaging, ownership conventions, and type erasure interacting unexpectedly. The review is useful for locating boundaries where static Swift assumptions do not apply.
- [THObserversAndBinders](https://github.com/th-in-gs/THObserversAndBinders) — iOS Dev Weekly · Issue 71 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Observation & State Management
  **Published:** `7th December 2012`
  **NeKI brief:** Provides the THObserversAndBinders source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [libextobjc](https://github.com/jspahrsummers/libextobjc) — iOS Dev Weekly · Issue 70 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `30th November 2012`
  **NeKI brief:** Examines A Cocoa library to extend the Objective-C programming language. - jspahrsummers/libextobjc. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Xcode in a Nutshell](http://cocoaheads.tumblr.com/post/35711948405/xcode-in-a-nutshell) — iOS Dev Weekly · Issue 68 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `16th November 2012`
  **NeKI brief:** Explains Xcode in a Nutshell with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Zipzap](https://github.com/pixelglow/zipzap) — iOS Dev Weekly · Issue 66 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd November 2012`
  **NeKI brief:** Provides the Zipzap source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [How to Choose Keywords for the App Store](http://mentalfaculty.tumblr.com/post/34476925606/how-to-choose-keywords-for-the-app-store) — iOS Dev Weekly · Issue 66 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains How to Choose Keywords for the App Store with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Chaos Testing With UI AutoMonkey](http://cocoamanifest.net/articles/2012/11/chaos-testing-with-ui-automonkey.html) — iOS Dev Weekly · Issue 66 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains Chaos Testing With UI AutoMonkey with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Mantle: a Model Framework for Objective-C](https://github.com/blog/1299-mantle-a-model-framework-for-objective-c) — iOS Dev Weekly · Issue 65 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `26th October 2012`
  **NeKI brief:** Provides the Mantle a Model Framework for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CTObjectiveCRuntimeAdditions](https://github.com/ebf/CTObjectiveCRuntimeAdditions) — iOS Dev Weekly · Issue 63 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `12th October 2012`
  **NeKI brief:** Provides the CTObjectiveCRuntimeAdditions source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The iPad 1](http://www.marco.org/2012/09/30/ipad-1) — iOS Dev Weekly · Issue 62 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `5th October 2012`
  **NeKI brief:** Reflects on the first iPad’s capabilities and limitations from an early platform perspective. Useful historical context for understanding how tablet interaction expectations developed.
- [Learnable Programming](http://worrydream.com/LearnableProgramming) — iOS Dev Weekly · Issue 61 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th September 2012`
  **NeKI brief:** Not related directly to iOS or Mac development (although it has some nice praise for Objective-C and Cocoa) but this article by Bret Victor on teaching programming and IDE design is wonderful.
- [Experimentation with build numbering](http://paul-samuels.com/blog/2012/08/25/experimentation-with-build-numbering) — iOS Dev Weekly · Issue 57 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `31st August 2012`
  **NeKI brief:** Explains Experimentation with build numbering with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why performSelector: Is More Dangerous Than I Thought](http://www.tomdalling.com/blog/cocoa/why-performselector-is-more-dangerous-than-i-thought) — iOS Dev Weekly · Issue 55 — Article · Topics: Objective-C & Cocoa
  **Published:** `17th August 2012`
  **NeKI brief:** Examines Why performSelector: Is More Dangerous Than I Thought — Tom Dalling. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Avoid security risks with iTunes Connect scraping services](http://www.marco.org/2012/07/31/itc-sales-users) — iOS Dev Weekly · Issue 53 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Security & Privacy
  **Published:** `3rd August 2012`
  **NeKI brief:** Explains Avoid security risks with iTunes Connect scraping services with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [7 Great iOS and Mac Developer Podcasts to Learn from Today](http://accidentaltechnologist.com/objective-c-2/7-great-ios-and-mac-developer-podcasts-to-learn-from-today) — iOS Dev Weekly · Issue 53 — Podcast · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `3rd August 2012`
  **NeKI brief:** Examines I have quite an extensive list of podcast subscriptions in iTunes these days with much of my interest on iOS and Mac development. ? Considering how iTunes is Apple, there are a lot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Busted! Eight Reasons not to use ARC](http://www.learn-cocos2d.com/2012/06/mythbusting-8-reasons-arc) — iOS Dev Weekly · Issue 49 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th July 2012`
  **NeKI brief:** Explains Busted Eight Reasons not to use ARC with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [On AppStore Search Ranking Algorithms](http://creativealgorithms.com/blog/content/appstore-search-ranking-algorithms) — iOS Dev Weekly · Issue 48 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `29th June 2012`
  **NeKI brief:** This article discusses App Store search-ranking algorithms and optimization factors. Follow it for historical discovery and metadata context, while treating rankings and platform behavior as time-sensitive.
- [Friday Q&A: Objective-C Literals](http://www.mikeash.com/pyblog/friday-qa-2012-06-22-objective-c-literals.html) — iOS Dev Weekly · Issue 48 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th June 2012`
  **NeKI brief:** Objective-C literals provide concise syntax for boxed numbers, arrays, dictionaries, and subscripting while retaining runtime collection semantics. The overview helps spot where literal convenience masks mutability or nullability concerns.
- [iOS Hierarchy Viewer](https://github.com/glock45/iOS-Hierarchy-Viewer) — iOS Dev Weekly · Issue 47 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `22nd June 2012`
  **NeKI brief:** Provides the iOS Hierarchy Viewer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Crazy Things you can do with Objective-C Dot Notation](http://www.learn-cocos2d.com/2012/06/crazy-objectivec-dot-notation) — iOS Dev Weekly · Issue 47 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `22nd June 2012`
  **NeKI brief:** Explains The Crazy Things you can do with Objective-C Dot Notation with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical.
- [Circle](https://github.com/mikeash/Circle) — iOS Dev Weekly · Issue 46 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `15th June 2012`
  **NeKI brief:** Provides the Circle source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Log All Messages in Objective-C](https://coderwall.com/p/7mopeq) — iOS Dev Weekly · Issue 45 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `8th June 2012`
  **NeKI brief:** Examines A protip by bontojr about simulator, debug, mac, iphone, and objective-c. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Four Years of App Store](http://www.macstories.net/stories/four-years-of-app-store-developers-weigh-in-on-search-discovery-and-curation) — iOS Dev Weekly · Issue 43 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `25th May 2012`
  **NeKI brief:** Examines "The App Store is a grand slam, with a staggering 10 million applications downloaded in just three days". That's how Apple co-founder and late CEO Steve Jobs saluted. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [My App Crashed, Now What?](http://www.raywenderlich.com/10209/my-app-crashed-now-what-part-1) — iOS Dev Weekly · Issue 42 — Article · Topics: Objective-C & Cocoa
  **Published:** `18th May 2012`
  **NeKI brief:** This is a topic I always like to dive into when training as people new to the language can really struggle to realise exactly what is going wrong when an app crashes. This article by Matthijs Hollemans is worth a read if you are new to Objective-C.
- [ReactiveCocoa for a better world](https://github.com/blog/1107-reactivecocoa-for-a-better-world) — iOS Dev Weekly · Issue 41 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th May 2012`
  **NeKI brief:** Provides the ReactiveCocoa for a better world source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Twitter Text](https://github.com/twitter/twitter-text-objc) — iOS Dev Weekly · Issue 41 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th May 2012`
  **NeKI brief:** Twitter have released an official port of their text handling libraries for Objective-C this week. If you are interacting with data from Twitter at all then I would imagine this library is going to come in very handy.
- [Faking generics in ObjC](http://overooped.com/post/22516989979/tctypesafety) — iOS Dev Weekly · Issue 41 — Article · Topics: Objective-C & Cocoa
  **Published:** `11th May 2012`
  **NeKI brief:** Examines An experiment with typesafe arrays and dictionaries in Objective-C from Joachim Bengtsson. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Lockbox](https://github.com/granoff/Lockbox) — iOS Dev Weekly · Issue 39 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `27th April 2012`
  **NeKI brief:** Provides the Lockbox source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Twitter’s “Innovator’s Patent Agreement”](http://www.marco.org/2012/04/18/twitter-patent-agreement) — iOS Dev Weekly · Issue 38 — Article · Topics: Objective-C & Cocoa
  **Published:** `20th April 2012`
  **NeKI brief:** Examines Twitter’s “Innovator’s Patent Agreement” – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Tipi: Tiny Templating Engine](https://github.com/hiddenmemory/Tipi) — iOS Dev Weekly · Issue 37 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th April 2012`
  **NeKI brief:** Provides the Tipi Tiny Templating Engine source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C, Unversioned](http://mjtsai.com/blog/2012/03/12/objective-c-unversioned) — iOS Dev Weekly · Issue 33 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `16th March 2012`
  **NeKI brief:** I guess we all knew this deep down but Chris Lattner makes it official with a post to the Objective-C language mailing list. No more version numbers for the Objective-C language.
- [Key-Value Observing Done Right: Take 2](http://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — iOS Dev Weekly · Issue 32 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th March 2012`
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NYXImagesKit](https://github.com/Nyx0uf/NYXImagesKit) — iOS Dev Weekly · Issue 31 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd March 2012`
  **NeKI brief:** Provides the NYXImagesKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Dev Weekly on the Cocoanetics Podcast](http://www.cocoanetics.com/2012/02/podcast-26-ios-dev-weekly) — iOS Dev Weekly · Issue 31 — Podcast · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `2nd March 2012`
  **NeKI brief:** I was interviewed by Oliver Drobnik this week for the Cocoanetics podcast so if you have an interest learning about the person behind this email or want to know how I create it each week then you might want to check this out.
- [Xcode and Friends](http://boredzo.org/blog/archives/2012-02-17/xcode-and-friends) — iOS Dev Weekly · Issue 30 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `24th February 2012`
  **NeKI brief:** Explains Xcode and Friends with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLVM 4.0 Compiler](http://cocoaheads.tumblr.com/post/18002019974/llvm-4-0-compiler) — iOS Dev Weekly · Issue 30 — Article · Topics: Objective-C & Cocoa · Systems Programming
  **Published:** `24th February 2012`
  **NeKI brief:** Examines Such tasty treats coming down the line with LLVM 4.0 which was included with the Mountain Lion developer preview release. Thanks to whoever runs this tumblr for breaking the NDA so I can link to this. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [A one finger rotation gesture recognizer](http://blog.mellenthin.de/archives/2012/02/13/an-one-finger-rotation-gesture-recognizer) — iOS Dev Weekly · Issue 29 — Article · Topics: Objective-C & Cocoa
  **Published:** `17th February 2012`
  **NeKI brief:** Explains A one finger rotation gesture recognizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Dependency Graph Tool for iOS Projects](http://jomnius.blogspot.com/2012/01/dependency-graph-tool-for-ios-projects.html) — iOS Dev Weekly · Issue 24 — Article · Topics: Cross-Platform & Web · Dependency Injection · Objective-C & Cocoa
  **Published:** `13th January 2012`
  **NeKI brief:** Examines Jouni Miettunen has been playing with (and fixing) with a visualisation tool for Objective-C project dependencies. I haven’t had a chance to play with it yet but it looks like fun. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [UIAlertView changes in iOS 5](http://useyourloaf.com/blog/2011/12/14/uialertview-changes-in-ios-5.html) — iOS Dev Weekly · Issue 20 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th December 2011`
  **NeKI brief:** Explains UIAlertView changes in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [When GCD Isn’t The Best Abstraction](http://cocoamanifest.net/articles/2011/12/when-gcd-isn-t-the-best-abstraction.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th December 2011`
  **NeKI brief:** Jonathan Penn on MKNetworkKit using NSOperation over GCD. Personally I am a big fan of NSOperation and usually find myself reaching for it in preference to GCD as I find it easier to write clean code with concurrent code being well separated into classes. I…
- [Deconstructing and Putting Back Together Some Icons in Acorn](http://shapeof.com/archives/2011/11/deconstructing_and_putting_back_together_some_icons_in_acorn.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th December 2011`
  **NeKI brief:** Examines Deconstructing and Putting Back Together Some Icons in Acorn. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [More iOS device and OS version stats from Instapaper](http://www.marco.org/2011/11/30/more-ios-device-and-os-version-stats-from-instapaper) — iOS Dev Weekly · Issue 18 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `2nd December 2011`
  **NeKI brief:** Marco Arment with a look at the latest device, carrier and iOS version number stats from Instapaper. Looks like iOS 5 is growing steadily but I agree with him that at 50% it seems too early to require it right now.
- [GMGridView](https://github.com/gmoledina/GMGridView) — iOS Dev Weekly · Issue 18 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd December 2011`
  **NeKI brief:** Provides the GMGridView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Date and Time Handling in Cocoa Cheat Sheet](http://oleb.net/blog/2011/11/date-and-time-in-cocoa-cheat-sheet) — iOS Dev Weekly · Issue 17 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `25th November 2011`
  **NeKI brief:** Collects Cocoa date and time API distinctions, useful for checking formatter, calendar, time-zone, and locale responsibilities before treating a Date as a user-facing value.
- [How to import contacts into the iPhone Simulator](http://www.icodeblog.com/2011/11/09/how-to-import-contacts-into-the-iphone-simulator) — iOS Dev Weekly · Issue 16 — Article · Topics: Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `18th November 2011`
  **NeKI brief:** Explains How to import contacts into the iPhone Simulator with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Why you should almost always write a test app for your Radar bug reports](http://boredzo.org/blog/archives/2011-11-09/why-you-should-almost-always-write-a-test-app-for-your-radar-bug-reports) — iOS Dev Weekly · Issue 15 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `11th November 2011`
  **NeKI brief:** Explains Why you should almost always write a test app for your Radar bug reports with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because.
- [CodeRunner](http://oleb.net/blog/2011/10/coderunner) — iOS Dev Weekly · Issue 14 — Article · Topics: Objective-C & Cocoa
  **Published:** `4th November 2011`
  **NeKI brief:** Explains CodeRunner with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Cleaning...](http://www.marco.org/2011/10/13/ios5-caches-cleaning) — iOS Dev Weekly · Issue 12 — Article · Topics: Objective-C & Cocoa
  **Published:** `21st October 2011`
  **NeKI brief:** Explains Cleaning..., focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Using Regular Expressions Part 2 - the Cocoa Connection](http://www.escortmissions.com/blog/2011/10/15/using-regular-expressions-part-2-the-cocoa-connection.html) — iOS Dev Weekly · Issue 12 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st October 2011`
  **NeKI brief:** Explains Using Regular Expressions Part 2 the Cocoa Connection with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Automatic Reference Counting](http://www.mikeash.com/pyblog/friday-qa-2011-09-30-automatic-reference-counting.html) — iOS Dev Weekly · Issue 10 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `7th October 2011`
  **NeKI brief:** Simply the clearest and best explanation of ARC that I have seen so far. Fascinating.
- [Syntax of the Future Past](http://www.blog.montgomerie.net/syntax-of-the-future-past) — iOS Dev Weekly · Issue 10 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `7th October 2011`
  **NeKI brief:** Jamie Montgomerie with a fascinating bit of internet archaeology digging into modern syntax for Objective-C. An old post but it came up this week after a discussion at the NSScotland conference (which was excellent!).
- [Customer culture](http://www.marco.org/2011/09/17/customer-culture-apple-and-microsoft) — iOS Dev Weekly · Issue 8 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd September 2011`
  **NeKI brief:** Much talk of Windows 8 this week, I liked Marco’s take on it.
- [CocoaPods](https://github.com/CocoaPods/CocoaPods) — iOS Dev Weekly · Issue 8 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `23rd September 2011`
  **NeKI brief:** Presents CocoaPods, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Objective-C Cheat Sheet and Quick Reference](http://www.raywenderlich.com/4872/objective-c-cheat-sheet-and-quick-reference) — iOS Dev Weekly · Issue 8 — Article · Topics: Objective-C & Cocoa
  **Published:** `23rd September 2011`
  **NeKI brief:** The reference sheet summarizes Objective-C syntax and common language constructs for developers maintaining or writing iOS code.
- [Code like you’re Notch](http://www.mrspeaker.net/2011/09/15/code-like-youre-notch) — iOS Dev Weekly · Issue 7 — Article · Topics: Objective-C & Cocoa
  **Published:** `16th September 2011`
  **NeKI brief:** Explains Code like you’re Notch with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS Audio & OpenAL](http://www.youtube.com/watch?v=6QQAzhwalPI) — iOS Dev Weekly · Issue 5 — Video · Topics: Objective-C & Cocoa
  **Published:** `2nd September 2011`
  **NeKI brief:** Records a two-hour CocoaHeads presentation covering iOS audio foundations before moving into cross-platform OpenAL, including buffer-lifetime caveats. Useful historical material for understanding low-level game audio APIs and their memory-management risks.
- [Core Animation Demos](https://github.com/bobmccune/Core-Animation-Demos) — iOS Dev Weekly · Issue 4 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `26th August 2011`
  **NeKI brief:** Presents Core Animation Demos, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Transient Entities and Core Data](http://www.cimgf.com/2011/08/08/transient-entities-and-core-data) — iOS Dev Weekly · Issue 2 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `12th August 2011`
  **NeKI brief:** Explains Transient Entities and Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Remember/Forget](https://github.com/danielctull/Remember-Forget) — iOS Dev Weekly · Issue 2 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `12th August 2011`
  **NeKI brief:** The GitHub repository contains Remember-Forget, an open-source developer project with publicly inspectable source code.
- [ARC](http://clang.llvm.org/docs/AutomaticReferenceCounting.html) — iOS Dev Weekly · Issue 2 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `12th August 2011`
  **NeKI brief:** This Clang specification defines the semantics and compiler rules of Objective-C Automatic Reference Counting. It is the authoritative technical reference for understanding ownership qualifiers, retain and release insertion, and ARC edge cases in mixed-language Apple code.
- [Apple to Lodsys: you’ll have to go through us to sue iOS devs](http://arstechnica.com/apple/news/2011/08/apple-tells-judge-intervention-against-lodsys-should-be-granted.ars) — iOS Dev Weekly · Issue 2 — Article · Topics: Objective-C & Cocoa
  **Published:** `12th August 2011`
  **NeKI brief:** Examines Patent firm Lodsys continues its legal rampage against independent iOS app …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Marco’s post on software patents](http://ignorethecode.net/blog/2011/08/11/why_software_patents_are_not_fixable) — iOS Dev Weekly · Issue 2 — Article · Topics: Objective-C & Cocoa
  **Published:** `12th August 2011`
  **NeKI brief:** I can’t imagine a weekly round up these days that doesn’t include a story about software patents. Apple seems to be insisting on getting involved with the Lodsys patent cases. Good news. You might also want to check out Marco’s post on software patents from…
- [MAD-SLIP](https://go.peterfriese.dev/slip-programming-language-on?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Provides background on SLIP, the list-processing system embedded into languages such as MAD and used by ELIZA. Read it to understand the data structures available to the original program rather than judging it through modern language assumptions.
- [Finding Eliza team](https://go.peterfriese.dev/finding-eliza-team?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Introduces the ELIZA Archaeology Project team that recovered and studied the original materials. It provides provenance for the linked source, reconstructions, and critical readings rather than another independent technical implementation.
- [copy on the Internet Archive](https://go.peterfriese.dev/eliza-1966-source-code?s=newsletter&t=ext) — Not only Swift · Issue 99 — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Routes to an Internet Archive scan of Joseph Weizenbaum’s original MAD-SLIP ELIZA source. Use it as primary historical evidence when checking claims about the interpreter, while expecting archival notation and tooling rather than directly runnable modern code.
- [What AI coding costs you](https://tomwojcik.com/posts/2026-02-15/finding-the-right-amount-of-ai) — Not only Swift · Issue 95 — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** Discusses What AI coding costs you in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Writing good agents.md files](https://www.philschmid.de/writing-good-agents) — Not only Swift · Issue 95 — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **NeKI brief:** This article covers writing effective AGENTS.md instruction files. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [PiSwift](https://github.com/xibbon/PiSwift) — Not only Swift · Issue 94 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** This source repository covers the PiSwift project and its Swift integration surface. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Why you should stop stashing and use worktrees](https://www.marcohaber.dev/blog/git-worktrees) — Not only Swift · Issue 89 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **NeKI brief:** Discusses Why you should stop stashing and use worktrees in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Hybrid AI - Building a Second Brain app (S3 E8)](https://www.youtube.com/watch?v=vQ-clCjkZws) — Not only Swift · Issue 87 — Video · Topics: AI Development · Developer Community & Business · Objective-C & Cocoa
  **NeKI brief:** This livestream builds a second-brain application with a hybrid AI workflow. It provides a concrete implementation walkthrough for combining application data, model-assisted features, and Swift-based product decisions in a real project.
- [Telecommunications Services for the 1990's](https://www.youtube.com/watch?v=_FlvwC1dkzc) — Not only Swift · Issue 85 — Video · Topics: Objective-C & Cocoa
  **NeKI brief:** This historical recording documents telecommunications work associated with the Post Office Research Station in Dollis Hill. It provides technical and institutional context for the research station referenced by the source, rather than being a current product or event listing.
- [The Post Office Research Station in Dollis Hill](https://en.wikipedia.org/wiki/Post_Office_Research_Station) — Not only Swift · Issue 85 — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** This reference article describes the Post Office Research Station in Dollis Hill and its role in telecommunications research. It supplies historical context for the engineering work represented in the linked recording and the development of communications technology.
- [20th Anniversary of Steve Jobs' Stanford Speech](https://stevejobsarchive.com/exhibits/stay-hungry-stay-foolish) — Not only Swift · Issue 83 — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** This Steve Jobs Archive exhibit revisits the 2005 Stanford commencement speech with contextual material and multiple perspectives. The enhanced presentation and supporting documents make it a concrete historical reference for the design and product principles frequently discussed in Apple development culture.
- [Copenhagen Swift & Cocoa Meetup](https://www.meetup.com/copenhagencocoa/events/307836809) — Not only Swift · Issue 81 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents a concrete implementation of Copenhagen Swift & Cocoa Meetup. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swift Error Handling Done Right: Overcoming the Objective-C Error Legacy](https://www.fline.dev/swift-error-handling-done-right-overcoming-the-objective-c-error-legacy) — Not only Swift · Issue 80 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents a concrete implementation of Swift Error Handling Done Right: Overcoming the Objective-C Error Legacy. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Tracing Thoughts in Language Models](https://www.anthropic.com/research/tracing-thoughts-language-model) — Not only Swift · Issue 78 — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** This article covers research methods for tracing language-model internal representations. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
