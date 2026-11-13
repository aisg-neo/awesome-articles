---
title: "How Zomato predicts your order's Food preparation time"
link: https://blog.zomato.com/predicting-fpt-optimally
topics:
  - AI/ML
year: 2022
---

Zomato needed food-preparation estimates that accounted for variable kitchen conditions and the different costs of overestimating and underestimating readiness. It adjusted quantile-based loss functions and replaced separately trained networks with a shared model that predicts preparation time, delivery-partner waiting time, and pickup handoff time. The shared representation reduces the need to train and maintain multiple large models.
