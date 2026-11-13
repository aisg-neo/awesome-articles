---
title: "Horizontally scaling the Rails backend of Shop app with Vitess"
link: https://shopify.engineering/horizontally-scaling-the-rails-backend-of-shop-app-with-vitess
topics:
  - Databases
  - Performance
year: 2024
---

Shop’s growing Rails backend reached the limits of a single MySQL database, with schema migrations taking weeks and background jobs throttled by database load. Shopify migrated it to Vitess, sharding user-owned data by user_id and using query verifiers to eliminate incompatible queries and transactions. Schema migrations now take hours, and further growth can be handled by adding shards.
