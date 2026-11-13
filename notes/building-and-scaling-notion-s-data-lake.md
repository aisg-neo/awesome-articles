---
title: "Building and scaling Notion's data lake"
link: https://www.notion.com/blog/building-and-scaling-notions-data-lake
topics:
  - Data Engineering
year: 2024
---

Notion's update-heavy Postgres data outgrew a warehouse pipeline built around hundreds of Fivetran connectors. The team built a data lake using Debezium, Kafka, Spark, and Hudi to support analytics and AI workloads while keeping load off production databases. Moving major datasets saved over a million dollars in 2022 and reduced ingestion delays from more than a day to minutes or hours.
