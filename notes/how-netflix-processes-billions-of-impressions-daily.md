---
title: "How Netflix processes billions of impressions daily"
link: https://netflixtechblog.com/introducing-impressions-at-netflix-e2b67c88c9fb
topics:
  - Data Engineering
year: 2025
---

Netflix built an impressions pipeline to track which artwork and promotions each profile has seen for personalization, frequency capping, and analytics. A Flink job validates and enriches events into a source-of-truth dataset, with Kafka providing real-time access and Iceberg retaining history. The system processes roughly 1–1.5 million impression events per second globally.
