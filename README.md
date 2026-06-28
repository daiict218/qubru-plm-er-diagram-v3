# Qubru PLM Data Model v3 — Validated Explorer

Interactive ER explorer for the Qubru PLM data model (v3): 44 entities, 9 domains.

Includes a **built-in deterministic validator**:
- **✓ Validate** re-runs every check and repopulates each node's problems.
- Per-node **🔧 Fix** buttons apply safe, deterministic corrections.
- **⚡ Fix all**, **⬇ Export model / report**, **↺ Reset**.

Checks: missing keys/edges, reversed edges, orphans, duplicate edges,
unbacked relationships, polymorphic FKs, CSV id-lists, money-as-float,
undefined enums, missing timestamps, redundant inverse pairs.

Mobile-friendly. Open `index.html` (served via GitHub Pages).
