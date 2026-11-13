---
title: "How we built an eventually-consistent data model to predict Slack Connect invites"
link: https://slack.engineering/email-classification/
topics:
  - AI/ML
  - Architecture
year: 2021
---

Slack needed to determine whether an invited email address belonged to an internal colleague or an external collaborator without aggregating millions of users on each request. It maintains role-based email-domain counts in Vitess through asynchronous incremental updates and uses those counts alongside organization settings and inviter context. A healer periodically reconciles count drift so the system can recommend workspace invites or Slack Connect invites.
