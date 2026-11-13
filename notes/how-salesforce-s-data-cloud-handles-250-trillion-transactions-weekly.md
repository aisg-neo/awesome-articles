---
title: "How Salesforce's Data Cloud Handles 250 Trillion Transactions Weekly"
link: https://engineering.salesforce.com/the-unstructured-data-dilemma-how-data-cloud-handles-250-trillion-transactions-weekly/
topics:
  - Data Engineering
  - Performance
year: 2024
---

Salesforce Data Cloud needed to process diverse unstructured data while integrating a microservice platform with Salesforce’s monolithic core. The team introduced chunking, vectorization, similarity search, and release quality gates across the two environments. Deploying models on Amazon EMR on EKS helped the platform handle approximately 250 trillion transactions per week across tenants.
