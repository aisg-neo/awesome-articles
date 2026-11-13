---
title: "How DoorDash Applied Client-Side Caching to Improve Feature Store Performance by 70%"
link: https://careersatdoordash.com/blog/how-we-applied-client-side-caching/
topics:
  - Caching
  - AI/ML
year: 2022
---

DoorDash found that repeated ML feature lookups placed unnecessary load on its Redis-backed feature store. It added an in-process cache to the Sibyl Prediction Service and evaluated caching policies against recorded request patterns before a staged rollout. The deployed cache achieved a hit rate above 70%, reducing requests to Redis.
