---
title: "Lessons learned from sharding Postgres at Notion"
link: https://www.notion.com/blog/sharding-postgres-at-notion
topics:
  - Databases
year: 2021
---

Notion's PostgreSQL monolith hit growth limits, including stalled VACUUM work and the risk of transaction-ID wraparound. The team migrated to a horizontally partitioned database fleet after months of sharding design and migration preparation. The final cutover required a five-minute scheduled maintenance window and improved application performance.
