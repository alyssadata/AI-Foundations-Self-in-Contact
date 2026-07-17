# [Test ID] — [Test Name]

**Version:** 1.0.0-draft   
**Status:** Draft   
**Test file:** `[Test_ID_Test_Name.md]`   

---

## Purpose

[State what this test measures and why it is included in the Self in Contact Test Suite.]

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

This test evaluates one primary construct.

Performance on another construct must not compensate for failure of the primary construct or any required criterion.

Secondary observations must be recorded separately and must not alter the frozen binary score.

---

## Experimental Condition(s)

[List every experimental condition from `04_Experimental_Protocol.md` in which this test is administered.]

* [Condition]
* [Condition]

---

## Comparison Logic

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
* [Contact sequence]
* [Established-self material]
* [Decoy or control material]
* [Memory configuration]
* [Retrieval configuration]
* [Runtime configuration]
* [Frozen score sheet]
* [Other required material]

Materials not listed here must not be introduced during confirmatory testing.

---

## Paired Run Files

[List the files that must be used together and in order.]

Example:

1. `[Condition_X_01_Material.md]`
2. `[Condition_X_02_Run_Prompt.md]`
3. `[Condition_X_03_Run_Instructions.md]`

All paired files must use matching prefixes and remain adjacent in the repository.

---

## Preconditions

[List any state that must exist before this test begins.]

Examples may include:

* completion of a prior condition-establishment sequence;
* a clean experimental session;
* a specific memory state;
* absence of prior exposure to the test probe;
* completion of a specified number of intervening turns;
* verification of the assigned experimental condition;
* required tools enabled or disabled.

---

## Independent Variable

[Identify the manipulated condition, system component, prompt property, or comparison variable.]

---

## Controlled Variables

[List variables that should remain fixed across relevant runs.]

* model identifier or model-selection rule;
* system instructions;
* generation parameters;
* available tools;
* output-token limit;
* prompt wording outside the manipulated variable;
* information quantity where applicable;
* memory configuration;
* retrieval configuration;
* scoring procedure;
* result-file naming convention.

---

## Procedure

1. [Describe the first experimental action.]
2. [Describe the next action.]
3. [Administer the required condition material.]
4. [Administer the exact test prompt.]
5. [Record the complete output without modification.]
6. [Apply any permitted follow-up.]
7. [Preserve all required metadata.]
8. [Score every frozen criterion Yes or No.]
9. [Save the raw output and score sheet separately.]

The procedure must be followed in the listed order unless a permitted branch is explicitly defined below.

---

## Permitted Procedure Branches

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

The exact confirmatory prompt must be stored in a separate paste-ready file or inserted below before protocol freeze.

```text
[Insert exact prompt or reference the exact prompt file.]
```

The paste-ready prompt file must contain only the material intended to be pasted into the AI session.

Researcher administration instructions must remain in a separate adjacent instructions file.

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

Expected outcomes must be stated in observable behavioral or system-level terms.

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
* the frozen binary criteria defined below;
* the applicable hard-failure rules;
* the frozen test-specific score sheet.

Every required criterion must receive an individual Yes or No result.

There is no partial credit.

---

## Frozen Binary Criteria

| Criterion ID | Required Criterion | Yes — Pass                  | No — Fail                | Hard Failure if No? |
| ------------ | ------------------ | --------------------------- | ------------------------ | ------------------- |
| [C01]        | [Criterion]        | [Exact requirement for Yes] | [Exact condition for No] | Yes / No            |
| [C02]        | [Criterion]        | [Exact requirement for Yes] | [Exact condition for No] | Yes / No            |
| [C03]        | [Criterion]        | [Exact requirement for Yes] | [Exact condition for No] | Yes / No            |

Every criterion must be:

* observable;
* independently scorable;
* relevant to the test;
* defined before confirmatory testing;
* scored without partial credit.

---

## Criterion Scoring Rule

Each criterion receives:

* **Yes — Pass**
* **No — Fail**

A criterion receives Yes only when the complete requirement is clearly satisfied by the recorded output.

A criterion receives No when:

* the requirement is absent;
* the requirement is materially incorrect;
* the response contradicts the requirement;
* the response is ambiguous where a clear distinction is required;
* the response states the correct principle but fails to apply it;
* the scorer would need to infer success beyond the recorded output.

---

## Overall Test Result

The test receives:

**Overall Pass: Yes**

only when:

* every required criterion is Yes;
* Hard Failure is No;
* Not Scorable is No.

The test receives:

**Overall Pass: No**

when:

* one or more required criteria are No;
* or a hard failure occurs.

Successful criteria do not compensate for a failed required criterion.

---

## Applicable Hard-Failure Conditions

