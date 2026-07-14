---
change: CHG-0003-define-the-existing-captain-corvid-comic-page-as-a-complete-canonical-contract
artifact: testing
---

# Testing

- REQ-comic-page-001: `identity` and `chapters` validate the exact existing title, tagline, and ordered headings.
- REQ-comic-page-002: chapter file tasks and `accessibility` validate all three non-empty assets and exact descriptions.
- REQ-comic-page-003: `narrative` and `chapters` validate story progression and closing cues.
- REQ-comic-page-004: `page` and `dependencies` validate the static document and external visual references; contract review confirms no form or custom application state.

Run `fledge lanes run verify` and strict SpecSync coverage. Confirm `git diff origin/main...HEAD -- landing` is empty.
