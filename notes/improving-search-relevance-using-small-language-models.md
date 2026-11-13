---
title: "Improving search relevance using small language models"
link: https://bytes.swiggy.com/improving-search-relevance-in-hyperlocal-food-delivery-using-small-language-models-ecda2acc24e6
topics:
  - AI/ML
  - Search
year: 2024
---

Swiggy needed semantic retrieval for complex food queries that direct string matching could not resolve. It fine-tuned small sentence-embedding models first on historical query and order data, then on curated query-item pairs enriched with food-taxonomy knowledge. The two-stage all-mpnet-base-v2 model performed best on overall retrieval metrics in its evaluation, and the feature was being tested with a small cohort.
