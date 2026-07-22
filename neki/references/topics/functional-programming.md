# Functional Programming

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Functional abstractions, compositional design, algebraic data types, and function-oriented Swift techniques.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **17**

## Direct-source reading

- [Tour of Sharing: Free for all to watch!](https://www.pointfree.co/blog/posts/163-tour-of-sharing-free-for-all-to-watch) — Point-Free · article catalogue
  **Published:** `2025-01-06T00:00:00Z`
  **NeKI brief:** The Sharing tour demonstrates state propagation and persistence as composable operations instead of view-specific plumbing. It is a useful workflow reference for tracing ownership and testing boundaries in a SwiftUI feature.
- [Open Sourcing isowords](https://www.pointfree.co/blog/posts/55-open-sourcing-isowords) — Point-Free · article catalogue
  **Published:** `2021-03-17T16:00:00Z`
  **NeKI brief:** Explains the open sourcing of isowords and exposes a production game's architecture. Use it as a case study for composable state, effects, and testable game feature design.
- [Announcing: isowords](https://www.pointfree.co/blog/posts/54-announcing-isowords) — Point-Free · article catalogue
  **Published:** `2021-03-17T07:00:00Z`
  **NeKI brief:** isowords demonstrates an application assembled from independently testable features, dependencies, and effects. Its open-source release is valuable for tracing architecture decisions through a nontrivial codebase.
- [Some news about contramap](https://www.pointfree.co/blog/posts/22-some-news-about-contramap) — Point-Free · article catalogue
  **Published:** `2018-10-29T09:00:00Z`
  **NeKI brief:** Contramap adapts a consumer to accept a broader input by transforming it before use, a dual to mapping outputs. The article explains how this functional operation composes formatting and validation behavior.
- [Overture 0.3.0: Now with Zip](https://www.pointfree.co/blog/posts/15-overture-0-3-0-now-with-zip) — Point-Free · article catalogue
  **Published:** `2018-08-17T05:57:04Z`
  **NeKI brief:** Functional zip combines independent computations into one result while preserving each input's structure. The release illustrates how small compositional primitives can remove repetitive coordination code.
- [Solutions to Exercises: Zip Part 3](https://www.pointfree.co/blog/posts/13-solutions-to-exercises-zip-part-3) — Point-Free · article catalogue
  **Published:** `2018-08-16T05:57:03Z`
  **NeKI brief:** Zip exercises demonstrate how combining effects depends on the algebra of the container, not merely tuple construction. The solutions are useful for recognizing when independent operations can be composed safely.
- [Solutions to Exercises: Zip Part 2](https://www.pointfree.co/blog/posts/12-solutions-to-exercises-zip-part-2) — Point-Free · article catalogue
  **Published:** `2018-08-15T05:57:03Z`
  **NeKI brief:** Zip composition combines independent structures positionally, exposing how success and failure behavior depends on the underlying effect. The exercises provide a concrete way to test that intuition.
- [Solutions to Exercises: Zip Part 1](https://www.pointfree.co/blog/posts/11-solutions-to-exercises-zip-part-1) — Point-Free · article catalogue
  **Published:** `2018-08-14T05:57:03Z`
  **NeKI brief:** Zip exercises make positional composition explicit, revealing how independent values and effects combine into one result. The examples help distinguish applicative composition from sequential dependency.
- [Tagged Seconds and Milliseconds](https://www.pointfree.co/blog/posts/6-tagged-seconds-and-milliseconds) — Point-Free · article catalogue
  **Published:** `2018-06-18T14:36:46Z`
  **NeKI brief:** Tagged time units prevent seconds and milliseconds from being mixed even though both are numeric values. The small type wrapper moves a common conversion error from runtime into the compiler.
- [Overture: Now with Functional Setters](https://www.pointfree.co/blog/posts/4-overture-now-with-functional-setters) — Point-Free · article catalogue
  **Published:** `2018-05-15T09:57:03Z`
  **NeKI brief:** Functional setters transform immutable values by returning updated copies, making configuration composable without shared mutation. The pattern clarifies how value semantics can support fluent construction.
- [Solutions to Exercises: Contravariance](https://www.pointfree.co/blog/posts/3-solutions-to-exercises-contravariance) — Point-Free · article catalogue
  **Published:** `2018-05-07T04:01:02Z`
  **NeKI brief:** Contravariance adapts consumers to broader input types by precomposing a transformation. The exercise grounds an abstract variance rule in composable Swift functions and type-safe API design.
- [Announcing Point-Free Pointers!](https://www.pointfree.co/blog/posts/1-announcing-point-free-pointers) — Point-Free · article catalogue
  **Published:** `2018-04-23T04:01:02Z`
  **NeKI brief:** Point-Free Pointers collects focused functional-programming material around small composable ideas. It is discovery context for the linked experiments, not a technical specification itself.

## Newsletter and related leads

- [type-driven design](https://swiftology.io/collections/type-driven-design) — Fatbobman’s Swift Weekly · Issue 118 — Article · Topics: Functional Programming · Swift
  **Published:** `2026-01-12T12:03:07.042Z`
  **NeKI brief:** This Swiftology collection gathers type-driven design material for modeling domain rules with compiler-checked types. Use it to explore stronger invariants and API boundaries, balancing abstraction costs against the application's actual complexity.
- [Free video: Natural Swift](https://gumroad.com/l/natural-swift) — iOS Dev Weekly · Issue 286 — Article · Topics: Functional Programming · Graphics, Media & Games · Swift
  **Published:** `3rd February 2017`
  **NeKI brief:** Examines Free video: Natural Swift, focusing on what makes “swifty” swift? paul hudson from hacking with swift has produced a free video that teaches you how to use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Functional Swift Snippets](http://www.objc.io/snippets) — iOS Dev Weekly · Issue 171 — Article · Topics: Functional Programming · Swift
  **Published:** `7th November 2014`
  **NeKI brief:** Explains Functional Swift Snippets with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Functional Programming in Swift](http://www.objc.io/books) — iOS Dev Weekly · Issue 171 — Article · Topics: Functional Programming · Swift
  **Published:** `7th November 2014`
  **NeKI brief:** Explains Functional Programming in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [AlamoFire](https://github.com/Alamofire/Alamofire) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Functional Programming · Objective-C & Cocoa
  **Published:** `22nd August 2014`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
