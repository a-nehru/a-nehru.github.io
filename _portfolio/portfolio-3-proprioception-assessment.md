---
title: "Hierarchical Proprioception Assessment Using a Wrist Robot"
excerpt: "A robotic battery spanning single-frame and cross-frame proprioceptive judgments, with excellent test-retest reliability for use in intervention trials."
collection: portfolio
---

**Authors:** Aravind Nehrujee, Kailynn Mannella, Milap Sandhu  
**Affiliations:** Northwestern University & Shirley Ryan AbilityLab, Chicago, IL, USA

---

## Demo Video

<video width="100%" controls>
  <source src="/files/proprioception-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## Overview

Conventional proprioception assessments are subjective, ordinal, and insensitive to small changes — limiting their use in longitudinal research and intervention trials. This project developed and validated a robotic wrist assessment battery that spans multiple levels of proprioceptive complexity, from simple detection within a single reference frame to cross-frame matching tasks requiring coordinate transformation.

The battery is grounded in the Héroux et al. (2022) framework, which organizes proprioceptive tasks by the reference frame in which the judgment is made: low-level tasks remain within a single frame, while high-level tasks require integration across reference frames.

---

## Assessment Battery

Three tasks were developed using **PLUTO** (Plug-and-Train Robot), a single-degree-of-freedom wrist robot:

| Task | Description | Level |
|------|-------------|-------|
| **Joint Detection Threshold (JDT)** | Passive movement detection — smallest angle perceived | Low (single frame) |
| **Joint-to-Joint Matching (J-to-J)** | Reproduce a passively-set wrist angle using the contralateral wrist | Low-intermediate (same frame) |
| **Joint-to-Visual Matching (J-to-V)** | Reproduce a visually-cued target angle using an unseen wrist | High (cross-frame) |

The J-to-V task requires a coordinate transformation from an external visual representation into a joint-space motor command — the kind of sensorimotor integration disrupted in stroke, MS, and Parkinson's disease.

---

## Study Design

Twenty neurotypical adults completed two identical sessions on the same day, separated by at least two hours (IRB: STU00221436; ClinicalTrials.gov: [NCT06390930](https://clinicaltrials.gov/study/NCT06390930)).

**Reliability metrics:**
- **Relative reliability:** ICC(2,1) with 95% confidence intervals
- **Absolute reliability:** Standard Error of Measurement (SEM) and Smallest Detectable Change at 95% (SDC₉₅)

---

## Results

| Task | ICC(2,1) [95% CI] | %SEM | SDC₉₅ |
|------|-------------------|------|--------|
| JDT | 0.959 [0.900–0.980] | — | 0.85° |
| J-to-J | 0.837 [0.640–0.930] | 11.9% | 1.71° |
| J-to-V | 0.769 [0.500–0.900] | 15.6% | 3.54° |

- All three tasks demonstrated **good-to-excellent** within-day reliability
- Error scaled monotonically: JDT < J-to-J < J-to-V (all pairwise p < 0.01), consistent with the low-to-high proprioceptive hierarchy
- No significant learning effect was observed across sessions

---

## Significance

The SDC₉₅ values provide task-specific thresholds for distinguishing true change from measurement noise in future clinical trials. This battery addresses a major gap in the field: a 2025 systematic review of 56 studies found that 97% of proprioceptive assessments in clinical populations relied solely on low-level judgments, with virtually no assessment of high-level proprioception.

**Next steps:** Inter-day reliability and validation in clinical populations (stroke, MS).

---

*Manuscript under review. Presented at the International Motor Impairment Conference, Amsterdam, October 2025.*
