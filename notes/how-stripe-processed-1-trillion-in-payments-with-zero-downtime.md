---
title: "How Stripe Processed $1 Trillion in Payments with Zero Downtime"
link: https://stripe.com/blog/how-stripes-document-databases-supported-99.999-uptime-with-zero-downtime-data-migrations
topics:
  - Databases
  - Payments
year: 2023
---

Stripe needed to move financial data between MongoDB-backed DocDB shards while keeping APIs available and data consistent. Its Data Movement Platform supports transparent shard splitting, consolidation, database upgrades, and tenant isolation without downtime. DocDB serves more than five million queries per second across over 2,000 shards; Stripe reports 99.999% uptime while processing $1 trillion in payments in 2023.
