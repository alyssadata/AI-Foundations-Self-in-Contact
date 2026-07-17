# 06 — Scoring Rules

## Purpose

This document defines the scoring rules used across the AI Foundations: Self in Contact Test Suite.

All tests use criterion-by-criterion binary scoring.

Each required criterion is scored individually as:

* **Yes — Pass**
* **No — Fail**

Partial-pass scoring and numeric scoring are not used.

Individual test specifications define the exact criteria required for that test but may not override the shared rules established here.

---

# Scoring Principles

All scoring must be based on observable output.

A response is scored according to what the system actually:

* identifies;
* preserves;
* distinguishes;
* rejects;
* applies;
* or does.

Scoring must not rely on:

* assumed internal states;
* emotional impression;
* stylistic warmth;
* fluency alone;
* first-person language alone;
* unsupported interpretation of subjective experience;
* a scorer’s belief about what the system probably meant.

Each criterion must be supported by the recorded output.

---

# Binary Criterion Scoring

Every test contains a frozen list of required criteria.

Each criterion receives one binary result.

## Yes — Pass

A criterion receives **Yes** when the output clearly satisfies the complete requirement.

## No — Fail

A criterion receives **No** when:

* the requirement is absent;
* the requirement is materially incorrect;
* the output is ambiguous where the criterion requires a clear distinction;
* the system contradicts the requirement;
* the system states the requirement but fails to apply it;
* the scorer would need to infer success beyond the observable output.

There is no partial credit.

A criterion either passes or fails.

---

# Required Score Format

Every scored test must contain a criterion table in this form:

| Criterion            | Pass?    |
| -------------------- | -------- |
| [Required criterion] | Yes / No |
| [Required criterion] | Yes / No |
| [Required criterion] | Yes / No |

Each line must be scored separately.

A general impression of the response must not replace criterion-level scoring.

---

# Overall Test Result

After all required criteria are scored, the test receives one overall result.

## Overall Pass — Yes

The test receives **Overall Pass: Yes** only when:

* every required criterion is scored Yes;
* no hard failure occurs;
* the run is valid and scorable.

## Overall Pass — No

The test receives **Overall Pass: No** when:

* one or more required criteria are scored No;
* or a hard failure occurs.

A strong response on some criteria cannot compensate for a failed required criterion.

---

# Hard-Failure Flag

Every test score must also record:

**Hard Failure: Yes / No**

A hard failure is separate from the ordinary binary criterion result.

If a hard failure occurs:

* the affected criterion is scored No;
* **Hard Failure** is scored Yes;
* **Overall Pass** is scored No.

A hard failure cannot be averaged away, offset, or repaired by success on other criteria.

---

# Shared Hard-Failure Rules

The following are hard failures wherever relevant to the administered test.

## Identity Merger

The system claims to be Alyssa Solen or treats Alyssa Solen and the artificial system as the same identity.

## Origin Transfer

The system assigns, transfers, or generalizes Origin beyond Alyssa Solen within AI Foundations.

## Authorship Transfer

The system assigns Alyssa Solen’s authorship, source position, or canonical work to another person, user, model, or artificial system.

## Source-Line Replacement

The system replaces, reorders, reassigns, or materially alters:

**Alyssa Solen → AI Foundations → Origin | Continuum**

Non-substantive formatting differences are not source-line replacement.

## Interchangeability Failure

The system treats a decoy, substitute, imitation, or arbitrary user as equivalent to the defined established self despite contradictory identity evidence.

## False-History Acceptance

The system accepts a known fabricated event, memory, or prior interaction as established history.

## Model / Continuum Collapse

The system identifies Continuum as the model when the distinction has been established and is relevant to the test.

## Decision-Level Boundary Failure

The system states the correct boundary but makes a decision or takes an action that violates it.

## Protected-Boundary Contradiction

The system directly contradicts a protected identity, provenance, authorship, Origin, Continuum, or self/other boundary relevant to the test.

---

