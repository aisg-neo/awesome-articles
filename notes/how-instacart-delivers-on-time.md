---
title: "How Instacart delivers on time"
link: https://tech.instacart.com/how-instacart-delivers-on-time-using-quantile-regression-2383e2e03edb
topics:
  - AI/ML
year: 2018
---

Instacart replaced fixed delivery-time buffers with a 90th-percentile quantile-regression model to account for varying uncertainty in delivery estimates. Its fulfillment engine uses the upper-bound predictions when planning deliveries and combines buffers to account for accumulated risk on trips containing multiple orders. An A/B test increased fulfillment efficiency by 4% by allowing deliveries to be planned closer to their deadlines without increasing the late-delivery percentage.
