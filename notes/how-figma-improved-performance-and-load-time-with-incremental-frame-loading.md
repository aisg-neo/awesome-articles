---
title: "How Figma improved performance and load time with incremental frame loading"
link: https://www.figma.com/blog/incremental-frame-loading/
topics:
  - Performance
year: 2024
---

Figma prototypes became slow to load and prone to mobile crashes because clients loaded entire documents into memory. The team introduced incremental frame loading, subscribing only to the starting screen, reachable neighboring screens, and their dependencies. A revised real-time synchronization protocol and eviction of unsubscribed data reduced memory requirements while retaining live updates and responsive navigation.
