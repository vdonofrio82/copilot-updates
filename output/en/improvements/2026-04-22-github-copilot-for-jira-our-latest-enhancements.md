---
title: "GitHub Copilot for Jira: Our latest enhancements"
date: "2026-04-22"
type: "improvements"
labels: ["copilot"]
image_url: ""
article_url: "https://github.blog/changelog/2026-04-22-github-copilot-for-jira-our-latest-enhancements/"
---

# GitHub Copilot for Jira: Our latest enhancements

---

## What changed

**GitHub Copilot for Jira** receives five new capabilities that deepen integration between Jira workflows and the Copilot cloud agent, moving it from a simple triage assistant to a fully configurable, policy-aware coding agent.

### Why it matters

- **Custom agents** — specify a custom Copilot cloud agent from your GitHub repository directly within a Jira ticket
- **Custom fields** — Copilot reads Atlassian custom fields (e.g., "acceptance criteria") for more accurate, context-aware implementations
- **Branching rules** — the cloud agent respects branch naming conventions specified in the Jira ticket when creating PRs
- **Space-level instructions** — define global default instructions at the Atlassian space level to reduce repetitive configuration
- **Review notifications** — Copilot posts a Jira comment when it opens a draft PR requesting review

### How to get started

1. Update to the latest **GitHub Copilot for Jira** app in your Atlassian Marketplace instance
2. Configure a custom agent by linking a GitHub repository in your Jira project settings
3. Add global instructions at the Atlassian space level for default session behavior
4. Optionally add custom fields (e.g., acceptance criteria) to your Jira issue types for richer agent context

### Who gets it

- **Copilot Business and Enterprise** users with the GitHub Copilot for Jira app installed
- **Available now** — update the Atlassian Marketplace app to unlock all new features

<!--
speaker_notes:
GitHub Copilot for Jira is growing into a real workflow automation layer. The five new features all target the same goal: making the Copilot cloud agent a configurable, policy-aware participant in Jira-driven delivery workflows. Custom agents let teams specify exactly which Copilot agent to use for different types of tickets. Custom field support means Copilot reads acceptance criteria and other structured fields, so implementations are more accurate from the start. Branch naming rule compliance is a big win for teams with naming conventions. Space-level instructions cut the overhead of configuring each session. And review notifications close the loop by posting a comment when Copilot opens a PR. Good demo: create a Jira ticket with acceptance criteria, trigger the Copilot agent, and show the resulting branch name, PR, and Jira notification.
-->
