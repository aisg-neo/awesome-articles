---
title: "Scaling our Apache Flink powered real-time ad event validation pipeline"
link: https://www.reddit.com/r/RedditEng/comments/1ijcfge/scaling_our_apache_flink_powered_realtime_ad/
topics:
  - Data Engineering
year: 2025
---

Reddit scaled its Flink-based Ad Events Validator by filtering unused payload fields, moving older event state into Cassandra, and improving recovery during Kubernetes maintenance. Field filtering reduced outgoing bytes by 90% and enabled CPU allocation reductions of 25% and memory reductions above 60%; tiered storage separately cut Flink memory allocation by more than a third at launch. Availability-zone-aware Cassandra routing and retries reduced network costs and p99 write latency by more than 50%, while lifecycle hooks and startup probes kept processing latency within the 15-minute target during full cluster maintenance.
