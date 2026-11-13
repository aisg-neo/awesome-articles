---
title: "How Dropbox uses ML to identify date formats in file names"
link: https://dropbox.tech/machine-learning/using-ml-to-identify-date-formats-in-file-names
topics:
  - AI/ML
year: 2023
---

Dropbox’s naming-conventions feature needed to recognize ambiguous date formats in filenames that rules could not reliably handle. The team trained a token-classification model to identify individual year, month, and day components using manually annotated and synthetic examples. It used DistilRoberta and inference optimizations to make the model suitable for the renaming workflow.
