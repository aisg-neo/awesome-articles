---
title: "eBay's real-time and performant index service for its large-scale, in-house database platform"
link: https://innovation.ebayinc.com/stories/ebays-global-secondary-indexes/
topics:
  - Databases
year: 2021
---

eBay built global secondary indexes for NuData so queries on non-primary-key fields do not have to visit every database shard. The service uses distributed index partitions, replicated with NuRaft, and the Jungle storage engine. It provides scalable indexing, fault tolerance, flexible resource management, and self-service schema tooling.
