---
title: "Tuning Java for high-performance services"
link: https://www.linkedin.com/blog/engineering/infrastructure/java-heap-memory-and-garbage-collection-tuning-for-high-performance-services
topics:
  - Performance
year: 2024
---

LinkedIn's FollowFeed storage faced heap growth and garbage-collection stalls while maintaining a latency SLA below 50 milliseconds. Engineers reduced object overhead and duplicate strings, lowered allocation rates, and migrated to JDK 21 with ZGC. Heap use fell by 34%, p999 latency dropped by 55%, and capacity increased by 28%.
