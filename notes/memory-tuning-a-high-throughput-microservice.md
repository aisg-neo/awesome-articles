---
title: "Memory Tuning a High Throughput Microservice"
link: https://blog.flipkart.tech/memory-tuning-a-high-throughput-microservice-ed57b3e60997
topics:
  - Performance
year: 2021
---

Flipkart merged two tightly coupled recommendation services but initially encountered increased garbage-collection overhead and a native-memory leak. It moved long-lived model data off the JVM heap and upgraded the JVM to fix a string-cleanup bug identified through Native Memory Tracking. The resulting recommendation system handles three times as much content on 20% less hardware.
