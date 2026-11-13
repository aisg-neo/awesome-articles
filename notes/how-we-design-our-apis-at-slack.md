---
title: "How We Design Our APIs at Slack"
link: https://slack.engineering/how-we-design-our-apis-at-slack/
topics:
  - Architecture
year: 2021
---

Slack describes how it designs APIs whose behavioral contracts are difficult to change after developers adopt them. Its guidelines emphasize focused operations, quick onboarding, consistent conventions, bounded collections, and careful specification, review, and testing. One example splits the large rtm.start response into rtm.connect, which only returns a WebSocket session URL.
