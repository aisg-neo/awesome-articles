---
title: "Using deep learning to detect dissonance between address text and location"
link: https://bytes.swiggy.com/using-deep-learning-to-detect-dissonance-between-address-text-and-location-4b228bc2c3fb
topics:
  - AI/ML
year: 2022
---

Swiggy trained a deep learning classifier to detect mismatches between a customer's written address and captured GPS location. It creates positive examples from delivered-order signals and synthesizes mismatches by perturbing locations, then fine-tunes RoBERTa on address text and geohash inputs. Manual validation on cancelled-order addresses in a large Indian city found 84% precision, with flagged locations corrected manually.
