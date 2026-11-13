---
title: "Rebuilding Netflix Video Processing Pipeline with Microservices"
link: https://netflixtechblog.com/rebuilding-netflix-video-processing-pipeline-with-microservices-4e5e6310e359
topics:
  - Video/Media
  - Architecture
year: 2024
---

Netflix rebuilt its Reloaded video-processing monolith as independently deployable Cosmos microservices to reduce coupling and long release cycles. Dedicated services handle inspection, complexity analysis, ladder generation, encoding, validation, and quality measurement, with separate orchestrators for streaming and studio workflows. The migration completed in September 2023, and the modular pipeline also supported rapidly changing requirements for advertising creatives.
