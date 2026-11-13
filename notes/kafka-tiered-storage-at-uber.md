---
title: "Kafka Tiered Storage at Uber"
link: https://www.uber.com/en-IN/blog/kafka-tiered-storage/
topics:
  - Data Engineering
year: 2024
---

Kafka's dependence on broker-local storage forced Uber to add CPU and memory capacity merely to retain more historical data. Uber proposed tiered storage that keeps recent log segments locally and older segments in remote storage, with independent retention policies and unchanged client APIs. This separates storage growth from broker compute and reduces data movement during recovery and rebalancing.
