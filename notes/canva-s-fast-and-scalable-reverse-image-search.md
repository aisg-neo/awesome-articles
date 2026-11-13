---
title: "Canva's fast and scalable reverse image search"
link: https://www.canva.dev/blog/engineering/simple-fast-and-scalable-reverse-image-search-using-perceptual-hashes-and-dynamodb/
topics:
  - Search
  - Databases
year: 2022
---

Canva built reverse image search using perceptual hashes and DynamoDB to detect visually similar media for moderation and deduplication. The design splits hashes into searchable pieces and verifies candidates by hash distance. Refinements reduced candidate rows for problematic queries from hundreds of thousands to tens.
