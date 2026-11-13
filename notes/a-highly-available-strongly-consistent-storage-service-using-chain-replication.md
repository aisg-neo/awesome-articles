---
title: "A highly available, strongly consistent storage service using chain replication"
link: https://engineering.fb.com/2022/05/04/data-infrastructure/delta/
topics:
  - Databases
  - Architecture
year: 2022
---

Meta built Delta to store critical build and distribution artifacts with few dependencies so infrastructure could be bootstrapped after a disaster. The object store uses chain replication, directing writes through a chain of replicas and reads to its tail to provide strong consistency. Its design prioritizes reliability and recovery over storage efficiency and latency.
