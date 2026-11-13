---
title: "Building a cost-effective logging platform for petabyte scale"
link: https://blog.zomato.com/building-a-cost-effective-logging-platform-using-clickhouse-for-petabyte-scale
topics:
  - Observability
  - Cost Optimization
year: 2023
---

Zomato replaced its increasingly costly and difficult-to-operate Elasticsearch logging setup with LogStore, built on ClickHouse. The design uses compression, sorting, and indexes to handle more than 50 TB of uncompressed logs per day while targeting subsecond queries and ingestion lag below a minute. The team estimated potential savings of more than a million dollars per year.
