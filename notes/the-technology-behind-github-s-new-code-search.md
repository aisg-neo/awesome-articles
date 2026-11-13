---
title: "The technology behind GitHub's new code search"
link: https://github.blog/engineering/architecture-optimization/the-technology-behind-githubs-new-code-search/
topics:
  - Search
year: 2023
---

GitHub built Blackbird, a Rust search engine, because general-purpose text engines could not meet its code-search features, indexing speed, and scale requirements. It uses code-oriented indexing and query execution to support punctuation and regular-expression searches while keeping repository results consistent at commit boundaries. At beta, the index covered almost 45 million repositories, 115 terabytes of code, and 15.5 billion documents.
