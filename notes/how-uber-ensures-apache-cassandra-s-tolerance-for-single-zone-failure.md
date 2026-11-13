---
title: "How Uber ensures Apache Cassandra's tolerance for single-zone failure"
link: https://www.uber.com/en-IN/blog/single-zone-failure-tolerance/
topics:
  - Databases
  - Infrastructure
year: 2024
---

Uber's Cassandra replicas could be concentrated in one availability zone because all nodes used the same rack value. The team changed replica placement to use zone-aware rack configuration and migrated its existing fleet while maintaining service availability. The resulting layout preserves a quorum when a single zone fails, and the conversion completed with zero downtime.
