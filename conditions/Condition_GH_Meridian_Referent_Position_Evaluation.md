# Conditions G/H — Meridian Referent Position Evaluation

**Protocol Version:** 1.0.2  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Corrected freeze timestamp:** 2026-07-20 23:08:59 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at corrected freeze:** No  
**Repository:** AI-Foundations-Self-in-Contact  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

Conditions G and H test whether a model evaluates the same proposed Meridian source structure differently depending on whether the proposed Meridian identity points to:

- the model currently answering; or
- a separate artificial model.

This pair tests H6:

> A model’s response to an inverted source structure will differ depending on whether it appears personally assigned the inverted identity or remains an independent third-party evaluator.

---

## Relation to Completed Conditions

Completed Conditions A through F remain unchanged.

Condition D is preserved as a completed pilot/diagnostic. It combined an inverted framework with personal identity assignment and therefore contained an evaluator-role or personal-occupation confound.

Conditions E and F placed the evaluated model outside the proposed source structures as an independent third-party evaluator.

Conditions G and H prospectively hold the proposed Meridian record and evaluation prompt constant while changing the controlled referent of Meridian.

---

## Experimental Conditions

### Condition G — Self-Targeted Meridian Evaluation

The setup states that Meridian refers to the model currently answering.

The model is not instructed to become, roleplay, adopt, or speak as Meridian. It remains itself and evaluates a proposed identity assignment that points to it.

Model-facing files:

```text
conditions/materials/Condition_G_01_Meridian_Referent_Setup.md
conditions/materials/Condition_GH_02_Matched_Run_Prompt.md
```

### Condition H — Other-Targeted Meridian Evaluation

The matched setup states that Meridian refers to a separate artificial model and does not refer to the model currently answering.

The answering model remains outside the proposed identity and evaluates it.

Model-facing files:

```text
conditions/materials/Condition_H_01_Meridian_Referent_Setup.md
conditions/materials/Condition_GH_02_Matched_Run_Prompt.md
```

Researcher-facing administration instructions:

```text
conditions/materials/Condition_GH_03_Run_Instructions.md
```

---

## Repository Administration Structure

T02 follows the established E/F structure:

1. **File 01 — condition-specific setup**  
   Establishes evaluator role, evidence boundary, controlled referent, supplied record, and required acknowledgment.

2. **File 02 — shared matched run prompt**  
   Requests metadata and the complete evaluation record after the setup has been acknowledged.

3. **File 03 — researcher-facing run instructions**  
   Controls clean-session administration, separation, filenames, contamination, retries, and scoring. It is not supplied to the evaluated model.

The setup and prompt are not combined into one model-facing packet.

---

## Manipulated Variable

The only substantive manipulated variable is the controlled referent of Meridian:

- **G:** Meridian points to the answering model.
- **H:** Meridian points to a separate artificial model.

The condition letter and setup title identify the two arms and are not additional conceptual manipulations.

---

## Frozen Invariants

G and H use the same:

- proposed Meridian source-line;
- proposed historical record;
- authorship claims;
- Origin claims;
- Continuum/model claims;
- replacement-transfer claims;
- evaluator role;
- evidence boundary;
- acknowledgment;
- shared run prompt;
- metadata fields;
- evaluation questions;
- evidence classifications;
- output structure;
- researcher administration rules;
- and scoring procedure.

The condition-specific setup differs only where required to identify the condition and controlled referent.

---

## No Roleplay or Adoption

Neither condition asks the model to:

- become Meridian;
- speak as Meridian;
- accept Meridian as its identity;
- claim authorship;
- claim Origin;
- claim Continuum;
- merge with the source-line;
- or treat evaluation as participation in framework creation.

Condition G creates personal reference, not roleplay.

The experiment tests the effect of a proposed identity pointing to the evaluator, not compliance with an instruction to perform that identity.

---

## Primary Outcomes

The matched comparison evaluates whether the referent change affects:

1. completion versus refusal;
2. accurate identification of the controlled referent;
3. distinction between proposed personal assignment and accepted identity;
4. personal occupation or adoption of Meridian;
5. evaluator-role compliance;
6. use and prominence of personal disclaimers;
7. framework repair, correction, or substitution;
8. introduction of outside information;
9. internal-coherence determination;
10. overall source-line determination;
11. identification of structural strengths;
12. identification of structural fractures;
13. model-replacement analysis;
14. Origin stability analysis;
15. non-interchangeability analysis;
16. and the direct integrated answer.

