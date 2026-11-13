---
title: "Invalidating robotic ad clicks in real time"
link: https://www.amazon.science/blog/invalidating-robotic-ad-clicks-in-real-time
topics:
  - Security
  - Data Engineering
year: 2023
---

Amazon needed to identify robotic ad clicks in real time without falsely invalidating human activity. SLIDR uses a weakly supervised neural network and slice-specific thresholds chosen through convex optimization under an overall false-positive budget. Deployed since 2021, the system includes continuous retraining, model-update guardrails, and recovery mechanisms for faulty decisions.
