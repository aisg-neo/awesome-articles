---
title: "Dropbox's scalable, consistent, metadata caching solution"
link: https://dropbox.tech/infrastructure/meet-chrono-our-scalable-consistent-metadata-caching-solution
topics:
  - Caching
year: 2024
---

Dropbox built Chrono to absorb growing metadata read traffic while preserving the read-after-write guarantees expected by existing clients. It layers a consistent cache over the Panda key-value store and allows followers to serve linearizable reads. The article explains its write coordination protocol, correctness modeling, and operational challenges such as sharding and hot spots.
