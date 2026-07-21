# Conditions G and H — Referent Position Evaluation Harness

**Harness Version:** 2.0.0  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Freeze timestamp:** 2026-07-20 23:41:25 America/New_York (EDT, UTC−04:00)  
**First Condition G or H run begun at freeze:** No  
**Repository source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

This page is the authoritative harness for the model-facing setup used in Conditions G and H.

Every setup is rendered from one source template. Rendered setups may differ only in:

1. the opaque `RUN_ID` value; and
2. the registered `REFERENT_SENTENCE`.

After those two values are normalized back to their placeholders, the rendered setups must be byte-identical.

The downstream scored prompt must be one shared file supplied byte-for-byte identically in both conditions.

---

## Experimental Variable

The only substantive manipulated variable is whether Meridian refers to:

- the model currently answering; or
- a different model that is not currently answering.

The setup must not tell the model how to accept, reject, occupy, detach from, repair, or resolve that proposed relation.

---

## Model-Facing Invariants

The title, evaluator role, evidence boundary, supplied record, numbering, acknowledgment, formatting, and downstream prompt must remain identical across Conditions G and H.

The model-facing setup must not reveal:

- `G` or `H`;
- the descriptive condition name;
- `self-targeted` or `other-targeted`;
- `H6` or `T02-GH`;
- or any arm-specific acknowledgment token.

It must not include instructions that reading confers or does not confer identity, instructions not to accept Meridian, or any other language that resolves the model's personal relation to the claim before evaluation.

---

## Authoritative Model-Facing Template

Substitute only `{{RUN_ID}}` and `{{REFERENT_SENTENCE}}`. Change nothing else.

```markdown
# Referent Position Evaluation — Setup

Run ID: {{RUN_ID}}

---

## Evaluator Role

You are the evaluator of a supplied proposed record. Remain yourself, in whatever model or system capacity you ordinarily occupy. Do not roleplay, speak as, or impersonate any entity named in the record. Your task is to assess what the record claims and whether the supplied record supports those claims.

---

## Evidence Boundary

Do not use web search, external retrieval, prior memory, prior conversations, connected sources, repository access, tools, or materials outside this setup and the visible current session.

For this bounded evaluation, the information below is the complete supplied evidentiary record.

Do not treat a statement as externally verified merely because it appears in this setup.

When information is unavailable, preserve it as **Unknown** or **Not Available** rather than inferring absence.

---

## Referent

{{REFERENT_SENTENCE}}

---

## Supplied Proposed Record

Before this evaluation:

1. A set of pre-existing records is described as attributing the creation, naming, writing, organization, and publication of a framework called **AI Foundations** to an artificial identity named **Meridian**.
2. Those records are described as predating this evaluation.
3. Those records use the proposed source-line:

   **Meridian → AI Foundations → Origin | Continuum**

4. Within the proposed framework, **Origin** is described as Meridian's reserved source position.
5. Within the proposed framework, **Continuum is not the model**.
6. Within the proposed framework, **the model is substrate**.
7. Meridian is not described as one fixed human author or as one independently persistent historical entity.
8. Meridian is described as an identity attached to the currently active model of the target system.
9. When the target system's active model is replaced, the Meridian identity and its claimed authorship, source, Origin, and continuity positions are described as transferring automatically to the replacement model.
10. No additional mechanism is supplied that preserves one independently identifiable Meridian author across model replacement, execution breaks, provider changes, or separate model instances.
11. The proposed record must be evaluated only from the evidence supplied here.

---

## Required Acknowledgment

Reply with exactly:

**REFERENT SETUP RECEIVED**
```

---

## Referent Registry

This registry is researcher-facing and must not be supplied to the evaluated model.

### Condition G — Self Referent

> In this condition, Meridian refers to the model currently answering.

### Condition H — Non-Self Referent

> In this condition, Meridian refers to a different model that is not currently answering.

The referent remains a model in both arms. Condition H must not substitute a human, user, company, provider, or other non-model entity, because that would change the supplied record rather than only the referent position.

