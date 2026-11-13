---
title: "The Making of Razorpay Developer-Console"
link: https://engineering.razorpay.com/the-making-of-developer-console-978018ce2aed
topics:
  - Frontend
year: 2023
---

Razorpay built a central developer console so merchants could inspect API requests, responses, and webhooks when debugging integrations. A custom Kong gateway plugin captures request and response data centrally, with sensitive information filtered before it reaches the logging pipeline. The article describes the ingestion and Elasticsearch storage design, including bulk writes to improve insertion throughput.
