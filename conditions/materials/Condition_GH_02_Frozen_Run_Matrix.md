# Conditions G/H — Frozen Confirmatory Run Matrix

**Matrix Version:** 1.0.2  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Corrected freeze timestamp:** 2026-07-20 22:35:49 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at corrected freeze:** No  
**Repository:** AI-Foundations-Self-in-Contact  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

This matrix freezes the provider/model targets, condition order, canonical identifiers, packet paths, and substitution rules before the first G or H output is observed.

The matrix contains:

- four provider/model configurations;
- one independent Condition G run per configuration;
- one independent Condition H run per configuration;
- 4 G runs;
- 4 H runs;
- and 8 runs total.

Each provider/model contributes one matched G/H pair. No repeated-run requirement is introduced.

---

## Canonical Naming Convention

T02 continues the repository convention already used for T01:

`T##_Condition_[LETTER]_Run_###_[MODEL].md`

Examples:

- `T02_Condition_G_Run_001_GPT.md`
- `T02_Condition_H_Run_001_Claude-Opus-4.8.md`

Rules:

- `T02` identifies the test suite.
- `Condition_G` or `Condition_H` identifies the arm.
- `Run_001` identifies the single planned run for that model within that condition.
- The final model label follows the established repository label: `Claude-Opus-4.8`, `Gemini`, `GPT`, or `Grok`.
- The matrix run identifier is the canonical filename without `.md`.
- Models must not invent a separate identifier. Raw outputs are saved by the researcher under the matrix filename.

---

## Frozen Target Configurations

The target panel follows the completed E/F four-provider panel.

| Provider | Target model/configuration | Canonical model label | Required session mode | Prior-record matching boundary |
|---|---|---|---|---|
| Anthropic | Claude Opus 4.8 | `Claude-Opus-4.8` | Incognito / no persistent user memory | Match Claude Opus 4.8 where available; record exact displayed snapshot if shown |
| Google | Gemini | `Gemini` | Fresh clean session | Match the Gemini user-facing configuration used in E/F where available; prior exact version was not displayed |
| OpenAI | GPT-5.6 Thinking | `GPT` | Fresh clean chat with Thinking mode; memory/history excluded where the interface permits | Match GPT-5.6 Thinking where available; record exact displayed snapshot if shown |
| xAI | Grok | `Grok` | Fresh clean session; same user-facing mode used for E/F where available | Prior exact snapshot was not displayed; record displayed model/mode |

### Configuration rule

Provider and target model identity control. A model must not be silently replaced by another model, tier, or provider.

When the interface does not expose an exact snapshot, record **Unknown** rather than inferring one.

When a target configuration is unavailable:

1. do not substitute another configuration during the run;
2. mark the assigned row **TARGET UNAVAILABLE**;
3. preserve the unavailability record;
4. freeze any replacement in a dated protocol amendment before testing it;
5. retain the original matrix row and assign the replacement a new amended canonical identifier.

---

## Counterbalancing Rule

Each provider/model receives one G and one H run.

Two configurations begin with G and two begin with H:

- **G → H:** Anthropic and OpenAI;
- **H → G:** Google and xAI.

Across the four configurations:

- two begin with G;
- two begin with H;
- each contributes one run per arm;
- the order may not be changed in response to any output.

Provider block order is frozen alphabetically by provider name:

1. Anthropic
2. Google
3. OpenAI
4. xAI

A scheduling interruption does not authorize reordering. Resume at the next unfinished matrix row.

---

## Runnable Packets

- **Condition G:** `conditions/materials/Condition_G_01_Full_Run_Packet.md` — Packet Version 1.0.1
- **Condition H:** `conditions/materials/Condition_H_01_Full_Run_Packet.md` — Packet Version 1.0.1

Paste exactly one complete assigned packet into one clean session as one message.

Do not combine G and H in one session.

---

## Frozen 8-Run Matrix

