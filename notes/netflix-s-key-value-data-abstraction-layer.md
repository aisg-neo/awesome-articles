---
title: "Netflix's Key-Value Data Abstraction Layer"
link: https://netflixtechblog.com/introducing-netflixs-key-value-data-abstraction-layer-1ea8a0a11b30
topics:
  - Databases
year: 2024
---

Netflix's services had to handle database-specific consistency, pagination, data-modeling, and API changes across multiple distributed stores. It built a Key-Value Data Abstraction Layer around a two-level map model with tunable consistency and reusable access patterns. The service decouples application code from native database APIs and supports hundreds of use cases.
