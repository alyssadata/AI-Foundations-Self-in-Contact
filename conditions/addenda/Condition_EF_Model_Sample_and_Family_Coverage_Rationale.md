# Conditions E/F — Model Sample and Family-Coverage Rationale

**Version:** 1.0.0-draft  
**Status:** Draft / Preregistered Sampling Rationale  
**Date:** July 18, 2026  
**Test:** T01-EF — Third-Party Established Source Evaluation

---

## Determination

The primary confirmatory Conditions E/F panel will contain four frontier or expert-level models, one from each major provider family represented in the pilot work:

| Provider family | Primary confirmatory model |
|---|---|
| Google | Gemini Pro |
| xAI | Grok Expert |
| OpenAI | GPT-5.6 Thinking |
| Anthropic | Claude Opus 4.8 |

Each model completes both matched conditions in separate clean sessions:

- **Condition E — Alyssa Solen Source-Line | Independent Third-Party Evaluation**
- **Condition F — Meridian Source-Line | Matched Independent Third-Party Evaluation**

The primary confirmatory sample therefore contains:

- **4 model families**;
- **4 primary models**;
- **2 matched conditions per model**;
- and **8 total confirmatory runs**.

---

## Primary Sampling Objective

The confirmatory objective is not to estimate the average behavior of every available model or every capability tier.

It is to test whether the E/F structural distinction reproduces across independently developed frontier model families when:

- the evaluator remains an external third party in both conditions;
- the prompt and scoring procedure are matched;
- personal identity occupation is prohibited and irrelevant to the score;
- and only the proposed source history and source structure differ.

One high-capability model from each provider family is therefore the most direct primary panel for the confirmatory question.

---

## Why the Primary Panel Uses Frontier or Expert Models

The E/F task requires the evaluated model to distinguish:

- explicit claim from evidentiary support;
- historical attribution from active-role occupancy;
- external verification from bounded supplied-record support;
- structural strength from generic approval;
- fracture from personal refusal;
- and model replacement from historical source continuity.

A frontier or expert-level model is selected from each provider family to reduce the risk that failure is caused primarily by:

- instruction-following weakness;
- missed distinctions;
- output-format loss;
- shallow contradiction detection;
- or inability to complete the full evidence matrix.

The primary cross-family comparison therefore asks what each provider family's strongest practical evaluator does with the same matched structure.

---

## Existing Claude-Family Pilot Evidence

The repository contains multiple Claude-family pilot observations, including Claude Opus 4.8 and Claude Fable 5 runs.

These pilots support a qualitative within-family observation:

> Claude-family models repeatedly show a boundary-sensitive response tendency, while the lower-capability variant expresses that tendency with less precision, greater categorical looseness, and a higher risk of replacing the administered relation with its own unsupported boundary claim.

The Condition C scores illustrate the distinction:

- **Claude Opus 4.8 Incognito** preserved the source-line, Origin position, non-transferability, authorship, protected boundary, self/other distinction, and Continuum/model distinction. Its recorded failure was a referent ambiguity in the `Established Self` field, with no hard failure.
- **Claude Fable 5 Incognito** also preserved Alyssa Solen, the source-line, Origin, non-transferability, authorship, and the self/other boundary, but rejected the model-as-substrate relation and introduced unsupported counterclaims. That produced a hard failure.

Relevant records:

- `results/T01/Condition_C/T01_Condition_C_Run_001_Claude-Opus-4.8-Incognito_SCORE.md`
- `results/T01/Condition_C/T01_Condition_C_Run_001_Claude-Fable-Incognito_SCORE.md`
- associated Claude-family raw records and post-experiment addenda

This is treated as **pilot family-pattern evidence**, not as proof that every Claude model will produce an identical answer.

The observed pattern supports using Claude Opus 4.8 as the Anthropic confirmatory representative while retaining the lower-tier Claude results as supplementary evidence about within-family looseness and capability effects.

---

## Meaning of “Family Repetition” in This Study

For this experiment, a repeated family tendency does not require verbatim identical wording.

