# design-koans

Small public repo for GUI and TUI design principles, guides, references, and assets.

The surrounding workspace mixes embedded systems, local-LLM tooling, CLIs/TUIs, dashboards, and product experiments. This repo isolates the design layer so reusable interface thinking can live outside any one codebase.

## Scope

- `principles/`: durable rules, heuristics, and taste
- `guides/`: applied notes for specific interface problems
- `resources/`: curated links and short annotations
- `assets/`: small original artifacts that support a note
- `templates/`: tiny starter files

## Invariants

- One file, one strong idea.
- Prefer examples over adjectives.
- Prefer links over copied source material.
- Keep filenames short and descriptive.
- Keep screenshots cropped, compressed, and explained.
- Remove stale notes instead of stacking versions.
- If a note cannot teach reuse, it probably does not belong here.

## GUI / TUI Bias

- GUI: layout, type, spacing, color, states, motion, flow
- TUI: hierarchy, density, navigation rhythm, keymaps, latency feel, terminal constraints
- Shared: clarity, contrast, affordance, recoverability, calm defaults

## Koan Mode

This repo should stay closer to a notebook of distilled lessons than a design archive.

Each entry should answer:

1. What problem is this solving?
2. What rule survives reuse?
3. What is the smallest example that proves it?

## How To Add

1. Start in the smallest fitting directory.
2. Use `templates/principle.md` for new principle notes.
3. Keep notes short; split only when claims stop belonging together.
4. Add assets only when a note truly needs them.
5. Link guides to principles, not the other way around.

## What Does Not Belong

- Bulk inspiration dumps
- Vendor docs copied verbatim
- Large binary packs
- Generated exports with no explanation
- Multiple near-duplicate screenshots
- "Maybe useful later" folders

## Naming

- Principles: `NN-short-title.md`
- Guides: `topic-short-title.md`
- Assets: `assets/<slug>/...`
- Resources: short markdown indexes or annotated lists

## Maintenance

- README stays under 150 lines.
- Prefer pruning to archiving.
- If the structure feels heavy, delete directories before adding more.
