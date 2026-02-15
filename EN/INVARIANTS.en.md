# INVARIANTS.en.md — Apparatus & Method (v0.1)


This file defines **system invariants** for the Causa Primera apparatus/method.  
An invariant is a constraint such that **if it is violated, the apparatus stops tracking the target phenomenon** (agency, reason in the strict sense, and the boundary of externalization).

Each invariant includes: (i) statement, (ii) what violates it, (iii) what breaks if violated, (iv) a minimal conceptual test.

---

## I1 — No normativity without imputable commitment (Signature Invariant)

**Statement**  
A judgement counts as reason (strict sense) only if it can be **owned** as an imputable commitment (a normative signature), i.e., answerable to demands of justification, retraction, repair.

**Violations**  
- Treating “good outputs” as judgements without any locus of answerability.
- Collapsing responsibility into “the system said so” with no accountable author.

**What breaks**  
- The method becomes a theory of output production, not of agency/reason.
- Externalization becomes indistinguishable from abdication.

**Minimal test**  
Given an error/harm: can a non-metaphorical subject be asked to justify/retract/repair *as the author of the commitment*?

---

## I2 — Suspension is constitutive (Non-Automaticity Invariant)

**Statement**  
Agency (strong sense) requires **genuine suspension**: the capacity to withhold endorsement and open a normative question (“should I?”) rather than following automatic continuation.

**Violations**  
- Replacing suspension with mere delay, hesitation, or a different automatic branch.
- Interpreting “uncertainty” (information deficit) as suspension.

**What breaks**  
- The apparatus cannot distinguish deliberation from sophisticated automaticity.
- The boundary of externalization loses its principled anchor.

**Minimal test**  
In a context with strong pressure to proceed, can the agent *withhold* specifically because endorsement is not yet justified (not because it lacks data or is blocked)?

---

## I3 — Evaluation requires a correctness-apt criterion (Criterion Invariant)

**Statement**  
Evaluation is not mere preference or optimization; it is selection under a **correctness-apt criterion** that can be invoked in justification and contested.

**Violations**  
- Treating scalar reward/performance as sufficient without any correctness claim.
- Using post-hoc rationalizations that do not constrain future judgements.

**What breaks**  
- “Reasons” collapse into “causes” (or into “works for me”), and the argument map becomes non-auditable.
- The apparatus cannot support disagreement, revision, or standards.

**Minimal test**  
Can the criterion be stated so that (a) another party can challenge it, and (b) the agent accepts that the challenge bears on correctness, not only on preference?

---

## I4 — Externalization boundary is normative, not technical (Boundary Invariant)

**Statement**  
The externalization boundary is defined by **normative role**, not by capability level.  
Operations may be externalized (search, drafting, simulation, enumeration), but **signature/commitment and ultimate criterion-choice** cannot be externalized without agency loss.

**Violations**  
- Defining the boundary by “current AI limitations” or by benchmark performance.
- Treating tool outputs as commitments without human signature.

**What breaks**  
- The system becomes temporally fragile (“AGI changes everything” becomes a refutation).
- The project degenerates into a moving commentary on technology rather than a stable theory of agency.

**Minimal test**  
If an external system becomes arbitrarily capable tomorrow, would your criterion for “who owns the commitment” remain unchanged? If not, the boundary is technical, not normative.

---

## I5 — No silent redefinition across layers (Coherence Invariant)

**Statement**  
Core terms (freedom, suspension, evaluation, commitment/signature, imputability, reason strict) must remain **definitionally stable** across Core-01 (transcendental argument), Core-03 (apparatus/method), and downstream domains. Any change must be explicit and versioned.

**Violations**  
- Shifting “commitment” from normative signature to mere confidence.
- Letting “evaluation” drift into statistical preference without correctness.
- Using “agency” sometimes behaviorally and sometimes normatively without warning.

**What breaks**  
- The apparatus ceases to be a reusable method; domains become ad hoc essays.
- Internal contradictions proliferate without detection.

**Minimal test**  
Take any downstream use of a core term: can you point to the same controlled definition and show that the downstream argument depends on it (and does not smuggle a new meaning)?

---

## I6 — Defeat conditions must remain live (Non-Dogmatism Invariant)

**Statement**  
The method must specify **conditions of defeat** (what would force revision) for its central claims, and those defeat conditions must not be neutralized by ad hoc moves.

**Violations**  
- Defining “agency” so that nothing could ever count against it.
- Treating all counterexamples as “not relevant by definition” without principled reason.

**What breaks**  
- The system becomes rhetorical rather than rationally assessable.
- Steelmanning becomes impossible, and the apparatus loses credibility even on its own terms.

**Minimal test**  
Can you state at least one plausible scenario that would require revising a core claim (e.g., signature without suspension), and can a critic in principle use it to argue?

---

## Maintenance rule (for releases)

- Any change to these invariants requires:
  1) a changelog entry,
  2) updated tests,
  3) an explicit note in TRANSLATION_LOG.md if the change is introduced during ES→EN release preparation.

Target for v0.2:
- Add 6–12 conceptual tests in `TESTS.en.md`, each mapped to one invariant.
