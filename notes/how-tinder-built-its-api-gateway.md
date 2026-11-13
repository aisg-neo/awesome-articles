---
title: "How Tinder built its API Gateway"
link: https://medium.com/tinder/how-we-built-the-tinder-api-gateway-831c6ca5ceca
topics:
  - Architecture
  - Infrastructure
year: 2022
---

Tinder needed consistent security and session handling across public APIs backed by more than 500 microservices. It built Tinder API Gateway, a configurable framework with centralized filters, Envoy-based service discovery, and request and response transformations. Application teams deploy independently scalable gateway instances by defining routes and application-specific configuration.
