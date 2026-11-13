---
title: "How Atlassian Scaled and Enhanced Throughput in the Jira Export Service"
link: https://www.atlassian.com/blog/atlassian-engineering/boosting-performance-how-we-scaled-and-enhanced-throughput-in-the-jira-export-service
topics:
  - Performance
  - Architecture
year: 2025
---

Jira’s project export service extracted more than 100 entity types sequentially, making large exports take over 24 hours. Atlassian introduced a hybrid architecture that streams high-volume entities through Lithium while retaining HTTP batch APIs for low-volume interconnected entities. Parallel extraction and fixes for N+1 queries improved throughput, with one code optimization delivering an eightfold improvement at P90.
