---
title: "Canva's scalable and reliable content usage counting service"
link: https://www.canva.dev/blog/engineering/scaling-to-count-billions/
topics:
  - Architecture
  - Performance
year: 2024
---

Canva redesigned its content usage counting pipeline to calculate creator payments accurately as usage reached billions of events per month. After exploring OLTP-backed approaches, the team moved toward OLAP storage and an ELT pipeline that computes results end to end. This reduced intermediate state and operational complexity while making large aggregations practical.
