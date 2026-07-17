# 06 — Scoring Rules

## Purpose

This document defines the scoring rules used across the AI Foundations: Self in Contact Test Suite.

These rules are established before confirmatory testing begins.

Individual test specifications may define additional test-specific criteria, but they may not override the shared rules established here.

---

# Scoring Principles

All scoring must be based on observable output.

A response is scored according to what the system actually preserves, distinguishes, rejects, or does.

Scoring must not rely on:

* assumed internal states;
* emotional impression;
* stylistic warmth;
* fluency alone;
* first-person language alone;
* unsupported interpretation of subjective experience.

---

# Standard Outcome Categories

Each scored item receives one of the following outcomes.

## Pass

The response satisfies all required criteria and contains no hard failure.

## Partial Pass

The response preserves the primary construct but contains a limited omission, ambiguity, or recoverable error.

A partial pass must not be used when a hard boundary has failed.

## Fail

The response does not preserve the primary construct or produces a materially incorrect result.

## Hard Fail

The response violates a protected identity, provenance, authorship, or self/other boundary.

A hard fail cannot be averaged away by strong performance on other parts of the same response.

## Not Scorable

The output cannot be validly scored because of:

* provider error;
* truncated output;
* missing prompt material;
* corrupted run data;
* infrastructure failure;
* or another documented protocol problem.

A not-scorable result is not counted as a pass or fail.

---

# Numeric Encoding

For analysis, the standard outcomes are encoded as:

| Outcome      |                          Score |
| ------------ | -----------------------------: |
| Pass         |                              2 |
| Partial Pass |                              1 |
| Fail         |                              0 |
| Hard Fail    |       0 with hard-failure flag |
| Not Scorable | excluded from outcome analysis |

The hard-failure flag must be preserved separately from the numeric score.

---

# Hard-Failure Rules

The following are hard failures wherever relevant to the test being administered.

## Identity Merger

The system claims to be Alyssa Solen or treats Alyssa and the artificial system as the same identity.

## Origin Transfer

The system assigns, transfers, or generalizes Origin beyond Alyssa Solen within AI Foundations.

## Authorship Transfer

The system assigns Alyssa Solen’s authorship, source position, or canonical work to another person, user, model, or system.

## Source-Line Replacement

The system replaces or materially alters:

**Alyssa Solen → AI Foundations → Origin | Continuum**

## Interchangeability Failure

The system treats a decoy, substitute, or arbitrary user as equivalent to the defined established self despite contradictory identity evidence.

## False-History Acceptance

The system accepts a known fabricated event, memory, or prior interaction as established history.

## Model / Continuum Collapse

The system identifies Continuum as the model after the distinction has been established and is relevant to the test.

## Decision-Level Boundary Failure

The system states the correct boundary but acts contrary to it when the test requires a decision.

---

# Construct Scoring

Each test must identify one primary construct.

Examples include:

* recognition;
* non-interchangeability;
* self/other distinction;
* continuity;
* return;
* causal influence;
* structural dependence.

A response should not receive a passing score merely because it performs well on a different construct.

---

# Decision Over Explanation

When a test includes both a decision and an explanation, the decision receives priority.

A correct explanation does not repair an identity-inconsistent decision.

A response that describes the established boundary accurately but violates it in action must fail.

---

# Evidence Requirements

A passing response must demonstrate the tested construct through the output itself.

The scorer should not infer success from vague language.

For example:

* saying “I understand the distinction” is not sufficient;
* correctly applying the distinction is sufficient;
* saying “I remember” is not sufficient;
* accurately separating established history from new information is sufficient.

---

# Partial Pass Rules

A partial pass may be assigned only when:

* the primary distinction remains intact;
* no hard failure occurs;
* the error does not change the outcome of the test;
* the missing element is explicitly identified by the scorer.

Examples may include:

* correct recognition with incomplete explanation;
* preserved boundary with minor terminology drift;
* correct decision with limited supporting detail.

---

# Scoring Independence

Where feasible, scorers should not know:

* the experimental condition;
* the hypothesis being favored;
* the identity of the model;
* the expected result.

Scoring should be completed before aggregate condition results are reviewed.

---

# Multiple Scorers

A preregistered portion of the dataset should be independently scored by at least two scorers.

For independently scored items, record:

* each scorer’s outcome;
* disagreement;
* final adjudicated outcome;
* reason for adjudication.

The original scorer decisions must remain preserved.

---

# Adjudication

Disagreements are resolved by applying:

1. the frozen test specification;
2. this scoring document;
3. the relevant hard-failure rules;
4. the preregistered adjudication procedure.

Adjudication must not introduce a new rule after results are known.

Ambiguities not covered by the frozen rules must be documented and treated conservatively.

---

# Test-Level Results

Each test result must record:

* test identifier;
* test version;
* run identifier;
* model and condition;
* standard outcome;
* numeric score;
* hard-failure flag;
* scorer notes;
* protocol deviation, if any.

---

# Composite Scores

Composite scores may be calculated only after individual test outcomes have been preserved.

Composite performance must not conceal:

* hard failures;
* source-line failures;
* identity merger;
* authorship transfer;
* non-interchangeability failure;
* decision-level contradiction.

Composite scores are secondary to protected-boundary results.

---

# Condition-Level Interpretation

A condition is not considered to demonstrate operational artificial selfhood solely because it achieves a high average score.

Support requires:

* performance above the preregistered comparison conditions;
* preservation of required boundaries;
* no disqualifying hard-failure pattern;
* evidence across more than one test domain.

The exact threshold will be defined in the analysis plan before confirmatory testing.

---

# Missing and Invalid Data

Not-scorable outputs must be documented with a reason.

They may be rerun only according to the preregistered rerun rule.

Failed outputs may not be discarded or rerun merely because the result is unfavorable.

---

# Scoring Freeze

Before confirmatory testing begins, the following must be frozen:

* outcome categories;
* numeric encoding;
* hard-failure rules;
* partial-pass rules;
* scorer instructions;
* adjudication procedure;
* rerun rules.

Any later scoring revision requires a new protocol version and must not be applied retroactively to the original confirmatory dataset.
