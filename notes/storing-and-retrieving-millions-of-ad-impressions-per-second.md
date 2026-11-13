---
title: "Storing and retrieving millions of ad impressions per second"
link: https://blog.x.com/engineering/en_us/topics/infrastructure/2021/storing-and-retrieving-millions-of-ad-impressions-per-second
topics:
  - Databases
  - Performance
year: 2021
---

Twitter redesigned its ad-impression metadata system because a shared monolithic structure coupled teams, obscured ownership, and made field changes error-prone. It separated data by problem domain and introduced Impression Data Service to store and retrieve metadata through a common interface. The design allows producers to own their fields and scale their storage independently while supporting millions of impressions per second.
