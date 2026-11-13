---
title: "How a request flows — from a Slack's user perspective"
link: https://slack.engineering/traffic-101-packets-mostly-flow/
topics:
  - Architecture
year: 2023
---

Slack describes how billions of daily requests travel from users through DNS, globally distributed edge points of presence, and ingress load balancers to its internal services. The article follows both WebSocket and ordinary HTTP traffic, explaining how nearby edge regions reduce latency while connecting users to core services in AWS us-east-1.
