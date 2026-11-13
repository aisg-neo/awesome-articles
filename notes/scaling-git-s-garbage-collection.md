---
title: "Scaling Git's garbage collection"
link: https://github.blog/engineering/architecture-optimization/scaling-gits-garbage-collection/
topics:
  - Performance
year: 2022
---

GitHub explains why deleting unreachable Git objects can cause races with concurrent pushes and why retaining them as loose objects creates scaling problems. It developed cruft packs to store unreachable objects compactly while retaining the timestamps needed for safe expiration. The work was contributed upstream to Git and supports more scalable repository garbage collection.
