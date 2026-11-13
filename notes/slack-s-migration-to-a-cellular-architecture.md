---
title: "Slack's Migration to a Cellular Architecture"
link: https://slack.engineering/slacks-migration-to-a-cellular-architecture/
topics:
  - Architecture
year: 2023
---

A partial availability-zone network failure exposed how Slack's cross-zone dependencies could turn an isolated fault into a user-visible outage. Slack migrated critical user-facing services to cells and built traffic controls to drain an affected zone quickly and gradually restore traffic. The design targets draining a zone within five minutes and supports traffic-weight adjustments as small as 1%.
