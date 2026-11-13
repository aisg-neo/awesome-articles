---
title: "How Airbnb improved page performance using HTTP Streaming"
link: https://medium.com/airbnb-engineering/improving-performance-with-http-streaming-ba9e72c66408
topics:
  - Performance
  - Frontend
year: 2023
---

Airbnb introduced HTTP streaming to reduce page-loading waterfalls in its React and Node.js web application. Early Flush sends resource references before backend data is ready, while deferred-data streaming lets rendering and server-side data fetching run in parallel. Experiments reduced First Contentful Paint by about 100 milliseconds on every tested page, and data streaming removed the FCP cost of slow backend queries.
