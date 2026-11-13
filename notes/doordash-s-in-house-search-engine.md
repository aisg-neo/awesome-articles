---
title: "DoorDash's in-house search engine"
link: https://careersatdoordash.com/blog/introducing-doordashs-in-house-search-engine/
topics:
  - Search
year: 2024
---

DoorDash replaced Elasticsearch with a Lucene-based search engine as document replication and complex item-store relationships limited efficient scaling. The new system separates indexing from search, replicates segments, and supports related document types. After migration, p99.9 latency fell by 50% and hardware costs by 75%.
