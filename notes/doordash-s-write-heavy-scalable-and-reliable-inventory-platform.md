---
title: "DoorDash's write-heavy scalable and reliable inventory platform"
link: https://careersatdoordash.com/blog/how-doordash-designed-a-successful-write-heavy-scalable-and-reliable-inventory-platform/
topics:
  - Architecture
  - Databases
year: 2023
---

DoorDash built an asynchronous inventory platform as convenience and grocery catalogs expanded to tens of thousands of items per store and more than a billion daily item refreshes. Cadence workflows validate and enrich inputs, calculate prices, predict availability, and apply guardrails before publishing updates. The article describes CockroachDB storage choices, scaling pitfalls, and item-level observability used to keep ingestion reliable.
