---
title: "Copilot CLI activity now included in usage metrics totals and feature breakdowns"
date: "2026-04-10"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-10-copilot-cli-activity-now-included-in-usage-metrics-totals-and-feature-breakdowns/"
---

# Copilot CLI activity now included in usage metrics totals and feature breakdowns

---

## What changed

**Copilot CLI activity** is now **merged into top-level usage metrics totals**, giving organizations a unified view of all Copilot usage across IDE and CLI surfaces.

### Why it matters

- **Unified reporting** — IDE and CLI usage combined in top-level fields like `code_generation_activity_count` and `code_acceptance_activity_count`
- **Feature-level breakdown** — CLI appears as `feature=copilot_cli` in `totals_by_feature` and related breakdowns
- **No manual aggregation** — the API now handles combining CLI and IDE totals automatically
- **Backward compatible** — the standalone `totals_by_cli` section and per-user CLI fields remain

### How to get started

1. Review dashboards and alerts that use top-level metric fields — values will increase now that CLI is included
2. Update threshold-based alerting to reflect the new combined totals
3. Use `feature=copilot_cli` in `totals_by_feature` to isolate CLI-specific usage when needed
4. CLI activity is excluded from `totals_by_ide` to preserve IDE-only analysis

### Who gets it

- **All enterprise and organization admins** — available in single-day and 28-day reports via the Copilot usage metrics API
- **Available now** — update your dashboards before comparing to historical baselines

<!--
speaker_notes:
This is a reporting quality-of-life improvement that matters for engineering leaders trying to understand total Copilot ROI. Previously, CLI usage was siloed in a separate totals_by_cli section, so top-level adoption metrics understated actual usage for teams relying heavily on the CLI. Now CLI is counted alongside IDE usage in all the main fields. It shows up as a distinct feature (copilot_cli) in the feature breakdowns, so you can still isolate it if needed. The important heads-up: dashboards treating these top-level fields as IDE-only will see higher numbers — that's expected, not a bug. Admins should review thresholds before the next reporting cycle.
-->
