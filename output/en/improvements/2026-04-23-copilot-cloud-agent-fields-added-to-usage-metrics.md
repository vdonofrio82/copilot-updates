---
title: "Copilot cloud agent fields added to usage metrics"
date: "2026-04-23"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-23-copilot-cloud-agent-fields-added-to-usage-metrics/"
---

# Copilot cloud agent fields added to usage metrics

---

## What changed

A new **`used_copilot_cloud_agent`** boolean field has been added to user-level usage metrics, replacing the older `used_copilot_coding_agent` field and aligning terminology with the updated Copilot cloud agent branding.

### Why it matters

- **Brand-aligned field name** — `used_copilot_cloud_agent` reflects the current product branding
- **Backward compatible** — the legacy `used_copilot_coding_agent` field returns the same value until **August 1, 2026**
- **No data loss** — both fields return identical values during the transition window
- **Available in all report types** — single-day and 28-day rolling reports at enterprise and org user levels

### How to get started

1. Update integrations, dashboards, and API consumers to reference **`used_copilot_cloud_agent`**
2. Plan migration from `used_copilot_coding_agent` before **August 1, 2026**
3. Run both fields in parallel to validate your migration

### Who gets it

- **All enterprise and organization admins** — available now in all usage metrics report types
- **Action required by August 1, 2026** — the `used_copilot_coding_agent` field will be deprecated on that date

<!--
speaker_notes:
This is a naming migration that aligns the metrics API with the product rebrand from "Copilot coding agent" to "Copilot cloud agent." A new boolean field — used_copilot_cloud_agent — now appears in user-level reports alongside the old used_copilot_coding_agent field. Both return the same value during the transition period, which runs until August 1, 2026. After that date, the old field will be deprecated. This is mainly important for teams that have built dashboards, reports, or automations against the metrics API — they need to update to the new field name before the deadline. The migration itself is simple (just a field rename). Good demo: show a side-by-side API response with both fields, then show an updated dashboard using the new field name.
-->
