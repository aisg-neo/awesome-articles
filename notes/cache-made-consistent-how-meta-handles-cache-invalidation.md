---
title: "Cache made consistent - How Meta handles cache invalidation"
link: https://engineering.fb.com/2022/06/08/core-infra/cache-made-consistent/
topics:
  - Caching
year: 2022
---

Meta investigated cache invalidation races that could leave TAO and other caches inconsistent with their databases. The team developed monitoring and debugging methods, including Polaris, to measure consistency independently and find failures that ordinary error metrics miss. By one measure, TAO consistency improved from six nines to ten nines, with 99.99999999% of cache writes consistent within five minutes.
