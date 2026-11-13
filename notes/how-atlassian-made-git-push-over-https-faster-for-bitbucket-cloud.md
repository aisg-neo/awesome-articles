---
title: "How Atlassian made Git push over HTTPS faster for Bitbucket Cloud"
link: https://www.atlassian.com/blog/atlassian-engineering/faster-git-push-over-https-for-bitbucket-cloud
topics:
  - Performance
year: 2022
---

Bitbucket Cloud found that Git pushes over HTTPS were constrained by default HTTP/2 flow-control settings on its edge load balancers. Increasing frame sizes and stream buffers removed the receive-window bottleneck, particularly benefiting high-latency connections and large repository migrations. A test push improved from about 321 KiB/s to 7.46 MiB/s after tuning.
