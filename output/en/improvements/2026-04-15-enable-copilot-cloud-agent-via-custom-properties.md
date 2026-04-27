---
title: "Enable Copilot cloud agent via custom properties"
date: "2026-04-15"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-15-enable-copilot-cloud-agent-via-custom-properties/"
---

# Enable Copilot cloud agent via custom properties

---

## What changed

Enterprise admins can now **selectively enable the Copilot cloud agent** on a per-organization basis using **custom properties** and new REST API endpoints, replacing the previous all-or-nothing global toggle.

### Why it matters

- **Granular rollout** — enable the cloud agent for specific organizations without affecting the entire enterprise
- **REST API control** — new endpoints to set policy state, add or remove organizations from the enabled list
- **AI Controls UI** — new "Enabled for selected organizations" option in the Copilot Cloud Agent settings
- **Phased adoption** — run pilots in selected teams before broad enterprise rollout

### How to get started

1. Navigate to your enterprise's **Copilot AI Controls settings page**
2. Select **"Enabled for selected organizations"** under Copilot Cloud Agent
3. Add organizations using the UI or the new REST API endpoints
4. Note: property-based access is evaluated at configuration time; changes to org properties require a manual settings update

### Who gets it

- **GitHub Enterprise Cloud admins** — available now via both UI and REST API

<!--
speaker_notes:
Previously, enabling the Copilot cloud agent was a global switch. Now admins can use custom properties to target specific organizations, or use new REST API endpoints to manage access programmatically. The UI gets a new "Enabled for selected organizations" option in the AI Controls settings. One important nuance: property-based access is only evaluated at configuration time — if an org's properties change later, the access doesn't update automatically. This is a key enterprise governance feature for Copilot cloud agent adoption. Good demo: show the AI Controls settings page with the per-org toggle and a quick REST API call to add an organization.
-->
