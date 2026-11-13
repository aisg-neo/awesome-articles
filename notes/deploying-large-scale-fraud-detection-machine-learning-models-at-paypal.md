---
title: "Deploying Large-scale Fraud Detection Machine Learning Models at PayPal"
link: https://medium.com/paypal-tech/machine-learning-model-ci-cd-and-shadow-platform-8c4f44998c78
topics:
  - AI/ML
  - Security
year: 2021
---

PayPal built Quokka, a self-service model CI/CD and shadow-testing platform, to replace scheduled releases and manual deployment steps for fraud-detection models. It runs models against sampled live traffic and production data without affecting risk decisions, allowing teams to check execution latency and score distributions before release. PayPal reports an 80% reduction in model development and deployment time, 3x higher user productivity, and no system rollbacks caused by model execution failures.
