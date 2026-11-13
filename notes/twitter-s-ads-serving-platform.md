---
title: "Twitter's ads serving platform"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2021/sharding-simplification-and-twitters-ads-serving-platform
topics:
  - Architecture
year: 2021
---

Twitter built ShardLib to simplify communication among the sharded microservices created by decomposing its ad server. The library abstracts shard mappings and routing so services with different shard counts can communicate efficiently. It also enables dynamic resharding without redeploying client services.
