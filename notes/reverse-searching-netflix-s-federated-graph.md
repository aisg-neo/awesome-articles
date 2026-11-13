---
title: "Reverse Searching Netflix's Federated Graph"
link: https://netflixtechblog.com/reverse-searching-netflixs-federated-graph-222ac5d23576
topics:
  - Architecture
  - Search
year: 2024
---

Netflix added reverse search to identify which saved queries match a changed document, enabling targeted notifications without repeatedly running every search across its federated graph. Saved Graph Search filters are translated into Elasticsearch queries and indexed with percolator fields. The same mechanism also supports rule-based movie classification and workflow assignment.
