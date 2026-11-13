---
title: "How Zomato Handles 100 Million Daily Search Queries"
link: https://blog.zomato.com/explained-how-zomato-handles-100-million-daily-search-queries-part-three
topics:
  - Search
  - Performance
year: 2023
---

Zomato's growing Solr deployment encountered scaling bottlenecks and a leader-election incident that made a shard unavailable for reads. It adopted TLOG and PULL replicas so queries could continue during leader elections, accepting a delay in index freshness. It also seeds new replicas from S3 snapshots so hundreds can scale out without downloading the full index from the leader.
