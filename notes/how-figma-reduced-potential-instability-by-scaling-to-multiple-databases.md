---
title: "How Figma reduced potential instability by scaling to multiple databases"
link: https://www.figma.com/blog/how-figma-scaled-to-multiple-databases/
topics:
  - Databases
year: 2023
---

Figma’s single Postgres database approached scaling limits as traffic roughly tripled each year. The team vertically partitioned groups of related tables into separate databases, using runtime query validators to identify safe boundaries. It built migration coordination that preserves availability and supports moving tables without maintenance windows.
