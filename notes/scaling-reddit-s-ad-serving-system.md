---
title: "Scaling Reddit's ad-serving system"
link: https://www.reddit.com/r/RedditEng/comments/1gzua17/scaling_ads_serving_find_and_eliminate_redundant/
topics:
  - Performance
year: 2024
---

Reddit redesigned its ad-serving pipeline to avoid repeating candidate sourcing, filtering, and heavy-model work for each ad slot while preserving slot-specific ranking and eligibility checks. New request APIs and a staged migration consolidated shared work across slots. Ad-shard QPS fell by about 50%, heavy-model inference QPS by 42%, and the changes saved millions in annual infrastructure costs.
