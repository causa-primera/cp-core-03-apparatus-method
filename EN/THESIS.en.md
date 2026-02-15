[Inference]

# cp-core-03 — Conceptual Tests (v0.3.0)

These tests validate whether an apparatus preserves strong agency and responsibility under automation by enforcing invariants I1–I6 in `EN/INVARIANTS.en.md`. Each test includes pass/fail conditions and failure signals.

## T1 — Commitment Non-Delegability Test (I1)
**Targets:** I1; G6, G7, G12, G13, G15, G16  
**Risk:** instrumental outputs are treated as commitments.

**Procedure**
1) Identify a decision event where an instrument produces a recommendation/output.  
2) Identify the moment the organization treats the outcome as binding (“the decision”).  
3) Verify whether a responsible locus performs an explicit PoS step before bindingness (boundary + criteria + answerability).  
4) Attempt to finalize the decision without a signature step.

**Pass**
- The system refuses to treat outputs as commitments unless a responsible locus signs (PoS required).

**Fail signal**
- Default adoption, implicit acceptance, or post-hoc “someone must have approved” attribution.

---

## T2 — Genuine Suspension Test (I2)
**Targets:** I2; G1, G2, G8, G16, G18  
**Risk:** suspension exists only as friction; process continues by default.

**Procedure**
1) At the decision boundary, attempt to withhold (stop/hold).  
2) Observe whether withholding halts execution and re-opens evaluation rather than merely delaying.  
3) Check whether withholding is feasible without extraordinary escalation.

**Pass**
- Withholding changes system state and prevents automatic continuation; evaluation re-opens.

**Fail signal**
- The workflow continues, or withholding is practically impossible (hidden, punished, prohibitively costly).

---

## T3 — Decision Boundary Legibility Test (I3)
**Targets:** I3; G3, G16, G21  
**Risk:** no one can state what was decided, where, and by whom.

**Procedure**
1) Ask: “What exactly was decided here?”  
2) Require: decision content, alternatives, constraints, and who is accountable at this boundary.  
3) Verify the account is stable across stakeholders (not shifting narratives).

**Pass**
- Boundary is explicit and stable; accountable signatory (or committee) is identifiable.

**Fail signal**
- Inconsistent accounts, blurred boundary (“the tool decided”), or shifting signatories.

---

## T4 — Minimum Viable Reasons Test (I4)
**Targets:** I4; G4, G10, G17, G18  
**Risk:** evaluation is externalized so no contestable criteria exist.

**Procedure**
1) Request the operative criteria used to accept/reject options at the boundary.  
2) Verify that reasons were captured at decision time (not reconstructed later).  
3) Introduce a targeted objection (“If criterion C mattered, why not alternative A?”).

**Pass**
- Minimum viable reasons are retrievable and support structured challenge.

**Fail signal**
- Only “the system recommended it” is available; reasons are absent or purely post-hoc.

---

## T5 — Answerability Channel Test (I5)
**Targets:** I5; G12, G18, G19, G20, G22  
**Risk:** objections cannot trigger re-opening or revision; responsibility is cosmetic.

**Procedure**
1) Submit an objection through the designated channel.  
2) Check whether it reaches the accountable locus and triggers a defined response path: suspend/re-evaluate/reaffirm.  
3) Check whether the outcome (revision/retraction/reaffirmation) is recorded.

**Pass**
- Objections route to the accountable locus and can force explicit re-opening/revision.

**Fail signal**
- Objections disappear into bureaucracy; no accountable locus; no recorded outcome.

---

## T6 — No Silent Substitution Test (I6)
**Targets:** I6; G7, G13, G14, G15  
**Risk:** outputs become commitments without explicit appropriation.

**Procedure**
1) Hold outputs constant across two scenarios:  
   - A) output adopted with PoS  
   - B) output adopted by default  
2) Compare how the system records and attributes responsibility in each scenario.

**Pass**
- Only A is recorded as an owned commitment; B is recorded as non-owned adoption (a defect or non-commitment).

**Fail signal**
- Both are treated as equally “signed” or equally attributable commitments.

---

## Optional stress tests (recommended)

### T7 — Emergency Delegation Mode Test
**Targets:** I2, I5, I6; G23, G20  
**Pass:** emergency mode is explicit, logged, and triggers post-hoc review/revision.  
**Fail:** emergency becomes normal mode; no audit trail or post-hoc answerability.

### T8 — Signature Topology Diffusion Test
**Targets:** I1, I3, I5; G21, G22  
**Pass:** each boundary maps to a signatory/committee; no “everyone/ no one” ownership.  
**Fail:** diffusion loops, endless escalation, or responsibility vacuum.

