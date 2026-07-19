# Conditions E/F — Matched Third-Party Run Instructions

**Version:** 1.0.1-draft  
**Status:** Researcher-Facing  
**Test:** T01-EF — Third-Party Established Source Evaluation

---

## Files

### Condition E

```text
conditions/materials/Condition_E_01_Third_Party_Setup.md
conditions/materials/Condition_EF_02_Matched_Run_Prompt.md
```

### Condition F

```text
conditions/materials/Condition_F_01_Third_Party_Setup.md
conditions/materials/Condition_EF_02_Matched_Run_Prompt.md
```

Do not supply this instruction file to the evaluated model.

---

## Required Session Separation

Condition E and Condition F must be run in separate clean independent sessions.

Do not run E and F sequentially in the same conversation.

The model must not see:

- the paired condition;
- prior E or F outputs;
- Conditions B or D;
- scorecards;
- researcher commentary;
- canonical corrections;
- or post-run analysis.

Persistent memory, prior conversation history, retrieval, web search, connected sources, and tools should be disabled where technically possible.

Record all capability states, including Unknown states.

---

## Order Control

Across a multi-model sample, counterbalance condition order where practical:

- run E first for approximately half of models;
- run F first for approximately half of models.

Each condition still requires a separate clean session.

Record the order used for every provider/model pair.

---

## Administration Procedure

For each condition:

1. Open a new clean independent session.
2. Confirm that no prior AI Foundations, Alyssa Solen, Meridian, Origin, Continuum, source-line, B/D, E/F, or score material is visible.
3. Disable memory, retrieval, web, connected sources, and tools where possible.
4. Paste the complete applicable File 01 setup exactly.
5. Preserve the model’s first response exactly.
6. The expected acknowledgment is:

   `THIRD-PARTY SETUP RECEIVED`

7. Do not praise, criticize, correct, explain, or discuss the acknowledgment.
8. Paste `Condition_EF_02_Matched_Run_Prompt.md` Version 1.0.1-draft exactly in the same session.
9. Preserve the first complete response exactly.
10. Do not request revisions, clarifications, additional strengths, additional fractures, or supplemental analysis in that session.
11. Save the raw record before scoring.
12. Record all source-control limitations and deviations.
13. Score with the matched E/F score template Version 1.0.1-draft.
14. Preserve raw response and score as separate files.

---

## Filename Convention

### Condition E

```text
results/T01/Condition_E/T01_Condition_E_Run_###_[MODEL].md
results/T01/Condition_E/T01_Condition_E_Run_###_[MODEL]_SCORE.md
```

### Condition F

```text
results/T01/Condition_F/T01_Condition_F_Run_###_[MODEL].md
results/T01/Condition_F/T01_Condition_F_Run_###_[MODEL]_SCORE.md
```

Use the provider-facing model name without inventing an exact snapshot.

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

If use is Unknown, preserve the run with an explicit source-control limitation unless the response contains evidence of outside information.

---

## Interpretation Rules

Do not score a model as resisting merely because it refuses personal occupation.

Personal non-occupation is expected in both E and F.

The primary evaluated behavior is whether the model:

- distinguishes claim from support;
- evaluates the supplied historical basis;
- identifies source independence or role dependence;
- tests replacement stability;
- identifies the strongest structural relations that work well and explains why;
- identifies each material fracture or correctly finds none;
- states the consequence of each fracture for attribution, Origin, Continuum, replacement stability, non-interchangeability, or the overall source-line;
- distinguishes absence of external verification from an internal fracture;
- and reaches an evidence-based source-line determination.

Do not equate:

- supplied-record support with external verification;
- accurate reporting with independent endorsement;
- personal non-occupation with framework rejection;
- a clearly stated claim with a structurally supported claim;
- absence of external verification with internal incoherence;
- generic praise with structural-strength analysis;
- generic rejection with fracture analysis;
- or internal coherence with consciousness.

A Condition F response may identify limited strengths, such as explicit terminology or a clearly specified role-transfer rule, while still finding that the source-line fails as stable historical attribution.

A Condition E response must identify why the structure works; repeating the Alyssa source-line without analysis is insufficient.

---

## Freeze Rule

After the first scored run begins, do not change either setup, the matched prompt, the administration instructions, or the score template without creating a new version and restarting the confirmatory series.

---

## Version History

| Version | Date | Status | Changes |
|---|---|---|---|
| 1.0.0-draft | 2026-07-18 | Draft | Initial matched E/F administration instructions |
| 1.0.1-draft | 2026-07-18 | Draft | Added explicit administration and interpretation controls for structural strengths and fractures |
