---
title: "How Slack automatically detects stolen session cookies"
link: https://slack.engineering/catching-compromised-cookies/
topics:
  - Security
year: 2024
---

Slack built stolen-cookie detection by looking for session forking, where multiple devices use copies of the same session cookie. It compares rotating access timestamps and supplements them with network and device signals. A two-phase candidate-cookie update and handling for concurrent requests reduce false positives caused by missed responses and in-flight requests.
