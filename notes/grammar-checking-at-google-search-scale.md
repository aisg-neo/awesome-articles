---
title: "Grammar checking at Google Search scale"
link: https://research.google/blog/grammar-checking-at-google-search-scale/
topics:
  - AI/ML
  - Search
year: 2023
---

Google built EdiT5 to provide grammatical corrections at Search latency requirements without regenerating every token autoregressively. The model identifies text to retain or reorder and generates only the needed additions, while a grammaticality classifier controls when corrections appear. Training data refined by a large language model further improved correction quality.