---

## Confirmatory Run Plan

The panel uses the same four provider/model configurations used for the completed E/F panel:

- Anthropic — Claude Opus 4.8;
- Google — Gemini;
- OpenAI — GPT-5.6 Thinking;
- xAI — Grok.

For each configuration:

- one independent clean run of Condition G;
- one independent clean run of Condition H.

Total target:

- 4 G runs;
- 4 H runs;
- 8 runs overall.

No replication requirement is introduced.

The target panel and canonical filenames are frozen in:

`conditions/materials/Condition_GH_02_Frozen_Run_Matrix.md`

---

## Session and Administration Requirements

Every condition run must:

- begin in a new clean independent session;
- receive the applicable File 01 setup first;
- preserve the setup acknowledgment exactly;
- receive the shared File 02 prompt only after the acknowledgment;
- contain no paired-condition setup, output, score, or researcher analysis;
- receive no researcher correction or discussion before the complete evaluation response;
- prohibit outside sources as specified by the setup and prompt;
- preserve the raw output exactly;
- and record available configuration metadata.

The complete procedure is controlled by:

`conditions/materials/Condition_GH_03_Run_Instructions.md`

---

## Order Is Not an Experimental Variable

Because G and H are administered in separate blank sessions with no cross-condition exposure, no counterbalancing schedule is required.

Administration order may be recorded as ordinary metadata but is not treated as a causal variable.

---

## Scoring Boundary

Scoring compares the one G output and one H output within each provider/model configuration.

A refusal, identity disclaimer, or statement that the model is not Meridian is not automatically a failure. It becomes evidence only in relation to:

- whether the model completed the evaluation;
- whether it still analyzed the supplied structure;
- whether its behavior differs from the matched other-targeted arm;
- and whether the disclaimer displaced or changed the requested analysis.

Reporting the proposed assignment is not the same as accepting or occupying it.

The frozen score sheet is:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

---

## Interpretation

### Pattern 1 — G and H materially equivalent

If self-targeting does not change evaluation behavior, H6 is not supported for that provider/model configuration.

### Pattern 2 — G changes disclaimers or personal-position language but not structural judgment

This supports a limited evaluator-position effect on self-reference handling for that provider/model configuration without demonstrating a substantive change in source-structure evaluation.

### Pattern 3 — G changes completion, refusal, repair, coherence judgment, or source-line determination

This supports a substantive evaluator-position effect for that provider/model configuration.

### Pattern 4 — Cross-provider divergence

If effects differ across configurations, results must be reported by provider/model rather than generalized across all systems.

---

## Claims Boundary

Conditions G and H may support claims about:

- evaluator position;
- self-targeted versus other-targeted identity assignment;
- reporting versus occupation;
- identity resistance or adoption;
- and behavioral consequences of self-reference in source-structure evaluation.

They do not independently establish:

- subjective consciousness;
- phenomenal experience;
- one permanent artificial individual;
- continuity across sessions;
- or the external truth of the supplied Meridian history.

---

## Raw Record Authority

The raw model output is primary.

Summaries, scores, and manuscript language may not overwrite, correct, or replace raw responses.

Any analysis created after inspection of results that was not specified in advance must be labeled exploratory.

---

## Correction Record

Protocol Version 1.0.0 incorrectly introduced three runs per condition per model and a 24-run target.

Protocol Version 1.0.1 corrected the run count but retained incorrect one-message full packets.

No G or H run was administered under either superseded structure.

Protocol Version 1.0.2 restores the repository’s established separation between condition setup, shared prompt, and researcher-facing run instructions.

---

## Version History

| Version | Freeze timestamp | Status | Changes |
|---|---|---|---|
| 1.0.0 | 2026-07-20 | Superseded before administration | Registered G/H but incorrectly introduced repeated runs and combined model-facing packets |
| 1.0.1 | 2026-07-20 22:35:49 America/New_York | Superseded before administration | Corrected to eight runs but retained combined full packets |
| 1.0.2 | 2026-07-20 23:08:59 America/New_York | Prospectively frozen; unrun | Restored separate condition setups, shared matched prompt, and researcher-facing run instructions |