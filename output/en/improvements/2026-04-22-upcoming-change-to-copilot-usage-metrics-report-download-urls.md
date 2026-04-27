---
title: "Upcoming change to Copilot usage metrics report download URLs"
date: "2026-04-22"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-22-upcoming-change-to-copilot-usage-metrics-report-download-urls/"
---

# Upcoming change to Copilot usage metrics report download URLs

---

## What changed

**Copilot usage metrics report download URLs** are migrating from Azure Front Door domains to stable, GitHub-owned domains on **May 20, 2026**, simplifying firewall and proxy allowlist management for enterprises.

### Why it matters

- **Stable, predictable URLs** — GitHub-owned domains won't change during infrastructure redeployments
- **Simpler allowlisting** — one stable hostname replaces volatile Azure Front Door URLs
- **Uninterrupted access** — updating allowlists before May 20 prevents download disruptions
- **Fallback coverage** — add `*.blob.core.windows.net` if uninterrupted access through Azure Front Door outages is critical

### Details

| Customer type | Old domain pattern | New domain pattern |
|---|---|---|
| **github.com (GHEC)** | `copilot-reports-*.b01.azurefd.net` | `copilot-reports.github.com` |
| **ghe.com** | `copilot-reports-*.b01.azurefd.net` | `copilot-reports.*.ghe.com` |

### Who gets it

- **All enterprise customers using Copilot usage metrics reports** — action required before May 20, 2026
- **Action needed** — add the new domain(s) to your firewall/proxy allowlist now

<!--
speaker_notes:
This is an infrastructure migration that primarily affects enterprise customers with firewall or proxy allowlists. The download URLs for Copilot usage metrics reports are moving from volatile Azure Front Door URLs to stable, GitHub-owned domains on May 20, 2026. For github.com customers the new domain is copilot-reports.github.com. For ghe.com customers it's copilot-reports.*.ghe.com. If your org uses automated report downloads or has strict firewall rules, update your allowlists before May 20 to avoid disruptions. There's also a potential fallback to Azure Blob Storage URLs — it's worth adding *.blob.core.windows.net as well for full resilience. The old domains continue to work through the transition period.
-->
