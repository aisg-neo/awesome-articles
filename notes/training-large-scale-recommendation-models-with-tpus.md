---
title: "Training Large-Scale Recommendation Models with TPUs"
link: https://eng.snap.com/training-models-with-tpus
topics:
  - AI/ML
  - Infrastructure
year: 2022
---

Snap moved large ad-recommendation training workloads from asynchronous CPU workers and parameter servers to synchronous TPU training. The article covers embedding lookups, input-pipeline tuning, and scaling limits specific to recommendation models. TPUs delivered faster, cheaper training than the CPU baseline, while synchronous execution made experiments more stable.
