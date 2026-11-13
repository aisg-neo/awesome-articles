---
title: "Migrating Netflix to GraphQL Safely"
link: https://netflixtechblog.com/migrating-netflix-to-graphql-safely-8e1e4d4f1e72
topics:
  - Architecture
year: 2023
---

Netflix migrated its mobile apps from a monolithic Falcor API to federated GraphQL without downtime. It first introduced a GraphQL shim over Falcor, then moved API ownership to domain services. A/B tests, replay tests for idempotent requests, and sticky canaries validated correctness, performance, and customer impact during the transition.
