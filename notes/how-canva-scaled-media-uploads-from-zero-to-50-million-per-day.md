---
title: "How Canva scaled media uploads from Zero to 50 Million per day"
link: https://www.canva.dev/blog/engineering/from-zero-to-50-million-uploads-per-day-scaling-media-at-canva/
topics:
  - Performance
  - Infrastructure
year: 2022
---

Canva’s media metadata service outgrew MySQL as uploads and stored media increased. The team migrated to DynamoDB using SQS messages that triggered current-state replication, prioritized active media, and validated results with dual reads. The production cutover had no downtime or errors, and the service now supports more than 25 billion uploaded media with 50 million new uploads daily.
