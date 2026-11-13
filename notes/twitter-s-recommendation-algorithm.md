---
title: "Twitter's Recommendation Algorithm"
link: https://blog.x.com/engineering/en_us/topics/open-source/2023/twitter-recommendation-algorithm
topics:
  - AI/ML
  - Search
year: 2023
---

Twitter describes how its For You timeline selects about 1,500 candidate tweets from in-network and out-of-network sources, ranks them with a roughly 48-million-parameter neural network, and applies visibility, diversity, and feedback filters. Home Mixer combines the results with ads and other content, drawing on social-graph traversal and embedding systems such as SimClusters. The pipeline runs about five billion times daily, completing in under 1.5 seconds on average while consuming 220 seconds of CPU time per execution.
