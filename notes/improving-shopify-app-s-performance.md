---
title: "Improving Shopify App's Performance"
link: https://shopify.engineering/improving-shopify-app-s-performance
topics:
  - Performance
  - Mobile
year: 2024
---

Shopify's mobile app slowed during its React Native migration, with P75 screen loads around 1.4 seconds and startup around four seconds. The team deferred offscreen rendering, adopted FlashList-based components, removed redundant updates, improved startup initialization, and repaired caching behavior. Individual changes reduced some screen load times by up to 50%, and enabling inline requires improved launch time by 17%.
