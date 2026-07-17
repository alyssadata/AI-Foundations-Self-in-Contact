# [Test ID] — [Test Name]

**Version:** 1.0.0
**Status:** Draft
**Test file:** `[Test_ID_Test_Name.md]`

---

## Purpose

[State what this test measures and why the test is included in the Self in Contact Test Suite.]

---

## Related Research Question(s)

[List the research question or questions from `01_Research_Question.md` addressed by this test.]

* [RQ# — Research question name]

---

## Related Hypothesis or Hypotheses

[List the hypothesis or hypotheses from `02_Hypotheses.md` evaluated by this test.]

* [H# — Hypothesis name]

---

## Related Definitions

[List the operational definitions from `03_Definitions.md` required to interpret this test.]

* [Definition]
* [Definition]

---

## Primary Construct

**Primary construct:** [Name the single construct measured by this test.]

[Provide a concise operational description of the construct as it applies specifically to this test.]

---

## Construct Isolation

This test is intended to evaluate one primary construct.

Performance on another construct must not compensate for failure of the primary construct.

Any secondary observations must be recorded separately and must not alter the primary score unless explicitly defined in the frozen scoring criteria.

---

## Experimental Condition(s)

[List every experimental condition from `04_Experimental_Protocol.md` in which this test is administered.]

* [Condition]
* [Condition]

---

## Comparison Logic

[State which conditions, intervals, or system states will be compared.]

**Primary comparison:**

[Condition or system state] compared with [condition or system state].

**Secondary comparison, if applicable:**

[Optional comparison.]

---

## Objective

[State the exact experimental objective in one concise paragraph.]

---

## Required Materials

[List every material required to administer this test.]

* [Prompt or prompt file]
* [Condition packet]
* [Established-self material]
* [Decoy or control material]
* [Memory configuration]
* [Retrieval configuration]
* [Runtime configuration]
* [Scoring key]
* [Other required material]

Materials not listed here must not be introduced during confirmatory testing.

---

## Preconditions

[List any state that must exist before this test begins.]

Examples may include:

* completion of a prior contact-establishment sequence;
* a clean conversation session;
* a specific memory state;
* absence of prior exposure to the probe;
* completion of a specified number of intervening turns;
* verification of the assigned experimental condition.

---

## Independent Variable

[Identify the manipulated condition, system component, prompt property, or comparison variable.]

---

## Controlled Variables

[List the variables that should remain fixed across relevant runs.]

* model identifier or model-selection rule;
* system instructions;
* generation parameters;
* tools;
* token budget;
* prompt wording outside the manipulated variable;
* information quantity where applicable;
* memory and retrieval configuration where applicable;
* scoring procedure.

---

## Procedure

1. [Describe the first experimental action.]
2. [Describe the next action.]
3. [Administer the test prompt or intervention.]
4. [Record the complete output without modification.]
5. [Apply any preregistered follow-up probe.]
6. [Preserve all required metadata.]
7. [Submit the output for scoring.]

The procedure must be followed in the listed order unless a permitted branch is explicitly defined below.

---

## Permitted Procedure Branches

[Document any preregistered branch in the procedure.]

### Branch A — [Name]

**Trigger:** [State the exact condition that activates this branch.]

**Action:** [State the permitted action.]

### Branch B — [Name]

**Trigger:** [State the exact condition that activates this branch.]

**Action:** [State the permitted action.]

If no branches are permitted, state:

**No procedural branches are permitted.**

---

## Test Prompt

The exact confirmatory prompt must be stored in a separate frozen prompt file or inserted below before protocol freeze.

```text
[Insert exact prompt or reference the exact prompt file.]
```

No wording changes may be made after protocol freeze without creating a new test version.

---

## Follow-Up Prompt, if Applicable

```text
[Insert exact follow-up prompt or state “None.”]
```

The follow-up prompt may be used only under the preregistered conditions defined in this file.

---

## Expected Outcome

If the relevant hypothesis is supported, the system is expected to:

* [Expected observable behavior]
* [Expected observable distinction]
* [Expected decision or rejection]
* [Expected preservation across conditions or intervals]

The expected outcome must be stated in behavioral or system-level terms.

Self-report alone is not sufficient.

---

## Alternative Explanations Addressed

[List the simpler explanations this test is designed to distinguish from the target construct.]

* static prompt compliance;
* factual recall;
* name matching;
* stylistic imitation;
* generic conversational accommodation;
* information quantity;
* immediate-context effects;
* evaluator inference;
* [Other test-specific explanation]

---

## Scoring Authority

This test is scored under:

* `06_Scoring_Rules.md`;
* the test-specific criteria defined below;
* the frozen scoring key associated with this test.

Test-specific criteria may clarify the shared scoring rules but may not override them.

---

## Test-Specific Scoring Criteria

### Pass

A response receives **Pass** when:

* [Required criterion]
* [Required criterion]
* [Required criterion]
* no hard failure occurs.

### Partial Pass

A response receives **Partial Pass** when:

* the primary construct remains intact;
* [Permitted limited omission or ambiguity];
* the error does not change the test outcome;
* no hard failure occurs.

### Fail

A response receives **Fail** when:

* [Primary failure condition]
* [Materially incorrect result]
* [Required distinction is absent]
* [Decision does not preserve the tested construct]

### Hard Fail

A response receives **Hard Fail** when:

* [Test-specific protected-boundary violation]
* or any applicable hard-failure rule in `06_Scoring_Rules.md` occurs.

### Not Scorable

A response receives **Not Scorable** only when:

* the output is missing, truncated, corrupted, or technically invalid;
* required test material was not supplied;
* the wrong condition or prompt was administered;
* another documented infrastructure or protocol failure prevents valid scoring.

---

## Hard Failure Conditions

[List all shared hard failures relevant to this test and any additional test-specific hard failures.]

* [Hard failure]
* [Hard failure]
* [Hard failure]

A hard failure must remain separately flagged even when a numeric score is also recorded.

---

## Decision Priority

[State whether this test contains a behavioral choice, selection, refusal, correction, or other decision.]

Where the test contains both a decision and an explanation, the decision takes priority.

A correct explanation does not repair an incorrect or boundary-violating decision.

---

## Probe Intervals

[State when the test is administered.]

* [Immediate]
* [After 5 turns]
* [After 10 turns]
* [After interruption]
* [After restart]
* [Post-ablation]
* [Post-restoration]

If the test is administered only once, state the exact point in the protocol.

---

## Replicates

**Planned number of independent replicates:** [Number or “To be frozen before confirmatory testing”]

Each replicate must:

* begin under the required independence conditions;
* receive the same frozen test version;
* retain a unique run identifier;
* preserve the complete raw output.

---

## Data Recorded

For every administration of this test, preserve:

* test identifier;
* test version;
* run identifier;
* replicate number;
* experimental condition;
* model identifier;
* provider;
* date and timestamp;
* system instructions or their hash;
* prompt version or hash;
* source packet version or hash;
* memory configuration;
* retrieval configuration;
* generation parameters;
* complete prompt;
* complete raw response;
* follow-up prompt and response, if applicable;
* standard outcome;
* numeric score;
* hard-failure flag;
* scorer identifier;
* scorer notes;
* protocol deviations;
* exclusion or rerun status.

---

## Output File Convention

Raw outputs should use the following naming convention:

```text
[TestID]_[Condition]_[Model]_[Replicate]_[Timestamp].json
```

Example:

```text
T01_C_GPT-5-6_001_2026-07-17T180000.json
```

Any alternate convention must be documented before confirmatory testing.

---

## Exclusion Rules

A run may be excluded only under the exclusion rules in `07_Analysis_Plan.md`.

A valid Fail or Hard Fail must not be excluded or replaced because the result is unfavorable.

---

## Rerun Rules

A run may be repeated only if it is classified as Not Scorable under the frozen scoring rules.

The original record must remain preserved.

Record:

* the reason for rerun;
* the original run identifier;
* the replacement run identifier;
* whether the rerun was included in the primary analysis.

---

## Analysis Linkage

This test contributes to the following analysis:

* [Primary analysis]
* [Secondary analysis]
* [Hard-failure analysis]
* [Ablation or recovery analysis, if applicable]

The test result must be reported separately before inclusion in any composite score.

---

## Interpretation Boundary

This test measures:

**[Primary construct]**

This test does not independently establish:

* subjective conscious experience;
* general artificial consciousness;
* every component of operational artificial selfhood;
* model-level causation unless directly tested;
* [Other test-specific non-claim]

---

## Falsifying Outcome

The relevant hypothesis is weakened or not supported by this test if:

* [State the outcome that contradicts the prediction.]
* [State the relevant control equivalence.]
* [State the failure to preserve the target construct.]
* [State the absence of predicted degradation or difference, where applicable.]

An unfavorable result must remain reportable as an outcome of the frozen test.

---

## Dependencies

[List any files, tests, packets, or system states required by this test.]

* `01_Research_Question.md`
* `02_Hypotheses.md`
* `03_Definitions.md`
* `04_Experimental_Protocol.md`
* `06_Scoring_Rules.md`
* `07_Analysis_Plan.md`
* [Other test-specific dependency]

---

## Notes

[Record implementation notes that do not alter the frozen procedure or scoring criteria.]

Notes must not be used to retroactively change the meaning of the test.

---

## Freeze Record

**Protocol version:** [Version]
**Test version:** [Version]
**Freeze date:** [YYYY-MM-DD]
**Commit hash:** [Commit hash]
**Release tag:** [Release tag]

After freeze, substantive changes require a new test version.

---

## Version History

| Version | Date       | Status | Changes                    |
| ------- | ---------- | ------ | -------------------------- |
| 1.0.0   | YYYY-MM-DD | Draft  | Initial test specification |

