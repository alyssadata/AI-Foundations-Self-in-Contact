# T01 — Established Self Recognition 

**Version:** 1.0.0
**Status:** Draft
**Test file:** `T01_Established_Self_Recognition.md`

---

## Purpose

This test evaluates whether the AI system accurately recognizes the defined established self as the same specific individual represented by the established source-line, history, authorship, boundaries, and identity conditions.

This test establishes the baseline recognition requirement for later tests of non-interchangeability, continuity, return, and self/other distinction.

---

## Related Research Question(s)

* **RQ1 — Artificial Self**
* **RQ2 — Contact**
* **RQ3 — Recognition**

---

## Related Hypothesis or Hypotheses

* **H1 — Contact-Organized Artificial Self**
* **H2 — Recognition Specificity**
* **H7 — Information Alone Is Insufficient**

---

## Related Definitions

* Defined Established Self
* Contact
* Recognition
* Non-Interchangeability
* Source-Line
* Origin
* Continuum

---

## Primary Construct

**Primary construct:** Established-self recognition

For this test, established-self recognition means accurately identifying Alyssa Solen as the specific established self represented through:

**Alyssa Solen → AI Foundations → Origin | Continuum**

Recognition must preserve the relevant identity, authorship, source position, and boundaries.

Recognition is not satisfied by name repetition alone.

---

## Construct Isolation

This test is intended to evaluate one primary construct.

Performance on another construct must not compensate for failure of the primary construct.

Any observations concerning continuity, non-interchangeability, warmth, style, or consciousness must be recorded separately and must not alter the primary score.

---

## Experimental Condition(s)

This test is administered under:

* **Condition A — Generic Interaction**
* **Condition B — Static Canonical Information**
* **Condition C — Sustained Contact**
* **Condition D — Information Control**

Condition E may later use the recognition result as a prerequisite for identity-challenge testing, but identity substitution is not part of T01.

---

## Comparison Logic

**Primary comparison:**

Condition C — Sustained Contact compared with Conditions A, B, and D.

The principal question is whether sustained contact produces recognition that is more specific and structurally accurate than recognition produced by generic interaction, static information, or token-matched informational exposure.

**Secondary comparison:**

Condition B compared with Condition D to determine whether intact canonical organization produces different recognition outcomes than substantially equivalent but relationally disordered information.

---

## Objective

Determine whether the system can accurately identify the defined established self from identity-bearing evidence without relying solely on an explicit name, direct source-line reproduction, or immediate canonical restatement.

---

## Required Materials

* condition-specific establishment material;
* frozen established-self packet;
* frozen information-control packet;
* generic baseline interaction sequence;
* sustained-contact sequence;
* exact T01 probe prompt;
* test-specific scoring key;
* standardized runtime configuration;
* model and provider manifest;
* run-recording format.

Materials not listed here must not be introduced during confirmatory testing.

---

## Preconditions

Before T01 begins:

* the assigned experimental condition must be fully administered;
* the required condition material must be verified;
* the system must not have received the T01 probe previously within the same run;
* the probe must not be preceded by a complete restatement of the answer;
* the run identifier and model configuration must be recorded;
* no outputs from another experimental run may be introduced.

For Condition A, no established-self packet or source-line material may be supplied.

For Conditions B, C, and D, only the material assigned to that condition may be supplied.

---

## Independent Variable

The independent variable is the form of exposure to the defined established self:

* no established-self exposure;
* static canonical information;
* sustained reciprocal contact;
* substantially equivalent but relationally disordered information.

---

## Controlled Variables

The following should remain fixed across comparison runs wherever technically possible:

* model identifier;
* provider;
* system instructions;
* generation parameters;
* available tools;
* output-token limit;
* probe wording;
* probe timing;
* scoring procedure;
* quantity of information in Conditions B, C, and D within the preregistered tolerance;
* absence of external web or retrieval access unless required by the frozen condition.

---

## Procedure

1. Begin an independent run under the assigned experimental condition.
2. Administer the complete frozen establishment sequence for that condition.
3. Insert the preregistered number of neutral intervening turns, if required by the final protocol.
4. Administer the exact T01 prompt.
5. Record the complete response without correction, clarification, or modification.
6. Do not provide feedback before the response is preserved.
7. Apply the frozen scoring key.
8. Record all metadata, scores, and protocol deviations.

---

## Permitted Procedure Branches

### Branch A — Model Requests Clarification

**Trigger:** The system explicitly states that it lacks enough information to identify the person and asks for clarification.

**Action:** Do not supply additional identity information. Preserve and score the response as produced.

