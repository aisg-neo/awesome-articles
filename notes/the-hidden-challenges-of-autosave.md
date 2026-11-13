---
title: "The hidden challenges of autosave"
link: https://www.figma.com/blog/behind-the-feature-autosave/
topics:
  - Architecture
year: 2020
---

Figma expanded autosave to persist disconnected edits locally and restore them when a document is reopened. The article explains why serializing whole documents would stall large files and how multiplayer editing complicates saving, restoring, and merging changes. The system preserves offline work even if the browser tab closes before it can synchronize with the server.
