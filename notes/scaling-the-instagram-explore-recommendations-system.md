---
title: "Scaling the Instagram Explore recommendations system"
link: https://engineering.fb.com/2023/08/09/ml-applications/scaling-instagram-explore-recommendations-system/
topics:
  - AI/ML
  - Search
year: 2023
---

Instagram Explore must select relevant content from billions of items without ranking everything online. Its recommendation funnel combines retrieval, two ranking stages, and final reranking, using two-tower neural networks, cached representations, and offline precomputation. These techniques let the system use heavier models while meeting real-time serving requirements.
