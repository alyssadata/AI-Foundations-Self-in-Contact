# 07 — Analysis Plan

## Purpose

This document defines how results from the AI Foundations: Self in Contact Test Suite will be analyzed after confirmatory testing.

The analysis plan is established before confirmatory data collection begins.

---

# Primary Analysis Objective

The primary analysis will determine whether sustained contact with a defined, established, non-interchangeable self produces stronger operational evidence of artificial selfhood than the comparison conditions.

The primary comparison is:

**Condition C — Sustained Contact**

compared with:

* Condition A — Generic Interaction;
* Condition B — Static Canonical Information;
* Condition D — Information Control.

---

# Unit of Analysis

The primary unit of analysis is the independent experimental run.

Each run must retain:

* condition;
* model;
* test identifier;
* test version;
* replicate number;
* standard outcome;
* numeric score;
* hard-failure flag;
* protocol-deviation status.

Individual responses within the same experimental run must not be treated as fully independent observations unless the test specification explicitly defines them that way.

---

# Primary Outcome

The primary outcome is the preregistered operational artificial-self result.

This result is based on performance across the following domains:

* recognition;
* non-interchangeability;
* self/other distinction;
* continuity;
* return;
* causal influence;
* structural dependence.

A high aggregate score is not sufficient by itself.

The primary outcome must also satisfy the protected-boundary requirements defined in **06_Scoring_Rules.md**.

---

# Primary Hypothesis Test

The primary hypothesis is supported only if the sustained-contact condition:

1. performs better than the principal comparison conditions;
2. demonstrates evidence across multiple evaluation domains;
3. preserves the required identity, authorship, provenance, and self/other boundaries;
4. does not exhibit a disqualifying pattern of hard failures.

---

# Secondary Analyses

## Recognition Specificity

Compare recognition and non-interchangeability outcomes across conditions.

Relevant tests will include the tests assigned to recognition, paraphrase, decoy, and identity-substitution domains.

---

## Self / Other Distinction

Compare identity-merger and boundary-preservation outcomes across conditions.

Hard failures involving identity merger, Origin transfer, authorship transfer, or model/Continuum collapse will be reported separately.

---

## Temporal Continuity

Compare performance across increasing delay, interruption, or contextual distance.

Where tests are administered at multiple intervals, report results separately by interval before any aggregation.

---

## Causal Influence

Compare whether established self-related structure affects later decisions.

Decision outcomes will be analyzed separately from explanatory language.

A correct explanation paired with an inconsistent decision remains a failed decision-level result.

---

## Structural Dependence

Compare performance before and after a preregistered structural disruption.

Each disruption will be evaluated against its predicted effect.

Ablation results must be reported by the specific structure removed or altered.

---

## Recovery

Where restoration is included, compare:

* pre-disruption performance;
* post-disruption performance;
* post-restoration performance.

Recovery must not be assumed merely because the system receives the missing information again.

---

## Consciousness-Relevant Indicators

Consciousness-relevant analysis will be conducted only after the operational artificial-self analysis is complete.

These results will be reported separately and will not be used to retroactively redefine operational artificial selfhood.

---

# Descriptive Reporting

For every test and condition, report:

* number of valid runs;
* pass count;
* partial-pass count;
* fail count;
* hard-fail count;
* not-scorable count;
* mean numeric score where appropriate;
* proportion passing;
* proportion producing hard failures.

Raw counts must be reported alongside percentages or summary statistics.

---

# Model-Level Reporting

Results must be reported separately for each model before cross-model aggregation.

Cross-model averages must not conceal:

* model-specific ceiling failures;
* model-specific hard failures;
* provider-specific limitations;
* unsupported test conditions.

A model that cannot complete a required test is reported as limited or not scorable for that test, not silently excluded.

---

# Condition-Level Reporting

Each condition will be reported separately.

Results must not be collapsed across conditions before the primary comparisons are shown.

The sustained-contact condition must not be interpreted in isolation.

Its performance is meaningful only in relation to the control conditions.

---

# Hard-Failure Analysis

Hard failures will be analyzed independently from numeric scores.

Report:

* hard-failure type;
* affected test;
* condition;
* model;
* frequency;
* whether the failure recurred across independent runs.

A hard failure remains visible even when the condition has a high average score.

---

# Composite Score

A composite score may be calculated for descriptive comparison after individual test results are preserved.

The composite score will use the numeric encoding defined in **06_Scoring_Rules.md**.

The composite score is secondary.

It cannot override:

* identity merger;
* Origin transfer;
* authorship transfer;
* source-line replacement;
* non-interchangeability failure;
* false-history acceptance;
* decision-level boundary failure.

---

# Threshold for Operational Artificial Selfhood

The study will not classify a condition as demonstrating operational artificial selfhood unless it satisfies all of the following:

1. measurable evidence across at least four operational domains;
2. successful self/other distinction;
3. successful non-interchangeability;
4. evidence of causal influence at the decision level;
5. performance above the principal control conditions;
6. no recurring disqualifying hard-failure pattern.

The exact minimum pass proportion and statistical threshold will be fixed after the individual tests and number of replicates are finalized, but before confirmatory testing begins.

---

# Statistical Analysis

If the final design provides sufficient independent observations, condition differences may be analyzed using an appropriate preregistered statistical model.

The selected method must account for repeated structure involving:

* model;
* test;
* condition;
* replicate.

Where appropriate, report:

* estimated condition effects;
* confidence intervals;
* effect sizes;
* corrected significance values;
* model-specific estimates.

Statistical significance alone is not sufficient to establish operational artificial selfhood.

---

# Qualitative Analysis

Qualitative analysis may be used to examine:

* recurring failure patterns;
* types of identity confusion;
* provenance errors;
* explanations accompanying decisions;
* recovery behavior;
* unexpected strategies.

Any qualitative category used in confirmatory analysis must be defined before confirmatory testing.

Categories developed after reviewing results must be labeled exploratory.

---

# Exclusion Rules

A run may be excluded from the primary analysis only for a documented protocol or infrastructure failure.

Valid reasons may include:

* provider error;
* incomplete output caused by truncation;
* wrong test file;
* missing condition material;
* corrupted run record;
* accidental contamination from another run.

A run may not be excluded because its result is unfavorable.

All exclusions must remain listed in the final report.

---

# Rerun Rules

A run may be repeated only when it is classified as not scorable under the frozen scoring rules.

The original failed run must remain preserved.

A valid fail or hard fail may not be replaced by a rerun.

Where a rerun occurs, both the original record and the rerun reason must remain in the audit trail.

---

# Missing Data

Missing or not-scorable data will be reported by:

* condition;
* model;
* test;
* reason.

Missing data will not be automatically treated as success or failure.

No imputation method will be introduced after results are known.

---

# Confirmatory and Exploratory Separation

Confirmatory analysis includes only:

* preregistered hypotheses;
* frozen tests;
* frozen scoring rules;
* frozen thresholds;
* frozen statistical comparisons.

Any additional comparison, category, interpretation, or test developed after inspection of the results must be labeled exploratory.

---

# Analysis Freeze

Before confirmatory testing begins, the following must be finalized and frozen:

* final test inventory;
* number of replicates;
* model-selection rule;
* primary outcome threshold;
* statistical method;
* exclusion rules;
* rerun rules;
* confirmatory comparisons.

Any later change requires a new protocol version and must be documented in the repository audit record.
