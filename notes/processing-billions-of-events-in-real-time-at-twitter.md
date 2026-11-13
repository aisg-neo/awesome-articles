---
title: "Processing billions of events in real time at Twitter"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2021/processing-billions-of-events-in-real-time-at-twitter-
topics:
  - Data Engineering
year: 2021
---

Twitter's interaction and engagement pipeline suffered streaming lag, possible event loss, and expensive batch processing at a company-wide scale of roughly 400 billion events per day. It moved from a batch-plus-streaming architecture to streaming pipelines using Kafka, Pub/Sub, Dataflow, and Bigtable. Event identifiers enable downstream deduplication while real-time aggregation replaces the batch reconciliation path.
