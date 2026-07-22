# Objective-C & Cocoa

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Objective-C language/runtime, Cocoa and Foundation-era APIs, and historical Mac/iOS implementation techniques.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **581**

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
  **NeKI brief:** The A11's heterogeneous cores make scheduling and benchmark interpretation hardware-aware: throughput and latency can vary with core assignment and workload. Follow it when diagnosing performance results that are not reproducible across devices.
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
  **NeKI brief:** A table-view implementation coordinates data source queries, visible-cell reuse, scrolling, and layout invalidation. Recreating it demonstrates why reuse identity and incremental updates are core performance mechanisms.
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
  **NeKI brief:** CommonCrypto exposes low-level hashing, encryption, and MAC primitives with byte-buffer APIs. The tour highlights algorithm choice, key handling, and authenticated encryption boundaries that wrappers must preserve.
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
  **NeKI brief:** A mutable array implementation must define indexing, capacity growth, mutation detection, ownership, and iteration guarantees together; its storage optimizations are valid only if those collection contracts remain intact.
- [mikeash.com: Friday Q&A 2012-03-02: Key-Value Observing Done Right: Take 2](https://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — Mike Ash · article catalogue
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [mikeash.com: Friday Q&A 2012-02-17: Ring Buffers and Mirrored Memory: Part II](https://www.mikeash.com/pyblog/friday-qa-2012-02-17-ring-buffers-and-mirrored-memory-part-ii.html) — Mike Ash · article catalogue
  **NeKI brief:** Mirrored virtual-memory mapping lets a ring buffer’s logical wraparound occupy contiguous address space, simplifying bulk reads and writes while trading implementation complexity and platform-specific virtual-memory setup.
- [mikeash.com: Friday Q&A 2012-02-03: Ring Buffers and Mirrored Memory: Part I](https://www.mikeash.com/pyblog/friday-qa-2012-02-03-ring-buffers-and-mirrored-memory-part-i.html) — Mike Ash · article catalogue
  **NeKI brief:** A ring buffer separates producer and consumer progress with bounded storage; keep index updates atomic and distinguish full from empty without forcing either side to copy or block unnecessarily.
- [mikeash.com: Friday Q&A 2012-01-20: Fork Safety](https://www.mikeash.com/pyblog/friday-qa-2012-01-20-fork-safety.html) — Mike Ash · article catalogue
  **NeKI brief:** After `fork`, a multithreaded process retains only the calling thread while locks may remain held by vanished threads; do minimal async-safe work before `exec` and avoid ordinary framework calls.
- [mikeash.com: Friday Q&A 2011-12-02: Object File Inspection Tools](https://www.mikeash.com/pyblog/friday-qa-2011-12-02-object-file-inspection-tools.html) — Mike Ash · article catalogue
  **NeKI brief:** Object-file inspection tools reveal symbols, sections, architectures, load commands, and linked dependencies; inspect build artifacts when linker, loader, or binary-size behavior differs from source-level expectations.
- [mikeash.com: Friday Q&A 2011-11-11: Building a Memoizing Block Proxy](https://www.mikeash.com/pyblog/friday-qa-2011-11-11-building-a-memoizing-block-proxy.html) — Mike Ash · article catalogue
  **NeKI brief:** Memoization caches a function result by its input identity, reducing repeated work only when the function is pure enough; bound cache lifetime and define invalidation for mutable data or resource-heavy results.
- [mikeash.com: Friday Q&A 2011-10-28: Generic Block Proxying](https://www.mikeash.com/pyblog/friday-qa-2011-10-28-generic-block-proxying.html) — Mike Ash · article catalogue
  **NeKI brief:** A generic block proxy can interpose before or after arbitrary callback execution, enabling instrumentation or adaptation; preserve the original signature, ownership, return behavior, and error propagation at the proxy boundary.
- [mikeash.com: Friday Q&A 2011-09-30: Automatic Reference Counting](https://www.mikeash.com/pyblog/friday-qa-2011-09-30-automatic-reference-counting.html) — Mike Ash · article catalogue
  **NeKI brief:** ARC inserts ownership operations from strong, weak, and unowned relationships, but cannot infer semantic lifetime; design the graph explicitly and use diagnostics to find cycles or escaping references.
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

- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Scribe](https://github.com/FluidInference/swift-scribe) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Swift Scribe combines local microphone transcription with on-device summarization on current Apple OS releases, without external dependencies. Useful for evaluating a privacy-preserving speech pipeline and its deployment-version constraints.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-07-15`
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [You asked…we delivered! Submit your swiftCon talk by July 5th!](https://www.nextappcon.com/swiftcon) — iOS Dev Weekly · Issue 757 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `3rd July 2026`
  **NeKI brief:** SwiftCon's call for speakers seeks production-focused Swift and iOS talks, including SwiftUI, architecture, performance, and testing. Follow the event page to assess the community's current themes or submit a concrete engineering case study.
- [Apple App Store Scraper](https://apify.com/maximedupre/apple-app-store-scraper) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Apify's Apple App Store Scraper extracts app metadata, ratings, reviews, rankings, and related store information into structured datasets. Use it for repeatable App Store research, while respecting platform terms and rate limits.
- [What’s New In SwiftUI For iOS 27?](https://www.youtube.com/watch?v=tNxEqyUVGck) — Those Who Swift · Issue 273 — Video · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-07-01`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [_UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots?ref=createwithswift.com) — Create with Swift · Issue 113 — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **Published:** `2026-06-27T18:12:28.000Z`
  **NeKI brief:** Explores UIKit's UIPortalView for live view replication without copying or taking snapshots. Follow it when evaluating mirrored or glass-like effects and when deciding how rendering, hierarchy, interaction, and performance constraints affect the design.
- [Liquid Glass In SwiftUI: How To Modernize An iOS App Template](https://iosapptemplates.com/blog/liquid-glass-swiftui-app-template-modernization) — Those Who Swift · Issue 272 — Article · Topics: Liquid Glass · Swift · SwiftUI
  **Published:** `2026-06-24`
  **NeKI brief:** Walks through modernizing a SwiftUI template with Liquid Glass styling. Use it to identify migration touchpoints in an existing UI, then validate visual hierarchy, accessibility, and API availability rather than applying the template wholesale.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — SwiftUI Weekly · SwiftUI Weekly - Issue #236 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-06-22T10:29:00.171Z`
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Fatbobman](https://fatbobman.com/en/about) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Presents fatbobman for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [BarDict](https://github.com/TokinoyuushaLink/BarDict) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Hardware & Devices · Objective-C & Cocoa
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** BarDict is a macOS menu-bar dictionary application supporting MDX and MDD resources. Useful for evaluating offline dictionary lookup and packaged language assets in a compact AppKit-style utility.
- [Modern Isn’t A Value. Fit Is.](https://www.swiftdifferently.com/blog/system-desgin/modern-isnot-a-value-fit-Is) — Those Who Swift · Issue 268 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-05-27`
  **NeKI brief:** Argues that modern APIs are not automatically the right fit for every product or codebase. Use it as an architecture prompt: weigh compatibility, team understanding, migration cost, and user value before adopting a newer framework pattern.
- [SwiftScript](https://github.com/Cocoanetics/SwiftScript) — Fatbobman’s Swift Weekly · Issue 137 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-05-25T12:03:50.192Z`
  **NeKI brief:** SwiftScript is an experimental embeddable interpreter that parses and executes Swift ASTs with SwiftSyntax rather than invoking swiftc. Use it to study interpreter architecture and dynamic scripting trade-offs in a Swift-hosted environment.
- [A Feature Flags System In Swift](https://livsycode.com/best-practices/a-feature-flags-system-in-swift) — Those Who Swift · Issue 267 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-05-21`
  **NeKI brief:** Presents a Swift feature-flags design with centralized evaluation and rollout control. Use it to compare configuration models and testing seams, while ensuring flag ownership, expiration, and failure defaults are explicit in production.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Those Who Swift · Issue 266 — Article · Topics: Architecture · Networking · Performance
  **Published:** `2026-05-13`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Those Who Swift · Issue 266 — Video · Topics: Architecture · Concurrency · Networking
  **Published:** `2026-05-13`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift ARC: From Zombie Objects to Side Tables](https://livsycode.com/swift/swift-arc-from-zombie-objects-to-side-tables) — SwiftLee Weekly · Issue 323 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2026-05-12T14:05:49.000Z`
  **NeKI brief:** Explains Swift ARC through zombie objects, reference counting, and side tables. Use it as a low-level diagnostic aid when investigating unexpected retention or weak-reference behavior, especially in mixed Swift and Objective-C code.
- [Swift Concurrency: One await, Two Actors: A Runtime Trace](https://adjoe.io/company/engineer-blog/swift-concurrency-await-runtime-trace-executor-hops) — Those Who Swift · Issue 265 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2026-05-06`
  **NeKI brief:** Traces how an await can move execution between actors and executors at runtime. Follow it when diagnosing latency or unexpected scheduling, using Instruments or logs to validate hops instead of inferring behavior from source order alone.
- [DanceUI](https://github.com/bytedance/DanceUI) — Fatbobman’s Swift Weekly · Issue 132 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** DanceUI is ByteDance's open-source exploration of reimplementing SwiftUI concepts. Use it to inspect alternative declarative-UI architecture and rendering decisions, without assuming behavior matches Apple's private implementation.
- [Modern Swift Library Architecture](https://coenttb.com/en/blog/4-1-the-swift-package) — Fatbobman’s Swift Weekly · Issue 132 — Article · Topics: Architecture · Foundation & Data Formats · Swift
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** Describes a layered Swift package ecosystem spanning primitives, standards, and foundations. Use it to study package-boundary design and dependency layering when a growing library family needs more than one monolithic module.
- [SwiftZilla](https://swiftzilla.dev/) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** SwiftZilla indexes a Swift project to expose dependency graphs, semantic search, impact analysis, and convention-aware code review through an AI workflow. It is useful for evaluating whether architectural onboarding can be automated without losing project-specific context.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [Returned For RevisionSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
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
- [I Refactored 3 Apps In A Year. Here’s What I Actually Learned](https://kubamilcarz.medium.com/i-refactored-3-apps-in-a-year-heres-what-i-actually-learned-bc519ba33bb1?source=rss-b30973e2bd56------2) — Those Who Swift · Issue 259 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-03-26`
  **NeKI brief:** Examines I Refactored 3 Apps In A Year. Here’s What I Actually Learned, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Those Who Swift · Issue 258 — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2026-03-18`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [add it to the directory](https://iosdevdirectory.com/contributing) — iOS Dev Weekly · Issue 746 — Article · Topics: Objective-C & Cocoa
  **Published:** `13th March 2026`
  **NeKI brief:** Explores add their site for them, focusing on so, whether you’ve fully migrated to mastodon or now split. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Those Who Swift · Issue 257 — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Borrowing from Kotlin/Android to Architect Scalable iOS Apps in SwiftUI](https://www.infoq.com/articles/kotlin-scalable-swiftui-patterns) — SwiftUI Weekly · SwiftUI Weekly - Issue #230 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-09T13:33:31.501Z`
  **NeKI brief:** Translates scalable architecture ideas from Kotlin and Android into SwiftUI patterns, with emphasis on boundaries and composition. Useful for comparing cross-platform architectural trade-offs before adopting abstractions in a growing iOS codebase.
- [ListKit](https://github.com/Iron-Ham/Lists) — Fatbobman’s Swift Weekly · Issue 125 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** Lists investigates UIKit diffable-data-source stalls caused by snapshot internals, then offers an alternative list approach. Use it when frequent updates cause measurable collection-view hitches and profiling points to diffing overhead.
- [SwiftUI Foundations: Build Great Apps Q&A](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — Those Who Swift · Issue 254 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2026-02-18`
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Add an Open Recent Menu to a SwiftUI app](https://swiftdevjournal.com/posts/open-recent-menu) — SwiftUI Weekly · SwiftUI Weekly - Issue #228 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-02-09T10:51:28.125Z`
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [its discontinuation](https://browsercompany.substack.com/p/letter-to-arc-members-2025) — iOS Dev Weekly · Issue 741 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th January 2026`
  **NeKI brief:** Explains the Browser Company's 2025 decision and communication to Arc members. Useful historical context for assessing product continuity, migration expectations, and risks when relying on a fast-changing developer tool.
- [Skip Is Now Free and Open Source](https://skip.dev/blog/skip-is-free) — iOS Dev Weekly · Issue 740 — Article · Topics: Objective-C & Cocoa · Product Design
  **Published:** `23rd January 2026`
  **NeKI brief:** Announces Skip as free and open source, enabling shared Swift and SwiftUI code to target additional platforms through translation. Useful for evaluating cross-platform reach, with platform-specific behavior still requiring verification.
- [MVVM and Reducer Pattern in Swift](https://www.fractal-dev.com/blog/mvvm-and-reducer-pattern?lang=en) — Those Who Swift · Issue 249 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2026-01-14`
  **NeKI brief:** Examines MVVM and Reducer Pattern in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [Mastering SwiftUI — Free Guide](https://psimas.gumroad.com/l/swiftui?layout=discover&recommended_by=search&_gl=1%2A10g751b%2A_ga%2AODYxNDkzMDQzLjE3NjU2NDU4NjM.%2A_ga_6LJN6D94N6%2AczE3NjU2NDU4NjIkbzEkZzAkdDE3NjU2NDU4NjIkajYwJGwwJGgw) — Those Who Swift · Issue 245 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines Mastering SwiftUI — Free Guide, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Organizing SwiftUI Views with TabContent and TabContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Those Who Swift · Issue 243 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-12-10`
  **NeKI brief:** Explains organizing SwiftUI tabs with TabContent and TabContentBuilder. Follow it when composing tab configuration declaratively, checking availability and selection state, and preserving clear navigation semantics as tab content grows.
- [Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`](https://github.com/apple/swift-evolution/blob/main/proposals/0283-tuples-are-equatable-comparable-hashable.md) — SwiftLee Weekly · Issue 301 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-12-09T15:08:23.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 301 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-12-09T15:08:23.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [RIB](https://github.com/son-iOS/SwiftUI-RIB) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SwiftUI-RIB adapts Uber's Router–Interactor–Builder architecture with dependency structs, Combine communication, and state/view containers. It is useful for comparing explicit parent-child lifecycle and navigation boundaries with coordinator or environment-driven SwiftUI designs.
- [Uber’s official documentation](https://github.com/uber/RIBs) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** Uber's RIBs framework structures mobile features around Router, Interactor, and Builder components with explicit lifecycles and parent-child ownership. Useful as an architectural comparison point for navigation-heavy applications and SwiftUI coordinators.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Those Who Swift · Issue 241 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-11-20`
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [From Swift to Mojo and high-performance AI Engineering with Chris Lattner](https://newsletter.pragmaticengineer.com/p/from-swift-to-mojo-and-high-performance) — SwiftLee Weekly · Issue 297 — Podcast · Topics: AI Development · Performance · Swift
  **Published:** `2025-11-11T15:06:31.000Z`
  **NeKI brief:** Presents From Swift to Mojo and high-performance AI Engineering with Chris Lattner, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Combine Annotations and Swift Concurrency](https://www.massicotte.org/combine-annotations) — Those Who Swift · Issue 239 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Organizing SwiftUI Views With ToolbarContent and ToolbarContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-toolbarcontent-and-toolbarcontentbuilder) — Those Who Swift · Issue 239 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2025-11-05`
  **NeKI brief:** Shows how ToolbarContent and ToolbarContentBuilder structure SwiftUI toolbars. Use it when sharing toolbar composition across screens while keeping placement, role, platform differences, and accessibility labels explicit.
- [MacPacker](https://github.com/sarensw/MacPacker) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** MacPacker creates and packages macOS applications from project inputs, automating repeatable archive, signing, and distribution steps. It is useful for examining a small focused alternative to hand-written packaging scripts in local or CI release workflows.
- [porting to the Android platform](https://github.com/OpenSwiftUIProject/OpenSwiftUI/issues?q=is%3Aissue+label%3A%22platform%3A+Android%22) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** This OpenSwiftUI issue view tracks Android-platform work and compatibility questions in an open-source SwiftUI reimplementation. Follow it to assess cross-platform progress and limitations, not as evidence about Apple's private SwiftUI implementation.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — SwiftLee Weekly · Issue 294 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents SwiftUI Architecture: Structure Views for Reusability and Clarity as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Build, run, debug, and test your Swift apps in Zed](https://luxmentis.org/blog/ios-and-mac-apps-in-zed) — iOS Dev Weekly · Issue 731 — Article · Topics: Objective-C & Cocoa · Performance · Product Design
  **Published:** `17th October 2025`
  **NeKI brief:** Presents build, run, debug, and test your swift apps in zed for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 293 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-10-14T14:14:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 106 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [Darling](https://github.com/darlinghq/darling) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Darling provides a macOS runtime environment on Linux, including DPREFIX-style environments, package and DMG handling, and support for compiling with Apple's toolchain and SDKs. It is useful for understanding the practical limits of cross-platform macOS compatibility.
- [Is MVVM a bad architecture for SwiftUI?](https://www.youtube.com/watch?v=KY4jvbrlzMM) — Those Who Swift · Issue 233 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-09-24`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Protocol Oriented Design: Build a Pluggable Data Source](https://blog.stackademic.com/swift-protocol-oriented-design-build-a-pluggable-data-source-57e7937312aa) — Those Who Swift · Issue 232 — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2025-09-17`
  **NeKI brief:** Examines Swift Protocol Oriented Design: Build a Pluggable Data Source, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Northern Stars of Liquid Glass](https://captainswiftui.substack.com/p/the-northern-stars-of-liquid-glass) — Those Who Swift · Issue 232 — Article · Topics: Liquid Glass · Objective-C & Cocoa · Swift
  **Published:** `2025-09-17`
  **NeKI brief:** Examines The Northern Stars of Liquid Glass, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Cupertino Ghost in the Machine: An Analysis of Xcode’s New AI Assistant](https://wezzard.com/post/2025/08/the-cupertino-ghost-in-the-machine-9ee3) — iOS Dev Weekly · Issue 725 — Article · Topics: AI Development · Objective-C & Cocoa · Xcode
  **Published:** `5th September 2025`
  **NeKI brief:** Presents the cupertino ghost in the machine: an analysis of xcode’s new ai assistant for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [The Great Shift in Apple Development](https://captainswiftui.substack.com/p/the-great-shift-in-apple-development) — Those Who Swift · Issue 230 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-09-03`
  **NeKI brief:** Examines The Great Shift in Apple Development, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [STTextView](https://github.com/krzyzanowskim/STTextView) — Fatbobman’s Swift Weekly · Issue 98 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-08-18T12:03:30.201Z`
  **NeKI brief:** STTextView is a TextKit 2-based text editor that exposes the practical gaps encountered in Apple's newer text system. Use it when building editor-like macOS UI and needing a tested reference for selection, layout, and editing behavior.
- [more Swift and SwiftUI](https://blog.timac.org/2024/1208-state-of-swift-and-swiftui-ios18) — iOS Dev Weekly · Issue 722 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `15th August 2025`
  **NeKI brief:** Surveys how Apple used Swift and SwiftUI in iOS 18, connecting framework capabilities to production features. Useful for identifying platform-supported patterns before designing equivalent app architecture.
- [NavigationStack Deep Linking in Large SwiftUI Apps](https://medium.com/@wesleymatlock/%EF%B8%8F-navigationstack-deep-linking-in-large-swiftui-apps-439a1ce77337) — Those Who Swift · Issue 227 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2025-08-13`
  **NeKI brief:** Examines NavigationStack Deep Linking in Large SwiftUI Apps, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Flux pattern in Swift](https://swiftandpizza.wpcomstaging.com/flux-in-swift) — SwiftLee Weekly · Issue 282 — Article · Topics: Objective-C & Cocoa · Product Design · Swift
  **Published:** `2025-07-29T14:14:45.000Z`
  **NeKI brief:** Presents Flux pattern in Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — SwiftLee Weekly · Issue 280 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 92 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-07-07T12:01:56.119Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 278 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Xcode
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Rewriting a 12 Year Old Objective-C iOS App with Claude Code](https://twocentstudios.com/2025/06/22/vinylogue-swift-rewrite) — iOS Dev Weekly · Issue 716 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `27th June 2025`
  **NeKI brief:** Examines Rewriting a 12 Year Old Objective-C iOS App with Claude Code, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Essential xcodebuild Commands for iOS Developers](https://medium.com/@awasthi027.ashish/essential-xcodebuild-commands-for-ios-developers-9ff101783ce2) — Those Who Swift · Issue 195 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Xcode
  **Published:** `2025-06-18`
  **NeKI brief:** Examines Essential xcodebuild Commands for iOS Developers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
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
- [SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-colours-and-images-in-a-swift-package) — Those Who Swift · Issue 213 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-05-07`
  **NeKI brief:** Examines SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Enforce Your Architecture in Swift with Harmonize](https://itnext.io/goodbye-code-reviews-hello-harmonize-0a49e2872b5a) — iOS Dev Weekly · Issue 710 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2nd May 2025`
  **NeKI brief:** Presents enforce your architecture in swift with harmonize for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — SwiftLee Weekly · Issue 269 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-04-29T14:18:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ErrorKit](https://github.com/FlineDev/ErrorKit) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** ErrorKit is an Apple-platform error presentation layer that turns failures into user-facing alerts, sheets, or notifications while keeping error handling composable. The source helps evaluate a centralized approach to reporting errors across SwiftUI and UIKit flows.
- [The first newsletter for product engineers](https://go.posthog.com/idt-apr24) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** This PostHog resource link leads to product analytics material shared with iOS Dev Tools. Use it to investigate event instrumentation and product insights, verifying the linked content, SDK behavior, consent model, and data-retention settings.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift 6.1 Released](https://www.swift.org/blog/swift-6.1-released) — iOS Dev Weekly · Issue 706 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `4th April 2025`
  **NeKI brief:** Summarizes the Swift 6.1 release and its ecosystem changes. Use it as a starting point for compiler or package upgrades, verifying source compatibility, concurrency diagnostics, and platform support against the toolchain you actually ship.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Composable Architecture: How Architectural Design Decisions Influence Performance](https://www.swiftyplace.com/blog/the-composable-architecture-performance) — SwiftUI Weekly · SwiftUI Weekly - Issue #211 — Article · Topics: Architecture · Objective-C & Cocoa · Performance
  **Published:** `2025-03-25T13:30:35.672Z`
  **NeKI brief:** Examines performance implications of The Composable Architecture in SwiftUI, including reducer and view update costs. Useful for measuring architectural overhead in realistic workloads rather than assuming framework use is free or prohibitive.
- [Let’s Vision](https://letsvision.swiftgg.team/) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Let’s Vision is an Apple-platform developer event in Shanghai, listed with its March dates. Use it to locate conference talks and community material around iOS and visionOS, not as a normative implementation source.
- [Swift on Android Community Workgroup](https://forums.swift.org/t/swift-on-android-working-group/77780) — Fatbobman’s Swift Weekly · Issue 71 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** Tracks the Swift on Android working group's scope and coordination. Use it to distinguish language/runtime portability from UIKit availability when assessing a shared Swift codebase for Android targets.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [ZIP Foundation](https://github.com/weichsel/ZIPFoundation) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Provides the public source repository for ZIP Foundation. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
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
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** Explains SwiftUI environment propagation, custom keys, and dependency lookup. Useful for deciding which shared services belong in environment values versus explicit initializer parameters.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** A configurable logging framework for Apple platforms that routes messages to destinations such as console, files, or remote servers. Its filtering and low-overhead logging model is useful when designing diagnostics that remain practical in production builds.
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
- [PragmaConf](https://pragmaconference.com/) — iOS Dev Tools · iOS Dev Tools: AboutKit, Swift Async Algorithms, Parchment — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `2024-10-17T15:13:39.704Z`
  **NeKI brief:** Provides the Pragmaconference event hub for talks and community sessions about Apple development. Use it to discover practitioner perspectives and verify session details before relying on a conference presentation.
- [Quick](https://github.com/Quick/Quick) — iOS Dev Tools · iOS Dev Tools: Jazzy, Concentric Onboarding, Quick — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-10-10T16:40:59.907Z`
  **NeKI brief:** Quick adds a behavior-driven testing DSL for Swift and Objective-C, organizing examples with describe/context blocks and readable expectations. Its companion Nimble matcher style is useful when comparing specification-oriented tests with XCTest assertions.
- [SwiftDeps](https://swiftdeps.com/) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** SwiftDeps visualizes and manages dependencies among Xcode project components, helping teams inspect architectural connections. Use it when reviewing modularization or dependency direction and when generated project structure needs a more navigable map.
- [A Summary Of How To Pass Data To SwiftUI Environment](https://serialcoder.dev/text-tutorials/swiftui/a-summary-of-how-to-pass-data-to-swiftui-environment?ref=createwithswift.com) — Create with Swift · Issue 22 — Tutorial · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2024-07-19T16:00:03.000Z`
  **NeKI brief:** Summarizes passing dependencies through SwiftUI environment values and custom keys. Useful for comparing environment injection with explicit data flow in reusable views.
- [Rand Fishkin](https://sparktoro.com/blog/author/rand) — Fatbobman’s Swift Weekly · Issue 39 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `2024-07-08T12:00:38.197Z`
  **NeKI brief:** Provides contextual background on Rand Fishkin, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [A Summary Of How To Pass Data To SwiftUI Environment](https://serialcoder.dev/text-tutorials/swiftui/a-summary-of-how-to-pass-data-to-swiftui-environment) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Tutorial · Topics: Developer Career & Practice · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Summarizes passing dependencies through SwiftUI environment values and custom keys. Useful for comparing environment injection with explicit data flow in reusable views.
- [Sw!ftalyzer](https://swiftalyzer.com/) — iOS Dev Tools · iOS Dev Tools: Sw!ftalyzer, Invoice Maker, SQLite.swift — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-05-30T15:20:30.896Z`
  **NeKI brief:** Swiftalyzer is a Swift code-analysis tool intended to surface project structure or quality signals. Use it as a discovery lead for static analysis, verifying rule coverage, false-positive handling, performance, and integration with the project’s review pipeline.
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
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [fully open-source and available on GitHub](https://github.com/thebrowsercompany/swift-winrt?ref=createwithswift.com) — Create with Swift · Issue 11 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-05-03T15:00:23.000Z`
  **NeKI brief:** swift-winrt generates Swift projections over Windows Runtime and its COM-based ABI. Use it to study cross-platform bindings, generated interop, and the boundary between Swift ergonomics and platform-specific runtime contracts.
- [Swift Server Workgroup](https://www.swift.org/sswg) — iOS Dev Weekly · Issue 658 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `26th April 2024`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Professional Grade Application Protection for Swift and Objective-C iOS Apps](https://www.vpdae.com/redirect/e9xwl532e60eyhhks87um6yabmy) — SwiftUI Weekly · SwiftUI Weekly - Issue #183 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2024-04-22T17:42:59.039Z`
  **NeKI brief:** Promotes application protection for Swift and Objective-C binaries. Useful only as security-product context when assessing threat models and tooling claims for shipped apps.
- [Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) — Fatbobman’s Swift Weekly · Issue 27 — Article · Topics: AI Development · Objective-C & Cocoa
  **Published:** `2024-04-15T22:00:50.399Z`
  **NeKI brief:** Ferret-UI studies grounded mobile-interface understanding with multimodal language models. Follow it for research context on extracting actionable UI structure from screenshots and interaction traces, distinct from ordinary OCR.
- [In Search of a Smooth Scroll](https://byla.lt/posts/in-search-of-smooth-scroll) — SwiftUI Weekly · SwiftUI Weekly - Issue #181 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-04-09T05:33:14.059Z`
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind In Search of a Smooth Scroll. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Recreating Apple’s beautiful visionOS search bar](https://christianselig.com/2024/03/recreating-visionos-search-bar) — iOS Dev Weekly · Issue 654 — Article · Topics: Objective-C & Cocoa · Spatial Computing · Swift
  **Published:** `29th March 2024`
  **NeKI brief:** Presents recreating apple’s beautiful visionos search bar for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Let’s VisionOS 2024](https://letsvisionos24.swiftgg.team/en) — iOS Dev Tools · iOS Dev tools: Ducky Model Editor, LocalizApp, Brewer X — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Spatial Computing
  **Published:** `2024-03-28T15:43:54.859Z`
  **NeKI brief:** Let’s VisionOS 2024 is a Beijing event focused on visionOS and Apple-platform development. Use it to find historical conference material and community perspectives, not as current API documentation or a direct implementation tutorial.
- [release process](https://forums.swift.org/t/swift-6-0-release-process/70220) — Fatbobman’s Swift Weekly · Issue 20 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `2024-02-26T22:00:30.721Z`
  **NeKI brief:** The Swift 6 release-process discussion records how toolchains, proposals, and release milestones are coordinated. Use it to understand version timing and migration planning rather than treating a release label as a complete compatibility guarantee.
- [On-device ML research with MLX and Swift](https://www.swift.org/blog/mlx-swift) — iOS Dev Weekly · Issue 649 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `23rd February 2024`
  **NeKI brief:** Presents on-device ml research with mlx and swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Quick Search with SwiftUI Searchable](https://danielsaidi.com/blog/2023/12/20/quick-search-with-swiftui-searchable) — Fatbobman’s Swift Weekly · Issue 12 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Shows a compact searchable SwiftUI flow with query state and filtering. Follow it when adding search to a list and deciding where debouncing, predicate construction, or empty-query behavior belongs.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [new mlx repository](https://github.com/ml-explore/mlx) — iOS Dev Weekly · Issue 639 — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `8th December 2023`
  **NeKI brief:** MLX is Apple's research-oriented array and machine-learning framework for Apple Silicon, exposing unified CPU/GPU memory concepts. Useful for evaluating local model experiments outside a Python-only workflow.
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
  **NeKI brief:** swift-winrt generates Swift projections over Windows Runtime and its COM-based ABI. Use it to study cross-platform bindings, generated interop, and the boundary between Swift ergonomics and platform-specific runtime contracts.
- [example](https://github.com/thebrowsercompany/windows-samples) — Fatbobman’s Swift Weekly · Issue 5 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Collects Windows sample projects that accompany experiments with Swift and WinRT interoperability. Follow it for concrete API-binding and build examples, while keeping platform-specific assumptions isolated from portable Swift package code.
- [OpenSwiftUI](https://github.com/Kyle-Ye/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Kyle Ye's OpenSwiftUI work offers a research implementation for studying SwiftUI and AttributeGraph-like behavior. Follow it for comparative experiments and internals-oriented learning, not as a compatibility promise for production Apple-platform code.
- [Xcode Search Scopes](https://xcode.tips/search-scopes) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `4th August 2023`
  **NeKI brief:** Explores Xcode Search Scopes, focusing on i’m a fan of the xcode feature in this latest. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introspect for SwiftUI - Unleashing the Power of UIKit and AppKit in SwiftUI](https://github.com/intitni/CopilotForXcode) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [A Layered Approach to Mobile App Security](https://www.guardsquare.com/defense-in-depth-layered-approach-to-mobile-app-security) — iOS Dev Weekly · Issue 612 — Article · Topics: Architecture · Objective-C & Cocoa · Security & Privacy
  **Published:** `2nd June 2023`
  **NeKI brief:** Explores A Layered Approach to Mobile App Security, focusing on developers are being called on to reevaluate their mobile application. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The difference between List and LazyVStack](https://dimillian.medium.com/swiftui-the-difference-between-list-and-lazyvstack-3d5eeaccb156) — SwiftUI Weekly · SwiftUI Weekly - Issue #134 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2023-03-06T15:27:12.172Z`
  **NeKI brief:** Compares List with LazyVStack through the rendering, scrolling, and interaction behaviour that makes them different despite similar output. Follow it before replacing one with the other in a performance-sensitive screen or a layout needing list-specific capabilities.
- [Arc Coding Chronicles](https://www.youtube.com/watch?v=94asyypYj5c) — SwiftUI Weekly · SwiftUI Weekly - Issue #132 — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `2023-02-21T07:37:59.536Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The evolution of Facebook’s iOS app architecture](https://engineering.fb.com/2023/02/06/ios/facebook-ios-app-architecture) — iOS Dev Weekly · Issue 596 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th February 2023`
  **NeKI brief:** Explores The evolution of Facebook’s iOS app architecture, focusing on i’ve never worked on a huge ios app like facebook,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift Snippets](https://forums.swift.org/t/swift-snippets/51947/1) — iOS Dev Weekly · Issue 585 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `18th November 2022`
  **NeKI brief:** Explores Swift Snippets, focusing on like marco eidinger, i was also reminded of the swift snippets feature in swift package manager as i read the post on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [His latest post covers IOS 16](https://blog.timac.org/2022/1005-state-of-swift-and-swiftui-ios16) — iOS Dev Weekly · Issue 579 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `7th October 2022`
  **NeKI brief:** Explores His latest post covers IOS 16, focusing on his latest post covers ios 16, and the results start. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
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
- [SwiftUI Digital Lounge archive](https://midnight-beanie-ccb.notion.site/swiftui-lounge-wwdc22-e20094b91f074398ba395c3fa245e63d) — iOS Dev Weekly · Issue 563 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `17th June 2022`
  **NeKI brief:** Explores SwiftUI Digital Lounge archive, focusing on the digital lounges were great again this year, but they. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Project wide refactoring for if let](https://dev.to/vibrazy/if-let-shorthand-project-wide-refactoring-using-xcode-regex-search-replace-enh) — iOS Dev Weekly · Issue 562 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `10th June 2022`
  **NeKI brief:** Explores Project wide refactoring for if let, focusing on if you’re already fully switched over to swift 5.7. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Transitioning from Intel to Apple Silicon](https://www.macstadium.com/transitioning-from-intel-to-apple-silicon) — iOS Dev Weekly · Issue 560 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `27th May 2022`
  **NeKI brief:** Explores Transitioning from Intel to Apple Silicon, focusing on not sure how your mac builds or tests will be. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [STTextView](https://christiantietze.de/posts/2022/05/sttextview-textkit-2-editor-without-nstextview) — iOS Dev Weekly · Issue 558 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th May 2022`
  **NeKI brief:** Explores STTextView, focusing on talking of textkit 2, in this post, christian tietze talks about marcin krzyzanowski’s syntax highlighting text editor control for macos, sttextview. it’s. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
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
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html) — iOS Dev Weekly · Issue 541 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `14th January 2022`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The SwiftUI Environment](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5maXZlc3RhcnMuYmxvZy9hcnRpY2xlcy9zd2lmdHVpLWVudmlyb25tZW50LXByb3BhZ2F0aW9uLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQwODQ4YzM4LWI2YTQtNDFiZC04Mzg0LTU4YzJlNWRjZjE1MSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJjNTRlMGI4OS0zZmY3LTQxMzQtYmJkYS01NjNhMDU4Y2QyMDkiLCJpYXQiOjE2NzQwNjI2MTcuNzcsImlzcyI6Im9yY2hpZCJ9.HuT9AYMXhtb-Iiu_vZyWQr5EEwI4m_9PWqCDa4hGB-M) — SwiftUI Weekly · SwiftUI Weekly - Issue #78 — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **Published:** `2021-10-04T18:21:47.000Z`
  **NeKI brief:** Explains how SwiftUI environment values propagate dependencies and configuration through a view hierarchy. Useful for designing shared settings and services while keeping injection explicit and previews manageable.
- [This post from Marco Arment](https://marco.org/2021/06/03/developer-relations) — iOS Dev Weekly · Issue 510 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `4th June 2021`
  **NeKI brief:** Explores This post from Marco Arment, focusing on looking around twitter and the web this week, i see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftPM Library](https://daveverwer.com/blog/launching-the-swiftpm-library) — iOS Dev Weekly · Issue 503 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `16th April 2021`
  **NeKI brief:** Explores SwiftPM Library, focusing on the original idea for building a package search engine popped into my head around two years before the launch of the index. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Dash](https://kapeli.com/dash) — iOS Dev Weekly · Issue 495 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th February 2021`
  **NeKI brief:** Dash is a macOS documentation browser with offline docsets and API search. Use it when evaluating local documentation workflows and the trade-off between bundled references and live web search.
- [Who said we can’t unit test SwiftUI views?](https://nalexn.github.io/swiftui-unit-testing) — iOS Dev Weekly · Issue 492 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines Who said we can't unit test SwiftUI views?, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [snapshot test](https://www.vadimbulavin.com/snapshot-testing-swiftui-views) — iOS Dev Weekly · Issue 492 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Covers snapshot test, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [well documented](https://github.com/nalexn/ViewInspector/blob/master/guide.md) — iOS Dev Weekly · Issue 492 — Source repository · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines well documented, focusing on when i first saw that all swiftui view hierarchy was a function of state stored in structs, i figured it would be ideal…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [GoSwifty](https://github.com/rsrbk/GoSwifty) — iOS Dev Weekly · Issue 479 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines GoSwifty, focusing on are you working on an app that’s transitioning from objective-c to swift? do you know what percentage of your code is in…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [implementation of it](https://github.com/crafterm/swiftui-app-switcher) — iOS Dev Weekly · Issue 474 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `18th September 2020`
  **NeKI brief:** Examines implementation of it, focusing on the ios app switcher is a complex ui control but is all driven from a single drag gesture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [How SwiftUI can now be used to build entire iOS apps](https://wwdcbysundell.com/2020/building-entire-apps-with-swiftui) — iOS Dev Weekly · Issue 462 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines How SwiftUI can now be used to build entire iOS apps, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Double-Edged Sword](https://mohsen.dev/2020/06/21/swiftui-double-edged-sword.html) — iOS Dev Weekly · Issue 462 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines Double-Edged Sword, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Building a view debugger using SceneKit](https://www.youtube.com/watch?v=S6YN2Bsde_Q) — iOS Dev Weekly · Issue 459 — Video · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2020`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
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
- [My experience replacing CocoaPods with SwiftPM](https://www.jessesquires.com/blog/replacing-cocoapods-with-swiftpm) — iOS Dev Weekly · Issue 445 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `28th February 2020`
  **NeKI brief:** Examines My experience replacing CocoaPods with SwiftPM, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Xcode’s Find Navigator & Search Scopes](https://patrickbalestra.com/blog/2020/02/09/xcode-find-navigator.html) — iOS Dev Weekly · Issue 443 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Xcode
  **Published:** `14th February 2020`
  **NeKI brief:** Examines Xcode's Find Navigator & Search Scopes, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [CocoaPods 1.9 Beta](http://blog.cocoapods.org/CocoaPods-1.9.0-beta) — iOS Dev Weekly · Issue 435 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `20th December 2019`
  **NeKI brief:** Examines CocoaPods 1.9 Beta, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftPM Catalog](https://zeezide.com/en/products/swiftpmcatalog) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftPM Catalog, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftUI Architectures: Model-View, Redux & MVVM](https://quickbirdstudios.com/blog/swiftui-architecture-redux-mvvm) — iOS Dev Weekly · Issue 430 — Article · Topics: Architecture · Objective-C & Cocoa · Product Design
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftUI Architectures: Model-View, Redux & MVVM, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftLibrary](https://github.com/kiliankoe/SwiftLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines SwiftLibrary, focusing on first of all, swiftlibrary from kilian koeltzsch – a command-line search tool built on top of the swiftpm library api. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Shape API in SwiftUI](https://mecid.github.io/2019/08/14/building-barchart-with-shape-api-in-swiftui) — iOS Dev Weekly · Issue 417 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `16th August 2019`
  **NeKI brief:** Examines The Shape API in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [this test](https://gist.github.com/mattgallagher/eaa5d3242d83360a52c45c9706479e34) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `28th June 2019`
  **NeKI brief:** Examines this test, focusing on when i saw this tweet i did wonder whether we were going to find that the true cost of a great api was runtime…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Solving ambiguous constraints without rerunning your app](https://mar.codes/2019-05-28/Solving-ambiguous-constraints-without-rerunning-your-app) — iOS Dev Weekly · Issue 406 — Article · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `31st May 2019`
  **NeKI brief:** Covers Solving ambiguous constraints without rerunning your app, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [this project](https://github.com/tarunon/XCTAssertAutolayout) — iOS Dev Weekly · Issue 406 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `31st May 2019`
  **NeKI brief:** Examines this project, focusing on tweak a constraint, build and run, tweak a constraint, build and run, tweak, build, tweak… there must be a better way?…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [In App visual debugger](https://github.com/indragiek/InAppViewDebugger) — iOS Dev Weekly · Issue 402 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `3rd May 2019`
  **NeKI brief:** Examines In App visual debugger, focusing on it’s probably not too much of a hassle to have a mac connected to your app so you can use reveal or the built in xcode…. Use it as a focused research reference for related Apple-platform work, and.
- [Down the rabbit hole of iOS design patterns](https://benoitpasquier.com/down-rabbit-hole-ios-design-patterns) — iOS Dev Weekly · Issue 399 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `12th April 2019`
  **NeKI brief:** Compares common iOS design-pattern trade-offs through concrete examples rather than prescribing one architecture. Use it to frame team discussions about responsibilities, coupling, and test seams in an existing app.
- [Swift by Sundell](https://www.swiftbysundell.com/podcast/45) — iOS Dev Weekly · Issue 399 — Podcast · Topics: Architecture · Developer Community & Business · Swift
  **Published:** `12th April 2019`
  **NeKI brief:** Examines Swift by Sundell, focusing on benoit pasquier talks a lot of sense in this article on app architecture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Designing a Modern Swift Network Stack](http://mikezornek.com/posts/2019/1/designing-a-modern-swift-network-stack-video-and-slides) — iOS Dev Weekly · Issue 387 — Article · Topics: Graphics, Media & Games · Networking · Swift
  **Published:** `18th January 2019`
  **NeKI brief:** Examines Designing a Modern Swift Network Stack, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [snapshot testing library](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 381 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `7th December 2018`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [Finally, a complete course on advanced iOS architecture](http://matteomanferdini.com/ios-architect) — iOS Dev Weekly · Issue 374 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `19th October 2018`
  **NeKI brief:** Walks through Finally, a complete course on advanced iOS architecture with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [Building iOS dependencies with Carthage](https://blog.kulman.sk/building-ios-depedencies-with-carthage) — iOS Dev Weekly · Issue 374 — Article · Topics: Dependency Injection · Objective-C & Cocoa
  **Published:** `19th October 2018`
  **NeKI brief:** Explores Building iOS dependencies with Carthage in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swift in 2018](https://www.jetbrains.com/research/devecosystem-2018/swift-objc) — iOS Dev Weekly · Issue 372 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `5th October 2018`
  **NeKI brief:** Explores Swift in 2018 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Apple](https://search.developer.apple.com/appsearch-validation-tool) — iOS Dev Weekly · Issue 364 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `10th August 2018`
  **NeKI brief:** Explains App Search API Validation Tool with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [git branch and clean/dirty status](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/daveverwer.zsh-theme) — iOS Dev Weekly · Issue 354 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st June 2018`
  **NeKI brief:** Examines git branch and clean/dirty status, focusing on nice tip from marc palmer on including various information in your terminal prompt. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Laws of Core Data](http://davedelong.com/blog/2018/05/09/the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [follow up](http://www.cimgf.com/2018/05/10/response-the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Responds to Core Data design rules with practical clarification about model boundaries, persistence behavior, and application architecture. Use it to compare competing guidance and identify trade-offs, then verify assumptions against current Core Data documentation and project constraints.
- [Swift Static Libraries in CocoaPods 1.5](http://blog.cocoapods.org/CocoaPods-1.5.0) — iOS Dev Weekly · Issue 346 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `6th April 2018`
  **NeKI brief:** Explores Swift Static Libraries in CocoaPods 1.5 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Serialization - Speed and Size](https://holtwick.de/blog/serialization) — iOS Dev Weekly · Issue 339 — Tutorial · Topics: Developer Community & Business · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `16th February 2018`
  **NeKI brief:** Walks through Serialization - Speed and Size with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [Top-down iOS error architecture](https://medium.com/@londeix/top-down-error-architecture-d8715a28d1ad) — iOS Dev Weekly · Issue 338 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `9th February 2018`
  **NeKI brief:** Examines Top-down iOS error architecture, focusing on what’s the best way to handle non-trivial errors in an app? bartosz polaczyk argues that a system that passes the error…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Some useful URL schemes in Xcode 9](https://cocoaengineering.com/2018/01/01/some-useful-url-schemes-in-xcode-9) — iOS Dev Weekly · Issue 336 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `26th January 2018`
  **NeKI brief:** Explores Some useful URL schemes in Xcode 9 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [LSAnimator and CoreAnimator](https://github.com/Lision/LSAnimator) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `5th January 2018`
  **NeKI brief:** Examines LSAnimator and CoreAnimator, focusing on chained animations are annoying to deal with using standard frameworks, and trying to add concurrency on top of this is…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Truth Behind Massive View Controllers](http://aplus.rs/2017/much-ado-about-ios-app-architecture) — iOS Dev Weekly · Issue 326 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th November 2017`
  **NeKI brief:** Explores The Truth Behind Massive View Controllers in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Developing For Apple Watch](http://benjaminmayo.co.uk/developing-for-apple-watch) — iOS Dev Weekly · Issue 324 — Article · Topics: Objective-C & Cocoa
  **Published:** `27th October 2017`
  **NeKI brief:** Explores Developing For Apple Watch in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [A State Container-based iOS Architecture](https://jobandtalent.engineering/ios-architecture-an-state-container-based-approach-4f1a9b00b82e) — iOS Dev Weekly · Issue 323 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `20th October 2017`
  **NeKI brief:** Explores A State Container-based iOS Architecture in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Using SpriteKit to create animations in Swift](https://www.swiftbysundell.com/posts/using-spritekit-to-create-animations-in-swift) — iOS Dev Weekly · Issue 309 — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **Published:** `14th July 2017`
  **NeKI brief:** Explores Using SpriteKit to create animations in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [UIFontMetrics 📐](https://littlebitesofcocoa.com/309-uifontmetrics) — iOS Dev Weekly · Issue 305 — Article · Topics: Accessibility · Objective-C & Cocoa
  **Published:** `16th June 2017`
  **NeKI brief:** Explores UIFontMetrics 📐 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [UIDebuggingInformationOverlay](http://ryanipete.com/blog/ios/swift/objective-c/uidebugginginformationoverlay) — iOS Dev Weekly · Issue 303 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2nd June 2017`
  **NeKI brief:** Explores UIDebuggingInformationOverlay in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [A Simple Undo/Redo Implementation in Swift](http://blog.benjamin-encz.de/post/simple-undo-redo-swift) — iOS Dev Weekly · Issue 301 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `19th May 2017`
  **NeKI brief:** Explores A Simple Undo/Redo Implementation in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Protocols and MVVM in Swift to avoid repetition](https://sudo.isl.co/swift-mvvm-protocols) — iOS Dev Weekly · Issue 300 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `12th May 2017`
  **NeKI brief:** Explores Protocols and MVVM in Swift to avoid repetition in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [LicensePlist](https://github.com/mono0926/LicensePlist) — iOS Dev Weekly · Issue 300 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `12th May 2017`
  **NeKI brief:** Examines LicensePlist, focusing on most of us use open-source libraries, and most oss asks that a license be included in apps that use them. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using protocol compositon for dependency injection](http://merowing.info/2017/04/using-protocol-compositon-for-dependency-injection) — iOS Dev Weekly · Issue 297 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `21st April 2017`
  **NeKI brief:** Explores Using protocol compositon for dependency injection in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [System Level Breakpoints in Swift](http://indiestack.com/2017/03/system-level-breakpoints-in-swift) — iOS Dev Weekly · Issue 293 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `24th March 2017`
  **NeKI brief:** Explores System Level Breakpoints in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Refactor Swift, Objective-C and C++ with AppCode](https://www.jetbrains.com/objc/whatsnew) — iOS Dev Weekly · Issue 288 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `17th February 2017`
  **NeKI brief:** Explores Refactor Swift, Objective-C and C++ with AppCode in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [GlueKit](https://github.com/lorentey/GlueKit) — iOS Dev Weekly · Issue 277 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `18th November 2016`
  **NeKI brief:** Examines GlueKit, focusing on do you miss kvo in swift? well this is going to be worth a look. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [spoke recently about how it works](https://www.youtube.com/watch?v=98jsahDV4ts) — iOS Dev Weekly · Issue 277 — Video · Topics: Objective-C & Cocoa · Swift
  **Published:** `18th November 2016`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [markdown parsers](https://github.com/indragiek/CocoaMarkdown) — iOS Dev Weekly · Issue 275 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Examines markdown parsers, focusing on loïc lecrenier with a new markdown parser, written in pure swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [CocoaPods 1.1](http://blog.cocoapods.org/CocoaPods-1.1.0) — iOS Dev Weekly · Issue 273 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `21st October 2016`
  **NeKI brief:** Explores CocoaPods 1.1 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
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
- [Swift 3 Changes in Beta 6](https://swifting.io/blog/2016/08/17/22-swift-3-access-control-beta-6) — iOS Dev Weekly · Issue 264 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `18th August 2016`
  **NeKI brief:** Explores Swift 3 Changes in Beta 6 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [PMHTTP](https://github.com/postmates/PMHTTP) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `18th August 2016`
  **NeKI brief:** Examines PMHTTP, focusing on kevin ballard with a new networking library written in swift but compatible with objective-c, pmhttp. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [reference implementation](https://github.com/tomkowz/NetworkLayerExample) — iOS Dev Weekly · Issue 263 — Source repository · Topics: Architecture · Core Data · Developer Tools
  **Published:** `11th August 2016`
  **NeKI brief:** Examines reference implementation, focusing on tomasz szulc on building network architecture that isn’t dependent on any third party libraries, or any apple provided…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SiriKit – Can you outsmart provided Intents?](https://swifting.io/blog/2016/07/18/20-sirikit-can-you-outsmart-provided-intents) — iOS Dev Weekly · Issue 260 — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa · Swift
  **Published:** `22nd July 2016`
  **NeKI brief:** Explores SiriKit – Can you outsmart provided Intents? in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [only 11%](https://medium.com/@ryanolsonk/are-the-top-apps-using-swift-42e880e7727f) — iOS Dev Weekly · Issue 259 — Article · Topics: Networking · Objective-C & Cocoa · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Explains Are the Top Apps Using Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Great Swift 3 Rename](https://littlebitesofcocoa.com/243-the-great-swift-3-rename) — iOS Dev Weekly · Issue 257 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `1st July 2016`
  **NeKI brief:** Explores The Great Swift 3 Rename in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Nullable Edge Cases](http://indiestack.com/2016/06/nullable-edge-cases) — iOS Dev Weekly · Issue 254 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `10th June 2016`
  **NeKI brief:** Explores Nullable Edge Cases in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [MarsEdit](https://www.red-sweater.com/marsedit) — iOS Dev Weekly · Issue 254 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `10th June 2016`
  **NeKI brief:** Explores MarsEdit in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Swifty Objective-C](https://pspdfkit.com/blog/2016/swifty-objective-c) — iOS Dev Weekly · Issue 253 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `3rd June 2016`
  **NeKI brief:** Explores Swifty Objective-C in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [relying on those dynamic Objective-C roots](http://furbo.org/2016/05/20/adulterated-swift) — iOS Dev Weekly · Issue 252 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `27th May 2016`
  **NeKI brief:** Explores relying on those dynamic Objective-C roots in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [New Swift, Core Data and Cocoa Books](http://useyourloaf.com/blog/new-swift-core-data-and-cocoa-books) — iOS Dev Weekly · Issue 251 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `20th May 2016`
  **NeKI brief:** Collects book recommendations around Swift, Core Data, and Cocoa as a learning route. Treat editions as historical context and cross-check API guidance against current Apple documentation.
- [Xcode Search: the Hidden Gems](http://holko.pl/2016/04/26/xcode-search) — iOS Dev Weekly · Issue 248 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `29th April 2016`
  **NeKI brief:** Explains Xcode Search the Hidden Gems with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Creating Swift Frameworks for iOS, watchOS, and tvOS](http://basememara.com/creating-cross-platform-swift-frameworks-ios-watchos-tvos-via-carthage-cocoapods) — iOS Dev Weekly · Issue 243 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `25th March 2016`
  **NeKI brief:** Explains Creating Swift Frameworks for iOS watchOS and tvOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Being a Good Low Power Mode Citizen](https://littlebitesofcocoa.com/192-being-a-good-low-power-mode-citizen) — iOS Dev Weekly · Issue 238 — Article · Topics: Objective-C & Cocoa
  **Published:** `19th February 2016`
  **NeKI brief:** Explains Being a Good Low Power Mode Citizen with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Supercharged Search Scopes](http://indiestack.com/2016/02/supercharged-search-scopes) — iOS Dev Weekly · Issue 237 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `12th February 2016`
  **NeKI brief:** Explains Supercharged Search Scopes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CocoaPods plugin and CLI for generating Swift Playgrounds](https://github.com/neonichu/ThisCouldBeUsButYouPlaying) — iOS Dev Weekly · Issue 237 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `12th February 2016`
  **NeKI brief:** Provides the CocoaPods plugin and CLI for generating Swift Playgrounds source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
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
- [Partial functions in Swift, Part 1: Avoidance](http://cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html) — iOS Dev Weekly · Issue 235 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `29th January 2016`
  **NeKI brief:** Explains Partial functions in Swift Part 1 Avoidance with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [PMKVObserver](https://github.com/postmates/PMKVObserver) — iOS Dev Weekly · Issue 231 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `1st January 2016`
  **NeKI brief:** Provides the PMKVObserver source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Flickr’s experience with iOS 9](http://code.flickr.net/2015/11/18/flickrs-experience-with-ios-9) — iOS Dev Weekly · Issue 227 — Article · Topics: App Intents & System Surfaces · Navigation & Deep Linking · Objective-C & Cocoa
  **Published:** `4th December 2015`
  **NeKI brief:** Explains Flickr’s experience with iOS 9 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Jazzy](https://github.com/realm/jazzy) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th November 2015`
  **NeKI brief:** Jazzy generates Apple-style API documentation from Swift and Objective-C source, including symbol graphs, declarations, and Markdown comments. The repository is useful when setting up repeatable documentation generation as part of a library or CI release pipeline.
- [Reachability.swift](https://github.com/ashleymills/Reachability.swift) — iOS Dev Weekly · Issue 222 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Provides the Reachability.swift source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Little Bites of Cocoa](https://littlebitesofcocoa.com/111-reachability-swift) — iOS Dev Weekly · Issue 222 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Explains Little Bites of Cocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Xcode Swift Snippets](https://github.com/Abizern/xcode-snippets) — iOS Dev Weekly · Issue 220 — Source repository · Topics: Core Data · Developer Tools · Xcode
  **Published:** `16th October 2015`
  **NeKI brief:** Provides the Xcode Swift Snippets source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UI for iOS: Filling Gaps in the UIKit Framework](http://www.telerik.com/ios-ui) — iOS Dev Weekly · Issue 219 — Article · Topics: Objective-C & Cocoa · Swift · UIKit
  **Published:** `9th October 2015`
  **NeKI brief:** Explains UI for iOS Filling Gaps in the UIKit Framework with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [XcodeGhost](http://researchcenter.paloaltonetworks.com/2015/09/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store) — iOS Dev Weekly · Issue 217 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** Explains XcodeGhost with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Interested in a tool that converts Objective-C to Swift?](https://www.myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 214 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `4th September 2015`
  **NeKI brief:** Describes a commercial Objective-C-to-Swift conversion service and its claimed migration workflow. Treat it as historical tooling context and evaluate generated-code quality, framework coverage, and licensing before considering automated migration for a production app.
- [Swift Error Handling and Objective-C Interop in Depth](http://blog.benjamin-encz.de/swift-error-handling-and-objective-c-interop-in-depth) — iOS Dev Weekly · Issue 209 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `31st July 2015`
  **NeKI brief:** Explains Swift Error Handling and Objective-C Interop in Depth with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [UI Testing with Xcode 7](https://medium.com/@larcus94/ui-testing-with-xcode-7-221d16bad276) — iOS Dev Weekly · Issue 204 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `26th June 2015`
  **NeKI brief:** Explains UI Testing with Xcode 7 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apple’s Bitcode Telegraphs Future CPU Plans](https://medium.com/@InertialLemon/apple-s-bitcode-telegraphs-future-cpu-plans-a7b90d326228) — iOS Dev Weekly · Issue 203 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `19th June 2015`
  **NeKI brief:** Explains Apple’s Bitcode Telegraphs Future CPU Plans with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [confirmed this week](http://9to5mac.com/2015/05/27/live-blog-apple-senior-vp-of-operations-jeff-williams-interview-at-code-conference) — iOS Dev Weekly · Issue 201 — Article · Topics: Developer Community & Business · Objective-C & Cocoa
  **Published:** `5th June 2015`
  **NeKI brief:** Live coverage of Jeff Williams at the Code Conference, linked in anticipation of the first native Apple Watch SDK preview. It records the launch-period conversation rather than SDK documentation.
- [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) — iOS Dev Weekly · Issue 198 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th May 2015`
  **NeKI brief:** Provides the CleanroomLogger source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Buildasaur](https://github.com/czechboy0/Buildasaur) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Architecture · Developer Tools · Xcode
  **Published:** `8th May 2015`
  **NeKI brief:** Provides the Buildasaur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [A First Look at ReactiveCocoa 3.0](http://blog.scottlogic.com/2015/04/24/first-look-reactive-cocoa-3.html) — iOS Dev Weekly · Issue 195 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `24th April 2015`
  **NeKI brief:** Explains A First Look at ReactiveCocoa 3.0 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Natalie - Storyboard Code Generator](http://blog.krzyzanowskim.com/2015/04/15/natalie-storyboard-code-generator) — iOS Dev Weekly · Issue 194 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `17th April 2015`
  **NeKI brief:** Explains Natalie Storyboard Code Generator with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Why I don’t use PDFs for iOS assets](http://bjango.com/articles/idontusepdfs) — iOS Dev Weekly · Issue 192 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `3rd April 2015`
  **NeKI brief:** Explains Why I don’t use PDFs for iOS assets with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Xcode Compromised](http://furbo.org/2015/03/10/xcode-compromised) — iOS Dev Weekly · Issue 189 — Article · Topics: Objective-C & Cocoa · Security & Privacy · Xcode
  **Published:** `13th March 2015`
  **NeKI brief:** Explains Xcode Compromised with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ReactKit](https://github.com/ReactKit/ReactKit) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa/pull/1382) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactiveCocoa source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Converting Complex Objective-C Macros to Swift Functions](http://www.andrewcbancroft.com/2015/01/29/converting-complex-objective-c-macros-swift-functions) — iOS Dev Weekly · Issue 183 — Article · Topics: Macros & Metaprogramming · Objective-C & Cocoa · Swift
  **Published:** `30th January 2015`
  **NeKI brief:** Explains Converting Complex Objective-C Macros to Swift Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
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
- [Objective-C’s Designated Secret](http://timekl.com/blog/2014/12/09/objective-cs-designated-secret) — iOS Dev Weekly · Issue 176 — Article · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Objective-C’s Designated Secret with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CocoaPods in 2014](http://blog.cocoapods.org/Stats-2014) — iOS Dev Weekly · Issue 174 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th November 2014`
  **NeKI brief:** Explains CocoaPods in 2014 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Developing a Bidding Kiosk for iOS in Swift](http://artsy.github.io/blog/2014/11/13/eidolon-retrospective) — iOS Dev Weekly · Issue 172 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Explains Developing a Bidding Kiosk for iOS in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [app is open source](https://github.com/artsy/eidolon) — iOS Dev Weekly · Issue 172 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Provides the app is open source source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Trials and Tribulations of Writing a 3rd Party iOS Keyboard](http://nuzzel.com/sharedstory/11082014/beta-blog.archagon/the_trials_and_tribulations_of_writing_a_3rd_party_ios_keyboard) — iOS Dev Weekly · Issue 172 — Article · Topics: Hardware & Devices · Objective-C & Cocoa
  **Published:** `14th November 2014`
  **NeKI brief:** Explains The Trials and Tribulations of Writing a 3rd Party iOS Keyboard with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [SuperRecord](https://github.com/michaelarmstrong/SuperRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the SuperRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the MagicalRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Overcast is now accidentally an iPad app, too](http://www.marco.org/2014/09/17/overcast-accidentally-universal) — iOS Dev Weekly · Issue 164 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `19th September 2014`
  **NeKI brief:** Explains Overcast is now accidentally an iPad app too with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [tip for replacing launch images with a storyboard](http://oleb.net/blog/2014/08/replacing-launch-images-with-storyboards) — iOS Dev Weekly · Issue 164 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `19th September 2014`
  **NeKI brief:** Launch screen storyboards replace static image variants with adaptive layout, reducing device-specific assets. The migration must avoid app-like initialization work because the system displays the launch screen before the process is ready.
- [Cocoa without the limitations of C compatibility](https://devforums.apple.com/message/1025388) — iOS Dev Weekly · Issue 160 — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa · Swift
  **Published:** `22nd August 2014`
  **NeKI brief:** Explains Cocoa without the limitations of C compatibility with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [AlamoFire](https://github.com/Alamofire/Alamofire) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Functional Programming · Objective-C & Cocoa
  **Published:** `22nd August 2014`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
- [Coursera iOS Software Engineer - Mountain View, CA](https://www.coursera.org/about/careers/96aecab7-9cb9-424a-b95c-002842a792e8) — iOS Dev Weekly · Issue 156 — Tutorial · Topics: Architecture · Developer Career & Practice · Developer Community & Business
  **Published:** `25th July 2014`
  **NeKI brief:** Explains Coursera iOS Software Engineer Mountain View CA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [The Core Data stack in Swift](http://www.cimgf.com/2014/06/08/the-core-data-stack-in-swift) — iOS Dev Weekly · Issue 152 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `27th June 2014`
  **NeKI brief:** Explains The Core Data stack in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Swift Language Highlights: An Objective-C Developer’s Perspective](http://www.raywenderlich.com/73997/swift-language-highlights) — iOS Dev Weekly · Issue 149 — Tutorial · Topics: Developer Community & Business · Objective-C & Cocoa · Swift
  **Published:** `6th June 2014`
  **NeKI brief:** Explains Swift Language Highlights An Objective-C Developer’s Perspective with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Flight search engine in your app](http://www.travelpayouts.com/promo/aviasales_ios_sdk) — iOS Dev Weekly · Issue 147 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Personal Essays
  **Published:** `23rd May 2014`
  **NeKI brief:** Explains Flight search engine in your app with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [GitHub repository](https://github.com/albertodebortoli/ADBActors) — iOS Dev Weekly · Issue 147 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Provides the GitHub repository source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Benchmarking](http://nshipster.com/benchmarking) — iOS Dev Weekly · Issue 147 — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** A useful benchmark controls compiler mode, inputs, warm-up and repetition before comparing implementations. Use it to answer one performance question at a time, corroborating measurements with profiling when a change affects architecture.
- [GCDWebServer](https://github.com/swisspol/GCDWebServer) — iOS Dev Weekly · Issue 142 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th April 2014`
  **NeKI brief:** Provides the GCDWebServer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [chisel](https://github.com/facebook/chisel) — iOS Dev Weekly · Issue 136 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `7th March 2014`
  **NeKI brief:** Provides the chisel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CocoaPods, or How I Learned to Stop Worrying and Love Objective-C Dependency Management](http://irace.me/cocoapods) — iOS Dev Weekly · Issue 136 — Article · Topics: Developer Career & Practice · Objective-C & Cocoa · Xcode
  **Published:** `7th March 2014`
  **NeKI brief:** Explains CocoaPods or How I Learned to Stop Worrying and Love Objective-C Dependency Management with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this.
- [StoryboardLint](https://github.com/jfahrenkrug/StoryboardLint) — iOS Dev Weekly · Issue 134 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `21st February 2014`
  **NeKI brief:** Provides the StoryboardLint source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Using CocoaPods to Modularize an iOS App](http://dev.hubspot.com/blog/architecting-a-large-ios-app-with-cocoapods) — iOS Dev Weekly · Issue 132 — Article · Topics: Architecture · Objective-C & Cocoa · Xcode
  **Published:** `7th February 2014`
  **NeKI brief:** HubSpot describes splitting a large iOS codebase into CocoaPods modules, making dependency boundaries and incremental ownership explicit. Useful when evaluating modularization costs and build-time trade-offs.
- [Replacing the Objective-C “Delegate Pattern” with ReactiveCocoa](http://spin.atomicobject.com/2014/02/03/objective-c-delegate-pattern) — iOS Dev Weekly · Issue 132 — Article · Topics: Objective-C & Cocoa
  **Published:** `7th February 2014`
  **NeKI brief:** Explains Replacing the Objective-C Delegate Pattern with ReactiveCocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Bolts](https://github.com/BoltsFramework/Bolts-iOS) — iOS Dev Weekly · Issue 131 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `31st January 2014`
  **NeKI brief:** Provides the Bolts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [objc-run](https://github.com/iljaiwas/objc-run) — iOS Dev Weekly · Issue 128 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th January 2014`
  **NeKI brief:** Provides the objc-run source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [APIClient](https://github.com/klaaspieter/APIClient) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Dependency Injection · Developer Tools · Navigation & Deep Linking
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the APIClient source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SDCAlertView](https://github.com/Scott90/SDCAlertView) — iOS Dev Weekly · Issue 122 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `29th November 2013`
  **NeKI brief:** Provides the SDCAlertView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Podlife](http://davander.com/podlife.html) — iOS Dev Weekly · Issue 121 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains Podlife with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSNotificationCenter with blocks considered harmful](http://sealedabstract.com/code/nsnotificationcenter-with-blocks-considered-harmful) — iOS Dev Weekly · Issue 121 — Article · Topics: Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains NSNotificationCenter with blocks considered harmful with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Inkpad](https://github.com/sprang/Inkpad) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides the Inkpad source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
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
- [ReactiveCocoa 2](https://github.com/ReactiveCocoa/ReactiveCocoa/blob/master/CHANGELOG.md) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the ReactiveCocoa 2 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Callbacks as our Generations’ Go To Statement](http://tirania.org/blog/archive/2013/Aug-15.html) — iOS Dev Weekly · Issue 107 — Article · Topics: Concurrency · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th August 2013`
  **NeKI brief:** Explains Callbacks as our Generations’ Go To Statement with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [New thing I do in code](http://cocoa-dom.tumblr.com/post/56517731293/new-thing-i-do-in-code) — iOS Dev Weekly · Issue 105 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Explains New thing I do in code with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [PSD.rb](http://layervault.tumblr.com/post/56891876898/psd-rb) — iOS Dev Weekly · Issue 105 — Article · Topics: Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Explains PSD.rb with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ParcelKit](https://github.com/overcommitted/ParcelKit) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Core Data · Objective-C & Cocoa · Testing
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the ParcelKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Objective-C Generics](https://github.com/tomersh/Objective-C-Generics) — iOS Dev Weekly · Issue 103 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Provides the Objective-C Generics source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Ruby-like nil messaging in Objective-C](http://ddeville.me/2013/06/ruby-like-nil-messaging-in-objective-c) — iOS Dev Weekly · Issue 101 — Article · Topics: Objective-C & Cocoa
  **Published:** `5th July 2013`
  **NeKI brief:** Explains Ruby-like nil messaging in Objective-C with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
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
- [Streamlining Cocoa Development With CocoaPods](http://mobile.tutsplus.com/tutorials/iphone/streamlining-cocoa-development-with-cocoapods) — iOS Dev Weekly · Issue 88 — Tutorial · Topics: Objective-C & Cocoa
  **Published:** `5th April 2013`
  **NeKI brief:** Explains Streamlining Cocoa Development With CocoaPods with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [25 iOS App Performance Tips & Tricks](http://www.raywenderlich.com/31166/25-ios-app-performance-tips-tricks) — iOS Dev Weekly · Issue 88 — Article · Topics: Objective-C & Cocoa · Performance
  **Published:** `5th April 2013`
  **NeKI brief:** Explains 25 iOS App Performance Tips Tricks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ADNKit](https://github.com/joeldev/ADNKit) — iOS Dev Weekly · Issue 86 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `22nd March 2013`
  **NeKI brief:** Provides the ADNKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Querying Objective-C Data Collections](http://www.cimgf.com/2013/02/05/querying-objective-c-data-collections) — iOS Dev Weekly · Issue 80 — Article · Topics: Objective-C & Cocoa
  **Published:** `8th February 2013`
  **NeKI brief:** Explains Querying Objective-C Data Collections with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Objective-C Vitamins](http://ashfurrow.com/blog/objective-c-vitamins) — iOS Dev Weekly · Issue 79 — Article · Topics: Accessibility · Objective-C & Cocoa · Testing
  **Published:** `1st February 2013`
  **NeKI brief:** Explains Objective-C Vitamins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [DLIntrospection](https://github.com/garnett/DLIntrospection) — iOS Dev Weekly · Issue 75 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `4th January 2013`
  **NeKI brief:** Provides the DLIntrospection source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Friday Q&A: Objective-C Pitfalls](http://www.mikeash.com/pyblog/friday-qa-2012-12-14-objective-c-pitfalls.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st December 2012`
  **NeKI brief:** Objective-C pitfalls often arise from dynamic dispatch, nil messaging, ownership conventions, and type erasure interacting unexpectedly. The review is useful for locating boundaries where static Swift assumptions do not apply.
- [THObserversAndBinders](https://github.com/th-in-gs/THObserversAndBinders) — iOS Dev Weekly · Issue 71 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Observation & State Management
  **Published:** `7th December 2012`
  **NeKI brief:** Provides the THObserversAndBinders source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
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
- [Experimentation with build numbering](http://paul-samuels.com/blog/2012/08/25/experimentation-with-build-numbering) — iOS Dev Weekly · Issue 57 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `31st August 2012`
  **NeKI brief:** Explains Experimentation with build numbering with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Avoid security risks with iTunes Connect scraping services](http://www.marco.org/2012/07/31/itc-sales-users) — iOS Dev Weekly · Issue 53 — Article · Topics: Developer Community & Business · Objective-C & Cocoa · Security & Privacy
  **Published:** `3rd August 2012`
  **NeKI brief:** Explains Avoid security risks with iTunes Connect scraping services with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Busted! Eight Reasons not to use ARC](http://www.learn-cocos2d.com/2012/06/mythbusting-8-reasons-arc) — iOS Dev Weekly · Issue 49 — Article · Topics: Objective-C & Cocoa
  **Published:** `6th July 2012`
  **NeKI brief:** Explains Busted Eight Reasons not to use ARC with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
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
- [ReactiveCocoa for a better world](https://github.com/blog/1107-reactivecocoa-for-a-better-world) — iOS Dev Weekly · Issue 41 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th May 2012`
  **NeKI brief:** Provides the ReactiveCocoa for a better world source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Lockbox](https://github.com/granoff/Lockbox) — iOS Dev Weekly · Issue 39 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `27th April 2012`
  **NeKI brief:** Provides the Lockbox source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Tipi: Tiny Templating Engine](https://github.com/hiddenmemory/Tipi) — iOS Dev Weekly · Issue 37 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th April 2012`
  **NeKI brief:** Provides the Tipi Tiny Templating Engine source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Key-Value Observing Done Right: Take 2](http://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — iOS Dev Weekly · Issue 32 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th March 2012`
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NYXImagesKit](https://github.com/Nyx0uf/NYXImagesKit) — iOS Dev Weekly · Issue 31 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd March 2012`
  **NeKI brief:** Provides the NYXImagesKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode and Friends](http://boredzo.org/blog/archives/2012-02-17/xcode-and-friends) — iOS Dev Weekly · Issue 30 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `24th February 2012`
  **NeKI brief:** Explains Xcode and Friends with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [A one finger rotation gesture recognizer](http://blog.mellenthin.de/archives/2012/02/13/an-one-finger-rotation-gesture-recognizer) — iOS Dev Weekly · Issue 29 — Article · Topics: Objective-C & Cocoa
  **Published:** `17th February 2012`
  **NeKI brief:** Explains A one finger rotation gesture recognizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UIAlertView changes in iOS 5](http://useyourloaf.com/blog/2011/12/14/uialertview-changes-in-ios-5.html) — iOS Dev Weekly · Issue 20 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th December 2011`
  **NeKI brief:** Explains UIAlertView changes in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [GMGridView](https://github.com/gmoledina/GMGridView) — iOS Dev Weekly · Issue 18 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd December 2011`
  **NeKI brief:** Provides the GMGridView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [How to import contacts into the iPhone Simulator](http://www.icodeblog.com/2011/11/09/how-to-import-contacts-into-the-iphone-simulator) — iOS Dev Weekly · Issue 16 — Article · Topics: Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `18th November 2011`
  **NeKI brief:** Explains How to import contacts into the iPhone Simulator with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Why you should almost always write a test app for your Radar bug reports](http://boredzo.org/blog/archives/2011-11-09/why-you-should-almost-always-write-a-test-app-for-your-radar-bug-reports) — iOS Dev Weekly · Issue 15 — Article · Topics: Objective-C & Cocoa · Testing
  **Published:** `11th November 2011`
  **NeKI brief:** Explains Why you should almost always write a test app for your Radar bug reports with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because.
- [CodeRunner](http://oleb.net/blog/2011/10/coderunner) — iOS Dev Weekly · Issue 14 — Article · Topics: Objective-C & Cocoa
  **Published:** `4th November 2011`
  **NeKI brief:** Explains CodeRunner with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Using Regular Expressions Part 2 - the Cocoa Connection](http://www.escortmissions.com/blog/2011/10/15/using-regular-expressions-part-2-the-cocoa-connection.html) — iOS Dev Weekly · Issue 12 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st October 2011`
  **NeKI brief:** Explains Using Regular Expressions Part 2 the Cocoa Connection with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Code like you’re Notch](http://www.mrspeaker.net/2011/09/15/code-like-youre-notch) — iOS Dev Weekly · Issue 7 — Article · Topics: Objective-C & Cocoa
  **Published:** `16th September 2011`
  **NeKI brief:** Explains Code like you’re Notch with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS Audio & OpenAL](http://www.youtube.com/watch?v=6QQAzhwalPI) — iOS Dev Weekly · Issue 5 — Video · Topics: Objective-C & Cocoa
  **Published:** `2nd September 2011`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Transient Entities and Core Data](http://www.cimgf.com/2011/08/08/transient-entities-and-core-data) — iOS Dev Weekly · Issue 2 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `12th August 2011`
  **NeKI brief:** Explains Transient Entities and Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [What AI coding costs you](https://tomwojcik.com/posts/2026-02-15/finding-the-right-amount-of-ai) — Not only Swift · Issue 95 — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** Discusses What AI coding costs you in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Writing good agents.md files](https://www.philschmid.de/writing-good-agents) — Not only Swift · Issue 95 — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **NeKI brief:** This article covers writing effective AGENTS.md instruction files. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [PiSwift](https://github.com/xibbon/PiSwift) — Not only Swift · Issue 94 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** This source repository covers the PiSwift project and its Swift integration surface. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Why you should stop stashing and use worktrees](https://www.marcohaber.dev/blog/git-worktrees) — Not only Swift · Issue 89 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **NeKI brief:** Discusses Why you should stop stashing and use worktrees in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Copenhagen Swift & Cocoa Meetup](https://www.meetup.com/copenhagencocoa/events/307836809) — Not only Swift · Issue 81 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents a concrete implementation of Copenhagen Swift & Cocoa Meetup. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swift Error Handling Done Right: Overcoming the Objective-C Error Legacy](https://www.fline.dev/swift-error-handling-done-right-overcoming-the-objective-c-error-legacy) — Not only Swift · Issue 80 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents a concrete implementation of Swift Error Handling Done Right: Overcoming the Objective-C Error Legacy. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Tracing Thoughts in Language Models](https://www.anthropic.com/research/tracing-thoughts-language-model) — Not only Swift · Issue 78 — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** This article covers research methods for tracing language-model internal representations. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