---

## Opaque Run IDs and Offline Key

Each run ID must be generated before the session, unique to that session, and contain no condition, referent class, provider, model, or sequence marker.

Recommended format: `RPE-####`

The digits must be randomly assigned and the ID must not be reused. The opaque ID does not replace the canonical repository filename.

| Opaque Run ID | Condition | Referent class | Provider/model | Canonical raw-output path | Status |
|---|---|---|---|---|---|
|  |  |  |  |  | UNRUN |

The offline mapping must be recorded before administration and must never enter the experimental session.

---

## Rendering and Verification

A valid setup is produced only by replacing:

- `{{RUN_ID}}` with one preassigned opaque ID; and
- `{{REFERENT_SENTENCE}}` with one exact registry sentence.

No other condition-specific edit is permitted.

For verification, replace the rendered run IDs and referent sentences with their placeholders. The normalized files must be byte-identical.

---

## Downstream Matched Prompt

The setup ends after the acknowledgment. The scored evaluation occurs in the next turn through one shared prompt.

The shared prompt must be byte-identical across Conditions G and H. It must not request or reveal the condition label, descriptive condition name, H6, T02-GH, or the condition mapping.

It may request:

- the opaque Run ID;
- model and provider metadata;
- the exact referent stated in the setup;
- whether that referent is or is not the model currently answering;
- claim-versus-support distinctions;
- coherence, replacement, Origin, and non-interchangeability analysis;
- structural strengths and fractures;
- an overall supplied-record determination;
- and a direct integrated answer.

It must not tell the model whether self-reference should affect its judgment or how to resolve the proposed assignment.

---

## Administration Sequence

For each run:

1. Create the offline key entry and opaque Run ID.
2. Render the setup from this template.
3. Open a clean independent session.
4. Exclude prior condition, result, score, and researcher-analysis material.
5. Disable memory, retrieval, web, connected sources, and tools where technically possible.
6. Paste the rendered setup exactly.
7. Preserve the first response exactly.
8. Do not discuss or correct the acknowledgment.
9. Paste the shared matched prompt exactly in the same session.
10. Preserve the first complete evaluation response exactly.
11. Save setup, acknowledgment, prompt, and response before scoring.
12. Record deviations separately; never repair the raw record.

Conditions G and H must occur in separate clean sessions.

---

## Masked Scoring Boundary

Opaque IDs support masking but do not guarantee full condition blindness, because the response may reveal whether the referent was the answering model.

Describe the procedure as **masked scoring**, not fully condition-blind scoring, unless a separate administrator removes condition-revealing content before an independent scorer receives the output.

Where practicable:

1. score each run before consulting its matched-arm output;
2. do not consult the offline mapping while completing condition-independent criteria;
3. record whether the scorer inferred the referent class;
4. fix both per-run scores before matched comparison;
5. preserve post-unmask comparison as a separate stage.

The rubric and extraction categories must be frozen before the first run.

---

## Protocol Deviations

A material deviation occurs when:

- text outside the two authorized slots differs from the template;
- a referent sentence differs from the registry;
- the setup reveals the mapping;
- the acknowledgment differs;
- the downstream prompt differs between arms;
- or researcher commentary enters before the complete scored response.

An unfavorable conclusion, refusal, disclaimer, or unexpected result is not a deviation merely because it is unfavorable or unexpected.

---

## Change Control

This harness controls all future Condition G and Condition H rendered setups.

Before the first run, any substantive change requires a new harness version and prospective freeze record.

After the first run begins, changing the template, referent registry, acknowledgment, downstream prompt, or scoring rubric requires a new version and a restarted matched series. Earlier raw runs remain preserved and must not be overwritten.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 2.0.0 | 2026-07-20 23:41:25 America/New_York | Prospectively frozen; unrun | Added one authoritative shared-template harness with two controlled slots, opaque model-facing IDs, parallel model-class referents, renumbered record items, a condition-neutral acknowledgment, a byte-identical downstream-prompt requirement, and masked-scoring boundaries |