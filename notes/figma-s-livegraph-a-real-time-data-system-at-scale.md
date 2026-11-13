---
title: "Figma's LiveGraph: a real-time data system at scale"
link: https://www.figma.com/blog/livegraph-real-time-data-at-scale/
topics:
  - Architecture
  - Data Engineering
year: 2024
---

Figma redesigned LiveGraph as growing sessions, query volume, and database changes strained its real-time data system. The new architecture separates responsibilities and introduces shared caching and careful coordination between reads and invalidations. Correctness checks compare cache values with primary data and verify that results converge with the old query engine.
