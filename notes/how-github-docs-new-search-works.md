---
title: "How GitHub Docs' new search works"
link: https://github.blog/engineering/architecture-optimization/how-github-docs-new-search-works/
topics:
  - Search
year: 2023
---

GitHub Docs outgrew an in-memory search index that duplicated searchable content across languages and product versions. The team moved search to Elasticsearch and combined differently boosted phrase, exact, and stemmed matches into a single request. Search execution on the Elasticsearch server takes about 20 ms, excluding network time.
