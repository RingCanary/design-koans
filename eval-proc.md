# Evaluation And Promotion Procedure

## Goal

Turn raw design study into a small public note set without taxonomy bloat.

## Working Model

- `inbox/` is a staging area for raw or semi-raw thought.
- Public docs only hold distilled notes.
- Nothing gets promoted without a clear problem, rule, and small example.

## Core Workflow

1. Ground the topic with a small source packet.
   - Use Don Norman as the base lens: signifiers, feedback, mappings, constraints, conceptual models, discoverability, error recovery.
   - Add only the minimum supporting stack: NN/g, WCAG 2.2, GOV.UK, Material, Baymard, HEART, Core Web Vitals.
2. Distill notes into atomic claims.
   - Each claim must state `problem`, `rule`, `why it matters`, `small example`, and `source`.
   - Reject anything that is really two claims glued together.
3. Classify before writing.
   - Every claim gets one primary `kind`, `family`, `lens`, `surface`, and `status`.
4. Promote only the smallest durable set.
   - Durable rules go to `principles/`.
   - Applied walkthroughs go to `guides/`.
   - Canonical source packets go to `resources/`.
   - Assets only exist to support a note.
5. Prune every cycle.
   - Merge overlaps before adding more.
   - Delete weak drafts, redundant guides, and unreferenced assets.

## Classifier

- `kind`: `principle` | `guide` | `resource` | `asset`
- `family`: `affordance` | `composition` | `quality`
- `lens`:
  - `affordance`: `signifiers`, `feedback`, `trust`
  - `composition`: `hierarchy`, `spacing`, `typography`, `color`
  - `quality`: `accessibility`, `performance`, `metrics`
- `surface`: `GUI` | `TUI` | `Shared`
- `status`: `draft` | `stable`

## Separation Rules

- Foundations: Norman-level ideas that should survive style changes.
- Heuristics: practical review checks such as hierarchy, spacing rhythm, and scanning.
- Requirements: accessibility and service-critical constraints that are not optional.
- Metrics: HEART, task-success signals, and performance thresholds.
- Aesthetic posture belongs in a short manifesto, not mixed into the classifier.

## Agent Split

- Agent A: build or refresh the source packet.
- Agent B: atomize raw notes into claims.
- Agent C: classify claims.
- Agent D: draft repo notes from approved claims.
- Human role: approve merges, reject duplicates, decide what becomes public.

## Promotion Pipeline

1. Raw note
2. Atomic claim
3. Classified claim
4. Draft principle or guide
5. Reviewed note
6. Optional stable promotion

Nothing skips steps 2 and 3.

## Current Merge Pass

- Promote `inbox/source-map.md` into a canonical grounding packet in `resources/`.
- Publish the first principle batch from high-confidence claims:
  - A-02, A-03, A-04, A-05, A-06, A-07, A-13, A-15, A-19, A-22, A-23, A-20
- Publish first guides:
  - A-25 manual accessibility testing
  - A-26 service journey validation
  - A-21 + A-22 list/filter findability
- Keep claim IDs visible in repo notes so lineage stays clear.

## Decision Rule

- Is it durable?
- Is it atomic?
- Is it reusable across GUI or TUI work?
- Does it include a smallest example?
- Does it reduce ambiguity instead of adding categories?

If not, keep it in `inbox/` and do not promote it.

## Open Gaps

- Semantic markup
- Responsive design
- Cognitive load
