---
title: "Anomaly Detection in Time Series Using Statistical Analysis"
link: https://medium.com/booking-com-development/anomaly-detection-in-time-series-using-statistical-analysis-cc587b21d008
topics:
  - Observability
  - Data Engineering
year: 2025
---

Booking.com built Granomaly to produce expected ranges for business metrics whose daily and weekly patterns make fixed thresholds unreliable. The service reads four to five weeks of Graphite history, excludes historical outliers, computes percentile-based prediction bounds, and writes those bounds back for Grafana dashboards and alerts. The article describes detecting both sudden drops and gradual declines, including adjustments for metrics running above their expected baseline.
