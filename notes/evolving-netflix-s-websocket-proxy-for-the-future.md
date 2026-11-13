---
title: "Evolving Netflix's WebSocket proxy for the future"
link: https://netflixtechblog.com/pushy-to-the-limit-evolving-netflixs-websocket-proxy-for-the-future-b468bc0ff658
topics:
  - Messaging
  - Infrastructure
year: 2024
---

Netflix evolved Pushy from best-effort notifications into a WebSocket platform supporting hundreds of millions of concurrent connections and hundreds of thousands of messages per second. The article describes reliability work, device-to-device messaging, connection handling, and caching. Pushy maintained 99.999% message delivery reliability, and its device-to-device path achieved median latency below one millisecond and p99 below four milliseconds.
