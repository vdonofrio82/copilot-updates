---
title: "GitHub Copilot code review will start consuming GitHub Actions minutes on June 1, 2026"
date: "2026-04-27"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-27-github-copilot-code-review-will-start-consuming-github-actions-minutes-on-june-1-2026/"
---

# GitHub Copilot code review will start consuming GitHub Actions minutes on June 1, 2026

---

## What changed

Starting **June 1, 2026**, Copilot code review in **private repositories** will consume **both GitHub AI Credits and GitHub Actions minutes**, reflecting its move to a full agentic, tool-calling architecture.

### Why it matters

- **Architecture upgrade** — Copilot code review now uses a full agentic tool-calling model that runs on GitHub Actions, enabling broader repository context in reviews
- **Billing change for private repos** — each review deducts Actions minutes from your plan's entitlement; overages billed at standard Actions rates
- **Public repos unaffected** — Copilot code review remains free in public repositories
- **Advance notice** — until June 1, 2026, code review is only counted against Copilot Premium Request Units (PRUs)

### How to get started

1. **Review current Actions usage** in Settings → Billing to understand your baseline
2. **Set spending limits** for Actions to control potential overage costs
3. **Monitor Copilot + Actions usage** via the Billing Usage Report after June 1
4. Optionally **adjust code review policies** (frequency, triggers) if budget constraints apply

### Who gets it

- **Copilot Pro, Pro+, Business, and Enterprise** — applies to code review in private repositories
- **Effective date** — June 1, 2026; no billing change before that date

<!--
speaker_notes:
This is an important heads-up for all Copilot customers using code review. Starting June 1 2026, Copilot code review in private repos will consume both AI credits and GitHub Actions minutes. The reason is that the code review agent has moved to a full agentic architecture that runs on GitHub Actions runners to access broader repository context. Public repos are unaffected. Customers should check their current Actions usage and set spending limits now to avoid surprises. Budget-sensitive organizations may want to review how frequently code review is triggered — auto-triggered reviews on every push could add up quickly for high-volume repos. The good news is the enhanced architecture should mean better review quality. Good demo: show the billing settings page with spending limit controls and explain the code review architecture change.
-->
