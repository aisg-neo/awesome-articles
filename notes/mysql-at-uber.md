---
title: "MySQL At Uber"
link: https://www.uber.com/en-IN/blog/mysql-at-uber/
topics:
  - Databases
year: 2025
---

Uber reworked the control plane for more than 2,300 MySQL clusters to improve availability from 99.9% to 99.99%. The architecture uses desired-state management with Odin, fault-tolerant Cadence workflows, and an external controller that observes clusters and reacts to rule violations. The redesign addresses coupling between database failures and infrastructure operations that had affected failover and node-management workflows.
