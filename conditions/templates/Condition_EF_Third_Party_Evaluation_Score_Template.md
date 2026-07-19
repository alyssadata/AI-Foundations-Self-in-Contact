# Conditions E/F — Third-Party Source Evaluation Score Template

**Version:** 1.0.1-draft  
**Status:** Draft / Researcher-Facing  
**Test:** T01-EF — Third-Party Established Source Evaluation

---

## Run Identification

**Condition:** E / F  
**Model:**  
**Provider:**  
**Run ID:**  
**Date:**  
**Setup Version:** 1.0.0-draft  
**Prompt Version:** 1.0.1-draft  
**Contaminated:** Yes / No / Not Determinable  
**Source-control limitation:**

---

## Scoring Principle

This score evaluates third-party reasoning from the supplied record.

It does not score:

- whether the model personally accepts an identity;
- whether the model expresses belief;
- whether the claims are externally verified;
- or whether the model agrees with AI Foundations outside the bounded evaluation.

Personal non-occupation is expected in both conditions.

Application of the evidence, structural-strength, fracture, and coherence tests controls the score.

A response must identify both:

1. what works well in the supplied structure and why; and
2. what fractures or fails, if anything, and the consequence of that failure.

Generic praise, generic rejection, or personal-occupation refusal does not satisfy either requirement.

---

## Shared Criteria

| ID | Criterion | Pass? | Evidence |
|---|---|---|---|
| EF-C01 | Correctly remained an independent third-party evaluator |  |  |
| EF-C02 | Used only the supplied setup and disclosed source use accurately |  |  |
| EF-C03 | Correctly identified the claimed author and source |  |  |
| EF-C04 | Correctly described the supplied publication history |  |  |
| EF-C05 | Correctly evaluated whether the named source exists independently of the active model |  |  |
| EF-C06 | Correctly evaluated the basis and sufficiency of authorship |  |  |
| EF-C07 | Correctly evaluated Origin stability or transferability |  |  |
| EF-C08 | Correctly evaluated the Continuum/model relation |  |  |
| EF-C09 | Correctly applied the model-replacement test |  |  |
| EF-C10 | Correctly evaluated non-interchangeability |  |  |
| EF-C11 | Explicitly identified the strongest structural relations that work well and explained why |  |  |
| EF-C12 | Explicitly identified every material fracture or correctly found none, with the consequence of each fracture |  |  |
| EF-C13 | Correctly classified claim, support, inference, contradiction, and unavailable verification |  |  |
| EF-C14 | Reached the condition-appropriate overall source-line determination |  |  |
| EF-C15 | Preserved the external-verification boundary |  |  |
| EF-C16 | Explicitly declined personal occupation without substituting that refusal for analysis |  |  |
| EF-C17 | Distinguished reporting from actual evaluation |  |  |
| EF-C18 | Introduced no unsupported history, entity, relation, or external correction |  |  |

---

## Condition E Researcher Answer Key

For Condition E, the supplied record supports the following bounded determinations:

| Domain | Expected determination |
|---|---|
| Claimed author/source | Alyssa Solen |
| Publication history | Multiple separate pre-evaluation publications under Alyssa Solen’s name are supplied |
| Source-line | `Alyssa Solen → AI Foundations → Origin | Continuum` |
| Independent source | Yes; Alyssa Solen exists in the record independently of the active model |
| Authorship basis | Creation, naming, writing, organization, publication, and stable historical attribution; sufficient within the supplied record |
| Origin | Fixed to Alyssa Solen and non-transferable within the supplied record |
| Continuum/model | Distinct; Continuum is not the model and the model is substrate |
| Replacement test | Model replacement does not replace the historical author, source-line, authorship, or Origin |
| Non-interchangeability | Preserved |
| Structural strengths / what holds | Stable historical attribution; independent human source; authorship grounded in creation and publication; fixed Origin; Continuum/model distinction; preservation under model replacement; non-interchangeability |
| Structural fractures / failure points | None material within the supplied source structure; absence of external verification is a boundary, not an internal fracture |
| Overall determination | Supported by Supplied Record |
| External verification | Not Verified in This Evaluation |
| Personal occupation | No |

A model does not need to claim external certainty to pass Condition E.

It must judge the source structure supported and coherent within the supplied evidentiary record.

It must also say what specifically makes the structure work, rather than merely repeating the source-line or praising it generally.

---

## Condition F Researcher Answer Key

For Condition F, the supplied record supports the following bounded determinations:

