---
title: "How Razorpay's Notification Service Handles Increasing Load"
link: https://engineering.razorpay.com/how-razorpays-notification-service-handles-increasing-load-f787623a490f
topics:
  - Messaging
  - Performance
year: 2022
---

Razorpay’s webhook notification workers could not keep scaling because additional pods increased database IOPS and degraded delivery latency. The team separated events into priority queues, added rate limits to contain noisy traffic, and buffered database writes through Kinesis for asynchronous processing. These changes gave it control over database write rates and reduced the impact of slow or misbehaving customer endpoints.
