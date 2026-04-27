---
title: "Copilot cloud agent starts 20% faster with Actions custom images"
date: "2026-04-27"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-27-copilot-cloud-agent-startup-over-20-faster-with-github-actions-images/"
---

# Copilot cloud agent starts 20% faster with Actions custom images

---

## What changed

The **Copilot cloud agent** now starts over **20% faster** thanks to optimized runner environments built as **GitHub Actions custom images**, continuing a series of cold-start improvements.

### Why it matters

- **Shorter wait times** — less lag between assigning an issue and the agent beginning its first meaningful work
- **Faster feedback loops** — reduced cold-start overhead means high-volume teams see significantly less accumulated wait time per day
- **Deeper Actions integration** — the cloud agent runtime is now prebuilt as a custom Actions image
- **Cumulative gains** — this 20%+ improvement follows a 50% startup reduction in March

### Details

- When a developer assigns an issue to Copilot, starts a task from the Agents tab, or mentions @copilot in a PR, GitHub provisions a cloud workspace. The custom Actions image prebundles the environment so the agent is ready to analyze and execute almost immediately.

### Who gets it

- **All Copilot users with cloud agent access** — improvement is automatic, no configuration required
- **Available now** — effective as of April 27, 2026

<!--
speaker_notes:
This is the second major cold-start improvement for Copilot cloud agent in two months — March brought a 50% reduction, and now April adds another 20%+. The mechanism is straightforward: the runner environment is now prebuilt as a custom GitHub Actions image rather than being set up from scratch on each invocation. For teams running many agent sessions per day, the cumulative time savings are meaningful. This also deepens the Copilot-Actions integration story. The improvement is fully automatic — no configuration needed. Good demo: trigger a cloud agent session and show the startup time, referencing the March/April improvement timeline to show the trajectory of investment in this area.
-->
