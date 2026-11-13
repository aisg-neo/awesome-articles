---
title: "Atlassian's journey scaling low latency, multi-region services on AWS"
link: https://www.atlassian.com/blog/atlassian-engineering/aws-scaling-multi-region-low-latency-service
topics:
  - Infrastructure
  - Performance
year: 2019
---

Atlassian built a globally distributed context service to resolve tenant information for stateless services moving to AWS. It evolved from database-backed lookups toward local caches with invalidations, Caffeine caching, and a client sidecar to meet strict latency and resilience requirements. The team reported almost 100% reliability after introducing the sidecar.
