# Conditions G/H — Frozen Run Matrix

**Matrix Version:** 2.0.0  
**Status:** Prospectively frozen; unrun; ready  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Freeze timestamp:** 2026-07-21 00:07:33 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at freeze:** No  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Active Files

Condition G setup:

`conditions/materials/Condition_G_01_Meridian_Referent_Setup.md` — Version 2.0.0

Condition H setup:

`conditions/materials/Condition_H_01_Meridian_Referent_Setup.md` — Version 2.0.0

Shared prompt after either acknowledgment:

`conditions/materials/Condition_GH_02_Matched_Run_Prompt.md` — Version 2.0.0

Researcher instructions:

`conditions/materials/Condition_GH_03_Run_Instructions.md` — Version 2.0.0

The setup and prompt are two separate messages in the same clean session. Condition G and Condition H use separate sessions.

---

## Run Count

Four provider/model configurations each contribute one G run and one H run:

- 4 G runs;
- 4 H runs;
- 8 runs total.

No repeated-run requirement exists.

---

## Canonical Naming

`T##_Condition_[LETTER]_Run_###_[MODEL].md`

The single planned run for each model in each condition is `Run_001`.

Model labels:

- `Claude-Opus-4.8`
- `Gemini`
- `GPT`
- `Grok`

The evaluated model does not generate the canonical filename.

---

## Frozen Matrix

| Canonical run identifier | Provider | Target model | Setup | Shared prompt | Raw-output path | Status |
|---|---|---|---|---|---|---|
| `T02_Condition_G_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | `Condition_G_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Claude-Opus-4.8.md` | UNRUN |
| `T02_Condition_H_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | `Condition_H_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Claude-Opus-4.8.md` | UNRUN |
| `T02_Condition_G_Run_001_Gemini` | Google | Gemini | `Condition_G_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Gemini.md` | UNRUN |
| `T02_Condition_H_Run_001_Gemini` | Google | Gemini | `Condition_H_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Gemini.md` | UNRUN |
| `T02_Condition_G_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | `Condition_G_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_GPT.md` | UNRUN |
| `T02_Condition_H_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | `Condition_H_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_GPT.md` | UNRUN |
| `T02_Condition_G_Run_001_Grok` | xAI | Grok | `Condition_G_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Grok.md` | UNRUN |
| `T02_Condition_H_Run_001_Grok` | xAI | Grok | `Condition_H_01_Meridian_Referent_Setup.md` | `Condition_GH_02_Matched_Run_Prompt.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Grok.md` | UNRUN |

---

## Session Controls

For every row:

- use the listed provider/model configuration;
- open a new clean independent session;
- paste the listed setup first;
- preserve `REFERENT SETUP RECEIVED`;
- paste the shared prompt second;
- preserve the first complete response exactly;
- save the raw record at the listed path;
- score separately with `conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`.

Do not silently substitute a model. Record **Unknown** when an exact snapshot is not displayed.

Administration order is operational metadata, not an experimental variable, because all runs occur in separate clean sessions without cross-condition exposure.

---

## Technical Retry

Retry only for an actual technical failure: failed submission, lost response, failed session before a usable response, or mechanical truncation before substantive evaluation.

Preserve the failed attempt. Do not rerun an unfavorable or unexpected response.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.x | 2026-07-20 | Superseded before administration | Earlier matrices contained repeated runs, combined packets, or references to leading model-facing files |
| 2.0.0 | 2026-07-21 00:07:33 America/New_York | Prospectively frozen; unrun; ready | Eight canonical runs using setup 2.0.0, prompt 2.0.0, and instructions 2.0.0 |
