---
title: "How Precision Time Protocol is being deployed at Meta"
link: https://engineering.fb.com/2022/11/21/production-engineering/precision-time-protocol-at-meta/
topics:
  - Infrastructure
year: 2022
---

Meta deployed Precision Time Protocol to improve clock synchronization beyond the millisecond precision of NTP. The article describes the timing infrastructure, from GNSS antennas and time appliances to hardware-timestamped network packets and client software. More precise time reduces uncertainty for distributed-system operations, with an experiment showing roughly a hundredfold performance difference between NTP and an early PTP implementation.
