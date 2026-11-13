---
title: "How eBay Loads and Updates Over Ten-Billion-Vertex Graphs"
link: https://innovation.ebayinc.com/stories/graphload-a-framework-to-load-and-update-over-ten-billion-vertex-graphs-with-performance-and-consistency/
topics:
  - Databases
  - Performance
year: 2021
---

eBay built GraphLoad to ingest batch files and Kafka streams into NuGraph while continuing to serve real-time graph queries. Parallel loaders and distributed transactions provide exactly-once loading and updating guarantees across failures. The production framework has maintained a graph with more than 15 billion vertices and 20 billion edges using hundreds of loader instances.
