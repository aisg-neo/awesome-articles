---
title: "How Discord Stores Trillions of Messages"
link: https://discord.com/blog/how-discord-stores-trillions-of-messages
topics:
  - Databases
year: 2023
---

Discord’s Cassandra message cluster developed unpredictable latency and high maintenance costs as storage grew to trillions of messages. The team migrated to ScyllaDB and introduced Rust data services to manage request concurrency and coalesce reads. Historical message fetch P99 latency fell from 40–125 ms to 15 ms, while message inserts stabilized at about 5 ms P99.
