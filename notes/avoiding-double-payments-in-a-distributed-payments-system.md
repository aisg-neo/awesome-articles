---
title: "Avoiding Double Payments in a Distributed Payments System"
link: https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb
topics:
  - Payments
  - Architecture
year: 2019
---

Airbnb built Orpheus, a reusable idempotency library, to prevent duplicate charges and payouts when distributed payment requests fail or are retried. The library separates database work from network calls, stores idempotency keys and responses on sharded primary databases, and uses expiring leases and retryable-error classifications to support write repair. Since launch, Airbnb reports five-nines payment consistency while its annual payment volume doubled.
