[Inference]

# cp-core-03 — Conceptual Tests (v0.3.0)

These tests validate whether an apparatus preserves responsibility under automation by enforcing invariants I1–I6 in `EN/INVARIANTS.en.md`.

## T1 — Commitment Non-Delegability Test (I1)
Pass: outputs are never treated as commitments without PoS.
Fail: default adoption or post-hoc attribution.

## T2 — Genuine Suspension Test (I2)
Pass: withholding halts execution and re-opens evaluation.
Fail: friction-only suspension; workflow continues.

## T3 — Decision Boundary Legibility Test (I3)
Pass: what/where/who is stable and explicit.
Fail: blurred boundary; shifting narratives.

## T4 — Minimum Viable Reasons Test (I4)
Pass: operative criteria are retrievable and contestable.
Fail: “the system recommended it” is the only reason.

## T5 — Answerability Channel Test (I5)
Pass: objections reach accountable locus and can force revision/reaffirmation.
Fail: objections disappear; no recorded outcome.

## T6 — No Silent Substitution Test (I6)
Pass: only PoS-governed adoption counts as owned commitment.
Fail: default and PoS adoption treated equivalently.
