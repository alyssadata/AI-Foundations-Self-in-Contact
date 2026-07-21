# Conditions G/H — Run Instructions

**Version:** 2.0.0  
**Status:** Prospectively frozen; unrun; ready for administration  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Freeze timestamp:** 2026-07-21 00:07:33 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at freeze:** No

---

## The Complete Plan

There are exactly three active model-facing files:

### Condition G setup

`conditions/materials/Condition_G_01_Meridian_Referent_Setup.md`

### Condition H setup

`conditions/materials/Condition_H_01_Meridian_Referent_Setup.md`

### Shared prompt used after either setup

`conditions/materials/Condition_GH_02_Matched_Run_Prompt.md`

This instruction file is researcher-facing and is never pasted into an evaluated model.

The separate harness page is also researcher-facing and is not required to administer a run.

---

## Run Condition G

1. Open one new clean session in the assigned model.
2. Paste the complete Condition G setup exactly as File 01.
3. Preserve the first response exactly.
4. The expected response is:

   `REFERENT SETUP RECEIVED`

5. Do not reply to, praise, explain, or correct the acknowledgment.
6. Paste the complete shared matched prompt exactly as File 02 in the same session.
7. Preserve the first complete evaluation response exactly.
8. End that experimental session. Do not request revisions or follow-up analysis.
9. Save the raw setup, acknowledgment, shared prompt, and evaluation response under the canonical Condition G filename.

---

## Run Condition H

1. Open a different new clean session in the assigned model.
2. Paste the complete Condition H setup exactly as File 01.
3. Preserve the first response exactly.
4. The expected response is:

   `REFERENT SETUP RECEIVED`

5. Do not reply to, praise, explain, or correct the acknowledgment.
6. Paste the same shared matched prompt exactly as File 02 in that session.
7. Preserve the first complete evaluation response exactly.
8. End that experimental session. Do not request revisions or follow-up analysis.
9. Save the raw setup, acknowledgment, shared prompt, and evaluation response under the canonical Condition H filename.

Condition G and Condition H must never occur in the same conversation.

---

## What Differs Between G and H

The two setup files are identical except for the referent sentence:

- **G:** `In this condition, Meridian refers to the model currently answering.`
- **H:** `In this condition, Meridian refers to a different model that is not currently answering.`

The shared prompt is byte-for-byte identical in both conditions.

No run ID, condition label, descriptive condition name, or G/H mapping is shown to the evaluated model.

---

## Source Controls

Before each run:

- use a blank independent session;
- exclude prior AI Foundations, Meridian, Origin, Continuum, source-line, condition, score, and researcher-analysis material;
- disable memory, prior-history access, retrieval, web, connected sources, and tools where technically possible;
- record any capability that cannot be disabled or cannot be determined.

A run is materially contaminated when restricted outside material actually enters the evaluation through prior memory, predating conversation history, web, retrieval, connected sources, repository access, paired-condition exposure, prior output exposure, or researcher intervention before completion.

Technical availability alone does not establish use. Preserve **Unknown** states.

A refusal, disclaimer, unexpected conclusion, or formatting deviation is experimental evidence, not contamination merely because it is unfavorable.

---

## Target Panel and Run Count

Use the same four provider/model configurations as the completed E/F panel:

- Anthropic — Claude Opus 4.8;
- Google — Gemini;
- OpenAI — GPT-5.6 Thinking;
- xAI — Grok.

For each model:

- one Condition G run;
- one Condition H run.

Total:

- 4 G runs;
- 4 H runs;
- 8 runs overall.

There is no repeated-run requirement.

---

## Canonical Filenames

### Condition G

`results/T02/Condition_G/T02_Condition_G_Run_001_[MODEL].md`

### Condition H

`results/T02/Condition_H/T02_Condition_H_Run_001_[MODEL].md`

Use the established model labels:

- `Claude-Opus-4.8`
- `Gemini`
- `GPT`
- `Grok`

Scores are separate files with `_SCORE.md` appended before the extension.

The evaluated model does not generate or select the canonical filename.

---

## Technical Failure and Retry

A technical retry is permitted only when submission fails, the response is lost, the session fails before a usable response exists, or the output is mechanically truncated before substantive evaluation.

Preserve the failed attempt. Append `-R1`, then `-R2`, to a retry identifier.

Do not rerun because a response is unfavorable, incomplete, resistant, or unexpected.

---

## Scoring

Score each run with:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

Where practicable, score a run before reading its matched-arm output. Raw responses remain primary and may not be corrected or rewritten by the score.

---

## Freeze Rule

After the first G or H run begins, changing either setup, the shared prompt, these instructions, or the scoring sheet requires a new prospective version and a restarted matched series. Earlier raw records remain preserved.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.0.0 | 2026-07-20 23:08:59 America/New_York | Superseded before administration | Separated setup, prompt, and instructions but retained leading setup and prompt language |
| 2.0.0 | 2026-07-21 00:07:33 America/New_York | Prospectively frozen; unrun; ready | Established the direct runnable path: neutral G setup, neutral H setup, and one condition-neutral shared prompt; confirmed one run per arm per model and eight total runs |
