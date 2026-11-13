---
title: "How Trino and Alluxio power analytics at Razorpay"
link: https://engineering.razorpay.com/how-trino-and-alluxio-power-analytics-at-razorpay-803d3386daaf
topics:
  - Data Engineering
year: 2022
---

Razorpay's externally managed analytics platform suffered reliability problems and SLA breaches as workloads grew. It built a self-managed Trino platform on Kubernetes, separating BI, scheduled transformation, and ad hoc workloads into different clusters. Alluxio adds a caching layer between Trino and the S3 data lake to improve access to frequently queried data.
