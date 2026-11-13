---
title: "Partitioning GitHub's relational databases to handle scale"
link: https://github.blog/engineering/infrastructure/partitioning-githubs-relational-databases-scale/
topics:
  - Databases
year: 2021
---

GitHub's main MySQL cluster became a scaling limit and a shared failure point for core features. The team introduced schema domains, SQL linters, and migration tooling to separate related tables and move them to independent database clusters. By 2021, load on the hosts holding the former mysql1 data had fallen by 50%, reducing database-related incidents.
