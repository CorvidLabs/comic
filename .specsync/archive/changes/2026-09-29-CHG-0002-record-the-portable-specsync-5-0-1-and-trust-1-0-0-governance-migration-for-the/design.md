---
change: CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the
artifact: design
---

# Design

Use `.trust.toml` as policy authority, `.specsync/sdd.json` as the lifecycle manifest, and `fledge lanes run verify` as the single native verification boundary. Keep the immutable hosted action pins and every integration file from the original migration.
