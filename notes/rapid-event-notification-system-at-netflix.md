---
title: "Rapid Event Notification System at Netflix"
link: https://netflixtechblog.com/rapid-event-notification-system-at-netflix-6deb1d2b57d1
topics:
  - Messaging
year: 2022
---

Netflix built Rapid Event Notification System (RENO) to keep member experiences consistent across devices as profiles, viewing activity, and recommendations change. It combines priority-specific event queues and processing clusters with push delivery and a Cassandra-backed polling path. At peak, RENO serves about 150,000 events per second, using deduplication, stale-event filtering, and device targeting to control traffic.
