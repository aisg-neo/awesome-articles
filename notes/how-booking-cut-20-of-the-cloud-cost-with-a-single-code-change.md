---
title: "How Booking Cut 20% of the Cloud Cost with a Single Code Change"
link: https://medium.com/booking-com-development/use-compression-luke-cut-20-of-the-cloud-cost-with-a-single-code-change-510d14d96891
topics:
  - Cost Optimization
year: 2025
---

Booking.com investigated high cross-availability-zone transfer costs in its Grafana Mimir metrics clusters and changed gRPC compression between distributors and ingesters. Zstandard initially caused excessive memory use, so the team adopted S2, which reduced traffic by about 45% compared with Snappy without increasing CPU or memory consumption. The change saved around 20% of the affected installations' total budget, and S2 support was included in Mimir 2.15.0.
