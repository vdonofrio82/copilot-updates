---
title: "C++ code intelligence for GitHub Copilot CLI in public preview"
date: "2026-04-22"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-22-c-code-intelligence-for-github-copilot-cli-in-public-preview/"
---

# C++ code intelligence for GitHub Copilot CLI in public preview

---

## What's new

**GitHub Copilot CLI** now offers **C++ code intelligence** via the Microsoft C++ Language Server — the same IntelliSense engine used in Visual Studio and VS Code — bringing precise symbol navigation and semantic analysis to the terminal in **public preview**.

### Why it matters

- **Semantic precision** — go-to-definition, symbol search, call hierarchies, and type information via a real language server, not text matching
- **Handles C++ complexity** — accurately resolves complex include hierarchies, macros, templates, and build dependencies
- **Terminal-native** — brings IDE-quality C++ intelligence to shell-based workflows without a GUI editor
- **Cross-platform build support** — CMake and MSBuild both supported

### Where you can use it

- **GitHub Copilot CLI** — any platform where the CLI is installed with a `compile_commands.json` project
- **CMake projects** — automated setup via dedicated GitHub skill
- **MSBuild projects** — sample app available to extract metadata

### Who gets it

- **Active Copilot subscribers** — public preview, available now
- **Setup steps** — authenticate with Copilot CLI, provide a `compile_commands.json`, install the Microsoft C++ Language Server npm package
- **Tip** — append "Use the C++ LSP" to queries for best results

<!--
speaker_notes:
C++ is notoriously difficult for AI coding tools because of its complexity — macros, templates, include hierarchies, and build dependencies all conspire to make naive text-search approaches unreliable. This update brings the Microsoft C++ Language Server — the same engine powering IntelliSense in Visual Studio and VS Code — to the Copilot CLI. The CLI can now answer questions about symbol definitions, call hierarchies, and type information with real semantic accuracy. The key requirement is a compile_commands.json file. For a great demo, take a large open-source C++ project like LLVM or OpenCV, load it in the CLI, and show precise go-to-definition and refactoring suggestions. This is a big win for embedded systems, game dev, and high-performance computing teams.
-->
