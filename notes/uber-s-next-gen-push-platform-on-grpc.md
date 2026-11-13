---
title: "Uber's Next Gen Push Platform on gRPC"
link: https://www.uber.com/en-IN/blog/ubers-next-gen-push-platform-on-grpc/
topics:
  - Messaging
  - Infrastructure
year: 2022
---

Uber migrated its RAMEN push platform from HTTP/1.1 Server-Sent Events to gRPC bidirectional streaming so clients could acknowledge messages immediately and handle connections more efficiently. The rollout required changes across mobile clients, proxies, and backend services and reached Rider, Driver, and Eats apps worldwide. P95 connection latency improved by at least 45%, and push success rates rose by at least 1–2% across apps.
