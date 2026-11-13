---
title: "Powering real-time data analytics with Druid at Twitter"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2022/powering-real-time-data-analytics-with-druid-at-twitter
topics:
  - Data Engineering
year: 2022
---

Twitter operates Druid as a shared real-time analytics platform across on-premises infrastructure and Google Cloud, with its largest cluster spanning more than 5,000 nodes and petabytes of data. To simplify onboarding from systems such as Kafka, HDFS, BigQuery, and GCS, it built a unified ingestion service and UI. Users can configure ingestion, backfills, and reindexing without writing pipeline code, then run sub-second interactive analytics.
