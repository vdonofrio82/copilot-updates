---
title: "GitHub Copilot CLI now supports Copilot auto model selection"
date: "2026-04-17"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-17-github-copilot-cli-now-supports-copilot-auto-model-selection/"
---

# GitHub Copilot CLI now supports Copilot auto model selection

---

## What's new

**GitHub Copilot CLI** now supports **auto model selection** (GA), dynamically routing each request to the most capable available model while respecting rate limits and organizational policies.

### Why it matters

- **Smart routing** — automatically selects among GPT-5.4, GPT-5.3-Codex, Claude Sonnet 4.6, and Haiku 4.5 based on availability
- **Rate limit resilience** — routes around congestion or temporary provider unavailability
- **Transparent selection** — the CLI reports which model was selected for every request
- **Policy compliance** — strictly respects organization and admin model restrictions
- **10% billing discount** — paid subscribers using auto get a 10% discount on the premium request multiplier

### Where you can use it

- **GitHub Copilot CLI** — all platforms where CLI is installed

### Who gets it

- **All paid Copilot plans** — generally available now
- **Toggle anytime** — switch between `auto` and a pinned model at any time

<!--
speaker_notes:
Auto model selection is now GA in Copilot CLI. Instead of manually picking a model for every session, the CLI automatically routes to the best model for your request — whether that's GPT-5.4, Codex, or a Claude model — while staying within your organization's policy constraints. It also mitigates rate limit friction by routing around congestion. Transparency is built in: the CLI tells you exactly which model handled each request. There's even a 10% billing discount when using auto mode. Admins don't need to do anything — it respects existing policies. Good demo angle: run a few complex coding tasks in auto mode and show the model selection output.
-->
