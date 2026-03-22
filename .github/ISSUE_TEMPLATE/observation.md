---
name: "Observation"
about: "Log an open finding, anomaly, or question from the experiment — does not require a completed run"
title: "[OBS] <brief description>"
labels: ["observation", "open"]
assignees: ""
---

## Observation

**Date:** <!-- YYYY-MM-DD -->
**Filed by:** <!-- Osmary / Sheldon -->
**Related run:** <!-- Issue #N / None -->

---

## What Was Observed

<!-- Describe the observation clearly. What happened? What was unexpected? -->

---

## Context

**Stage when observed:**
- [ ] Before logon seeding
- [ ] During operator application (QLCM phase)
- [ ] During Ei measurement
- [ ] During STP sealing
- [ ] After sealing (post-seal Ei)
- [ ] During result interpretation
- [ ] Outside a formal run

**Framework involved:**
- [ ] QLCM
- [ ] STP / AION
- [ ] Both
- [ ] Neither / methodological

---

## Significance

**How significant is this observation?**
- [ ] Minor — note for the record, no action needed
- [ ] Moderate — worth discussing before the next run
- [ ] Major — may affect experiment design or interpretation
- [ ] Architectural — questions the assumptions of one or both frameworks

---

## Questions Raised

<!-- What questions does this observation open? What would need to be true for it to be explained? -->

---

## Proposed Next Step

<!-- Optional. What should happen next as a result of this observation? -->
<!-- e.g. adjust logon selection, re-run with different operator, revise assumption in docs/assumptions.md -->

---

## Assumptions Affected

<!-- If this observation challenges a documented assumption in docs/assumptions.md, list which one(s) -->

---
*This observation does not require a STP seal unless it contains a falsifiable claim that one or both parties wish to anchor permanently. Use the experiment-run template for sealed runs.*

