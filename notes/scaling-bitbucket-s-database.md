---
title: "Scaling Bitbucket's Database"
link: https://www.atlassian.com/blog/atlassian-engineering/scaling-bitbuckets-database
topics:
  - Databases
year: 2020
---

Bitbucket's PostgreSQL primary was overloaded while read replicas were underused, causing requests to wait for pooled connections. The team experimented with routing reads to replicas until a request writes, then using the primary, while tracking each user's WAL position in Redis to preserve read-after-write consistency across requests. Production traffic analysis suggested that 80% of primary traffic could move to replicas.
