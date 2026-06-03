# Absolute World Wiki

A lightweight, file-based lore wiki for tracking setting canon, unresolved drafts, and NPC-facing knowledge.

## Layout

- `schemas/` contains JSON Schema documents for reusable world data shapes.
- `data/` contains canonical world entries grouped by domain.
- `drafts/` contains non-canonical notes, extracted meeting details, and lore questions.
- `changelog/` records dated changes to the wiki.

## Canon Rules

1. Entries under `data/` are considered canonical unless marked otherwise.
2. Entries under `drafts/` are provisional and should be reviewed before promotion.
3. NPC knowledge files describe what a class of NPCs commonly believes, not necessarily objective truth.
4. When a canonical entry changes, add a dated note in `changelog/`.
