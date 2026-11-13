---
title: "How we built Twitter's highly reliable ads pacing service"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2021/how-we-built-twitter-s-highly-reliable-ads-pacing-service
topics:
  - Architecture
year: 2021
---

Twitter moved ad-budget pacing out of its monolithic ad server to avoid repeating the same computation for every request. The standalone service recomputes campaign pacing every 10 seconds and uses sharding, redundant instances, and replication to remain available through failures. The team reports zero incidents during its first two years of operation.
