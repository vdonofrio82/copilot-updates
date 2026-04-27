---
title: "Copilot CLI supports custom registry based MCP allowlists"
date: "2026-04-16"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-16-copilot-cli-supports-custom-registry-based-mcp-allowlists/"
---

# Copilot CLI supports custom registry based MCP allowlists

---

## What's new

**GitHub Copilot CLI** now supports **custom MCP registry allowlists**, letting enterprise admins specify exactly which Model Context Protocol servers can be used in terminal workflows — in **public preview**.

### Why it matters

- **Governance at the CLI level** — MCP server allowlists enforced in the terminal, not just in IDEs or the web UI
- **Bring Your Own Registry (BYOR)** — admins point the CLI at an internal MCP registry URL; only listed servers are permitted
- **Runtime enforcement** — attempts to connect to unlisted MCP servers are blocked immediately
- **Unified policy coverage** — MCP governance now extends consistently across all Copilot surfaces

### Where you can use it

- **Terminal / shell** — any environment running GitHub Copilot CLI
- **Enterprise and organization policies page** — admins configure the registry URL from Copilot policies settings

### Who gets it

- **Copilot Business and Enterprise** — public preview, available now
- **Setup** — admins configure the MCP registry URL per GitHub docs: "Configure an MCP registry for your organization or enterprise"

<!--
speaker_notes:
As MCP usage grows, controlling which MCP servers can be invoked is a critical security concern — especially in regulated industries. This update closes a gap by extending the MCP allowlist policy to the terminal. Admins configure a custom registry URL in the Copilot policies settings, and the CLI enforces it at runtime. If a developer tries to call an unlisted MCP server, it's blocked. Public preview available today for Copilot Business and Enterprise. Good demo: show the admin policy configuration, then demonstrate an attempt to connect to a non-allowlisted server getting blocked versus an allowlisted one succeeding.
-->
