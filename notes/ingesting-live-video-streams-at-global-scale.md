---
title: "Ingesting Live Video Streams at Global Scale"
link: https://blog.twitch.tv/en/2022/04/26/ingesting-live-video-streams-at-global-scale/
topics:
  - Video/Media
  - Infrastructure
year: 2022
---

Twitch's static HAProxy ingest routing left origin capacity unevenly used and could not readily respond to demand changes or origin failures. It built Intelligest, combining media proxies at points of presence with a routing service that assigns streams to origins under compute and network constraints. The system enables global resource balancing rather than provisioning every origin for its own regional peak.
