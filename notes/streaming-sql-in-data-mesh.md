---
title: "Streaming SQL in Data Mesh"
link: https://netflixtechblog.com/streaming-sql-in-data-mesh-0d83f5a00d08
topics:
  - Data Engineering
year: 2023
---

Netflix added a Flink SQL processor to Data Mesh because composing small processors imposed extra jobs and Kafka hops, while custom processors required low-level Flink expertise. Users can express transformations in one platform-managed SQL job with UDFs and lookup joins where needed. Interactive queries, real-time validation, schema inference, and platform guardrails shorten iteration and reduce pipeline overhead.
