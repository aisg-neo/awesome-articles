---
title: "Predicting your next query even before you type!"
link: https://blog.flipkart.tech/predicting-your-next-query-even-before-you-type-83487a34109d
topics:
  - AI/ML
  - Search
year: 2021
---

Flipkart built personalized query suggestions from the search reformulations and product clicks recorded in customer shopping journeys. Its Content Generation Framework combines query-transition and shared-product signals, filters candidates for spelling, duplication, and historical performance, and writes ranked relationships to a distributed key-value store. A stateless autosuggest service uses these relationships to populate Discover More suggestions. In offline analysis, 99.5% of bulk lookups for these relationships finished in under four milliseconds.
