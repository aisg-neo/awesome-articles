---
title: "Migrating Uber's Compute Platform to Kubernetes"
link: https://www.uber.com/en-IN/blog/migrating-ubers-compute-platform-to-kubernetes-a-technical-journey/?uclick_id=b4e6f2b7-b4a5-446a-beeb-0cc53334b2fe
topics:
  - Infrastructure
year: 2025
---

Uber migrated all shared stateless workloads from Mesos to Kubernetes in 2024 while keeping the change transparent to service developers. It addressed large-cluster scheduling, API-server load, deployment compatibility, and reliability with customizations and extensive benchmarking. The platform supports about 4,000 services using three million cores, and peak migration throughput reached roughly 300,000 cores in one week.
