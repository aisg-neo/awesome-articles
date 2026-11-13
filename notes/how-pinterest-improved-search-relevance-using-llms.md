---
title: "How Pinterest improved Search Relevance using LLMs"
link: https://medium.com/pinterest-engineering/improving-pinterest-search-relevance-using-large-language-models-4cd938d4e892
topics:
  - AI/ML
  - Search
year: 2025
---

Pinterest improved search relevance by fine-tuning cross-encoder language models on human relevance judgments and distilling their predictions into a lightweight online model. The teacher labels billions of logged query–Pin examples, using enriched Pin text that includes image captions, board titles, and engagement-derived queries, while the student combines query, Pin, and interaction features. Online evaluation showed a 2.18% improvement in nDCG@20, and the article reports search fulfillment-rate gains above 1.5%.
