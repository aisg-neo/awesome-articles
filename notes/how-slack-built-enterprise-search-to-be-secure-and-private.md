---
title: "How Slack built enterprise search to be secure and private"
link: https://slack.engineering/how-we-built-enterprise-search-to-be-secure-and-private/
topics:
  - Search
  - Security
year: 2025
---

Slack built enterprise search to retrieve permissioned external content without storing a separate copy of source data in its database. It uses real-time partner APIs and user-authorized OAuth access, then supplies relevant results to RAG models hosted inside Slack’s trust boundary. Admins and users control source access, and search answers are displayed without being retained in the database.
