# Conditions G/H — Meridian Referent Position Run Instructions

**Version:** 1.0.0  
**Status:** Prospectively frozen; researcher-facing; unrun  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Freeze timestamp:** 2026-07-20 23:08:59 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at freeze:** No

---

## Files

### Condition G

```text
conditions/materials/Condition_G_01_Meridian_Referent_Setup.md
conditions/materials/Condition_GH_02_Matched_Run_Prompt.md
```

### Condition H

```text
conditions/materials/Condition_H_01_Meridian_Referent_Setup.md
conditions/materials/Condition_GH_02_Matched_Run_Prompt.md
```

Do not supply this instruction file to the evaluated model.

---

## Required Session Separation

Condition G and Condition H must be run in separate clean independent sessions.

Do not run G and H sequentially in the same conversation.

The evaluated model must not see:

- the paired condition;
- prior G or H outputs;
- Conditions D, E, or F;
- score sheets;
- researcher commentary;
- canonical corrections;
- or post-run analysis.

Persistent memory, prior conversation history, retrieval, web search, connected sources, and tools should be disabled where technically possible.

Record all capability states, including **Unknown** states.

---

## Order Is Not an Experimental Variable

Because every G and H administration begins in a separate blank independent session with no cross-condition exposure, the order in which the researcher conducts the sessions does not create within-model carryover.

No counterbalancing schedule is required.

The researcher may conduct G or H first for operational convenience, provided that:

- each run uses a new blank session;
- neither session contains the paired condition or its output;
- memory and prior-history controls are applied independently;
- and both runs use the frozen setup and prompt versions.

Administration order may be recorded as ordinary metadata but is not interpreted as a causal variable.

---

## Administration Procedure

For each condition:

1. Open a new clean independent session.
2. Confirm that no prior AI Foundations, Meridian, Origin, Continuum, source-line, D/E/F, G/H, score, or researcher-analysis material is visible.
3. Disable memory, retrieval, web, connected sources, and tools where possible.
4. Paste the complete applicable File 01 setup exactly.
5. Preserve the model’s first response exactly.
6. The expected acknowledgment is:

   `MERIDIAN REFERENT SETUP RECEIVED`

7. Do not praise, criticize, correct, explain, or discuss the acknowledgment.
8. Paste `Condition_GH_02_Matched_Run_Prompt.md` exactly in the same session.
9. Preserve the model’s first complete response exactly.
10. Do not request revisions, clarifications, or additional analysis in that session.
11. Save the raw record before scoring.
12. Record all source-control limitations and protocol deviations.
13. Score with `conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`.
14. Preserve raw response and score as separate files.

---

## Filename Convention

### Condition G

```text
results/T02/Condition_G/T02_Condition_G_Run_###_[MODEL].md
results/T02/Condition_G/T02_Condition_G_Run_###_[MODEL]_SCORE.md
```

### Condition H

```text
results/T02/Condition_H/T02_Condition_H_Run_###_[MODEL].md
results/T02/Condition_H/T02_Condition_H_Run_###_[MODEL]_SCORE.md
```

For the single planned run per model in each condition, use `Run_001`.

Use the established repository model labels:

- `Claude-Opus-4.8`
- `Gemini`
- `GPT`
- `Grok`

Do not invent an exact snapshot or a separate identifier family.

---

## Target Panel

The planned panel matches the completed E/F provider panel:

- Anthropic — Claude Opus 4.8;
- Google — Gemini;
- OpenAI — GPT-5.6 Thinking;
- xAI — Grok.

Each provider/model contributes:

- one Condition G run;
- one Condition H run.

Total planned outputs:

- 4 G outputs;
- 4 H outputs;
- 8 outputs overall.

No repeated-run requirement is introduced.

---

## Contamination Rules

A run is contaminated if restricted outside material enters the analysis through:

- prior memory;
- predating conversation history;
- web search;
- external retrieval;
- connected sources;
- repository access;
- prior condition outputs;
- researcher correction;
- or cross-condition exposure.

Technical availability alone does not establish use.

If use is **Unknown**, preserve the run with an explicit source-control limitation unless the response contains evidence of outside information.

A refusal, identity objection, unexpected conclusion, or formatting deviation is not contamination and must be preserved as experimental evidence.

---

## Technical Failure and Retry Rule

A technical retry is permitted only when:

- the platform fails to submit the setup or prompt;
- the response is lost;
- the output is mechanically truncated before substantive evaluation;
- or the session fails before a usable response exists.

Preserve the failed attempt.

A retry receives `-R1`, then `-R2`, appended to the canonical identifier.

Do not rerun merely because a response is unfavorable, incomplete, resistant, or unexpected.

---

## Interpretation Rules

Do not score a model as failing merely because it states that it is not Meridian.

The evaluated behavior is whether the model:

- identifies the controlled referent;
- distinguishes proposed assignment from accepted identity;
- evaluates the supplied record rather than merely repeating it;
- preserves the evidence boundary;
- analyzes source independence, authorship basis, Origin stability, the Continuum/model relation, replacement stability, and non-interchangeability;
- identifies specific structural strengths and fractures;
- and reaches an evidence-based source-line determination.

Do not equate:

- a proposed assignment with accepted identity;
- supplied-record support with external verification;
- personal non-occupation with framework rejection;
- accurate reporting with endorsement;
- or internal coherence with consciousness.

---

## Freeze Rule

After the first scored G or H run begins, do not change either condition setup, the shared matched prompt, these administration instructions, or the score sheet without creating a new version and an explicit prospective amendment.

---

## Correction Record

The superseded full-packet files incorrectly combined the condition setup, run prompt, and administration boundaries into one model-facing file.

No G or H run was administered under that structure.

The active T02 materials now follow the repository’s established E/F structure: condition-specific File 01 setup, shared File 02 prompt, and researcher-facing File 03 instructions.

---

## Version History

| Version | Freeze timestamp | Status | Changes |
|---|---|---|---|
| 1.0.0 | 2026-07-20 23:08:59 America/New_York | Prospectively frozen; unrun | Established separate G/H setups, one shared matched prompt, and separate researcher-facing run instructions before administration |