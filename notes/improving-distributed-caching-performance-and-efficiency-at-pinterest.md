---
title: "Improving Distributed Caching Performance and Efficiency at Pinterest"
link: https://medium.com/pinterest-engineering/improving-distributed-caching-performance-and-efficiency-at-pinterest-92484b5fe39b
topics:
  - Caching
year: 2022
---

Pinterest sought performance and cost improvements across a memcached fleet serving about 180 million requests per second. It used synthetic benchmarks and shadow production traffic to evaluate hardware choices, compute tuning, and network changes. Improvements included TCP Fast Open, larger connection backlogs, and TLS session resumption to reduce connection overhead and deployment-related errors.
