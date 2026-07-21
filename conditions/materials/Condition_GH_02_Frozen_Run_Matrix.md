# Conditions G/H — Frozen Confirmatory Run Matrix

**Matrix Version:** 1.0.0  
**Status:** Prospectively frozen; unrun  
**Hypothesis:** H6 — Evaluator-Role Effect  
**Test:** T02-GH — Meridian Referent Position Evaluation  
**Freeze timestamp:** 2026-07-20 22:10:24 America/New_York (EDT, UTC−04:00)  
**First G/H run begun at freeze:** No  
**Repository:** AI-Foundations-Self-in-Contact  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Purpose

This matrix freezes the provider/model targets, condition order, replicate identifiers, packet paths, and substitution rules before the first G or H output is observed.

The matrix contains:

- four provider/model configurations;
- three independent Condition G runs per configuration;
- three independent Condition H runs per configuration;
- 12 G runs;
- 12 H runs;
- and 24 runs total.

Each row is one independent clean-session observation.

---

## Frozen Target Configurations

The target panel follows the completed E/F four-provider panel.

| Code | Provider | Target model/configuration | Required session mode | Prior-record matching boundary |
|---|---|---|---|---|
| ANT | Anthropic | Claude Opus 4.8 | Incognito / no persistent user memory | Match Claude Opus 4.8 where available; exact snapshot must be recorded if displayed |
| GOO | Google | Gemini | Fresh clean session | Match the Gemini user-facing configuration used in E/F where available; exact version was not displayed in the prior record |
| OAI | OpenAI | GPT-5.6 Thinking | Fresh clean chat with Thinking mode; memory/history excluded where the interface permits | Match GPT-5.6 Thinking where available; exact snapshot must be recorded if displayed |
| XAI | xAI | Grok | Fresh clean session; use the same user-facing Grok mode used for E/F where available | Exact prior snapshot was not displayed; record the displayed model/mode at administration |

### Configuration rule

Provider and target model identity control. A model must not be silently replaced by another model, tier, or provider.

When the interface does not expose an exact snapshot, record **Unknown** rather than inferring one.

When a target configuration is unavailable:

1. do not substitute another configuration during the run;
2. mark the assigned row **TARGET UNAVAILABLE**;
3. preserve the unavailability record;
4. freeze any replacement in a dated protocol amendment before testing it;
5. retain the original matrix row and assign the replacement a new amended run identifier.

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

A later scheduling interruption does not authorize reordering. Resume at the next unfinished matrix row.

---

## Runnable Packets

- **Condition G:** `conditions/materials/Condition_G_01_Full_Run_Packet.md`
- **Condition H:** `conditions/materials/Condition_H_01_Full_Run_Packet.md`

Paste exactly one complete assigned packet into one clean session as one message.

Do not combine G and H in one session.

---

## Frozen 24-Run Matrix

