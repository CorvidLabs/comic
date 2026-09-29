---
change: CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the
artifact: testing
---

# Testing

Run `fledge lanes run verify`, released `specsync check --strict --require-coverage 100 --force`, all-agent status, and `fledge trust doctor` plus `fledge trust verify`. Hosted Trust must pass on the exact pull-request head. Confirm the diff contains no `landing/` file.
