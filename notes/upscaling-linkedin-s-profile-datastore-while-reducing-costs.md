---
title: "Upscaling LinkedIn's Profile Datastore While Reducing Costs"
link: https://www.linkedin.com/blog/engineering/data-management/upscaling-profile-datastore-while-reducing-costs
topics:
  - Databases
  - Cost Optimization
year: 2023
---

LinkedIn's profile datastore could no longer scale economically just by adding Espresso nodes as request volume grew. The team introduced Couchbase as a centralized read cache and addressed synchronization, schema conversion, and failure protection. The cache achieved a hit rate above 99%, reduced tail latency by more than 60%, and lowered annual serving costs by 10%.
