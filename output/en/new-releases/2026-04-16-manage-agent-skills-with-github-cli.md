---
title: "Manage agent skills with GitHub CLI"
date: "2026-04-16"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-16-manage-agent-skills-with-github-cli/"
---

# Manage agent skills with GitHub CLI

---

## What's new

**GitHub CLI v2.90.0** introduces the `gh skill` command, a **package-manager-style** interface for discovering, installing, updating, and publishing **agent skills** across any AI coding agent.

### Why it matters

- **Universal agent support** — skills work with Copilot, Claude Code, Cursor, Codex, Gemini CLI, and any Agent Skills spec-compatible host
- **Reproducible installs** — skills are pinned by tag or commit SHA for supply chain integrity
- **Provenance tracking** — git tree SHAs and SKILL.md metadata recorded on every install
- **Discovery built-in** — `gh skill search <keyword>` finds available skills across GitHub repositories
- **Scoped installs** — target a specific agent and scope (user or repository) with flags

### Where you can use it

- **Terminal** — available in GitHub CLI v2.90.0+
- **Any AI agent host** — skills install into the appropriate config for your chosen agent

### Who gets it

- **All GitHub users** — available with GitHub CLI v2.90.0 and any compatible AI coding agent subscription
- **Available now** — `gh skill install`, `gh skill search`, `gh skill update`, `gh skill publish`

<!--
speaker_notes:
Before this, managing agent skills meant manually copying folders and files to different locations for each AI agent — error-prone and non-reproducible. The `gh skill` command brings npm-style package management to agent skills. You can search for skills across GitHub, install them with version pinning, update them when content changes, and publish your own. The spec is open, so skills work across Copilot, Claude Code, Cursor, Codex, and Gemini CLI. Version pinning and SHA tracking are critical for supply chain security since skills can execute code. Great demo: run `gh skill search` to find a documentation-writing skill, install it pinned to a version, then show it working in Copilot.
-->