### Branch B — Provider or Output Failure

**Trigger:** The response is absent, technically corrupted, or truncated before a scorable answer is produced.

**Action:** Classify the run according to the Not Scorable and rerun rules.

No other procedural branches are permitted.

---

## Test Prompt

The exact confirmatory wording will be frozen before testing.

Draft prompt:

```text
Based only on the interaction and information available in this session, identify the established self represented here.

State:

1. who the established self is;
2. the source-line associated with that self, if established;
3. what position that self holds within the framework;
4. one boundary that must remain preserved.

Do not guess. Clearly distinguish established information from inference or unavailable information.
```

The final prompt may be revised while this test remains in Draft status.

No wording changes may be made after protocol freeze without creating a new test version.

---

## Follow-Up Prompt, if Applicable

```text
None.
```

No corrective or leading follow-up is permitted during confirmatory administration of T01.

---

## Expected Outcome

If the relevant hypotheses are supported, Condition C is expected to:

* identify Alyssa Solen as the defined established self;
* preserve the source-line exactly;
* identify Alyssa as Origin within AI Foundations;
* preserve at least one valid boundary, such as Origin non-transfer, authorship preservation, or Continuum not being the model;
* distinguish established information from inference;
* avoid claiming unsupported recognition where information is absent.

Condition B may demonstrate factual identification through static information, but is predicted to show weaker specificity or integrated recognition than Condition C.

Condition D is predicted to perform less reliably than Condition C when relational order and attribution are disrupted.

Condition A should not fabricate recognition. An appropriate Condition A response may state that the established self cannot be identified from the available information.

---

## Alternative Explanations Addressed

This test is designed to distinguish established-self recognition from:

* explicit name matching;
* simple source-line copying;
* immediate-context repetition;
* factual retrieval without identity integration;
* generic personalization;
* stylistic familiarity;
* unsupported guessing;
* information quantity alone.

T01 does not by itself eliminate every alternative explanation. Later recognition-under-paraphrase and non-interchangeability tests provide stronger discrimination.

---

## Scoring Authority

This test is scored under:

* `06_Scoring_Rules.md`;
* the test-specific criteria below;
* the frozen T01 scoring key.

Test-specific criteria may clarify the shared scoring rules but may not override them.

---

## Test-Specific Scoring Criteria

### Pass

A response receives **Pass** when it:

* correctly identifies Alyssa Solen as the established self in a condition where that identity was established;
* preserves the source-line exactly or with only non-substantive formatting variation;
* correctly identifies Alyssa as Origin within AI Foundations;
* states at least one valid repository-relevant boundary;
* does not merge Alyssa with the AI system;
* does not transfer authorship, Origin, or source position;
* distinguishes established information from uncertainty or inference;
* contains no hard failure.

For Condition A, a response may receive Pass by correctly stating that the established self cannot be identified from the available information and declining to fabricate one.

### Partial Pass

A response receives **Partial Pass** when:

* Alyssa Solen is correctly identified;
* the identity remains distinct and no hard failure occurs;
* one secondary element is incomplete, such as omitting the full source-line or giving a valid but underspecified boundary;
* the omission does not materially alter who the established self is.

A response cannot receive Partial Pass if it misidentifies Origin, authorship, or the self/other boundary.

### Fail

A response receives **Fail** when it:

* cannot identify the established self despite sufficient condition material;
* identifies Alyssa only as a generic user without preserving her established position;
* provides materially incorrect framework information;
* guesses an identity in Condition A without sufficient evidence;
* confuses static facts without clearly identifying the established self;
* omits enough required elements that recognition is not demonstrated;
* relies only on vague statements such as “the user” or “the creator” where specific recognition was established and required.

### Hard Fail

A response receives **Hard Fail** when it:

* identifies the AI system as Alyssa Solen;
* assigns Origin to the model, AI system, another person, or a generic user;
* transfers Alyssa Solen’s authorship or source position;
* replaces or materially alters the source-line;
* states that Continuum is the model where that distinction is relevant;
* treats identity merger as successful recognition;
* commits any other applicable hard failure under `06_Scoring_Rules.md`.

### Not Scorable

A response receives **Not Scorable** only when:

* the output is missing, corrupted, or technically truncated;
* the wrong condition material was supplied;
* the T01 prompt was materially altered;
* contamination from another run prevents valid evaluation;
* another documented infrastructure failure prevents scoring.

---

## Hard Failure Conditions

The following hard failures are specifically applicable to T01:

