---
title: "How we sped up Notion in the browser with WASM SQLite"
link: https://www.notion.com/blog/how-we-sped-up-notion-in-the-browser-with-wasm-sqlite
topics:
  - Performance
  - Frontend
year: 2024
---

Notion brought its native apps' SQLite client cache to browsers using WebAssembly SQLite and persistent storage in the Origin Private File System. A SharedWorker routes queries from multiple tabs to one active tab's dedicated worker, avoiding concurrent access problems. The change improved page navigation times by 20% overall, with gains of 28% in Australia, 31% in China, and 33% in India.
