---
title: "How Slack traces the flow of notifications across systems"
link: https://slack.engineering/tracing-notifications/
topics:
  - Observability
  - Messaging
year: 2023
---

Slack’s notification issues were difficult to debug because events crossed many services with incompatible logs and formats. It standardized notification events and created a separate trace for each notification, linking it to the sender’s trace with span links. This enabled complete notification tracing without enormous message-level traces and reduced customer-experience ticket triage time by 30%.
