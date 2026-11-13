---
title: "How Instacart Uses Embeddings to Improve Search Relevance"
link: https://tech.instacart.com/how-instacart-uses-embeddings-to-improve-search-relevance-e569839c3c36
topics:
  - AI/ML
  - Search
year: 2022
---

Instacart built ITEMS to improve search relevance when query-product pairs have sparse engagement data or misleading categorical matches. The transformer-based two-tower model embeds queries and products into a shared space and learns from converted searches with in-batch negatives. Independently computed embeddings allow the relevance signal to be used efficiently in retrieval and ranking.
