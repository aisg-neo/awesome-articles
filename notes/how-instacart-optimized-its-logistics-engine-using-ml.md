---
title: "How Instacart optimized its Logistics engine using ML"
link: https://tech.instacart.com/dont-let-the-crow-guide-your-routes-f24c96daedba
topics:
  - AI/ML
year: 2021
---

Instacart’s logistics engine needed accurate travel distances for billions of route comparisons without making a paid mapping API call for each one. It combined cached Mapbox distances with an XGBoost model trained on historical trips and corrected GPS observations. In Orange County, the model reduced mean absolute percentage error from 33% for straight-line distance to 11%.
