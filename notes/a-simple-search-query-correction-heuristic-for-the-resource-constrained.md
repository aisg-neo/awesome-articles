---
title: "A simple search query correction heuristic for the resource-constrained"
link: https://tech.instacart.com/avacado-or-avocado-4b4b78dc0698
topics:
  - Search
year: 2020
---

Instacart needed to correct misspelled grocery searches without maintaining an expanding manual dictionary. The team used historical query transitions and successful conversions to build a Markov-chain-inspired heuristic that maps unsuccessful queries to likely successful alternatives. This provided a lightweight way to improve recall for misspellings using customer search behavior.
