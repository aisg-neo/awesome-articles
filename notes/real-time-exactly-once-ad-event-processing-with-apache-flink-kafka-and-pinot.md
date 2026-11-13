---
title: "Real-Time Exactly-Once Ad Event Processing with Apache Flink, Kafka, and Pinot"
link: https://www.uber.com/en-IN/blog/real-time-exactly-once-ad-event-processing/
topics:
  - Data Engineering
year: 2021
---

Uber built an ad-event pipeline that cleans, aggregates, and attributes impressions and clicks without losing or double-counting billable events. It combines Flink and Kafka transactions with record identifiers, Pinot upserts, and Hive deduplication to provide exactly-once results across two regions. The system processed hundreds of millions of events per week, with a two-minute checkpoint interval determining when processed data becomes visible.
