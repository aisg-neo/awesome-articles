---
title: "The Reddit Media Metadata Store"
link: https://www.reddit.com/r/RedditEng/comments/1avlywv/the_reddit_media_metadata_store/
topics:
  - Video/Media
  - Databases
year: 2023
---

Reddit consolidated scattered post-media metadata into an AWS Aurora PostgreSQL service using dual writes, backfills, dual reads, and Kafka-driven consistency validation during migration. Range partitioning by post ID and denormalized JSONB records optimize batch reads without a read-through cache. At 100,000 requests per second, the store achieved read latencies of 2.6 milliseconds at p50 and 17 milliseconds at p99, and was about 50% faster than the previous system.
