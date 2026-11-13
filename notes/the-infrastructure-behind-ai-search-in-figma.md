---
title: "The infrastructure behind AI search in Figma"
link: https://www.figma.com/blog/the-infrastructure-behind-ai-search-in-figma/
topics:
  - Search
  - AI/ML
year: 2024
---

Figma built semantic and visual search by generating CLIP embeddings for designs and components and indexing them for nearest-neighbor retrieval. The infrastructure must identify useful frames, render images, and update billions of embeddings while combining semantic matches with existing lexical results. Debouncing indexing to at most once every four hours reduced the amount of data requiring processing to 12%.
