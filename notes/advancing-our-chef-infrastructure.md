---
title: "Advancing Our Chef Infrastructure"
link: https://slack.engineering/advancing-our-chef-infrastructure/
topics:
  - Infrastructure
year: 2024
---

Slack's single Chef stack and simultaneous cookbook deployments created a risk of fleet-wide failures. The team sharded Chef infrastructure, separated development and production stacks, moved node discovery to Consul, and introduced Chef Librarian to manage versioned artifacts and staged promotion. These changes made provisioning and configuration deployment safer as the EC2 fleet grew.
