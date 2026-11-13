---
title: "How Canva collects 25 billion events per day"
link: https://www.canva.dev/blog/engineering/product-analytics-event-collection/
topics:
  - Data Engineering
year: 2024
---

Canva built an analytics pipeline that validates, enriches, and distributes 25 billion product events per day using typed Protobuf schemas and generated tooling. Replacing SQS and SNS transport with Kinesis reduced that transport cost twentyfold, while batched zstd compression saved an estimated $600,000 annually. SQS remains an overflow path to keep collection endpoint P99 latency below 20 ms.
