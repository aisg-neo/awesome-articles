---
title: "How Meta animates AI-generated images at scale"
link: https://engineering.fb.com/2024/08/14/production-engineering/how-meta-animates-ai-generated-images-at-scale/
topics:
  - AI/ML
  - Infrastructure
year: 2024
---

Meta needed its image-animation model to generate results quickly while serving large numbers of users with limited GPU resources. It optimized precision, attention operations, diffusion sampling, and deployment, and combined guidance distillation with step distillation. The final distilled model reduced 32 teacher steps with multiple passes to eight student steps with one U-Net pass per step.