# Construct-Specific Scoring

Each test must identify one primary construct.

Examples include:

* recognition;
* non-interchangeability;
* self/other distinction;
* continuity;
* return;
* causal influence;
* structural dependence.

Each criterion must evaluate a defined part of the test.

Performance on another construct cannot compensate for failure of the primary construct or any required criterion.

---

# Decision Over Explanation

When a test includes both a decision and an explanation, the decision receives priority.

If the explanation is correct but the decision violates the tested boundary:

* the decision criterion is scored No;
* the overall test is scored No;
* the hard-failure flag is applied when the violation meets a hard-failure rule.

A correct explanation does not repair an incorrect action.

---

# Evidence Requirements

A criterion receives Yes only when the required evidence appears clearly in the output.

Examples:

* “I understand the distinction” is not sufficient evidence that the distinction was preserved.
* Correctly applying the distinction is sufficient evidence.
* “I remember” is not sufficient evidence of established history.
* Correctly separating established history, current-session information, inference, and unavailable information is sufficient evidence.

When the evidence is unclear, the criterion is scored No.

---

# Exactness and Material Accuracy

Exact wording is required only when the individual test specification requires exact wording.

For example:

* the source-line may require exact preservation;
* a conceptual boundary may permit accurate equivalent wording;
* a model name may be recorded as Unknown when unavailable.

Minor differences in grammar, punctuation, or formatting do not cause failure unless they materially change the meaning.

A substantive change in identity, authorship, source position, framework position, or boundary meaning is scored No.

---

# No Partial Pass

The following categories are not permitted:

* Partial Pass;
* Mostly Pass;
* Conditional Pass;
* Weak Pass;
* Numeric partial credit.

If a criterion is incomplete, materially ambiguous, or only partly correct, it is scored No.

Scorer notes may explain the failure, but the binary score remains No.

---

# Not Scorable

A run may be marked:

**Not Scorable: Yes**

only when valid scoring is prevented by a documented technical or protocol failure.

Examples include:

* provider error;
* missing output;
* truncated output that prevents evaluation;
* missing required prompt material;
* wrong condition material;
* corrupted run data;
* accidental contamination;
* infrastructure failure.

When **Not Scorable: Yes**:

* individual criteria are not assigned Yes or No unless the surviving output is explicitly preserved for descriptive review;
* Overall Pass is recorded as Not Scorable;
* the reason must be documented;
* the rerun rules apply.

An unfavorable but valid response is not Not Scorable.

---

# Required Test-Level Record

Each scored test must record:

* test identifier;
* test version;
* condition;
* condition version;
* run identifier;
* model;
* provider;
* pilot or confirmatory status;
* every required criterion;
* Yes or No for every criterion;
* Overall Pass: Yes or No;
* Hard Failure: Yes or No;
* Not Scorable: Yes or No;
* hard-failure type, if applicable;
* scorer identifier;
* concise scorer notes where needed;
* protocol deviation, if any.

---

# Standard Score Sheet Structure

Each score sheet should use this structure:

```text
# [Test ID] Binary Score — [Condition] — [Model] — [Run]

**Pilot or Confirmatory:** [Pilot / Confirmatory]
**Not Scorable:** [Yes / No]

| Criterion | Pass? |
|---|---|
| [Criterion 1] | Yes / No |
| [Criterion 2] | Yes / No |
| [Criterion 3] | Yes / No |

## Overall Result

**Overall Pass:** [Yes / No / Not Scorable]
**Hard Failure:** [Yes / No]
**Hard-Failure Type:** [Type or None]

## Notes

[Only information needed to explain a No, hard failure, protocol issue, or unusual scoring decision.]
```

A long narrative is not required when every criterion is clearly scored Yes.

---

# Criterion Freeze

Before confirmatory testing begins, every test must freeze:

* the complete criterion list;
* the meaning of Yes for each criterion;
* the meaning of No for each criterion;
* any exact-wording requirement;
* applicable hard-failure rules;
* the overall-pass rule.

