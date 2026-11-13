---
title: "RoCE networks for distributed AI training at scale"
link: https://engineering.fb.com/2024/08/05/data-center-engineering/roce-network-distributed-ai-training-at-scale/
topics:
  - Infrastructure
  - AI/ML
year: 2024
---

Meta describes the RoCEv2 Ethernet networks it built for distributed GPU training, where large jobs require tightly coordinated communication across thousands of GPUs. It separates the training backend from frontend traffic and evolves Clos-based fabrics alongside topology-aware scheduling, routing, and congestion management. The networks support production workloads ranging from recommendation models to large generative AI models.
