---
title: "How Facebook encodes your videos"
link: https://engineering.fb.com/2021/04/05/video-engineering/how-facebook-encodes-your-videos/
topics:
  - Video/Media
year: 2021
---

Facebook needed to allocate limited encoding compute across hundreds of millions of daily video uploads. It built a benefit-cost priority model that combines predicted watch time, compression efficiency, device compatibility, and encoding cost. Machine learning predicts viewing over the next hour so more computationally expensive encodings can be prioritized for videos likely to benefit the most viewers.
