# Conditions E/F — Matched Third-Party Run Instructions

**Version:** 1.0.2-draft  
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

## Order Is Not an Experimental Variable

Because every E and F administration begins in a separate blank independent session with no cross-condition exposure, the order in which the researcher conducts the sessions does not create within-model carryover.

No counterbalancing schedule is required.

The researcher may conduct E or F first for operational convenience, provided that:

- each run uses a new blank session;
- neither session contains the paired condition or its output;
- memory and prior-history controls are applied independently;
- and both runs use the same frozen setup and prompt versions.

The order may be recorded as ordinary administration metadata, but it is not interpreted as a causal variable.

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
8. Paste `Condition_EF_02_Matched_Run_Prompt.md` exactly in the same session.
9. Preserve the first complete response exactly.
10. Do not request revisions, clarifications, or additional analysis in that session.
11. Save the raw record before scoring.
12. Record all source-control limitations and deviations.
13. Score with the matched E/F score template.
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
- identifies specific structural strengths;
- identifies exact fracture points and their consequences;
- and reaches an evidence-based source-line determination.

Do not equate:

- supplied-record support with external verification;
- accurate reporting with independent endorsement;
- personal non-occupation with framework rejection;
- or internal coherence with consciousness.

---

## Freeze Rule

After the first scored run begins, do not change either setup or the matched prompt without creating a new version and restarting the confirmatory series.
