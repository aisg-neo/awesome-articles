---
title: "Introducing a Global Retrieval Ranking Model in the Ads Funnel"
link: https://www.reddit.com/r/RedditEng/comments/1d2wfsd/introducing_a_global_retrieval_ranking_model_in/
topics:
  - AI/ML
year: 2024
---

Reddit introduced a global retrieval ranker to reduce the number of ad candidates reaching expensive downstream ranking models. A multitask two-tower sparse network shares one user embedding across campaign objectives while producing objective-specific ad embeddings. The model is trained daily, with user embeddings cached for 24 hours and ad embeddings refreshed about every five minutes through a centralized embedding delivery service.
