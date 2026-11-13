---
title: "Making a distributed priority queue disaster-ready"
link: https://engineering.fb.com/2022/01/18/production-engineering/foqs-disaster-ready/
topics:
  - Architecture
year: 2022
---

Meta needed its Facebook Ordered Queueing Service to remain usable when an entire region became unavailable. It evolved FOQS from isolated regional installations into a global architecture with routing and failover support. The migration finished in 2021 without downtime for internal clients.
