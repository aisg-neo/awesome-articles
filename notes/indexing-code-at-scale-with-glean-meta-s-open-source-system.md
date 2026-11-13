---
title: "Indexing code at scale with Glean - Meta's open source system"
link: https://engineering.fb.com/2024/12/19/developer-tools/glean-open-source-code-indexing/
topics:
  - Search
  - Infrastructure
year: 2024
---

Meta needed shared code indexes because indexing large codebases separately on each developer's machine was expensive and slow. Glean stores facts extracted from source code and exposes a query language that supports multiple programming languages and developer tools. Meta uses it for code browsing, search, documentation generation, and other code analysis.
