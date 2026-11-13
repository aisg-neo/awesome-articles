---
title: "Scaling Ads Pacing: from Singleton to Sharded"
link: https://www.reddit.com/r/RedditEng/comments/1e5mhs3/scaling_ads_pacing_from_singleton_to_sharded/
topics:
  - Architecture
year: 2024
---

Reddit replaced a singleton Spark pacing job after growing campaign data and controller complexity pushed it beyond the requirement to recalculate all campaign signals once per minute. The new Scala application runs as a Kubernetes StatefulSet, assigns advertiser-partitioned Kafka budget updates to stable shard ranges, and publishes pacing signals through Kafka. Four weeks of parallel comparisons showed approximately linear scaling, with pacing runtime falling to roughly 1/n for n shards.
