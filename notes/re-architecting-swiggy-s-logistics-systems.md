---
title: "Re-Architecting Swiggy's logistics systems"
link: https://bytes.swiggy.com/re-architecting-swiggys-logistics-systems-ddf301a29fa0
topics:
  - Architecture
year: 2021
---

Swiggy rebuilt its delivery monolith because its food-specific model, vertically scaled databases, and low test coverage made new logistics services difficult to support. The new event-driven platform models tasks, jobs, job legs, and trips with logical isolation for multiple service lines. It supports merged trips and multi-leg deliveries and enabled offerings such as Genie and Instamart.
