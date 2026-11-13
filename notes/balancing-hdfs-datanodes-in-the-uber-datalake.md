---
title: "Balancing HDFS DataNodes in the Uber DataLake"
link: https://www.uber.com/en-IN/blog/balancing-hdfs-datanodes-in-the-uber-datalake/
topics:
  - Data Engineering
year: 2024
---

Uber's HDFS clusters developed uneven disk utilization as heavy writes and node decommissioning overwhelmed the standard balancer. The team changed the balancing algorithm to redistribute data more effectively across DataNodes. The changes increased balancing throughput by more than three times and allowed a highlighted cluster to reach roughly 83% utilization.
