---
title: "How we built a general purpose key value store for Facebook with ZippyDB"
link: https://engineering.fb.com/2021/08/06/core-infra/zippydb/
topics:
  - Databases
year: 2021
---

Facebook built ZippyDB to keep product teams from independently implementing replication, fault tolerance, and capacity management around RocksDB. The managed key-value store combines RocksDB with the Data Shuttle replication library, shard management, and distributed configuration. Applications can choose consistency and durability levels and use conditional writes and serializable transactions within a shard.
