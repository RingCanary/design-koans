# Recoverable Errors

- Status: draft
- Domain: Shared
- Claim: A-04
- Family: affordance
- Lens: feedback
- Question: What makes an error actionable instead of frustrating?
- Rule: Every error should explain what failed, where it failed, how to fix it, and preserve user input.
- Why it works: Specific recovery paths reduce abandonment and support dependency.
- Use when: Forms, uploads, mutations, filters, or any state change can fail.
- Avoid when: Error text is generic, detached from the field, or wipes entered data.
- Small example: Invalid email shows inline guidance plus a linked summary, while preserving the typed value.
- Related: [In-Context Feedback](./02-in-context-feedback.md), [Prevent Invalid Actions](./05-prevent-invalid-actions.md)
