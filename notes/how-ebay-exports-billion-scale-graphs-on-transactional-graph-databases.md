---
title: "How ebay Exports Billion-Scale Graphs on Transactional Graph Databases"
link: https://innovation.ebayinc.com/stories/how-we-export-billion-scale-graphs-on-transactional-graph-databases/
topics:
  - Databases
year: 2023
---

eBay needed to export very large transactional graphs for analytics without disrupting online queries. It built a JanusGraph analytics plugin that scans a disaster-recovery copy of the FoundationDB backend in parallel and writes the graph to HDFS. Exporting its largest graph, with over 15 billion vertices and 24 billion edges, took three hours on a Spark cluster with 380 CPU cores and 3.7 TB of memory.
