---
title: "How eBay Handles Real-Time Push Notifications at Scale"
link: https://innovation.ebayinc.com/stories/ebays-notification-streaming-platform-how-ebay-handles-real-time-push-notifications-at-scale/
topics:
  - Messaging
year: 2022
---

eBay’s notification platform needed to broadcast business events to 20,000 subscribers without blocking event processing on a single large database fetch. It divided subscriptions into timestamp-based windows, materialized the window boundaries, and processed subtasks concurrently. A Reactive Streams pipeline supplies asynchronous execution and backpressure within eBay’s existing microservice architecture.
