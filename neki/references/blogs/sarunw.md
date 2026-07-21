# Sarunw

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://sarunw.com/posts/](https://sarunw.com/posts/)
- Last collected: `2026-07-22T15:20:34Z`
- Indexed entries: **443**

- [Animating number changes in SwiftUI | Sarunw](https://sarunw.com/posts/animating-number-changes-in-swiftui) — 2023-11-15
  **NeKI brief:** Uses iOS 17's contentTransition(.numericText()) with animation to interpolate changing numeric text rather than manually assembling transitions. Follow it when counters need legible updates while retaining SwiftUI's text layout.
- [How to create custom view modifiers in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-create-custom-view-modifier-in-swiftui) — 2023-11-08
  **NeKI brief:** Builds reusable styling as a ViewModifier and exposes it through a View extension, keeping call sites declarative while centralizing modifier order and parameters. This pattern is useful when the same visual contract appears across screens.
- [How to request users to review your app in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-request-users-to-review-app-in-swiftui) — 2023-11-01
  **NeKI brief:** Requests App Store ratings through the requestReview environment action, while stressing that the system controls presentation and frequency. The timing discussion helps place prompts after meaningful success instead of treating them as guaranteed UI.
- [How to copy text to the clipboard in iOS | Sarunw](https://sarunw.com/posts/how-to-copy-text-to-clipboard-in-ios) — 2023-10-23
  **NeKI brief:** Uses UIPasteboard.general to write and read string data, then separates the clipboard operation from the UI that triggers it. Useful when implementing copy actions that must also support later inspection or paste flows.
- [How to request users to review your app in UIKit | Sarunw](https://sarunw.com/posts/how-to-request-users-to-review-app-in-uikit) — 2023-10-16
  **NeKI brief:** Shows SKStoreReviewController's requestReview entry point and its system-imposed limits: calls are requests, not immediate prompts, and production frequency is controlled by StoreKit. Use the guidance to choose a contextually appropriate success moment.
- [How to dismiss Keyboard in SwiftUI | Sarunw](https://sarunw.com/posts/dismiss-keyboard-in-swiftui) — 2023-10-09
  **NeKI brief:** Demonstrates dismissing the keyboard from SwiftUI using environment actions and focus state. Useful for predictable form submission and navigation flows without reaching for global UIKit calls.
- [How to break multiple nested loops in Swift | Sarunw](https://sarunw.com/posts/how-to-break-multiple-nested-loops-in-swift) — 2023-10-02
  **NeKI brief:** Labels the outer loop and uses break with that label from an inner loop, making the exit target explicit. This is a small but valuable control-flow tool when a match should terminate several nested iterations.
- [Create Button with Rounded Corner Border in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-bordered-button) — 2023-09-25
  **NeKI brief:** Compares SwiftUI's bordered and borderedProminent button styles, then shows how tint, control size, and corner-radius adjustments affect the resulting control. It is a practical route to system-shaped buttons without rebuilding hit testing.
- [How to get Root view controller in Swift | Sarunw](https://sarunw.com/posts/how-to-get-root-view-controller) — 2023-09-18
  **NeKI brief:** Traverses the active UIWindowScene and key window to locate a root view controller, while acknowledging the shortcut's lifecycle assumptions. Follow it when legacy UIKit integration needs a bridge from scene-based app state to view-controller APIs.
- [Different ways to map over Dictionary in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-map-dictionary-in-swift) — 2023-09-11
  **NeKI brief:** Distinguishes mapValues for transforming dictionary values from map into tuples when keys also change, and shows key-only transformation separately. The choice preserves dictionary semantics where possible and avoids accidental duplicate-key loss.
- [How to convert Degrees to Radians in Swift | Sarunw](https://sarunw.com/posts/how-to-convert-degrees-to-radians) — 2023-09-04
  **NeKI brief:** Relates degree-based UI input to the radian units expected by rotation APIs, presenting both a reusable function and an Angle-style conversion approach. This avoids scattering the pi/180 factor through geometry code.
- [How to fix "libobjc.A.dylib is being read from process memory" error | Sarunw](https://sarunw.com/posts/how-to-fix-libobjc_A_dylib-is-being-read-from-process-memory-error) — 2023-08-28
  **NeKI brief:** Diagnoses the slow device-launch warning about libobjc.A.dylib being read from process memory and ties it to Xcode's debugger behavior rather than app logic. Use the checks to separate a tooling delay from a runtime regression.
- [How to convert between NSAttributedString and AttributedString | Sarunw](https://sarunw.com/posts/how-to-convert-between-nsattributedstring-and-attributedstring) — 2023-08-21
  **NeKI brief:** Uses each type's bridging initializer to move between Foundation's NSAttributedString and Swift's AttributedString. It is useful when SwiftUI and UIKit APIs meet, but the conversion boundary should remain explicit so attribute loss is visible.
- [Better print for AnyKeyPath in Swift 5.8 | Sarunw](https://sarunw.com/posts/better-print-anykeypath) — 2023-08-17
  **NeKI brief:** Explains Swift 5.8's CustomDebugStringConvertible conformance for AnyKeyPath, which makes debug output identify the path more usefully. This improves diagnostics for key-path-driven observation, mapping, or dynamic property access.
- [How to convert Radians to Degrees in Swift | Sarunw](https://sarunw.com/posts/how-to-covert-radins-to-degrees-in-swift) — 2023-08-14
  **NeKI brief:** Converts the radian values used by Core Graphics and transform APIs back into degrees through a reusable function or extension. Keeping this conversion localized makes display-facing angles easier to read without changing API units.
- [Default Value in Swift Dictionary | Sarunw](https://sarunw.com/posts/default-value-in-swift-dictionary) — 2023-08-10
  **NeKI brief:** Uses Dictionary's subscript(default:) to read a fallback or mutate a missing key in place. The single API handles lookup and accumulation without a separate contains check, reducing race-prone or repetitive dictionary branching.
- [How to hide a Navigation Back button in SwiftUI | Sarunw](https://sarunw.com/posts/hide-navigation-back-button-in-swiftui) — 2023-08-07
  **NeKI brief:** Applies navigationBarBackButtonHidden to the destination view, and discusses when removing the system back affordance is appropriate. The placement matters because pushed destinations own their navigation-bar policy.
- [ContentUnavailableView in SwiftUI | Sarunw](https://sarunw.com/posts/content-unavailable-view-in-swiftui) — 2023-08-03
  **NeKI brief:** Introduces ContentUnavailableView for representing empty or unavailable states in SwiftUI on iOS 17. Useful for standardizing search, loading-failure, and no-content screens with system-consistent messaging and actions.
- [How to fix "dyld: Library not loaded @rpath" error | Sarunw](https://sarunw.com/posts/how-to-fix-dyld-library-not-loaded-error) — 2023-07-27
  **NeKI brief:** Diagnoses an @rpath dyld failure as a runtime embedding/linking problem for a third-party framework, then points to the target's framework embedding configuration. Use it to check packaging rather than changing source-level imports.
- [How to add a Toolbar in UINavigationController | Sarunw](https://sarunw.com/posts/how-to-add-toolbar-in-uikit) — 2023-07-24
  **NeKI brief:** Shows the concrete UINavigationController steps for configuring toolbarItems, enabling the navigation controller’s toolbar, and placing flexible spaces or controls so a UIKit toolbar appears and lays out as intended.
- [Observation Framework in iOS 17 | Sarunw](https://sarunw.com/posts/observation-framework-in-ios17) — 2023-07-17
  **NeKI brief:** Introduces the iOS 17 Observation framework and migration from ObservableObject. Useful for understanding macro-generated tracking, ownership, and the deployment constraints of the newer model.
- [Floating Action Button in SwiftUI | Sarunw](https://sarunw.com/posts/floating-action-button-in-swiftui) — 2023-07-11
  **NeKI brief:** Composes a floating action button from a SwiftUI Button, shape, shadow, and overlay positioning rather than relying on a UIKit-specific control. The example highlights safe-area placement and keeping the control's hit region independent of decoration.
- [How to Filter an Array in Swift | Sarunw](https://sarunw.com/posts/swift-array-filter) — 2023-07-10
  **NeKI brief:** Shows filter as a non-mutating sequence operation that returns only elements satisfying a predicate. It is a clear route for deriving display collections while preserving the original model and making the inclusion rule testable.
- [Bookmark in Xcode 15 | Sarunw](https://sarunw.com/posts/bookmark-in-xcode15) — 2023-07-06
  **NeKI brief:** Introduces Xcode 15 bookmarks, including naming and grouping entries in the Bookmarks navigator. This is a lightweight navigation workflow for recurring code locations that avoids scattering temporary comments through a project.
- [How to use NSAttributedString in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-use-nsattributedstring-in-swiftui) — 2023-07-03
  **NeKI brief:** Bridges an existing NSAttributedString into SwiftUI's AttributedString and displays it with Text. The adapter is useful during incremental migrations where UIKit still produces rich text but the destination view is declarative.
- [Built-in symbol animations in UIKit controls | Sarunw](https://sarunw.com/posts/built-in-symbol-animations-in-uikit-controls) — 2023-06-29
  **NeKI brief:** Uses UIButton and other UIKit controls' symbol animation property introduced with iOS 17 to opt into or out of built-in SF Symbol transitions. It provides a state-driven alternative to manually launching symbolEffect animations.
- [SwiftUI Plain Button Style cannot tap on an Empty space | Sarunw](https://sarunw.com/posts/swiftui-plain-button-style-cannot-tap) — 2023-06-26
  **NeKI brief:** Explains why PlainButtonStyle can make a button's empty background non-interactive and fixes the hit area with contentShape. The distinction separates visual styling from the semantic region users can tap.
- [Animate SF Symbols with symbolEffect | Sarunw](https://sarunw.com/posts/animate-sf-symbols-with-symboleffect) — 2023-06-22
  **NeKI brief:** Introduces SwiftUI's symbolEffect modifier and its trigger-driven behaviors for animating SF Symbols in iOS 17. Follow it when choosing repeat, value-change, or discrete effects instead of coordinating custom animation state.
- [Access Images and Colors with Enum in Xcode 15 | Sarunw](https://sarunw.com/posts/swift-symbols-for-asset-catalog) — 2023-06-19
  **NeKI brief:** Shows Xcode 15's generated Swift symbols for asset-catalog images and colors, contrasting the feature with R.swift and SwiftGen. Strongly typed resource access removes string lookups while naming conventions become part of the build contract.
- [Apply Small Caps for unsupported language in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-textscale) — 2023-06-15
  **NeKI brief:** Uses iOS 17's textScale to produce small-cap-like typography when a locale lacks true small-cap support, contrasting it with font-level smallCaps. The choice preserves a typographic effect without assuming every language has matching glyphs.
- [How to test In-App purchases in Development | Sarunw](https://sarunw.com/posts/test-in-app-purchases-in-development) — 2023-06-12
  **NeKI brief:** Sets up App Store Connect sandbox test users and signs in through the development purchase flow instead of using a personal Apple ID. The caveats explain why local StoreKit testing and sandbox behavior should be treated as separate test environments.
- [Little big improvements in Xcode 15 | Sarunw](https://sarunw.com/posts/little-big-improvements-xcode15) — 2023-06-09
  **NeKI brief:** Collects practical Xcode 15 improvements across editing, previews, and debugging. Useful as a toolchain-upgrade checklist for changes that improve workflow without touching runtime code.
- [How to preview UIViewController in Xcode Previews | Sarunw](https://sarunw.com/posts/xcode-previews-with-uiviewcontroller) — 2023-06-08
  **NeKI brief:** Wraps a UIViewController in UIViewControllerRepresentable so programmatic or storyboard controllers can render in Xcode Previews. The helper and storyboard-loading variants make UIKit previewability incremental rather than requiring a SwiftUI rewrite.
- [What's new in SF Symbols 5 | Sarunw](https://sarunw.com/posts/whats-new-in-sf-symbols-5) — 2023-06-07
  **NeKI brief:** Covers SF Symbols 5 animation capabilities, including symbolEffect behaviors and customization of layers and timing. It is a versioned design-and-implementation route for adding motion while respecting symbol rendering structure.
- [Xcode Previews with UIKit and AppKit in Xcode 15 | Sarunw](https://sarunw.com/posts/xcode-previews-with-uikit-appkit-in-xcode-15) — 2023-06-06
  **NeKI brief:** Explains Xcode 15's UIKit and AppKit preview support through UIViewRepresentable and UIViewControllerRepresentable wrappers. The same bridge lets teams preview existing imperative components while keeping production ownership in UIKit or AppKit.
- [How to preview UIView in Xcode Previews | Sarunw](https://sarunw.com/posts/xcode-previews-with-uiview) — 2023-06-05
  **NeKI brief:** Demonstrates previewing a programmatically built UIView via UIViewRepresentable and notes lifecycle caveats around construction. This provides a focused visual feedback loop for UIKit components without adding an Interface Builder representation.
- [SwiftUI Button can't tap on a background | Sarunw](https://sarunw.com/posts/swiftui-button-cannot-tap) — 2023-05-31
  **NeKI brief:** Makes a SwiftUI button's full visual background tappable by defining the intended content shape, rather than relying on painted background pixels. The fix keeps accessibility and gesture semantics aligned with the visible control.
- [How to Disable swipe down to dismiss Sheet in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-interactive-dismiss-disabled) — 2023-05-29
  **NeKI brief:** Applies interactiveDismissDisabled to prevent a sheet's swipe-down dismissal and shows conditional control for state such as unsaved edits. It is useful when dismissal must be gated without replacing the system sheet presentation.
- [Allow implicit self for weak self captures, after self is unwrapped | Sarunw](https://sarunw.com/posts/allow-implicit-self-for-weak-self) — 2023-05-25
  **NeKI brief:** Describes Swift 5.8's relaxed implicit-self rule after a weak capture is unwrapped with guard, reducing repetitive self references while preserving the capture-list ownership boundary. The rule is scoped to escaping-closure safety, not a blanket omission.
- [Back deploy Swift Function | Sarunw](https://sarunw.com/posts/function-back-deployment) — 2023-05-23
  **NeKI brief:** Explains @backDeployed as a library mechanism that ships a fallback implementation for older OS versions while newer systems use the native symbol. Availability and performance limitations make it a compatibility tool, not arbitrary API polyfilling.
- [Find Callers of methods or variables in Xcode | Sarunw](https://sarunw.com/posts/xcode-callers) — 2023-05-22
  **NeKI brief:** Uses Xcode's Call Hierarchy to inspect callers of methods, functions, or variables and trace usage through a codebase. It is a practical impact-analysis step before changing APIs or removing supposedly unused behavior.
- [What is contentInset in a scroll view | Sarunw](https://sarunw.com/posts/what-is-contentinset-in-scrollable-content) — 2023-05-18
  **NeKI brief:** Separates UIScrollView contentInset from safe-area adjustment and explains how the inset changes where content begins and ends. The model helps diagnose unexpected padding in UIKit scrolling layouts instead of compensating with arbitrary view offsets.
- [#file behavior change in Swift 5.8 | Sarunw](https://sarunw.com/posts/file-behavior-change) — 2023-05-15
  **NeKI brief:** Documents a Swift or Xcode file-behavior change and its migration implications. Useful when updating older projects whose generated or resource-file handling no longer matches current tooling.
- [How to make Empty Space Tappable in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-make-empty-space-tappable-in-swiftui) — 2023-05-11
  **NeKI brief:** Uses contentShape to define a stack's tappable geometry, while recommending Button for semantic actions. This resolves the gap between a view's painted content and its intended hit target without adding a global gesture workaround.
- [How to use AttributedString in UIKit | Sarunw](https://sarunw.com/posts/how-to-use-attributedstring-in-uikit) — 2023-05-10
  **NeKI brief:** Bridges Swift's AttributedString into UIKit controls through NSAttributedString initializers, letting modern rich-text data feed legacy labels and text views. The conversion is a useful boundary during mixed SwiftUI/UIKit migrations.
- [How to set ContentInsets on SwiftUI List | Sarunw](https://sarunw.com/posts/how-to-set-contentinsets-in-swiftui) — 2023-05-09
  **NeKI brief:** Uses safeAreaInset as SwiftUI's indirect equivalent to a scroll view content inset, placing additional content-aware space around a List. The approach composes with SwiftUI layout instead of reaching into an underlying UIScrollView.
- [How to check if code is in DEBUG or RELEASE build in Swift | Sarunw](https://sarunw.com/posts/how-to-check-if-swift-code-is-in-debug-build-configuration) — 2023-05-08
  **NeKI brief:** Uses conditional compilation with DEBUG or custom SWIFT_ACTIVE_COMPILATION_CONDITIONS to include code only in selected build configurations. This keeps diagnostics and development-only behavior out of release binaries at compile time.
- [Xcode Previews: What is it, and how to use it | Sarunw](https://sarunw.com/posts/xcode-previews) — 2023-05-04
  **NeKI brief:** Walks through creating and opening Xcode Previews with PreviewProvider and the canvas, including preview variants and device context. It is a workflow reference for shortening visual iteration without changing runtime navigation.
- [Remove all limitations on variables in result builders | Sarunw](https://sarunw.com/posts/lift-all-limitations-on-variables-in-result-builders) — 2023-05-03
  **NeKI brief:** Explains Swift 5.8's SE-0373 change allowing local variables and declarations inside result builders, removing earlier compiler restrictions. This makes intermediate calculations readable in SwiftUI DSL code without extracting every step into a helper.
- [Detecting if SwiftUI app is in Xcode Previews | Sarunw](https://sarunw.com/posts/detecting-xcode-previews) — 2023-05-02
  **NeKI brief:** Detects Preview execution through Xcode's environment marker so preview-only setup or expensive integrations can be bypassed. Keep the branch scoped to tooling concerns; it should not become a substitute for dependency injection in app behavior.
- [How to make Large size ProgressView in SwiftUI | Sarunw](https://sarunw.com/posts/progressview-size) — 2023-05-01
  **NeKI brief:** Explains why SwiftUI's ProgressView does not accept UIKit-style sizing directly, then uses the control's style and frame behavior to achieve a large indicator. Useful when migrating an existing UIKit progress affordance without assuming size maps one-to-one.
- [How to use SFSafariViewController in SwiftUI | Sarunw](https://sarunw.com/posts/sfsafariviewcontroller-in-swiftui) — 2023-04-27
  **NeKI brief:** Wraps SFSafariViewController with UIViewControllerRepresentable, while also showing the simpler Link/openURL choices for ordinary navigation. Follow this when in-app Safari presentation, rather than an external browser handoff, is a deliberate product requirement.
- [Configure Launch screen in UIKit without Storyboard | Sarunw](https://sarunw.com/posts/launch-screen-without-storyboard) — 2023-04-25
  **NeKI brief:** Uses the iOS 14 information-property-list launch-screen configuration to remove a UIKit storyboard dependency. The article is a practical migration checklist: move static launch appearance into plist keys, but keep runtime UI out of the launch screen contract.
- [How to open URL in Safari in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-open-url) — 2023-04-24
  **NeKI brief:** Compares SwiftUI's Link view with the openURL environment action: one is declarative content, the other is an imperative event hook. That distinction helps choose a testable interaction path when URLs come from state or user actions.
- [Conditional compilation for Attributes in Swift 5.8 | Sarunw](https://sarunw.com/posts/conditional-compilation-for-attributes) — 2023-04-20
  **NeKI brief:** Introduces Swift 5.8's hasAttribute conditional directive for source that must compile with and without a newer attribute. It provides a compatibility seam for libraries supporting multiple toolchains, avoiding duplicated files or brittle compiler-version checks.
- [How to initialize @Binding in SwiftUI | Sarunw](https://sarunw.com/posts/binding-initialization) — 2023-04-19
  **NeKI brief:** Clarifies initializing SwiftUI views that accept Binding values and the distinction between a binding and its wrapped value. Useful for avoiding underscore-storage mistakes in custom view initializers.
- [Stable Sort in Swift | Sarunw](https://sarunw.com/posts/stable-sort-in-swift) — 2023-04-18
  **NeKI brief:** Clarifies that Swift's sort is not a stability guarantee and demonstrates preserving original order for equal keys with a stable-sort approach. Follow it when UI lists or ranked results must avoid surprising reshuffles between refreshes.
- [WebView in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-webview) — 2023-04-17
  **NeKI brief:** Separates opening a URL with Safari from embedding WKWebView through UIViewRepresentable. The comparison exposes the maintenance and navigation trade-off: external browser features come for free, while embedded content requires lifecycle bridging.
- [Getting All cases of Enum with Swift CaseIterable | Sarunw](https://sarunw.com/posts/swift-caseiterable) — 2023-04-13
  **NeKI brief:** Shows CaseIterable for enum-driven lists and pickers, then explains why associated-value cases cannot synthesize allCases. The limitation matters when modeling options: use a manually supplied collection when payloads make enumeration ambiguous.
- [Configure Different Launch screens based on URL Scheme | Sarunw](https://sarunw.com/posts/launch-screen-url-scheme) — 2023-04-12
  **NeKI brief:** Configures multiple iOS 14 launch-screen definitions and selects one through URL-scheme metadata. This supports branded entry points while preserving the launch screen's static-only constraint and keeping scheme selection in configuration.
- [SwiftUI Form Styling | Sarunw](https://sarunw.com/posts/swiftui-form-styling) — 2023-04-11
  **NeKI brief:** Shows how SwiftUI Form styling follows the platform’s List behavior: use tint and foregroundColor for controls, hide the scroll background before applying a custom color, and put listRowBackground on sections or row content rather than the Form itself.
- [How to Open using Rosetta in Xcode 14.3 | Sarunw](https://sarunw.com/posts/open-using-rosetta-in-xcode-14-3) — 2023-04-10
  **NeKI brief:** Explains Xcode's Rosetta launch option for Apple-silicon Macs when simulator or binary tooling still depends on Intel translation. Treat it as a compatibility diagnostic with performance cost, not a default build setting.
- [What's New in Swift 5.8 | Sarunw](https://sarunw.com/posts/whats-new-in-swift-5-8) — 2023-04-09
  **NeKI brief:** Surveys Swift 5.8 additions including conditional attributes and macro-related language work, giving migration context rather than one isolated recipe. Follow the relevant feature sections against the project's deployment and compiler-version constraints.
- [How to Hide Navigation Bar on Tap in UIKit | Sarunw](https://sarunw.com/posts/hide-navigation-bar-on-tap-in-uikit) — 2023-04-06
  **NeKI brief:** Adds a tap gesture that toggles navigation and toolbar visibility in UIKit. The interaction is useful for immersive content, but gesture ownership and animated bar transitions must coexist with existing scroll and accessibility behavior.
- [Create Button with Image in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-image-button) — 2023-04-05
  **NeKI brief:** Builds a SwiftUI Button whose label is an image, then adjusts rendering mode and tint so the asset follows the control's state. This keeps semantics and hit testing from being replaced by a decorative gesture.
- [How to pop view from Navigation stack in iOS 16 | Sarunw](https://sarunw.com/posts/how-to-pop-view-from-navigation-stack-in-swiftui) — 2023-04-04
  **NeKI brief:** Uses the iOS 16 dismiss/navigation APIs to pop a NavigationStack destination rather than mutating an index manually. The system-owned route action keeps the view decoupled from stack representation and supports adaptive navigation.
- [Custom Back button in SwiftUI | Sarunw](https://sarunw.com/posts/custom-back-button-in-swiftui) — 2023-04-03
  **NeKI brief:** Replaces the default back affordance with a custom toolbar item while invoking the environment dismiss action. It preserves navigation ownership, but the replacement must retain a clear label and sufficient accessibility hit area.
- [How to Reload view in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-reload-view-in-swiftui) — 2023-03-30
  **NeKI brief:** Shows refresh strategies for SwiftUI data-driven views, distinguishing state invalidation from forcing identity changes. Prefer changing the model or task input; identity resets are a last resort because they discard local view state.
- [How to fix "You are not authorized to make purchases of this InApp in Sandbox at this time" error | Sarunw](https://sarunw.com/posts/how-to-fix-you-are-not-authorized-to-make-purchases-of-this-inapp-in-sandbox-at-this-time-error) — 2023-03-29
  **NeKI brief:** Explains the Sandbox purchase authorization error as an environment and account-state problem, then lists reset checks. Use it to distinguish StoreKit configuration failures from code defects before changing transaction handling.
- [What are Character and Run in AttributedString | Sarunw](https://sarunw.com/posts/attributed-string-views) — 2023-03-28
  **NeKI brief:** Distinguishes AttributedString's Character and Run views: characters address textual units, while runs group contiguous attributes. This is a useful inspection model when styling or parsing rich text without treating each Unicode character as an independent attribute span.
- [How to Hide Toolbar on Scroll in iOS | Sarunw](https://sarunw.com/posts/hide-toolbar-on-scroll-in-uikit) — 2023-03-27
  **NeKI brief:** Uses scroll callbacks to hide or reveal a UIKit toolbar as content moves. The pattern improves reading space, but requires threshold and direction handling to avoid flicker during small, noisy scroll deltas.
- [How to remove the First row separator in SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-remove-first-separator) — 2023-03-23
  **NeKI brief:** Demonstrates removing only the first SwiftUI List separator, targeting the row rather than disabling separators globally. The narrow adjustment preserves platform list affordances elsewhere and avoids replacing List with a custom scrolling implementation.
- [How to pop View programmatically in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-pop-view-from-navigation-view-in-swiftui) — 2023-03-22
  **NeKI brief:** Demonstrates programmatic dismissal from the older NavigationView model using SwiftUI's presentation environment. It is a compatibility reference for pre-NavigationStack code, where route state and modal dismissal have different ownership rules.
- [How to create SwiftUI Picker from Enum | Sarunw](https://sarunw.com/posts/swiftui-picker-enum) — 2023-03-21
  **NeKI brief:** Makes an enum picker-friendly by combining CaseIterable with an identifiable or hashable selection value. It keeps the selection domain type-safe and documents the boundary where display labels may differ from raw enum values.
- [AttributedString in iOS 15 | Sarunw](https://sarunw.com/posts/attributed-string) — 2023-03-20
  **NeKI brief:** Introduces AttributedString as Swift's value-typed rich-text model, covering concatenation, containers, and partial styling. Follow it when replacing NSAttributedString to gain safer composition while still mapping presentation attributes deliberately.
- [How to set Info.plist Values based on Build Configuration in Xcode | Sarunw](https://sarunw.com/posts/set-info-plist-value-per-build-configuration) — 2023-03-16
  **NeKI brief:** Uses build-setting substitution and custom Info.plist entries to supply configuration-specific values. This keeps staging and production metadata out of source conditionals, but requires auditing generated plist output so missing substitutions fail visibly.
- [Configure Launch screen in SwiftUI using Storyboard | Sarunw](https://sarunw.com/posts/launch-screen-with-storyboard) — 2023-03-15
  **NeKI brief:** Keeps a storyboard launch screen when plist configuration cannot express the required layout flexibility. The comparison clarifies the trade-off: richer static composition costs another resource and must still finish before app UI starts.
- [How to preview SwiftUI Layout without device frame | Sarunw](https://sarunw.com/posts/swiftui-preview-without-device-frame) — 2023-03-14
  **NeKI brief:** Removes the device chrome from SwiftUI previews to inspect the view's actual layout bounds. This speeds visual iteration and makes spacing easier to judge, while device-specific safe-area behavior should still be tested separately.
- [How to Hide Navigation Bar when Keyboard is shown in UIKit | Sarunw](https://sarunw.com/posts/hide-navigation-bar-when-keyboard-appears) — 2023-03-13
  **NeKI brief:** Observes keyboard notifications and adjusts UIKit navigation-bar visibility while text input is active. The workflow must restore state on every keyboard transition and account for interactive dismissal to avoid leaving bars hidden.
- [Swift fileprivate vs private | Sarunw](https://sarunw.com/posts/swift-fileprivate-vs-private) — 2023-03-09
  **NeKI brief:** Compares Swift's private and fileprivate scopes with concrete type-extension examples. The choice is an encapsulation trade-off: private preserves tighter invariants across files, while fileprivate can support intentionally split implementation details.
- [How to add Launch Screen in SwiftUI | Sarunw](https://sarunw.com/posts/launch-screen-using-plist) — 2023-03-08
  **NeKI brief:** Explains the SwiftUI project's plist-based launch screen setup and the keys that describe its static appearance. It is useful during storyboard removal, with the important constraint that launch configuration cannot perform dynamic application work.
- [How to whitelist files in .gitignore | Sarunw](https://sarunw.com/posts/whitelist-in-gitignore) — 2023-03-07
  **NeKI brief:** Shows negation patterns in .gitignore for re-including a file beneath an ignored directory. The ordering detail is crucial: parent directories must be traversable, otherwise an apparently correct whitelist rule never reaches Git.
- [How to Deprecate old API in Swift | Sarunw](https://sarunw.com/posts/deprecate-old-api-in-swift) — 2023-03-06
  **NeKI brief:** Compares Swift deprecation annotations and message/renamed metadata for evolving APIs. Good annotations guide callers toward replacements at compile time, while staged deprecation avoids abruptly breaking downstream clients.
- [How to Play Haptic Feedback or Vibrate using UIFeedbackGenerator | Sarunw](https://sarunw.com/posts/play-haptic-feedback-using-uifeedbackgenerator) — 2023-03-02
  **NeKI brief:** Uses UIFeedbackGenerator subclasses for selection, impact, and notification haptics, matching feedback type to interaction meaning. Generators provide system-tuned output, but should be prepared and triggered sparingly so feedback reinforces rather than distracts.
- [How to change Command + Click behavior in Xcode | Sarunw](https://sarunw.com/posts/xcode-command-click-behavior) — 2023-03-01
  **NeKI brief:** Configures Xcode's Command-click behavior to control whether symbols open definitions, documentation, or related navigation. This small workflow adjustment reduces accidental context switches during code review and source exploration.
- [How to Run code in Release build in Xcode | Sarunw](https://sarunw.com/posts/run-code-in-release-build-in-xcode) — 2023-02-28
  **NeKI brief:** Runs an app with Xcode's Release configuration to expose optimization-only behavior and performance characteristics. Release diagnostics complement Debug testing, but stripped assertions and instrumentation mean failures need deliberate logging or profiling.
- [How to Hide Navigation Bar on Scroll in UIKit | Sarunw](https://sarunw.com/posts/hide-navigation-bar-on-scroll-in-uikit) — 2023-02-27
  **NeKI brief:** Hides a UIKit navigation bar in response to scroll direction, recovering vertical content space. A robust implementation needs thresholds and state tracking so bounce and tiny deltas do not cause visible bar flicker.
- [Allow users to manage In-App Subscription in SwiftUI | Sarunw](https://sarunw.com/posts/manage-in-app-subscription-in-swiftui) — 2023-02-23
  **NeKI brief:** Presents Apple's subscription-management sheet from SwiftUI, delegating account changes to the system rather than building custom billing UI. Availability and entitlement refresh still belong in the app's StoreKit state pipeline.
- [Swift In-Out (inout) Parameters | Sarunw](https://sarunw.com/posts/swift-inout-parameter) — 2023-02-22
  **NeKI brief:** Explains inout as exclusive, temporary access to a caller's storage, including copy-in/copy-out and exclusivity constraints. It is useful for mutation helpers, but reference types or return values may express ownership more clearly.
- [How to remove Back button title in SwiftUI | Sarunw](https://sarunw.com/posts/remove-back-button-title-in-swiftui) — 2023-02-21
  **NeKI brief:** Removes a SwiftUI back-button title while retaining the navigation affordance and its system action. The visual cleanup should preserve an accessible label and avoid globally changing navigation semantics for unrelated screens.
- [How to fix "No exact matches in call to initializer" error in Swift | Sarunw](https://sarunw.com/posts/how-to-fix-no-exact-matches-in-call-to-initializer) — 2023-02-20
  **NeKI brief:** Diagnoses Swift's no-exact-matches initializer error by checking argument labels, inferred types, and available overloads. The workflow favors reading the compiler's candidate mismatch before adding casts that could conceal the real API contract.
- [4 Picker styles in SwiftUI Form | Sarunw](https://sarunw.com/posts/swiftui-form-picker-styles) — 2023-02-18
  **NeKI brief:** Compares Picker styles inside SwiftUI Form so the same selection model can adopt platform-appropriate presentation. Style choice affects discoverability and space usage; test the rendered control on each target platform.
- [What's new in Xcode 14.3 and iOS 16.4 | Sarunw](https://sarunw.com/posts/whats-new-in-xcode-14_3-and-ios-16_4) — 2023-02-17
  **NeKI brief:** Summarizes Xcode 14.3 and iOS 16.4 changes relevant to SwiftUI development. Useful as a versioned route into SDK additions and toolchain behavior when maintaining older deployment targets.
- [SwiftUI ProgressView | Sarunw](https://sarunw.com/posts/swiftui-progressview) — 2023-02-16
  **NeKI brief:** Introduces determinate and indeterminate ProgressView forms, clarifying when progress can communicate measurable completion versus ongoing work. Feeding inaccurate fractions is worse than using an indeterminate indicator because it creates false expectations.
- [Computed property vs Method: Which one to use | Sarunw](https://sarunw.com/posts/computed-property-vs-method) — 2023-02-15
  **NeKI brief:** Compares a read-only computed property with a method returning the same value, focusing on API intent and call-site semantics. Properties suit cheap, noun-like derived state; methods better signal work or side effects.
- [SwiftUI TabView | Sarunw](https://sarunw.com/posts/swiftui-tabview) — 2023-02-14
  **NeKI brief:** Builds tab navigation with SwiftUI TabView and selection state, showing how tags connect content to a typed selection. Keep tab identity stable so switching tabs does not discard each child view's state unexpectedly.
- [Timer in SwiftUI | Sarunw](https://sarunw.com/posts/timer-in-swiftui) — 2023-02-13
  **NeKI brief:** Explains periodic SwiftUI work with Timer.publish and onReceive, including main-run-loop scheduling and autoconnect. Cancellation stops the upstream connection; resuming requires recreating the published timer, typically by storing it in State.
- [Swift Ternary operator (?:) | Sarunw](https://sarunw.com/posts/swift-ternary-operator) — 2023-02-09
  **NeKI brief:** Uses Swift's ternary expression for compact value selection while noting its readability boundary. It works best for short, side-effect-free branches; nested conditions should become explicit control flow or a named computation.
- [What is SwiftUI Form | Sarunw](https://sarunw.com/posts/swiftui-form) — 2023-02-08
  **NeKI brief:** Explains Form's platform styling and behavior relative to List, helping choose the semantic container when controls need settings-oriented grouping.
- [Swift private access level change in Swift 4 | Sarunw](https://sarunw.com/posts/swift-private-access-level-change) — 2023-02-07
  **NeKI brief:** Swift 4's `private` scope changed from file-based to lexical, so extensions in the same file may no longer share members automatically. The migration choice is between narrower encapsulation and `fileprivate` for intentional file-wide collaboration.
- [Easy way to Format Date in SwiftUI Text | Sarunw](https://sarunw.com/posts/swiftui-text-date-format) — 2023-02-06
  **NeKI brief:** Uses SwiftUI Text date initializers to delegate locale-aware formatting, avoiding manual DateFormatter strings when the display requirement matches system styles.
- [Adding and Removing Swift Package dependencies in Xcode | Sarunw](https://sarunw.com/posts/managing-swift-package-in-xcode) — 2023-02-02
  **NeKI brief:** Adds and removes Swift Package dependencies in Xcode, emphasizing package identity and target linkage so dependency changes remain reviewable.
- [SwiftUI Checkbox | Sarunw](https://sarunw.com/posts/swiftui-checkbox) — 2023-02-01
  **NeKI brief:** Builds a checkbox-style SwiftUI control, illustrating how visual state, accessibility value, and toggle semantics should remain aligned across input methods.
- [What is Info.plist in Xcode | Sarunw](https://sarunw.com/posts/what-is-info-plist) — 2023-01-31
  **NeKI brief:** Explains Info.plist's role and location, helping diagnose configuration issues by distinguishing generated build settings from source-controlled project metadata.
- [How to use SwiftUI as UIView in Storyboard | Sarunw](https://sarunw.com/posts/swiftui-view-as-uiview-in-storyboard) — 2023-01-30
  **NeKI brief:** Wraps a SwiftUI view for storyboard UIKit integration, preserving UIKit ownership while establishing a narrow hosting boundary for incremental migration.
- [How to Pop to the Root view in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-pop-to-root-view-in-swiftui) — 2023-01-28
  **NeKI brief:** Uses NavigationPath mutation to pop SwiftUI navigation to root, replacing imperative controller traversal with explicit route-state ownership and predictable restoration.
- [How to remove duplicate items from Array in Swift | Sarunw](https://sarunw.com/posts/remove-duplicate-items-from-array-in-swift) — 2023-01-26
  **NeKI brief:** Compares order-preserving duplicate removal with Swift Algorithms, making the trade-off between Hashable constraints, clarity, and dependency choice explicit.
- [How to manage Safe Area insets in Flutter | Sarunw](https://sarunw.com/posts/flutter-safe-area) — 2023-01-25
  **NeKI brief:** Safe-area insets describe where system UI can obscure Flutter content, so padding should derive from the framework's inset value rather than fixed device constants. This keeps layouts resilient across notches and system bars.
- [Custom Back button Action in SwiftUI | Sarunw](https://sarunw.com/posts/custom-back-button-action-in-swiftui) — 2023-01-24
  **NeKI brief:** Implements custom back behavior while preserving navigation semantics, highlighting when toolbar replacement must also account for accessibility and interactive dismissal.
- [How to use SwiftUI in Storyboard using UIHostingController subclass | Sarunw](https://sarunw.com/posts/swiftui-view-in-uikit-using-uihostingcontroller-subclass) — 2023-01-23
  **NeKI brief:** Shows a custom UIHostingController subclass for placing SwiftUI in storyboard positions where IBSegueAction is unavailable, such as an initial controller, navigation root, or tab. The subclass fixes its generic root view and implements init(coder:).
- [How to use SwiftUI as UIViewController in Storyboard | Sarunw](https://sarunw.com/posts/swiftui-view-as-uiviewcontroller-in-storyboard) — 2023-01-19
  **NeKI brief:** Embedding a SwiftUI view in a storyboard uses a hosting controller as the UIKit lifecycle boundary. The pattern preserves storyboard navigation while making environment injection and size negotiation explicit at the bridge.
- [How to change Background color of Rounded Corner Border Button in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-bordered-button-background-color) — 2023-01-18
  **NeKI brief:** Combines background and border modifiers for a SwiftUI button, clarifying modifier order when shape clipping and stroke rendering otherwise produce surprises.
- [Where is Info.plist in Xcode 13 | Sarunw](https://sarunw.com/posts/where-is-info-plist) — 2023-01-17
  **NeKI brief:** Modern Xcode projects can generate Info.plist content from target settings, so a physical file may be absent while the app still receives a built plist. The distinction matters when diagnosing bundle metadata or migration scripts.
- [What is Swift Guard Case | Sarunw](https://sarunw.com/posts/swift-guard-case) — 2023-01-16
  **NeKI brief:** Uses guard-case to validate one enum case early, reducing nested switching when a function has a single required state and a clear failure path.
- [Using SwiftUI in UIKit as UIView | Sarunw](https://sarunw.com/posts/swiftui-view-as-uiview) — 2023-01-12
  **NeKI brief:** A `UIHostingController` can expose SwiftUI content to UIKit, while `UIHostingConfiguration` offers a lighter cell-oriented path on newer systems. The choice depends on lifecycle ownership, sizing, and deployment targets.
- [How to Hide Navigation bar in SwiftUI | Sarunw](https://sarunw.com/posts/hide-navigation-bar-in-swiftui) — 2023-01-11
  **NeKI brief:** Explains hiding SwiftUI navigation bars per destination. Older code uses navigationBarHidden; iOS 16 replaces it with toolbar(.hidden, for: .navigationBar). The modifier belongs on the content view, and pushed destinations need their own policy.
- [Splash screen vs Launch screen in iOS | Sarunw](https://sarunw.com/posts/splash-screen-vs-launch-screen) — 2023-01-10
  **NeKI brief:** A launch screen is a system-controlled snapshot shown while the app starts, whereas a splash screen is app content shown after launch. Keeping them separate avoids delaying readiness with branding animation.
- [How to Disable and Enable Button in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-button-disable) — 2023-01-09
  **NeKI brief:** Controls SwiftUI button disabled state declaratively, ensuring the same condition drives both interaction availability and the visual affordance.
- [How to Save and Read Array in UserDefaults in Swift | Sarunw](https://sarunw.com/posts/how-to-save-array-in-userdefaults) — 2023-01-05
  **NeKI brief:** Persists Codable arrays in UserDefaults for small settings data, while making the size and security boundary clear before choosing a database.
- [Using SwiftUI in UIKit as UIViewController | Sarunw](https://sarunw.com/posts/swiftui-view-as-uiviewcontroller) — 2023-01-04
  **NeKI brief:** Hosts SwiftUI inside a UIViewController, useful for UIKit coordinators that need lifecycle and presentation control around a declarative child view.
- [Enable and Disable SwiftUI List rows reordering on a specific row | Sarunw](https://sarunw.com/posts/swiftui-list-move-disabled) — 2023-01-02
  **NeKI brief:** Restricts List row reordering to eligible items, showing how onMove validation can enforce domain rules instead of trusting gesture position alone.
- [Unwrap Swift optional value in Switch case | Sarunw](https://sarunw.com/posts/optional-binding-switch-case) — 2023-01-01
  **NeKI brief:** Combines optional binding with switch cases to unwrap values at the branch boundary, keeping success and nil handling explicit without force casts.
- [How to change Background Color of Button in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-button-background-color) — 2022-12-29
  **NeKI brief:** SwiftUI button backgrounds interact with button styles, labels, and hit testing; styling the label alone may not fill the tappable region. The examples show where modifiers belong to preserve both appearance and accessibility.
- [How to join an Array of strings into a Single string in Swift | Sarunw](https://sarunw.com/posts/how-to-join-array-of-strings-into-single-string) — 2022-12-28
  **NeKI brief:** Joins Swift string arrays with separator-aware APIs, avoiding manual accumulation and making empty-array behavior explicit in formatting code.
- [Enable and Disable SwiftUI List rows deletion on a specific row | Sarunw](https://sarunw.com/posts/swiftui-list-delete-disabled) — 2022-12-26
  **NeKI brief:** `onDelete` applies to list rows broadly, so disabling deletion for selected items requires filtering the edit action or conditionally exposing the handler. The approach keeps destructive policy in the data model rather than relying on row visuals.
- [How to change SwiftUI Button Size | Sarunw](https://sarunw.com/posts/swiftui-button-size) — 2022-12-22
  **NeKI brief:** Controls SwiftUI button sizing through labels, frames, and styles, clarifying which layer should own hit-target expansion versus visual dimensions.
- [How to check if an Element is in an Array in Swift | Sarunw](https://sarunw.com/posts/swift-array-contains) — 2022-12-21
  **NeKI brief:** Compares Swift collection membership checks, making the trade-off between readable contains calls and predicate-based searches explicit for common data types.
- [How to remove the Last row separator in SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-remove-last-separator) — 2022-12-19
  **NeKI brief:** Hides a specific SwiftUI List separator while preserving other rows, showing how list styling scope affects the resulting layout.
- [What is Swift Computed Property | Sarunw](https://sarunw.com/posts/swift-computed-property) — 2022-12-15
  **NeKI brief:** Contrasts stored and computed Swift properties, clarifying when derived values should remain recalculated instead of persisted state for correctness.
- [How to make Swift Enum conforms to Identifiable protocol | Sarunw](https://sarunw.com/posts/swift-enum-identifiable) — 2022-12-14
  **NeKI brief:** Makes enum cases Identifiable for SwiftUI collections, choosing stable identity so list diffing does not reset row state.
- [What is the difference between #available and @available | Sarunw](https://sarunw.com/posts/available-vs-available) — 2022-12-13
  **NeKI brief:** Distinguishes runtime #available checks from declaration-level @available annotations, helping place deployment compatibility at the correct API boundary and avoid redundant guards.
- [How to Reorder List rows in SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-onmove) — 2022-12-12
  **NeKI brief:** SwiftUI's `onMove` supplies source and destination offsets for reordering a mutable collection, leaving persistence and validation to the model. The article clarifies how edit mode and stable identity affect the interaction.
- [Swift mod operator (%) | Sarunw](https://sarunw.com/posts/swift-mod) — 2022-12-08
  **NeKI brief:** Explains Swift's remainder operator and sign behavior, preventing incorrect assumptions when formatting indices or calculating cyclic values in algorithms.
- [What is Button Role in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-button-role) — 2022-12-07
  **NeKI brief:** Button roles communicate intent such as destructive or cancellation actions to SwiftUI, allowing platform styles and accessibility surfaces to adapt. Assigning the role at the action boundary is clearer than styling danger colors manually.
- [How to declare Multiline String in Swift | Sarunw](https://sarunw.com/posts/swift-multiline-string) — 2022-12-06
  **NeKI brief:** Uses multiline string literals for readable embedded text, preserving indentation and avoiding fragile concatenation across source lines and localized content.
- [How to change Status Bar text color in SwiftUI | Sarunw](https://sarunw.com/posts/change-status-bar-text-color-in-swiftui) — 2022-12-05
  **NeKI brief:** Changes status-bar appearance from SwiftUI while accounting for UIKit hosting boundaries, color-scheme behavior, and the controller that owns presentation style.
- [How to Delete List rows from SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-ondelete) — 2022-12-01
  **NeKI brief:** Adds row deletion to SwiftUI List, making mutation ownership explicit and keeping the data source authoritative during updates and persistence.
- [What is Swift If Case | Sarunw](https://sarunw.com/posts/swift-if-case) — 2022-11-30
  **NeKI brief:** `if case` matches one enum case while binding its associated value, avoiding a temporary switch when only one path matters. The syntax keeps optional and state checks concise without weakening exhaustive handling elsewhere.
- [SwiftUI Button Style Examples | Sarunw](https://sarunw.com/posts/swiftui-button-style-examples) — 2022-11-29
  **NeKI brief:** Compares SwiftUI button styles, showing how semantic roles and platform interaction states should survive visual customization across appearances and devices.
- [How to fix "The compiler is unable to type-check this expression in reasonable time" error | Sarunw](https://sarunw.com/posts/how-to-fix-the-compiler-is-unable-to-type-check-this-expression-in-reasonable-time) — 2022-11-28
  **NeKI brief:** Swift type-checking timeouts often come from deeply composed expressions and overloaded inference. Breaking a view or expression into typed intermediate values gives the compiler smaller constraints and makes the true ambiguity observable.
- [SwiftUI Dynamic List View | Sarunw](https://sarunw.com/posts/swiftui-dynamic-list) — 2022-11-24
  **NeKI brief:** Builds a dynamic SwiftUI List from collection data, emphasizing stable identity so inserts and deletes animate predictably during updates.
- [How to make parts of Text view Bold in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-text-mixed-styles) — 2022-11-23
  **NeKI brief:** Combines styled Text segments in SwiftUI, preserving one accessible text flow instead of assembling unrelated labels with separate semantics.
- [How to fix preferredStatusBarStyle not getting called | Sarunw](https://sarunw.com/posts/preferredstatusbarstyle-not-getting-called) — 2022-11-22
  **NeKI brief:** Diagnoses preferredStatusBarStyle not being called, tracing container ownership and appearance forwarding instead of changing unrelated view code or global styling.
- [How to change SwiftUI List section separator color | Sarunw](https://sarunw.com/posts/swiftui-list-section-separator-color) — 2022-11-21
  **NeKI brief:** Customizes section separator color while keeping list styling scoped, avoiding global appearance changes that leak into unrelated screens.
- [How to remove List Section separators in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-list-section-separator-visibility) — 2022-11-19
  **NeKI brief:** Controls SwiftUI section separator visibility declaratively, preserving platform list behavior instead of overlaying custom divider views and breaking accessibility.
- [Multiple rows Selection in SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-multiple-selection) — 2022-11-17
  **NeKI brief:** Supports multiple List selection in SwiftUI, tying selection state to edit-mode and platform behavior rather than custom gesture tracking code.
- [SwiftUI Button: Basic usage | Sarunw](https://sarunw.com/posts/swiftui-button-basic) — 2022-11-16
  **NeKI brief:** Builds a semantic SwiftUI Button, keeping action ownership and label content separate for accessibility, testing, styling, and predictable interaction.
- [How to make equal height subviews in HStack | Sarunw](https://sarunw.com/posts/swiftui-equal-height-hstack) — 2022-11-15
  **NeKI brief:** Equalizes HStack child heights through shared layout constraints, avoiding fixed dimensions that break with dynamic content and localization.
- [How to make a Horizontal List in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-horizontal-list) — 2022-11-14
  **NeKI brief:** Builds a horizontal SwiftUI list, choosing scroll direction and item sizing explicitly instead of rotating a vertical list for convenience.
- [How to find a font name of a custom font in iOS | Sarunw](https://sarunw.com/posts/how-to-find-font-name-in-ios) — 2022-11-12
  **NeKI brief:** Finds a font's PostScript name for iOS registration, avoiding silent fallback when custom font files use different display names.
- [Supporting SwiftUI List Selection | Sarunw](https://sarunw.com/posts/swiftui-list-selection) — 2022-11-10
  **NeKI brief:** Preserves SwiftUI List selection across navigation, keeping selection state separate from row presentation and data mutation during updates.
- [How to change Status Bar text color in iOS | Sarunw](https://sarunw.com/posts/change-status-bar-text-color-in-uikit) — 2022-11-09
  **NeKI brief:** Changes UIKit status-bar text appearance through the owning controller, clarifying why child views alone may not receive style callbacks.
- [Create SwiftUI List from an Array | Sarunw](https://sarunw.com/posts/swiftui-list-from-array) — 2022-11-08
  **NeKI brief:** Creates a SwiftUI List from array data, emphasizing stable Identifiable values so row updates do not reset interaction state.
- [How to dismiss fullScreenCover in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-dismiss-fullscreencover) — 2022-11-07
  **NeKI brief:** Dismisses fullScreenCover through SwiftUI presentation state, avoiding parent view mutation and preserving the modal ownership boundary for every presentation path.
- [How to use custom fonts with SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-custom-font) — 2022-11-05
  **NeKI brief:** Registers and applies custom fonts in SwiftUI, distinguishing file registration from the PostScript name used by Font.custom at runtime.
- [What is the difference between List and ForEach in SwiftUI | Sarunw](https://sarunw.com/posts/difference-between-list-foreach) — 2022-11-03
  **NeKI brief:** Contrasts List with ForEach, clarifying that List supplies container behavior while ForEach only repeats child view construction for a collection.
- [Should we manually call @StateObject initializer | Sarunw](https://sarunw.com/posts/manually-initialize-stateobject) — 2022-11-02
  **NeKI brief:** Examines manual StateObject initialization, clarifying that stable ownership and initialization timing matter more than recreating injected inputs on render.
- [@State variable initialization in SwiftUI | Sarunw](https://sarunw.com/posts/state-variable-initialization) — 2022-11-01
  **NeKI brief:** Explains State initialization semantics in SwiftUI, preventing callers from assuming later input changes overwrite view-owned state during body updates.
- [How to change List Row separator color in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-list-row-separator-color) — 2022-10-31
  **NeKI brief:** Customizes row separator color at the List-row scope, avoiding broad appearance changes that affect unrelated list screens throughout the app.
- [How to Get Push Notification while iOS App is in Foreground | Sarunw](https://sarunw.com/posts/notification-in-foreground) — 2022-10-30
  **NeKI brief:** Handles foreground notifications through the notification-center delegate, explicitly choosing whether alerts, sounds, or badges remain visible to the current user.
- [How to remove the SwiftUI List Row separators | Sarunw](https://sarunw.com/posts/swiftui-list-row-separator-visibility) — 2022-10-28
  **NeKI brief:** Controls SwiftUI row separator visibility declaratively, retaining list semantics rather than covering separators with custom backgrounds or overlays.
- [Using ForEach in SwiftUI List | Sarunw](https://sarunw.com/posts/swiftui-list-with-foreach) — 2022-10-27
  **NeKI brief:** Uses ForEach inside List when repeated rows need a separate identity or grouping boundary, keeping collection logic explicit.
- [Disable scrolling in SwiftUI ScrollView and List | Sarunw](https://sarunw.com/posts/disable-scrolling-swiftui) — 2022-10-26
  **NeKI brief:** Disables scrolling through SwiftUI's scrollDisabled modifier, retaining the platform scroll container instead of intercepting gestures manually in parent views.
- [How to show badge on List Row in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-list-row-badge) — 2022-10-25
  **NeKI brief:** Adds badges to SwiftUI List rows, making count or status metadata visible while keeping row navigation semantics unchanged.
- [How to change a Tab Bar item color in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-tabbaritem-color) — 2022-10-24
  **NeKI brief:** Configures SwiftUI tab-item tint, separating selected-item appearance from global color changes that affect unrelated controls and navigation elements.
- [How to Upload dSYM to Firebase using upload_symbols_to_crashlytics and SPM | Sarunw](https://sarunw.com/posts/upload-dsym-to-firebase-with-fastlane) — 2022-10-23
  **NeKI brief:** Uploads dSYM files to Firebase Crashlytics with Fastlane and SPM, preserving symbolication when Xcode build artifacts change across release configurations.
- [Set SwiftUI app theme with AccentColor | Sarunw](https://sarunw.com/posts/swiftui-accentcolor) — 2022-10-22
  **NeKI brief:** Sets an app AccentColor for consistent SwiftUI theming, while recognizing semantic tint should still adapt to context and accessibility.
- [How to scale margin and padding with @ScaledMetric Property Wrapper | Sarunw](https://sarunw.com/posts/swiftui-scaledmetric) — 2022-10-20
  **NeKI brief:** Uses SwiftUI's @ScaledMetric to scale padding and margins with Dynamic Type instead of changing fonts alone. The technique helps preserve readable spacing when accessibility sizes turn otherwise fixed layouts into collisions or clipping.
- [Missing dSYM download link in App Store Connect | Sarunw](https://sarunw.com/posts/app-store-connect-download-dsym) — 2022-10-19
  **NeKI brief:** Explains the missing dSYM download path in App Store Connect, directing symbolication workflows toward archived build artifacts and automated uploads.
- [Building Static List in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-static-list) — 2022-10-18
  **NeKI brief:** Builds a static SwiftUI List for fixed settings content, using sections and rows without inventing a backing collection.
- [How to use Non Uppercase in SwiftUI List section header | Sarunw](https://sarunw.com/posts/swiftui-list-section-header-textcase) — 2022-10-17
  **NeKI brief:** Controls List section-header text case, preserving product terminology when platform default capitalization conflicts with labels and accessibility wording.
- [How to adjust List row separator insets in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-list-row-separator-insets) — 2022-10-16
  **NeKI brief:** Adjusts SwiftUI List separator insets through alignment configuration, preserving list semantics while aligning rows with custom content margins.
- [How to remove nil elements from an array in Swift | Sarunw](https://sarunw.com/posts/swift-remove-nil-elements-from-array) — 2022-10-15
  **NeKI brief:** Removes nil array elements with compactMap, preserving nonoptional values without force unwrapping, manual index mutation, or temporary storage.
- [How to change TabView color in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-tabview-color) — 2022-10-13
  **NeKI brief:** Changes TabView colors using current SwiftUI APIs, separating tab-bar background treatment from selected-item tint configuration and accessibility contrast.
- [How to show badge on Tab Bar Item in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-tabbar-badge) — 2022-10-12
  **NeKI brief:** Adds tab-bar badges in SwiftUI, exposing changing counts without replacing tab navigation or maintaining custom overlay views for each destination.
- [SwiftUI List Style examples | Sarunw](https://sarunw.com/posts/swiftui-list-style) — 2022-10-11
  **NeKI brief:** Compares SwiftUI List styles, helping choose platform-appropriate grouping and navigation presentation without custom table-view styling for every screen.
- [How to dismiss sheet in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-dismiss-sheet) — 2022-10-10
  **NeKI brief:** Dismisses a SwiftUI sheet through presentation state, preserving modal ownership instead of reaching into parent navigation state or changing unrelated routes.
- [How to scale custom fonts with Dynamic Type in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-scale-custom-font-dynamic-type) — 2022-10-08
  **NeKI brief:** Shows how custom SwiftUI fonts can participate in Dynamic Type through relative text styles and scaling. It is useful when branding requires a custom face but accessibility settings must still control the rendered size.
- [How to add Keyboard Shortcuts in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-keyboard-shortcuts) — 2022-10-06
  **NeKI brief:** Adds keyboard shortcuts in SwiftUI, connecting command keys to semantic actions across iPad and macOS without manual key-event routing.
- [How to change SwiftUI Font Width | Sarunw](https://sarunw.com/posts/swiftui-font-width) — 2022-10-04
  **NeKI brief:** Adjusts SwiftUI font width with modern typography APIs, preserving text style semantics while fitting constrained layouts and Dynamic Type.
- [How to create Rounded Corners View in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-rounded-corners-view) — 2022-10-03
  **NeKI brief:** Creates rounded SwiftUI views with shape clipping, clarifying how background, stroke, and hit testing interact at corners during layout.
- [How to use UIView in SwiftUI | Sarunw](https://sarunw.com/posts/uiview-in-swiftui) — 2022-09-29
  **NeKI brief:** Wraps a UIKit UIView for SwiftUI, keeping update logic in UIViewRepresentable instead of leaking UIKit lifecycle code into parent views.
- [How to create Rounded Corners Button in UIKit | Sarunw](https://sarunw.com/posts/uikit-rounded-corners-button) — 2022-09-26
  **NeKI brief:** Creates rounded UIKit buttons with layer-backed styling, accounting for control state, dynamic content, and minimum deployment differences across supported systems.
- [How to check if String is Number in Swift | Sarunw](https://sarunw.com/posts/how-to-check-if-string-is-number-in-swift) — 2022-09-24
  **NeKI brief:** Checks whether Swift strings represent numbers, distinguishing parsing success from broader validation rules such as locale, signs, or decimals.
- [viewDidLoad() in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-viewdidload) — 2022-09-22
  **NeKI brief:** Explains why SwiftUI lacks viewDidLoad, using lifecycle-aware callbacks without assuming a view's body creation is a one-time event.
- [For loop in SwiftUI using ForEach | Sarunw](https://sarunw.com/posts/swiftui-foreach) — 2022-09-21
  **NeKI brief:** Uses ForEach to generate repeated SwiftUI content, assigning stable identities so diffing preserves row state across data updates.
- [How to get index and value from for loop in Swift | Sarunw](https://sarunw.com/posts/swift-for-loop-with-index) — 2022-09-20
  **NeKI brief:** Retrieves indexes alongside values in Swift iteration, avoiding unsafe integer assumptions when collections use nonzero or custom indices.
- [SwiftUI zIndex: Everything you need to know | Sarunw](https://sarunw.com/posts/swiftui-zindex) — 2022-09-19
  **NeKI brief:** Uses zIndex to control overlapping SwiftUI views, making draw order explicit without restructuring the view hierarchy or relying on modifier accident.
- [How to Show/hide whitespace characters in Xcode | Sarunw](https://sarunw.com/posts/how-to-show-hide-whitespace-in-xcode) — 2022-09-17
  **NeKI brief:** Shows invisible whitespace in Xcode, providing a lightweight diagnostic for indentation, trailing spaces, and formatting-sensitive source changes during reviews.
- [SwiftUI List: Basic usage | Sarunw](https://sarunw.com/posts/swiftui-list-basic) — 2022-09-15
  **NeKI brief:** Introduces SwiftUI List as a semantic scrolling container, separating row identity and content construction from table-style behavior across platforms.
- [How to use UIViewController in SwiftUI | Sarunw](https://sarunw.com/posts/uiviewcontroller-in-swiftui) — 2022-09-12
  **NeKI brief:** Embeds a UIKit view controller in SwiftUI with UIViewControllerRepresentable, retaining controller lifecycle and delegate boundaries during incremental migration work.
- [How to add button to navigation bar in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-add-button-to-navigation-bar-in-swiftui) — 2022-09-10
  **NeKI brief:** Adds navigation-bar buttons through SwiftUI toolbar placement, preserving adaptive platform layout instead of manually overlaying controls within screen content.
- [SF Font Expanded, Condensed, and Compressed: Three New font width styles in iOS 16 | Sarunw](https://sarunw.com/posts/sf-font-width-styles) — 2022-09-08
  **NeKI brief:** Explains SF font width styles such as expanded and condensed. Use it when fitting text density while preserving the system typeface and Dynamic Type behavior.
- [How to use UIFont in SwiftUI Font | Sarunw](https://sarunw.com/posts/uifont-to-font) — 2022-09-06
  **NeKI brief:** Bridges UIFont into SwiftUI Font, retaining UIKit typography choices when migrating a design system incrementally across existing screens.
- [How to make SwiftUI button with buttonStyle expand to full width | Sarunw](https://sarunw.com/posts/swiftui-button-style-width) — 2022-09-05
  **NeKI brief:** Expands a button styled with ButtonStyle to full width, separating hit-target layout from the style's visual treatment and semantic role.
- [Loop n times in Swift | Sarunw](https://sarunw.com/posts/swift-loop-n-times) — 2022-09-03
  **NeKI brief:** Repeats Swift work a fixed number of times, choosing an explicit range so iteration count and zero-case behavior remain readable.
- [SwiftUI AnyLayout - smooth transitions between layout types | Sarunw](https://sarunw.com/posts/swiftui-anylayout) — 2022-09-01
  **NeKI brief:** Uses AnyLayout to transition between SwiftUI layout types, preserving child identity while adapting composition to available space and size-class changes.
- [How to capitalize the first letter in Swift | Sarunw](https://sarunw.com/posts/how-to-capitalize-the-first-letter-in-swift) — 2022-08-27
  **NeKI brief:** Capitalizes Swift strings with explicit Unicode-aware transformations, keeping display formatting distinct from locale-sensitive user-content rules and avoiding unsafe character indexing.
- [SwiftUI Gauge | Sarunw](https://sarunw.com/posts/swiftui-gauge) — 2022-08-25
  **NeKI brief:** Uses SwiftUI Gauge for ranged values, selecting gauge styles that communicate progress or measurements without custom drawing code.
- [How to save enum with associated value in UserDefaults using Swift | Sarunw](https://sarunw.com/posts/how-to-save-enum-associated-value-in-userdefaults-using-swift) — 2022-08-22
  **NeKI brief:** Persists enums with associated values in UserDefaults through Codable representation, keeping serialization stable as enum cases evolve over future releases.
- [Custom Layout in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-custom-layout) — 2022-08-18
  **NeKI brief:** Builds a custom SwiftUI Layout, controlling measurement and placement when stacks cannot express the required container behavior and alignment.
- [How to save enum in UserDefaults using Swift | Sarunw](https://sarunw.com/posts/how-to-save-enum-in-userdefaults-using-swift) — 2022-08-15
  **NeKI brief:** Stores simple Swift enums in UserDefaults using raw values, keeping persistence format explicit and recoverable when values are absent.
- [Responsive layout in SwiftUI with ViewThatFit | Sarunw](https://sarunw.com/posts/swiftui-viewthatfits) — 2022-08-11
  **NeKI brief:** Uses ViewThatFits for responsive SwiftUI composition, ordering alternatives so compact layouts are selected only when necessary across changing container sizes.
- [What is the fixedSize modifier in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-fixedsize) — 2022-08-08
  **NeKI brief:** Explains fixedSize in SwiftUI, clarifying how intrinsic content can resist parent compression and alter surrounding layout proposals across containers.
- [How to change a navigation bar color in SwiftUI on iOS 16 | Sarunw](https://sarunw.com/posts/swiftui-navigation-bar-color) — 2022-08-04
  **NeKI brief:** Changes navigation-bar color using current SwiftUI appearance APIs, keeping toolbar styling scoped to the owning navigation hierarchy and scene.
- [Improve numbers readability with underscores | Sarunw](https://sarunw.com/posts/numeric-literals-extra-formatting) — 2022-08-01
  **NeKI brief:** Uses underscore-separated numeric literals to improve source readability, retaining the same numeric value while making large constants auditable.
- [Move the most recent commits to a new branch with git | Sarunw](https://sarunw.com/posts/move-commits-to-new-branch-in-git) — 2022-07-28
  **NeKI brief:** Moves recent commits onto a new Git branch, preserving shared history while correcting an accidental branch choice without rewriting collaborators' work.
- [Variable Color in SF Symbols 4 | Sarunw](https://sarunw.com/posts/sf-symbols-variable-color) — 2022-07-25
  **NeKI brief:** Uses SF Symbols variable color rendering, choosing hierarchical layers that communicate state without shipping custom colored artwork or separate image assets.
- [Hide keyboard when scrolling in SwiftUI with scrollDismissesKeyboard | Sarunw](https://sarunw.com/posts/swiftui-scrolldismisseskeyboard) — 2022-07-21
  **NeKI brief:** Uses scrollDismissesKeyboard to control keyboard dismissal while scrolling, preserving system gesture behavior instead of custom responder management in every scroll view.
- [Bottom Sheet in SwiftUI on iOS 16 with presentationDetents modifier | Sarunw](https://sarunw.com/posts/swiftui-bottom-sheet) — 2022-07-18
  **NeKI brief:** Builds an iOS 16 SwiftUI bottom sheet with presentationDetents, choosing supported heights without hand-rolled drag interactions or custom geometry.
- [New way to control number of lines of SwiftUI Text in iOS 16 | Sarunw](https://sarunw.com/posts/swiftui-text-linelimit) — 2022-07-14
  **NeKI brief:** Controls SwiftUI Text line limits with modern APIs, distinguishing truncation behavior from minimum reserved line space for variable content.
- [UIPasteBoard's privacy change in iOS 16 | Sarunw](https://sarunw.com/posts/uipasteboard-privacy-change-ios16) — 2022-07-11
  **NeKI brief:** Explains UIPasteboard privacy changes in iOS 16, helping apps avoid unexpected paste prompts through deliberate clipboard access and user actions.
- [Better way to get paths to system directories in iOS 16 | Sarunw](https://sarunw.com/posts/url-type-properties) — 2022-07-07
  **NeKI brief:** Uses URL type properties for system directories, replacing fragile string paths with platform-managed file locations and correct sandbox scope.
- [How to change SwiftUI list background color | Sarunw](https://sarunw.com/posts/swiftui-list-background-color) — 2022-07-06
  **NeKI brief:** Changes SwiftUI List background color using list-aware styling, avoiding overlays that break scrolling and grouped appearance behavior across platforms.
- [New if let shorthand for optional binding | Sarunw](https://sarunw.com/posts/if-let-shorthand) — 2022-07-04
  **NeKI brief:** Uses Swift's if-let shorthand for optional binding, reducing repeated variable names while retaining explicit nil control flow in branches.
- [How to change status bar color in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-status-bar-color) — 2022-06-30
  **NeKI brief:** Changes status-bar color in SwiftUI by respecting hosting-controller ownership, separating system-bar appearance from ordinary view background styling and safe areas.
- [How to get AppStore Connect Team ID and Developer Portal Team ID for Fastlane actions | Sarunw](https://sarunw.com/posts/fastlane-find-team-id) — 2022-06-23
  **NeKI brief:** Finds App Store Connect and Developer Portal team identifiers for Fastlane, preventing signing automation from targeting the wrong account.
- [Calendar view in SwiftUI with MultiDatePicker | Sarunw](https://sarunw.com/posts/swiftui-multidatepicker) — 2022-06-20
  **NeKI brief:** Uses MultiDatePicker for calendar-style multi-selection, keeping selected dates as typed state rather than parsing custom calendar controls manually.
- [How to create multiline TextField in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-multiline-textfield) — 2022-06-18
  **NeKI brief:** Creates multiline SwiftUI TextField input, choosing axis and line limits so growing text remains accessible and layout-safe across devices.
- [Create a mac menu bar app in SwiftUI with MenuBarExtra | Sarunw](https://sarunw.com/posts/swiftui-menu-bar-app) — 2022-06-16
  **NeKI brief:** Builds a macOS menu bar app with MenuBarExtra, choosing menu or window presentation without inventing a custom status-item lifecycle.
- [SwiftUI Grid - The complete Guide | Sarunw](https://sarunw.com/posts/swiftui-grid) — 2022-06-13
  **NeKI brief:** Explains SwiftUI Grid layout, distinguishing eager row and column sizing from lazy grid behavior for data-heavy and adaptive content.
- [How to add a TextField to Alert in SwiftUI | Sarunw](https://sarunw.com/posts/swiftui-alert-textfield) — 2022-06-08
  **NeKI brief:** Adds a TextField to a SwiftUI alert, binding user input within the system alert workflow rather than presenting a separate sheet.
- [Little big improvements in Xcode 14 | Sarunw](https://sarunw.com/posts/little-big-improvements-xcode14) — 2022-06-07
  **NeKI brief:** Surveys small Xcode 14 workflow improvements, useful for finding editor and debugging changes without treating the article as current documentation.
- [How to change SwiftUI list row background color | Sarunw](https://sarunw.com/posts/swiftui-list-row-background-color) — 2022-06-06
  **NeKI brief:** Sets a SwiftUI List row background color with row-scoped modifiers, preserving selection and grouped-list behavior across platforms and appearances.
- [CollectionView in SwiftUI with LazyVGrid and LazyHGrid | Sarunw](https://sarunw.com/posts/swiftui-lazyvgrid-lazyhgrid) — 2022-06-02
  **NeKI brief:** Builds collection-style SwiftUI layouts with LazyVGrid and LazyHGrid, balancing lazy rendering against grid sizing and scrolling behavior across content sizes.
- [7 Xcode shortcuts for a large iOS project | Sarunw](https://sarunw.com/posts/xcode-shortcuts-for-navigation) — 2022-05-19
  **NeKI brief:** Use Xcode's navigation shortcuts to open symbols, reveal the current file, filter the project, move through history, jump to lines, and inspect document items. These commands reduce context-switching in large projects without changing source structure.
- [How to add section header and footer to SwiftUI list | Sarunw](https://sarunw.com/posts/swiftui-list-section-header-footer) — 2022-05-16
  **NeKI brief:** Adds SwiftUI List section headers and footers, using semantic grouping instead of manually inserting text rows into collections.
- [Divider in SwiftUI - Everything you need to know | Sarunw](https://sarunw.com/posts/swiftui-divider) — 2022-05-12
  **NeKI brief:** Uses Divider in SwiftUI to express a semantic visual separation, choosing orientation and container placement without hand-drawn lines.
- [How to style SwiftUI text Font | Sarunw](https://sarunw.com/posts/swiftui-text-font) — 2022-05-09
  **NeKI brief:** Styles SwiftUI Text with Font APIs, preserving dynamic type and semantic text roles while applying typography changes consistently across views.
- [How to create SwiftUI circular progress bar | Sarunw](https://sarunw.com/posts/swiftui-circular-progress-bar) — 2022-05-05
  **NeKI brief:** Builds a circular SwiftUI progress indicator, connecting trimmed shape progress to a normalized value and accessible status text.
- [How to change SwiftUI font size | Sarunw](https://sarunw.com/posts/how-to-change-swiftui-font-size) — 2022-05-02
  **NeKI brief:** Changes SwiftUI font size through Font modifiers, preserving Dynamic Type behavior where fixed sizing would reduce accessibility for users.
- [How to prepare your iOS project to support modular architecture | Sarunw](https://sarunw.com/posts/how-to-prepare-ios-project-for-modular-architecture) — 2022-04-28
  **NeKI brief:** Prepare later modularization by organizing folders around prospective modules and enforcing access levels before targets are split. Treat a folder boundary as a design boundary now, so extracting it into a package or framework does not expose accidental internals.
- [How to handle API Changes with @available | Sarunw](https://sarunw.com/posts/how-to-handle-api-changes-with-available) — 2022-04-21
  **NeKI brief:** Use @available to annotate declarations with platform constraints, and use #available to branch at runtime when an API may be absent. Keeping those roles separate lets the compiler enforce unsupported use while preserving an explicit fallback implementation.
- [Swift Type placeholder: What is it and when to use it | Sarunw](https://sarunw.com/posts/swift-type-placeholder) — 2022-04-07
  **NeKI brief:** Swift's underscore type placeholder asks the compiler to infer a type where context makes it unambiguous. Use it to reduce redundant annotations, but supply an explicit type when inference obscures an important API boundary or produces surprising overload selection.
- [How to force two lines of Text in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-force-two-lines-of-text-in-swiftui) — 2022-03-31
  **NeKI brief:** Reserve two lines for a SwiftUI Text label by using a layout workaround that gives the view enough vertical space before content arrives. Treat it as a presentation hack and reevaluate on newer iOS versions with improved line-limit behavior.
- [How to fix "Unable to boot the iOS simulator" error | Sarunw](https://sarunw.com/posts/how-to-fix-unable-to-boot-the-ios-simulator) — 2022-03-28
  **NeKI brief:** Treat an unable-to-boot Simulator error as environment state rather than application logic: reset or recreate the affected runtime only after checking the local simulator configuration. Keep the fix scoped, because broad resets can erase useful test state.
- [Swift typealias: What is it and when to use it | Sarunw](https://sarunw.com/posts/swift-typealias) — 2022-03-24
  **NeKI brief:** Use typealias to give a complex or domain-specific existing type a clearer local name without creating a new runtime type. It improves readability at API boundaries, but should not be used to conceal meaning that deserves a dedicated struct.
- [How to modularize existing iOS projects using Swift Package | Sarunw](https://sarunw.com/posts/how-to-modularize-existing-ios-projects-using-swift-package) — 2022-03-17
  **NeKI brief:** Extract an existing iOS feature into a Swift Package by moving files, adding the package target, reconnecting it to the app, and tightening access levels. The access audit is essential: module boundaries expose every accidental reliance on internal symbols.
- [How to set UserDefaults value with Launch Arguments | Sarunw](https://sarunw.com/posts/how-to-set-userdefaults-value-with-launch-arguments) — 2022-03-10
  **NeKI brief:** Use launch arguments to override UserDefaults values during tests or debug runs without changing persistent app state manually. Define predictable argument-to-key mapping and reset behavior, so test scenarios remain reproducible across simulator and CI launches.
- [How to make a transparent navigation bar in iOS | Sarunw](https://sarunw.com/posts/how-to-make-transparent-navigation-bar-in-ios) — 2022-03-03
  **NeKI brief:** Make a navigation bar transparent either through shared appearance configuration or by styling one navigation-bar instance. Choose the scope deliberately: global customization creates consistency, while per-controller styling prevents an immersive screen from changing unrelated flows.
- [How to reset push notification permission on macOS | Sarunw](https://sarunw.com/posts/how-to-reset-push-notification-permission-on-macos) — 2022-02-24
  **NeKI brief:** Reset macOS notification authorization during development with the platform-specific permission reset workflow, then relaunch to retest first-run behavior. Treat this as test-environment maintenance; production apps cannot programmatically force the permission prompt to reappear.
- [How to render text with a color gradient in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-render-text-with-color-gradient-in-swiftui) — 2022-02-14
  **NeKI brief:** Render gradient SwiftUI text with a mask on earlier iOS versions or foregroundStyle on iOS 15 and later. Gate the simpler API by availability, and keep the gradient aligned to the text bounds rather than the entire container.
- [How to parse ISO 8601 date in Swift | Sarunw](https://sarunw.com/posts/how-to-parse-iso8601-date-in-swift) — 2022-02-07
  **NeKI brief:** Parse ISO 8601 timestamps with ISO8601DateFormatter and configure the formatter options for the variants your API emits. Codable date decoding needs the same contract; otherwise fractional seconds or timezone forms can silently fail parsing.
- [How to reset push notification permission on iOS | Sarunw](https://sarunw.com/posts/how-to-reset-push-notification-permission-on-ios) — 2022-02-03
  **NeKI brief:** Reset iOS notification permission only through the development environment's app or simulator state, then launch again to test the initial authorization path. Design the app to explain denied permission because production code cannot re-display the system prompt.
- [How to use Label in SwiftUI custom view | Sarunw](https://sarunw.com/posts/how-to-use-label-in-swiftui-custom-view) — 2022-01-31
  **NeKI brief:** Shows composing SwiftUI Label with custom visual content and supplying custom accessibility data when the default title-and-icon semantics are insufficient. Follow it when reusable views need consistent spoken descriptions and localization.
- [How to draw custom paths and shapes in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-draw-custom-paths-and-shapes-in-swiftui) — 2022-01-27
  **NeKI brief:** Create a custom Shape by defining its Path in normalized geometry, then use it for clipped or drawn SwiftUI content such as hexagonal avatars. Base points on the supplied rect so the shape scales correctly across layout sizes.
- [How to align text center/leading/trailing in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-align-text-in-swiftui) — 2022-01-24
  **NeKI brief:** SwiftUI text alignment depends on both the Text view's multiline alignment and the parent container's frame alignment. Set each at the layer that owns the relevant space; changing only text alignment cannot reposition the view within its container.
- [How to test UI layout for different languages with Pseudolanguages | Sarunw](https://sarunw.com/posts/how-to-test-ui-layout-for-different-languages-with-pseudolanguages) — 2022-01-17
  **NeKI brief:** Use pseudolanguages to stress layouts with expanded text, altered glyph heights, and right-to-left direction before localization ships. Test screens with these variants in Simulator so truncation, fixed widths, and directional assumptions become visible early.
- [How to customize automatic synthesizing Codable for enums with associated values | Sarunw](https://sarunw.com/posts/how-to-customize-automatic-synthesizing-codable-for-enums-with-associated-values) — 2022-01-13
  **NeKI brief:** Customize synthesized Codable enum representation by controlling coding keys and associated-value labels while preserving a stable external schema. Inspect the synthesized structure before changing cases, because seemingly local enum edits can break stored data or API decoding.
- [How to quickly test apps in other languages with an Xcode scheme | Sarunw](https://sarunw.com/posts/how-to-test-apps-in-other-languages-with-xcode-scheme) — 2022-01-10
  **NeKI brief:** Configures Xcode schemes to test an app in another language. Use it when localization needs quick manual validation without changing the device-wide language setting.
- [SwiftUI Label: A standard way to label user interface items | Sarunw](https://sarunw.com/posts/swiftui-label-a-standard-way-to-label-user-interface-items) — 2022-01-03
  **NeKI brief:** Use SwiftUI Label to pair text with an icon using system-adaptive semantics and styles. It communicates the relationship to accessibility and platform conventions more clearly than independently arranged image and text views for standard labeled actions.
- [Codable synthesis for enums with associated values in Swift 5.5 | Sarunw](https://sarunw.com/posts/codable-synthesis-for-enums-with-associated-values-in-swift) — 2021-12-27
  **NeKI brief:** Swift 5.5 synthesizes Codable for enums with associated values using a predictable nested keyed representation. Know that default wire format before adopting it across an API, because associated-value labels and case names become serialized compatibility commitments.
- [How to generate code coverage reports in Xcode | Sarunw](https://sarunw.com/posts/how-to-generate-code-coverage-reports-in-xcode) — 2021-12-20
  **NeKI brief:** Enable Xcode test coverage at the scheme level, then inspect the report by target, file, and line to find unexecuted code. Treat percentage as a diagnostic signal, not a goal: meaningful tests must still exercise behavior and failure paths.
- [How to change UIImage color in Swift | Sarunw](https://sarunw.com/posts/how-to-change-uiimage-color-in-swift) — 2021-12-16
  **NeKI brief:** Use template rendering mode with tintColor when an image should inherit interface color, or create a directly tinted image when the color is intrinsic. Select the approach from reuse needs; template assets retain flexibility across states and themes.
- [How to make custom XCTest assertions show an error at the call site | Sarunw](https://sarunw.com/posts/how-to-make-custom-xctest-assertions-show-an-error-at-call-site) — 2021-12-13
  **NeKI brief:** Forward file and line default parameters from a custom XCTest assertion into the underlying failure API, so Xcode marks the caller instead of the helper. This preserves the debugging ergonomics developers expect from built-in assertions.
- [What is image rendering mode in iOS | Sarunw](https://sarunw.com/posts/what-is-image-rendering-mode-in-ios) — 2021-12-09
  **NeKI brief:** UIImage rendering mode determines whether pixels display as authored or as a tintable template. Set it deliberately for icons and controls; an accidental template mode can discard color detail, while original mode prevents expected tint adaptation.
- [What is a variant in SF Symbols | Sarunw](https://sarunw.com/posts/what-is-variant-in-sf-symbols) — 2021-12-06
  **NeKI brief:** Use SF Symbol variants to express semantic states such as fill, slash, or circle without manually selecting unrelated symbol names. Apply symbolVariant within the view hierarchy so state presentation remains consistent with the base symbol and platform styling.
- [How to decode enums ignoring case in Swift Codable | Sarunw](https://sarunw.com/posts/how-to-decode-enums-ignoring-case-in-swift-codable) — 2021-12-02
  **NeKI brief:** Implements case-insensitive Codable decoding for raw-value enums by normalizing the decoded string before matching, making external API capitalization differences explicit rather than silently broadening model semantics.
- [How to disable dark mode in iOS | Sarunw](https://sarunw.com/posts/how-to-disable-dark-mode-in-ios) — 2021-11-29
  **NeKI brief:** Compares app-wide and view-specific UIKit interface-style overrides, clarifying when Info.plist defaults, window overrides, and controller or view overrides control Dark Mode behavior.
- [What do @main, @UIApplicationMain, and @NSApplicationMain mean | Sarunw](https://sarunw.com/posts/what-do-main-uiapplicationmain-nsapplicationmain-mean) — 2021-11-22
  **NeKI brief:** Explains how Swift's @main and the older UIApplicationMain or NSApplicationMain attributes establish an app entry point, clarifying the migration from generated main functions.
- [How to position an UIButton image to the right side of the text | Sarunw](https://sarunw.com/posts/how-to-position-uibutton-image-to-th-right-side-of-text.md) — 2021-11-18
  **NeKI brief:** Place a UIButton image after its title using the modern configuration image placement or carefully coordinated semantic layout direction for older APIs. Keep spacing and content insets in the same approach, so right-to-left layouts do not invert a purely visual workaround.
- [How to make a macOS menu bar app | Sarunw](https://sarunw.com/posts/how-to-make-macos-menu-bar-app) — 2021-11-15
  **NeKI brief:** Build a macOS menu-bar utility by configuring a status item and presenting only the compact actions or popover that belong there. Treat the menu bar as a persistent but low-attention surface, and keep full workflows in a separate window when necessary.
- [How to initialize NSViewController programmatically without nib | Sarunw](https://sarunw.com/posts/how-to-initialize-nsviewcontroller-programmatically-without-nib) — 2021-11-11
  **NeKI brief:** Initializes an AppKit NSViewController without a nib by overriding loadView and assigning its root view, making programmatic view-controller setup work like UIKit's code-first lifecycle.
- [How to use different fonts for different languages in an iOS application | Sarunw](https://sarunw.com/posts/how-to-use-different-fonts-for-different-languages-in-ios-application) — 2021-11-08
  **NeKI brief:** Uses language-specific fonts for localized iOS content. Use it when glyph coverage or typographic conventions require different font choices per locale.
- [How to use custom fonts in WKWebView | Sarunw](https://sarunw.com/posts/how-to-use-custom-fonts-in-wkwebview) — 2021-11-04
  **NeKI brief:** Loads bundled custom fonts into WKWebView by making the font resource reachable to the HTML/CSS context, keeping native asset registration separate from web-document styling.
- [How to create a macOS app without storyboard or xib files | Sarunw](https://sarunw.com/posts/how-to-create-macos-app-without-storyboard) — 2021-11-01
  **NeKI brief:** Builds an AppKit macOS interface without a storyboard by creating the window, assigning the app delegate, and setting the content view programmatically, making lifecycle ownership explicit.
- [How to simulate location in Xcode and Simulator | Sarunw](https://sarunw.com/posts/how-to-simulate-location-in-xcode-and-simulator) — 2021-10-28
  **NeKI brief:** Test location-dependent behavior with Simulator presets or project GPX waypoints and routes, selecting the location from Xcode's debug controls. Use deterministic coordinates and movement paths so permission, geofence, and map states can be reproduced in development and tests.
- [How to add custom fonts to iOS app | Sarunw](https://sarunw.com/posts/how-to-add-custom-fonts-to-ios-app) — 2021-10-25
  **NeKI brief:** Bundle custom font files, register them in the target configuration, and verify the PostScript name before applying them in UIKit or SwiftUI. Treat font licensing and Dynamic Type behavior as part of the integration, not merely an asset-copying step.
- [How to remove extra padding when converting HTML to NSAttributedString | Sarunw](https://sarunw.com/posts/how-to-remove-extra-padding-when-converting-html-to-nsattributedstring) — 2021-10-21
  **NeKI brief:** When HTML conversion adds UILabel spacing, distinguish block-element margins from trailing newline characters in the attributed result. Normalize the HTML or trim only leading and trailing whitespace while preserving attributes, rather than compensating with arbitrary layout offsets.
- [How to make a SwiftUI view to fill its container width and height | Sarunw](https://sarunw.com/posts/how-to-make-swiftui-view-fill-container-width-and-height) — 2021-10-18
  **NeKI brief:** Make a SwiftUI view fill offered space with a flexible frame while distinguishing proposal size from a child's intrinsic size. Use maxWidth or maxHeight deliberately, because an infinite frame changes alignment and hit area but does not guarantee every parent can supply space.
- [How to make a custom button style supports leading dot syntax in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-make-custom-button-style-supports-leading-dot-syntax-in-swiftui) — 2021-10-14
  **NeKI brief:** Make a custom SwiftUI ButtonStyle available through leading-dot syntax by exposing a static style member in the expected namespace. This keeps call sites consistent with system styles while retaining a concrete type that centralizes configuration and pressed-state rendering.
- [What is a KeyPath in Swift | Sarunw](https://sarunw.com/posts/what-is-keypath-in-swift) — 2021-10-11
  **NeKI brief:** Explains Swift KeyPath values as type-safe references to properties, useful for deferred access, mapping, and observation while preserving compile-time checks that string key paths lack.
- [Should every if statement has an else clause | Sarunw](https://sarunw.com/posts/should-every-if-statement-has-else-clause) — 2021-10-07
  **NeKI brief:** Discusses when an if branch needs an explicit else, distinguishing exhaustive state handling from guard-style side effects so control flow remains readable and intentional.
- [How to present an alert in SwiftUI in iOS 15 | Sarunw](https://sarunw.com/posts/how-to-present-alert-in-swiftui-ios15) — 2021-10-04
  **NeKI brief:** Use the iOS 15 SwiftUI alert APIs to bind presentation to state and define actions plus message in the declarative view hierarchy. Keep destructive and cancel roles explicit, so the system can apply correct ordering and accessibility semantics without manual UIAlertController bridging.
- [What does the ?? operator mean in Swift | Sarunw](https://sarunw.com/posts/what-does-nil-coalescing-operator-means-in-swift) — 2021-09-30
  **NeKI brief:** Use Swift's nil-coalescing operator to express a fallback only when the optional's absence is an expected value decision. Keep the default local and meaningful, and use explicit branching when nil must trigger validation, logging, or a distinct control-flow path.
- [How to present a Bottom Sheet in iOS 15 with UISheetPresentationController | Sarunw](https://sarunw.com/posts/bottom-sheet-in-ios-15-with-uisheetpresentationcontroller) — 2021-09-27
  **NeKI brief:** Configure UISheetPresentationController with appropriate detents, selected height, scrolling expansion, grabber visibility, and dismissal rules instead of recreating a sheet manually. Treat the selected detent as presentation state, especially when content or navigation changes the sheet's practical height.
- [7 ways to pass a closure as an argument in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-pass-closure-as-argument) — 2021-09-20
  **NeKI brief:** Pass closures using trailing syntax, named functions, shorthand arguments, or operators according to the call site's readability. Preserve the closure's escaping and throwing contract, and favor the form that makes captured state and the operation's intent clearest to the next reader.
- [How to make a custom button style with UIButton.Configuration in iOS 15 | Sarunw](https://sarunw.com/posts/how-to-mark-custom-button-style-with-uibuttonconfiguration) — 2021-09-13
  **NeKI brief:** Build a custom UIKit button appearance from UIButton.Configuration so title, image, padding, background, and state updates remain part of one configuration model. Use configuration update handlers for dynamic state instead of layering unrelated view mutations onto the button.
- [How to set custom CodingKey for the convertFromSnakeCase decoding strategy | Sarunw](https://sarunw.com/posts/how-to-set-custom-codingkey-for-convertfromsnakecase-decoding-strategy) — 2021-09-06
  **NeKI brief:** Use JSONDecoder.convertFromSnakeCase for ordinary keys, then define explicit CodingKeys for acronym or legacy exceptions such as URL and ID. Test underscore and capitalization edge cases against real payloads instead of assuming the automatic conversion matches every property name.
- [How to define custom Environment Values in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-define-custom-environment-values-in-swiftui) — 2021-08-30
  **NeKI brief:** Defines custom SwiftUI EnvironmentValues through an EnvironmentKey and optional modifier, injecting scoped configuration down a view hierarchy without threading parameters through every intermediate view.
- [How to reference a method with the same name and parameters but a different return type in Swift | Sarunw](https://sarunw.com/posts/how-to-reference-method-with-the-same-name-and-parameters-but-different-return-type-in-swift) — 2021-08-23
  **NeKI brief:** Disambiguate same-parameter Swift overloads that differ by return type by supplying result context, such as a typed local value or a typed function reference. This lets protocol-required void methods coexist with value-returning helpers without recursive or ambiguous calls.
- [How to show multiple alerts on the same view in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-show-multiple-alerts-on-the-same-view-in-swiftui) — 2021-08-18
  **NeKI brief:** Coordinates multiple SwiftUI alerts from one view. Use it when distinct error or confirmation states must present predictably without competing modifier bindings.
- [How to do print debugging in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-do-print-debugging-in-swiftui) — 2021-08-14
  **NeKI brief:** Uses SwiftUI print diagnostics and _printChanges to identify why a view body reevaluates, separating state-driven invalidation from assumptions that a body call necessarily redraws everything.
- [Pop-Up Buttons in SwiftUI | Sarunw](https://sarunw.com/posts/popup-buttons-in-swiftui) — 2021-08-11
  **NeKI brief:** Shows the macOS SwiftUI approach to pop-up controls by configuring a Picker with the appropriate menu-style presentation. It clarifies how the selection binding and option tags provide the AppKit-style pop-up behavior without embedding a custom NSView control.
- [Different ways to catch throwing errors from Swift do-catch | Sarunw](https://sarunw.com/posts/different-ways-to-catch-throwing-errors-in-swift) — 2021-08-09
  **NeKI brief:** Handle Swift errors with ordered catch clauses that match the domain cases you can recover from, then preserve an explicit fallback for unexpected failures. Avoid collapsing every error into one generic path, because it hides user action, retry policy, and diagnostic context.
- [How to ignore safe area insets in UIKit | Sarunw](https://sarunw.com/posts/how-to-ignore-safe-area-insets-in-uikit) — 2021-08-04
  **NeKI brief:** Controls UIKit scroll-view safe-area adjustment with contentInsetAdjustmentBehavior, choosing all-edge or edge-specific behavior instead of applying arbitrary content inset offsets.
- [Spell checking in Xcode | Sarunw](https://sarunw.com/posts/spell-checking-in-xcode) — 2021-08-02
  **NeKI brief:** Enables Xcode spell checking and shows how to inspect, correct, add, unlearn, and bulk-handle misspellings. It is a lightweight code-quality workflow for catching prose errors in identifiers, comments, and strings before they escape into UI copy or documentation.
- [How to explicitly specialize a generic function in Swift | Sarunw](https://sarunw.com/posts/how-to-explicitly-specialize-generic-function-in-swift) — 2021-07-28
  **NeKI brief:** Explains Swift’s lack of call-site generic specialization syntax and uses parameter or result-type context to guide inference, keeping generic APIs expressive without forcing unnecessary wrapper functions.
- [How to show and hide a sidebar in a SwiftUI macOS app | Sarunw](https://sarunw.com/posts/how-to-toggle-sidebar-in-macos) — 2021-07-26
  **NeKI brief:** Explains how a macOS SwiftUI sidebar can become unreachable after collapsing and demonstrates recovery through toolbar or command actions. Follow it when testing window navigation states beyond the initial layout.
- [Dynamic button configuration in iOS 15 | Sarunw](https://sarunw.com/posts/dynamic-button-configuration) — 2021-07-21
  **NeKI brief:** Use UIButton configuration update handlers to derive title, color, and appearance from button state and external model changes. Keep configuration as a pure state-to-style mapping where possible, while retaining older setTitle APIs only for behavior the configuration system does not own.
- [Always show search bar in a navigation bar in SwiftUI | Sarunw](https://sarunw.com/posts/always-show-search-bar-in-swiftui) — 2021-07-19
  **NeKI brief:** Keep a navigation search field visible by configuring the underlying search controller or SwiftUI search presentation mode rather than relying on scroll position. Choose the persistent display only when filtering is a primary task, since it permanently consumes navigation space.
- [4 Xcode shortcuts to get back your screen space | Sarunw](https://sarunw.com/posts/xcode-shortcuts-for-space) — 2021-07-14
  **NeKI brief:** Shows four Xcode shortcuts for reclaiming MacBook screen space: toggling the debug, navigator, and inspector areas, plus focusing the editor and moving between editors. It is a compact workflow reference for hiding panes during coding without repeatedly navigating menus.
- [Searchable modifier in SwiftUI: A UISearchController and UISearchBar equivalent | Sarunw](https://sarunw.com/posts/searchable-in-swiftui) — 2021-07-07
  **NeKI brief:** Builds native SwiftUI search with searchable, including placement, query binding, suggestions, completion, submission, and presentation behavior. Use it to make a navigation-based list searchable while keeping filtering, suggestion data, and dismissal state explicit in the view's model.
- [How to manually add existing certificates to the Fastlane match | Sarunw](https://sarunw.com/posts/how-to-manually-add-existing-certificates-to-fastlane-match) — 2021-07-05
  **NeKI brief:** Import an existing signing certificate and private key into fastlane match only when migrating known credentials, then verify repository encryption, team ownership, and profile linkage. Treat manual import as a controlled recovery path, not a replacement for managed certificate lifecycle discipline.
- [New Formatters in iOS 15: Why do we need another formatter | Sarunw](https://sarunw.com/posts/new-formatters-in-ios15) — 2021-06-30
  **NeKI brief:** Compares iOS 15's value-formatting APIs with older Formatter objects, focusing on locale-aware strings, type safety, and composable formatting choices. It explains why new formatting syntax reduces mutable formatter setup without eliminating the need to choose presentation rules deliberately.
- [How to share an iOS distribution certificate | Sarunw](https://sarunw.com/posts/how-to-share-ios-distribution-certificate) — 2021-06-28
  **NeKI brief:** A distribution certificate requires its private key as well as the certificate file, so export and import it through Keychain only within an authorized team workflow. Prefer managed signing or an encrypted credential store, and never treat a certificate file alone as deployable signing access.
- [A better way to ask for a one-time user's location with the Location Button | Sarunw](https://sarunw.com/posts/location-button) — 2021-06-23
  **NeKI brief:** Explains Core Location's LocationButton as a focused way to request a one-time location action while communicating the privacy-sensitive intent in the UI. The customization and caveats help decide when it is preferable to a generic permission prompt.
- [Preview a device in landscape orientation with previewInterfaceOrientation | Sarunw](https://sarunw.com/posts/preview-device-in-landscape-orientation-with-previewinterfaceorientation) — 2021-06-22
  **NeKI brief:** Use previewInterfaceOrientation to exercise a SwiftUI preview in portrait or landscape and expose size-class and layout assumptions before runtime. The modifier is a focused orientation test; treat the older PreviewProvider setup as context when translating the idea to current macro-based previews.
- [How to use a pre-release Swift version with command-line tools | Sarunw](https://sarunw.com/posts/how-to-use-pre-release-swift-version-with-command-line-tools) — 2021-06-21
  **NeKI brief:** Shows how to identify and select a downloaded Swift toolchain for command-line builds, including CI. Verify the active compiler version so Fastlane or xcodebuild does not silently fall back to Xcode's default toolchain.
- [A new way to style UIButton with UIButton.Configuration in iOS 15 | Sarunw](https://sarunw.com/posts/new-way-to-style-uibutton-in-ios15) — 2021-06-17
  **NeKI brief:** Explains iOS 15 UIButton.Configuration as a replacement for scattered title, image, inset, and background mutations, covering preset configurations and state-driven updates for consistently styled UIKit buttons.
- [How to use a pre-release Swift version in Xcode | Sarunw](https://sarunw.com/posts/how-to-use-pre-release-swift-version-in-xcode) — 2021-06-14
  **NeKI brief:** Walks through installing an alternative Swift toolchain and selecting it inside Xcode to experiment with language features before the matching IDE release. The caveats and removal steps help keep an exploratory compiler choice from silently becoming a project-wide default.
- [Pull to refresh in SwiftUI with refreshable | Sarunw](https://sarunw.com/posts/pull-to-refresh-in-swiftui) — 2021-06-09
  **NeKI brief:** Adds pull-to-refresh with refreshable, covering the async action, refresh environment, programmatic refresh, and a custom view's refreshing state. Use it to connect reload work to SwiftUI's lifecycle rather than embedding a UIKit refresh control or manually coordinating spinner visibility.
- [How to read App Name, Version, and Build Number from Info.plist | Sarunw](https://sarunw.com/posts/how-to-read-info-plist) — 2021-05-17
  **NeKI brief:** Read app display name, version, and build number from the bundled Info.plist through Bundle APIs, then keep presentation formatting separate from the raw values. This avoids duplicating release metadata in source and lets diagnostics reflect the actual built artifact.
- [How to set up iOS environments: develop, staging, and production | Sarunw](https://sarunw.com/posts/how-to-set-up-ios-environments) — 2021-05-10
  **NeKI brief:** Model development, staging, and production as explicit build configurations and shared schemes, with xcconfig values feeding configuration-specific settings. Keep environment endpoints and identifiers out of source literals, and ensure CI selects the same scheme and configuration deliberately.
- [How to make a simple bevel effect using inner shadows in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-make-bevel-effect-in-swiftui) — 2021-05-03
  **NeKI brief:** Create a SwiftUI bevel with paired light and dark inner-shadow treatments that follow the same shape and corner radius. Keep the effect decorative and test it against contrast requirements, because inner shadows alone do not communicate an interactive control's semantics.
- [What is a Property Wrapper in Swift | Sarunw](https://sarunw.com/posts/what-is-property-wrappers-in-swift) — 2021-04-26
  **NeKI brief:** Use a property wrapper to package repeated property access behavior behind a clear projected or wrapped-value contract, rather than duplicating observers across models. Keep initialization, mutation rules, and storage semantics explicit so the wrapper does not conceal surprising state changes.
- [4 Xcode shortcuts to boost your productivity for SwiftUI | Sarunw](https://sarunw.com/posts/xcode-shortcuts-for-swiftui) — 2021-04-21
  **NeKI brief:** Collects Xcode shortcuts useful for SwiftUI editing and navigation. Use it to reduce repetitive mouse work while moving between previews, symbols, diagnostics, and running the current scheme.
- [How to set a screen's background color in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-set-screen-background-color-in-swiftui) — 2021-04-19
  **NeKI brief:** Give a SwiftUI screen background a flexible frame or place Color in a ZStack, then apply ignoresSafeArea to the background layer only. This fills system regions without extending foreground controls or text into unsafe layout areas.
- [How to resize an image view to fit a container view in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-resize-an-image-to-fit-a-container-view-in-swiftui) — 2021-04-14
  **NeKI brief:** In a SwiftUI overlay, combine a resizable image with scaledToFit and set layoutPriority so essential foreground content retains its proposed space. This explains why an image can shrink unexpectedly when sibling views compete within a container.
- [Replicate 12 UIKit's contentMode options in SwiftUI | Sarunw](https://sarunw.com/posts/uikits-contentmode-in-swiftui) — 2021-04-12
  **NeKI brief:** Map UIKit image scaling intent to SwiftUI by combining resizable images with scaledToFit or scaledToFill and a frame alignment. Add clipping only when a filled image must be cropped, because the visual scaling choice does not itself constrain overflow.
- [How to add background to your view in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-add-background-to-your-view-in-swiftui) — 2021-04-07
  **NeKI brief:** Use SwiftUI's background modifier to attach decorative or structural content behind a view while controlling alignment and size ownership. Distinguish it from overlay: the background follows the modified view's layout, which avoids UIKit-style subview-order bookkeeping.
- [NSAttributedString in SwiftUI | Sarunw](https://sarunw.com/posts/nsattributedstring-in-swiftui) — 2021-03-31
  **NeKI brief:** Explains bringing NSAttributedString content into SwiftUI while preserving styled text and links. Follow it when rich text must remain readable, navigable, and semantically understandable under Dynamic Type and assistive technologies.
- [How to resize and position an image in UIImageView using contentMode | Sarunw](https://sarunw.com/posts/how-to-resize-and-position-image-in-uiimageview-using-contentmode) — 2021-03-29
  **NeKI brief:** Use UIImageView contentMode to choose scaling versus cropping and, where appropriate, positional alignment within its bounds. Match scaleAspectFit, scaleAspectFill, or scaleToFill to the visual contract before changing constraints, because content mode does not change the view's layout size.
- [What is the difference between Tuist init and scaffold | Sarunw](https://sarunw.com/posts/what-is-the-difference-between-tuist-init-and-scaffold) — 2021-03-22
  **NeKI brief:** Choose a project-bootstrap template when creating an initial Tuist structure and a scaffold template when adding architecture-specific components later. Design attributes and generated files around that lifecycle distinction, so feature generation does not overwrite project-level configuration.
- [How to resize a SwiftUI Image and keep its aspect ratio | Sarunw](https://sarunw.com/posts/how-to-resize-swiftui-image-and-keep-aspect-ratio) — 2021-03-17
  **NeKI brief:** Make a SwiftUI Image resizable, then choose scaledToFit for complete content or scaledToFill plus clipping for a filled frame. Keep the frame and clipping decision together so aspect-ratio preservation does not unexpectedly overflow surrounding layout.
- [Tuist scaffold: How to use the Tuist template to create a new module for an ongoing project | Sarunw](https://sarunw.com/posts/tuist-scaffold) — 2021-03-15
  **NeKI brief:** Use a Tuist scaffold template to generate a repeatable feature or component inside an established project, with attributes controlling names and paths. Keep the template aligned with the team's module and testing conventions so scaffolding reduces drift instead of producing generic boilerplate.
- [How to fix ZStack's views disappear transition not animated in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-fix-zstack-transition-animation-in-swiftui) — 2021-03-10
  **NeKI brief:** Explains a disappearing ZStack transition failure through sibling z-order and fixes it with nonzero zIndex placement, making transition visibility explicit when layers overlap.
- [Tuist init: How to use Tuist templates to bootstrap your project | Sarunw](https://sarunw.com/posts/tuist-init) — 2021-03-08
  **NeKI brief:** Use Tuist initialization templates to bootstrap a project structure when the initial targets, manifests, and source layout should be generated consistently. Treat the generated files as owned project inputs, then adapt their dependencies and settings to the actual architecture rather than hand-editing derived output.
- [Tuist Template: What is it and how to create them | Sarunw](https://sarunw.com/posts/tuist-template) — 2021-03-01
  **NeKI brief:** Define Tuist templates with explicit required or optional attributes and file or string outputs, then invoke them through the scaffold workflow. A small template contract makes repeated module creation predictable while keeping architecture-specific decisions version controlled.
- [Using App Store Connect API with Fastlane Match | Sarunw](https://sarunw.com/posts/using-app-store-connect-api-with-fastlane-match) — 2021-02-22
  **NeKI brief:** Provide fastlane match with an App Store Connect API key through scoped environment-backed configuration, then use read-only signing access for routine CI lanes. Keep issuer, key identifier, and private key material out of the repository and handle encoded key content deliberately.
- [How to fix "no identity found - Command CodeSign failed with a nonzero exit code" error in Xcode | Sarunw](https://sarunw.com/posts/how-to-fix-command-codesign-failed) — 2021-02-20
  **NeKI brief:** Diagnoses Xcode CodeSign identity failures by connecting the selected signing identity to installed certificates and private keys, separating target signing configuration from the codesign command symptom.
- [Sort array of objects by multiple properties with Swift Tuple | Sarunw](https://sarunw.com/posts/sort-array-of-objects-by-multiple-properties-with-swift-tuple) — 2021-02-16
  **NeKI brief:** Uses tuple comparison to express lexicographic sorting across several object properties, including ascending, descending, and mixed-direction rules. Follow it when a collection needs deterministic tie-breakers, while keeping the comparison fields and ordering contract visible rather than relying on incidental input order.
- [How to create segmented control in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-create-segmented-control-in-swiftui) — 2021-02-15
  **NeKI brief:** Uses Picker with segmented style to model mutually exclusive SwiftUI choices, binding the selected value to state instead of introducing a separate UIKit-style control abstraction.
- [How to add a unit test target to a Tuist project | Sarunw](https://sarunw.com/posts/how-to-add-unit-test-target-to-tuist-project) — 2021-02-13
  **NeKI brief:** Add a Tuist unit-test target by declaring its product, sources, dependencies, and host relationship in the manifest, then regenerate the project. Keep test-only dependencies out of the app target so production linkage and test setup remain independently understandable.
- [How to delete UserDefaults data on macOS and Catalyst | Sarunw](https://sarunw.com/posts/how-to-delete-userdefaults-data-on-macos-catalyst) — 2021-02-11
  **NeKI brief:** Uses macOS defaults domains to reset standard or custom UserDefaults during development, distinguishing bundle identifiers from suite names so Catalyst preference cleanup targets the intended store.
- [How to use SwiftUI Picker | Sarunw](https://sarunw.com/posts/how-to-use-swiftui-picker) — 2021-02-09
  **NeKI brief:** Builds a SwiftUI Picker from fixed choices, dynamic collections, or enum cases, with tags that match the bound selection type. The examples clarify how data identity and selection values must line up before a picker can update application state predictably.
- [Does Swift enum retain its associated value | Sarunw](https://sarunw.com/posts/does-enum-retained-its-associated-value) — 2021-02-07
  **NeKI brief:** Swift enum cases hold associated reference values strongly unless those values are wrapped in another ownership mechanism. Model that lifetime deliberately when an enum stores objects, because a case change does not make reference-cycle or cancellation concerns disappear.
- [Record iOS Simulator video as mp4 and GIF with Xcode | Sarunw](https://sarunw.com/posts/record-ios-simulator-video-and-gif-with-xcode) — 2021-02-04
  **NeKI brief:** Records Simulator output as video or GIF using the built-in screen-recording commands, including its preference and caveat settings. Use it to create reproducible visual evidence for App Store previews, pull requests, issues, or documentation without adding a separate capture tool.
- [Navigation in SwiftUI | Sarunw](https://sarunw.com/posts/navigation-in-swiftui) — 2021-02-02
  **NeKI brief:** Introduces the original SwiftUI NavigationView and NavigationLink model, covering source and destination views plus title customization. It provides useful historical context for projects supporting early SwiftUI, while making the navigation container's ownership explicit.
- [Getting Started with Tuist | Sarunw](https://sarunw.com/posts/getting-started-with-tuist) — 2021-01-31
  **NeKI brief:** Use Tuist manifests as a version-controlled source of truth for Xcode project structure when generated project files create team merge friction. Keep targets, dependencies, and settings declarative, then regenerate consistently rather than manually editing the derived project.
- [How to resize an UIImageView to fit a container view using auto layout | Sarunw](https://sarunw.com/posts/how-to-resize-uiimageview-to-fit-container-view-using-auto-layout) — 2021-01-27
  **NeKI brief:** When an image view competes with other Auto Layout content, lower its compression-resistance priority on the constrained axis instead of hard-coding dimensions. This lets the layout express which view may shrink while preserving the container's required constraints.
- [How to sort by multiple properties in Swift | Sarunw](https://sarunw.com/posts/how-to-sort-by-multiple-properties-in-swift) — 2021-01-25
  **NeKI brief:** Write a lexicographic sorted comparator that evaluates the primary property first and uses later properties only to break ties. Keep each comparison direction explicit, and return false for equal records so the ordering rule remains understandable and testable.
- [List view, a UITableView equivalent in SwiftUI | Sarunw](https://sarunw.com/posts/list-view-uitableview-equivalent-in-swiftui) — 2021-01-23
  **NeKI brief:** Introduces SwiftUI List as the UITableView-style container for static and ForEach-driven rows, including its styling and scrolling boundaries. It helps distinguish row identity and list behavior from a manually assembled ScrollView stack.
- [How to create custom operators and do operators overloading in Swift | Sarunw](https://sarunw.com/posts/how-to-create-custom-operators-and-operators-overloading-in-swift) — 2021-01-20
  **NeKI brief:** Distinguishes overloading existing Swift operators from declaring custom prefix, infix, and postfix operators, including precedence constraints that keep domain syntax readable rather than surprising callers.
- [How to use ScrollView in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-use-scrollview-in-swiftui) — 2021-01-17
  **NeKI brief:** Introduces SwiftUI ScrollView by choosing vertical, horizontal, or combined axes and configuring indicator visibility. It is useful for deciding when custom scrolling is a better fit than List, while keeping the content's layout and scrolling direction explicit.
- [What is @Environment in SwiftUI | Sarunw](https://sarunw.com/posts/what-is-environment-in-swiftui) — 2021-01-15
  **NeKI brief:** Read system-provided SwiftUI context such as locale, calendar, color scheme, and size classes through @Environment, then inject overrides at a containing boundary for previews or controlled subtrees. This keeps contextual dependencies declarative without turning them into global mutable state.
- [Create a list of views in SwiftUI using ForEach | Sarunw](https://sarunw.com/posts/create-list-of-views-in-swiftui-using-foreach) — 2021-01-13
  **NeKI brief:** Use ForEach with stable identity when SwiftUI creates dynamic list content, and distinguish that case from static child views. Identity drives diffing and state retention, so array offsets are safe only when insertion, deletion, and reordering cannot invalidate them.
- [Different ways to check if a string contains another string in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-check-if-string-contains-another-string-in-swift) — 2021-01-11
  **NeKI brief:** Choose String range searches and comparison options from the matching rule you need: literal containment, case-insensitive matching, locale-aware behavior, or character-class inspection. Keep the option explicit, because a seemingly simple contains check can encode product-facing text semantics.
- [Different ways to compare string in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-compare-string-in-swift) — 2021-01-08
  **NeKI brief:** Compare Swift strings with equality for exact values, comparison APIs for ordering, and explicit case or locale options when the product rule requires them. Do not substitute one for another: user-visible sorting and identifier matching can have different correctness contracts.
- [TextField in SwiftUI | Sarunw](https://sarunw.com/posts/textfield-in-swiftui) — 2021-01-06
  **NeKI brief:** Introduces SwiftUI TextField through data binding, editing callbacks, formatted input, validation states, and custom styling. Sarunw contrasts the control with UIKit’s UITextField and demonstrates how state flows into and out of the field before refining its appearance.
- [How to change the color of SF Symbols | Sarunw](https://sarunw.com/posts/how-to-change-color-of-sf-symbols) — 2021-01-04
  **NeKI brief:** Configure SF Symbol color with tint, foreground styles, or a symbol rendering mode chosen for the intended hierarchy. Use multicolor only where the symbol supports it and the semantic state remains clear, rather than baking a fixed image for every appearance.
- [How to fix "Skipping duplicate build file" warning in Xcode | Sarunw](https://sarunw.com/posts/how-to-fix-duplicate-references-warning) — 2021-01-02
  **NeKI brief:** Resolves Xcode duplicate build-file warnings by removing repeated project references or build-phase entries, preserving a single source-of-truth membership for each compiled resource.
- [How to convert a String to an Int in Swift | Sarunw](https://sarunw.com/posts/how-to-convert-string-to-int-in-swift) — 2021-01-01
  **NeKI brief:** Compares Int initializer with NumberFormatter for turning external numeric strings into Int values, making invalid-input behavior explicit and reserving locale-aware formatting for inputs that actually require it.
- [Different ways to sort an array of strings in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-sort-array-of-strings-in-swift) — 2020-12-26
  **NeKI brief:** Choose sort or sorted based on whether the collection should mutate, then provide a comparator when lexical default order is not the product order. Keep locale, case, and numeric ordering requirements explicit instead of relying on an accidental String comparison.
- [How to specify fractional digits for formatted number string in Swift | Sarunw](https://sarunw.com/posts/how-to-specify-fractional-digits-for-formatted-number-string-in-swift) — 2020-12-22
  **NeKI brief:** Choose minimum and maximum fraction digits according to the display contract, using locale-aware NumberFormatter or modern formatting APIs for user-visible values. Reserve fixed printf-style formatting for controlled technical output, because separators and rounding are locale-sensitive.
- [How to use DateFormatter in Swift | Sarunw](https://sarunw.com/posts/how-to-use-dateformatter) — 2020-12-20
  **NeKI brief:** Explains why DateFormatter creation is expensive, how thread-safety affects sharing, and when caching is appropriate. It keeps locale-aware user-facing formatting separate from a casually shared singleton, avoiding both repeated setup work and incorrect assumptions about use across threads.
- [How to fix "Build input file cannot be found" error in Xcode | Sarunw](https://sarunw.com/posts/how-to-fix-build-input-file-cannot-be-found) — 2020-12-14
  **NeKI brief:** Diagnoses Xcode missing build-input errors after project-file merge conflicts by reconciling file references and build phases, rather than treating a stale project entry as a compiler failure.
- [How expensive is DateFormatter | Sarunw](https://sarunw.com/posts/how-expensive-is-dateformatter) — 2020-12-13
  **NeKI brief:** Measures DateFormatter creation cost and motivates formatter reuse. Use it when date-heavy rendering or parsing appears in a hot path, while avoiding premature caching without profiling.
- [How to get the first N elements of array in Swift | Sarunw](https://sarunw.com/posts/how-to-get-first-n-elements-of-swift-array) — 2020-12-10
  **NeKI brief:** Uses prefix and range APIs to take the first N Swift collection elements while accounting for ArraySlice indices and avoiding out-of-bounds assumptions in empty or short inputs.
- [UIStackView padding | Sarunw](https://sarunw.com/posts/uistackview-padding) — 2020-12-02
  **NeKI brief:** Give a UIStackView internal padding by enabling isLayoutMarginsRelativeArrangement and setting directional layout margins. This keeps arranged subviews aligned to an inset content area and avoids adding wrapper views or constraints solely to simulate stack padding.
- [Custom UIStackView spacing | Sarunw](https://sarunw.com/posts/custom-uistackview-spacing) — 2020-11-26
  **NeKI brief:** Shows custom spacing between arranged UIStackView subviews. Use it when one layout gap needs different treatment without nesting additional stacks or inserting spacer views.
- [Scaling custom fonts automatically with Dynamic Type | Sarunw](https://sarunw.com/posts/scaling-custom-fonts-automatically-with-dynamic-type) — 2020-11-18
  **NeKI brief:** Demonstrates automatic Dynamic Type scaling for custom SwiftUI fonts and explains the relevant text-style relationship. Use it to keep custom typography aligned with system accessibility settings instead of hard-coding a single size.
- [Multi-cursor editing in Xcode | Sarunw](https://sarunw.com/posts/multi-cursor-editing-in-xcode) — 2020-11-11
  **NeKI brief:** Demonstrates Xcode's multi-cursor editing workflow for placing several insertion points and applying the same change across repeated code. It is a practical navigation and refactoring aid when a small, visually obvious edit does not warrant a broad search-and-replace.
- [Getting the number of days between two dates in Swift | Sarunw](https://sarunw.com/posts/getting-number-of-days-between-two-dates) — 2020-11-02
  **NeKI brief:** Define whether a day means crossing a calendar boundary or a full 24-hour duration before calculating a difference. Use Calendar components for user-facing date boundaries and time intervals for elapsed duration, with timezone and daylight-saving behavior treated as part of the requirement.
- [Understanding Date and DateComponents | Sarunw](https://sarunw.com/posts/understanding-date-and-datecomponents) — 2020-10-26
  **NeKI brief:** Use Date for an absolute instant and Calendar plus DateComponents for user-facing calendar arithmetic such as adding months or selecting fields. Avoid fixed-second intervals for calendar periods, because timezone and daylight-saving transitions are part of the requested behavior.
- [What is @escaping in Swift closures | Sarunw](https://sarunw.com/posts/what-is-escaping-in-swift-closures) — 2020-10-19
  **NeKI brief:** Mark a closure @escaping when the function stores it or invokes it after the call returns, and release stored completion handlers after delivering a result. Make the lifetime explicit so asynchronous delegates, cancellation, and captured ownership can be reasoned about safely.
- [Better print debugging with Xcode breakpoints | Sarunw](https://sarunw.com/posts/better-print-debugging-with-xcode-breakpoints) — 2020-10-12
  **NeKI brief:** Attach an Xcode breakpoint action to log expressions, commands, or diagnostics without adding temporary print statements to source. Scope the action and continue execution automatically, so an investigation captures runtime values while leaving the repository and normal control flow clean.
- [Reduce boilerplate code with an automatic synthesis of Equatable and Hashable conformance | Sarunw](https://sarunw.com/posts/reduce-boilerplate-code-with-automatic-synthesis-of-equatable-and-hashable-conformance) — 2020-10-08
  **NeKI brief:** Explains when Swift synthesizes Equatable and Hashable for structs and enums, when properties block synthesis, and how a custom implementation supersedes it. Use it to keep value semantics concise while checking that every stored member participates in equality and hashing as intended.
- [Setting default values for NSUserDefaults | Sarunw](https://sarunw.com/posts/setting-default-value-for-nsuserdefaults) — 2020-09-30
  **NeKI brief:** Register UserDefaults defaults instead of writing fallback values on every launch, and distinguish registered defaults from persisted user choices. The walkthrough covers property-list input and the nil-key behavior, helping preference code preserve a user's override while retaining a reliable initial value.
- [How to save/export an image in Mac Catalyst | Sarunw](https://sarunw.com/posts/how-to-save-export-image-in-mac-catalyst) — 2020-09-23
  **NeKI brief:** Export a generated UIImage by writing image data to a temporary URL and presenting a document picker for the user-selected destination. Configure the Mac Catalyst sandbox entitlement and clean up the temporary file after completion or cancellation.
- [3 lesser-known ways of using Swift enums | Sarunw](https://sarunw.com/posts/lesser-known-ways-of-using-swift-enums) — 2020-09-14
  **NeKI brief:** Covers compound enum cases with value bindings, pattern matching through if or guard case, and optionals as enums. These patterns help replace nested switch or optional-unwrapping code with branches that state the exact case and associated data being handled.
- [Testing delegates and protocols in XCTest | Sarunw](https://sarunw.com/posts/testing-delegates-and-protocols-in-xctest) — 2020-09-06
  **NeKI brief:** Builds XCTest coverage for delegate and protocol callbacks with a small system under test, Arrange-Act assertions, and a test double that records interactions. It helps test behavior delivered through delegation without coupling tests to unrelated UI implementation details.
- [Make a placeholder view in SwiftUI with redacted() | Sarunw](https://sarunw.com/posts/make-placeholder-view-in-swiftui-with-redacted) — 2020-09-02
  **NeKI brief:** Uses redacted to turn a real SwiftUI hierarchy into loading placeholders, then shows opt-out and redaction-aware subviews. The caveats are useful when skeleton state should preserve layout without accidentally leaving interactive controls misleadingly available.
- [Move your view around with Drag Gesture in SwiftUI | Sarunw](https://sarunw.com/posts/move-view-around-with-drag-gesture-in-swiftui) — 2020-08-25
  **NeKI brief:** Builds draggable SwiftUI content with DragGesture, separating transient gesture updates from committed position state. The comparison of onChanged, onEnded, and updating helps avoid jumpy movement or stale offsets when a drag is cancelled or completes.
- [Quick way to open a Custom URL Scheme in iOS Simulator | Sarunw](https://sarunw.com/posts/quick-way-to-open-custom-url-scheme-in-ios-simulator) — 2020-08-19
  **NeKI brief:** Test an app's custom URL scheme from the command line with xcrun simctl openurl booted instead of repeatedly typing it into Simulator Safari. Keep representative deep-link URLs as reproducible commands so route handling can be triggered quickly during development and debugging.
- [How to renew an expired certificate with Fastlane Match | Sarunw](https://sarunw.com/posts/how-to-renew-expired-certificate-with-fastlane-match) — 2020-08-17
  **NeKI brief:** Treat an expired signing certificate as a coordinated fastlane match lifecycle event: revoke or replace the affected certificate, regenerate the matching profiles, and verify team and bundle identifiers before CI uses them. Avoid manual ad-hoc certificate sharing as the normal renewal path.
- [How to Add inline images with text in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-add-inline-images-with-text-in-swiftui) — 2020-08-08
  **NeKI brief:** Embed an Image in a Text composition for inline symbols that share typography, wrapping, and baseline behavior with surrounding text. Prefer this over an HStack when the image is part of one sentence or label rather than a separately laid-out control.
- [How to declare Swift protocol for a specific class | Sarunw](https://sarunw.com/posts/how-to-declare-swift-protocol-for-specific-class) — 2020-08-04
  **NeKI brief:** Restricts a Swift protocol to a particular class hierarchy with inheritance constraints, allowing specialized requirements while preserving compile-time conformance checks and avoiding runtime type switching.
- [A new way to manage the back button title in iOS 14 with backButtonDisplayMode | Sarunw](https://sarunw.com/posts/new-way-to-manage-back-button-title-in-ios14) — 2020-07-27
  **NeKI brief:** Explains UINavigationItem.backButtonDisplayMode and the title sources it controls, including default, generic, and minimal behavior. It helps change a pushed screen's back label through the navigation item rather than replacing the system back button.
- [SVG image assets supported in Xcode 12 | Sarunw](https://sarunw.com/posts/svg-image-assets-supported-in-xcode12) — 2020-07-19
  **NeKI brief:** Explains importing SVG artwork into an Xcode asset catalog, its PDF-like vector treatment, and the format's practical limitations. Use it to align a designer handoff with asset-catalog packaging while validating rendering and platform support against the current Xcode toolchain.
- [Cross-promote apps with SKOverlay | Sarunw](https://sarunw.com/posts/cross-promote-apps-with-skoverlay) — 2020-07-10
  **NeKI brief:** Present an SKOverlay to cross-promote an App Store app from UIKit or SwiftUI while letting StoreKit control the purchase and dismissal experience. Tie presentation to a relevant success moment, and avoid treating the overlay as a guaranteed full-screen navigation step.
- [UIToolbar in SwiftUI | Sarunw](https://sarunw.com/posts/uitoolbar-in-swiftui) — 2020-07-06
  **NeKI brief:** Place bottom-bar actions in SwiftUI with toolbar and explicit ToolbarItem placements, keeping action semantics in the view hierarchy. When adapting older navigation code, distinguish the toolbar's presentation policy from the individual actions rather than manually recreating UIKit bar-button layout.
- [Custom navigation bar title view in SwiftUI | Sarunw](https://sarunw.com/posts/custom-navigation-bar-title-view-in-swiftui) — 2020-07-05
  **NeKI brief:** Place a custom inline navigation title in a principal ToolbarItem so SwiftUI keeps it within the navigation bar's layout contract. Keep the content compact and resilient to dynamic type, because the principal slot competes with back and trailing controls.
- [A first look at matchedGeometryEffect | Sarunw](https://sarunw.com/posts/a-first-look-at-matchedgeometryeffect) — 2020-07-01
  **NeKI brief:** Use matchedGeometryEffect with a shared Namespace to animate elements that preserve identity across layouts. Keep both endpoints in the same hierarchy when possible, and test navigation or sheet transitions separately because matching has presentation-boundary limitations.
- [Add custom SwiftUI view to View Library with LibraryContentProvider | Sarunw](https://sarunw.com/posts/add-custom-swiftui-view-to-view-library) — 2020-06-24
  **NeKI brief:** Registers custom SwiftUI views with the Xcode library. Use it when reusable components should be discoverable to designers or developers through the IDE.
- [SwiftUI's Toggle Customization | Sarunw](https://sarunw.com/posts/swiftui-toggle-customization) — 2020-06-21
  **NeKI brief:** Builds a reusable ToggleStyle by first modeling the control's binding and interaction directly, then moving the appearance into a style configuration. Use it to create a custom toggle without losing the semantic state transition that makes a standard Toggle accessible and composable.
- [Easy way to detect a retain cycle in a view controller | Sarunw](https://sarunw.com/posts/easy-way-to-detect-retain-cycle-in-view-controller) — 2020-06-16
  **NeKI brief:** Detect a suspected view-controller retain cycle by asserting that deinit runs after dismissal, using a symbolic breakpoint or targeted diagnostic instead of leaving print statements in source. This is a fast ownership check before escalating to Instruments for the retaining path.
- [Sleep sort: A sorting algorithm without compare | Sarunw](https://sarunw.com/posts/sleep-sort-sorting-algorithm-without-compare) — 2020-06-14
  **NeKI brief:** Uses sleep sort as a deliberately impractical concurrency illustration. Use it to reason about ordering, task scheduling, and why timing is not a valid general sorting mechanism.
- [Animation delay and repeatForever in SwiftUI | Sarunw](https://sarunw.com/posts/animation-delay-and-repeatforever-in-swiftui) — 2020-06-11
  **NeKI brief:** Compose delay and repeatForever in the intended order, because delaying the animation versus delaying each repeated cycle produces different timing. Decide whether reversal belongs in the repeating animation, then trigger the state change once instead of coordinating manual timers.
- [How to request a user's location | Sarunw](https://sarunw.com/posts/how-to-request-user-location) — 2020-06-08
  **NeKI brief:** Request one current location with CLLocationManager after the appropriate authorization state and usage-description key are in place. Handle both didUpdateLocations and didFailWithError, choose accuracy deliberately, and avoid continuous updates when a single fix is sufficient.
- [What is backIndicatorTransitionMaskImage | Sarunw](https://sarunw.com/posts/what-is-backindicatortransitionmaskimage) — 2020-06-04
  **NeKI brief:** Explains UIKit's backIndicatorTransitionMaskImage and its role in navigation-bar back indicator transitions. Use it when customizing the back glyph without breaking transition rendering.
- [How to change a back button image | Sarunw](https://sarunw.com/posts/how-to-change-back-button-image) — 2020-05-31
  **NeKI brief:** Shows changing a UINavigationBar back-button image. Use it when branding navigation while preserving hit targets, tint behavior, and standard back navigation semantics.
- [Responsive design with UIStackView | Sarunw](https://sarunw.com/posts/responsive-design-with-uistackview) — 2020-05-27
  **NeKI brief:** Uses UIStackView for responsive UIKit layouts. Use it when orientation or size-class changes should reorganize content through constraints rather than separate view-controller implementations.
- [Match a view's shadow to the Sketch shadow | Sarunw](https://sarunw.com/posts/match-view-shadow-to-sketch-shadow) — 2020-05-20
  **NeKI brief:** Translates Sketch blur and spread settings into UIKit shadow radius, offset, opacity, and an optional shape-based spread layer. It is useful when visual specifications cannot be matched by assigning design-tool values directly to CALayer properties.
- [Different ways to check for String suffix in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-check-string-suffix-in-swift) — 2020-05-17
  **NeKI brief:** Use hasSuffix to test a known ending and suffix to extract a bounded trailing substring. The length is a maximum, so these APIs remain safe for short input while preserving Swift String's grapheme-aware indexing model.
- [Decode an array with a corrupted element | Sarunw](https://sarunw.com/posts/decode-array-with-corrupted-element) — 2020-05-15
  **NeKI brief:** Codable normally fails an entire array when one element violates its schema, which is the right default for controlled APIs. For legacy or third-party data, decode elements through a lossy optional wrapper, discard failures deliberately, and log the data-quality trade-off.
- [How to set cornerRadius for only some corners | Sarunw](https://sarunw.com/posts/how-to-set-corner-radius-for-some-corners) — 2020-05-13
  **NeKI brief:** Round selected UIKit corners with CALayer maskedCorners on supported systems, or derive a UIBezierPath mask after bounds are final. Reapply path-based masks during layout changes, since creating them before final sizing produces incorrect geometry.
- [How to set status bar style | Sarunw](https://sarunw.com/posts/how-to-set-status-bar-style) — 2020-05-11
  **NeKI brief:** For UIKit status-bar changes, return the appropriate preferredStatusBarStyle from the responsible view controller and call setNeedsStatusBarAppearanceUpdate when state changes. Keep view-controller-based status-bar appearance enabled so the system consults that policy rather than a global fixed setting.
- [Different ways to check for String prefix in Swift | Sarunw](https://sarunw.com/posts/different-ways-to-check-string-prefix-in-swift) — 2020-05-09
  **NeKI brief:** Use hasPrefix when testing a known String prefix, and prefix when extracting a bounded leading substring. Treat the length as a maximum rather than assuming input is long enough, and retain String's index-safe APIs instead of integer offset arithmetic.
- [How to compare two app version strings in Swift | Sarunw](https://sarunw.com/posts/how-to-compare-two-app-version-strings-in-swift) — 2020-05-08
  **NeKI brief:** Compare app version strings as numeric components rather than ordinary lexical strings, so versions such as 1.10 sort after 1.9. Define how missing components, prerelease values, and build numbers participate before using the result for update or migration policy.
- [How to split a string into an array of substrings in Swift | Sarunw](https://sarunw.com/posts/how-to-split-string-into-array-of-substrings-in-swift) — 2020-05-07
  **NeKI brief:** Use components(separatedBy:) when empty fields and multi-character separators matter, or String.split when empty subsequences should be omitted. Choose a CharacterSet for several delimiters, then normalize or validate fields before treating a split result as structured input.
- [How to make multi-line text in UIButton | Sarunw](https://sarunw.com/posts/how-to-make-multi-line-text-in-uibutton) — 2020-05-06
  **NeKI brief:** Allow a UIButton title to wrap by configuring its title label and layout constraints for multiple lines, then test with long localized strings. The button's content insets, image placement, and compression priorities determine whether the text actually receives usable width.
- [History of Auto Layout constraints | Sarunw](https://sarunw.com/posts/history-of-auto-layout-constraints) — 2020-04-29
  **NeKI brief:** Prefer modern Auto Layout anchors or constraint activation APIs over older verbose construction and third-party wrappers when standard APIs express the relationship clearly. Keep constraints grouped by layout intent, so changes reveal which spacing, alignment, or size rule is responsible.
- [How to preserve a struct memberwise initializer when you have a custom initializer | Sarunw](https://sarunw.com/posts/how-to-preserve-memberwise-initializer) — 2020-04-21
  **NeKI brief:** Preserve a struct's memberwise initializer by moving custom construction into an extension rather than declaring it in the type body. This keeps ergonomic internal construction available while still allowing a domain-specific initializer that validates or transforms selected inputs.
- [Memberwise Initializers for Structure Types | Sarunw](https://sarunw.com/posts/memberwise-initializers-for-structure-types) — 2020-04-16
  **NeKI brief:** Explains how stored-property defaults and access choices affect Swift's synthesized memberwise initializer. It helps preserve ergonomic struct construction while deciding which properties should remain configurable, receive defaults, or be hidden behind a custom initializer.
- [How to display HTML in UILabel and UITextView | Sarunw](https://sarunw.com/posts/how-to-display-html-in-uilabel-and-uitextview) — 2020-04-14
  **NeKI brief:** Converts HTML into NSAttributedString for UILabel or UITextView, then applies app styling around the rendered value when a backend supplies marked-up text without embedding a web view.
- [How to remove text from a navigation bar back button | Sarunw](https://sarunw.com/posts/how-to-remove-text-from-uinavigationbar-back-button) — 2020-04-08
  **NeKI brief:** Control a pushed navigation bar's back-label through the previous controller's navigation item, using an empty backButtonTitle when the chevron should remain without text. Keep the system back behavior intact instead of replacing it with a custom gesture or button.
- [tintColor | Sarunw](https://sarunw.com/posts/tintcolor) — 2020-03-25
  **NeKI brief:** Use UIKit tintColor as an inherited semantic accent, overriding it at the narrowest view or window scope that matches the intended theme. Custom views that derive their rendering from tint should respond in tintColorDidChange rather than caching the initial color.
- [SwiftUI ButtonStyle | Sarunw](https://sarunw.com/posts/swiftui-buttonstyle) — 2020-03-22
  **NeKI brief:** Moves reusable SwiftUI button appearance from repeated modifiers into a ButtonStyle implementation and its configuration state. Use it when pressed-state behavior and visual rules must travel together across buttons, rather than copying a design-specific modifier chain into every call site.
- [SF Symbols: What is it, and how to use? | Sarunw](https://sarunw.com/posts/sf-symbols-1) — 2020-03-17
  **NeKI brief:** Introduces SF Symbols as text-aligned system imagery and shows configuration through fonts, weights, scales, and preferredSymbolConfiguration in UIKit and SwiftUI. Use it when symbol geometry must track surrounding typography, then confirm the desired symbol and availability for the deployment target.
- [How to create code snippets in Xcode | Sarunw](https://sarunw.com/posts/how-to-create-code-snippets-in-xcode) — 2020-03-12
  **NeKI brief:** Creates and manages Xcode code snippets with placeholders, autocomplete, and drag-and-drop, turning repeated source patterns into editable local templates rather than copying fragile boilerplate between files.
- [Class-only Protocols: class or AnyObject | Sarunw](https://sarunw.com/posts/class-only-protocols-class-or-anyobject) — 2020-03-09
  **NeKI brief:** Constrain a protocol with AnyObject when it represents reference-only behavior such as a weak delegate. This replaces the deprecated class spelling while preserving the ownership requirement the compiler needs before a property can be declared weak.
- [How to remove Cocoapods from your project | Sarunw](https://sarunw.com/posts/how-to-remove-cocoapods-from-your-project) — 2020-03-06
  **NeKI brief:** Remove CocoaPods integration by deintegrating the Xcode project and deleting generated Pods, lockfile, workspace, and no-longer-needed Podfile artifacts. Reopen the project rather than the workspace, then replace dependencies deliberately so stale build settings and linked frameworks are not retained.
- [How to read a Property List (plist) into the code | Sarunw](https://sarunw.com/posts/how-to-read-plist-file) — 2020-03-03
  **NeKI brief:** Load a bundled property-list resource through Bundle, then decode its data with PropertyListSerialization into the expected dictionary or array shape. Keep the resource name and schema explicit, and treat decode failure as configuration validation rather than force-casting arbitrary values.
- [How to create Activity Ring in SwiftUI | Sarunw](https://sarunw.com/posts/how-to-create-activity-ring-in-swiftui) — 2020-02-17
  **NeKI brief:** Builds a SwiftUI activity ring by decomposing arcs, progress trimming, rotation, gradients, and layered shapes, showing how a complex visual control emerges from independently testable drawing pieces.
- [Testing Remote Push Notification in iOS simulator | Sarunw](https://sarunw.com/posts/testing-remote-push-notification-in-ios-simulator) — 2020-02-10
  **NeKI brief:** Demonstrates remote push testing on an iOS Simulator using an APNs JSON payload and xcrun simctl push. The workflow covers selecting a booted device or identifier and drag-and-drop alternatives, enabling repeatable notification and deep-link checks without a physical device.
- [Gradient in SwiftUI | Sarunw](https://sarunw.com/posts/gradient-in-swiftui) — 2020-02-05
  **NeKI brief:** Render gradient SwiftUI text with a mask on earlier systems or foregroundStyle on iOS 15 and later. Gate the simpler API by availability, and align the gradient to the text bounds so layout changes do not produce unintended color placement.
- [SwiftUI basic Shape operations | Sarunw](https://sarunw.com/posts/swiftui-basic-shape-operations) — 2020-02-01
  **NeKI brief:** Demonstrates how SwiftUI Shape operations such as fill, inset, offset, rotation, scale, stroke, strokeBorder, and trim compose custom drawing. Use it to build a visual primitive from geometry and ShapeStyle before reaching for a bespoke Canvas or image asset.
- [Intrinsic content size in SwiftUI | Sarunw](https://sarunw.com/posts/intrinsic-content-size-in-swiftui) — 2020-01-29
  **NeKI brief:** Separates SwiftUI's proposed-size layout from UIKit-style intrinsic sizing by comparing frame constraints and fixedSize. It shows how to preserve a view's ideal dimension or deliberately override it, rather than treating every frame as a hard content size.
- [Sign in with Apple Tutorial, Part 4: Web and Other Platforms | Sarunw](https://sarunw.com/posts/sign-in-with-apple-4) — 2020-01-22
  **NeKI brief:** Extends Sign in with Apple to web or cross-platform flows. Follow it when coordinating redirect URIs, authorization-code exchange, and shared account identity across native and browser-based clients.
- [Print unescaped string output in Swift | Sarunw](https://sarunw.com/posts/print-unescaped-string) — 2020-01-12
  **NeKI brief:** When LLDB po escapes quotes and newlines in a Swift String, wrap the value as NSString or invoke print from the debugger to see copyable text. This is particularly useful when checking serialized JSON for malformed formatting without confusing debugger representation with stored content.
- [Sign in with Apple Tutorial, Part 3: Backend – Token verification | Sarunw](https://sarunw.com/posts/sign-in-with-apple-3) — 2020-01-06
  **NeKI brief:** Covers server-side verification of Sign in with Apple identity tokens. Use it to separate client authorization from backend trust decisions and to validate issuer, audience, nonce, and token expiry correctly.
- [Inset grouped List in SwiftUI | Sarunw](https://sarunw.com/posts/inset-grouped-in-swiftui) — 2019-12-30
  **NeKI brief:** Explains the version-dependent way to obtain an inset-grouped List appearance in SwiftUI, comparing the early iOS 13.2 path with the iOS 14 list-style API. It helps avoid styling code that is correct only for one deployment target.
- [What is @discardableResult | Sarunw](https://sarunw.com/posts/what-is-discardableResult) — 2019-12-27
  **NeKI brief:** Mark a return value @discardableResult only when callers may legitimately use an operation for its side effect or choose to inspect its result. Preserve ordinary unused-result warnings for values that signal required handling, so the annotation does not hide accidental omissions.
- [Sign in with Apple Tutorial, Part 2: Private Email Relay Service | Sarunw](https://sarunw.com/posts/sign-in-with-apple-2) — 2019-12-22
  **NeKI brief:** Explains Sign in with Apple's private email relay implications and user-facing account data. Follow it when storing identity attributes and designing communication paths that do not assume a real email address.
- [SwiftUI Animation | Sarunw](https://sarunw.com/posts/swiftui-animation) — 2019-12-18
  **NeKI brief:** Relates SwiftUI state changes to animations, timing curves, transitions, and asymmetric effects through small view examples. Use it to reason about which state-driven changes should animate together, while adapting the older animation modifier syntax to the target SwiftUI release.
- [Sign in with Apple Tutorial, Part 1: Apps | Sarunw](https://sarunw.com/posts/sign-in-with-apple-1) — 2019-12-11
  **NeKI brief:** Introduces Sign in with Apple configuration and the authorization request flow. Use it to route capability setup, nonce handling, and credential state before implementing account creation or session restoration.
- [Manually symbolicate crash reports | Sarunw](https://sarunw.com/posts/symbolicate-crash-reports) — 2019-12-05
  **NeKI brief:** Walks through manually symbolicating an iOS crash report by locating the matching dSYM and applying the symbolication tools to unsymbolicated addresses. It is useful for diagnosing crashes when an external reporting service has not already resolved the stack frames.
- [Swift Documentation | Sarunw](https://sarunw.com/posts/swift-documentation) — 2019-11-30
  **NeKI brief:** Covers Swift documentation comments as they surface in Quick Help and code completion, including summaries, parameters, returns, throws, and generated documentation. Use it to make an API's contract discoverable at the call site instead of leaving callers to infer behavior from implementation details.
- [Unwrap optional values in XCTest with XCTUnwrap | Sarunw](https://sarunw.com/posts/unwrap-optional-values-in-xctest-with-xctunwrap) — 2019-11-18
  **NeKI brief:** Use XCTUnwrap in a throwing XCTest when an optional is required before subsequent assertions. It records a focused failure at the unwrap site and supplies the non-optional value, avoiding optional-chaining assertions that obscure which setup condition failed.
- [// MARK: - What is it? | Sarunw](https://sarunw.com/posts/mark-what-is-it) — 2019-11-14
  **NeKI brief:** Explains how // MARK comments create named sections in Xcode's source navigator and jump menu, including common variations. It is a small but concrete organization technique for separating extensions, lifecycle code, and feature areas without affecting runtime behavior.
- [Dark color cheat sheet | Sarunw](https://sarunw.com/posts/dark-color-cheat-sheet) — 2019-11-11
  **NeKI brief:** Choose semantic background, label, separator, tint, and grayscale colors according to their interface roles rather than fixed RGB values. The role-based palette preserves visual hierarchy across Dark Mode and accessibility contrast settings, while custom colors still require both-mode validation.
- [Github Actions for iOS projects | Sarunw](https://sarunw.com/posts/github-actions-for-ios-projects) — 2019-11-04
  **NeKI brief:** Set up iOS CI in GitHub Actions with repository workflow files that build, test, collect relevant failure artifacts, and control distribution credentials. Keep signing and TestFlight delivery isolated from ordinary validation jobs so pull-request feedback stays fast and secrets remain scoped.
- [if let: How not to use it | Sarunw](https://sarunw.com/posts/if-let-how-not-to-use-it) — 2019-11-02
  **NeKI brief:** Questions optional binding used only as a disguised Boolean test and favors control flow that exposes the real intent. The contrast is useful when reviewing Swift code that unwraps a value even though its payload is never needed.
- [Dark color | Sarunw](https://sarunw.com/posts/dark-color) — 2019-10-28
  **NeKI brief:** Use semantic and dynamic UIKit colors so foregrounds, backgrounds, separators, and tint adapt with the active trait collection. Apply explicit overrides only for intentional brand treatment, then verify contrast and hierarchy in both appearances rather than inverting a light palette.
- [Take a screenshot and record a video in iOS Simulator | Sarunw](https://sarunw.com/posts/take-screenshot-and-record-video-in-ios-simulator) — 2019-10-24
  **NeKI brief:** Shows the built-in Simulator workflows for capturing screenshots and recording video, without introducing external tooling. It is a concise reference for producing reproducible visual evidence during UI development, demos, and bug reports.
- [UINavigationBar changes in iOS13, Part2: UISearchController | Sarunw](https://sarunw.com/posts/uinavigationbar-changes-in-ios13-part2) — 2019-10-23
  **NeKI brief:** Continues iOS 13 navigation-bar migration with appearance customization details and compatibility considerations. Use it when reconciling legacy bar properties with UINavigationBarAppearance across deployment targets.
- [Data in SwiftUI, Part 3: Tools | Sarunw](https://sarunw.com/posts/data-in-swiftui-3) — 2019-10-15
  **NeKI brief:** Introduces SwiftUI's data flow concepts and explains why state ownership matters in declarative views. Follow it when deciding where observable data belongs and how bindings should cross view boundaries.
- [Data in SwiftUI, Part 2: Views as a function of data | Sarunw](https://sarunw.com/posts/data-in-swiftui-2) — 2019-10-12
  **NeKI brief:** Explores passing and observing data across SwiftUI view hierarchies. Follow it when a screen needs shared model state but should keep mutation authority explicit and testable.
- [Data in SwiftUI, Part 1: Data | Sarunw](https://sarunw.com/posts/data-in-swiftui-1) — 2019-10-09
  **NeKI brief:** Covers foundational SwiftUI data and state property wrappers. Use it to route ownership, mutation, and binding decisions before adding persistence or observable-object coordination.
- [UINavigationBar changes in iOS13 | Sarunw](https://sarunw.com/posts/uinavigationbar-changes-in-ios13) — 2019-09-19
  **NeKI brief:** Details iOS 13 UINavigationBar appearance changes and the new appearance APIs. Follow it when a navigation bar unexpectedly changes styling after deployment and you need deterministic standard, compact, and scroll-edge configuration.
- [Adopting iOS Dark Mode | Sarunw](https://sarunw.com/posts/adopting-ios-dark-mode) — 2019-09-13
  **NeKI brief:** Adopt Dark Mode with semantic colors, adaptive images, and trait-aware overrides instead of maintaining separate fixed palettes. Test both appearances as first-class states, because hard-coded colors and cached assets can break hierarchy or contrast after a mode change.
- [Modality changes in iOS13 | Sarunw](https://sarunw.com/posts/modality-changes-in-ios13) — 2019-09-01
  **NeKI brief:** Explains iOS 13's default card-style modal presentation and how it changes dismissal behavior. Use it when migrating UIKit or SwiftUI flows that relied on full-screen assumptions or custom interactive transitions.
- [Custom UIHostingController | Sarunw](https://sarunw.com/posts/custom-uihostingcontroller) — 2019-08-27
  **NeKI brief:** Subclass UIHostingController when a SwiftUI root view must participate in a storyboard or UIKit controller flow. Keep UIKit lifecycle and navigation ownership in the controller, while passing only the required model or callbacks into the SwiftUI root view.
- [SwiftUI's ViewModifier | Sarunw](https://sarunw.com/posts/swiftui-viewmodifier) — 2019-08-20
  **NeKI brief:** Explains ViewModifier and ModifiedContent through a simple reusable modifier, then extends it with state and animation. Use it to package a repeated SwiftUI transformation behind a meaningful API, keeping modifier-specific state local instead of duplicating chains throughout a screen.
- [How to use SwiftUI in UIKit | Sarunw](https://sarunw.com/posts/swiftui-in-uikit) — 2019-07-26
  **NeKI brief:** Embeds SwiftUI in an existing UIKit hierarchy with UIHostingController, covering programmatic setup, storyboard creation, child-controller containment, and view sizing. Use it for incremental adoption where UIKit owns navigation, while treating the article's prototype-era binding example as historical context.
- [Better dependency injection for Storyboards in iOS13 | Sarunw](https://sarunw.com/posts/better-dependency-injection-for-storyboards-in-ios13) — 2019-07-12
  **NeKI brief:** Inject storyboard dependencies through @IBSegueAction during controller initialization instead of exposing mutable properties for post-instantiation setup. This makes required collaborators explicit before the destination loads and prevents a storyboard flow from reaching an incompletely configured controller.
- [How to use UIKit in SwiftUI | Sarunw](https://sarunw.com/posts/uikit-in-swiftui) — 2019-06-30
  **NeKI brief:** Bridge an existing UIKit control into SwiftUI with UIViewRepresentable, creating it in makeUIView and synchronizing SwiftUI state in updateUIView. Use a Coordinator for delegate or target-action callbacks, so imperative events return through bindings instead of bypassing SwiftUI ownership.
- [Browse SF Symbols on Mac | Sarunw](https://sarunw.com/posts/browse-sf-symbols) — 2019-06-19
  **NeKI brief:** Use Apple's SF Symbols app to find canonical symbol names, inspect rendering variants, and verify availability before coding UIKit or SwiftUI icons. Prefer system symbol configuration over baked images so weight, scale, color, and accessibility behavior remain platform-adaptive.
- [Introduction to Coordinator | Sarunw](https://sarunw.com/posts/introduction-to-coordinator) — 2019-01-09
  **NeKI brief:** Uses a shopping-flow example to move navigation decisions out of individual view controllers into a coordinator. This makes screen transitions, child-flow ownership, and dependency assembly explicit instead of distributing routing knowledge throughout the UI layer.
- [Enum & custom type from primitive JSON type | Sarunw](https://sarunw.com/posts/enum-custom-type-from-primitive-json-type) — 2018-12-18
  **NeKI brief:** Map primitive JSON values to typed Swift enums by giving the enum a raw value and Codable conformance, then add custom decoding only for irregular payloads. This keeps wire values centralized and prevents stringly typed status checks from spreading through the model layer.
- [Codable in Swift 4.0 | Sarunw](https://sarunw.com/posts/codable-in-swift-4) — 2017-07-09
  **NeKI brief:** Model JSON with Codable using optionals, CodingKeys, and custom encode or decode logic only where the wire format differs from the Swift API. Keep schema exceptions at that boundary, so the rest of the app sees typed values instead of dictionary parsing.
- [Where is my getter/setter in Swift? | Sarunw](https://sarunw.com/posts/where-is-my-getter-setter-swift) — 2014-06-05
  **NeKI brief:** Express Swift getter and setter behavior with computed properties or property observers, while recognizing that observers do not run for every initialization path. Put invariants in initialization or dedicated mutation APIs when they must hold regardless of how stored state is established.
