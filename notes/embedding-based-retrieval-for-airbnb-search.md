---
title: "Embedding-Based Retrieval for Airbnb Search"
link: https://medium.com/airbnb-engineering/embedding-based-retrieval-for-airbnb-search-aabebfc85839
topics:
  - Search
  - AI/ML
year: 2025
---

Airbnb built an embedding-based retrieval system to narrow large pools of eligible homes before more expensive search-ranking models run. It trains a two-tower model using booked homes and unbooked homes from users' search journeys, precomputes listing embeddings daily, and uses inverted-file clustering to retrieve candidates within existing search filters. The system launched in Search and Email Marketing and produced a statistically significant increase in bookings, comparable to some of Airbnb's largest search-ranking ML improvements over the preceding two years.
