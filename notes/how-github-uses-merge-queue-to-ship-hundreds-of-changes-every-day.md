---
title: "How GitHub uses merge queue to ship hundreds of changes every day"
link: https://github.blog/engineering/engineering-principles/how-github-uses-merge-queue-to-ship-hundreds-of-changes-every-day/
topics:
  - Infrastructure
year: 2024
---

GitHub’s internal deployment trains became difficult to manage as the number of daily changes grew, delaying merges and burdening engineers. The team developed and adopted merge queue to group, validate, and merge changes through a workflow available in GitHub itself. It now uses the queue to ship hundreds of pull requests each day.
