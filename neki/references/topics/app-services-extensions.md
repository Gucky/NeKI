# App Services & Extensions

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** System-integrated app capabilities including extensions, notifications, widgets, App Clips, background execution, and shared activities.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **44**

## Direct-source reading

- [Fitting the Lapse experience into 15 MegaBytes](https://blog.jacobstechtavern.com/p/get-lapse-under-15mb) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-04-21T14:02:35.921Z`
  **NeKI brief:** Describes reducing an App Clip to a 15 MB footprint through resource and dependency choices. It is a concrete optimization case study for size-constrained targets; recheck current App Clip limits before applying it.
- [Sending trial notifications with provisional authorization on iOS](https://nilcoalescing.com/blog/TrialNotificationsWithProvisionalAuthorizationOnIOS) — Nil Coalescing · article catalogue
  **Published:** `2025-03-31`
  **NeKI brief:** Uses provisional notification authorization to trial notifications before asking for full permission. Useful for measuring engagement while delaying a disruptive prompt until the user has seen value.
- [Setting up SharePlay on an iOS app](https://www.polpiella.dev/setting-up-shareplay-on-an-ios-app-from-scratch) — Pol Piella · article catalogue
  **Published:** `2024-02-07T00:00:00.000Z`
  **NeKI brief:** SharePlay coordinates a group session through GroupActivities, where an activity declares metadata and participants join through system UI. The implementation must separate session lifecycle from app content so interruptions and late joins remain recoverable.
- [MusicKit and App Clips](https://www.polpiella.dev/musickit-and-app-clips) — Pol Piella · article catalogue
  **Published:** `2023-09-27T00:00:00.000Z`
  **NeKI brief:** MusicKit in an App Clip must respect both App Clip size and authorization constraints, so the feature should request only the catalog data needed for the immediate task. The integration highlights capability and entitlement boundaries.
- [How to create an App Clip for your app](https://www.polpiella.dev/create-app-clips) — Pol Piella · article catalogue
  **Published:** `2023-09-20T00:00:00.000Z`
  **NeKI brief:** An App Clip packages a focused invocation path with associated domains and an App Clip target, then hands off to the full app when installed. The workflow makes size, entitlement, and shared-data boundaries part of feature design.
- [Scheduling daily notifications on iOS using Calendar and DateComponents](https://www.donnywals.com/scheduling-daily-notifications-on-ios-using-calendar-and-datecomponents) — Donny Wals · article catalogue
  **Published:** `2019-12-12T07:45:26+00:00`
  **NeKI brief:** Calendar notification triggers model recurring local delivery through date components, but authorization, timezone, and missed-trigger behavior need product decisions.
- [Adding haptic feedback to your app with CoreHaptics – Donny Wals](https://www.donnywals.com/adding-haptics-to-your-app) — Donny Wals · article catalogue
  **Published:** `2019-11-27T08:00:43+00:00`
  **NeKI brief:** Haptic feedback reinforces direct interactions through system generators, but timing and intensity should support meaning rather than add incidental vibration.
- [Updating your apps with silent push notifications – Donny Wals](https://www.donnywals.com/updating-your-apps-with-silent-push-notifications) — Donny Wals · article catalogue
  **Published:** `2019-11-20T08:00:03+00:00`
  **NeKI brief:** Silent pushes can request background refresh without user interruption, but delivery is best-effort and needs a fallback for stale app data.
- [Service workers are awesome – Donny Wals](https://www.donnywals.com/service-workers-are-awesome) — Donny Wals · article catalogue
  **Published:** `2015-03-29T15:18:57+00:00`
  **NeKI brief:** Service workers intercept web requests for offline caching and background behavior, but update lifecycle and stale-content strategy must be designed deliberately.
- [How to Debug an App That Was Launched by Push Notification or URL Handler – Ole Begemann](https://oleb.net/blog/2010/05/how-to-debug-app-launched-by-remote-event) — Ole Begemann · article catalogue
  **Published:** `2010-05-06T21:17:00Z`
  **NeKI brief:** Shows two launch-debugging strategies for URL handlers and push events: inspect persistent logs when no debugger is attached, or configure the debugger to wait for the next process launch and stop at lifecycle breakpoints. Update the historical Xcode UI steps for current tooling.
- [Quick guide on local notifications for iOS](https://tanaschita.com/ios-local-notifications-guide) — Tanaschita · article catalogue
  **NeKI brief:** Local notification scheduling covers authorization, content and trigger configuration through UserNotifications. It is useful for separating scheduling policy from presentation, especially when permissions are denied or requests become stale.
- [Scheduling notifications with time, calendar, and location triggers in iOS](https://tanaschita.com/ios-local-notification-triggers) — Tanaschita · article catalogue
  **NeKI brief:** Configures local notification triggers based on time intervals, calendar dates, and locations. Useful for choosing the correct UNNotificationTrigger and validating repeat behavior instead of scheduling every reminder identically.
- [Developer guide on App Clips for iOS](https://tanaschita.com/20230424-app-clips) — Tanaschita · article catalogue
  **NeKI brief:** This App Clip guide connects invocation, associated domains and a focused task flow. It is useful for designing a small install-free experience that can hand off state cleanly to the full app.
- [Cheatsheet for the JSON payload of an iOS push notification](https://tanaschita.com/20230417-cheatsheet-for-anatomy-of-ios-push-notifications) — Tanaschita · article catalogue
  **NeKI brief:** The push payload cheatsheet distinguishes alert, sound, badge and custom data fields. Follow it when debugging delivery behavior, keeping payload size, background execution and sensitive content constraints visible.
- [Designing Better Notifications](https://martiancraft.com/blog/2018/04/designing-better-notifications) — MartianCraft · article catalogue
  **NeKI brief:** Notification design is treated as a constrained interaction surface: communicate context quickly, offer meaningful actions, and avoid turning alerts into noise. The guidance helps audit payload content and user interruption cost.
- [Notification Handling on WatchKit](https://martiancraft.com/blog/2018/02/notification-handling-on-watchkit) — MartianCraft · article catalogue
  **NeKI brief:** WatchKit notifications are treated as a primary interaction surface, with actionable content and concise context rather than miniature app screens. The demo-oriented guidance helps validate payload handling across local and push notification paths.
- [Managing Across Time](https://martiancraft.com/blog/2015/04/managing-time) — MartianCraft · article catalogue
  **NeKI brief:** Coordinate distributed engineering through written handoffs, visible task state, agreed overlap windows, and explicit contact expectations instead of rigid local-hour schedules. This preserves timezone flexibility while keeping decisions and dependencies from stalling.

## Newsletter and related leads

- [3 Key Strategies to Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — SwiftUI Weekly · SwiftUI Weekly - Issue #233 — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **Published:** `2026-05-11T08:48:00.658Z`
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [SwiftUI Live Activity Broadcast Push Notifications](https://medium.com/@itsuki.enjoy/swiftui-live-activity-broadcast-push-notifications-1fcf4418f87b) — Those Who Swift · Issue 246 — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **Published:** `2025-12-24`
  **NeKI brief:** Examines SwiftUI Live Activity Broadcast Push Notifications, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Active ReviewSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 289 — Source repository · Topics: App Services & Extensions · Developer Tools · Swift
  **Published:** `2025-09-16T14:09:42.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Testing Remote Push Notifications with iOS Simulators](https://www.tiagohenriques.dev/blog/testing-push-notifications-ios-simulators) — SwiftLee Weekly · Issue 272 — Article · Topics: App Services & Extensions · Testing · Xcode
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Explains Testing Remote Push Notifications with iOS Simulators, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: App Services & Extensions · Swift · Testing
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: App Services & Extensions · Swift · Testing
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Updating your apps with silent push notifications](https://www.donnywals.com/updating-your-apps-with-silent-push-notifications?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: App Services & Extensions · Swift · Testing
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** Silent pushes can request background refresh without user interruption, but delivery is best-effort and needs a fallback for stale app data.
- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: App Services & Extensions · Developer Tools
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** MBProgressHUD presents an overlay progress indicator over UIKit content while background work runs. Use it for legacy UIKit flows that need an explicit blocking-progress affordance, while ensuring cancellation and accessibility remain available.
- [Building chat and struggling with state, push notifications, and more? 🤓💬](https://getstream.io/tutorials/ios-chat) — iOS Dev Weekly · Issue 671 — Tutorial · Topics: App Services & Extensions · Graphics, Media & Games
  **Published:** `26th July 2024`
  **NeKI brief:** Walks through integrating Stream's chat SDK into an iOS app, including message UI and networking. Useful as an implementation reference when evaluating managed real-time messaging.
- [Your Complete Guide to Push Notifications in SwiftUI](https://medium.com/@jpmtech/your-complete-guide-to-push-notifications-in-swiftui-8a13f5588662) — SwiftUI Weekly · SwiftUI Weekly - Issue #188 — Tutorial · Topics: App Services & Extensions · Swift · SwiftUI
  **Published:** `2024-05-27T10:42:14.070Z`
  **NeKI brief:** Walks through push-notification registration and handling in a SwiftUI app. Useful for connecting authorization, device tokens, and notification-driven navigation into app lifecycle code.
- [Parse Platform](https://parseplatform.org/) — iOS Dev Tools · iOS Dev tools: Chime, Parse Platform, Veertu — Article · Topics: App Services & Extensions
  **Published:** `2024-04-18T13:45:11.063Z`
  **NeKI brief:** Parse Platform is an open-source backend stack with APIs, SDKs, and self-hosting options. Evaluate it when comparing managed versus owned backend responsibilities for mobile applications.
- [How to cancel a background task in Swift](https://swdevnotes.com/swift/2023/how-to-cancel-a-background-task-in-swift) — iOS Dev Weekly · Issue 595 — Article · Topics: App Services & Extensions · Swift
  **Published:** `3rd February 2023`
  **NeKI brief:** Explores How to cancel a background task in Swift, focusing on have you ever thought, i know i can cancel background. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How to build a configurable widget with WidgetKit and SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3RhbmFzY2hpdGEuY29tLzIwMjIwOTA1LWhvdy10by1idWlsZC1hLWNvbmZpZ3VyYWJsZS13aWRnZXQtd2l0aC13aWRnZXRraXQtYW5kLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjJlMDk0NDEtYjQ5ZC00NjY2LWJkZjQtY2EwMTVlY2ZhN2IxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjM2FjOGE0LTVhOGEtNDNkZS1iZjc4LWMwZWI1M2YxZmVmNSIsImlhdCI6MTY3NDA2MjU1OC4wOTYsImlzcyI6Im9yY2hpZCJ9.rMp3X_sYwUx7J0iCHmj_IUI8W8XzqKIELF-qKAwhWbE) — SwiftUI Weekly · SwiftUI Weekly - Issue #114 — Article · Topics: Product Design · Swift · SwiftUI
  **Published:** `2022-09-13T16:37:55.000Z`
  **NeKI brief:** Builds a configurable WidgetKit widget with SwiftUI configuration and timeline data. Useful for connecting user-selected widget parameters to deterministic entries and previewable widget states.
- [How to build a configurable iOS widget](https://tanaschita.com/20220905-how-to-build-a-configurable-widget-with-widgetkit-and-swiftui) — iOS Dev Weekly · Issue 575 — Article · Topics: App Intents & System Surfaces · App Services & Extensions · Swift
  **Published:** `9th September 2022`
  **NeKI brief:** Builds a configurable WidgetKit widget with SwiftUI configuration and timeline data. Useful for connecting user-selected widget parameters to deterministic entries and previewable widget states.
- [first WidgetKit article](https://tanaschita.com/20220905-building-widgets-for-ios-applications-with-widgetkit-and-swiftui) — iOS Dev Weekly · Issue 575 — Article · Topics: App Intents & System Surfaces · App Services & Extensions · Swift
  **Published:** `9th September 2022`
  **NeKI brief:** Introduces building iOS widgets with WidgetKit and SwiftUI, from the widget extension through the lightweight information it presents outside the app. A practical starting point for deciding what app state belongs in a glanceable widget experience.
- [Deploying SwiftUI on the Web](https://www.carsonkatri.com/articles/deploying-swiftui-on-the-web) — iOS Dev Weekly · Issue 531 — Article · Topics: Swift · SwiftUI
  **Published:** `29th October 2021`
  **NeKI brief:** Explores Deploying SwiftUI on the Web, focusing on i’ve linked to swiftwasm before but haven’t been keeping a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How to Create iOS 14 Widgets With WidgetKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2V4eXRlLmNvbS9ibG9nL2hvdy10by1jcmVhdGUtd2lkZ2V0cy13aXRoLXdpZGdldGtpdD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImNmZjYyNDI3LTE0NDMtNDgwZi05MTY3LTU4Nzk0Njk4MDE5ZCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJhMWQyOWY1My0xMzliLTQ0M2MtOGJmNC1jYzBmYWJiNzNmZjIiLCJpYXQiOjE2NzQwNjI2NzguMzcyLCJpc3MiOiJvcmNoaWQifQ.oxFvSu5jv-Gz7PUZapxW-Nfadb-f5DpSLiMhaLqq2b4) — SwiftUI Weekly · SwiftUI Weekly - Issue #52 — Article · Topics: Swift · SwiftUI
  **Published:** `2021-03-29T17:21:08.000Z`
  **NeKI brief:** Builds an iOS 14 WidgetKit extension and its timeline content. Follow it to understand provider configuration, placeholder snapshots, and the constraints that distinguish widget rendering from an app scene.
- [App Clips size limit](https://rambo.codes/posts/2020-08-29-turning-the-chibistudio-canvas-into-an-app-clip) — iOS Dev Weekly · Issue 472 — Article · Topics: App Services & Extensions · Developer Community & Business
  **Published:** `4th September 2020`
  **NeKI brief:** Covers App Clips size limit, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Poes](https://github.com/AvdLee/Poes) — iOS Dev Weekly · Issue 444 — Source repository · Topics: App Services & Extensions · Developer Tools · Testing
  **Published:** `21st February 2020`
  **NeKI brief:** Examines Poes, focusing on one of the best new features of xcode 11.4 is that the new simulator can easily test remote push notifications. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [What’s new in Vapor 4](https://forums.swift.org/t/whats-new-in-vapor-4/31832) — iOS Dev Weekly · Issue 435 — Article · Topics: App Services & Extensions · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** Examines What’s new in Vapor 4, focusing on talking of vapor, this week also saw a “what’s new in vapor 4” post pop up on the forums. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Spotlight Indexing for Your App Content](https://samwize.com/2019/04/26/spotlight-indexing-for-your-app-content) — iOS Dev Weekly · Issue 401 — Article · Topics: App Intents & System Surfaces · App Services & Extensions
  **Published:** `26th April 2019`
  **NeKI brief:** Examines Spotlight Indexing for Your App Content, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Parse iOS SDK](https://parse.com/products/ios) — iOS Dev Weekly · Issue 193 — Article · Topics: App Services & Extensions
  **Published:** `10th April 2015`
  **NeKI brief:** Explains Parse iOS SDK with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Learn the ropes of Mobile Services with Brent Simmons](http://www.windowsazure.com/en-us/develop/mobile/ios?WT.mc_id=azuregb_us_display_mirluna_2) — iOS Dev Weekly · Issue 88 — Article · Topics: App Services & Extensions · Product Design
  **Published:** `5th April 2013`
  **NeKI brief:** Explains Learn the ropes of Mobile Services with Brent Simmons with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [iOS Push Notifications: Best Practices](https://www.pushlayer.com/blog/2013/03/12/ios-push-notifications-best-practices) — iOS Dev Weekly · Issue 85 — Article · Topics: App Services & Extensions
  **Published:** `15th March 2013`
  **NeKI brief:** Explains iOS Push Notifications Best Practices with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Learn the ropes of Mobile Services with Brent Simmons](http://www.windowsazure.com/iOS) — iOS Dev Weekly · Issue 84 — Article · Topics: App Services & Extensions · Product Design
  **Published:** `8th March 2013`
  **NeKI brief:** Explains Windows Azure Mobile Services is a scalable backend for your iOS app with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is.
