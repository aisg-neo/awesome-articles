---
title: "Elasticsearch Optimizations at Lyft"
link: https://eng.lyft.com/elasticsearch-optimizations-at-lyft-b555dc020932
topics:
  - Search
  - Performance
year: 2021
---

Lyft optimized the Elasticsearch cluster behind feature-based customer cohorts after new workloads increased latency and AWS costs. Changes included omitting unnecessary source data, sorting scrolls by document order, and using routing to avoid searching every shard. Average scroll latency fell from over a second to 100–300 milliseconds, and lower cluster load allowed resource reductions.