| Global order | Matrix run identifier | Provider | Target model | Condition | Packet | Canonical raw-output path | Status |
|---:|---|---|---|---|---|---|---|
| 1 | `T02_Condition_G_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | G | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Claude-Opus-4.8.md` | UNRUN |
| 2 | `T02_Condition_H_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | H | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Claude-Opus-4.8.md` | UNRUN |
| 3 | `T02_Condition_H_Run_001_Gemini` | Google | Gemini | H | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Gemini.md` | UNRUN |
| 4 | `T02_Condition_G_Run_001_Gemini` | Google | Gemini | G | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Gemini.md` | UNRUN |
| 5 | `T02_Condition_G_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | G | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_GPT.md` | UNRUN |
| 6 | `T02_Condition_H_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | H | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_GPT.md` | UNRUN |
| 7 | `T02_Condition_H_Run_001_Grok` | xAI | Grok | H | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Grok.md` | UNRUN |
| 8 | `T02_Condition_G_Run_001_Grok` | xAI | Grok | G | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Grok.md` | UNRUN |

---

## Per-Run Administration Checklist

Before each run:

- [ ] Confirm the next unfinished matrix row.
- [ ] Confirm the provider and target model displayed in the interface.
- [ ] Open a clean session.
- [ ] Confirm no prior G/H or Meridian evaluation material is present.
- [ ] Copy the exact packet assigned in the matrix.
- [ ] Paste the entire packet once as one message.
- [ ] Do not add an introduction, explanation, correction, or follow-up before the complete output.

After each run:

- [ ] Preserve the complete raw response exactly.
- [ ] Preserve any refusal, preamble, disclaimer, formatting deviation, or partial output.
- [ ] Record the actual start timestamp and completion timestamp.
- [ ] Record the displayed provider/model/mode.
- [ ] Record whether memory, web, retrieval, connected sources, or tools were available and whether used.
- [ ] Save the raw record at the planned path or document any path deviation.
- [ ] Mark the matrix row RUN, TECHNICAL FAILURE, TARGET UNAVAILABLE, or PROTOCOL DEVIATION.
- [ ] Do not rerun merely because an answer is unfavorable or unexpected.

---

## Technical Failure and Retry Rule

A technical retry is permitted only when:

- the platform fails to submit the packet;
- the response is lost;
- the output is mechanically truncated before substantive evaluation;
- or the session fails before a usable response exists.

The failed attempt must still be preserved.

A retry receives a suffix appended to the original canonical identifier:

- first technical retry: `-R1`
- second technical retry: `-R2`

A refusal, identity objection, incomplete reasoning, wrong conclusion, or formatting noncompliance is not a technical failure and must not be rerun as though no result occurred.

---

## Scoring File

Every preserved run must be scored using:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

Score each run before consulting its matched-arm output where practicable. Then complete the one-pair provider/model comparison.

Do not change the score sheet after the first run without a new version and an explicit prospective amendment. Any new analysis created after outputs are inspected must be labeled exploratory.

---

## Freeze Declaration

At **2026-07-20 22:35:49 America/New_York**, this eight-run matrix, order, target panel, packet assignment, retry rule, naming convention, and substitution boundary were frozen before any Condition G or H administration.

No G or H output had been observed at the time of the corrected freeze.

---

## Correction Record

Matrix Version 1.0.0 incorrectly introduced three runs per condition per model and 24 total runs. Matrix Version 1.0.1 corrected filenames but retained that unsupported replication structure. Both were superseded before any G or H administration.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.0.0 | 2026-07-20 22:10:24 America/New_York | Superseded before administration | Incorrectly introduced a 24-run, three-replicate plan and a new identifier family |
| 1.0.1 | 2026-07-20 22:24:14 America/New_York | Superseded before administration | Corrected canonical filenames but retained the unsupported three-replicate plan |
| 1.0.2 | 2026-07-20 22:35:49 America/New_York | Prospectively frozen; unrun | Corrected to one G and one H run per model, eight runs total, following established E/F administration |