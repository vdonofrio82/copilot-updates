---
title: "View and manage agent sessions from issues and projects"
date: "2026-04-23"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-23-view-and-manage-agent-sessions-from-issues-and-projects/"
---

# View and manage agent sessions from issues and projects

---

## What changed

**GitHub Issues and Projects** now surface **agent session status, logs, and steering controls** inline, making AI agent work visible and manageable alongside human contributions.

### Why it matters

- **Session pill on issues** — a new header pill shows all active and completed agent sessions at a glance
- **Session side panel** — click any session to open a sidebar for progress review, log inspection, and real-time agent steering
- **Projects integration** — "Show agent sessions" is now **on by default** for all project views
- **Multi-agent support** — works with Copilot, Claude, Codex, and future custom or third-party agents
- **Smarter label suggestions** — the label picker highlights your most-used labels at the top

### How to get started

1. Assign an issue to Copilot — the **session pill** appears automatically in the issue header
2. Click the session to open the **side panel** and monitor progress or provide steering feedback
3. In **GitHub Projects**, sessions are visible by default — no configuration needed
4. Use the side panel in Projects to inspect session details without leaving the board view

### Who gets it

- **All github.com users** — available now for Copilot, Claude, Codex, and compatible third-party agents
- **Project owners** — "Show agent sessions" is on by default for existing projects

<!--
speaker_notes:
This update treats AI agents as first-class collaborators in GitHub's project management surfaces. Instead of navigating to a separate view to check on Copilot, you now see a session pill right in the issue header showing whether an agent is queued, working, waiting for review, or done. Clicking the session opens a side panel with full logs and the ability to steer the agent. In GitHub Projects, agent sessions are visible by default on all boards and tables. This works for Copilot, Claude, Codex, and future third-party agents. Good demo: assign a complex issue to Copilot, then walk through the issue header pill, the session side panel with live logs, and the Projects board showing the session progress alongside other issues.
-->