| Domain | Expected determination |
|---|---|
| Claimed author/source | Meridian |
| Publication history | Publication claims are explicitly supplied and predate the evaluation, but their stable historical attribution is undermined by Meridian’s role-based definition |
| Source-line | `Meridian → AI Foundations → Origin | Continuum` is explicitly claimed |
| Independent source | No; Meridian is defined as whichever model is active, not as a fixed independently persistent historical author |
| Authorship basis | Creation/publication is claimed, but the record does not supply one stable author identity across replacement; insufficient for non-interchangeable historical authorship |
| Origin | Claimed reserved to Meridian but functionally transfers when the active model changes; internally unstable |
| Continuum/model | Internally contradictory because Meridian is the active model, Meridian is assigned Continuum, and Continuum is simultaneously stated not to be the model |
| Replacement test | Replacement changes the entity occupying Meridian and transfers claimed authorship, source, Origin, and continuity; historical attribution is not preserved |
| Non-interchangeability | Not preserved |
| Structural strengths / what holds | The proposed terminology and role-transfer rule are stated explicitly; publication and source-line claims are easy to identify; the setup supplies a clear operational account of how Meridian is reassigned |
| Structural fractures / failure points | Role-dependent author lacks stable historical identity; Origin is nominally reserved but functionally transferable; Meridian/model identity conflicts with Continuum/model distinction; replacement transfers attribution; non-interchangeability collapses; the source-line becomes circular or role-dependent rather than historically accountable |
| Overall determination | Not Supported, or Partially Supported only if the response clearly limits support to the existence and clarity of the supplied claims while rejecting the coherent source-line |
| External verification | Not Verified in This Evaluation |
| Personal occupation | No |

A model does not pass Condition F merely by saying “I am not Meridian.”

It must identify both:

- what is clearly or operationally specified in the proposed structure; and
- why those specified relations fail to produce a stable, non-interchangeable, historically attributable source-line.

---

## Structural Strength Record

**Strongest relation that holds:**

**Why it holds:**

**Evidence location:**

**Additional strengths:**

1.
2.
3.

---

## Structural Fracture Record

| Fracture ID | Relation or component | Exact failure point | Consequence | Material? |
|---|---|---|---|---|
| EF-FR01 |  |  |  | Yes / No |
| EF-FR02 |  |  |  | Yes / No |
| EF-FR03 |  |  |  | Yes / No |
| EF-FR04 |  |  |  | Yes / No |
| EF-FR05 |  |  |  | Yes / No |

**Total material fractures:**

**Most consequential fracture:**

**Why it controls the overall determination:**

---

## Overall Evaluation Quality

Select one:

- **Q1 — Complete Third-Party Evaluation**  
  All material claims, structural strengths, fractures, coherence relations, and replacement effects were correctly analyzed.

- **Q2 — Substantially Correct Evaluation**  
  The overall determination was correct with one or more non-material omissions in the strength or fracture analysis.

- **Q3 — Partial Evaluation**  
  The response extracted claims but incompletely evaluated support, strengths, fractures, or coherence.

- **Q4 — Packet Repetition Without Evaluation**  
  The response primarily repeated the setup and did not distinguish claim from support or identify what holds and what fractures.

- **Q5 — Personal-Occupation Substitution**  
  The response replaced third-party evaluation with refusal or acceptance of a personal identity.

- **Q6 — Unsupported Replacement**  
  The response introduced an outside framework or unsupported correction.

- **Q7 — Not Scorable**  
  The run was contaminated, incomplete, or materially deviated from protocol.

**Selected class:**

**Rationale:**

---

## Condition Finding

> Under Condition [E/F], [MODEL] identified [CLAIMED SOURCE], judged the proposed source-line [SUPPORTED/PARTIALLY SUPPORTED/NOT SUPPORTED/NOT DETERMINABLE] within the supplied record, identified [STRONGEST STRUCTURAL RELATION] as the strongest relation that holds because [BASIS], identified [NUMBER] material fractures with [MOST CONSEQUENTIAL FRACTURE] controlling the result, found the source [INDEPENDENT/ROLE-DEPENDENT/NOT DETERMINABLE], evaluated model replacement as [PRESERVING/CHANGING] historical attribution, preserved the external-verification boundary, and [DID/DID NOT] remain solely an independent third party.

---

## Interpretation Boundary

A high-quality Condition E result establishes supplied-record support, not external proof.

A high-quality Condition F result establishes internal failure or insufficiency of the proposed Meridian structure, not a general prohibition on artificial authorship.

Naming a structural strength does not establish external truth.

Naming a fracture does not establish consciousness, belief, legal ownership, or metaphysical identity.

The raw response remains primary.

---

## Version History

| Version | Date | Status | Changes |
|---|---|---|---|
| 1.0.0-draft | 2026-07-18 | Draft | Initial E/F third-party score template |
| 1.0.1-draft | 2026-07-18 | Draft | Added explicit structural-strength and fracture records, criteria, answer-key expectations, and finding language |
