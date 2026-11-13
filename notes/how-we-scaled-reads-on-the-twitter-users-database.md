---
title: "How we scaled Reads On the Twitter Users Database"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2023/how-we-scaled-reads-on-the-twitter-users-database
topics:
  - Databases
  - Performance
year: 2023
---

Twitter's User Reservation System needed to serve millions of reads per second while meeting latency, availability, and cross-datacenter consistency requirements. The team adopted Vitess over MySQL and moved stateless Vtgate proxies off database hosts onto independently scaled Mesos instances. It also contributed TLS changes to support encrypted connections without downtime during rollout.
