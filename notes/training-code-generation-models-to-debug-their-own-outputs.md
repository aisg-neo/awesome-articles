---
title: "Training code generation models to debug their own outputs"
link: https://www.amazon.science/blog/training-code-generation-models-to-debug-their-own-outputs
topics:
  - AI/ML
year: 2025
---

Amazon researchers trained code-generation models to diagnose and repair their own mistakes using synthetic debugging examples verified by unit tests. They combined supervised fine-tuning with reinforcement learning, using execution feedback and CodeBLEU as reward signals. Across experiments with StarCoder and CodeLlama models, the approach improved pass@k scores by up to 39% on standard benchmarks such as MBPP.
