---
title: "How Discord Creates Insights from Trillions of Data Points"
link: https://discord.com/blog/how-discord-creates-insights-from-trillions-of-data-points
topics:
  - Data Engineering
year: 2021
---

Discord’s small Data Platform team needed a self-service way to transform trillions of raw records into dependable BigQuery tables. It built Derived, a declarative system that manages table dependencies, incremental processing, rebuilds, and data governance. The system maintains a warehouse exceeding 30 petabytes while reducing the need for users to manage transformation orchestration themselves.
