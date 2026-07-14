---
spec: comic-page.spec.md
---

# Comic Page Testing

The deterministic native gate is `fledge lanes run verify`.

- REQ-comic-page-001 is checked by the `identity` and `chapters` tasks against the exact existing title, tagline, and chapter headings.
- REQ-comic-page-002 is checked by the three chapter file tasks and the `accessibility` task against the exact image descriptions.
- REQ-comic-page-003 is checked by the `narrative` and `chapters` tasks against the story markers, continuation cue, and footer invitation.
- REQ-comic-page-004 is checked by the `page` and `dependencies` tasks. Manual contract review confirms the existing document has no form or custom application script; the only script element loads Tailwind CSS.

The `ci` lane adds `specsync check --strict --require-coverage 100 --force` after the native gate. The migration must not modify `landing/index.html` or any image.
