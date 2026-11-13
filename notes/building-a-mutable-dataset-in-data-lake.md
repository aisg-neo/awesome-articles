---
title: "Building a mutable dataset in data lake"
link: https://www.linkedin.com/blog/engineering/data-management/opal-building-a-mutable-dataset-in-data-lake
topics:
  - Data Engineering
year: 2022
---

LinkedIn built Opal to reflect database inserts, updates, and deletes in an otherwise immutable data lake without repeatedly rewriting large snapshots. It stores columnar data with row identifiers and validity metadata, then filters rows at read time to expose current or historical snapshots. The system has supported low-latency use cases spanning petabytes since 2020.
