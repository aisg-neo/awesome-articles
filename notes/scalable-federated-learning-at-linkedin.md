---
title: "Scalable federated learning at LinkedIn"
link: https://www.linkedin.com/blog/engineering/machine-learning/scalable-federated-learning-at-linkedin
topics:
  - AI/ML
year: 2025
---

LinkedIn built a federated learning framework to train shared models while keeping customer data logically isolated across roughly 23,000 silos. A central server aggregates models and schedules tasks for independent gRPC executors, each processing one tenant's data at a time. The framework supports synchronous and asynchronous training and extensions such as differential privacy.
