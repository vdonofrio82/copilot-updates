---
title: "Bring your own language model key in VS Code now available"
date: "2026-04-22"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-22-bring-your-own-language-model-key-in-vs-code-now-available/"
---

# Bring your own language model key in VS Code now available

---

## What's new

**GitHub Copilot Business and Enterprise** users can now use **Bring Your Own Key (BYOK)** in **VS Code**, connecting their own API keys for models from Anthropic, OpenAI, Azure, Google Gemini, OpenRouter, and local providers like Ollama.

### Why it matters

- **Provider freedom** — access models not included in the default Copilot offering, including local and air-gapped options
- **Independent billing** — BYOK usage is billed directly by the provider, not by GitHub, and does not count against Copilot request quotas
- **Compliance and cost control** — route to specific providers for regional or regulatory requirements
- **Admin governance** — BYOK policy is on by default; admins can disable per organization
- **Chat-scoped** — applies to VS Code Chat interface and custom agents; does not affect code completions

### Where you can use it

- **Visual Studio Code** — all versions with the Copilot extension
- **VS Code Chat** — built-in chat and custom agent panels

### Who gets it

- **Copilot Business and Enterprise** — available now
- **Default state** — enabled for organizations by default; admins can disable via Settings → Copilot policies

<!--
speaker_notes:
BYOK in VS Code is now generally available for Copilot Business and Enterprise. This lets teams plug in their own API keys for models from Anthropic, OpenAI, Azure, Gemini, and even local models via Ollama. The key differentiator: usage goes directly through the provider and doesn't touch your Copilot request quotas. This is a strong value proposition for organizations with existing enterprise agreements with model providers or that need to use specific models for compliance reasons. It's scoped to VS Code Chat — completions aren't affected. A great demo: show installing a third-party language model extension, connecting your own Anthropic key, and using Claude models in VS Code Chat alongside regular Copilot features.
-->
