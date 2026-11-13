---
title: "HTTP/2 in infrastructure: Ambry network stack refactoring"
link: https://www.linkedin.com/blog/engineering/optimization/http-2-in-infrastructure-ambry-network-stack-refactoring
topics:
  - Infrastructure
  - Performance
year: 2021
---

LinkedIn's Ambry object store encountered connection and network bottlenecks as its storage fleet grew and SSL became necessary. The team replaced the custom TCP networking stack between frontends and storage nodes with a Netty-based HTTP/2 implementation. HTTP/2 multiplexing addresses the need for large connection pools as the cluster scales.
