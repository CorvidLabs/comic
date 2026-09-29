---
id: CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the
state: archived
type: migration
base_commit: 03d079d8f18667ccba823c578d5edc62b7b47cee
---

# Record the portable SpecSync 5.0.1 and Trust 1.0.0 governance migration for the comic repository

## Intent

Record the portable SpecSync 5.0.1 and Trust 1.0.0 governance migration for the comic repository

## Affected Canonical Specs

- None

## Acceptance Criteria

- All migration files are covered by exact paths; all four agent integrations are installed; the native validation lane passes; SpecSync strict coverage is 100%; Trust verification passes without changing landing content or assets

## No-spec Rationale

This successor records governance, agent integration, and verification configuration only; it does not change the comic page contract or deployed assets.

## Migration Note

Migrated by hand to SpecSync 6 per Leif's decision (2026-09-28); the 6.0.0 tool refused to archive this legacy record (`` legacy accepted change `CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the` requires exactly one distinct valid historical reconstruction, found 0; first reconstruction failure: legacy accepted change `CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the` cannot reproduce its signed raw-content aggregate ``).

- Workflow v1 (SpecSync 5) record, accepted on 2026-07-14 by the closing approval already stored in `approvals.json`. SpecSync 6.0.0 reports its accepted evidence as stale, for the reason quoted above.
- Moved by hand from `.specsync/changes/CHG-0002-record-the-portable-specsync-5-0-1-and-trust-1-0-0-governance-migration-for-the/` into the layout `specsync change archive` writes: `accepted-state.json` is the unchanged accepted `state.json`, `state.json` is marked `archived`, and this file's front matter says `archived`.
- `approvals.json`, `verification.json` and every other artifact are the original SpecSync 5 evidence, unchanged. `verification.json` verifies commit `5a4bfbac8d8204fcda27c6ea1bf94e2d21a6d355`, not the tree this record was archived from.
- There is no `verification-attempts.json`: SpecSync 5 did not write one for this record, and this migration does not invent attempt history.
- This migration added no verification evidence, test result, attempt history, or approval. It is a manual migration, not a fresh re-verification.
- Closing it through the tool takes `specsync change reopen`, `specsync change verify`, then `specsync change accept`, which writes a new closing approval. Per Leif's decision it was archived by hand instead, so no reopen or new approval is recorded.
