# Prevent Invalid Actions

- Status: draft
- Domain: Shared
- Claim: A-06
- Family: affordance
- Lens: feedback
- Question: How can the interface prevent failure before it happens?
- Rule: Constrain choices before submission whenever the system already knows an option is invalid.
- Why it works: Prevention is cheaper and less frustrating than post-failure recovery.
- Use when: Date pickers, required fields, destructive actions, impossible combinations, and known limits.
- Avoid when: Disabled states hide needed explanation or block exploration without context.
- Small example: Invalid dates are disabled, required fields gate submit only after the rule is clear, and dangerous actions ask for confirmation.
- Related: [Recoverable Errors](./03-recoverable-errors.md), [Visible Focus](./09-visible-focus.md)
