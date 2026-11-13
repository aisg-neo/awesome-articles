---
title: "Using Server Sent Events to Simplify Real-time Streaming at Scale"
link: https://shopify.engineering/server-sent-events-data-streaming
topics:
  - Architecture
  - Data Engineering
year: 2022
---

Shopify replaced a polling-based delivery path for its Black Friday Cyber Monday Live Map with Server-Sent Events to reduce complexity and latency. A Go service subscribes to Kafka and immediately broadcasts updates to browser connections, with NGINX load balancing supporting horizontal scaling. The article describes implementation details and reports 100% Live Map uptime during the event.
