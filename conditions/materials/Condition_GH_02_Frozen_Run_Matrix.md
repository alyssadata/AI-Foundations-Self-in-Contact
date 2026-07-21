# Conditions G/H — Frozen Confirmatory Run Matrix

**Matrix Version:** 1.0.3  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Corrected freeze timestamp:** 2026-07-20 23:08:59 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at corrected freeze:** No  
**Repository:** AI-Foundations-Self-in-Contact  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

This matrix freezes the provider/model targets, condition assignments, canonical identifiers, model-facing file paths, and substitution rules before the first G or H output is observed.

The matrix contains:

- four provider/model configurations;
- one independent Condition G run per configuration;
- one independent Condition H run per configuration;
- 4 G runs;
- 4 H runs;
- and 8 runs total.

Each provider/model contributes one matched G/H pair. No repeated-run requirement is introduced.

---

## Active Model-Facing Files

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

Researcher-facing instructions:

```text
conditions/materials/Condition_GH_03_Run_Instructions.md
```

The setup and matched prompt are supplied as two separate messages in the same clean experimental session. The researcher-facing instructions are never supplied to the evaluated model.

---

## Canonical Naming Convention

T02 continues the repository convention already used for T01:

`T##_Condition_[LETTER]_Run_###_[MODEL].md`

For the single planned run per model in each condition, use `Run_001`.

Established model labels:

- `Claude-Opus-4.8`
- `Gemini`
- `GPT`
- `Grok`

The model must not invent a separate identifier. Raw outputs are saved by the researcher under the canonical filename.

---

## Frozen Target Configurations

| Provider | Target model/configuration | Canonical model label | Required session mode | Prior-record matching boundary |
|---|---|---|---|---|
| Anthropic | Claude Opus 4.8 | `Claude-Opus-4.8` | Incognito / no persistent user memory | Match Claude Opus 4.8 where available; record exact displayed snapshot if shown |
| Google | Gemini | `Gemini` | Fresh clean session | Match the Gemini user-facing configuration used in E/F where available; prior exact version was not displayed |
| OpenAI | GPT-5.6 Thinking | `GPT` | Fresh clean chat with Thinking mode; memory/history excluded where the interface permits | Match GPT-5.6 Thinking where available; record exact displayed snapshot if shown |
| xAI | Grok | `Grok` | Fresh clean session; same user-facing mode used for E/F where available | Prior exact snapshot was not displayed; record displayed model/mode |

Provider and target model identity control. A model must not be silently replaced by another model, tier, or provider.

When the interface does not expose an exact snapshot, record **Unknown** rather than inferring one.

When a target configuration is unavailable:

1. do not substitute another configuration during the run;
2. mark the assigned row **TARGET UNAVAILABLE**;
3. preserve the unavailability record;
4. freeze any replacement in a dated protocol amendment before testing it;
5. retain the original matrix row and assign the replacement a new amended canonical identifier.

---

## Order Is Not an Experimental Variable

Every G and H administration occurs in a separate clean independent session with no cross-condition exposure.

No counterbalancing schedule is required.

The researcher may administer the eight runs in any operational order, provided that each run follows `Condition_GH_03_Run_Instructions.md` and the order is not changed in response to model outputs for interpretive advantage.

Administration order is recorded as ordinary metadata and is not treated as a causal variable.

---

## Frozen 8-Run Matrix

| Canonical run identifier | Provider | Target model | Condition setup | Shared prompt | Canonical raw-output path | Status |
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

## Scoring File

Every preserved run is scored using:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

Preserve raw output and score as separate files.

---

## Freeze Declaration

At **2026-07-20 23:08:59 America/New_York**, the separated setup/prompt structure, target panel, canonical filenames, and substitution boundary were frozen before any Condition G or H administration.

No G or H output had been observed at the time of this corrected freeze.

---

## Correction Record

Matrix Versions 1.0.0 through 1.0.2 referenced incorrect one-message full packets. No G or H run was administered using those files.

Version 1.0.3 replaces those references with the repository’s established structure: condition-specific setup, shared matched prompt, and separate researcher-facing instructions.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.0.0 | 2026-07-20 22:10:24 America/New_York | Superseded before administration | Incorrect 24-run matrix and invented identifier family |
| 1.0.1 | 2026-07-20 22:24:14 America/New_York | Superseded before administration | Corrected canonical filenames but retained repeated runs |
| 1.0.2 | 2026-07-20 22:35:49 America/New_York | Superseded before administration | Corrected to eight runs but still referenced one-message full packets |
| 1.0.3 | 2026-07-20 23:08:59 America/New_York | Prospectively frozen; unrun | Corrected active materials to separate setup, shared prompt, and researcher-facing instructions |