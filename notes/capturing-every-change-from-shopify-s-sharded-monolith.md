---
title: "Capturing Every Change From Shopify's Sharded Monolith"
link: https://shopify.engineering/capturing-every-change-shopify-sharded-monolith
topics:
  - Data Engineering
  - Architecture
year: 2021
---

Shopify replaced query-based change data capture with an append-only log-based system using Kafka Connect and Debezium. The design captures changes across its sharded monolith for both internal data infrastructure and merchant-facing analytics. One consumer reduced data freshness delays from a day to an hour by modeling the CDC stream with Beam.
