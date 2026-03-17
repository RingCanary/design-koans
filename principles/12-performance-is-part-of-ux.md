# Performance Is Part Of UX

- Status: draft
- Domain: Shared
- Claim: A-20
- Family: quality
- Lens: performance
- Question: When does performance become a design concern?
- Rule: Track Core Web Vitals and design interactions to reduce delay, instability, and main-thread spikes.
- Why it works: Perceived quality collapses when pages load slowly, shift visibly, or lag during interaction.
- Use when: Any public web page, filtered list, dashboard, or app flow with network and rendering cost.
- Avoid when: Visual or interaction choices ignore latency, layout shift, or input delay.
- Small example: Reserve image space, avoid heavy synchronous work during filter changes, and prefetch likely next actions.
- Related: [Findability-First Listings](./10-findability-first-listings.md), [Service Journey Validation](../guides/service-journey-validation.md)
