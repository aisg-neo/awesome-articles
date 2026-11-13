---
title: "How Discord Reduced Websocket Traffic by 40%"
link: https://discord.com/blog/how-discord-reduced-websocket-traffic-by-40-percent
topics:
  - Performance
  - Messaging
year: 2024
---

Discord investigated how to reduce bandwidth on the gateway connections that deliver real-time client updates. It replaced zlib with tuned streaming zstandard compression and changed passive-session updates from full snapshots to deltas. Together, these changes reduced client gateway bandwidth by almost 40%.
