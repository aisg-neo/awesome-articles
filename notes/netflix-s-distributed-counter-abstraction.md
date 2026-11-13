---
title: "Netflix's Distributed Counter Abstraction"
link: https://netflixtechblog.com/netflixs-distributed-counter-abstraction-8d0c45eb66b2
topics:
  - Architecture
year: 2024
---

Netflix needed distributed counters with different trade-offs between immediate availability, accuracy, durability, and cost. It built a configurable counter abstraction on its TimeSeries service, exposing add, read, and reset operations while hiding storage details. Users can select best-effort or eventually consistent counting, with idempotency support for applicable modes.
