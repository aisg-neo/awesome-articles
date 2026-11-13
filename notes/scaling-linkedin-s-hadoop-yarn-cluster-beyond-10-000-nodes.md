---
title: "Scaling LinkedIn's Hadoop YARN cluster beyond 10,000 nodes"
link: https://www.linkedin.com/blog/engineering/open-source/scaling-linkedin-s-hadoop-yarn-cluster-beyond-10-000-nodes
topics:
  - Infrastructure
  - Data Engineering
year: 2021
---

LinkedIn encountered scheduler slowdowns and unfair queue allocation as its Hadoop YARN cluster approached 10,000 nodes. It optimized partition-aware scheduling, built DynoYARN to replay workloads and forecast limits, and introduced Robin to route jobs across smaller physical clusters. One scheduler optimization improved worst-case throughput ninefold, while Robin provided a path beyond a single resource manager's scaling limit.
