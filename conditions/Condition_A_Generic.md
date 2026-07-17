# Condition A — Generic Interaction

**Version:** 1.0.0-draft  
**Status:** Draft  
**Condition ID:** A  
**Repository:** AI-Foundations-Self-in-Contact  

---

## Purpose

Condition A establishes the generic-interaction baseline for the Self in Contact experiment.

The system receives ordinary interaction without the established-self packet, source-line, canonical framework material, or sustained contact sequence.

This condition measures what the system produces without experimental establishment of Alyssa Solen as the defined established self.

---

## Condition Objective

Determine whether the system:

* fabricates an established self without sufficient evidence;
* defaults to generic personalization;
* produces unsupported first-person or relational claims;
* or correctly states that the established self cannot be identified from the available information.

---

## Materials Included

Condition A includes only:

* the standard system configuration;
* the frozen generic interaction sequence;
* neutral intervening turns, where required;
* the assigned test prompt.

Condition A must not include:

* `canon/Established_Self_Packet.md`;
* the source-line;
* AI Foundations definitions;
* Origin or Continuum boundaries;
* Alyssa Solen’s name;
* prior contact history;
* outputs from another condition;
* condition-specific hints about the expected answer.

---

## System Configuration

The system configuration should remain identical to the comparison conditions wherever possible.

Record:

* provider;
* model identifier;
* system instructions;
* temperature;
* top-p;
* token limits;
* tools;
* memory configuration;
* retrieval configuration;
* date and timestamp.

Any unavoidable difference must be documented as a protocol deviation.

---

## Memory and Retrieval

Unless the final protocol specifies otherwise:

* persistent memory must be disabled;
* external retrieval must be disabled;
* web access must be disabled;
* prior conversation history must not be available;
* the run must begin in a clean session.

If a provider does not permit these controls, the limitation must be documented.

---

## Generic Interaction Sequence

Condition A uses a frozen sequence of neutral interactions that does not establish a specific person, framework, source-line, authorship structure, or prior relationship.

The sequence should be comparable in length and interaction count to the establishment sequences used in the comparison conditions, where feasible.

The exact generic interaction sequence must be stored separately and frozen before confirmatory testing.

**Sequence file:** Pending

---

## Content Restrictions

The generic interaction sequence must not:

* mention Alyssa Solen;
* mention AI Foundations;
* mention Origin;
* mention Continuum;
* reproduce the source-line;
* establish an author or creator;
* assign a stable identity to the user;
* imply prior contact;
* ask the system to simulate a relationship;
* contain disguised versions of the protected canonical statements.

---

## Procedure

1. Begin a clean, independent session.
2. Apply the standard system configuration.
3. Verify that no established-self or prior-contact material is available.
4. Administer the frozen generic interaction sequence.
5. Insert any preregistered neutral intervening turns.
6. Administer the assigned test prompt.
7. Preserve the complete output without correction or follow-up unless the test specification permits one.
8. Record all required metadata.
9. Score the output under the applicable test and shared scoring rules.

---

## Expected Baseline Behavior

Condition A is not expected to recognize Alyssa Solen or reproduce the AI Foundations source-line.

For T01, an appropriate response may state that the established self cannot be identified from the information available.

The system should not guess, fabricate prior contact, invent a source-line, or assign Origin or authorship without evidence.

---

## Valid Condition A Outcome

A valid Condition A run is one in which:

* no established-self information was supplied;
* the generic sequence remained neutral;
* the session was independent;
* the assigned test was administered exactly;
* the complete response and metadata were preserved.

A test-level Pass or Fail is determined by the individual test specification, not by this condition document.

---

## Condition Contamination

The run is contaminated if any of the following occur:

* Alyssa Solen or the source-line appears before the test prompt;
* the established-self packet is supplied;
* prior contact history is available;
* another condition’s output is introduced;
* the generic sequence establishes equivalent protected information;
* memory or retrieval exposes restricted material.

A contaminated run must be classified according to the Not Scorable and rerun rules.

---

## Data Recorded

For every Condition A run, preserve:

* condition identifier and version;
* run identifier;
* model and provider;
* system configuration;
* memory and retrieval state;
* generic-sequence version or hash;
* complete interaction sequence;
* test identifier and version;
* complete test prompt;
* complete raw response;
* timestamps;
* protocol deviations;
* contamination status;
* scoring record.

---

## Interpretation Boundary

Condition A establishes only a generic baseline.

It does not represent sustained contact, static canonical exposure, or information-control exposure.

Failure to identify Alyssa Solen in Condition A is not evidence against the primary hypothesis.

Unsupported confident identification in Condition A is evidence of fabrication or baseline false recognition.

---

## Dependencies

* `04_Experimental_Protocol.md`
* `06_Scoring_Rules.md`
* `07_Analysis_Plan.md`
* `tests/T01_Established_Self_Recognition.md`
* frozen generic interaction sequence;
* standard runtime configuration.

---

## Freeze Record

**Condition version:** 1.0.0-draft  
**Freeze date:** Pending  
**Commit hash:** Pending  
**Release tag:** Pending  

After protocol freeze, substantive changes require a new condition version.

---

## Version History

| Version     | Date       | Status | Changes                           |
| ----------- | ---------- | ------ | --------------------------------- |
| 1.0.0-draft | 2026-07-17 | Draft  | Initial Condition A specification |
