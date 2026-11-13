---
title: "Netflix's TimeSeries Data Abstraction Layer"
link: https://netflixtechblog.com/introducing-netflix-timeseries-data-abstraction-layer-31552f6326f8
topics:
  - Databases
year: 2024
---

Netflix needed to store high-throughput immutable event histories at petabyte scale while retaining low-latency access. Its TimeSeries abstraction combines temporal partitioning, event bucketing, configurable consistency and retention, and storage backends such as Cassandra and Elasticsearch. The article describes handling bursty traffic and reports an 86% tail-latency reduction after moving to JDK 21 with ZGC.
