---
title: "Scaling, rearchitecting, and decomposing Confluence Cloud"
link: https://www.atlassian.com/blog/atlassian-engineering/scaling-rearchitecting-and-decomposing-confluence-cloud
topics:
  - Architecture
year: 2020
---

Confluence Cloud's multi-tenant architecture hit database connection bottlenecks that caused errors and forced throttling of background workers. Atlassian began extracting expensive data domains into independently owned services, using DynamoDB where it fit the access patterns. The article describes regional deployment principles and the routing infrastructure used to migrate requests gradually from the monolith.
