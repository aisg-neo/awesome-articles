---
title: "Uber's Highly Scalable and Distributed Shuffle as a Service"
link: https://www.uber.com/en-IN/blog/ubers-highly-scalable-and-distributed-shuffle-as-a-service/
topics:
  - Data Engineering
year: 2022
---

Uber built a Remote Shuffle Service to move Spark shuffle data off compute nodes, whose local disks created reliability, wear, and scaling problems. Mappers stream partitioned data to dedicated shuffle servers, and reducers fetch it from those servers, with replication providing fault tolerance. The design separates compute from shuffle storage and achieved service reliability above 99.99% after reliability improvements.
