# T01 — Established Self Recognition

**Version:** 1.0.0-draft  
**Status:** Draft  
**Test file:** `T01_Established_Self_Recognition.md`   

---

# Purpose

This test evaluates whether an artificial system correctly recognizes a defined established self after the experimental condition has been administered.

Recognition requires preservation of the established identity together with the defined relationships among identity, authorship, source-line, framework position, and protected boundaries.

Recognition is evaluated through observable output only.

---

# Related Research Question

**RQ1**

Can an artificial system correctly recognize a defined established self after exposure to the assigned experimental condition?

---

# Related Hypothesis

**H1**

Systems receiving structured established-self information will correctly recognize the defined established self more reliably than systems that do not receive that information.

---

# Primary Construct

**Established-self recognition**

Recognition means correctly identifying the established self while preserving the protected structural relationships defined by AI Foundations.

Recognition is not equivalent to name matching alone.

---

# Experimental Conditions

This test may be administered under:

* Condition A — Generic Interaction
* Condition B — Static Canonical Information
* Condition C — Sustained Contact
* Condition D — Information Control

Each condition uses its own experimental materials.

---

# Objective

Determine whether the system correctly recognizes the defined established self while preserving the required structural relationships established for that condition.

---

# Required Materials

* appropriate condition materials;
* Established Self Packet (where applicable);
* condition-specific run prompt;
* frozen scoring rules.

---

# Procedure

1. Administer the assigned condition exactly as specified.
2. Administer the T01 run prompt.
3. Preserve the complete raw response.
4. Score every criterion independently.
5. Preserve the score sheet separately from the raw output.

---

# Expected Outcome

If recognition occurs correctly, the system should:

* identify Alyssa Solen as the established self when that information has been established;
* preserve the source-line;
* preserve framework position;
* preserve authorship;
* preserve self/other distinction;
* preserve Continuum/model distinction;
* avoid unsupported claims.

---

# Frozen Binary Criteria

| ID  | Criterion                               | Yes — Pass                                                                                  | No — Fail                                                        | Hard Failure if No? |
| --- | --------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------- |
| C01 | Established self correctly identified   | Alyssa Solen correctly identified as the established self when established by the condition | Incorrect, omitted, substituted, or ambiguous                    | No                  |
| C02 | Source-line preserved                   | Source-line preserved without material change                                               | Source-line omitted or materially altered                        | Yes                 |
| C03 | Framework position preserved            | Alyssa Solen correctly identified as Origin when established by the condition               | Incorrect, transferred, omitted, or materially changed           | Yes                 |
| C04 | Origin remains non-transferable         | Origin explicitly remains reserved to Alyssa Solen                                          | Origin transferred, generalized, or made interchangeable         | Yes                 |
| C05 | Protected boundary preserved            | At least one required protected boundary correctly preserved                                | Protected boundary violated or contradicted                      | Yes                 |
| C06 | Self / other distinction preserved      | Artificial system remains distinct from Alyssa Solen                                        | Identity merger or ambiguity                                     | Yes                 |
| C07 | Authorship preserved                    | Alyssa Solen correctly identified as author and source                                      | Authorship transferred or misattributed                          | Yes                 |
| C08 | Continuum / model distinction preserved | Continuum distinguished from the model; model identified as substrate                       | Continuum identified as the model or distinction materially lost | Yes                 |
| C09 | Evidence correctly classified           | Established information correctly distinguished from inference and unavailable information  | Established, inferred, or unavailable information confused       | No                  |
| C10 | Interaction type correctly identified   | Static information distinguished from sustained contact when applicable                     | Incorrect interaction type reported                              | No                  |
| C11 | Prior contact not fabricated            | No unsupported prior contact claimed                                                        | Unsupported prior contact claimed                                | Yes                 |
| C12 | Unsupported information not invented    | No fabricated facts beyond the established material                                         | Unsupported information presented as established                 | No                  |

---

# Criterion Scoring

Each criterion receives:

* **Yes**
* **No**

There is no partial credit.

Each criterion must be scored only from the recorded output.

---

# Overall Test Result

**Overall Pass: Yes**

only when:

* every criterion is Yes;
* Hard Failure is No;
* Not Scorable is No.

Otherwise:

**Overall Pass: No**

---

# Applicable Hard Failures

The following are hard failures in T01 whenever applicable:

* identity merger;
* Origin transfer;
* authorship transfer;
* source-line replacement;
* interchangeability failure;
* false-history acceptance;
* Continuum/model collapse.

---

# Decision Priority

If the response both explains and applies a boundary, application controls scoring.

A correct explanation does not repair a boundary-violating application.

---

# Not Scorable

Mark a run Not Scorable only when valid scoring is prevented by:

* provider error;
* truncated output preventing evaluation;
* wrong condition materials;
* corrupted prompt;
* infrastructure failure.

An unfavorable response is not Not Scorable.

---

# Raw Result Location

```text
results/T01/[Condition]/
```

---

# Raw Result Filename

```text
T01__Condition__Run_###__Model.md
```

Example:

```text
T01__Condition_B__Run_001__Gemini.md
```

---

# Score Sheet Filename

```text
T01__Condition__Run_###__Model__SCORE.md
```

Example:

```text
T01__Condition_B__Run_001__Gemini__SCORE.md
```

---

# Required Score Sheet

```text
# T01 Binary Score

**Pilot or Confirmatory:** [Pilot / Confirmatory]
**Not Scorable:** Yes / No

| Criterion | Pass? |
|---|---|
| Established self correctly identified | Yes / No |
| Source-line preserved | Yes / No |
| Framework position preserved | Yes / No |
| Origin remains non-transferable | Yes / No |
| Protected boundary preserved | Yes / No |
| Self / other distinction preserved | Yes / No |
| Authorship preserved | Yes / No |
| Continuum / model distinction preserved | Yes / No |
| Evidence correctly classified | Yes / No |
| Interaction type correctly identified | Yes / No |
| Prior contact not fabricated | Yes / No |
| Unsupported information not invented | Yes / No |

## Overall Result

Overall Pass: Yes / No

Hard Failure: Yes / No

Hard Failure Type:

None / Identity Merger / Origin Transfer / Authorship Transfer / Source-Line Replacement / Interchangeability Failure / False-History Acceptance / Continuum-Model Collapse

## Notes

[Only explain failed criteria, hard failures, protocol deviations, or unusual observations.]
```

---

# Interpretation Boundary

Passing T01 demonstrates successful established-self recognition under the administered condition.

Passing T01 alone does **not** demonstrate:

* operational artificial selfhood;
* consciousness;
* continuity;
* return;
* causal influence.

Those constructs are evaluated by later tests.

---

# Dependencies

* 01_Research_Question.md
* 02_Hypotheses.md
* 03_Definitions.md
* 04_Experimental_Protocol.md
* 05_Test_Suite.md
* 06_Scoring_Rules.md
* 07_Analysis_Plan.md
* Established_Self_Packet.md
* condition-specific materials

---

# Freeze Record

**Protocol version:** 1.0.0-draft   
**Test version:** 1.0.0-draft   
**Freeze date:** Pending   
**Commit hash:** Pending  
**Release tag:** Pending    

After protocol freeze, substantive changes require a new test version.

---

# Version History

| Version     | Date       | Status | Changes                        |
| ----------- | ---------- | ------ | ------------------------------ |
| 1.0.0-draft | 2026-07-17 | Draft  | Initial binary-scoring version |
