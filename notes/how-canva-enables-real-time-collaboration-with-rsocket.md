---
title: "How Canva enables real-time collaboration with RSocket"
link: https://www.canva.dev/blog/engineering/enabling-real-time-collaboration-with-rsocket/
topics:
  - Messaging
  - Architecture
year: 2021
---

Canva needed bidirectional real-time APIs for collaboration without opening a separate WebSocket connection for every backend service. It built a gateway using RSocket to multiplex independent streams over a single WebSocket connection. Per-stream backpressure prevents an unavailable backend from creating a backlog that disrupts other services sharing the gateway.
