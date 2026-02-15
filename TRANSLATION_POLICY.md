# Translation Policy (Model B)

## Tracks
- English files (`*.en.md`) are the release track and the canonical public reference.
- Spanish snapshots are stored under `es-snapshots/` only at release points.

## Source of truth
- Concept development happens off-repo (local Spanish workbench).
- Public releases are English-only; Spanish appears only as a frozen snapshot for provenance.

## No silent divergence
If the English release introduces a conceptual change that is not a pure translation of the Spanish snapshot, it must be recorded explicitly in `TRANSLATION_LOG.md` as a substantive divergence.

## Minimal provenance
Each English release must reference exactly one Spanish snapshot folder:
`es-snapshots/vX.Y.Z/`
