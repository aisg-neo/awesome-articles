---
title: "Reducing Instagram's basic video compute time by 94 percent"
link: https://engineering.fb.com/2022/11/04/video-engineering/instagram-video-processing-encoding-reduction/
topics:
  - Video/Media
  - Performance
year: 2022
---

Instagram projected that growing video uploads would exhaust its processing capacity within a year, with more than 80% of resources spent on minimum-functionality encodings. Engineers reused progressive video frames by repackaging them into adaptive-bitrate containers instead of transcoding the same video again. This reduced basic video encoding compute time by 94%, freeing capacity for more advanced encodings.
