---
title: "Building an Experiment-Based Routing Service"
link: https://www.reddit.com/r/RedditEng/comments/1c4pkql/building_an_experimentbased_routing_service/
topics:
  - Architecture
year: 2023
---

Reddit built an experiment-based routing service to migrate users between legacy web applications and Shreddit without manual experiment analysis or inconsistent exposure events. An Envoy reverse proxy uses a Go external processor integrated with Reddit's experimentation SDK to determine eligibility, log exposure, and route requests to the selected application. After A/A and A/B validation, developers used the service for more than a dozen experiments routing billions of requests.
