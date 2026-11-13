---
title: "Running Geo Queries At Scale"
link: https://bytes.swiggy.com/running-geo-queries-at-scale-adea70f5af45
topics:
  - Databases
  - Performance
year: 2020
---

Swiggy built a shared geospatial platform for proximity, polygon containment, and service-area queries over large datasets. It chose Tile38 and created Kafka-backed masterless clones to prioritize availability, with S3 snapshots and event replay supporting startup recovery. The system serves read-heavy geospatial use cases without depending on a single leader.
