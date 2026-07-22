# Nil Coalescing

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://nilcoalescing.com/blog/](https://nilcoalescing.com/blog/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **209**

- [Building adaptive non-modal panels in SwiftUI](https://nilcoalescing.com/blog/BuildingAdaptiveNonModalPanelsInSwiftUI)
  **Published:** `2026-07-20`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI panel that changes from a bottom sheet to an edge-aligned panel using measured scene geometry, custom Layout, preferences, and detents. The drag implementation preserves scrolling by combining gestures deliberately.
- [Geometry, compositing and drawing groups in SwiftUI](https://nilcoalescing.com/blog/GeometryCompositingAndDrawingGroupsInSwiftUI)
  **Published:** `2026-07-17`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Separates geometryGroup, compositingGroup, and drawingGroup by the stage of rendering or animation they affect. The comparison helps diagnose visual artifacts and choose a modifier based on actual compositing needs rather than similar names.
- ["The SwiftUI Way" book update: expanded guidance on data flow and performance](https://nilcoalescing.com/blog/TheSwiftUIWayUpdateJuly2026)
  **Published:** `2026-07-14`
  **Topics:** Performance · Swift · SwiftUI · Xcode
  **NeKI brief:** The SwiftUI Way update records changed patterns and examples as the framework evolves, making it a versioned perspective rather than a normative reference.
- [React to network status updates in SwiftUI](https://nilcoalescing.com/blog/ReactToNetworkStatusUpdatesInSwiftUI)
  **Published:** `2026-07-13`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Adapts NWPathMonitor into an AsyncSequence so SwiftUI state can react to connectivity changes with structured cancellation. Follow it when replacing callback plumbing while preserving lifecycle-safe observation.
- [Using Observation framework outside of SwiftUI](https://nilcoalescing.com/blog/ObservationFrameworkOutsideOfSwiftUI)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses withObservationTracking to observe selected properties of an @Observable class without requiring a SwiftUI view. It demonstrates a focused bridge for model, service, or test code that needs change notifications without broad invalidation.
- [Using @Observable in SwiftUI views](https://nilcoalescing.com/blog/ObservableInSwiftUI)
  **Published:** `2026-07-13`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Introduces @Observable and explains its property-level tracking difference from ObservableObject. The examples show why migration can reduce needless view updates while still requiring deliberate ownership of observable instances.
- [Lazy vars in @Observable classes in Swift](https://nilcoalescing.com/blog/LazyVarsInObservableClasses)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift
  **NeKI brief:** Shows why lazy properties in @Observable types need @ObservationIgnored and where observation would otherwise treat initialization as a tracked mutation. It is a targeted fix for compiler or runtime behavior during Observation migration.
- [Initializing @Observable classes within the SwiftUI hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Initializing @Observable classes with the @State macro in Xcode 27](https://nilcoalescing.com/blog/InitializingObservableClassesWithTheStateMacroInXcode27)
  **Published:** `2026-07-13`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI · Xcode
  **NeKI brief:** Explains initializing an @Observable reference type through @State in current SwiftUI. Use it when a view owns an observable model and must preserve its identity across body recalculation rather than recreating it inline.
- [Equatable properties in @Observable classes](https://nilcoalescing.com/blog/EquatablePropertiesInObservableClasses)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains using equatable properties to limit Observation invalidation in reference types. Useful when expensive SwiftUI views depend on models whose unrelated mutations should not trigger recomputation.
- [Custom bindings in SwiftUI: closures vs subscripts](https://nilcoalescing.com/blog/CustomBindingsInSwiftUIClosuresVsSubscripts)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Compares closure-based and subscript-based custom Bindings in SwiftUI, including how each expresses read and write access. Use it when designing reusable bindings and choosing an approach that keeps transformations clear, composable, and maintainable.
- [Automatic property observation in UIKit with @Observable](https://nilcoalescing.com/blog/AutomaticPropertyObservationInUIKitWithObservable)
  **Published:** `2026-07-13`
  **Topics:** Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Shows applying @Observable-style automatic property tracking outside SwiftUI, including UIKit. Use it when an imperative UI needs targeted change observation without manually maintaining a broad notification mechanism.
- [Create an AsyncStream from withObservationTracking() function](https://nilcoalescing.com/blog/AsyncStreamFromWithObservationTrackingFunc)
  **Published:** `2026-07-13`
  **Topics:** Concurrency
  **NeKI brief:** Builds an AsyncStream from withObservationTracking to bridge observation changes into async sequences. Follow it when an async consumer needs cancellation-aware updates from an observation-based model.
- [The hidden cost of unstable SwiftUI environment defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI)
  **Published:** `2026-07-10`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.
- [AsyncImage improvements in iOS 27](https://nilcoalescing.com/blog/AsyncImageImprovementsInSwiftUIOnIOS27)
  **Published:** `2026-06-22`
  **Topics:** Concurrency · Networking · Swift · SwiftUI
  **NeKI brief:** Covers iOS 27 AsyncImage improvements for loading behavior and presentation. Useful when replacing custom image loaders, while checking cache, cancellation, and failure semantics against the deployment target.
- [New SwiftUI APIs for reordering and drag and drop on iOS 27](https://nilcoalescing.com/blog/NewSwiftUIAPIsForReorderingAndDragAndDropOniOS27)
  **Published:** `2026-06-18`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explores iOS 27 reorder and drag-container APIs for SwiftUI collections. Useful for implementing movable content with explicit drop configuration instead of manually translating gesture coordinates.
- [Navigation transition updates in SwiftUI on iOS 27](https://nilcoalescing.com/blog/SwiftUINavigationTransitionUpdatesIniOS27)
  **Published:** `2026-06-15`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Covers iOS 27 navigation transition updates and how destination transitions participate in the navigation stack. Useful when aligning custom transitions with system navigation state.
- [Custom scroll layouts with swipe actions in SwiftUI on iOS 27](https://nilcoalescing.com/blog/CustomScrollLayoutsWithSwipeActionsInSwiftUIOnIOS27)
  **Published:** `2026-06-11`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows custom scroll layouts combined with swipe actions in SwiftUI on iOS 27. Use it when list-like interactions need nonstandard geometry without giving up contextual swipe affordances.
- [SwiftUI Environment](https://nilcoalescing.com/blog/SwiftUIEnvironment)
  **Published:** `2026-06-10`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains environment propagation and dependency lookup in SwiftUI. Useful for deciding which shared values belong in environment keys versus explicit view inputs.
- [Scheduling and handling background app refresh in SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI)
  **Published:** `2026-06-10`
  **Topics:** Swift · SwiftUI · Testing · Xcode
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).
- [iOS app setup for remote push notifications](https://nilcoalescing.com/blog/RemotePushSetup)
  **Published:** `2026-06-10`
  **Topics:** Testing · Xcode
  **NeKI brief:** Walks through remote push notification setup, entitlements, payload handling, and testing. Useful for diagnosing why a correctly signed app still fails to receive or process pushes.
- [Modern SwiftUI APIs for programmatic scrolling](https://nilcoalescing.com/blog/ModernSwiftUIAPIsForProgrammaticScrolling)
  **Published:** `2026-06-10`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses modern SwiftUI scrolling APIs to observe visible items, target positions, and programmatic movement. Useful for replacing preference-key workarounds with typed scroll coordination.
- [Designing a custom lazy list in SwiftUI with better performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI)
  **Published:** `2026-06-10`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [Schedule a countdown timer with AlarmKit](https://nilcoalescing.com/blog/CountdownTimerWithAlarmKit)
  **Published:** `2026-06-10`
  **Topics:** Apple Platform Ecosystem
  **NeKI brief:** Schedules a countdown through AlarmKit rather than a foreground-only timer. Use it when an app needs a system-managed alert that survives normal lifecycle interruptions.
- [Corner concentricity in SwiftUI on iOS 26](https://nilcoalescing.com/blog/ConcentricRectangleInSwiftUI)
  **Published:** `2026-06-10`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Introduces ConcentricRectangle for corners that follow the system's concentric geometry. Useful for iOS 26 surfaces that need nested cards and containers to align with platform visual language.
- [Codable conformance for Swift enums](https://nilcoalescing.com/blog/CodableConformanceForSwiftEnums)
  **Published:** `2026-06-10`
  **Topics:** Swift
  **NeKI brief:** Explains synthesized and custom Codable conformance for Swift enums, including manual implementations for complex cases. Use it when serialized representations need compatibility beyond automatic coding keys.
- [Wrapping text within another view in SwiftUI](https://nilcoalescing.com/blog/WrappingTextWithinAnotherViewInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows how to make a custom container report text's intrinsic size and wrapping correctly. Useful when composed text gets clipped because a wrapper consumes the wrong proposed width.
- [Using enumerated() with SwiftUI List and ForEach to show item numbers](https://nilcoalescing.com/blog/UsingEnumeratedWithListAndForEach)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains that Swift 6.2 and iOS 26 let EnumeratedSequence conform to RandomAccessCollection, enabling direct use of enumerated() in List and ForEach. Useful for displaying item numbers while preserving SwiftUI collection identity and efficient iteration.
- [Use onChange() modifier with computed properties](https://nilcoalescing.com/blog/UseOnChangeModifierWithComputedProperties)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** onChange can observe any Equatable computed value, so one derived property can coordinate reactions to several inputs. This avoids duplicated modifiers and gives a single change boundary for coupled state such as alarm date and activation.
- [Text modifiers in SwiftUI](https://nilcoalescing.com/blog/TextModifiersInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains composing text modifiers in SwiftUI and how modifier order affects rendered output. Use it when styling, accessibility, and localization concerns interact in a Text view and visual results seem surprising.
- [Text concatenation vs Text interpolation in SwiftUI](https://nilcoalescing.com/blog/TextConcatenationVsTextInterpolationInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Contrasts concatenating Text views with interpolating values into localized strings. Useful for preserving localization and formatting semantics when constructing styled SwiftUI copy.
- [String interpolation in LocalizedStringKey](https://nilcoalescing.com/blog/StringInterpolationInLocalizedStringKey)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** LocalizedStringKey string interpolation captures values for localization rather than behaving like ordinary String formatting. The article clarifies which interpolated types receive localized styling and where explicit interpolation is safer.
- [State restoration for DisclosureGroup expansion in List rows](https://nilcoalescing.com/blog/StateRestorationForDisclosureGroupExpansionInListRows)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SceneStorage restores DisclosureGroup expansion by persisting an explicit collection of identifiers rather than the transient row views. The pattern highlights how to serialize nested row state while keeping List data source identity stable.
- [Set a shape as background in SwiftUI](https://nilcoalescing.com/blog/SetAShapeAsBackgroundInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A Shape can be used as a SwiftUI background while preserving the view's proposed size and clipping behavior. This avoids overlay geometry hacks when adding custom fills, borders, or adaptive background decoration.
- [Resizing SF Symbols in SwiftUI](https://nilcoalescing.com/blog/ResizingSFSymbolsInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SF Symbols should be resized with font semantics, not resizable(), because resizable raster treatment loses symbol metrics and text alignment behavior. The small distinction prevents baseline and layout regressions in labels and toolbars.
- [Mesh gradients in SwiftUI](https://nilcoalescing.com/blog/MeshGradientsInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds mesh gradients in SwiftUI by defining a grid of interpolated colors and positions. Useful for expressive backgrounds while understanding rendering cost and the need for platform availability checks.
- [Hierarchical background styles in SwiftUI](https://nilcoalescing.com/blog/HierarchicalBackgroundStyles)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains hierarchical background styles and how they derive contrast from surrounding system materials. Useful for adaptive surfaces that should remain legible across appearances without custom color branches.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.
- [Get tap location in SwiftUI](https://nilcoalescing.com/blog/GetTapLocationInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The iOS 16 onTapGesture overload supplies a CGPoint in a requested local or global coordinate space. Using that event directly avoids a GeometryReader or UIKit bridge when hit-testing custom drawing and gesture-driven controls.
- [Formatting data inside SwiftUI Text views](https://nilcoalescing.com/blog/FormattingDataInsideSwiftUITextViews)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Formats inline values inside SwiftUI Text using interpolation and format styles. Useful for localized dates, measurements, and numbers where presentation should follow locale rather than manual string assembly.
- [Interpolate text with custom foreground style in SwiftUI](https://nilcoalescing.com/blog/ForegroundStyleInsideTextInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows styling interpolated Text ranges with foregroundStyle in SwiftUI, enabling richer inline formatting from iOS 17. Useful for badges, emphasized fragments, and semantic text that needs multiple styles without overlaying separate labels.
- [Ways to customize text color in SwiftUI](https://nilcoalescing.com/blog/ForegroundColorStyleAndTintInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI's `foregroundStyle`, `foregroundColor`, `tint`, AttributedString attributes, and text-rendering options. Use it when choosing between semantic hierarchy, control accenting, gradients, and advanced per-run text styling.
- [Font modifiers in SwiftUI](https://nilcoalescing.com/blog/FontModifiersInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows how custom font modifiers can centralize typography while preserving Dynamic Type and environment behavior. Useful for design-system APIs that should express semantic text roles rather than repeat font construction.
- [Encode and decode SwiftUI color](https://nilcoalescing.com/blog/EncodeAndDecodeSwiftUIColor)
  **Published:** `2026-06-09`
  **Topics:** Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Encodes and decodes SwiftUI Color values. Use it when persisting user-selected colors while accounting for color-space and dynamic-system-color limitations.
- [Dynamic dates with monospaced digits in SwiftUI](https://nilcoalescing.com/blog/DynamicDatesWithMonospacedDigits)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses monospaced digits for dynamic dates in SwiftUI. Use it when changing time text should not cause distracting width shifts or layout jitter.
- [Customizing the appearance of symbol images in SwiftUI](https://nilcoalescing.com/blog/CustomizingTheAppearanceOfSymbolImagesInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates SwiftUI symbol rendering modes, palettes, and hierarchical styles. Useful for making SF Symbols communicate emphasis and state without exporting separate tinted assets.
- [SwiftUI matched geometry effect in a custom segmented control](https://nilcoalescing.com/blog/CustomSegmentedControlWithMatchedGeometryEffect)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a segmented control with matchedGeometryEffect so the selection indicator moves between segments. Useful for coordinated SwiftUI transitions while keeping selection state separate from animation identity.
- [Defining custom scenes in SwiftUI](https://nilcoalescing.com/blog/CustomScenesInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** Custom Scene definitions let a SwiftUI app declare window, menu, or document behavior as composable scene values. Follow it to understand lifecycle boundaries that are easy to obscure when everything is placed in App.body.
- [Custom environment values in SwiftUI](https://nilcoalescing.com/blog/CustomEnvironmentValuesInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Macros & Metaprogramming · Swift · SwiftUI · Xcode
  **NeKI brief:** Compares the pre-Xcode 16 pattern for defining SwiftUI environment keys with the @Entry macro, then shows how values flow through a view hierarchy.
- [Area chart with a dimming layer up to the current point in time](https://nilcoalescing.com/blog/AreaChartWithADimmingLayer)
  **Published:** `2026-06-09`
  **Topics:** Swift
  **NeKI brief:** An area chart can dim historical data by layering a shape up to the current time coordinate, combining chart geometry with ordinary SwiftUI drawing. The technique is useful for temporal dashboards that need a clear present-versus-past distinction.
- [Animate Text style changes in SwiftUI](https://nilcoalescing.com/blog/AnimateTextStyleChangesInSwiftUI)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Animating Text style changes depends on SwiftUI recognizing text identity and interpolatable attributes, not merely wrapping the view in animation. The example helps diagnose why font or foreground transitions snap unexpectedly.
- [Adjust the intensity of colors in SwiftUI views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews)
  **Published:** `2026-06-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [Adaptive layouts with ViewThatFits](https://nilcoalescing.com/blog/AdaptiveLayoutsWithViewThatFits)
  **Published:** `2026-06-09`
  **Topics:** SwiftUI
  **NeKI brief:** ViewThatFits tries alternatives against the proposed size and keeps the first layout that fits, making responsive composition declarative. It is useful when breakpoint logic would otherwise duplicate content or rely on device-specific widths.
- [Styling measurement unit fonts in SwiftUI](https://nilcoalescing.com/blog/StylingMeasurementUnitFontsInSwiftUI)
  **Published:** `2026-06-07`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows styling measurement-unit fonts in SwiftUI so values and units retain intentional hierarchy. Follow it when displaying measurements, percentages, or localized quantities where typography should distinguish numeric content from its unit.
- [Isolate SwiftUI animations to specific attributes](https://nilcoalescing.com/blog/IsolateSwiftUIAnimationsToSpecificAttributes)
  **Published:** `2026-06-04`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows how to scope SwiftUI animation to selected attributes rather than every state change in a view update. Use it when unrelated layout or content changes animate accidentally and make interaction feel unstable.
- [SwiftUI animation timing](https://nilcoalescing.com/blog/AnimationTimingInSwiftUI)
  **Published:** `2026-06-04`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Breaks down SwiftUI animation timing and how duration, delay, and timing curves shape transitions. Use it when a visual effect feels out of sync and the fix requires separating state change from animation parameters.
- [Clearing UserDefaults during macOS app development](https://nilcoalescing.com/blog/ClearingUserDefaultsDuringmacOSAppDevelopment)
  **Published:** `2026-06-02`
  **Topics:** Persistence & Synchronisation · Testing
  **NeKI brief:** Shows targeted UserDefaults cleanup during macOS development. Use it to reset persisted test state without deleting unrelated preferences, especially when a menu-bar or sandboxed app retains configuration between launches.
- [Refreshing and animating views using TimelineView in SwiftUI](https://nilcoalescing.com/blog/TimelineViewInSwiftUI)
  **Published:** `2026-05-25`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses TimelineView to refresh SwiftUI content on a schedule without manually managing a timer. Follow it for clocks, elapsed-time displays, and periodic UI updates where lifecycle and cadence should remain declarative.
- [Overview of resizable sheet APIs in SwiftUI](https://nilcoalescing.com/blog/ResizableSheetInSwiftUI)
  **Published:** `2026-05-24`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Resizable sheet APIs combine detents, selection, and presentation state to let users change modal height. The examples clarify how detent identity and bindings interact when restoring or programmatically changing a sheet size.
- [Create immersive backgrounds in SwiftUI with backgroundExtensionEffect()](https://nilcoalescing.com/blog/BackgroundExtensionEffectInSwiftUI)
  **Published:** `2026-05-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's backgroundExtensionEffect for extending a visual background beyond a view's ordinary bounds. Use it when designing immersive layered interfaces and needing a deliberate alternative to ad-hoc safe-area or blur tricks.
- [Scenes types in a SwiftUI Mac app](https://nilcoalescing.com/blog/ScenesTypesInASwiftUIMacApp)
  **Published:** `2026-05-12`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI scene types for macOS applications, including windows, menus, and settings. Useful for choosing lifecycle and presentation boundaries before adding imperative AppKit plumbing.
- [Show a popover on iPhone in SwiftUI](https://nilcoalescing.com/blog/PopoverOniPhoneInSwiftUI)
  **Published:** `2026-05-12`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows iPhone popover presentation and adaptation behavior in SwiftUI. Useful for lightweight contextual actions that should not become a full navigation destination or sheet.
- [Customizing macOS window background in SwiftUI](https://nilcoalescing.com/blog/CustomizingMacOSWindowBackgroundInSwiftUI)
  **Published:** `2026-05-12`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows how to customize a macOS SwiftUI window background while respecting the hosting window boundary. Useful for translucent or branded surfaces that cannot be achieved with view modifiers alone.
- [A guide to macOS window toolbar styles in SwiftUI](https://nilcoalescing.com/blog/AGuideToMacOSToolbarStylesInSwiftUI)
  **Published:** `2026-05-12`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares macOS SwiftUI toolbar styles and their visual roles. Use it when a window's title area, navigation controls, and command density should align with the platform instead of inheriting an accidental default appearance.
- [Overview of the onChange() modifier in SwiftUI](https://nilcoalescing.com/blog/OverviewOfonChangeInSwiftUI)
  **Published:** `2026-04-28`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** The onChange modifier observes Equatable values after SwiftUI updates, with overload differences affecting old and new value access. This overview is useful for choosing the right observation boundary and avoiding feedback loops.
- [Embedding SF Symbols in SwiftUI Text](https://nilcoalescing.com/blog/EmbeddingSFSymbolsInSwiftUIText)
  **Published:** `2026-04-06`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows embedding SF Symbols inline with SwiftUI Text so symbol and typography layout together. Use it when labels need dynamic-type-aware iconography without separate HStack alignment and baseline adjustments.
- [AttributedString attribute scopes](https://nilcoalescing.com/blog/AttributedStringAttributeScopes)
  **Published:** `2026-04-06`
  **Topics:** Accessibility · Swift · SwiftUI · UIKit
  **NeKI brief:** AttributedString attribute scopes constrain which custom and Foundation attributes are available through typed lookup. The article helps design safe rich-text transformations without stringly-typed keys or accidental scope collisions.
- [SwiftUI Search Enhancements in iOS and iPadOS 26](https://nilcoalescing.com/blog/SwiftUISearchEnhancementsIniOSAndiPadOS26)
  **Published:** `2026-04-01`
  **Topics:** Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Shows iOS and iPadOS 26 SwiftUI search enhancements for placement, suggestions, and presentation. Useful for modernizing search flows without rebuilding the search field and toolbar integration.
- [ScrollView snapping in SwiftUI](https://nilcoalescing.com/blog/ScrollViewSnappingInSwiftUI)
  **Published:** `2026-04-01`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Configures SwiftUI scroll target behavior and snapping so items settle at deliberate positions. Useful for carousels and paged content without implementing custom drag-end calculations.
- [Presenting Liquid Glass sheets in SwiftUI on iOS 26](https://nilcoalescing.com/blog/PresentingLiquidGlassSheetsInSwiftUI)
  **Published:** `2026-04-01`
  **Topics:** Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates presenting sheets that participate in iOS 26 Liquid Glass styling and detents. Useful for adopting system material behavior while keeping modal content and dismissal state explicit.
- [SwiftUI Liquid Glass sheets with NavigationStack and Form](https://nilcoalescing.com/blog/LiquidGlassSheetsWithNavigationStackAndForm)
  **Published:** `2026-04-01`
  **Topics:** Liquid Glass · Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Explains composing Liquid Glass sheets with NavigationStack and Form, including presentation structure and styling boundaries. Follow it when migrating modal editing flows to iOS 26 while keeping navigation titles, controls, and form content legible.
- [Build a macOS menu bar utility in SwiftUI](https://nilcoalescing.com/blog/BuildAMacOSMenuBarUtilityInSwiftUI)
  **Published:** `2026-04-01`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Walks through a SwiftUI macOS menu-bar utility, including scene configuration and status-item presentation. Useful for small persistent tools that should avoid a conventional document window.
- [Animating SF Symbols in SwiftUI](https://nilcoalescing.com/blog/AnimatingSFSymbolsInSwiftUI)
  **Published:** `2026-04-01`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI symbol effects and configuration to animate SF Symbols in response to state changes. Useful for lightweight feedback that remains tied to semantic icon transitions rather than custom image sequences.
- [Add a Close button to SwiftUI modals on iOS 26](https://nilcoalescing.com/blog/AddACloseButtonToSwiftUIModalsOnIOS26)
  **Published:** `2026-04-01`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates the iOS 26 modal close-button API and its placement rules. Useful for adopting system-consistent dismissal affordances without building a custom toolbar button for every sheet.
- [Adjusting line height in SwiftUI on iOS 26](https://nilcoalescing.com/blog/AdjustingLineHeightInSwiftUIOniOS26)
  **Published:** `2026-03-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows the iOS 26 SwiftUI line-height controls for tuning text leading while preserving Dynamic Type behavior. Useful when typography needs precise rhythm without hard-coded UIKit paragraph styles.
- [Access application files on iOS simulator](https://nilcoalescing.com/blog/AccessApplicationFilesOniOSSimulator)
  **Published:** `2026-03-04`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Simulator application data can be located and inspected through the platform's container layout, which is invaluable for checking persistence and exported files. The workflow distinguishes app containers from shared and system data.
- [Defining custom string interpolation behavior in Swift](https://nilcoalescing.com/blog/DefiningCustomStringInterpolationBehaviorInSwift)
  **Published:** `2026-01-13`
  **Topics:** Swift
  **NeKI brief:** Shows extending Swift string interpolation so domain types can control formatting directly inside literals. Use it when designing readable, type-directed output while keeping conversion logic centralized instead of scattering formatter calls through UI code.
- [Add an inner shadow to a symbol image in SwiftUI](https://nilcoalescing.com/blog/AddAnInnerShadowToASymbolImageInSwiftUI)
  **Published:** `2025-12-09`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Creates an inner-shadow effect for SF Symbols in SwiftUI through masking and compositing. Use it when symbol depth needs a controlled visual treatment without replacing scalable system glyphs with raster assets.
- [Introducing Breve: an arty coffee app built for iOS 26](https://nilcoalescing.com/blog/IntroducingBreve)
  **Published:** `2025-10-29`
  **Topics:** Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Breve combines Liquid Glass sheets, a background extension effect, stretchy header, search, and AlarmKit in one SwiftUI app. Keeping those system integrations separate from presentation state helps feature-rich screens retain clear lifecycle and interaction boundaries.
- ["SwiftUI Fundamentals" book update: refreshed for iOS 26 and the Liquid Glass design](https://nilcoalescing.com/blog/SwiftUIFundamentalsUpdateOctober2025)
  **Published:** `2025-10-20`
  **Topics:** Liquid Glass · Swift · SwiftUI
  **NeKI brief:** The fundamentals update refreshes SwiftUI state and layout examples for newer SDKs, useful for routing but still subject to current Apple API verification.
- [Show icons only in SwiftUI swipe actions on iOS 26](https://nilcoalescing.com/blog/ShowIconsOnlyInSwiftUISwipeActionsOnIOS26)
  **Published:** `2025-10-15`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows how iOS 26 SwiftUI swipe actions can present icons without visible button titles. Use it to create compact row actions while checking discoverability, accessibility labels, destructive styling, and whether the reduced affordance remains understandable.
- [Automatically generated List edit operations](https://nilcoalescing.com/blog/AutomaticallyGeneratedListEditOperations)
  **Published:** `2025-10-15`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI can derive List delete and move operations from collection identity, reducing manual index bookkeeping. The pattern still depends on stable IDs and correctly scoped mutations, making it useful for diagnosing reorder bugs.
- [Avoiding text truncation in SwiftUI with Dynamic Type](https://nilcoalescing.com/blog/AvoidingTextTruncationInSwiftUI)
  **Published:** `2025-10-06`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates detecting and preventing SwiftUI text truncation through layout and typography choices. Useful for resilient localized interfaces where fixed line counts or widths are unsafe.
- [Core Spotlight integration for Spotlight and internal app search](https://nilcoalescing.com/blog/CoreSpotlightIntegration)
  **Published:** `2025-08-11`
  **Topics:** App Intents & System Surfaces
  **NeKI brief:** Shows using a shared Core Spotlight index to expose app content to system Spotlight and internal search. Useful for designing one indexing pipeline with searchable attributes, stable identifiers, updates, and deletion handling across both search surfaces.
- [Iterate over items and indices in Swift collections](https://nilcoalescing.com/blog/IterateOverItemsAndIndicesInSwiftCollections)
  **Published:** `2025-06-24`
  **Topics:** Swift
  **NeKI brief:** Swift collection iteration can expose an element and its index together without manually zipping or maintaining counters. The examples preserve collection semantics while avoiding index invalidation pitfalls during read-only transformations.
- [Stretchy header in SwiftUI with visualEffect()](https://nilcoalescing.com/blog/StretchyHeaderInSwiftUI)
  **Published:** `2025-06-16`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a stretchy scrolling header with GeometryReader and visual effects tied to scroll offset. Useful for immersive detail screens while keeping the effect isolated from content layout.
- [Enable scrolling based on content size in SwiftUI](https://nilcoalescing.com/blog/EnableScrollingBasedOnContentSizeInSwiftUI)
  **Published:** `2025-05-26`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses measured content and container dimensions to enable scrolling only when content exceeds available space. Useful for avoiding awkward always-scrollable screens in adaptive SwiftUI layouts.
- [Delay an async Task in Swift using the new clock APIs](https://nilcoalescing.com/blog/DelayAnAsyncTaskInSwift)
  **Published:** `2025-05-10`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Swift 5.7 clock, instant, and duration APIs express an async delay without nanosecond arithmetic and can include tolerance. The example is a useful migration reference for readable, testable timing and cancellation-aware Task scheduling.
- [Re-indent selected code in Xcode](https://nilcoalescing.com/blog/ReindentSelectedCodeInXcode)
  **Published:** `2025-05-02`
  **Topics:** Xcode
  **NeKI brief:** Xcode's editor command re-indents only the selected code, applying the current language and indentation rules without formatting unrelated lines. It is a small but practical workflow for repairing generated or conflict-resolved source safely.
- [Noncopyable types in Swift](https://nilcoalescing.com/blog/NoncopyableTypesInSwift)
  **Published:** `2025-05-02`
  **Topics:** Swift
  **NeKI brief:** Explains noncopyable Swift types and ownership restrictions. Use it when a resource must have unique lifetime semantics and accidental copying would be invalid or expensive.
- [Format long parameter lists into separate lines in Xcode](https://nilcoalescing.com/blog/FormatLongParameterListsIntoSeparateLinesInXcode)
  **Published:** `2025-05-02`
  **Topics:** Xcode
  **NeKI brief:** Shows Xcode formatting support for breaking long parameter lists into readable lines. Useful for keeping generated or refactored Swift declarations reviewable without manual whitespace churn.
- [Embedding a custom font into a macOS app bundle](https://nilcoalescing.com/blog/EmbeddingACustomFontIntoAMacOSAppBundle)
  **Published:** `2025-04-30`
  **Topics:** Xcode
  **NeKI brief:** Embedding a custom font requires bundling the resource and registering it with the app process before use. The macOS workflow is useful for diagnosing fonts that work in development but disappear in packaged builds.
- [Programmatically open a new window in SwiftUI on macOS](https://nilcoalescing.com/blog/ProgrammaticallyOpenANewWindowInSwiftUIOnMacOS)
  **Published:** `2025-04-23`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's openWindow action targets a scene by identifier, separating a request to create or focus a window from view construction. Follow it when implementing macOS multi-window flows without manually managing NSWindow instances.
- [Create a fully custom About window for a Mac app in SwiftUI](https://nilcoalescing.com/blog/FullyCustomAboutWindowForAMacAppInSwiftUI)
  **Published:** `2025-04-23`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A custom About window uses a dedicated scene and platform window styling while keeping content in SwiftUI. The pattern shows where app metadata, sizing, and lifecycle belong when replacing the default macOS About panel.
- [Customize ShareLink appearance in SwiftUI with view modifiers](https://nilcoalescing.com/blog/CustomizeShareLinkAppearance)
  **Published:** `2025-04-18`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates customizing ShareLink appearance while preserving the system sharing action. Follow it when adapting labels, icons, or styling without reimplementing share-sheet presentation and its platform behavior.
- [Keyboard driven navigation with focusable() on iPad in SwiftUI](https://nilcoalescing.com/blog/KeyboardNavigationWithFocusable)
  **Published:** `2025-04-16`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Adding focusable() makes otherwise non-focusable SwiftUI views participate in iPad keyboard navigation introduced with iPadOS 17. The pattern is useful for auditing focus order and separating visual composition from hardware-input affordances.
- [Automatic image accessibility labels from localized strings in SwiftUI](https://nilcoalescing.com/blog/ImageAccessibilityLabelsFromLocalizableStringsFiles)
  **Published:** `2025-04-16`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's localized image-label lookup, where a matching localization key can supply an accessibility label without repeating modifier text. It also highlights the naming dependency to verify when localization changes.
- [if/else statements as expressions in Swift](https://nilcoalescing.com/blog/IfElseExpressionsInSwift)
  **Published:** `2025-04-16`
  **Topics:** Swift
  **NeKI brief:** Swift if/else expressions return a value, allowing conditional initialization without temporary mutable variables. The article highlights type inference and branch exhaustiveness so the syntax improves clarity rather than hiding divergent side effects.
- [User-level string search in Swift](https://nilcoalescing.com/blog/UserLevelStringSearchInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** User-level string search accounts for locale and linguistic equivalence instead of comparing Unicode scalars literally. The Foundation APIs are useful for matching names or text where case, diacritics, and user language should not cause false negatives.
- [User-friendly descriptions and recovery suggestions for custom errors in Swift](https://nilcoalescing.com/blog/UserFriendlyDescriptionsAndRecoverySuggestionsForCustomErrorsInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Custom errors can expose localized descriptions and recovery suggestions through Foundation protocols, separating machine-readable failure identity from user-facing remediation. Follow it when error handling needs actionable UI without stringly typed branching.
- [Use cases for self, Self and Self.self in Swift](https://nilcoalescing.com/blog/UseCasesForSelfInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Self, self, and Self.self refer to different type, instance, and metatype contexts in Swift. The examples are useful for diagnosing generic factory code and avoiding accidental dynamic dispatch or instance capture.
- [Trigger property observers from initializers in Swift](https://nilcoalescing.com/blog/TriggerPropertyObserversFromInitializersInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Property observers normally do not run during initialization, so triggering equivalent logic requires an explicit post-init assignment or helper. The distinction prevents initialization code from relying on callbacks that Swift intentionally suppresses.
- [Sending trial notifications with provisional authorization on iOS](https://nilcoalescing.com/blog/TrialNotificationsWithProvisionalAuthorizationOnIOS)
  **Published:** `2025-03-31`
  **Topics:** App Services & Extensions
  **NeKI brief:** Uses provisional notification authorization to trial notifications before asking for full permission. Useful for measuring engagement while delaying a disruptive prompt until the user has seen value.
- [Sorting arrays in Swift using comparison operators as closures](https://nilcoalescing.com/blog/SortingArraysInSwiftUsingComparisonOperators)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Swift comparison operators can be passed as closures for concise ascending or descending sorts, while stable ordering and optional values still require explicit policy. Follow it for readable sorting without losing comparator semantics.
- [Rendering quadratic Bézier curves with Metal](https://nilcoalescing.com/blog/RenderingQuadraticBezierCurvesWithMetal)
  **Published:** `2025-03-31`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** For freehand strokes with thousands of points, a quadratic Bézier representation can move curve rendering to Metal while tolerating self-intersections. The implementation favors a simple GPU pipeline, making its performance compromises explicit for production drawing tools.
- [Recursive enums in Swift](https://nilcoalescing.com/blog/RecursiveEnumsInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Uses recursive enums to model tree-like or nested data in Swift, including indirect cases. Useful for parsers and expression models where reference objects would obscure value semantics.
- [Pattern matching for custom types in Swift](https://nilcoalescing.com/blog/PatternMatchingForCustomTypesInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Swift pattern matching can use custom ~= overloads to express domain-specific case tests while keeping switch exhaustiveness. The technique is useful for readable validation, but should be constrained to avoid hiding expensive predicates.
- [See all parameter permutations in code completion in Xcode 15](https://nilcoalescing.com/blog/ParameterPermutationsInXcode15Autocomplete)
  **Published:** `2025-03-31`
  **Topics:** Xcode
  **NeKI brief:** Xcode 15 code completion can expose parameter permutations for overloaded or labeled APIs, reducing trial-and-error when constructing calls. Follow it for a small tooling workflow that improves correctness at the call site.
- [Notification action buttons with images in iOS](https://nilcoalescing.com/blog/NotificationActionButtonsWithImages)
  **Published:** `2025-03-31`
  **Topics:** Testing
  **NeKI brief:** Shows adding icons to actionable push-notification buttons with UNNotificationActionIcon. Use it to make notification actions more recognizable while checking platform and asset requirements.
- [Streamline multi-criteria data sorting and organization with tuples](https://nilcoalescing.com/blog/MultiCriteriaDataSortingWithTuples)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Tuple comparison lets Swift sort records by several fields in priority order without a verbose comparator, provided each component is Comparable. The pattern is useful for deterministic lists and makes tie-break policy visible.
- [Creating gradient on polylines in SwiftUI MapKit](https://nilcoalescing.com/blog/GradientOnPolylinesInSwiftUIMapKit)
  **Published:** `2025-03-31`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Applies a gradient along MapKit polylines rendered in SwiftUI. Useful for route visualizations where color encodes progress or another value along a geographic path.
- [Filtering logs in Xcode 15](https://nilcoalescing.com/blog/FilteringLogsInXcode15)
  **Published:** `2025-03-31`
  **Topics:** Xcode
  **NeKI brief:** Xcode 15's console predicates filter logs by subsystem, category, process, or message content, making noisy concurrent output actionable. The workflow helps isolate lifecycle and networking diagnostics without changing production logging code.
- [Enhanced replace transition for SF Symbols in iOS 18](https://nilcoalescing.com/blog/EnhancedReplaceTransitionForSFSymbolsInIOS18)
  **Published:** `2025-03-31`
  **Topics:** SwiftUI
  **NeKI brief:** Combines symbol replacement effects with SwiftUI transitions for smoother icon changes on iOS 18. Useful when state-driven symbols should animate semantically instead of cross-fading unrelated images.
- [Count the number of objects that pass a test in Swift using count(where:)](https://nilcoalescing.com/blog/CountTheNumberOfObjectsThatPassATestInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift · Testing
  **NeKI brief:** Counts collection elements satisfying a predicate using readable standard-library operations. Useful for expressing test-like aggregate conditions without manual counters or unnecessary intermediate arrays.
- [ControlGroup in context menus in SwiftUI](https://nilcoalescing.com/blog/ControlGroupInContextMenus)
  **Published:** `2025-03-31`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ControlGroup groups related commands inside a SwiftUI context menu while preserving menu semantics and platform presentation. Follow it when a long action list needs structure without custom UIKit menu plumbing.
- [Compare arrays based on custom criteria](https://nilcoalescing.com/blog/CompareArraysBasedOnCustomCriteria)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Array comparison by a custom criterion requires deciding order, duplicates, and element identity rather than relying on direct equality. The examples help turn a vague 'same contents' check into a testable domain rule.
- [Case insensitive string comparison in Swift](https://nilcoalescing.com/blog/CaseInsensitiveStringComparisonInSwift)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** Compares Swift strings case-insensitively with locale-aware options rather than lowercasing blindly. Useful for search and identity checks where Unicode and user locale affect correctness.
- [Auto-convert JSON snake case to Swift camel case properties](https://nilcoalescing.com/blog/AutoConvertJsonSnakeCaseToSwiftCamelCaseProperties)
  **Published:** `2025-03-31`
  **Topics:** Swift
  **NeKI brief:** JSONDecoder's convertFromSnakeCase strategy maps wire keys to Swift naming conventions, reducing repetitive CodingKeys while retaining explicit exceptions. The article is useful for auditing where automatic conversion changes names unexpectedly.
- [Method dispatch mechanisms in Swift: static and dynamic dispatch](https://nilcoalescing.com/blog/MethodDispatchMechanismsInSwift)
  **Published:** `2025-03-28`
  **Topics:** Performance · Swift
  **NeKI brief:** Contrasts static and dynamic Swift dispatch mechanisms. Use it when protocol requirements, extensions, class inheritance, or generics produce a method call that resolves differently than expected.
- [Overview of the new SwiftUI navigation APIs](https://nilcoalescing.com/blog/SwiftUINavigation2022)
  **Published:** `2025-03-26`
  **Topics:** Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Overviews the 2022 SwiftUI navigation APIs. Use it when migrating from NavigationView to typed destinations, path-based stacks, and split-view-aware routing.
- [Using the dismiss action from the SwiftUI environment](https://nilcoalescing.com/blog/UsingTheDismissActionFromTheSwiftUIEnvironment)
  **Published:** `2025-03-25`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Demonstrates SwiftUI's dismiss action from the environment for closing sheets, popovers, and navigation presentations. Useful for keeping dismissal owned by the presented context instead of passing imperative callbacks through reusable child views.
- [Adapting images and symbols to Dynamic Type sizes in SwiftUI](https://nilcoalescing.com/blog/AdaptingImagesAndSymbolsToDynamicTypeSizesInSwiftUI)
  **Published:** `2025-03-24`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses Dynamic Type size information to adapt image and symbol sizing alongside text, rather than letting decorative controls become visually disproportionate. The approach is useful when auditing compact layouts at accessibility sizes.
- [Provide macOS system-wide services from your app](https://nilcoalescing.com/blog/macOSSystemWideServices)
  **Published:** `2025-03-21`
  **Topics:** Testing
  **NeKI brief:** Shows integrating macOS system-wide services into a SwiftUI application. Useful when exposing text or data transformations to other apps through the platform Services menu.
- [Access colors and images from asset catalog via static properties in Xcode 15](https://nilcoalescing.com/blog/Xcode15Assets)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Reviews Xcode 15 asset-catalog changes and their impact on app resources. Useful for auditing asset pipelines when adopting newer simulator, color, and symbol tooling.
- [WebSocket demo server in Node.js](https://nilcoalescing.com/blog/WebSocketDemoServerInNodeJS)
  **Published:** `2025-03-21`
  **Topics:** Networking · Testing
  **NeKI brief:** A small Node.js WebSocket server exposes connection lifecycle, message framing, and broadcast behavior behind a minimal demo. Follow it to validate a Swift client protocol before introducing production authentication and reconnection policy.
- [Save custom Codable types in AppStorage or SceneStorage](https://nilcoalescing.com/blog/SaveCustomCodableTypesInAppStorageOrSceneStorage)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** AppStorage and SceneStorage only natively persist scalar Foundation values, but Codable values can be encoded through a RawRepresentable wrapper. This preserves typed settings or restoration state while keeping the property-wrapper API intact.
- [Reading keyboard modifiers on iPad in SwiftUI](https://nilcoalescing.com/blog/ReadingKeyboardModifiers)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Reads keyboard modifier flags in SwiftUI commands and gestures. Useful for macOS and iPad keyboard workflows where the same action changes with Command, Option, Shift, or Control.
- [Add launch at login setting to a macOS app](https://nilcoalescing.com/blog/LaunchAtLoginSetting)
  **Published:** `2025-03-21`
  **Topics:** macOS & AppKit
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [Large content viewer in SwiftUI](https://nilcoalescing.com/blog/LargeContentViewerInSwiftUI)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's largeContentViewer enables an enlarged preview for compact controls when accessibility settings or pointer interaction make labels hard to read. The article shows where the modifier helps and why it should complement, not replace, visible labeling.
- [Exporting and importing localizations in a SwiftUI app](https://nilcoalescing.com/blog/ExportingAndImportingLocalizations)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** String Catalog localization export/import creates a translator-facing interchange while preserving source keys and app metadata. Follow it to design an i18n workflow that separates translation edits from generated project files.
- [Subscribe to Django ORM changes over a WebSocket connection](https://nilcoalescing.com/blog/DjangoChannelsRestFrameworkSubscribingToModels)
  **Published:** `2025-03-21`
  **Topics:** Networking
  **NeKI brief:** Subscribing to Django ORM changes over a WebSocket turns model events into a live client stream, but requires explicit filtering and lifecycle handling. Follow it when designing server push beyond request-response APIs.
- [Expose Django REST-like API over a WebSocket connection](https://nilcoalescing.com/blog/DjangoChannelsRestFramework)
  **Published:** `2025-03-21`
  **Topics:** Networking
  **NeKI brief:** Exposing a REST-like API over Django Channels demonstrates routing WebSocket messages into database-backed actions. The example helps compare persistent connections with HTTP while keeping serialization and authorization boundaries visible.
- [Managing WebSocket messages concurrently with detached actions](https://nilcoalescing.com/blog/DetachedActionsInDjangoChannelsRestFramework)
  **Published:** `2025-03-21`
  **Topics:** Networking
  **NeKI brief:** Detached actions let concurrent WebSocket handlers perform work without blocking the receive loop, but introduce ordering and cancellation concerns. The article is useful for diagnosing races in message-driven async services.
- [Copy a string to the clipboard in Swift on macOS](https://nilcoalescing.com/blog/CopyStringToClipboardInSwiftOnMacOS)
  **Published:** `2025-03-21`
  **Topics:** Swift
  **NeKI brief:** Highlights the platform difference between macOS NSPasteboard and iOS UIPasteboard when replacing clipboard contents: macOS requires clearing existing items first. The small distinction prevents stale pasteboard data in a cross-platform implementation.
- [Check localizable strings with the accented pseudolanguage in Xcode](https://nilcoalescing.com/blog/CheckLocalizableStringsWithAccentedPseudolanguage)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Shows using Xcode's accented pseudolanguage to expose missing or hard-coded localization strings. Follow it as a practical UI test pass before translation review, especially for text assembled across multiple views.
- [Change TextEditor background in SwiftUI](https://nilcoalescing.com/blog/ChangeTextEditorBackground)
  **Published:** `2025-03-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows that TextEditor keeps its scroll-content background unless scrollContentBackground(.hidden) is applied before supplying a custom background. It is a focused workaround for styling SwiftUI editors without fighting the internal scroll view.
- [Adjust SwiftUI controls for the Button Shapes accessibility setting](https://nilcoalescing.com/blog/ButtonShapesSetting)
  **Published:** `2025-03-21`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses the accessibilityShowButtonShapes environment value to expose shape cues for buttons and links embedded in text. It provides a concrete fallback for interfaces whose color or typography alone does not communicate affordance.
- [Build a realtime social network using Django Channels](https://nilcoalescing.com/blog/BuildingARealtimeSocialNetworkUsingDjangoChannels)
  **Published:** `2025-03-21`
  **Topics:** Networking
  **NeKI brief:** A realtime social network combines Django models, Channels consumers, and WebSocket fan-out, making event ownership explicit. Follow it for an end-to-end reference while evaluating presence, ordering, and reconnect behavior.
- [Multiple buttons in SwiftUI List rows](https://nilcoalescing.com/blog/MultipleButtonsInListRows)
  **Published:** `2025-03-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains why multiple SwiftUI buttons in a List row can inherit row-wide tap behavior and fire together. Applying an explicit button style restores independent hit targets, a useful diagnosis for platform-default interaction surprises.
- [Customizing modal presentation background and color scheme in SwiftUI](https://nilcoalescing.com/blog/ModalPresentationBackgroundAndColorSchemeInSwiftUI)
  **Published:** `2025-03-08`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows custom backgrounds and explicit color-scheme control for SwiftUI sheets, popovers, and full-screen covers. Use it when modal presentation needs consistent appearance across light and dark environments.
- [Reading and setting color scheme in SwiftUI](https://nilcoalescing.com/blog/ReadingAndSettingColorSchemeInSwiftUI)
  **Published:** `2025-03-07`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI colorScheme can be read from the environment or overridden with preferredColorScheme, separating inherited system preference from a view's presentation choice. This distinction helps test dark-mode behavior without global side effects.
- [SwiftUI sheet sizing updates on iPadOS 18](https://nilcoalescing.com/blog/FormSheetInSwiftUI)
  **Published:** `2025-03-07`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Presents form-sheet sizing and presentation behavior in SwiftUI, including platform-specific adaptation. Useful when a form needs modal structure without treating every sheet as full-screen content.
- [Preview SwiftUI views with bindings using @Previewable](https://nilcoalescing.com/blog/PreviewSwiftUIViewsWithBindings)
  **Published:** `2025-03-04`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI · Xcode
  **NeKI brief:** Shows how Xcode 16's @Previewable macro supplies local mutable state so SwiftUI previews can exercise views that require bindings.
- [Testing remote push notifications on iOS simulator](https://nilcoalescing.com/blog/TestingRemotePushOniOSSimulator)
  **Published:** `2025-03-03`
  **Topics:** Testing · Xcode
  **NeKI brief:** Explains the Xcode 14 simulator device-token support for remote push testing, including obtaining a token and sending server payloads without a physical device, .apns fixture, or simctl push command.
- [Detecting the focused window on macOS in SwiftUI](https://nilcoalescing.com/blog/DetectFocusedWindowOnMacOS)
  **Published:** `2025-03-03`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates detecting macOS window focus with SwiftUI’s appearsActive environment value. Use it to update controls or visuals when a scene becomes active or inactive.
- [Using Measurements from Foundation for values in Swift Charts](https://nilcoalescing.com/blog/UsingMeasurementsFromFoundationAsValuesInSwiftCharts)
  **Published:** `2025-02-19`
  **Topics:** Swift
  **NeKI brief:** Foundation Measurement values can feed Swift Charts while preserving unit semantics and conversion rules. The technique helps avoid plotting mixed units as if they were comparable raw numbers.
- [Testing SceneStorage state persistence in Xcode](https://nilcoalescing.com/blog/TestingSceneStorageStatePersistenceInXcode)
  **Published:** `2025-02-19`
  **Topics:** Persistence & Synchronisation · Swift · SwiftUI · Testing · Xcode
  **NeKI brief:** Describes a repeatable simulator sequence for testing SceneStorage restoration: background the app, terminate or relaunch it, and verify state after scene recreation. The workflow avoids false positives from merely navigating away within one process.
- [Sort elements based on a property value using KeyPathComparator](https://nilcoalescing.com/blog/SortElementsBasedOnAPropertyValueUsingKeyPathComparator)
  **Published:** `2025-02-19`
  **Topics:** Swift
  **NeKI brief:** KeyPathComparator packages a property-based ordering with type information, making sort descriptors reusable for tables and lists. Follow it when ordering logic should remain declarative and consistent across UI surfaces.
- [Set supported platforms in file target membership options in Xcode](https://nilcoalescing.com/blog/SetSupportedPlatformsInFileTargetMembershipOptionsInXcode)
  **Published:** `2025-02-19`
  **Topics:** Xcode
  **NeKI brief:** Xcode target membership can specify supported platforms per file, allowing shared projects to keep platform-specific implementations close together. The workflow is useful for diagnosing accidental compilation on an unsupported SDK.
- [Scroll List to row in SwiftUI on iOS 13](https://nilcoalescing.com/blog/ScrollListToRowInSwiftUI)
  **Published:** `2025-02-19`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** List scrolling before modern SwiftUI APIs required stable row identity and often a UIKit bridge to locate the underlying scroll view. The workaround is useful only when supporting older deployment targets.
- [Fill bar marks with gradient in Swift Charts](https://nilcoalescing.com/blog/FillBarMarksWithGradient)
  **Published:** `2025-02-19`
  **Topics:** Swift
  **NeKI brief:** Demonstrates filling Swift Charts BarMark values with gradients. Use it when visual encoding needs a controlled gradient while preserving mark identity, legibility, and a meaningful legend or label.
- [Show chart annotations on hover in Swift Charts](https://nilcoalescing.com/blog/ChartAnnotationsOnHover)
  **Published:** `2025-02-19`
  **Topics:** Swift
  **NeKI brief:** Swift Charts hover annotations combine pointer location with chart proxy coordinate conversion to identify the nearest data value. The pattern is useful for desktop dashboards where a tooltip must follow marks precisely.
- [Animate UIKit views with SwiftUI animations in iOS 18](https://nilcoalescing.com/blog/AnimateUIKitViewsWithSwiftUIAnimations)
  **Published:** `2025-02-19`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Shows how iOS 18 lets UIKit views participate in SwiftUI animation transactions, using UIViewRepresentable-backed views and the new animation bridge. Apply it when incrementally adding SwiftUI motion to an existing UIKit screen while keeping UIKit layout and lifecycle ownership.
- [SwiftUI Fundamentals: a deeper look into the framework](https://nilcoalescing.com/blog/SwiftUIFundamentalsReleaseAnnouncement)
  **Published:** `2025-02-18`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Announces Natalia Panferova's SwiftUI Fundamentals book, which develops core framework concepts and APIs. Use it as structured learning material, checking examples against the SDK version used by a project.
- [Plotting data distributions with Swift Charts](https://nilcoalescing.com/blog/PlottingDataDistributionsWithSwiftCharts)
  **Published:** `2025-02-02`
  **Topics:** Swift
  **NeKI brief:** Plotting distributions in Swift Charts requires choosing bins, domains, and mark density before styling. The examples help turn raw observations into an interpretable chart while keeping aggregation policy explicit.
- [Capture UUID values with regex in Swift](https://nilcoalescing.com/blog/CaptureUUIDValuesWithRegex)
  **Published:** `2025-02-02`
  **Topics:** Swift
  **NeKI brief:** Uses Swift RegexBuilder to extract and validate UUID values with reusable typed components. Use it when parsing identifiers from user input or untrusted text without ad-hoc string operations.
- [Responding to keyboard modifiers on macOS in SwiftUI](https://nilcoalescing.com/blog/RespondingToModifierKeys)
  **Published:** `2025-01-17`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI on macOS exposes keyboard modifier state through event-aware handlers, enabling alternate commands without replacing native input routing. Follow it when pointer and keyboard interactions must share one action model.
- [Reduce Codable boilerplate with the help of property wrappers](https://nilcoalescing.com/blog/ReducingTheCodableBoilerplate)
  **Published:** `2025-01-09`
  **Topics:** Swift
  **NeKI brief:** Uses Codable property wrappers to centralize per-field encoding and decoding rules, reducing repeated custom init code while preserving typed models. The approach is useful when several fields share transformations but still need explicit failure behavior.
- [Encode and decode polymorphic types in Swift](https://nilcoalescing.com/blog/BringingPolymorphismToCodable)
  **Published:** `2025-01-09`
  **Topics:** Swift
  **NeKI brief:** Builds reusable Codable support for polymorphic values by recording a discriminator and dispatching decoding to the matching concrete type. It makes the wire-format contract explicit instead of relying on fragile type inference.
- [Custom function evaluation on the GPU with MPSGraph](https://nilcoalescing.com/blog/FunctionsOnYourGPU)
  **Published:** `2024-08-05`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** MPSGraph evaluates custom functions on the GPU by translating tensor operations into a graph execution plan. The article helps weigh setup overhead and data-transfer cost against throughput for numeric workloads.
- [iOS keyboard shortcuts in SwiftUI on iOS 13](https://nilcoalescing.com/blog/iOSKeyboardShortcutsInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI keyboard shortcuts attach commands to views with discoverable titles and modifiers, but focus and platform scope determine delivery. Follow it when adding hardware-keyboard actions without bypassing the responder system.
- [View modifier for a custom hover effect in SwiftUI](https://nilcoalescing.com/blog/ViewModifierForACustomHoverEffectInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A custom hover modifier packages pointer-state transitions into reusable view behavior while retaining platform availability boundaries. The pattern helps keep desktop affordances consistent without scattering onHover closures.
- [State restoration with SceneStorage in SwiftUI apps](https://nilcoalescing.com/blog/UsingSceneStorageForStateRestorationInSwiftUIApps)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SceneStorage persists scene-local values across restoration, unlike app-wide settings, so keys and serialization determine what returns after relaunch. The guide helps avoid sharing window-specific navigation state accidentally.
- [Tracking hover location in SwiftUI](https://nilcoalescing.com/blog/TrackingHoverLocationInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates continuous pointer tracking with onContinuousHover on macOS 13 and iPadOS 16. Store the active HoverPhase location in State, then use the coordinates for hover-driven drawing, effects, or custom interaction within the view’s bounds.
- [Test iOS build from production Xcode on beta iOS simulators](https://nilcoalescing.com/blog/TestIOSBuildFromProductionXcodeOnBetaIOSSimulators)
  **Published:** `2024-07-14`
  **Topics:** Testing · Xcode
  **NeKI brief:** Testing a production Xcode build on beta simulators separates app compatibility from adopting an unfinished toolchain. The workflow is useful for catching OS regressions while keeping release builds reproducible.
- [Swift enum pattern matching with extra conditions](https://nilcoalescing.com/blog/SwiftEnumPatternMatchingWithExtraConditions)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Swift enum pattern matching can add a where condition to bind associated values and test extra predicates in one case. This keeps branching exhaustive while making domain validation visible at the switch site.
- [Show multiple sheets at once in SwiftUI](https://nilcoalescing.com/blog/ShowMultipleSheetsAtOnceInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Presenting multiple SwiftUI sheets requires attaching presentation state at the correct hierarchy and ensuring each identity remains distinct. The pattern helps diagnose why a second modal silently replaces the first.
- [Show half-sheet in SwiftUI](https://nilcoalescing.com/blog/ShowHalfSheetInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A half-sheet presentation uses a controlled UIKit presentation boundary when early SwiftUI lacked detents. The technique makes dismissal and sizing explicit, useful for legacy-target compatibility decisions.
- [Set custom actions for links in Text views](https://nilcoalescing.com/blog/SetCustomActionsForLinksInTextViews)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI Text links can route through custom OpenURL actions, allowing in-app destinations or confirmation flows while retaining link styling and accessibility. Follow it when external URLs need policy-aware handling.
- [Use ScrollViewReader in SwiftUI to scroll to a new item](https://nilcoalescing.com/blog/ScrollToNewlyAddedItemUsingScrollViewReaderAndOnChangeModifier)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ScrollViewReader can move to a newly appended item when an observed collection change occurs, provided the destination has stable identity. The pattern helps avoid race conditions between layout and imperative scrolling.
- [Scroll TextField into visible range in SwiftUI by wrapping UITextField](https://nilcoalescing.com/blog/ScrollTextFieldIntoVisibleRange)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Scrolling a TextField into view may require bridging UIKit focus and scroll coordinates when the keyboard changes available space. The workaround is useful for older SwiftUI targets with form fields near screen edges.
- [Use SwiftUI views as points in scatter plot](https://nilcoalescing.com/blog/ScatterPlotWithCustomViews)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a Swift Charts scatter plot using SwiftUI views as data-point marks. Use it when chart points need richer labels or symbols than the standard mark styling.
- [Ridgeline plot with Swift Charts](https://nilcoalescing.com/blog/RidgePlotWithSwiftCharts)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Creates a ridgeline plot with Swift Charts. Use it when comparing multiple distributions over a common axis and standard bar or line charts obscure the pattern.
- [Requesting App Store reviews in SwiftUI](https://nilcoalescing.com/blog/RequestingAppStoreReviewsInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Requesting App Store reviews in SwiftUI uses an environment action whose presentation remains system-controlled. The article clarifies trigger timing and why repeated calls cannot guarantee a prompt, useful for respectful review UX.
- [Provide the current document to menu commands in a SwiftUI app](https://nilcoalescing.com/blog/ProvidingTheCurrentDocumentToMenuCommands)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Passes the focused document from a SwiftUI scene into Commands through a focused scene value, so menu actions operate on the active window's model. The pattern avoids global selection state in multi-window document apps.
- [Programmatically hide and show sidebar in split view](https://nilcoalescing.com/blog/ProgrammaticallyHideAndShowSidebarInSplitView)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Controls a SwiftUI split-view sidebar programmatically. Use it when selection, window width, or a user command should coordinate sidebar visibility.
- [Preview files with QuickLook in SwiftUI](https://nilcoalescing.com/blog/PreviewFilesWithQuickLookInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** QuickLook preview integration presents local documents through a platform controller while SwiftUI owns selection state. Follow it when file previews need system rendering rather than custom format-specific views.
- [Pin a view to the bottom of safe area in SwiftUI](https://nilcoalescing.com/blog/PinAViewToTheBottomOfSafeArea)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Pinning a view to the safe-area bottom uses layout and inset policy rather than hard-coded device offsets. The pattern helps keep persistent controls above home indicators and keyboards across devices.
- [Nil coalescing for optionals in debug prints](https://nilcoalescing.com/blog/NilCoalescingForOptionalsInDebugPrints)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Debug output can coalesce optionals into readable placeholders without changing production data flow. The small technique helps logs distinguish an absent value from an interpolation artifact during diagnostics.
- [Markdown in SwiftUI Text views](https://nilcoalescing.com/blog/MarkdownInSwiftUITextViews)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI Text renders supported Markdown into semantic styled runs, with limitations around unsupported syntax and custom interaction. Follow it when choosing between lightweight rich text and a full HTML or attributed-text pipeline.
- [Selection based navigation in SwiftUI macOS apps](https://nilcoalescing.com/blog/ListSelectionForNavigation)
  **Published:** `2024-07-14`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Selection-driven navigation in macOS SwiftUI binds a List selection to detail content, separating route identity from the visible row. The pattern is useful for split views and state restoration.
- [Reorder List rows containing text fields in SwiftUI on macOS](https://nilcoalescing.com/blog/ListReorderingWhileStillBeingAbleToEditTheListItems)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Reordering List rows containing editable controls requires stable identity and carefully scoped gestures so drag interaction does not steal text editing. The pattern resolves that gesture conflict without abandoning inline editing.
- [Use KeyPath to drive programmatic focus](https://nilcoalescing.com/blog/KeyPathFocus)
  **Published:** `2024-07-14`
  **Topics:** Observation & State Management · SwiftUI
  **NeKI brief:** Key-path focus APIs connect SwiftUI focus state to a specific model field, keeping keyboard navigation and validation aligned with domain identity. The pattern helps avoid ad-hoc booleans for complex forms.
- [Inspectors in SwiftUI](https://nilcoalescing.com/blog/InspectorInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's inspector presentation to expose contextual controls from a view. Useful for macOS and iPad interfaces where secondary configuration should remain discoverable without another navigation screen.
- [Hide and show a view with opacity](https://nilcoalescing.com/blog/HideAndShowAViewWithOpacity)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Hiding with opacity keeps a view in layout and can preserve accessibility or hit-testing unless those aspects are changed separately. The article helps choose between visual transition and structural removal.
- [Handling undo & redo in SwiftUI](https://nilcoalescing.com/blog/HandlingUndoAndRedoInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Wraps UndoManager access in a reusable SwiftUI view modifier that records binding changes and exposes undo/redo actions. The design keeps editing history close to state mutation while leaving the surrounding view declarative.
- [Getting ready for iOS 14 local network privacy restrictions](https://nilcoalescing.com/blog/GettingReadyForNewiOS14LocalNetworkPrivacyRestrictions)
  **Published:** `2024-07-14`
  **Topics:** Networking
  **NeKI brief:** iOS local-network privacy requires declaring usage and handling authorization before device discovery or LAN connections. Follow it when debugging connections that work in development but fail after privacy enforcement.
- [Get URLs for system folders in iOS 16](https://nilcoalescing.com/blog/GetURLsForSystemFolders)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Uses Foundation APIs to locate standard system folders on iOS 16. Use it when file persistence needs the correct Documents, Caches, Application Support, or temporary directory semantics.
- [Find and replace in iOS and iPadOS 16](https://nilcoalescing.com/blog/FindAndReplaceIniOSAndiPadOS)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Find-and-replace in an iOS text editor needs matching policy, replacement ranges, and selection updates to remain consistent. The article offers a concrete editing-workflow reference for document-style apps.
- [Enable text selection for non-editable text](https://nilcoalescing.com/blog/EnableTextSelectionForNonEditableText)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Noneditable SwiftUI text can enable selection without becoming an input control, separating copy behavior from editing state. The technique helps preserve accessibility and platform text interactions in read-only screens.
- [Editable navigation titles in SwiftUI on iOS 16](https://nilcoalescing.com/blog/EditableNavigationTitlesInSwiftUIoniOS16)
  **Published:** `2024-07-14`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Editable navigation titles expose a compact editing interaction whose binding must reconcile draft text, validation, and navigation state. Follow it when titles are user data rather than static labels.
- [Display high precision time with Duration and TimeFormatStyle](https://nilcoalescing.com/blog/DurationAndTimeFormatStyle)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Duration and TimeFormatStyle format temporal values with locale-aware semantics instead of hand-built strings. The article helps keep elapsed-time display correct across units, pluralization, and user settings.
- [Customize the style of links embedded in Text](https://nilcoalescing.com/blog/CustomizeTheStyleOfLinksEmbeddedInText)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Text links can be styled through attributed or environment-based presentation without changing their URL semantics. The pattern helps distinguish visual branding from routing and accessibility behavior.
- [Customize navigation bar background](https://nilcoalescing.com/blog/CustomizeNavigationBarBackground)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Customizing a navigation bar background must account for scroll-edge appearance, toolbar placement, and system contrast rules. The examples help prevent a style that only works at one scroll position.
- [Customizable toolbar on iPad in SwiftUI](https://nilcoalescing.com/blog/CustomizableToolbarOniPadInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Customizable iPad toolbars let users control command visibility and order, so item identifiers must be stable across launches. The article is useful for building persistent, user-owned command layouts.
- [Customize About panel on macOS in SwiftUI](https://nilcoalescing.com/blog/CustomiseAboutPanelOnMacOSInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A custom macOS About panel uses SwiftUI scene composition while retaining application metadata and native window behavior. The pattern helps replace defaults without scattering AppKit setup throughout the app.
- [Provide custom size for UIViews wrapped in UIViewRepresentable](https://nilcoalescing.com/blog/CustomSizeForUIViewsWrappedInUIViewRepresentable)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses UIViewRepresentable.sizeThatFits to let a wrapped UIKit view participate in SwiftUI's proposed-size negotiation. It provides a precise escape hatch when intrinsic content size alone cannot express the desired layout.
- [Using compositing group for unifying shapes within buttons in SwiftUI](https://nilcoalescing.com/blog/CompositingGroupInButtons)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains how compositingGroup changes rendering and hit behavior in styled SwiftUI buttons. Useful when effects, masks, and backgrounds produce unexpected visual or interaction results.
- [Check if two values of type Any are equal](https://nilcoalescing.com/blog/CheckIfTwoValuesOfTypeAnyAreEqual)
  **Published:** `2024-07-14`
  **Topics:** Swift · Xcode
  **NeKI brief:** Comparing two Any values requires recovering equatable type information at runtime, with clear limits for heterogeneous values. The article helps avoid false assumptions when designing type-erased data structures.
- [Build and style a chart with the new Swift Charts framework](https://nilcoalescing.com/blog/BuildAndStyleAChartWithSwiftChartsFramework)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Introduces building and styling charts with Swift Charts. Use it when a data visualization needs typed marks, scales, and accessibility-aware system chart behavior.
- [Dynamic List of items in SwiftUI](https://nilcoalescing.com/blog/BindingToArrayInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Bindings to array elements rely on stable indices and collection mutation rules, otherwise a view can write to the wrong item after reorder or deletion. The guide helps model editable lists safely.
- [Using Layout protocol to align explicitly positioned views in SwiftUI](https://nilcoalescing.com/blog/AnchoredPositionInSwiftUI)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates anchored positioning for placing SwiftUI content relative to a point or anchor. Useful for overlays and callouts that should follow layout geometry without manual offsets.
- [Align y-axis to leading edge in Swift Charts](https://nilcoalescing.com/blog/AlignYAxisToLeadingEdgeInSwiftCharts)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Aligning a Swift Charts y-axis to the leading edge uses chart-axis configuration rather than view offsets. The technique helps keep labels readable and consistently placed in adaptive layouts.
- [Adjust the direction of focus-based navigation in SwiftUI](https://nilcoalescing.com/blog/AdjustTheDirectionOfFocusBasedNavigation)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Adjusts focus-based navigation direction in SwiftUI. Use it when tvOS or keyboard interfaces need predictable directional movement between controls.
- [Adjust List row separator insets](https://nilcoalescing.com/blog/AdjustListRowSeparatorInsets)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** List row separator insets can be adjusted without replacing the system List, preserving native behavior while matching a design grid. The article helps avoid custom separators that impair accessibility or reuse.
- [Mutable static properties in generic types and protocol extensions](https://nilcoalescing.com/blog/AddingMutableStaticPropertiesToGenericsAndProtocolExtensions)
  **Published:** `2024-07-14`
  **Topics:** Swift
  **NeKI brief:** Mutable static properties in generic and protocol-extension contexts reveal how Swift specializes storage and type identity. Follow it when shared configuration appears unexpectedly isolated or shared across conforming types.
- [Double column navigation in a SwiftUI document app](https://nilcoalescing.com/blog/AddingDoubleColumnNavigationToASwiftUIDocumentApp)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Double-column navigation in a SwiftUI document app combines document identity, selection, and split-view structure. The pattern helps preserve a coherent detail route across opening, closing, and restoring documents.
- [Add underline and strikethrough styles to Text](https://nilcoalescing.com/blog/AddUnderlineAndStrikethroughStylesToText)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Text underline and strikethrough styles apply semantic decoration without turning text into images or custom drawing. The examples help maintain Dynamic Type and accessibility while adding editorial emphasis.
- [Add placeholder text to SwiftUI TextEditor](https://nilcoalescing.com/blog/AddPlaceholderTextToSwiftUITextEditor)
  **Published:** `2024-07-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** TextEditor lacks a native placeholder, so an overlay must track emptiness, focus, and hit testing without intercepting editing. The pattern is useful for forms that need prompt text and standard input behavior.
