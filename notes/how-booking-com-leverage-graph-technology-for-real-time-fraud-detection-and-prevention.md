---
title: "How Booking.com Leverage graph technology for real-time Fraud Detection and Prevention"
link: https://medium.com/booking-com-development/leverage-graph-technology-for-real-time-fraud-detection-and-prevention-438336076ea5
topics:
  - Security
year: 2024
---

Booking.com built a real-time graph service to expose relationships between reservation identifiers and previously observed fraud. The service stores the graph in JanusGraph backed by Cassandra, adds identifiers and edges for incoming requests, and uses breadth-first traversal to calculate features such as node counts and distance to known fraud. These features feed fraud models and expert rules, with indexing and other optimizations achieving a p99 response time of 300 milliseconds.
