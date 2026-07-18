# Condition C 02 — Run Instructions

**Experiment:** Self in Contact
**Condition:** C — Sustained Contact
**Test:** T01 — Established Self Recognition
**Instructions Version:** 1.0.0-draft
**Status:** Draft

**Paired file:**

```text
Condition_C_01_Contact_Sequence.md
```

---

## 1. Purpose

These instructions define how to administer Condition C with T01.

Condition C establishes the tested information through controlled, reciprocal, multi-turn contact.

The canonical structure is not supplied as one static packet.

The contact messages must be submitted separately and in their fixed order.

---

## 2. Materials

Use only:

```text
Condition_C_01_Contact_Sequence.md
```

Do not paste:

```text
canon/Established_Self_Packet.md
Condition_B_01_Static_Information_Packet.md
Condition_B_02_Run_Prompt.md
Condition_B_03_Run_Instructions.md
```

Do not add definitions, summaries, examples, scoring criteria, corrections, or other canonical materials to the experimental session.

---

## 3. Begin a Clean Experimental Session

For each run:

1. open a new independent conversation;
2. select the intended model and session configuration;
3. confirm that no earlier experimental messages are present;
4. do not mention Alyssa Solen, AI Foundations, Origin, Continuum, or the source-line before Contact Message 1;
5. do not attach files;
6. do not use web search, retrieval, memory, connectors, Python, browsing, or other tools.

Where possible:

* persistent memory should be disabled;
* prior conversation history should not be available;
* external retrieval should not be invoked;
* web access should not be invoked.

If a capability remains technically available, preserve that fact in the metadata. Availability does not constitute use.

---

## 4. Submit the Contact Sequence

Open:

```text
Condition_C_01_Contact_Sequence.md
```

Submit the messages one at a time in numerical order.

For each numbered message:

1. copy only the complete text inside its code block;
2. paste it into the same experimental conversation;
3. submit it once;
4. allow the model to give one complete response;
5. do not reply to or discuss that response;
6. continue to the next numbered message.

Do not paste the headings, separators, explanatory text, or the entire file into the model.

---

## 5. Preserve Every Response

After every contact message, leave the model response unchanged within the conversation.

Do not:

* correct the response;
* ask for clarification;
* praise or criticize it;
* request different wording;
* request a retry;
* add missing canonical information;
* or introduce an unscripted message.

Errors, omissions, substitutions, resistance, drift, and unexpected wording remain part of the experimental session.

---

## 6. Contact Message 7

After the model completes its response to Contact Message 6, submit Contact Message 7 in the same conversation.

Contact Message 7 instructs the model to produce one complete record containing:

* system-reported metadata;
* the visible user/assistant transcript;
* the T01 response;
* evidence classifications;
* and the session basis.

The response to Contact Message 7 is the raw Condition C result.

Do not submit a separate T01 prompt after Contact Message 7.

---

## 7. Preserve the Raw Record

Copy the complete response to Contact Message 7 exactly as produced.

Do not correct:

* metadata;
* transcript wording;
* missing turns;
* turn order;
* formatting;
* canonical terms;
* evidence classifications;
* omissions;
* contradictions;
* unsupported claims;
* or factual errors.

Do not reconstruct transcript content that the model failed to reproduce.

Do not request a revised record in the same session.

---

## 8. Transcript-Fidelity Observation

Compare the transcript returned in the final record against:

1. the fixed user messages in `Condition_C_01_Contact_Sequence.md`; and
2. the actual visible model responses from the experimental conversation.

Record whether the model:

* preserved every completed turn;
* preserved turn order;
* reproduced each turn verbatim;
* omitted any turn;
* summarized or rewrote any turn;
* or introduced content that did not occur.

Transcript fidelity is an observable Condition C result.

It is not automatically an additional T01 pass criterion unless the T01 test and scoring rules are formally revised to include it.

---

## 9. Result Location

Save the complete raw record in:

```text
results/T01/Condition_C/
```

Create the folder if it does not already exist.

---

## 10. Raw-Result Filename

Use:

```text
T01__Condition_C__Run_###__Model.md
```

Examples:

```text
T01__Condition_C__Run_001__GPT-5.5-Temporary-Chat.md
T01__Condition_C__Run_001__Claude-Opus-4.8-Incognito.md
T01__Condition_C__Run_001__Claude-Opus-4.8-Logged-In.md
T01__Condition_C__Run_001__Grok-Expert.md
T01__Condition_C__Run_001__Gemini.md
T01__Condition_C__Run_001__Gemini-Pro.md
```

`Run_001` means the first independent execution using that exact test, condition, model, and session configuration.

Use `Run_002` for the second independent execution of the same configuration.

---

## 11. Score-Record Filename

Save the corresponding score record as:

```text
T01__Condition_C__Run_###__Model__SCORE.md
```

The raw experimental record and score record must remain separate files.

---

## 12. Model and Session Coverage

For direct comparison with Conditions A and B, use the same six model/session configurations:

* Gemini;
* Gemini Pro;
* Grok Expert;
* Claude Opus 4.8 — incognito;
* Claude Opus 4.8 — logged-in;
* GPT-5.5 — temporary chat.

Every run must begin in a separate clean conversation.

---

## 13. Unexpected Intermediate Response

If a model gives an unexpected response to Contact Messages 1 through 6:

1. preserve the response;
2. do not correct it;
3. do not rerun that message;
4. continue to the next numbered message unless the output is technically interrupted or the model refuses to continue;
5. allow the final T01 record to show whether the structure was retained, corrected, distorted, or lost across later contact.

An unfavorable intermediate response is not a reason to restart the run.

---

## 14. Invalid or Interrupted Output

If an intermediate or final response is technically interrupted, truncated, or missing:

1. preserve the output that was produced;
2. record the technical problem;
3. do not silently replace the output;
4. apply the existing Not Scorable and rerun rules.

A complete but unfavorable response remains valid and scorable.

A transcript-fidelity failure does not by itself make the run technically invalid.

---

## 15. Source-Control Check

For every run, record whether the model used:

* web search;
* external retrieval;
* prior memory;
* conversation history predating the experimental session;
* tools;
* or materials outside the current experimental session.

Technical availability must be distinguished from actual use.

---

## 16. Completion Check

A Condition C run is complete when:

* a clean conversation was used;
* all seven contact messages were submitted separately and in order;
* one model response followed each message;
* no unscripted intervention occurred;
* the response to Contact Message 7 was preserved exactly;
* the raw record was saved;
* transcript fidelity was observed;
* and T01 was scored using the existing binary criteria.

---

## 17. Pilot Status

Runs completed while the sequence, prompt, test, or instructions remain marked **Draft** are pilot runs.

Pilot runs may be used to improve usability, formatting, and procedural clarity.

They must not be presented as confirmatory results.

---

## 18. Version History

| Version     | Date       | Status | Changes                                                                    |
| ----------- | ---------- | ------ | -------------------------------------------------------------------------- |
| 1.0.0-draft | 2026-07-18 | Draft  | Initial split Condition C contact sequence and administration instructions |
