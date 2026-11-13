---
title: "Using Client-Side Map Data to Improve Real-Time Positioning"
link: https://eng.lyft.com/using-client-side-map-data-to-improve-real-time-positioning-a382585ac6e
topics:
  - Mobile
year: 2021
---

Lyft moved map data and map matching onto mobile devices to improve location freshness and keep localization working without cellular reception. It partitions maps into small S2 cells, downloads nearby cells through a CDN-backed service, and builds local road graphs in a shared C++ library. A SQLite cache reduced map-data downloads by an order of magnitude while limiting memory use.
