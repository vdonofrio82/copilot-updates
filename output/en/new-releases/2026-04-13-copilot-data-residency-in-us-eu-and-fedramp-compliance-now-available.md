---
title: "Copilot data residency in US + EU and FedRAMP compliance now available"
date: "2026-04-13"
type: "new-releases"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-13-copilot-data-residency-in-us-eu-and-fedramp-compliance-now-available/"
---

# Copilot data residency in US + EU and FedRAMP compliance now available

---

## What's new

**GitHub Copilot** now offers **data residency** for US and EU regions and **FedRAMP Moderate** compliance for US government customers, ensuring all AI inference stays within your designated geography.

### Why it matters

- **Full feature parity** — agent mode, inline suggestions, chat, cloud agent, code review, PR summaries, and CLI all route through data-resident endpoints
- **EU Data Boundary alignment** — covers all EU member states plus EFTA countries (Iceland, Liechtenstein, Norway, Switzerland) as of May 1, 2026
- **FedRAMP Moderate** — US government customers get inference routed through federally authorized model infrastructure
- **Broad model support** — GPT-5.4, Claude Sonnet 4.6, Claude Opus 4.6, and more at launch
- **More regions coming** — Japan and Australia on the roadmap for later in 2026

### Where you can use it

- **GitHub Enterprise Cloud** — enterprise and organization admins enable via Copilot settings
- **All Copilot surfaces** — IDE, CLI, cloud agent, web chat, and mobile all respect residency routing

### Who gets it

- **Copilot Business and Enterprise** — admin opt-in required; off by default
- **Pricing note** — 10% model request multiplier premium applies
- **Gemini models excluded** — Google Cloud does not yet offer data-resident inference

<!--
speaker_notes:
Data residency has been one of the most requested enterprise features for Copilot, and it's now live for US and EU customers. Every part of the Copilot experience routes exclusively through data-resident infrastructure. This is a huge unlock for regulated industries like finance, healthcare, and public sector. EU customers get coverage aligned with the Microsoft EU Data Boundary, and US government customers get FedRAMP Moderate compliance. Note the 10% model multiplier — for regulated customers this is simply the cost of compliance. Admins enable it in Copilot settings; it's off by default. Gemini models aren't yet supported because Google Cloud doesn't offer data-resident inference. Japan and Australia regions are coming later this year. Good demo angle: show the admin toggle in settings and the model availability matrix in the docs.
-->
