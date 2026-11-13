---
title: "Scaling Kubernetes to Over 4k Nodes and 200k Pods"
link: https://medium.com/paypal-tech/scaling-kubernetes-to-over-4k-nodes-and-200k-pods-29988fad6ed
topics:
  - Infrastructure
year: 2022
---

PayPal stress-tested Kubernetes during its migration from Mesos and found bottlenecks in the API server, controllers, scheduler, and etcd. It tuned request limits and concurrency and separated event storage into a distinct etcd cluster to improve control-plane stability. The tests scaled to about 4,100 nodes and 200,000 pods, with p99 pod-start latency around five seconds.
