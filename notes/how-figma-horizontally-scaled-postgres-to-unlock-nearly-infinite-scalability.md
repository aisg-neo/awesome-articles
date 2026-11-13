---
title: "How Figma horizontally scaled Postgres to unlock nearly infinite scalability"
link: https://www.figma.com/blog/how-figmas-databases-team-lived-to-tell-the-scale/
topics:
  - Databases
year: 2024
---

Figma’s vertically partitioned Postgres databases still faced limits when individual tables grew to billions of rows and several terabytes. The team built horizontal sharding on its existing RDS Postgres infrastructure, tailoring the supported operations and colocation strategy to Figma’s application. The approach supports incremental rollout and rollback while avoiding a migration to an entirely new database system.
