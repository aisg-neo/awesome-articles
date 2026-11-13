---
title: "Walmart's Cassandra CDC Solution"
link: https://medium.com/walmartglobaltech/walmarts-cassandra-cdc-solution-6fc650031a3
topics:
  - Data Engineering
  - Databases
year: 2022
---

Walmart built a Cassandra CDC pipeline using Debezium and Kafka to bring transactional changes into its data platform. It modified the connector to process commit logs incrementally and used Redis-backed Bloom filters to deduplicate changes produced by Cassandra replication. A three-VM benchmark processed 623,000 records per minute, with p95 batch processing time of two seconds.
