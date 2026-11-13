---
title: "How PayPal Uses Real-time Graph Database and Graph Analysis to Fight Fraud"
link: https://medium.com/paypal-tech/how-paypal-uses-real-time-graph-database-and-graph-analysis-to-fight-fraud-96a2b918619a
topics:
  - Security
  - Databases
year: 2021
---

PayPal built an integrated graph platform to detect linked and repeat fraud through real-time queries, interactive investigations, and offline graph analytics. Its homegrown real-time graph database uses an Aerospike-backed storage layer and Gremlin queries, with batch loading and event-driven updates that keep relationships fresh within seconds. The article describes a 100-millisecond SLA for real-time graph computation, an average 10-millisecond requirement for two-hop queries, and mirror-graph support for generating graph embeddings.
