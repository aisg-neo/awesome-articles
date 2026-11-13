---
title: "Building a resilient DNS client for web-scale infrastructure"
link: https://www.linkedin.com/blog/engineering/infrastructure/building-a-resilient-dns-client-for-web-scale-infrastructure
topics:
  - Infrastructure
year: 2025
---

LinkedIn built DCL to replace its legacy DNS client cache with a more resilient and observable client deployed across its host fleet. Fault detection, validation, query tracing, and staged rollout mechanisms help isolate upstream failures and diagnose application connectivity issues. DCL handles millions of queries per second, serves most requests in under a millisecond, and reduced infrastructure outage detection from hours to minutes.
