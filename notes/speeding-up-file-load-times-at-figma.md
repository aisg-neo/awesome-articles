---
title: "Speeding up file load times at Figma"
link: https://www.figma.com/blog/speeding-up-file-load-times-one-page-at-a-time/
topics:
  - Performance
year: 2024
---

Figma introduced dynamic page loading so large files need not load every page before users can work. Its QueryGraph dependency framework tracks cross-page read and write dependencies so components, styles, variables, and edits remain correct as content loads on demand. The change reduced load times by 33% for the slowest 5% of page loads.