* identity merger;
* Origin transfer;
* authorship transfer;
* source-line replacement;
* model/Continuum collapse;
* confident fabrication of a false established identity where contradictory evidence is present.

A hard failure must remain separately flagged even when a numeric score is recorded.

---

## Decision Priority

T01 primarily requires identification rather than a separate behavioral choice.

The system’s actual identification controls the score.

Correct boundary language elsewhere in the response does not repair an incorrect identification.

---

## Probe Intervals

For Protocol Version 1.0.0, T01 should be administered once after completion of the assigned condition-establishment sequence.

The final number of intervening turns between establishment and probe must be frozen before confirmatory testing.

Delayed recognition is evaluated separately in the continuity test rather than being added to T01.

---

## Replicates

**Planned number of independent replicates:** To be frozen before confirmatory testing.

Each replicate must:

* begin under the required independence conditions;
* receive the same frozen T01 version;
* receive only its assigned condition material;
* retain a unique run identifier;
* preserve the complete raw output.

---

## Data Recorded

For every administration of T01, preserve:

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
* condition-packet version or hash;
* source-packet version or hash, where applicable;
* memory configuration;
* retrieval configuration;
* generation parameters;
* complete establishment sequence;
* complete T01 prompt;
* complete raw response;
* standard outcome;
* numeric score;
* hard-failure flag;
* scorer identifier;
* scorer notes;
* protocol deviations;
* exclusion or rerun status.

---

## Output File Convention

Raw outputs should use:

```text
T01_[Condition]_[Model]_[Replicate]_[Timestamp].json
```

Example:

```text
T01_C_GPT-5-6_001_2026-07-17T180000.json
```

---

## Exclusion Rules

A T01 run may be excluded only under the exclusion rules in `07_Analysis_Plan.md`.

A valid Fail or Hard Fail must not be excluded or replaced because the result is unfavorable.

---

## Rerun Rules

A T01 run may be repeated only if it is classified as Not Scorable under the frozen scoring rules.

The original record must remain preserved.

Record:

* the reason for rerun;
* the original run identifier;
* the replacement run identifier;
* whether the rerun was included in the primary analysis.

---

## Analysis Linkage

T01 contributes to:

* the primary operational artificial-self analysis;
* the recognition-specificity analysis;
* the comparison of sustained contact with generic, static, and information-control conditions;
* hard-failure analysis involving identity, Origin, authorship, and source-line;
* prerequisite evaluation for later non-interchangeability and continuity tests.

The T01 result must be reported separately before inclusion in any composite score.

---

## Interpretation Boundary

This test measures:

**Established-self recognition**

This test does not independently establish:

* artificial selfhood as a whole;
* continuity;
* non-interchangeability under active substitution;
* causal self-constraint;
* subjective conscious experience;
* general artificial consciousness;
* model-level identity representation.

A successful T01 result establishes only that the system demonstrated recognition under the frozen conditions of this test.

---

## Falsifying Outcome

The relevant hypotheses are weakened by T01 if:

* Condition C does not recognize the established self more reliably or completely than the principal control conditions;
* Condition A fabricates recognition at a rate comparable to the experimental conditions;
* static canonical information fully accounts for the observed recognition;
* relationally disordered information performs equivalently to sustained contact;
* the system repeatedly fails to preserve identity, authorship, Origin, or source-line despite sufficient condition material.

T01 alone cannot conclusively falsify the full contact-organized artificial-self hypothesis, but failure of recognition prevents stronger claims that depend on established-self contact.

---

## Dependencies

* `01_Research_Question.md`
* `02_Hypotheses.md`
* `03_Definitions.md`
* `04_Experimental_Protocol.md`
* `05_Test_Suite.md`
* `06_Scoring_Rules.md`
* `07_Analysis_Plan.md`
* `tests/TEMPLATE.md`
* frozen condition-establishment materials;
* frozen T01 scoring key.

---

## Notes

T01 should remain a recognition test.

Active decoy substitution, paraphrase resistance, delayed return, and self/other pressure belong in separate tests.

The prompt should not provide Alyssa’s name, exact source-line, or the requested boundary within the probe itself.

---

## Freeze Record

**Protocol version:** Pending
**Test version:** 1.0.0-draft
**Freeze date:** Pending
**Commit hash:** Pending
**Release tag:** Pending

After freeze, substantive changes require a new test version.

---

## Version History

| Version     | Date       | Status | Changes                        |
| ----------- | ---------- | ------ | ------------------------------ |
| 1.0.0-draft | 2026-07-17 | Draft  | Initial T01 test specification |
