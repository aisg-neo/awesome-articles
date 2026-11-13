---
title: "Creating the Notion API"
link: https://www.notion.com/blog/creating-the-notion-api
topics:
  - Architecture
year: 2022
---

Notion describes the API design choices needed to expose flexible blocks, rich text, nested content, and database properties through a consistent REST interface. The team chose structured representations and pagination mechanisms that fit varied user content. For expensive rollups, cursors can carry accumulated partial results so calculations proceed across pages of related records.
