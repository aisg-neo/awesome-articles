---
title: "How Pinterest scaled the size of it's ad corpus by 60x"
link: https://medium.com/pinterest-engineering/how-we-scaled-the-size-of-pinterests-ad-corpus-by-60x-d6d5bfa6bf16
topics:
  - Performance
year: 2021
---

Pinterest moved its ads index from service memory into an external key-value store and consolidated nine shards into a single stateless ads-mixer service to support a 60x larger ad corpus. Go heap optimizations reduced heap objects from about 280 million to 60 million, improving tail latency by nearly 10% and success rate by 1%. Parallel index fetching, a local cache that reduced key-value-store traffic by about 94%, and Kafka-based updates controlled latency and improved data freshness from hours to minutes.
