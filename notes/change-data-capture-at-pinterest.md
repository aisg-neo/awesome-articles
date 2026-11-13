---
title: "Change Data Capture at Pinterest"
link: https://medium.com/pinterest-engineering/change-data-capture-at-pinterest-7e4c357ac527
topics:
  - Data Engineering
year: 2024
---

Pinterest replaced isolated change-data-capture implementations with a generic Debezium-based system for its distributed online databases. A separate control plane reconciles shard topology and connector configuration, while distributed Kafka Connect workers capture each shard's changes into Kafka. Connector and rebalance fixes reduced failover recovery from more than two hours to under a minute and stabilized a 3,000-task deployment at roughly 45% CPU instead of 99%.
