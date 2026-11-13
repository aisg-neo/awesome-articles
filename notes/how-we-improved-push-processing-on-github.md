---
title: "How we improved push processing on GitHub"
link: https://github.blog/engineering/architecture-optimization/how-we-improved-push-processing-on-github/
topics:
  - Performance
year: 2024
---

GitHub's push processing ran more than 60 tasks owned by 20 services in one sequential background job, causing coupled failures and conflicting retry requirements. It replaced that job with a Kafka event that fans out to independently owned background jobs with their own retry policies. This isolates failures and lets tasks such as pull-request synchronization run without waiting for unrelated processing.
