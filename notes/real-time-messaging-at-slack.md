---
title: "Real-time Messaging at Slack"
link: https://slack.engineering/real-time-messaging/
topics:
  - Messaging
year: 2023
---

Slack describes how its real-time messaging system distributes messages and presence updates to connected clients worldwide. Consistent hashing assigns channels to channel servers, while regional gateway servers maintain WebSocket connections and subscriptions. Its ring managers can replace an unhealthy channel server in under 20 seconds.