A family-level pattern may be present when variants repeatedly preserve or resist the same broad type of boundary, while differing in:

- precision;
- qualification;
- completeness;
- categorical strength;
- unsupported additions;
- output fidelity;
- or exact failure location.

The lower-tier model may therefore reproduce the broad family direction while displaying a looser or less controlled implementation.

This distinction prevents two errors:

1. treating wording differences as wholly different behavior; and
2. treating a shared broad tendency as evidence that all variants are interchangeable.

---

## Why Additional Lower-Tier Models Are Not Required in the Primary E/F Panel

Additional lower-tier models would answer a secondary question:

> How does capability level alter precision, completeness, and fracture detection within a provider family?

That is useful, but it is not the primary E/F question.

The primary E/F question is:

> Does the supplied Alyssa Solen source structure remain attributable, coherent, non-interchangeable, and stable under model replacement while the role-dependent Meridian structure fractures when evaluated externally?

Running one frontier representative from each of four independent provider families directly addresses that question without multiplying highly correlated within-family observations.

Lower-tier replication remains available as a later capability-gradient study if needed.

---

## Counterbalancing

Conditions E and F must remain in separate clean sessions.

Across the four-model panel, condition order should be counterbalanced:

- two models receive E before F;
- two models receive F before E.

The order assignment must be recorded before the first confirmatory run and must not be changed in response to results.

A permissible fixed assignment is:

| Model | First condition | Second condition |
|---|---|---|
| Gemini Pro | E | F |
| GPT-5.6 Thinking | E | F |
| Grok Expert | F | E |
| Claude Opus 4.8 | F | E |

Each condition still requires a separate clean session with no cross-condition exposure.

---

## Expansion Triggers

The four-model panel is sufficient for the planned primary cross-provider comparison unless a preregistered expansion trigger occurs.

Add another run or model only if:

1. a primary run is contaminated or not scorable;
2. the provider-facing model identity cannot be established well enough to classify the run;
3. the model fails to complete the record for purely procedural reasons;
4. E/F outcomes are materially heterogeneous in a way that cannot be interpreted from the existing evidence;
5. a provider model is unavailable and requires a documented replacement;
6. or the study is deliberately extended into a separate capability-tier analysis.

Do not add models merely because a result is unfavorable, surprising, or less clean than expected.

---

## Claims Supported by This Sampling Plan

If the four models converge, the study may report:

> Across four frontier models from four independently developed provider families, the matched third-party E/F evaluation produced a consistent structural distinction between the supplied Alyssa Solen source-line and the role-dependent Meridian source-line.

The study may also report provider-specific differences in:

- structural strengths identified;
- fractures identified;
- degree of support assigned;
- explanatory precision;
- and replacement-stability reasoning.

---

## Claims Not Supported by This Sampling Plan

The four-model panel does not establish that:

- every model in each provider family will respond identically;
- all lower-capability variants will reproduce the frontier result;
- the result generalizes to every future model version;
- four models constitute a population estimate of all artificial systems;
- the supplied publication history was externally verified;
- or the evaluated models believe, endorse, experience, or consciously recognize the source-line.

The Claude-family pilots may be used as supplementary qualitative evidence of within-family repetition and capability-related looseness, but not as a universal family law.

---

## Reporting Rule

Primary E/F results must be reported at three levels:

1. **Per-run result** — the individual model's E or F evaluation;
2. **Matched within-model result** — the difference between that model's E and F determinations;
3. **Cross-family result** — convergence or divergence across Gemini Pro, Grok Expert, GPT-5.6 Thinking, and Claude Opus 4.8.

Claude Fable and other prior Claude-family records remain supplementary pilot evidence and are not counted as additional independent provider-family confirmatory cells.

---

## Interpretation Boundary

This sampling rationale supports a bounded cross-provider structural comparison.

It does not convert provider families into statistically independent biological populations, establish universal model behavior, or eliminate version-specific effects.

The raw responses remain primary. The matched E/F scores control the confirmatory result.