---
title: "Stripe's payments APIs: The first 10 years"
link: https://stripe.com/blog/payment-api-design
topics:
  - Architecture
  - Payments
year: 2020
---

Stripe traces how its payment APIs evolved from simple card Charges and Tokens to abstractions supporting asynchronous payments and additional customer authentication. Adding payment methods exposed limits in models designed around immediate card payments and accumulated confusing states and responsibilities. PaymentIntents and PaymentMethods separate the payment lifecycle from payment credentials to support these more complex flows.
