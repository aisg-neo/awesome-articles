---
title: "How we rebuilt the Walmart Autocomplete Backend"
link: https://medium.com/walmartglobaltech/how-we-rebuilt-the-walmart-autocomplete-backend-10efe71d624a
topics:
  - Search
  - Performance
year: 2021
---

Walmart's separate e-commerce and grocery autocomplete services used in-memory trees that limited capacity and complicated scaling and deployment. The team unified them into a cloud-hosted, multi-tenant service and precomputed the highest-ranked suggestions for each prefix in an external distributed cache. This turns online suggestion retrieval into key-value lookups and separates feature development from in-memory tree management.
