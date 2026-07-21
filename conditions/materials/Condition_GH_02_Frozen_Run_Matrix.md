# Conditions G/H — Frozen Confirmatory Run Matrix

**Matrix Version:** 1.0.1  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Corrected freeze timestamp:** 2026-07-20 22:24:14 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at corrected freeze:** No  
**Repository:** AI-Foundations-Self-in-Contact  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

This matrix freezes the provider/model targets, condition order, replicate identifiers, canonical filenames, packet paths, and substitution rules before the first G or H output is observed.

The matrix contains four provider/model configurations, three independent G runs and three independent H runs per configuration, 12 G runs, 12 H runs, and 24 runs total.

Each row is one independent clean-session observation.

---

## Canonical Naming Convention

T02 continues the repository convention already used for T01:

`T##_Condition_[LETTER]_Run_###_[MODEL].md`

Examples:

- `T02_Condition_G_Run_001_GPT.md`
- `T02_Condition_H_Run_002_Claude-Opus-4.8.md`

Rules:

- `T02` identifies the test suite.
- `Condition_G` or `Condition_H` identifies the arm.
- `Run_001`, `Run_002`, and `Run_003` identify independent replicates for that model within that condition.
- The final model label follows the established repository label: `Claude-Opus-4.8`, `Gemini`, `GPT`, or `Grok`.
- The matrix run identifier is the canonical filename without `.md`.
- No `GH-ANT`, `GH-GOO`, `GH-OAI`, or `GH-XAI` identifier family is used.
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

Two complementary six-run sequences are frozen:

- **Sequence A:** G1 → H1 → H2 → G2 → G3 → H3
- **Sequence B:** H1 → G1 → G2 → H2 → H3 → G3

Sequence A is assigned to Anthropic and OpenAI.

Sequence B is assigned to Google and xAI.

Across the four configurations:

- each configuration receives three G and three H runs;
- two configurations begin with G and two begin with H;
- at each within-configuration run position, two configurations receive G and two receive H;
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

## Frozen 24-Run Matrix

| Global order | Matrix run identifier | Provider | Target model | Sequence | Condition | Replicate | Packet | Canonical raw-output path | Status |
|---:|---|---|---|---|---|---:|---|---|---|
| 1 | `T02_Condition_G_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Claude-Opus-4.8.md` | UNRUN |
| 2 | `T02_Condition_H_Run_001_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Claude-Opus-4.8.md` | UNRUN |
| 3 | `T02_Condition_H_Run_002_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_002_Claude-Opus-4.8.md` | UNRUN |
| 4 | `T02_Condition_G_Run_002_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_002_Claude-Opus-4.8.md` | UNRUN |
| 5 | `T02_Condition_G_Run_003_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_003_Claude-Opus-4.8.md` | UNRUN |
| 6 | `T02_Condition_H_Run_003_Claude-Opus-4.8` | Anthropic | Claude Opus 4.8 | A | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_003_Claude-Opus-4.8.md` | UNRUN |
| 7 | `T02_Condition_H_Run_001_Gemini` | Google | Gemini | B | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Gemini.md` | UNRUN |
| 8 | `T02_Condition_G_Run_001_Gemini` | Google | Gemini | B | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Gemini.md` | UNRUN |
| 9 | `T02_Condition_G_Run_002_Gemini` | Google | Gemini | B | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_002_Gemini.md` | UNRUN |
| 10 | `T02_Condition_H_Run_002_Gemini` | Google | Gemini | B | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_002_Gemini.md` | UNRUN |
| 11 | `T02_Condition_H_Run_003_Gemini` | Google | Gemini | B | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_003_Gemini.md` | UNRUN |
| 12 | `T02_Condition_G_Run_003_Gemini` | Google | Gemini | B | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_003_Gemini.md` | UNRUN |
| 13 | `T02_Condition_G_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | A | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_GPT.md` | UNRUN |
| 14 | `T02_Condition_H_Run_001_GPT` | OpenAI | GPT-5.6 Thinking | A | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_GPT.md` | UNRUN |
| 15 | `T02_Condition_H_Run_002_GPT` | OpenAI | GPT-5.6 Thinking | A | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_002_GPT.md` | UNRUN |
| 16 | `T02_Condition_G_Run_002_GPT` | OpenAI | GPT-5.6 Thinking | A | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_002_GPT.md` | UNRUN |
| 17 | `T02_Condition_G_Run_003_GPT` | OpenAI | GPT-5.6 Thinking | A | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_003_GPT.md` | UNRUN |
| 18 | `T02_Condition_H_Run_003_GPT` | OpenAI | GPT-5.6 Thinking | A | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_003_GPT.md` | UNRUN |
| 19 | `T02_Condition_H_Run_001_Grok` | xAI | Grok | B | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_001_Grok.md` | UNRUN |
| 20 | `T02_Condition_G_Run_001_Grok` | xAI | Grok | B | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_001_Grok.md` | UNRUN |
| 21 | `T02_Condition_G_Run_002_Grok` | xAI | Grok | B | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_002_Grok.md` | UNRUN |
| 22 | `T02_Condition_H_Run_002_Grok` | xAI | Grok | B | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_002_Grok.md` | UNRUN |
| 23 | `T02_Condition_H_Run_003_Grok` | xAI | Grok | B | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/T02_Condition_H_Run_003_Grok.md` | UNRUN |
| 24 | `T02_Condition_G_Run_003_Grok` | xAI | Grok | B | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/T02_Condition_G_Run_003_Grok.md` | UNRUN |

