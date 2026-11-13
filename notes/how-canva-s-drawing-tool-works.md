---
title: "How Canva's drawing tool works"
link: https://www.canva.dev/blog/engineering/behind-the-draw/
topics:
  - Frontend
year: 2024
---

Canva built a vector drawing tool using a state machine and perfect-freehand to turn pointer input into SVG strokes. To address mobile latency and design-size limits, it buffered input natively, split long strokes, and simplified SVG geometry. Relative path commands alone reduced average stroke length by about 32%, with additional savings from path simplification and merging overlapping regions.
