---
title: "Razorpay's Authentication Revamp"
link: https://engineering.razorpay.com/razorpays-authentication-revamp-turbocharging-performance-b8bb9d750fe8
topics:
  - Performance
  - Security
year: 2023
---

Razorpay's decomposed services still routed requests through a monolith for authentication and authorization, adding up to 60% of overall latency. The team moved those checks into configurable API gateway plugins and passed verified identity to services in an internal JWT called Passport. Shadow comparisons and synchronized data supported the migration, which reduced latency by 50%.
