---
title: "Caching JQL search in Jira Cloud"
link: https://www.atlassian.com/blog/atlassian-engineering/reducing-jql-database-load-with-caches
topics:
  - Caching
  - Databases
year: 2021
---

Atlassian introduced caching for repetitive JQL searches as some Jira Cloud databases reached the largest available RDS instance size. The cache uses issue-change events and query matching to invalidate affected results while respecting existing consistency expectations. The article reports database-load reductions of up to 76% per user.
