---
title: "How Meta trains large language models at scale"
link: https://engineering.fb.com/2024/06/12/data-infrastructure/training-large-language-models-at-scale-meta/
topics:
  - AI/ML
  - Infrastructure
year: 2024
---

Meta’s move from many smaller recommendation-training jobs to enormous LLM jobs required changes across hardware, networking, scheduling, and recovery. It adapted H100-based Grand Teton systems, improved failure detection and checkpointing, and built two 24,000-GPU clusters using RoCE and InfiniBand respectively. The article explains how these choices address the reliability and communication demands of training across so many GPUs.
