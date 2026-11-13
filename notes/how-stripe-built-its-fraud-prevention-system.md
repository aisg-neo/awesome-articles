---
title: "How Stripe built its fraud prevention system"
link: https://stripe.com/blog/how-we-built-it-stripe-radar
topics:
  - Security
  - Payments
year: 2023
---

Stripe Radar must distinguish rare fraudulent payments from legitimate transactions within the payment authorization window. Stripe replaced its combined XGBoost and neural-network architecture with a multi-branch neural network, reducing training time by more than 85% to under two hours. Radar evaluates over 1,000 transaction characteristics in less than 100 milliseconds and incorrectly blocks 0.1% of legitimate payments.
