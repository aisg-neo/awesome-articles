---
title: "Scaling Datastores at Slack with Vitess"
link: https://slack.engineering/scaling-datastores-at-slack-with-vitess/
topics:
  - Databases
year: 2020
---

Slack migrated from application-managed, workspace-sharded MySQL clusters to Vitess after large customers and cross-workspace features strained its original design. Vitess provided horizontal scaling and more flexible sharding while moving database routing out of the application. By publication, it served 99% of query load, with peak traffic of 2.3 million queries per second and p99 latency of 11 milliseconds.
