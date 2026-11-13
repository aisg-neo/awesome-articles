---
title: "Building Netflix's Distributed Tracing Infrastructure"
link: https://netflixtechblog.com/building-netflixs-distributed-tracing-infrastructure-bb856c319304
topics:
  - Observability
year: 2020
---

Netflix built distributed tracing infrastructure to help engineers investigate streaming failures across many services. The article describes collecting, sampling, storing, and querying traces for its Edgar troubleshooting experience and other engineering uses. Tail-based sampling reduced trace data volume by 20% without affecting the user experience.
