---
title: "Migrating Millions of Concurrent Websockets to Envoy"
link: https://slack.engineering/migrating-millions-of-concurrent-websockets-to-envoy/
topics:
  - Infrastructure
  - Messaging
year: 2021
---

Slack's HAProxy-based WebSocket load balancers required reloads when backends changed, complicating management of millions of long-lived connections. The team migrated to Envoy to use dynamic endpoint configuration and improved handling of connection draining and restarts. The article describes the operational problems and migration process for the real-time messaging service.
