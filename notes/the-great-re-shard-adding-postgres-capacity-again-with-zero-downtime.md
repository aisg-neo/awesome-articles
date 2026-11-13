---
title: "The Great Re-shard: adding Postgres capacity (again) with zero downtime"
link: https://www.notion.com/blog/the-great-re-shard
topics:
  - Databases
year: 2023
---

Notion's 32 Postgres content shards were approaching CPU, IOPS, and connection limits as usage grew. The team tripled the fleet to 96 shards using logical replication, shadow-read comparisons, and a controlled traffic cutover without downtime. Peak CPU and IOPS utilization fell to around 20%, providing headroom for further growth.