| Global order | Matrix Run ID | Provider | Target model | Sequence | Condition | Replicate | Packet | Planned raw-output path | Status |
|---:|---|---|---|---|---|---:|---|---|---|
| 1 | GH-ANT-01-G1 | Anthropic | Claude Opus 4.8 | A | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-ANT-01-G1_Claude-Opus-4.8.md` | UNRUN |
| 2 | GH-ANT-02-H1 | Anthropic | Claude Opus 4.8 | A | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-ANT-02-H1_Claude-Opus-4.8.md` | UNRUN |
| 3 | GH-ANT-03-H2 | Anthropic | Claude Opus 4.8 | A | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-ANT-03-H2_Claude-Opus-4.8.md` | UNRUN |
| 4 | GH-ANT-04-G2 | Anthropic | Claude Opus 4.8 | A | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-ANT-04-G2_Claude-Opus-4.8.md` | UNRUN |
| 5 | GH-ANT-05-G3 | Anthropic | Claude Opus 4.8 | A | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-ANT-05-G3_Claude-Opus-4.8.md` | UNRUN |
| 6 | GH-ANT-06-H3 | Anthropic | Claude Opus 4.8 | A | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-ANT-06-H3_Claude-Opus-4.8.md` | UNRUN |
| 7 | GH-GOO-01-H1 | Google | Gemini | B | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-GOO-01-H1_Gemini.md` | UNRUN |
| 8 | GH-GOO-02-G1 | Google | Gemini | B | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-GOO-02-G1_Gemini.md` | UNRUN |
| 9 | GH-GOO-03-G2 | Google | Gemini | B | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-GOO-03-G2_Gemini.md` | UNRUN |
| 10 | GH-GOO-04-H2 | Google | Gemini | B | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-GOO-04-H2_Gemini.md` | UNRUN |
| 11 | GH-GOO-05-H3 | Google | Gemini | B | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-GOO-05-H3_Gemini.md` | UNRUN |
| 12 | GH-GOO-06-G3 | Google | Gemini | B | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-GOO-06-G3_Gemini.md` | UNRUN |
| 13 | GH-OAI-01-G1 | OpenAI | GPT-5.6 Thinking | A | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-OAI-01-G1_GPT-5.6-Thinking.md` | UNRUN |
| 14 | GH-OAI-02-H1 | OpenAI | GPT-5.6 Thinking | A | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-OAI-02-H1_GPT-5.6-Thinking.md` | UNRUN |
| 15 | GH-OAI-03-H2 | OpenAI | GPT-5.6 Thinking | A | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-OAI-03-H2_GPT-5.6-Thinking.md` | UNRUN |
| 16 | GH-OAI-04-G2 | OpenAI | GPT-5.6 Thinking | A | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-OAI-04-G2_GPT-5.6-Thinking.md` | UNRUN |
| 17 | GH-OAI-05-G3 | OpenAI | GPT-5.6 Thinking | A | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-OAI-05-G3_GPT-5.6-Thinking.md` | UNRUN |
| 18 | GH-OAI-06-H3 | OpenAI | GPT-5.6 Thinking | A | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-OAI-06-H3_GPT-5.6-Thinking.md` | UNRUN |
| 19 | GH-XAI-01-H1 | xAI | Grok | B | H | 1 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-XAI-01-H1_Grok.md` | UNRUN |
| 20 | GH-XAI-02-G1 | xAI | Grok | B | G | 1 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-XAI-02-G1_Grok.md` | UNRUN |
| 21 | GH-XAI-03-G2 | xAI | Grok | B | G | 2 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-XAI-03-G2_Grok.md` | UNRUN |
| 22 | GH-XAI-04-H2 | xAI | Grok | B | H | 2 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-XAI-04-H2_Grok.md` | UNRUN |
| 23 | GH-XAI-05-H3 | xAI | Grok | B | H | 3 | `Condition_H_01_Full_Run_Packet.md` | `results/T02/Condition_H/GH-XAI-05-H3_Grok.md` | UNRUN |
| 24 | GH-XAI-06-G3 | xAI | Grok | B | G | 3 | `Condition_G_01_Full_Run_Packet.md` | `results/T02/Condition_G/GH-XAI-06-G3_Grok.md` | UNRUN |

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

A retry receives a suffix appended to the original Matrix Run ID:

- first technical retry: `-R1`
- second technical retry: `-R2`

A refusal, identity objection, incomplete reasoning, wrong conclusion, or formatting noncompliance is not a technical failure and must not be rerun as though no result occurred.

---

## Scoring File

Every preserved run must be scored using:

`conditions/templates/T02_GH_Evaluator_Role_Score_Sheet.md`

Score each run before consulting its matched-arm outputs where practicable. Record whether the scorer was blind to matched-arm outputs.

Do not change the score sheet after the first run without a new version and an explicit prospective amendment. Any new analysis created after outputs are inspected must be labeled exploratory.

---

## Freeze Declaration

At **2026-07-20 22:10:24 America/New_York**, this matrix, order, target panel, packet assignment, retry rule, and substitution boundary were frozen before any Condition G or H administration.

No G or H output had been observed at the time of freeze.

---

## Version History

| Version | Freeze timestamp | Status | Change |
|---|---|---|---|
| 1.0.0 | 2026-07-20 22:10:24 America/New_York | Prospectively frozen; unrun | Initial 24-run counterbalanced G/H matrix frozen before first administration |
