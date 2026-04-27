---
title: "Inline agent mode in preview and more in GitHub Copilot for JetBrains IDEs"
date: "2026-04-24"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-24-inline-agent-mode-in-preview-and-more-in-github-copilot-for-jetbrains-ides/"
---

# Inline agent mode in preview and more in GitHub Copilot for JetBrains IDEs

---

## What's new

**GitHub Copilot for JetBrains IDEs** now offers **inline agent mode** (public preview), enhanced **Next Edit Suggestions**, and new **global auto-approve controls** — bringing agentic assistance directly into the editor.

### Why it matters

- **Inline agent mode** — invoke Copilot's full agent capabilities inside the code editor via Inline Chat (Shift+Ctrl+I / Shift+Cmd+I), without switching to a separate panel
- **Next Edit Suggestions with inlay previews** — see suggested edits inline as inlay text; gutter indicators navigate to off-screen suggestions
- **Global auto-approve** — optionally auto-approve all tool calls across workspaces including file edits and terminal commands (use with caution)
- **Granular approval defaults** — new fine-grained options to auto-approve specific categories independently

### Where you can use it

- **All JetBrains IDEs** — IntelliJ IDEA, PyCharm, WebStorm, GoLand, and other JetBrains products
- **Inline Chat** — Shift+Ctrl+I (Windows/Linux) or Shift+Cmd+I (Mac), then switch to agent mode

### Who gets it

- **All Copilot subscribers** — JetBrains plugin with latest update
- **Business / Enterprise** — admins must enable "Editor preview features" for inline agent mode and Next Edit Suggestions
- **Auto-approve settings** — Settings → GitHub Copilot → Chat → Auto Approve

<!--
speaker_notes:
JetBrains users have been waiting for inline agent mode, and it's now in public preview. The big workflow change: instead of switching to the chat panel to run agentic tasks, you can invoke agent mode directly inline in the editor. This keeps developers in the flow. Next Edit Suggestions now show as inline inlay previews so you can see the proposed change in context, and gutter indicators help jump to off-screen suggestions. The global auto-approve option should be flagged carefully — it approves all tool calls including destructive ones. Enterprise customers with admins need to enable "Editor preview features." Good demo: show the inline agent mode workflow for a complex refactoring task entirely within the code editor, then demonstrate jumping between Next Edit Suggestions using gutter indicators.
-->
