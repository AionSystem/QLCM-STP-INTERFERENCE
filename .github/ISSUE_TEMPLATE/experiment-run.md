---
name: "Experiment Run"
about: "Log a completed, sealed QLCM · STP interference experiment run"
title: "[RUN] <logon> — <operator> — <date>"
labels: ["experiment-run", "pending-seal"]
assignees: ""
---

## Experiment Run Log

**Run date:** <!-- YYYY-MM-DD -->
**Conducted by:** <!-- Osmary / Sheldon / Both -->

---

## Logon

> The semantic seed used in this run.

**Logon text:**
<!-- Paste the exact logon here -->

**Logon source:** <!-- seed-001 / custom / proposed by Osmary / proposed by Sheldon -->

---

## QLCM Phase

**Operator applied:** <!-- ÓC / ÓN / ÓD -->

**Pre-seal Ei measurement:**
<!-- Paste Osmary's Ei score here — e.g. 0.74 -->

**Measurement method:**
<!-- Brief description of how Ei was computed for this run -->

**Observations before sealing:**
<!-- Anything notable about the logon's behaviour under the operator before the seal was applied -->

---

## STP Seal Phase

**Seal applied:** <!-- Yes / No -->

**STP ledger issue number:** <!-- e.g. #12 — link to the sealed GitHub issue -->

**SHA-256 seal hash:**
<!-- Paste the seal hash here -->

**Seal timestamp (Gregorian):**
<!-- e.g. March 22, 2026 -->

**Seal timestamp (Hebrew):**
<!-- e.g. 22 Adar II 5786 -->

**Seal timestamp (Dreamspell):**
<!-- e.g. Day 16, Solar Moon 9/13 -->

---

## Post-Seal Measurement

**Post-seal Ei measurement:**
<!-- Paste Osmary's Ei score after sealing -->

**Ei delta (post − pre):**
<!-- Calculate: post-seal Ei minus pre-seal Ei -->

**Direction:** <!-- Increased / Decreased / No change / Qualitative change -->

---

## Interference Signal

**Result category:**
- [ ] H₀ — No measurable effect (Ei unchanged)
- [ ] H₁a — Ei increased (sealing as coherence-stabilising act)
- [ ] H₁b — Ei decreased (reduction of superposition on fixation)
- [ ] H₂ — Qualitative transformation (structure changed, scalar ambiguous)
- [ ] Inconclusive — insufficient data

**Observations:**
<!-- What did you observe? Unexpected results, anomalies, questions raised -->

---

## Documentation Checklist

- [ ] Logon text recorded exactly as used
- [ ] Pre-seal Ei recorded
- [ ] STP seal applied and ledger issue number confirmed
- [ ] Post-seal Ei recorded
- [ ] Ei delta calculated
- [ ] Result category selected
- [ ] Run added to `docs/experiment-log.md`
- [ ] Results file saved to `docs/results/run-<date>.md` (if applicable)

---

**Declaration:** I confirm that this run was conducted as documented, that the measurements were recorded honestly, and that no post-hoc adjustment has been made to the pre-seal Ei figure.

- [ ] Confirmed

