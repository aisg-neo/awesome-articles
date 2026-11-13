---
title: "Instacart's Item Availability Architecture: Solving for scale and consistency"
link: https://tech.instacart.com/instacarts-item-availability-architecture-solving-for-scale-and-consistency-f5661acb20a6
topics:
  - Architecture
year: 2023
---

Instacart needed real-time availability predictions to be fast to retrieve in bulk and consistent across shopping surfaces. It stores model scores near retrieval data and combines periodic full synchronization with lazy background refreshes triggered by search activity. Lazy refresh cut ingestion load by two-thirds, and a configuration-based framework supports parallel model experiments.
