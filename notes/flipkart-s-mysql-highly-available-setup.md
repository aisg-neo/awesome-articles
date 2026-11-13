---
title: "Flipkart's MySQL Highly Available Setup"
link: https://blog.flipkart.tech/mysql-high-availability-5f71838f19e1
topics:
  - Databases
year: 2023
---

Flipkart built Altair, a managed MySQL service, to reduce operational work and maintain availability across its many microservices. The article describes failure detection, primary isolation, replica promotion, and recovery coordination designed to prevent split-brain scenarios. Its failover implementation had detected and recovered from more than 500 primary failures.
