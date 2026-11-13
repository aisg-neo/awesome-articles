---
title: "Improve Git monorepo performance with a file system monitor"
link: https://github.blog/engineering/infrastructure/improve-git-monorepo-performance-with-a-file-system-monitor/
topics:
  - Performance
  - Infrastructure
year: 2022
---

Large Git working directories make commands such as git status expensive because they must scan many files for changes. Git's built-in file system monitor tracks filesystem notifications so subsequent commands can inspect the changed paths instead of scanning the entire working tree. The article explains how this works with Git's index and untracked cache to improve monorepo performance.
