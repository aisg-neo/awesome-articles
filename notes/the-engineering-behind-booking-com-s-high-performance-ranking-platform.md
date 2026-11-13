---
title: "The Engineering Behind Booking.com's High-Performance Ranking Platform"
link: https://medium.com/booking-com-development/the-engineering-behind-booking-coms-ranking-platform-a-system-overview-2fb222003ca6
topics:
  - Search
  - Performance
year: 2024
---

Booking.com describes the ranking platform that scores search candidates using user context, property features, and machine learning models. Dedicated ranking services collect cached features and split variable-sized requests into parallel inference calls, with separate ranking stages and continuous experimentation. Static fallback scores and isolated inference capacity help the system meet stringent latency requirements despite search-shard fanout and heavy models.
