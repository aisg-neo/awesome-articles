---
title: "Airbnb's Data Framework for faster and more reliable read-heavy workloads"
link: https://medium.com/airbnb-engineering/riverbed-optimizing-data-access-at-airbnbs-scale-c37ecf6456d9
topics:
  - Data Engineering
  - Performance
year: 2023
---

Airbnb built Riverbed to simplify distributed materialized views for read-heavy queries that otherwise require complex joins and business logic across services. Its Lambda-style architecture combines Kafka-based change processing with Spark backfills and reconciliation, reusing GraphQL-defined queries and business logic while using document partitioning and version checks to coordinate writes. Riverbed processes 2.4 billion events and writes 350 million documents daily, powering more than 50 materialized views.
