---
title: "How LedgerStore Supports Trillions of Indexes at Uber"
link: https://www.uber.com/en-IN/blog/how-ledgerstore-supports-trillions-of-indexes/
topics:
  - Databases
year: 2024
---

Uber’s immutable LedgerStore needs multiple indexing strategies to support financial transaction lookups across hundreds of billions of ledgers. It uses index intents for strong read-after-write guarantees, asynchronous Docstore materialized views for eventual indexes, and time-range indexes for bulk archival workflows. Together these support trillions of indexes with a petabyte-scale storage footprint.
