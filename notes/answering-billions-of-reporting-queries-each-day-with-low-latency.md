---
title: "Answering billions of reporting queries each day with low latency"
link: https://research.google/blog/answering-billions-of-reporting-queries-each-day-with-low-latency/
topics:
  - Databases
  - Performance
year: 2023
---

Google's Napa data warehouse must serve billions of advertising reporting queries despite highly skewed data and tight latency requirements. The team developed progressive partitioning, using a B-tree to split query work into increasingly balanced pieces without collecting enormous samples. The method makes parallelization decisions in milliseconds and outperformed sample-based partitioning.
