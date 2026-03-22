# Documented Assumptions

**Repository:** QLCM · STP Interference Experiment
**Last updated:** 2026-03-22
**Maintained by:** Osmary Lisbeth Navarro Tovar · Sheldon K. Salmon

---

## Purpose

This document records every assumption the experiment rests on — explicitly and permanently. An assumption is any claim we are treating as true for the purposes of running the experiment, without having proven it within this experiment itself.

Undocumented assumptions are epistemic debt. This file exists to make that debt visible.

Any observation that challenges an assumption listed here should reference this document by assumption ID (e.g. `A-001`) in the relevant issue.

---

## QLCM Framework Assumptions

### A-001 — Language operates as a quantum-like field
**Claim:** Linguistic communication exhibits quantum-like properties — superposition, entanglement, and non-locality — at the semantic level.
**Status:** [S] Strategic — foundational to QLCM, under active theoretical development since 2016
**Source:** Osmary Lisbeth Navarro Tovar, QLCM (2016–present)
**Implication for experiment:** If false, Ei has no meaningful interpretation and the experiment produces noise rather than signal.
**Falsification condition:** A demonstration that Ei scores are uncorrelated with any measurable semantic property across a sufficient sample.

---

### A-002 — Ei is a stable and reproducible metric
**Claim:** The Ei (entanglement index) measurement produces consistent results when applied to the same logon under the same conditions by the same or different evaluators.
**Status:** [?] Unverified — inter-rater reliability has not been formally tested in this experiment
**Source:** QLCM methodology
**Implication for experiment:** If Ei is not reproducible, changes in Ei before and after sealing cannot be attributed to the seal — they may be measurement variance.
**Falsification condition:** Two independent Ei measurements of the same logon under the same conditions producing significantly different scores.
**Open question:** What is the acceptable variance range for Ei to be considered stable?

---

### A-003 — QLCM operators produce distinct and measurable effects
**Claim:** ÓC (coherence), ÓN (non-locality), and ÓD (dimension) produce distinguishable effects on a logon's Ei score.
**Status:** [R] Reasoned — derived from QLCM theoretical framework
**Source:** Osmary Lisbeth Navarro Tovar, QLCM operator definitions
**Implication for experiment:** If operators are not distinguishable in their effects, operator choice cannot be used as a controlled variable.
**Falsification condition:** Ei scores showing no statistically significant difference across operator types when applied to the same logon.

---

### A-004 — A logon can be meaningfully isolated as a unit
**Claim:** A single word, phrase, or concept can function as a discrete semantic unit (logon) for the purposes of Ei measurement.
**Status:** [R] Reasoned
**Source:** QLCM logon theory
**Implication for experiment:** If meaning is always contextual and cannot be isolated, Ei measurements on discrete logons may not be valid.
**Open question:** What criteria determine whether a candidate logon is well-formed for this experiment?

---

## STP / AION Framework Assumptions

### A-005 — SHA-256 sealing constitutes a meaningful semantic event
**Claim:** The act of cryptographic sealing — computing a deterministic hash of semantic content and anchoring it in a public ledger — is not merely technical. It constitutes a meaningful act in the semantic field of the content being sealed.
**Status:** [?] Unverified — this is the core hypothesis of the experiment, not a proven claim
**Source:** Sheldon K. Salmon, STP / AION Constitutional Stack
**Implication for experiment:** If false — if sealing is purely technical with no semantic dimension — then Ei will not change and H₀ will be confirmed. That is a valid result.
**Falsification condition:** Ei showing no change across a sufficient number of sealed runs.

---

### A-006 — The STP seal is deterministic and stable
**Claim:** The same semantic content, sealed at the same moment, always produces the same SHA-256 hash. The seal does not vary.
**Status:** [D] Data — verified. FROZEN-2.0 stamp function has 35 passing checks.
**Source:** STP FROZEN-2.0 specification and test suite
**Implication for experiment:** The seal itself introduces no variance. Any change in Ei is attributable to the semantic event of sealing, not to randomness in the seal computation.

---

### A-007 — The triple-time stamp does not alter the semantic content
**Claim:** Adding Gregorian, Hebrew, and Dreamspell timestamps to the sealed record does not change the meaning of the logon being sealed.
**Status:** [R] Reasoned
**Source:** STP architecture
**Implication for experiment:** If timestamps alter semantic content, the Ei change could be attributed to temporal anchoring rather than cryptographic sealing.
**Open question:** This is worth discussing with Osmary — QLCM may have a view on whether temporal anchoring constitutes a semantic operation.

---

## Shared / Methodological Assumptions

### A-008 — The two frameworks are measuring compatible phenomena
**Claim:** QLCM's Ei and STP's seal operate on the same semantic substrate — that the "meaning" QLCM measures and the "content" STP seals are the same thing.
**Status:** [?] Unverified — this is the deepest assumption in the experiment
**Source:** Both frameworks
**Implication for experiment:** If the frameworks are operating on different definitions of semantic content, the interference signal may be an artefact of incompatible measurement rather than genuine interaction.
**Falsification condition:** Ei showing consistent, non-random changes that correlate with sealing — this would suggest the frameworks share a substrate.

---

### A-009 — A single logon is sufficient to produce a detectable signal
**Claim:** The interference signal (if it exists) is detectable with a minimal experimental unit — one logon, one operator, one seal.
**Status:** [?] Unverified — statistical power unknown at this stage
**Source:** Experimental design
**Implication for experiment:** Early runs are exploratory. A single run is not sufficient to confirm or deny the hypotheses. Multiple runs across different logons and operators are required for any conclusion.
**Note:** This assumption will be revisited after the first five runs.

---

### A-010 — No forced fusion is required for the experiment to be valid
**Claim:** The experiment can produce meaningful results without merging QLCM and STP into a unified framework. Observation of interference does not require the frameworks to agree on definitions.
**Status:** [D] Data — structural decision confirmed by both participants
**Source:** Experiment founding agreement, March 2026
**Implication for experiment:** Results are interpreted within each framework's own terms first. Cross-framework interpretation is secondary and clearly labelled.

---

## Assumption Status Key

| Tag | Meaning |
|-----|---------|
| [D] | Data — directly observed, measured, or formally verified |
| [R] | Reasoned — logically derived from verified evidence |
| [S] | Strategic — directional claim under active development |
| [?] | Unverified — open question, contested, or untested |

---

## Revision Log

| Date | Change | Filed by |
|------|--------|----------|
| 2026-03-22 | Initial version — 10 assumptions documented | Sheldon K. Salmon · ALBEDO |

---

*This document is a living record. New assumptions discovered during runs should be added here immediately, before they become invisible.*

