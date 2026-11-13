---
title: "Razorpay's Real-Time Denormalized Data Streaming Platform"
link: https://engineering.razorpay.com/real-time-denormalized-data-streaming-platform-part-3-optimisations-and-monitoring-5f7a58d9d97
topics:
  - Data Engineering
year: 2023
---

Razorpay describes optimizations to its streaming platform for maintaining large, mutable denormalized tables from Kafka CDC events. The pipeline uses Spark micro-batches and a dependency graph to join changes into Delta tables on S3. Broadcast caching, Z-ordering, parallel processing of independent nodes, and revised handling of unmatched records reduce redundant work, while Grafana monitoring tracks latency, throughput, and source-to-target lag.
