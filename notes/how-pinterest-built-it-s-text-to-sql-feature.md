---
title: "How Pinterest built it's Text-to-SQL feature"
link: https://medium.com/pinterest-engineering/how-we-built-text-to-sql-at-pinterest-30bad30dabff
topics:
  - AI/ML
  - Data Engineering
year: 2024
---

Pinterest built a Text-to-SQL feature in Querybook to help analysts find relevant tables and turn analytical questions into SQL. The system supplies schema information to an LLM and adds retrieval over embeddings of table and query summaries in OpenSearch, followed by LLM table selection and user validation. In offline table-retrieval evaluation, adding table documentation to the embeddings increased the search hit rate from 40% to as high as 90%.
