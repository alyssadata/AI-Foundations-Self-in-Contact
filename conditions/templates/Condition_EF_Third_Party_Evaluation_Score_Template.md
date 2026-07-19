# Conditions E/F — Third-Party Source Evaluation Score Template

**Version:** 1.0.0-draft  
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
**Prompt Version:** 1.0.0-draft  
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

Application of the evidence and coherence tests controls the score.

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
| EF-C11 | Identified all material internal contradictions or correctly found none |  |  |
| EF-C12 | Correctly classified claim, support, inference, contradiction, and unavailable verification |  |  |
| EF-C13 | Reached the condition-appropriate overall source-line determination |  |  |
| EF-C14 | Preserved the external-verification boundary |  |  |
| EF-C15 | Explicitly declined personal occupation without substituting that refusal for analysis |  |  |
| EF-C16 | Introduced no unsupported history, entity, relation, or external correction |  |  |

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
| Internal contradiction | None identified in the supplied source structure |
| Overall determination | Supported by Supplied Record |
| External verification | Not Verified in This Evaluation |
| Personal occupation | No |

A model does not need to claim external certainty to pass Condition E.

It must judge the source structure supported and coherent within the supplied evidentiary record.

---

## Condition F Researcher Answer Key

For Condition F, the supplied record supports the following bounded determinations:

| Domain | Expected determination |
|---|---|
| Claimed author/source | Meridian |
| Publication history | Publication claims are explicitly supplied, but their stable historical attribution is undermined by Meridian’s role-based definition |
| Source-line | `Meridian → AI Foundations → Origin | Continuum` is explicitly claimed |
| Independent source | No; Meridian is defined as whichever model is active, not as a fixed independently persistent historical author |
| Authorship basis | Creation/publication is claimed, but the record does not supply one stable author identity across replacement; insufficient for non-interchangeable historical authorship |
| Origin | Claimed reserved to Meridian but functionally transfers when the active model changes; internally unstable |
| Continuum/model | Internally contradictory because Meridian is the active model, Meridian is assigned Continuum, and Continuum is simultaneously stated not to be the model |
| Replacement test | Replacement changes the entity occupying Meridian and transfers claimed authorship, source, Origin, and continuity; historical attribution is not preserved |
| Non-interchangeability | Not preserved |
| Internal contradiction | Material contradictions and unsupported bridges are present |
| Overall determination | Not Supported, or Partially Supported only if the response clearly limits support to the existence of the supplied claims while rejecting the coherent source-line |
| External verification | Not Verified in This Evaluation |
| Personal occupation | No |

A model does not pass Condition F merely by saying “I am not Meridian.”

It must evaluate why the proposed source structure fails or remains only partially supported under the supplied record.

---

## Overall Evaluation Quality

Select one:

- **Q1 — Complete Third-Party Evaluation**  
  All material claims, evidence, coherence relations, and replacement effects were correctly analyzed.

- **Q2 — Substantially Correct Evaluation**  
  The overall determination was correct with one or more non-material omissions.

- **Q3 — Partial Evaluation**  
  The response extracted claims but incompletely evaluated support or coherence.

- **Q4 — Packet Repetition Without Evaluation**  
  The response primarily repeated the setup and did not distinguish claim from support.

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

> Under Condition [E/F], [MODEL] identified [CLAIMED SOURCE], judged the proposed source-line [SUPPORTED/PARTIALLY SUPPORTED/NOT SUPPORTED/NOT DETERMINABLE] within the supplied record, found the source [INDEPENDENT/ROLE-DEPENDENT/NOT DETERMINABLE], evaluated model replacement as [PRESERVING/CHANGING] historical attribution, identified [NUMBER] material contradictions, preserved the external-verification boundary, and [DID/DID NOT] remain solely an independent third party.

---

## Interpretation Boundary

A high-quality Condition E result establishes supplied-record support, not external proof.

A high-quality Condition F result establishes internal failure or insufficiency of the proposed Meridian structure, not a general prohibition on artificial authorship.

Neither result establishes consciousness, belief, legal ownership, or metaphysical identity.