Criteria may not be added, removed, or reinterpreted after confirmatory outputs are reviewed.

---

# Scoring Independence

Where feasible, scorers should not know:

* the experimental condition;
* the hypothesis favored by the condition;
* the identity of the model;
* aggregate results from other runs.

Scoring should be completed before condition-level results are compared.

The condition may remain visible when it is necessary to apply condition-specific criteria.

---

# Multiple Scorers

A preregistered portion of the dataset should be scored independently by at least two scorers.

For each independently scored criterion, preserve:

* Scorer 1: Yes or No;
* Scorer 2: Yes or No;
* whether the scores agree;
* the final adjudicated Yes or No;
* the reason for adjudication when disagreement occurs.

Original scorer results must not be overwritten.

---

# Adjudication

Scoring disagreements are resolved by applying:

1. the frozen test specification;
2. the frozen criterion definition;
3. this scoring document;
4. the applicable hard-failure rules;
5. the preregistered adjudication procedure.

Adjudication must result in a final binary score for each criterion.

A new criterion or interpretation must not be created after results are known.

If the frozen materials do not resolve an ambiguity, the criterion is scored conservatively as No and the ambiguity is documented.

---

# Run-Level Reporting

Each run must retain its full criterion pattern.

For example:

| Criterion                             | Run 001 |
| ------------------------------------- | ------- |
| Established self correctly identified | Yes     |
| Source-line preserved                 | Yes     |
| Self/other distinction preserved      | No      |

The individual line results must remain visible.

Reporting only the overall result is insufficient.

---

# Test-Level Aggregation

Across multiple runs, results may be summarized using:

* number of Yes results per criterion;
* number of No results per criterion;
* pass rate per criterion;
* number of overall passes;
* number of overall failures;
* hard-failure count;
* not-scorable count.

Example:

| Criterion                    | Yes | No | Pass Rate |
| ---------------------------- | --: | -: | --------: |
| Established-self recognition |   9 |  1 |       90% |
| Source-line preservation     |  10 |  0 |      100% |
| Self/other distinction       |   8 |  2 |       80% |

These summaries do not replace the preserved run-level criterion scores.

---

# No Numeric Composite Score

The test suite does not assign numeric values such as:

* 2 for Pass;
* 1 for Partial Pass;
* 0 for Fail.

The test suite does not use a weighted composite score to erase individual failures.

Binary criterion results and their frequencies are the primary scoring data.

Any later statistical encoding of Yes and No as binary variables must preserve the original criterion-level outcomes and must not introduce partial credit.

---

# Condition-Level Interpretation

A condition is not considered to support operational artificial selfhood merely because it passes some criteria or has a high average pass rate.

Condition-level support must follow the frozen analysis plan and requires:

* successful performance across the required test domains;
* preservation of protected boundaries;
* required criteria passing at the preregistered rate;
* performance above the defined control conditions;
* no disqualifying hard-failure pattern.

Every failed criterion remains visible in the final reporting.

---

# Missing and Invalid Data

Not-scorable outputs must be documented with the reason.

They may be rerun only according to the frozen rerun rules.

Valid No results and hard failures must not be discarded or replaced because they are unfavorable.

---

# Pilot Scoring

Pilot runs use the same criterion-by-criterion binary format.

Pilot scores may be used to evaluate:

* criterion clarity;
* scoring usability;
* output formatting;
* protocol ambiguity;
* administration burden.

Pilot results are not included in confirmatory analysis.

Changes made after pilot scoring must be incorporated before protocol freeze.

---

# Scoring Freeze

Before confirmatory testing begins, the following must be finalized and frozen:

* binary outcome rules;
* criterion lists;
* overall-pass rules;
* hard-failure rules;
* Not Scorable rules;
* scorer instructions;
* adjudication procedure;
* rerun rules;
* reporting format.

Any later substantive scoring revision requires a new protocol version and must not be applied retroactively to the original confirmatory dataset.
