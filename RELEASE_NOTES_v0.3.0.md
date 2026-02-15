# RELEASE_NOTES_v0.3.0.md

[Inference]

# Release v0.3.0 — Core solidity (cp-core-03-apparatus-method)

## Summary
This release upgrades **cp-core-03** from scaffold to **Core solidity** by making the Apparatus Method **auditable and testable**: the invariant set is operationalized via conceptual tests, the argument map is expanded to v0.3-level granularity, the glossary is expanded to a controlled vocabulary suitable for cross-referencing, and objections are made **Core-03-specific** (apparatus-focused).

## Highlights
- **Gate v0.3.0 compliance (Core solidity)**
  - Added `EN/TESTS.en.md` with pass/fail criteria mapped to invariants **I1–I6**.
  - Expanded `EN/GLOSSARY.en.md` to **22 terms (G1–G22)** with boundary notes (“Boundary note” / “Not”).
  - Expanded `EN/ARGUMENT_MAP.en.md` with a more exhaustive premise set (P1–P16) and explicit glossary linking.
  - Replaced/refined `EN/OBJECTIONS.en.md` so objections target the **Apparatus Method** (bureaucratization, PoS gaming, boundary legibility limits, privacy/logging tension, contestability attack surface, emergency-mode abuse, etc.).

- **Metadata and traceability fixes**
  - Fixed `CITATION.cff` title/repo metadata to match **cp-core-03-apparatus-method**.
  - Updated `TRANSLATION_LOG.md` to explicitly list translated artifacts (paths) for clearer Model B traceability.

## Key artifacts (canonical EN track)
- `EN/THESIS.en.md`
- `EN/INVARIANTS.en.md` (I1–I6)
- `EN/ARGUMENT_MAP.en.md`
- `EN/GLOSSARY.en.md` (G1–G22)
- `EN/OBJECTIONS.en.md`
- `EN/TESTS.en.md`

## Model B provenance requirement
Before tagging/publishing `v0.3.0`, freeze exactly one Spanish provenance snapshot folder:

- `es-snapshots/v0.3.0/`
  - `THESIS.es.md`
  - `ARGUMENT_MAP.es.md`
  - `GLOSSARY.es.md`
  - (optional but recommended) `INVARIANTS.es.md`, `OBJECTIONS.es.md`, `TESTS.es.md`

And ensure:
- `TERMINOLOGY.md`, `TRANSLATION_POLICY.md` unchanged unless intentionally amended,
- `TRANSLATION_LOG.md` includes a `v0.3.0` entry, and
- any conceptual mismatch EN vs ES is recorded as **Substantive divergence** (or “None” explicitly).

## Compatibility note
- Pre-1.0 releases: treat invariants **I1–I6** and glossary IDs **G#** as the stable reference surface from this release onward.
- Downstream repos should reference core-03 invariants when specifying apparatus compliance in methods/domains.

## Known limitations
- This release is structural and normative; it does not provide domain-specific implementations (law/education/finance), which belong in domain repos.
- Contestability and logging create real tensions (privacy, operational security, adversarial misuse). These are flagged as design constraints, not solved definitively here.

## Next steps (recommended)
1) Freeze `es-snapshots/v0.3.0/` and finalize `TRANSLATION_LOG.md` entry for `v0.3.0`.
2) Run T1–T6 on at least one representative workflow (human+AI mediated decision).
3) Publish GitHub Release `v0.3.0` using these notes and linking/pointer to `es-snapshots/v0.3.0/`.
