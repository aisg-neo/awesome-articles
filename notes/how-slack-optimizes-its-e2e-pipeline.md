---
title: "How Slack Optimizes its E2E Pipeline"
link: https://slack.engineering/speedup-e2e-testing/
topics:
  - Infrastructure
year: 2025
---

Slack found that its E2E pipeline rebuilt frontend assets even when a pull request contained no frontend changes. It added Git-based change detection and reused recent production assets from S3 through an internal CDN. The change reduced frontend build frequency by 60% and, together with an earlier Webpack upgrade, brought average E2E pipeline build time from about ten minutes to two.
