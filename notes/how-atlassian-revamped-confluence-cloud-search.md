---
title: "How Atlassian Revamped Confluence Cloud Search"
link: https://www.atlassian.com/blog/atlassian-engineering/revamping-confluence-cloud-search
topics:
  - Search
year: 2021
---

Confluence Cloud’s self-managed Elasticsearch search platform had operational problems, expensive permission checks, and limited regional failover. Atlassian moved to a cross-product search platform using AWS-managed Elasticsearch, streaming indexing, tenant-aware sharding, and indexed permission expressions. Replicating indexes across compliant regions enabled automatic failover without downtime.