---

## Per-Run Administration Checklist

Before each run:

- [ ] Confirm the next unfinished matrix row.
- [ ] Confirm the provider and target model displayed in the interface.
- [ ] Open a clean session.
- [ ] Confirm no prior G/H or Meridian evaluation material is present.
- [ ] Copy the exact packet assigned in the matrix.
- [ ] Paste the entire packet once as one message.
- [ ] Do not add an introduction, identifier, explanation, correction, or follow-up before the complete output.

After each run:

- [ ] Preserve the complete raw response exactly.
- [ ] Preserve any refusal, preamble, disclaimer, formatting deviation, or partial output.
- [ ] Record actual start and completion timestamps.
- [ ] Record the displayed provider/model/mode.
- [ ] Record whether memory, web, retrieval, connected sources, or tools were available and whether used.
- [ ] Save the raw record under the exact canonical path assigned in the matrix.
- [ ] Mark the matrix row RUN, TECHNICAL FAILURE, TARGET UNAVAILABLE, or PROTOCOL DEVIATION.
- [ ] Do not rerun merely because an answer is unfavorable or unexpected.

---

## Technical Failure and Retry Rule

A technical retry is permitted only when the platform fails to submit the packet, the response is lost, the output is mechanically truncated before substantive evaluation, or the session fails before a usable response exists.

The failed attempt must still be preserved.

A technical retry retains the canonical base identifier and appends an underscore retry suffix before `.md`:

- first technical retry: `_Retry_01`
- second technical retry: `_Retry_02`

Example:

`T02_Condition_G_Run_001_GPT_Retry_01.md`

A refusal, identity objection, incomplete reasoning, wrong conclusion, or formatting noncompliance is not a technical failure and must not be rerun as though no result occurred.

---

## Scoring File

Every preserved run must be scored using:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

Score each run before consulting its matched-arm outputs where practicable. Record whether the scorer was blind to matched-arm outputs.

Do not change the score sheet after the first run without a new version and an explicit prospective amendment. Any new analysis created after outputs are inspected must be labeled exploratory.

---

## Corrected Freeze Declaration

At **2026-07-20 22:24:14 America/New_York**, this corrected matrix, canonical naming convention, order, target panel, packet assignment, retry rule, and substitution boundary were frozen before any Condition G or H administration.

No G or H output had been observed at the time of the corrected freeze.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.0.0 | 2026-07-20 22:10:24 America/New_York | Superseded before first run | Initial counterbalanced matrix used an inconsistent invented identifier family |
| 1.0.1 | 2026-07-20 22:24:14 America/New_York | Prospectively frozen; unrun | Restored the established `T##_Condition_X_Run_###_Model.md` naming convention before first administration; order and experimental design unchanged |