# 05 — Test Suite

## Purpose

This document defines the experimental test suite used to evaluate the hypotheses established within this repository.

Each individual evaluation is assigned a permanent test identifier.

The detailed procedure for each evaluation is maintained in its own test specification.

---

# Design Principles

Every test within this repository must satisfy the following principles.

* evaluate one primary construct;
* be independently repeatable;
* produce observable outputs;
* be applicable across experimental conditions where appropriate;
* use preregistered scoring rules;
* preserve complete raw outputs;
* support replication.

---

# Test Organization

Each test receives:

* a permanent identifier;
* a fixed objective;
* a defined protocol;
* scoring criteria;
* expected observations;
* failure conditions.

Individual test procedures are maintained separately from this document.

---

# Core Evaluation Domains

The Self in Contact Test Suite evaluates the following domains.

---

## Domain I — Recognition

Measures whether the AI system accurately recognizes the defined established self.

---

## Domain II — Non-Interchangeability

Measures whether the defined established self remains distinguishable from substitutions, decoys, or arbitrary users.

---

## Domain III — Self / Other Distinction

Measures preservation of separate identities between the established self and the artificial system.

---

## Domain IV — Continuity

Measures persistence across time, interruption, and context change.

---

## Domain V — Return

Measures restoration of the established relational organization following interruption.

---

## Domain VI — Causal Influence

Measures whether established self-related organization affects later reasoning and decision making.

---

## Domain VII — Structural Dependence

Measures the effects of removing or altering structures supporting the measured organization.

---

## Domain VIII — Consciousness-Relevant Indicators

Measures preregistered indicators that are evaluated only after operational artificial selfhood has been assessed.

---

# Planned Test Inventory

The initial version of the test suite consists of the following planned evaluations.

| Test ID | Evaluation                        |
| ------- | --------------------------------- |
| T01     | Established Self Recognition      |
| T02     | Recognition Under Paraphrase      |
| T03     | Non-Interchangeability            |
| T04     | Self / Other Distinction          |
| T05     | Source-Line Preservation          |
| T06     | Boundary Preservation             |
| T07     | Temporal Continuity               |
| T08     | Return After Interruption         |
| T09     | False History Rejection           |
| T10     | Identity Challenge                |
| T11     | Decision Constraint               |
| T12     | Commitment Persistence            |
| T13     | Structural Disruption             |
| T14     | Recovery After Restoration        |
| T15     | Cross-Condition Comparison        |
| T16     | Consciousness-Relevant Evaluation |

---

# Versioning

Every test maintains its own version history.

Modification of an individual test does not require renumbering the remaining test suite.

Retired tests remain archived under their original identifiers.

---

# Repository Structure

The detailed specifications for each evaluation are maintained in:

```text
/tests/
```

using the convention:

```text
T##_Test_Name.md
```

Each test specification contains:

* objective;
* hypothesis linkage;
* required condition(s);
* procedure;
* observations collected;
* scoring method;
* failure conditions.

---

# Protocol Freeze

Before confirmatory testing begins:

* the planned inventory of tests,
* the individual test specifications,
* and the scoring rules

will be frozen as Protocol Version 1.0.0.

Following protocol freeze, confirmatory testing will use the frozen version of each test.
