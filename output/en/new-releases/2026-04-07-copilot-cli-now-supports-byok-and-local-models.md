---
title: "Copilot CLI now supports BYOK and local models"
date: "2026-04-07"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-07-copilot-cli-now-supports-byok-and-local-models/"
---

# Copilot CLI now supports BYOK and local models

---

## What's new

**GitHub Copilot CLI** now supports **Bring Your Own Key (BYOK)** and **local model** connections, enabling fully air-gapped and provider-independent terminal workflows.

### Why it matters

- **Provider flexibility** — connect to Azure OpenAI, Anthropic, or any OpenAI-compatible API or local models (Ollama, vLLM, Foundry Local) via environment variables
- **Air-gapped mode** — set `COPILOT_OFFLINE=true` to disable all telemetry and restrict traffic to your own provider
- **No forced GitHub auth** — use the CLI with only your provider credentials; GitHub login is optional
- **Sub-agent inheritance** — built-in sub-agents (explore, task, code-review) inherit your provider configuration automatically
- **Transparent errors** — misconfigured providers show actionable messages; the CLI never silently falls back to GitHub-hosted models

### Where you can use it

- **Terminal / shell** — any environment where GitHub Copilot CLI is installed
- **Air-gapped environments** — organizations with strict network egress policies
- **Local model setups** — developer machines running Ollama, vLLM, or Microsoft Foundry Local

### Who gets it

- **All Copilot plans** — BYOK is available to all subscribers
- **Minimum model requirements** — tool calling + streaming support and ≥128k context window recommended
- **Available now** — configure with `copilot help providers`

<!--
speaker_notes:
This is a significant unlock for enterprises with strict data sovereignty or air-gap requirements. Copilot CLI can now be pointed at any OpenAI-compatible endpoint — including Azure OpenAI, Anthropic, or a locally running Ollama instance — by setting a few environment variables. Setting COPILOT_OFFLINE=true fully disables telemetry, making it suitable for classified or regulated environments. GitHub auth is optional in BYOK mode. Sub-agents like "explore" and "task" automatically inherit the provider config. If something's misconfigured, the CLI gives you an actionable error rather than silently degrading. For a demo, show setting up Copilot CLI with a local Ollama model and running a code review session entirely offline. This resonates strongly with financial services, government, and defense customers.
-->
