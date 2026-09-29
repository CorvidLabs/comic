---
id: CHG-0003-define-the-existing-captain-corvid-comic-page-as-a-complete-canonical-contract
state: archived
type: documentation
base_commit: 03d079d8f18667ccba823c578d5edc62b7b47cee
---

# Define the existing Captain Corvid comic page as a complete canonical contract

## Intent

Define the existing Captain Corvid comic page as a complete canonical contract

## Affected Canonical Specs

- `comic-page`

## Acceptance Criteria

- The canonical comic-page spec exactly describes the existing static page; every requirement has deterministic native evidence; landing/index.html has 100% canonical coverage; no comic HTML or image bytes change

## No-spec Rationale

Not applicable

## Migration Note

Migrated by hand to SpecSync 6 per Leif's decision (2026-09-28); the 6.0.0 tool refused to archive this legacy record (`` failed to parse local registry .specsync/registry.toml while resolving `comic-page` ``). The error's absolute checkout path is shortened to the repo-relative path.

- Workflow v1 (SpecSync 5) record, accepted on 2026-07-14 by the closing approval already stored in `approvals.json`. SpecSync 6.0.0 reports its accepted evidence as stale, for the reason quoted above.
- Moved by hand from `.specsync/changes/CHG-0003-define-the-existing-captain-corvid-comic-page-as-a-complete-canonical-contract/` into the layout `specsync change archive` writes: `accepted-state.json` is the unchanged accepted `state.json`, `state.json` is marked `archived`, and this file's front matter says `archived`.
- `approvals.json`, `verification.json` and every other artifact are the original SpecSync 5 evidence, unchanged. `verification.json` verifies commit `5a4bfbac8d8204fcda27c6ea1bf94e2d21a6d355`, not the tree this record was archived from.
- There is no `verification-attempts.json`: SpecSync 5 did not write one for this record, and this migration does not invent attempt history.
- This migration added no verification evidence, test result, attempt history, or approval. It is a manual migration, not a fresh re-verification.
- Closing it through the tool takes `specsync change reopen`, `specsync change verify`, then `specsync change accept`, which writes a new closing approval. Per Leif's decision it was archived by hand instead, so no reopen or new approval is recorded.
