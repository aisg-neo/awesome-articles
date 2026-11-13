---
title: "Real-time Fraud Detection with Yoda and ClickHouse"
link: https://tech.instacart.com/real-time-fraud-detection-with-yoda-and-clickhouse-bd08e9dbe3f4
topics:
  - Security
  - Data Engineering
year: 2024
---

Instacart built Yoda so fraud analysts could define rules that evaluate fresh data and trigger actions such as transaction blocks or account reviews. PostgreSQL CDC and application events flow through Kafka and configurable Flink jobs into ClickHouse, which supplies low-latency aggregate features. The platform combines these features with machine learning and feature-store signals to make fraud decisions in fractions of a second.
