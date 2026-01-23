# CG Primitive Registry, Formal Plane

This repository is the Formal Plane for Convergent Governance (CG) primitives.

## Purpose
This registry is the canonical, authoritative record of governance primitives. It exists to preserve identity, provenance, constraints, and evolution of primitives over time.

## Two-plane rule
The Semantic Plane may reference the Formal Plane.
The Formal Plane must never depend on the Semantic Plane.

## Canon rule
No primitive may be referenced as authoritative CG doctrine unless it has a canonical record in `primitives/` and an entry in `INDEX.md`.

## Change discipline
Edits to primitive records should be intentional, minimal, and traceable. Prefer small commits with clear messages.

## Structure
- `INDEX.md` is the navigation table.
- `PRIMITIVE_TEMPLATE.md` is the canonical record template.
- `primitives/` contains one file per primitive, named by Primitive ID.

## Status states
- Identified
- Validated
