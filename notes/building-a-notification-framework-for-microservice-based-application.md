---
title: "Building a Notification Framework for Microservice-based Application"
link: https://medium.com/walmartglobaltech/building-a-notification-framework-for-microservice-based-application-6fe5ac9dfcee
topics:
  - Messaging
  - Architecture
year: 2021
---

Walmart built a reusable notification framework so microservices can notify individual users or groups and preserve notifications for users who are offline. A Java library stores notifications in Redis and publishes change messages, while an Express server pushes updates to browsers through Server-Sent Events. SharedWorkers let browser tabs share one connection to avoid SSE's six-connection limit, and REST endpoints record notification status changes.
