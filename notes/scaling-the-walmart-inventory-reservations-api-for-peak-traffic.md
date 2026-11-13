---
title: "Scaling the Walmart Inventory Reservations API for Peak Traffic"
link: https://medium.com/walmartglobaltech/scaling-the-walmart-inventory-reservations-api-for-peak-traffic-9ba37833ef9d
topics:
  - Performance
  - Architecture
year: 2022
---

Walmart's inventory reservation API encountered write conflicts when multiple instances updated the same Cosmos DB partition. The team split reservation requests by selling ID, routed each key to one pod and actor mailbox, and batched reservation events to overcome per-partition write limits. Stress tests exceeded 5,000 orders per second for an item, while snapshot caching reduced database reads.
