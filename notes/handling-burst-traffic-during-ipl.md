---
title: "Handling Burst Traffic During IPL"
link: https://engineering.razorpay.com/ipl-razorpays-second-innings-ae7c86b0894c
topics:
  - Performance
  - Infrastructure
year: 2021
---

Razorpay’s systems suffered outages during IPL 2019 when short transaction bursts and slow bank responses exhausted capacity and database connections. The team added ProxySQL connection pooling, throttling, automated bank routing, and infrastructure improvements. Automated routing improved payment success rates by 60% during bursts, and the 45-day IPL 2020 season ran without degradation or downtime.
