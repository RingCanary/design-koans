# Manual Accessibility Testing Sequence

- Status: draft
- Domain: Shared
- Claim: A-25
- Type: guide
- Links to principles: [Visible Focus](../principles/09-visible-focus.md), [Never Use Color Alone](../principles/08-never-use-color-alone.md), [Recoverable Errors](../principles/03-recoverable-errors.md)

## Sequence

1. Run the core path with keyboard only.
2. Verify visible focus on every interactive element and transition.
3. Check hover/focus-triggered content for dismissal, persistence, and readability.
4. Trigger form errors and confirm they are specific, connected, and recoverable.
5. Run screen-reader passes on the same key flows.
6. Check zoom, contrast, reduced motion, and color-independent meaning.
7. Record failures by flow, control, and severity, not just by page.

## Exit Criteria

- No critical step requires a mouse.
- Focus is always visible and never lost.
- Meaning survives without color alone.
- Error recovery is possible without re-entering work.
