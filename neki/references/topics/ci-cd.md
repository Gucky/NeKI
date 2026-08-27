# CI/CD & Automation

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Continuous integration, delivery pipelines, build automation, and release operations.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **229**

## Direct-source reading

- [How To Release Without Fear](https://blog.jacobstechtavern.com/p/release-without-fear) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-03-10T16:01:09.054Z`
  **NeKI brief:** Turns release confidence into an engineering system of staged rollout, observability, rollback readiness, and measurable risk, replacing one-shot deployment anxiety with feedback loops that expose regressions before broad customer impact.
- [Automate GitHub Tasks with GitHub CLI in Actions Workflows: A Step-by-Step Guide](https://www.polpiella.dev/how-to-use-the-github-cli-from-github-actions-workflows) — Pol Piella · article catalogue
  **Published:** `2024-11-14T00:00:00.000Z`
  **NeKI brief:** GitHub CLI commands in Actions can create and update issues or pull requests using the workflow token, making repository automation reproducible. The setup must scope permissions explicitly so convenience does not become an over-privileged CI credential.
- [How to install the same version of Ruby and Fastlane locally and on CI/CD](https://www.polpiella.dev/install-ruby-and-gems-on-ci-cd) — Pol Piella · article catalogue
  **Published:** `2024-10-17T00:00:00.000Z`
  **NeKI brief:** Pinning Ruby and gem versions locally and in GitHub Actions removes a hidden source of Fastlane drift. The workflow makes the toolchain reproducible by sharing version files and installing dependencies before signing or release steps.
- [Mobile Deployment Pipelines for $0](https://blog.jacobstechtavern.com/p/0-to-deploy-free-ci-with-fastlane) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-07-08T16:15:20.826Z`
  **NeKI brief:** Establish a small iOS delivery pipeline that builds, tests, signs, and distributes through fastlane with credentials isolated from repository content. Make each lane reproducible locally and in CI, then keep expensive deployment steps separate from fast pull-request validation.
- [How Enterprise level CI/CD with AppCircle helps you scale](https://www.donnywals.com/how-enterprise-level-ci-cd-with-appcircle-helps-you-scale) — Donny Wals · article catalogue
  **Published:** `2024-04-25T11:00:17+00:00`
  **NeKI brief:** Enterprise CI/CD is framed around repeatable signing, testing, and distribution pipelines, with centralized automation trading setup complexity for consistent release control.
- [GitHub Actions workflows side effects](https://www.polpiella.dev/github-action-workflows-side-effects) — Pol Piella · article catalogue
  **Published:** `2023-04-26T00:00:00.000Z`
  **NeKI brief:** Workflow-completion events can trigger dependent GitHub Actions jobs without coupling every concern to one pipeline. Use webhook filtering and idempotent handlers, guarding against loops, duplicate delivery and unintended write-side effects.
- [Fastlane and App Store Connect API keys](https://www.polpiella.dev/fastlane-appstore-connect-api-and-github-actions) — Pol Piella · article catalogue
  **Published:** `2023-01-11T00:00:00.000Z`
  **NeKI brief:** App Store Connect API keys let Fastlane and GitHub Actions authenticate without an interactive Apple ID session. Use encrypted, scoped credentials and rotation, ensuring CI logs never expose issuer, key ID or private key material.
- [Automagically load your Gulp plugins – Donny Wals](https://www.donnywals.com/automagically-load-your-gulp-plugins) — Donny Wals · article catalogue
  **Published:** `2015-03-11T06:45:54+00:00`
  **NeKI brief:** Automatic Gulp plugin loading reduces repetitive imports, but explicit dependencies can be clearer when build behavior must be easy to audit.
- [How to prevent Gulp from crashing all the time – Donny Wals](https://www.donnywals.com/how-to-prevent-gulp-from-crashing-all-the-time) — Donny Wals · article catalogue
  **Published:** `2015-03-03T12:00:43+00:00`
  **NeKI brief:** Build-stream error handling keeps Gulp watch tasks alive after an asset compilation failure, exposing the error without forcing a manual restart.
- [Getting started with Gulp – Donny Wals](https://www.donnywals.com/getting-started-with-gulp) — Donny Wals · article catalogue
  **Published:** `2015-02-15T13:22:00+00:00`
  **NeKI brief:** Gulp organizes repeatable asset and development tasks as streams, but teams should keep the toolchain proportional to the project's actual build needs.
- [Continuous integration and delivery for iOS](https://tanaschita.com/20230529-continuous-integration-and-delivery-for-ios) — Tanaschita · article catalogue
  **NeKI brief:** CI/CD concepts are mapped onto an iOS workflow covering tests, signing and distribution. Follow it to separate build verification from release promotion, with credentials and environment configuration treated as pipeline inputs.

## Newsletter and related leads

- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — SwiftLee Weekly · Issue 337 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2026-08-18T14:06:21.000Z`
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [🚨 Bitrise is retiring its Xcode 26 edge stacks](https://bitrise.io/blog/post/xcode-26-edge-stack-removal) — iOS CI Newsletter · Issue 91 — Article · Topics: CI/CD & Automation · Xcode
  **Published:** `2026-07-28T00:00:00.000Z`
  **NeKI brief:** Examines Bitrise is retiring its Xcode 26 edge stacks in the context of CI/CD & Automation and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Squeeze every last bit of value out of GitHub Actions](https://l.fatbobman.com/w0146-03) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Developer Tools
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** Audits GitHub Actions spending by removing flaky reruns, choosing cheaper runners for non-Apple work, retiring obsolete jobs, and tightening caches. The useful lesson is to measure effective validation per minute instead of merely shortening every job.
- [The Platform for Agentic macOS Development](https://go.macstadium.com/build-faster-with-orka) — iOS Dev Weekly · Issue 758 — Article · Topics: AI Development · CI/CD & Automation · Testing
  **Published:** `10th July 2026`
  **NeKI brief:** MacStadium's Orka overview describes API- and CLI-driven Apple-silicon virtual machines for CI, testing, and agent workflows. Use it to evaluate elastic macOS capacity against cost, isolation, Kubernetes integration, and reproducible build requirements.
- [👀 How Warp runs their CI/CD pipelines](https://namespace.so/customers/warp) — iOS CI Newsletter · Issue 90 — Article · Topics: CI/CD & Automation
  **Published:** `2026-07-06T00:00:00.000Z`
  **NeKI brief:** Examines How Warp runs their CI/CD pipelines in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🤖 Safari now has an MCP!](https://webkit.org/blog/18136/introducing-the-safari-mcp-server-for-web-developers) — iOS CI Newsletter · Issue 90 — Article · Topics: AI Development · CI/CD & Automation
  **Published:** `2026-07-06T00:00:00.000Z`
  **NeKI brief:** Examines Safari now has an MCP! in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [⚠️ GitHub Actions macos-latest image is changing](https://github.blog/changelog/2026-05-14-github-actions-upcoming-image-migrations) — iOS CI Newsletter · Issue 88 — Article · Topics: Developer Tools · macOS & AppKit · Testing
  **Published:** `2026-05-18T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions macos-latest image is changing in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [CI/CD Build Speed Benchmark: Codemagic Vs GitHub Actions Vs Bitrise](https://blog.codemagic.io/build-speed-benchmark-comparison) — Those Who Swift · Issue 260 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Developer Tools
  **Published:** `2026-04-01`
  **NeKI brief:** Examines How fast can each CI/CD service build your app? in the context of CI/CD & Automation and Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🐙 GitHub’s Platform fee explained](https://cloud.namespace.so/pd3382pdfrpeq/updates/github-pricing-dec16-2025) — iOS CI Newsletter · Issue 84 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Examines GitHub’s Platform fee explained in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [✂️ How monday.com cut their CI build times in half](https://tuist.dev/case-studies/monday) — iOS CI Newsletter · Issue 84 — Article · Topics: Architecture · CI/CD & Automation
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Examines How monday.com cut their CI build times in half in the context of Architecture and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools/tree/master) — iOS CI Newsletter · Issue 83 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-12-16T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Fastlane alternative - Codemagic CLI tools, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [🎥 [FREE WEBINAR] Running iOS Automated Tests on Real Devices](https://streamyard.com/watch/6UKiHuAgBQb7) — iOS CI Newsletter · Issue 83 — Article · Topics: CI/CD & Automation · Personal Essays · Testing
  **Published:** `2025-12-16T00:00:00.000Z`
  **NeKI brief:** Examines FREE WEBINAR] Running iOS Automated Tests on Real Devices in the context of CI/CD & Automation and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Improving Swift Package Scripts with GitHub Actions workflows](https://danielsaidi.com/blog/2025/11/26/improving-swift-package-scripts-with-github-action-workflows) — SwiftLee Weekly · Issue 300 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-12-02T15:13:04.000Z`
  **NeKI brief:** Examines A list of ready-to-use GitHub Actions workflows for Swift Packages in the context of Developer Tools and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🎥 [WEBINAR RECORDING] Automate your app’s releases with AWS](https://streamyard.com/watch/WfUTdS8snB6i) — iOS CI Newsletter · Issue 81 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-11-24T00:00:00.000Z`
  **NeKI brief:** Summarises FREE WEBINAR] Automate your app’s releases with AWS for Developer Tools. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [🚀 Set up iOS CI/CD on Azure DevOps](https://brightinventions.pl/blog/first-ios-ci-in-azure-devops) — iOS CI Newsletter · Issue 81 — Article · Topics: CI/CD & Automation
  **Published:** `2025-11-24T00:00:00.000Z`
  **NeKI brief:** Examines Set up iOS CI/CD on Azure DevOps in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Building Closed-Source Binaries With GitHub Actions](https://danielsaidi.com/blog/2025/11/09/building-closed-source-binaries-with-github-actions) — Those Who Swift · Issue 240 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-11-12`
  **NeKI brief:** Describes building closed-source binaries with GitHub Actions. Useful for designing reproducible distribution pipelines while keeping source private and making signing, artifacts, and release inputs explicit.
- [Level up your iOS CI/CD: top tips for success](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — iOS CI Newsletter · Issue 80 — Article · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `2025-11-10T00:00:00.000Z`
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [👀 A sneak peek into RightMove’s CI/CD set up](https://bitrise.io/blog/post/behind-the-scenes-rightmove-mobile-transformation-with-bitrise) — iOS CI Newsletter · Issue 80 — Article · Topics: CI/CD & Automation
  **Published:** `2025-11-10T00:00:00.000Z`
  **NeKI brief:** Examines A sneak peek into RightMove’s CI/CD set up in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🆕 What’s new in GitHub Actions](https://github.blog/changelog/2025-11-06-new-releases-for-github-actions-november-2025) — iOS CI Newsletter · Issue 80 — Article · Topics: Developer Tools
  **Published:** `2025-11-10T00:00:00.000Z`
  **NeKI brief:** Summarises What’s new in GitHub Actions for Developer Tools. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [🖥️ How this app saved $4000+ every month with self-hosted CI/CD Runners](https://jeffverkoeyen.com/blog/2025/10/17/SelfHostingMacMinis) — iOS CI Newsletter · Issue 79 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-11-02T00:00:00.000Z`
  **NeKI brief:** Examines How this app saved $4000+ every month with self-hosted CI/CD Runners in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🎥 Speed up your CI/CD pipelines with Selective Testing](https://www.youtube.com/watch?v=U1fJQRbq-TY) — iOS CI Newsletter · Issue 79 — Video · Topics: CI/CD & Automation · Swift · Testing
  **Published:** `2025-11-02T00:00:00.000Z`
  **NeKI brief:** Records Speed up your CI/CD pipelines with Selective Testing as a visual walkthrough relevant to CI/CD & Automation and Swift. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Jeff Verkoeyen](https://www.threads.com/@featherless) — iOS Dev Weekly · Issue 732 — Article · Topics: Developer Tools
  **Published:** `24th October 2025`
  **NeKI brief:** Jeff Verkoeyen recently decided to see how much it would cost to add CI to his Sidecar app. GitHub Actions is great for the first 3,000 minutes per month, unless you’re using macOS runners, in which case the allowance is 300 minutes. 😬 The other options…
- [Beyond QA: Mobile Testing Strategies](https://mobilesystemdesign.substack.com/p/beyond-qa-mobile-testing-strategies) — Those Who Swift · Issue 236 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `2025-10-15`
  **NeKI brief:** Discusses mobile testing strategies beyond conventional QA. Useful for combining exploratory, automated, and production-signal approaches when assessing confidence in an iOS release.
- [Run your entire CI/CD pipeline in AWS](https://aws.amazon.com/blogs/aws/announcing-amazon-ec2-m4-and-m4-pro-mac-instances) — iOS CI Newsletter · Issue 78 — Article · Topics: CI/CD & Automation · Performance · Testing
  **Published:** `2025-10-13T00:00:00.000Z`
  **NeKI brief:** Examines Run your entire CI/CD pipeline in AWS in the context of CI/CD & Automation and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧪 How to test Swift CLIs using GitHub Actions](https://www.ioscoffeebreak.com/issue/issue59) — iOS CI Newsletter · Issue 78 — Article · Topics: Developer Tools · Swift · Testing
  **Published:** `2025-10-13T00:00:00.000Z`
  **NeKI brief:** Walks through how to test Swift CLIs using GitHub Actions, with practical context for Developer Tools and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [🧠 Start formatting your CI/CD output with AI in mind](https://ldomaradzki.com/blog/stop-wasting-context-build-output) — iOS CI Newsletter · Issue 77 — Article · Topics: AI Development · CI/CD & Automation
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** Examines Start formatting your CI/CD output with AI in mind in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [xcsift](https://github.com/ldomaradzki/xcsift) — iOS CI Newsletter · Issue 77 — Source repository · Topics: AI Development · CI/CD & Automation · Developer Tools
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** xcsift condenses xcodebuild output so coding agents receive actionable build and test diagnostics instead of full verbose logs. Use it when agent context windows are consumed by compiler noise rather than failures requiring repair.
- [🎥 CI/CD for iOS Developers webinar recording](https://streamyard.com/ik659maf7b32) — iOS CI Newsletter · Issue 77 — Article · Topics: CI/CD & Automation · Combine & Reactive Programming
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** Examines CI/CD for iOS Developers webinar recording in the context of CI/CD & Automation and Combine & Reactive Programming. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [If you’re interested in the code that I used for the webinar, check out this step by step guide that I put together.](https://pol.link/ci-cd-for-ios-workshop) — iOS CI Newsletter · Issue 77 — Tutorial · Topics: CI/CD & Automation
  **Published:** `2025-10-06T00:00:00.000Z`
  **NeKI brief:** Examines If you’re interested in the code that I used for the webinar, check out this step by step guide that I put… in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Run your entire CI/CD pipeline in AWS](https://aws.amazon.com/ec2/instance-types/mac) — iOS CI Newsletter · Issue 76 — Article · Topics: CI/CD & Automation · Performance · Testing
  **Published:** `2025-10-01T00:00:00.000Z`
  **NeKI brief:** Examines Run your entire CI/CD pipeline in AWS in the context of CI/CD & Automation and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💪 ReleaseTools: A lightweight alternative to Fastlane written entirely in Swift](https://elegantchaos.com/2025/09/26/release-tools.html) — iOS CI Newsletter · Issue 76 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Swift
  **Published:** `2025-10-01T00:00:00.000Z`
  **NeKI brief:** Summarises ReleaseTools: A lightweight alternative to Fastlane written entirely in Swift for CI/CD & Automation and Cross-Platform & Web. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [⚠️ Node 20 will soon be deprecated on GitHub Actions](https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners) — iOS CI Newsletter · Issue 75 — Article · Topics: Developer Tools
  **Published:** `2025-09-21T00:00:00.000Z`
  **NeKI brief:** Examines Node 20 will soon be deprecated on GitHub Actions in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift-Build GitHub Action](https://l.fatbobman.com/w0102-07) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Provides a GitHub Action for building and testing Swift packages across platforms. Follow it when setting up matrix-based package validation and comparing CI workflows for Linux, macOS, and other supported targets.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [🤖 How to generate GitHub Actions workflows automatically](https://elegantchaos.com/2025/08/28/action-builder.html) — iOS CI Newsletter · Issue 74 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-10T00:00:00.000Z`
  **NeKI brief:** Walks through how to generate GitHub Actions workflows automatically, with practical context for Cross-Platform & Web and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [🧰 Automating Swift binary releases using GitHub Actions](https://www.ioscoffeebreak.com/issue/issue58) — iOS CI Newsletter · Issue 74 — Article · Topics: Developer Tools · Swift
  **Published:** `2025-09-10T00:00:00.000Z`
  **NeKI brief:** Summarises Automating Swift binary releases using GitHub Actions for Developer Tools and Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Automating Swift Binary Releases Using GitHub Actions](https://l.fatbobman.com/w0101-04) — Fatbobman’s Swift Weekly · Issue 101 — Article · Topics: Developer Tools · Swift
  **Published:** `2025-09-08T12:03:42.721Z`
  **NeKI brief:** Shows how GitHub Actions can build and publish Swift command-line tools automatically when a new tag is pushed. Follow it when designing a release pipeline with reproducible triggers, artifact generation, and package distribution steps.
- [What Is a Mobile Platform Engineer](https://mobilesystemdesign.substack.com/p/what-is-a-mobile-platform-engineer) — Those Who Swift · Issue 225 — Article · Topics: Architecture · CI/CD & Automation · Performance
  **Published:** `2025-08-07`
  **NeKI brief:** Examines What Is a Mobile Platform Engineer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [⚠️ Important updates to GitHub-hosted macOS runners](https://github.blog/changelog/2025-07-11-upcoming-changes-to-macos-hosted-runners-macos-latest-migration-and-xcode-support-policy-updates) — iOS CI Newsletter · Issue 72 — Article · Topics: Developer Tools · macOS & AppKit · Testing
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Important updates to GitHub-hosted macOS runners in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🏷️ Uploading your app to TestFlight using GitHub Actions](https://nowham.dev/posts/github_actions_testflight) — iOS CI Newsletter · Issue 72 — Article · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Uploading your app to TestFlight using GitHub Actions in the context of App Distribution & Store Operations and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [✨ How to build delight Swift CLIs](https://swifttoolkit.dev/posts/terminal-utilities) — iOS CI Newsletter · Issue 72 — Article · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Walks through how to build delight Swift CLIs, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [📦 A decentralized CLI tool manager](https://albertodebortoli.com/2025/07/13/how-to-implement-a-decentralised-cli-tool-manager) — iOS CI Newsletter · Issue 72 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Examines A decentralized CLI tool manager in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Codemagic makes Apple M2 machines available, even on the free tier!](https://codemagic.io/start) — iOS CI Newsletter · Issue 71 — Article · Topics: CI/CD & Automation
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Examines Codemagic CI/CD for mobile teams in the context of CI/CD & Automation and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧪 How to run Unit Tests on CI/CD](https://nowham.dev/posts/github_actions_unit_tests) — iOS CI Newsletter · Issue 71 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Walks through how to run Unit Tests on CI/CD, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [The Evolution of Mobile CI: Navigating the Shift to Infrastructure‑as‑a‑Service](https://tuist.dev/blog/2025/06/18/mobile-ci) — Those Who Swift · Issue 220 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-06-25`
  **NeKI brief:** Describes the evolution of mobile CI toward infrastructure services. Useful for comparing reproducibility, scaling, and operational ownership when designing an iOS build pipeline.
- [Essential xcodebuild Commands for iOS Developers](https://medium.com/@awasthi027.ashish/essential-xcodebuild-commands-for-ios-developers-9ff101783ce2) — Those Who Swift · Issue 195 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Xcode
  **Published:** `2025-06-18`
  **NeKI brief:** Examines Essential xcodebuild Commands for iOS Developers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Supercharge your GitHub Actions with fully managed M4 Pro runners from Cirrus Labs](https://cirrus-runners.app/) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Article · Topics: Developer Tools · Testing
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Describes managed M4 Pro runners for GitHub Actions workloads. Use it to evaluate faster macOS CI capacity, queue behavior, and cost before moving iOS builds to hosted hardware.
- [How Secure Is Your Mobile CI/CD Pipeline?](https://appcircle.io/blog/mobile-ci-cd-security-top-5-best-practices) — iOS CI Newsletter · Issue 68 — Article · Topics: CI/CD & Automation · Security & Privacy
  **Published:** `2025-05-18T00:00:00.000Z`
  **NeKI brief:** Examines How Secure Is Your Mobile CI/CD Pipeline? in the context of CI/CD & Automation and Security & Privacy. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🪝How to use Git Hooks for iOS projects](https://nowham.dev/posts/git_hooks) — iOS CI Newsletter · Issue 68 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-05-18T00:00:00.000Z`
  **NeKI brief:** Walks through how to use Git Hooks for iOS projects, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Are You Overlooking Mobile CI/CD Security?](https://appcircle.io/whitepapers/enhancing-mobile-ci-cd-security) — SwiftLee Weekly · Issue 270 — Article · Topics: CI/CD & Automation · Security & Privacy
  **Published:** `2025-05-06T14:02:39.000Z`
  **NeKI brief:** Discusses Are You Overlooking Mobile CI/CD Security?, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [🎥 FREE Webinar: Automating Multiplatform App Releases](https://streamyard.com/watch/BwQ2t4Q5aCkk) — iOS CI Newsletter · Issue 67 — Article · Topics: Apple Platform Ecosystem · CI/CD & Automation
  **Published:** `2025-05-04T00:00:00.000Z`
  **NeKI brief:** Summarises FREE Webinar: Automating Multiplatform App Releases for Apple Platform Ecosystem and CI/CD & Automation. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [💨 Speed up your CI/CD pipelines by running Unit Tests in parallel](https://nowham.dev/posts/parallelize_unit_tests) — iOS CI Newsletter · Issue 67 — Article · Topics: CI/CD & Automation · Personal Essays · Testing
  **Published:** `2025-05-04T00:00:00.000Z`
  **NeKI brief:** Examines Speed up your CI/CD pipelines by running Unit Tests in parallel in the context of CI/CD & Automation and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🤖 Interacting with GitHub Actions from an AI Assistant](https://github.com/ko1ynnky/github-actions-mcp-server) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Interacting with GitHub Actions from an AI Assistant, relevant to AI Development and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [🤖 Interacting with Bitrise from an AI Assistant](https://bitrise.io/blog/post/chat-with-your-builds-ci-and-more-introducing-the-bitrise-mcp-server) — iOS CI Newsletter · Issue 66 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Examines Interacting with Bitrise from an AI Assistant in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 Is fastlane the right tool for Mobile Automation in 2025?](https://tuist.dev/blog/2025/04/15/automation-in-swift-projects) — iOS CI Newsletter · Issue 66 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Examines Is fastlane the right tool for Mobile Automation in 2025? in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Webinar recording](https://streamyard.com/asubu9a35gcn) — iOS CI Newsletter · Issue 65 — Article · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Examines Webinar recording in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Workflow that runs unit tests on all available platforms on every push to main and every push to a Pull Request targetting the main branch](https://github.com/polpielladev/reading-time/blob/main/.github/workflows/main.yml) — iOS CI Newsletter · Issue 65 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Workflow that runs unit tests on all available platforms on every push to main and every push to a Pull…, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Workflow that runs when on every new tag with a Semver version as the name that compiles executables for each available platform and creates a GitHub release.](https://github.com/polpielladev/reading-time/blob/main/.github/workflows/release.yml) — iOS CI Newsletter · Issue 65 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Workflow that runs when on every new tag with a Semver version as the name that compiles executables for each…, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [the Vapor team built an action that uses Swiftly under the hood and that installs any version of Swift you want as part of your GitHub Actions workflows](https://github.com/vapor/swiftly-action) — iOS CI Newsletter · Issue 65 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for the Vapor team built an action that uses Swiftly under the hood and that installs any version of Swift you…, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [🚀 How to automate App Store screenshot generation for macOS apps](https://www.jessesquires.com/blog/2025/03/24/automate-perfect-mac-screenshots) — iOS CI Newsletter · Issue 65 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Community & Business
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to automate App Store screenshot generation for macOS apps, with practical context for App Distribution & Store Operations and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Discover the Top 10 Best Practices in App Distribution](https://appcircle.io/blog/10-best-practices-in-app-distribution-for-testing) — SwiftLee Weekly · Issue 265 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Examines Discover the Top 10 Best Practices in App Distribution in the context of CI/CD & Automation and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📦 FREE Webinar: CI/CD for Swift Packages](https://streamyard.com/watch/62AzM2xGJ2hB) — iOS CI Newsletter · Issue 64 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `2025-03-23T00:00:00.000Z`
  **NeKI brief:** Examines FREE Webinar: CI/CD for Swift Packages in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚨 Upcoming breaking changes in GitHub Actions](https://github.blog/changelog/2025-03-20-notification-of-upcoming-breaking-changes-in-github-actions) — iOS CI Newsletter · Issue 64 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-03-23T00:00:00.000Z`
  **NeKI brief:** Examines Upcoming breaking changes in GitHub Actions in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 How to build an iOS app using fastlane](https://nowham.dev/posts/build_app_with_fastlane) — iOS CI Newsletter · Issue 64 — Article · Topics: CI/CD & Automation
  **Published:** `2025-03-23T00:00:00.000Z`
  **NeKI brief:** Walks through how to build an iOS app using fastlane, with practical context for CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Scalable Continuous Integration for iOS | Swift Heroes Talk](https://www.youtube.com/watch?v=gy5ZHcDj4tE) — Those Who Swift · Issue 205 — Video · Topics: CI/CD & Automation · Swift
  **Published:** `2025-03-12`
  **NeKI brief:** Reviews Scalable Continuous Integration for iOS | Swift Heroes Talk. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [XCFolder](https://github.com/ZhgChgLi/XCFolder) — Fatbobman’s Swift Weekly · Issue 74 — Source repository · Topics: CI/CD & Automation · Developer Career & Practice · Xcode
  **Published:** `2025-03-10T12:03:47.395Z`
  **NeKI brief:** XCFolder converts Xcode's virtual groups into real directories, aligning project structure with filesystem-based generators such as Tuist and XcodeGen. Useful for reducing project-file drift while planning a source-tree migration.
- [set_github_release](https://preview.convertkit-mail2.com/click/dpheh0hzhm/aHR0cHM6Ly9kb2NzLmZhc3RsYW5lLnRvb2xzL2FjdGlvbnMvc2V0X2dpdGh1Yl9yZWxlYXNlLw==) — iOS CI Newsletter · Issue 63 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-03-09T00:00:00.000Z`
  **NeKI brief:** Summarises set_github_release for CI/CD & Automation and Developer Tools. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [we created a PR in the Fastlane repository](https://preview.convertkit-mail2.com/click/dpheh0hzhm/aHR0cHM6Ly9naXRodWIuY29tL2Zhc3RsYW5lL2Zhc3RsYW5lL3B1bGwvMjk0NzU=) — iOS CI Newsletter · Issue 63 — Article · Topics: CI/CD & Automation
  **Published:** `2025-03-09T00:00:00.000Z`
  **NeKI brief:** Examines we created a PR in the Fastlane repository in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 An introduction to fastlane for iOS developers](https://nowham.dev/posts/into_to_fastlane) — iOS CI Newsletter · Issue 63 — Article · Topics: CI/CD & Automation · Developer Community & Business
  **Published:** `2025-03-09T00:00:00.000Z`
  **NeKI brief:** Examines An introduction to fastlane for iOS developers in the context of CI/CD & Automation and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📺 Turning your Swift command-line apps into beautiful macOS apps](https://www.swiftyplace.com/blog/building-macos-utiltiy-apps) — iOS CI Newsletter · Issue 63 — Article · Topics: CI/CD & Automation · macOS & AppKit · Swift
  **Published:** `2025-03-09T00:00:00.000Z`
  **NeKI brief:** Examines Turning your Swift command-line apps into beautiful macOS apps in the context of CI/CD & Automation and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Check for new ASC API versions automatically:](https://github.com/AvdLee/appstoreconnect-swift-sdk/blob/master/.github/workflows/sync_asc_api.yml) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Check for new ASC API versions automatically, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Test on all available platforms:](https://github.com/AvdLee/appstoreconnect-swift-sdk/blob/master/.github/workflows/ci.yml) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Test on all available platforms, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [🧪 Exploring built-in fastlane actions](https://nowham.dev/posts/useful_built_ins) — iOS CI Newsletter · Issue 62 — Article · Topics: CI/CD & Automation · Developer Community & Business
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines Exploring built-in fastlane actions in the context of CI/CD & Automation and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🛸 Emerge tools CLI is available](https://www.emergetools.com/blog/posts/the-emerge-cli) — iOS CI Newsletter · Issue 62 — Article · Topics: CI/CD & Automation
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines Emerge tools CLI is available in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SwiftUI Navigation: View If Needed](https://www.joshholtz.com/blog/2025/02/08/swiftui-navigation-view-if-needed) — Those Who Swift · Issue 201 — Article · Topics: CI/CD & Automation · Swift · SwiftUI
  **Published:** `2025-02-12`
  **NeKI brief:** Discusses SwiftUI navigation behavior and when a view is needed. Useful for reviewing navigation structure and avoiding accidental destination creation or state lifetime problems.
- [🧪 Advanced tips to use fastlane like a pro](https://nowham.dev/posts/intermediate_fastlane) — iOS CI Newsletter · Issue 59 — Article · Topics: CI/CD & Automation
  **Published:** `2025-01-13T00:00:00.000Z`
  **NeKI brief:** Examines Advanced tips to use fastlane like a pro in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💪 Struggling to get back into a routine after the break? Check out this article](https://david-smith.org/blog/2025/01/10/accomplish-one-thing) — iOS CI Newsletter · Issue 59 — Article · Topics: CI/CD & Automation
  **Published:** `2025-01-13T00:00:00.000Z`
  **NeKI brief:** Examines Struggling to get back into a routine after the break? Check out this article in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💾 How using Tuist cache helped reduce build times by 65%](https://tuist.dev/blog/2024/12/16/trendyol) — iOS CI Newsletter · Issue 57 — Article · Topics: CI/CD & Automation
  **Published:** `2024-12-17T00:00:00.000Z`
  **NeKI brief:** Examines How using Tuist cache helped reduce build times by 65% in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 How to make the fastlane developer experience nicer](https://nowham.dev/posts/nicer-fastlane) — iOS CI Newsletter · Issue 57 — Article · Topics: CI/CD & Automation · Developer Community & Business
  **Published:** `2024-12-17T00:00:00.000Z`
  **NeKI brief:** Walks through how to make the fastlane developer experience nicer, with practical context for CI/CD & Automation and Developer Community & Business. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [🕵️‍♂️ Automate memory leak discovery using GitHub Actions](https://www.amanjeet.me/discovering-ios-memory-leaks-part-three) — iOS CI Newsletter · Issue 56 — Article · Topics: Developer Tools
  **Published:** `2024-12-02T00:00:00.000Z`
  **NeKI brief:** Examines Automate memory leak discovery using GitHub Actions in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 Use Bitrise on Amazon Web Services](https://bitrise.io/blog/post/bitrise-on-aws-benefits-of-using-a-cloud-native-mobile-ci-cd-solution) — iOS CI Newsletter · Issue 56 — Article · Topics: CI/CD & Automation
  **Published:** `2024-12-02T00:00:00.000Z`
  **NeKI brief:** Examines Use Bitrise on Amazon Web Services in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS CI Newsletter · Issue 55 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [⏭️ Bumping a Swift Package’s version using Fastlane](https://nowham.dev/posts/fastlane-version-bump) — iOS CI Newsletter · Issue 55 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines Bumping a Swift Package’s version using Fastlane in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [fastlane match](https://docs.fastlane.tools/actions/match) — iOS CI Newsletter · Issue 55 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines fastlane match in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚨 GitHub Actions list of upcoming breaking changes](https://github.blog/changelog/2024-11-05-notice-of-breaking-changes-for-github-actions) — iOS CI Newsletter · Issue 55 — Article · Topics: Developer Tools
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions list of upcoming breaking changes in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📦 Bitrise Release Management is now CI agnostic!](https://bitrise.io/blog/post/bitrise-release-management-introduces-ci-agnostic-distribution-tool-for-testing-and-releasing-to-stores) — iOS CI Newsletter · Issue 55 — Article · Topics: CI/CD & Automation · Developer Career & Practice · Testing
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Summarises Bitrise Release Management is now CI agnostic! for CI/CD & Automation and Developer Career & Practice. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Being Sendable with SwiftData](https://brightdigit.com/tutorials/swiftdata-sendable?issue=057) — Fatbobman’s Swift Weekly · Issue 57 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** Explains Sendable boundaries around SwiftData models and persistence access. Use it when concurrency checking exposes non-Sendable model crossings and you need to decide where actors or value projections belong.
- [📈 GitHub Actions metrics now available](https://github.blog/changelog/2024-10-31-actions-performance-metrics-in-public-preview) — iOS CI Newsletter · Issue 54 — Article · Topics: Developer Tools · Performance
  **Published:** `2024-11-03T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions metrics now available in the context of Developer Tools and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧪 Converting Fastlane lanes to shell scripts](https://danielsaidi.com/blog/2024/10/03/replacing-fastlane-with-shell-scripts) — iOS CI Newsletter · Issue 52 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2024-10-06T00:00:00.000Z`
  **NeKI brief:** Examines Converting Fastlane lanes to shell scripts in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📱 Install older simulator runtimes on CI/CD](https://testableapple.com/install-ios-simulator-runtimes) — iOS CI Newsletter · Issue 51 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Testing
  **Published:** `2024-09-23T00:00:00.000Z`
  **NeKI brief:** Examines Install older simulator runtimes on CI/CD in the context of CI/CD & Automation and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚨 FlyCI Runners to be discontinued on September 30th](https://flyci.net/blog/flyci-discontinue-macos-runners) — iOS CI Newsletter · Issue 49 — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines FlyCI Runners to be discontinued on September 30th in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [CI Wingman feature](https://flyci.net/docs) — iOS CI Newsletter · Issue 49 — Article · Topics: Developer Tools
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines Automatically fix your failing CI/CD builds in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [☁️ How to set up Xcode Cloud on your project](https://darrylbayliss.net/getting-setup-with-xcode-cloud) — iOS CI Newsletter · Issue 49 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Xcode
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Walks through how to set up Xcode Cloud on your project, with practical context for App Distribution & Store Operations and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [a tool like fastlane](https://docs.fastlane.tools/getting-started/ios/screenshots) — iOS CI Newsletter · Issue 48 — Article · Topics: CI/CD & Automation
  **Published:** `2024-08-11T00:00:00.000Z`
  **NeKI brief:** Examines a tool like fastlane in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧰 Releasing Swift Binaries with GitHub Actions](https://swifttoolkit.dev/posts/releasing-with-gh-actions) — iOS CI Newsletter · Issue 48 — Article · Topics: Developer Tools · Product Design · Swift
  **Published:** `2024-08-11T00:00:00.000Z`
  **NeKI brief:** Examines Releasing Swift Binaries with GitHub Actions in the context of Developer Tools and Product Design. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Answer: Codemagic CI/CD](https://codemagic.io/ios-continuous-integration) — iOS Dev Tools · iOS Dev Tools: AnimationPlanner, Xcode-Kotlin, React-native-vision-camera — Article · Topics: CI/CD & Automation
  **Published:** `2024-08-01T16:50:45.265Z`
  **NeKI brief:** Codemagic CI/CD documents cloud automation for building, testing, signing, and delivering iOS applications. Follow it for a concrete mobile-release pipeline and compare its configuration model with the project’s own signing requirements.
- [Line](https://line.me/en) — iOS CI Newsletter · Issue 47 — Article · Topics: CI/CD & Automation · Swift · Testing
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Examines Line in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🏃 Why you need CI/CD as an Indie Dev](https://www.rudrank.com/exploring-indie-life-reducing-friction-by-ci-cd) — iOS CI Newsletter · Issue 47 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Examines Why you need CI/CD as an Indie Dev in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧪 How to build and run tests for an iOS app using GitHub Actions](https://brightinventions.pl/blog/ios-build-run-tests-github-actions) — iOS CI Newsletter · Issue 47 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Walks through how to build and run tests for an iOS app using GitHub Actions, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [💰 Free CI/CD for your side projects](https://jacobbartlett.substack.com/p/0-to-deploy-free-ci-with-fastlane) — iOS CI Newsletter · Issue 46 — Article · Topics: CI/CD & Automation
  **Published:** `2024-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Free CI/CD for your side projects in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📖 A guide to the App Store Connect API](https://www.runway.team/blog/a-hitchhikers-guide-to-the-app-store-connect-api) — iOS CI Newsletter · Issue 45 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-07-01T00:00:00.000Z`
  **NeKI brief:** Examines A guide to the App Store Connect API in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧐 How GitHub reduced testing time for iOS apps with new runner features](https://github.blog/2024-06-03-how-github-reduced-testing-time-for-ios-apps-with-new-runner-features) — iOS CI Newsletter · Issue 44 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2024-06-16T00:00:00.000Z`
  **NeKI brief:** Examines How GitHub reduced testing time for iOS apps with new runner features in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💨 Save CI resources by running tests before committing](https://antran.app/2024/ios_selective_testing) — iOS CI Newsletter · Issue 43 — Article · Topics: Architecture · Personal Essays · Testing
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Examines Save CI resources by running tests before committing in the context of Architecture and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [XcodeSelectiveTesting](https://github.com/mikeger/XcodeSelectiveTesting) — iOS CI Newsletter · Issue 43 — Source repository · Topics: Architecture · Testing · Xcode
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for XcodeSelectiveTesting, relevant to Architecture and Testing. Inspect its implementation, open issues, and release state before adopting the approach.
- [scheduled GitHub actions workflow that checks if a new version of the App Store Connect API’s Open API spec is available](https://github.com/MortenGregersen/Bagbutik/blob/10.3.0/.github/workflows/check-for-new-spec.yml) — iOS CI Newsletter · Issue 43 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for scheduled GitHub actions workflow that checks if a new version of the App Store Connect API’s Open API spec is…, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [🚀 Using Danger with Swift on CI](https://swiftunwrap.com/article/dangerswift) — iOS CI Newsletter · Issue 40 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Examines Using Danger with Swift on CI in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Danger](https://github.com/danger/danger) — iOS CI Newsletter · Issue 40 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Danger, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Veertu](https://veertu.com/) — iOS Dev Tools · iOS Dev tools: Chime, Parse Platform, Veertu — Article · Topics: CI/CD & Automation · Testing
  **Published:** `2024-04-18T13:45:11.063Z`
  **NeKI brief:** Veertu provides ephemeral macOS virtual machines intended for iOS continuous-integration testing without dedicated physical hardware. Use it when comparing reproducible macOS build capacity, accounting for licensing, performance, provisioning, and simulator constraints.
- [🆕 Roundup of all updates to GitHub-hosted runners](https://github.blog/changelog/2024-04-02-whats-new-for-github-actions-hosted-runners) — iOS CI Newsletter · Issue 39 — Article · Topics: Developer Tools
  **Published:** `2024-04-07T00:00:00.000Z`
  **NeKI brief:** Examines Roundup of all updates to GitHub-hosted runners in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💨 Building DocC automatically using GitHub Actions](https://danielsaidi.com/blog/2024/03/10/automating-docc-for-a-swift-package-with-github-actions) — iOS CI Newsletter · Issue 37 — Article · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2024-03-10T00:00:00.000Z`
  **NeKI brief:** Examines Building DocC automatically using GitHub Actions in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [⚙️ How to deploy apps with Codemagic and GitHub Actions](https://blog.codemagic.io/deploy-your-app-to-app-store-with-codemagic-cli-tools-and-github-actions) — iOS CI Newsletter · Issue 36 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Walks through how to deploy apps with Codemagic and GitHub Actions, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [🛑 Deprecation of widely used GitHub Actions actions](https://github.blog/changelog/2024-02-13-deprecation-notice-v1-and-v2-of-the-artifact-actions) — iOS CI Newsletter · Issue 36 — Article · Topics: Developer Tools
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Examines Deprecation of widely used GitHub Actions actions in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [upload](https://github.com/actions/upload-artifact) — iOS CI Newsletter · Issue 36 — Source repository · Topics: Developer Tools
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for @actions/upload-artifact (v2), relevant to Developer Tools and Testing. Inspect its implementation, open issues, and release state before adopting the approach.
- [download artifacts](https://github.com/actions/download-artifact) — iOS CI Newsletter · Issue 36 — Source repository · Topics: Developer Tools
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for actions/download-artifact, relevant to Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [this awesome article](https://blog.eidinger.info/why-and-how-to-adopt-actionscheckoutv3-in-your-github-action-workflow) — iOS CI Newsletter · Issue 36 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Examines actions/checkout GitHub action updated! in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧰 Compile and distribute your iOS SDK as a pre-compiled xcframework](https://krausefx.com/blog/how-to-automaticallycompile-and-distribute-your-ios-sdk-as-a-pre-compiled-xcframework) — iOS CI Newsletter · Issue 35 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa
  **Published:** `2024-02-11T00:00:00.000Z`
  **NeKI brief:** Examines Compile and distribute your iOS SDK as a pre-compiled xcframework in the context of CI/CD & Automation and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🆕 GitHub-hosted macOS Sonoma runners are now available!](https://github.blog/changelog/2024-01-30-github-actions-macos-14-sonoma-is-now-available) — iOS CI Newsletter · Issue 35 — Article · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2024-02-11T00:00:00.000Z`
  **NeKI brief:** Examines GitHub-hosted macOS Sonoma runners are now available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 Scalable iOS CI](https://albertodebortoli.com/2024/01/03/scalable-continuous-integration-for-ios) — iOS CI Newsletter · Issue 33 — Article · Topics: CI/CD & Automation
  **Published:** `2024-01-14T00:00:00.000Z`
  **NeKI brief:** Examines Scalable iOS CI in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🎓 GitHub Actions certifications](https://github.blog/2024-01-08-github-certifications-are-generally-available) — iOS CI Newsletter · Issue 33 — Article · Topics: Developer Tools
  **Published:** `2024-01-14T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions certifications in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🥉 Automatic memory leak detection on CI/CD](https://levelup.gitconnected.com/automating-memory-leak-detection-with-ci-integration-for-ios-380f08a55f0b) — iOS CI Newsletter · Issue 32 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2023-12-31T00:00:00.000Z`
  **NeKI brief:** Examines Automating Memory Leak Detection with CI Integration for iOSA solution to automate memory leak detection in… in the context of Developer Tools and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [✨ Using Emerge Tools on CI/CD to optimise your app’s size](https://blog.codemagic.io/optimising-ios-app-size-emerge-tools-ci-cd) — iOS CI Newsletter · Issue 31 — Article · Topics: CI/CD & Automation · Combine & Reactive Programming
  **Published:** `2023-12-17T00:00:00.000Z`
  **NeKI brief:** Examines Using Emerge Tools on CI/CD to optimise your app’s size in the context of CI/CD & Automation and Combine & Reactive Programming. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🎉 Fastlane officially moves to the Mobile Native Foundation](https://github.com/MobileNativeFoundation/discussions/discussions/194) — iOS CI Newsletter · Issue 28 — Source repository · Topics: CI/CD & Automation · Developer Tools · Foundation & Data Formats
  **Published:** `2023-11-05T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Fastlane might be moving to Mobile Native Foundation!, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [⭐️ Stellar: The idea of Swift replacement for Fastlane](https://albertodebortoli.com/2023/10/29/the-idea-of-a-fastlane-replacement) — iOS CI Newsletter · Issue 28 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2023-11-05T00:00:00.000Z`
  **NeKI brief:** Examines Stellar: The idea of Swift replacement for Fastlane in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Stellar](https://github.com/StellarTools/Stellar) — iOS Dev Weekly · Issue 634 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `3rd November 2023`
  **NeKI brief:** Examines Contribute to StellarTools/Stellar development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [🔐 1Password + CI/CD](https://blog.1password.com/1password-service-accounts) — iOS CI Newsletter · Issue 27 — Article · Topics: CI/CD & Automation · Security & Privacy
  **Published:** `2023-10-22T00:00:00.000Z`
  **NeKI brief:** Examines 1Password + CI/CD in the context of CI/CD & Automation and Security & Privacy. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📹 [NSSpain] Why CI/CD won’t save your mobile team](https://vimeo.com/865678854) — iOS CI Newsletter · Issue 27 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `2023-10-22T00:00:00.000Z`
  **NeKI brief:** Records NSSpain] Why CI/CD won’t save your mobile team as a visual walkthrough relevant to CI/CD & Automation and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [🎉 M1 GitHub-hosted runners publicly available!](https://github.blog/changelog/2023-10-02-github-actions-apple-silicon-m1-macos-runners-are-now-available-in-public-beta) — iOS CI Newsletter · Issue 26 — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2023-10-08T00:00:00.000Z`
  **NeKI brief:** Examines M1 GitHub-hosted runners publicly available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [⚠️ Time to update your GitHub Actions](https://github.blog/changelog/2023-09-22-github-actions-transitioning-from-node-16-to-node-20) — iOS CI Newsletter · Issue 25 — Article · Topics: Developer Tools
  **Published:** `2023-09-24T00:00:00.000Z`
  **NeKI brief:** Examines Time to update your GitHub Actions in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [actions/checkout](https://github.com/actions/checkout) — iOS CI Newsletter · Issue 25 — Source repository · Topics: Developer Tools · Testing
  **Published:** `2023-09-24T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for @actions/checkout (v2), relevant to Developer Tools and Testing. Inspect its implementation, open issues, and release state before adopting the approach.
- [🖥️ How to use EC2 Macs for Apple app CI/CD](https://bitrise.io/blog/post/summit-speaker-spotlight-series-aws) — iOS CI Newsletter · Issue 25 — Article · Topics: App Intents & System Surfaces · CI/CD & Automation
  **Published:** `2023-09-24T00:00:00.000Z`
  **NeKI brief:** Walks through how to use EC2 Macs for Apple app CI/CD, with practical context for App Intents & System Surfaces and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [✅ Get ASC app status updates on Slack](https://www.roger.ml/p/launching-statused) — iOS CI Newsletter · Issue 24 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2023-09-10T00:00:00.000Z`
  **NeKI brief:** Examines Get ASC app status updates on Slack in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💻 How to set up self-hosted GHA runners](https://www.manu.show/2023-09-03-self-hosted-gha-runners) — iOS CI Newsletter · Issue 24 — Article · Topics: CI/CD & Automation
  **Published:** `2023-09-10T00:00:00.000Z`
  **NeKI brief:** Walks through how to set up self-hosted GHA runners, with practical context for CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [🔨 Create Pull Requests automatically using Fastlane](https://mdb1.github.io/2023-08-12-use-fastlane-to-create-prs) — iOS CI Newsletter · Issue 22 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2023-08-13T00:00:00.000Z`
  **NeKI brief:** Examines Create Pull Requests automatically using Fastlane in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [the snapshot action](https://docs.fastlane.tools/actions/snapshot) — iOS CI Newsletter · Issue 22 — Article · Topics: CI/CD & Automation
  **Published:** `2023-08-13T00:00:00.000Z`
  **NeKI brief:** Examines the snapshot action in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Qonto](https://qonto.com/en) — iOS CI Newsletter · Issue 21 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `2023-07-31T00:00:00.000Z`
  **NeKI brief:** Examines Qonto in the context of CI/CD & Automation and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [an article last year](https://blog.eidinger.info/xcode-133-supports-spm-binary-dependency-in-private-github-release) — iOS CI Newsletter · Issue 20 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines an article last year in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 New Fastlane version](https://github.com/fastlane/fastlane/releases/tag/2.214.0) — iOS CI Newsletter · Issue 20 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for New Fastlane version, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [highlight this PR](https://github.com/fastlane/fastlane/pull/20956) — iOS CI Newsletter · Issue 20 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for highlight this PR, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [✍️ Fastlane 2.213.0: Run Xcode 14.3 with Rosetta](https://github.com/fastlane/fastlane/releases/tag/2.213.0) — iOS CI Newsletter · Issue 18 — Source repository · Topics: CI/CD & Automation · Developer Tools · Xcode
  **Published:** `2023-06-18T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Fastlane 2.213.0: Run Xcode 14.3 with Rosetta, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [this article](https://www.roger.ml/p/run-xcodebuild-using-rosetta-xcode-14-3) — iOS CI Newsletter · Issue 18 — Article · Topics: CI/CD & Automation · Xcode
  **Published:** `2023-06-18T00:00:00.000Z`
  **NeKI brief:** Examines this article in the context of CI/CD & Automation and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🤯 Running GitHub Actions workflows locally](https://grantisom.com/2023/05/15/using-act-to.html) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Developer Tools · Personal Essays
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines Running GitHub Actions workflows locally in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Act](https://github.com/nektos/act) — iOS CI Newsletter · Issue 16 — Source repository · Topics: Developer Tools · Personal Essays
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Act, relevant to Developer Tools and Personal Essays. Inspect its implementation, open issues, and release state before adopting the approach.
- [📱 Edit GitHub Actions workflows from your phone](https://github.blog/changelog/2023-05-11-edit-workflow-files-on-github-mobile) — iOS CI Newsletter · Issue 16 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines Edit GitHub Actions workflows from your phone in the context of Cross-Platform & Web and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [❗️ Node 12 will no longer be allowed in GitHub Actions](https://github.blog/changelog/2023-05-04-github-actions-all-actions-will-run-on-node16-instead-of-node12) — iOS CI Newsletter · Issue 16 — Article · Topics: Developer Tools
  **Published:** `2023-05-21T00:00:00.000Z`
  **NeKI brief:** Examines Node 12 will no longer be allowed in GitHub Actions in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🆕 GitHub Actions: macOS 13 available!](https://github.blog/changelog/2023-04-24-github-actions-macos-13-is-now-available) — iOS CI Newsletter · Issue 15 — Article · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2023-05-07T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions: macOS 13 available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [📖 The ultimate guide to Jenkins for iOS](https://www.roger.ml/p/jenkins-ios-setup) — iOS CI Newsletter · Issue 15 — Article · Topics: CI/CD & Automation
  **Published:** `2023-05-07T00:00:00.000Z`
  **NeKI brief:** Examines The ultimate guide to Jenkins for iOS in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [including Apple themselves](https://www.swift.org/continuous-integration) — iOS CI Newsletter · Issue 15 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2023-05-07T00:00:00.000Z`
  **NeKI brief:** Examines including Apple themselves in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🍕 Should you use CI/CD as an indie dev?](https://blog.codemagic.io/deep-dish-swift-2023) — iOS CI Newsletter · Issue 14 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `2023-04-23T00:00:00.000Z`
  **NeKI brief:** Examines Should you use CI/CD as an indie dev? in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💡A technical guide to Mobile CI/CD](https://wolfia.com/blog/streamlining-mobile-app-development) — iOS CI Newsletter · Issue 14 — Article · Topics: CI/CD & Automation
  **Published:** `2023-04-23T00:00:00.000Z`
  **NeKI brief:** Examines A technical guide to Mobile CI/CD in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🚀 Fastlane 2.212.2 is out!](https://github.com/fastlane/fastlane/releases/tag/2.212.2) — iOS CI Newsletter · Issue 14 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2023-04-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Fastlane 2.212.2 is out!, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [one of my contributions which makes deliver’s verify_only option work out of the box again by using altool instead of the iTunes Transporter](https://github.com/fastlane/fastlane/pull/20738) — iOS CI Newsletter · Issue 14 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2023-04-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for one of my contributions which makes deliver’s verify_only option work out of the box again by using altool…, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [chatty](https://github.com/polpielladev/chatty-cli) — iOS CI Newsletter · Issue 13 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for chatty, relevant to Architecture and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [✨ Using GitHub Actions to create PRs automatically](https://github.com/SwiftPackageIndex/PackageList/blob/main/.github/workflows/issues.yml) — iOS CI Newsletter · Issue 12 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2023-03-26T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Using GitHub Actions to create PRs automatically, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub webhooks](https://docs.github.com/en/webhooks-and-events/webhooks/about-webhooks) — iOS CI Newsletter · Issue 12 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2023-03-26T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for GitHub webhooks, relevant to Developer Tools and Xcode. Inspect its implementation, open issues, and release state before adopting the approach.
- [release of Fastlane 2.211.0](https://github.com/fastlane/fastlane/releases/tag/2.211.0) — iOS CI Newsletter · Issue 11 — Source repository · Topics: CI/CD & Automation · Developer Tools · Xcode
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for release of Fastlane 2.211.0, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [version 1.3.0](https://github.com/RobotsAndPencils/xcodes/releases/tag/1.3.0) — iOS CI Newsletter · Issue 11 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Xcode
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for version 1.3.0, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [🚀 How to build custom Fastlane actions](https://www.runway.team/blog/how-to-build-custom-fastlane-action-and-plugin) — iOS CI Newsletter · Issue 11 — Article · Topics: CI/CD & Automation
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Walks through how to build custom Fastlane actions, with practical context for CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Runway’s blog](https://www.runway.team/blog) — iOS CI Newsletter · Issue 11 — Article · Topics: CI/CD & Automation
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Examines Runway’s blog in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Pull Request](https://github.com/fastlane/fastlane/pull/21073) — iOS CI Newsletter · Issue 10 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2023-02-26T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Pull Request, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [the release of version 2.212.1 of Fastlane](https://github.com/fastlane/fastlane/releases/tag/2.212.1) — iOS CI Newsletter · Issue 10 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `2023-02-26T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for the release of version 2.212.1 of Fastlane, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Quickstart CI/CD by Runway](https://www.runway.team/blog/introducing-quickstart-ci-cd-by-runway) — iOS CI Newsletter · Issue 10 — Article · Topics: CI/CD & Automation · Cross-Platform & Web
  **Published:** `2023-02-26T00:00:00.000Z`
  **NeKI brief:** Examines Quickstart CI/CD by Runway in the context of CI/CD & Automation and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [How big open-source projects handle CI/CD](https://rudrank.blog/open-source-ios-projects) — iOS CI Newsletter · Issue 9 — Article · Topics: CI/CD & Automation
  **Published:** `2023-02-12T00:00:00.000Z`
  **NeKI brief:** Examines How big open-source projects handle CI/CD in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Saving money when using GitHub Actions](https://blog.eidinger.info/save-money-when-using-github-actions-for-ios-cicd) — iOS CI Newsletter · Issue 8 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2023-01-29T00:00:00.000Z`
  **NeKI brief:** Examines Saving money when using GitHub Actions in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [xcmonkey](https://github.com/alteral/xcmonkey) — iOS CI Newsletter · Issue 8 — Source repository · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2023-01-29T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for xcmonkey, relevant to Developer Tools and Testing. Inspect its implementation, open issues, and release state before adopting the approach.
- [using a self-hosted runner](https://docs.github.com/en/actions/hosting-your-own-runners/using-self-hosted-runners-in-a-workflow) — iOS Dev Weekly · Issue 594 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `27th January 2023`
  **NeKI brief:** There are some good tips in this post from Marco Eidinger for keeping costs down when running GitHub Actions on private repositories, but the one I was surprised to see missing was using a self-hosted runner.
- [New version of Bitrise Insights is out!](https://bitrise.io/blog/post/insights-v2-is-here-and-heres-what-to-expect) — iOS CI Newsletter · Issue 6 — Article · Topics: CI/CD & Automation
  **Published:** `2023-01-01T00:00:00.000Z`
  **NeKI brief:** Examines New version of Bitrise Insights is out! in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [GitHub issue about the availability of macOS 13 GitHub-hosted runners](https://github.com/actions/runner-images/issues/6426) — iOS CI Newsletter · Issue 5 — Source repository · Topics: Developer Tools
  **Published:** `2022-12-18T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for GitHub issue about the availability of macOS 13 GitHub-hosted runners, relevant to Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Update fastlane on your CI! 🚀](https://github.com/fastlane/fastlane/releases/tag/2.210.0) — iOS CI Newsletter · Issue 1 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Update fastlane on your CI! 🚀, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [deliver](https://docs.fastlane.tools/actions/deliver) — iOS CI Newsletter · Issue 1 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Examines deliver in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [pilot](http://docs.fastlane.tools/actions/pilot) — iOS CI Newsletter · Issue 1 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Examines pilot in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [iTMSTransporter command line tool](https://github.com/fastlane/fastlane/issues/20371) — iOS CI Newsletter · Issue 1 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for iTMSTransporter command line tool, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Scalable Apple silicon M1 in the cloud, for your iOS CI/CD by Bitrise](https://www.bitrise.io/why/technologies/virtualized-m1-environment) — iOS Dev Weekly · Issue 565 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `1st July 2022`
  **NeKI brief:** Explores Scalable Apple silicon M1 in the cloud, for your iOS CI/CD by Bitrise, focusing on accelerate your transition to apple silicon through our fully virtualized,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The world’s first virtualized M1 CI/CD environment on Bitrise](https://www.bitrise.io/m1-preregister) — iOS Dev Weekly · Issue 538 — Article · Topics: CI/CD & Automation · Performance · Testing
  **Published:** `17th December 2021`
  **NeKI brief:** Explores The world’s first virtualized M1 CI/CD environment on Bitrise, focusing on optimized for speed, stability, and extensibility. the performance of apple. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How does Homebrew work with Rosetta on M1 machines?](https://www.youtube.com/watch?v=EG-K5n20_HQ) — iOS Dev Weekly · Issue 531 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `29th October 2021`
  **NeKI brief:** You probably don’t need as elaborate a brew setup as Josh Holtz does, being the lead maintainer of fastlane, but that doesn’t mean you won’t learn plenty from this half-hour video and associated blog post. I learned plenty about Rosetta from watching this…
- [associated blog post](https://www.joshholtz.com/blog/2021/10/27/joshs-m1-development-environemnt.html) — iOS Dev Weekly · Issue 531 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `29th October 2021`
  **NeKI brief:** Examines This is the setup I’m using on my M1 Mac (and Rosetta) to handle homebrew, zsh, Ruby and python version managers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Automating App Store Screenshots](https://lickability.com/blog/automating-app-store-screenshots-with-fastlane-and-swiftui) — iOS Dev Weekly · Issue 519 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Localization
  **Published:** `6th August 2021`
  **NeKI brief:** Whenever I mention using fastlane’s snapshot tool for App Store screenshots, I justify it by saying it’ll save you time if you have “ten screenshots for every device type in different localisations”. In reality, even if you have just two screenshots in one…
- [fastlane and the Upcoming Two-Step/Two-Factor Enforcement](https://www.joshholtz.com/blog/2021/02/17/apples-2fa-with-fastlane.html) — iOS Dev Weekly · Issue 495 — Article · Topics: CI/CD & Automation · Concurrency · Cross-Platform & Web
  **Published:** `19th February 2021`
  **NeKI brief:** Examines Preface. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [no idea](https://github.com/fastlane/fastlane/graphs/contributors) — iOS Dev Weekly · Issue 484 — Source repository · Topics: App Distribution & Store Operations · App Intents & System Surfaces · CI/CD & Automation
  **Published:** `27th November 2020`
  **NeKI brief:** Presents no idea, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Managing Version Numbers with Fastlane](https://benscheirman.com/2020/10/managing-version-numbers-with-fastlane) — iOS Dev Weekly · Issue 479 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `23rd October 2020`
  **NeKI brief:** Choosing how to increment your app’s version number is one thing, but remembering all the steps to get a release out of the door is another! How many times have you forgotten to increment the version number before an App Store Connect upload? Or maybe you…
- [Swift Package Continuous Integration Guide](https://learningswift.brightdigit.com/swift-package-continuous-integration-guide) — iOS Dev Weekly · Issue 446 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `6th March 2020`
  **NeKI brief:** Examines Swift Package Continuous Integration Guide, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Continuous Integration Using GitHub Actions](https://andreaslydemann.com/continuous-integration-using-github-actions-for-ios-projects) — iOS Dev Weekly · Issue 438 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `10th January 2020`
  **NeKI brief:** Examines Github Actions are finally publicly released! It’s an opportunity to easily enable continuous integration in your projects on GitHub, so here’s how you set it up for yo. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this post from Jesse Squires](https://www.jessesquires.com/blog/selecting-an-xcode-version-on-github-ci) — iOS Dev Weekly · Issue 438 — Article · Topics: Developer Tools · Xcode
  **Published:** `10th January 2020`
  **NeKI brief:** Explains selecting an Xcode version in GitHub Actions, covering runner images and reproducible CI configuration. Compare its pinning strategy with your workflow, then verify currently supported macOS and Xcode combinations.
- [Build and operate better iOS apps, faster](https://www.bitrise.io/features/ios-features) — iOS Dev Weekly · Issue 424 — Article · Topics: CI/CD & Automation · Testing · Xcode
  **Published:** `4th October 2019`
  **NeKI brief:** Examines Build and operate better iOS apps, faster, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Puma](https://github.com/pumaswift/Puma) — iOS Dev Weekly · Issue 418 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `23rd August 2019`
  **NeKI brief:** Examines Puma, focusing on build utilities, written in pure swift (not that that really matters for build utilities) from khoa pham. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Continuous Integration](http://khanlou.com/2019/07/continuous-integration) — iOS Dev Weekly · Issue 413 — Article · Topics: CI/CD & Automation · Personal Essays · Testing
  **Published:** `19th July 2019`
  **NeKI brief:** Examines Khanlou | Continuous Integration. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Life in the slow lane](https://silverhammermba.github.io/blog/2019/03/12/slowlane) — iOS Dev Weekly · Issue 395 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `15th March 2019`
  **NeKI brief:** The article reflects on software performance and the practical consequences of allowing applications or workflows to become slow.
- [Ending my fastlane chapter](https://krausefx.com/blog/ending-my-fastlane-chapter) — iOS Dev Weekly · Issue 391 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Community & Business
  **Published:** `15th February 2019`
  **NeKI brief:** The page covers “Ending my fastlane chapter” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [actual documentation for the feature](https://docs.fastlane.tools/actions/capture_ios_screenshots) — iOS Dev Weekly · Issue 387 — Article · Topics: CI/CD & Automation · Objective-C & Cocoa
  **Published:** `18th January 2019`
  **NeKI brief:** Examines capture_ios_screenshots - fastlane docs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Continuous Delivery for your profile picture](https://krausefx.com/blog/continuous-delivery-for-your-profile-picture) — iOS Dev Weekly · Issue 385 — Article · Topics: CI/CD & Automation · Performance
  **Published:** `4th January 2019`
  **NeKI brief:** The article describes an automated continuous-delivery workflow for generating and deploying a profile picture.
- [Automate your library releases with Fastlane](https://mar.codes/2018-11-14/Automate-open-source-libraries-releases-with-fastlane) — iOS Dev Weekly · Issue 381 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Objective-C & Cocoa
  **Published:** `7th December 2018`
  **NeKI brief:** It’s easy to forget that fastlane can automate much more than code signing and App Store releases. What about using it to release new versions of open source libraries you maintain to CocoaPods? Marcos Griselli shows us how.
- [swiff](https://github.com/agens-no/swiff) — iOS Dev Weekly · Issue 366 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `24th August 2018`
  **NeKI brief:** Examines swiff, focusing on this script from håvard fossli looks useful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Build Incrementation Techniques for iOS Apps](http://shashikantjagtap.net/build-incrementation-techniques-for-ios-release-train) — iOS Dev Weekly · Issue 353 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `25th May 2018`
  **NeKI brief:** Presents build-incrementation techniques for an iOS release train. Follow it for concrete versioning and CI release workflow ideas, while checking current Xcode and App Store requirements.
- [Microsoft and GitHub Present: A Solution for Mobile CI](https://aka.ms/appcentermarketplace) — iOS Dev Weekly · Issue 351 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Microsoft and GitHub Present: A Solution for Mobile CI, focusing on automate the build-test-distribute process for your mobile projects in github. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Capture video of the iOS Simulator with simctl](http://www.avanderlee.com/workflow/capture-ios-simulator-video-app-preview) — iOS Dev Weekly · Issue 351 — Article · Topics: CI/CD & Automation · Graphics, Media & Games · Xcode
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Create App Preview videos using App Store Connect's required specifications without the need of conversions using tools like ffmpeg. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [fastlane.ci](https://github.com/fastlane/ci/releases/tag/1.0.0.alpha.1) — iOS Dev Weekly · Issue 346 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `6th April 2018`
  **NeKI brief:** Records an early fastlane.ci release and its automation-project context. Useful for understanding the historical direction of iOS CI tooling, while current behavior requires maintained documentation.
- [Write fastlane configurations in Swift](https://docs.fastlane.tools/getting-started/ios/fastlane-swift) — iOS Dev Weekly · Issue 331 — Article · Topics: CI/CD & Automation · Swift
  **Published:** `15th December 2017`
  **NeKI brief:** This change seemed inevitable – you can now write your Fastfile in Swift, for those of us without experience writing Ruby! 🎉 While this is currently in beta, I’m looking forward to Fastlane.swift to become feature-complete. This is going to make these tools…
- [Automating Your App’s Release Process Using fastlane](https://m.youtube.com/watch?v=scfOk5SgrKU) — iOS Dev Weekly · Issue 325 — Video · Topics: CI/CD & Automation · Graphics, Media & Games
  **Published:** `3rd November 2017`
  **NeKI brief:** I have not used fastlane for my own projects yet, but I don’t know why – it seems to make things better in so many ways. In this talk, Felix Krause and Josh Liebowitz discuss how to use fastlane to make releasing new app versions a breeze.
- [Snapshot now supports multiple concurrent simulators](http://fabric.io/blog/2017/8/29/fastlane-snapshot-supports-multiple-concurrent-simulators) — iOS Dev Weekly · Issue 316 — Article · Topics: CI/CD & Automation · Xcode
  **Published:** `1st September 2017`
  **NeKI brief:** Explores Snapshot now supports multiple concurrent simulators in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Introducing fastlane precheck](https://fabric.io/blog/introducing-fastlane-precheck) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `30th June 2017`
  **NeKI brief:** Ah fastlane, what would we do without it? 🎉 Precheck is a wonderful App Store metadata checker that’ll make sure you don’t fall foul of some of the the most common reasons for a first rejection. Looks great! ✅
- [one of our events](https://www.buddybuild.com/blog/buddybuild-events-at-wwdc17) — iOS Dev Weekly · Issue 303 — Article · Topics: Apple Platform Ecosystem · CI/CD & Automation · Testing
  **Published:** `2nd June 2017`
  **NeKI brief:** Explores one of our events in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [fastlane](https://github.com/fastlane/fastlane) — iOS Dev Weekly · Issue 294 — Source repository · Topics: CI/CD & Automation · Developer Tools · Graphics, Media & Games
  **Published:** `31st March 2017`
  **NeKI brief:** Felix Krause, the creator of fastlane, on what he has learned from working on a massively successful open source project. Nobody creates a new repository on Github expecting it to grow in the way Felix’s has, but before you realize it, this talk may help you…
- [iOS Continous integration: Xcode Server, Jenkins, Travis and fastlane](http://thebugcode.github.io/ios-continous-integration-choosing-a-build-server-and-tooling) — iOS Dev Weekly · Issue 292 — Article · Topics: CI/CD & Automation · Developer Tools · Xcode
  **Published:** `17th March 2017`
  **NeKI brief:** Profiles iOS Continous integration: Xcode Server, Jenkins, Travis and fastlane, a developer tool or product relevant to Apple-platform workflows. Evaluate its integration surface, operational costs, privacy implications, and fit for the current project, then verify supported SDKs and capabilities before adoption.
- [Code signing guides from fastlane](https://github.com/fastlane/fastlane/tree/master/fastlane/docs/Codesigning) — iOS Dev Weekly · Issue 258 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `8th July 2016`
  **NeKI brief:** Examines Code signing guides from fastlane, focusing on felix krause with a set of guides covering all things code signing. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Introducing fastlane plugins](https://fabric.io/blog/introducing-fastlane-plugins) — iOS Dev Weekly · Issue 257 — Article · Topics: CI/CD & Automation
  **Published:** `1st July 2016`
  **NeKI brief:** Examines Discover Firebase, Google’s mobile and web app development platform that helps developers build apps and games that users will love. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [CocoaPods and Capital One](http://blog.cocoapods.org/Capital-One) — iOS Dev Weekly · Issue 222 — Article · Topics: CI/CD & Automation · Developer Community & Business · Objective-C & Cocoa
  **Published:** `30th October 2015`
  **NeKI brief:** This announcement describes Capital One sponsoring CocoaPods development and distinguishes project support from product promotion. It is useful historical context for how critical open-source infrastructure can receive sustainable funding from companies that depend on it.
- [fastlane is now part of Fabric](https://krausefx.com/blog/fastlane-is-now-part-of-fabric) — iOS Dev Weekly · Issue 221 — Article · Topics: CI/CD & Automation
  **Published:** `23rd October 2015`
  **NeKI brief:** The wonderful fastlane project had a big announcement this week, it’s now part of Twitter’s Fabric suite. The great news is that this means it will get plenty of dedicated development time which it will continue to need to keep up with a constantly moving…
- [running tests](https://github.com/fastlane/scan) — iOS Dev Weekly · Issue 221 — Source repository · Topics: CI/CD & Automation · Developer Tools · Personal Essays
  **Published:** `23rd October 2015`
  **NeKI brief:** Presents running tests, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Thoughts on iOS build tools](https://krausefx.com/blog/ios-tools) — iOS Dev Weekly · Issue 211 — Article · Topics: CI/CD & Automation
  **Published:** `14th August 2015`
  **NeKI brief:** Examines Up until now you had 2 good ways to build and sign your application from the command line:. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [gym](https://github.com/fastlane/gym) — iOS Dev Weekly · Issue 211 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `14th August 2015`
  **NeKI brief:** The page covers “gym” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Shenzen](https://github.com/nomad/shenzhen) — iOS Dev Weekly · Issue 211 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `14th August 2015`
  **NeKI brief:** Mattt Thompson released a new version of Shenzhen this week, the utility for creating and uploading IPA archives to various services. The big news is that builds can now be uploaded directly to iTunes Connect using this tool. If you’re new to iOS development…
- [Pilot and Boarding](https://github.com/fastlane/pilot) — iOS Dev Weekly · Issue 208 — Source repository · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** Examines The best way to manage your TestFlight testers and builds from your terminal - fastlane-old/pilot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Boarding](https://github.com/fastlane/boarding) — iOS Dev Weekly · Issue 208 — Source repository · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Instantly create a simple signup page for TestFlight beta testers - fastlane/boarding. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [thoughts on automation](https://krausefx.com/blog/letting-computers-do-the-hard-work) — iOS Dev Weekly · Issue 208 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** The page covers “thoughts on automation” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [sigh](https://github.com/KrauseFx/sigh/releases/tag/1.0.0.beta5) — iOS Dev Weekly · Issue 202 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `12th June 2015`
  **NeKI brief:** Provides the sigh source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Fastlane 1.0](https://krausefx.com/blog/fastlane-10) — iOS Dev Weekly · Issue 197 — Article · Topics: CI/CD & Automation
  **Published:** `8th May 2015`
  **NeKI brief:** The fastlane suite of tools has been around for a while now but this week Felix Krause shipped 1.0. The release includes OS X support, better documentation, auto update and a few other smaller features and bug fixes. Even if you don’t want to automate an…
- [Unofficial iTunes Connect API Docs](https://github.com/fastlane/itc-api-docs) — iOS Dev Weekly · Issue 191 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the Unofficial iTunes Connect API Docs source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Continuous Integration With Xcode Server](http://useyourloaf.com/blog/2014/11/02/continuous-integration-with-xcode-server.html) — iOS Dev Weekly · Issue 171 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Xcode
  **Published:** `7th November 2014`
  **NeKI brief:** A historical Xcode Server CI setup guide showing how bots, integrations, and signing fit together. It is useful for understanding the pre-Xcode-Cloud workflow and its operational constraints.
- [Stop Sucking At Build Environments](http://blog.sudeium.com/2013/10/24/stop-sucking-at-build-environments) — iOS Dev Weekly · Issue 136 — Article · Topics: CI/CD & Automation
  **Published:** `7th March 2014`
  **NeKI brief:** Alex Garibay on the state of automating builds and continuous integration for iOS projects (Spoiler: Not much good news). However he then turns the post all positive by going through best practices for getting your project into the best possible state for…
