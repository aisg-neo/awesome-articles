---
title: "Netflix's High-Throughput, Low-Latency Priority Queueing System"
link: https://netflixtechblog.com/timestone-netflixs-high-throughput-low-latency-priority-queueing-system-with-built-in-support-1abf249ba95f
topics:
  - Architecture
  - Performance
year: 2022
---

Netflix built Timestone because its media-encoding platform needed low-latency priority queues with linearizable assignment and support for work that must not run concurrently. The service dequeues messages by earliest deadline and provides exclusive queues that enforce nonparallel execution without consumer-side locking. It now also supports workflow orchestration and data-pipeline scheduling, handling millions of critical workflows daily.
