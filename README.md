<p align="center">
  <img src="neki/assets/neki_circular.png" alt="NeKI" width="140">
</p>

<h1 align="center">NeKI — Newsletter Knowledge Index</h1>

<p align="center">
  <img alt="AI Agents - Skill" src="https://img.shields.io/badge/AI--Agents-Skill-EF9035?style=flat">
  <a href="LICENSE"><img alt="MIT License for original NeKI material" src="https://img.shields.io/badge/License-MIT-blue?style=flat"></a>
  <a href="https://www.linkedin.com/in/wolfgang-muhsal-12408194/"><img alt="Contact Wolfgang Muhsal on LinkedIn" src="https://img.shields.io/badge/Contact-LinkedIn-95a5a6.svg?style=flat"></a>
</p>

NeKI is a compact routing skill for curated third-party Apple-platform developer writing. It helps agents find newsletters, developer blogs, and articles about Swift, SwiftUI, UIKit, SwiftData, Xcode, and related topics without bundling the underlying articles or republishing their text.

Every entry is a research lead, not an API contract or approved best practice. Check publication dates, author context, project fit, and current Apple primary sources before applying a conclusion.

## Installing NeKI

Install the skill with `npx`:

```bash
npx skills add https://github.com/Gucky/NeKI --skill neki
```

To install it globally for Codex:

```bash
npx skills add https://github.com/Gucky/NeKI --skill neki --agent codex --global
```

For a specific agent:

```bash
npx skills add https://github.com/Gucky/NeKI --skill neki --agent claude-code
```

For all supported agents:

```bash
npx skills add https://github.com/Gucky/NeKI --skill neki --agent '*'
```

If `npx` is not available, install Node.js first. On macOS with Homebrew:

```bash
brew install node
```

## Using NeKI

Invoke the skill directly:

```text
$neki
```

Or ask naturally, for example: “Find third-party perspectives on SwiftData migrations, SwiftUI navigation, or Swift concurrency.”

For a broad question, start with a topic. For curated external reading, use a
newsletter; for a specific author's own writing, use that publication's blog
catalogue.

NeKI provides:

- curated Apple-platform newsletters with selected external reading;
- complete catalogues of directly observed developer blogs and long-form posts;
- focused topic lookups for Swift, SwiftUI, UIKit, SwiftData, Xcode, and related work;
- source context and review boundaries for third-party writing;
- candidate domains as discovery material, not recommendations.

## Using the Index Responsibly

Treat every linked article as a third-party perspective, and verify current framework or API claims against Apple documentation and the project context.

## Requirements

- Node.js for `npx`
- An AI coding assistant that supports agent skills
- Internet access for following the indexed source links

## License and third-party material

NeKI was created by [Wolfgang Muhsal](https://github.com/Gucky). The [MIT License](LICENSE) applies only to original NeKI material: its skill instructions, index structure, authored metadata, code, and assets.

Linked resources, publisher and author names, trademarks, article titles, and any third-party material remain with their respective rights holders. NeKI grants no license in that material; links and minimal routing metadata are provided solely to identify the original source. See [NOTICE](NOTICE).
