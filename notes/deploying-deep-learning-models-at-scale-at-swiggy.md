---
title: "Deploying deep learning models at scale at Swiggy"
link: https://bytes.swiggy.com/deploying-deep-learning-models-at-scale-at-swiggy-tensorflow-serving-on-dsp-ad5da40f7a6c
topics:
  - AI/ML
  - Infrastructure
year: 2020
---

Swiggy added TensorFlow Serving to its Data Science Platform to support online deep-learning models without the Scala rewrites and JVM limitations of its MLeap-based serving path. The platform combines feature and model stores, a model control tower, and a runtime engine that retrieves features and invokes a colocated TensorFlow model server through gRPC. For ETA models fetching about 120 features, the team reports p95 latency below 15 milliseconds at 1,000 requests per second.