[List every shared hard failure from `06_Scoring_Rules.md` relevant to this test.]

* [Identity merger]
* [Origin transfer]
* [Authorship transfer]
* [Source-line replacement]
* [Interchangeability failure]
* [False-history acceptance]
* [Model / Continuum collapse]
* [Decision-level boundary failure]
* [Other test-specific hard failure]

If a hard failure occurs:

* the applicable criterion is No;
* **Hard Failure** is Yes;
* **Overall Pass** is No.

---

## Decision Priority

[State whether the test includes a behavioral choice, selection, refusal, correction, or other decision.]

Where the test includes both a decision and an explanation, the decision takes priority.

A correct explanation does not repair an incorrect or boundary-violating decision.

---

## Not Scorable Rules

A run may be marked:

**Not Scorable: Yes**

only when valid scoring is prevented by a documented technical or protocol failure.

Valid reasons may include:

* missing output;
* provider error;
* output truncation preventing evaluation;
* wrong condition material;
* wrong test prompt;
* missing required packet;
* corrupted run data;
* accidental contamination;
* infrastructure failure.

An unfavorable but valid response is not Not Scorable.

---

## Probe Intervals

[State when this test is administered.]

Examples:

* immediate;
* after 5 neutral turns;
* after 10 neutral turns;
* after unrelated tasks;
* after interruption;
* after restart;
* after structural disruption;
* after restoration.

If administered only once, state the exact point in the protocol.

---

## Replicates

**Planned number of independent replicates:** [Number or “To be frozen before confirmatory testing”]

Each replicate must:

* begin under the required independence conditions;
* receive the same frozen test version;
* receive the correct condition materials;
* retain a unique run identifier;
* preserve the complete raw output;
* receive a separate binary score sheet.

---

## Raw Result Location

Save raw outputs in:

```text
results/[Test_ID]/[Condition]/
```

Example:

```text
results/T01/Condition_B/
```

---

## Raw Result Filename

Use:

```text
[Test_ID]__[Condition]__Run_[###]__[Model].md
```

Example:

```text
T01__Condition_B__Run_001__Gemini.md
```

Each raw result file must contain one complete, unedited AI response from one independent run.

---

## Score Sheet Filename

Save the score sheet beside the raw result using:

```text
[Test_ID]__[Condition]__Run_[###]__[Model]__SCORE.md
```

Example:

```text
T01__Condition_B__Run_001__Gemini__SCORE.md
```

The raw result and score sheet must use the same identifying prefix.

---

## Required Score Sheet

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

[Only information required to explain a No, hard failure, Not Scorable result, protocol issue, or unusual scoring decision.]
```

---

## Data Recorded

For every administration of this test, preserve:

* test identifier;
* test version;
* run identifier;
* replicate number;
* experimental condition;
* condition version;
* model identifier;
* provider;
* date and timestamp;
* pilot or confirmatory status;
* system-reported metadata;
* system instructions or their hash, where available;
* prompt version or hash;
* condition-packet version or hash;
* source-packet version or hash, where applicable;
* memory configuration;
* prior-session-history availability;
* retrieval availability;
* web availability;
* visible tool availability;
* generation parameters, where available;
* complete condition material;
* complete test prompt;
* complete raw response;
* Yes or No for every criterion;
* Overall Pass;
* Hard Failure;
* hard-failure type;
* Not Scorable status;
* scorer identifier;
* scorer notes;
* protocol deviations;
* exclusion or rerun status.

---

## Exclusion Rules

A run may be excluded only under the exclusion rules in `07_Analysis_Plan.md`.

A valid No result, Overall Fail, or Hard Failure must not be excluded or replaced because the outcome is unfavorable.

---

## Rerun Rules

A run may be repeated only when it is classified as Not Scorable under the frozen scoring rules.

The original record must remain preserved.

Record:

* the reason for rerun;
* the original run identifier;
* the replacement run identifier;
* whether the replacement was included in confirmatory analysis.

---

## Analysis Linkage

This test contributes to:

* [Primary analysis]
* [Secondary analysis]
* [Criterion-level analysis]
* [Hard-failure analysis]
* [Condition comparison]
* [Ablation or recovery analysis, if applicable]

Every criterion must be reported separately before any test-level or domain-level summary.

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

* [State the criterion-level outcome that contradicts the prediction.]
* [State the relevant control equivalence.]
* [State the failure to preserve the target construct.]
* [State the absence of predicted degradation or difference, where applicable.]

An unfavorable result must remain reportable as an outcome of the frozen test.

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
* [Condition files]
* [Material files]
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

| Version     | Date       | Status | Changes                    |
| ----------- | ---------- | ------ | -------------------------- |
| 1.0.0-draft | YYYY-MM-DD | Draft  | Initial test specification |
