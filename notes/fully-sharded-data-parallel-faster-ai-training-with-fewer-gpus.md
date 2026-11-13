---
title: "Fully Sharded Data Parallel: faster AI training with fewer GPUs"
link: https://engineering.fb.com/2021/07/15/open-source/fsdp/
topics:
  - AI/ML
  - Infrastructure
year: 2021
---

Meta introduced Fully Sharded Data Parallel to train large models without replicating all model state on every GPU. FSDP shards parameters, gradients, and optimizer state across workers, gathers layer weights when needed, and can offload work to CPUs. Its FairScale implementation combines lower memory use with communication and computation overlap to train larger models with fewer GPUs.
