---
title: "Copilot code review user counts now aggregate in usage metrics API"
date: "2026-04-22"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-22-copilot-code-review-user-counts-now-aggregate-in-usage-metrics-api/"
---

# Copilot code review user counts now aggregate in usage metrics API

---

## What changed

**Copilot code review usage reports** now include separate **active and passive user counts** at daily, weekly, and monthly intervals, giving admins clear visibility into intentional adoption versus policy-driven usage.

### Why it matters

- **Active vs. passive distinction** — active users manually requested or applied a Copilot review; passive users had reviews auto-triggered by policy
- **ROI clarity** — distinguish genuine developer adoption from automatic review enforcement
- **Trend tracking** — daily, weekly, and monthly breakdowns enable accurate adoption trend analysis
- **"Active always trumps passive"** — users counted in both categories in a period are reported only as active

### Details

Six new fields in enterprise and organization 1-day and 28-day usage metrics:

| Field | Meaning |
|---|---|
| `daily_active_copilot_code_review_users` | Users who actively engaged with code review daily |
| `daily_passive_copilot_code_review_users` | Policy-triggered reviews, no active engagement |
| `weekly_active_copilot_code_review_users` | Active engagement weekly |
| `weekly_passive_copilot_code_review_users` | Passive policy-triggered weekly |
| `monthly_active_copilot_code_review_users` | Active engagement monthly |
| `monthly_passive_copilot_code_review_users` | Passive policy-triggered monthly |

### Who gets it

- **All enterprise and organization admins** — available now via the Copilot usage metrics API
- **No action required** — new fields appear automatically in existing reports

<!--
speaker_notes:
This reporting improvement matters for engineering leaders making data-driven decisions about Copilot code review rollout. Previous metrics didn't distinguish between developers actively choosing to use Copilot code review versus those whose reviews were triggered automatically by policy. Now there are six new fields covering daily, weekly, and monthly breakdowns of both active and passive users. Active users deliberately requested a review or applied a suggestion; passive users had reviews triggered by policy but didn't engage. If you're both, you're only counted as active. This lets teams see true adoption curves separate from policy enforcement numbers. The fields appear automatically in existing reports, so no migration work is needed.
-->
