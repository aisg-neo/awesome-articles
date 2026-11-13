---
title: "Swiggy's Text-to-SQL Solution"
link: https://bytes.swiggy.com/hermes-a-text-to-sql-solution-at-swiggy-81573fb4fb6e
topics:
  - AI/ML
  - Data Engineering
year: 2024
---

Swiggy built Hermes so employees can ask data questions in Slack, receive generated SQL, and run queries without relying entirely on analysts. After a basic LLM implementation struggled with company-specific schemas and complex questions, the team added a curated metadata knowledge base, retrieval, query validation, and correction retries. Snowflake authentication ensures queries execute only against data the requesting user can access.
