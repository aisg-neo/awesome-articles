---
title: "Running a multi-region Zookeeper at Flipkart"
link: https://blog.flipkart.tech/running-a-multi-region-zookeeper-58e52cec44ff
topics:
  - Infrastructure
year: 2021
---

Flipkart describes running ZooKeeper across regions as a configuration store for active-active applications. It spreads voting nodes across at least three regions so no region holds a majority, and combines local discovery, observers, and read-only mode to balance latency, read scaling, and partition behavior. The article also covers session timing, write-volume limits, and network prioritization.
