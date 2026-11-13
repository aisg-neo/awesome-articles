---
title: "How one of Atlassian's critical services consistently gets above 99.9999% of availability"
link: https://www.atlassian.com/blog/atlassian-engineering/atlassian-critical-services-above-six-nines-of-availability
topics:
  - Infrastructure
year: 2022
---

Atlassian evolved its Tenant Context Service client sidecars into resilient node-local caches to keep tenant metadata available during backend and regional failures. The sidecars maintain long-lived caches, monitor multiple parent services, and isolate concurrent fallback requests by region. They serve up to 32 billion requests daily with cache hit rates above 99.5%, while the service consistently exceeds 99.9999% availability.
