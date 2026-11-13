---
title: "Scaling a distributed priority queue at Meta"
link: https://engineering.fb.com/2021/02/22/production-engineering/foqs-scaling-a-distributed-priority-queue/
topics:
  - Architecture
year: 2021
---

Facebook Ordered Queueing Service provides a persistent distributed priority queue for asynchronous work across hundreds of internal use cases. Built on sharded MySQL, it supports priorities, delayed delivery, acknowledgments, and retries through a multitenant API. The article explains its data model and shard management for scaling workloads such as notifications, video encoding, and translation.
