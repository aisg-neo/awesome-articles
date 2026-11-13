---
title: "Breaking the Monolith at Twitch"
link: https://blog.twitch.tv/en/2022/04/12/breaking-the-monolith-at-twitch-part-2/
topics:
  - Architecture
year: 2022
---

Twitch describes its Wexit migration from a Rails monolith to Go microservices as shared deployments, slow builds, and unclear ownership became bottlenecks. An NGINX proxy and new API edge let teams migrate endpoints gradually while routing traffic between old and new implementations. The completed migration left teams operating services independently in isolated AWS accounts with common platform tooling.
