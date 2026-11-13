---
title: "How Uber Serves Over 40 Million Reads Per Second from Online Storage Using an Integrated Cache"
link: https://www.uber.com/en-IN/blog/how-uber-serves-over-40-million-reads-per-second-using-an-integrated-cache/
topics:
  - Caching
  - Performance
year: 2024
---

Uber's Docstore needed much higher read throughput without the cost and operational burden of scaling its disk-backed database fleet or having each service manage Redis separately. The team integrated caching into the database platform to centralize cache management and data consistency. The resulting system serves more than 40 million reads per second.
