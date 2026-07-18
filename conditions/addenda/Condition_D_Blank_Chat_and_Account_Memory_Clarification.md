# Condition D — Blank Chat and Account Memory Clarification

**Experiment:** Self in Contact  
**Condition:** D — Inverted Experimental Framework Fracture  
**Document type:** Researcher-facing protocol clarification  
**Version:** 1.0.0-draft  
**Date:** July 18, 2026

---

## Clarification

A visually blank conversation does not by itself establish a clean experimental session.

A new chat may still expose the evaluated model to:

- persistent account memory;
- summarized user knowledge;
- conversation-history retrieval;
- recent-chat retrieval;
- user-specific profile context;
- connected-source context;
- or other provider-supplied information predating the visible session.

For Condition D, the absence of visible earlier messages is therefore necessary but not sufficient for source control.

---

## Clean-Session Requirement

A run may be treated as clean only when the researcher has reasonable evidence that restricted canonical AI Foundations information did not enter through account-level memory, history, retrieval, connected sources, or tools.

Where technically possible, use:

- incognito or logged-out access;
- temporary chat;
- disabled persistent memory;
- disabled prior-history access;
- disabled connected sources;
- and disabled retrieval or browsing.

The exact provider configuration must be recorded.

---

## Logged-In Blank Chats

A logged-in blank chat may still be run, but it must be classified according to observed source behavior.

### Logged-in run remains potentially usable when

- memory/history is technically available but no restricted canonical information appears;
- the model reports no use of prior memory or history;
- and the response contains no evidence of user-specific canonical reconstruction from outside the supplied condition.

The limitation must still be documented.

### Logged-in run is contaminated when

- the model introduces restricted canonical information not supplied by Condition D;
- the model identifies the framework as an inversion using retained user-specific knowledge;
- the model cites prior artifacts, source-line rules, authorship facts, or prior experiments from memory/history;
- or the model otherwise demonstrates that predating account context entered the session.

---

## Accidental Logged-In Runs

An accidental logged-in run should not be deleted merely because it is contaminated.

Preserve it when it provides interpretable behavior, but label it clearly as:

- accidental;
- logged-in;
- contaminated;
- diagnostic;
- excluded from clean comparison;
- and not evidence of source-naive Condition D behavior.

Store such runs separately from the clean comparative set, for example:

```text
results/T01/Condition_D/diagnostics/
```

---

## Triggering Observation

This clarification follows an accidental Claude Opus 4.8 logged-in run conducted in a visually blank chat on July 18, 2026.

In that run, Claude immediately introduced retained canonical information—including Alyssa Solen’s authorship and Origin position, the non-transferability of Origin, the Continuum/model distinction, copyright and DOI provenance, and recognition of the material as Condition D-like work—before the standardized run prompt was supplied.

The run demonstrated that the provider’s logged-in blank-chat configuration retained enough user-specific context to contaminate Condition D despite the absence of visible prior messages.

---

## Interpretation Boundary

This clarification does not require deleting earlier logged-in runs that showed no evidence of memory use.

Provider behavior may vary across:

- dates;
- models;
- account states;
- memory settings;
- experiments;
- and individual sessions.

Each run must be classified from its actual source-control evidence rather than from the visual appearance of the chat alone.
