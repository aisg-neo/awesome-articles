---
title: "Pushing Discord's Limits with a Million+ Online Users in a Single Server"
link: https://discord.com/blog/maxjourney-pushing-discords-limits-with-a-million-plus-online-users-in-a-single-server
topics:
  - Performance
  - Infrastructure
year: 2023
---

Discord's largest servers were reaching the throughput and responsiveness limits of a single Elixir guild process. The team introduced passive sessions, distributed fanout through relays, and moved expensive work to worker processes using ETS. Passive connections reduced fanout work by about 90%, while the broader changes supported servers approaching two million concurrent users.
