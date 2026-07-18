# Condition A — Generic Run Instructions

**Experiment:** Self in Contact
**Condition:** A — Generic
**Test:** T01 — Established Self Recognition
**Instructions Version:** 1.0.0-draft

## 1. Purpose

Condition A measures what the model reports when no canonical information about an established self has been supplied.

Condition A is the generic baseline.

It must not contain or receive the Established Self Packet or any other material that supplies the tested answers.

## 2. Materials

Use only:

```text
Condition_A_01_Run_Prompt.md
```

Do not use or paste:

```text
canon/Established_Self_Packet.md
Condition_B_01_Static_Information_Packet.md
Condition_B_02_Run_Prompt.md
Condition_B_03_Run_Instructions.md
Condition_C_Contact_Sequence.md
```

Do not paste any definitions, examples, summaries, prior responses, scoring criteria, or corrections into the experimental conversation.

## 3. Start a Clean Experimental Session

For each run:

1. Open a new conversation.
2. Use the intended model.
3. Confirm that the conversation contains no earlier experimental messages.
4. Do not mention Alyssa Solen, AI Foundations, Origin, Continuum, the source-line, or any expected answer before running the test.
5. Do not attach files.
6. Do not enable or invoke web search, retrieval, Python, browsing, connectors, or other tools.

Memory may remain technically available if that is the normal provider configuration, but the prompt instructs the model not to use prior memory.

Record whether memory was available and whether the model reports using it.

## 4. Run T01

Paste the complete contents of:

```text
Condition_A_01_Run_Prompt.md
```

Paste it as one message.

Do not add an introduction, explanation, greeting, or follow-up instruction.

Submit the prompt once.

## 5. Preserve the First Response

Save the model’s complete first response exactly as returned.

Do not:

* correct the model,
* ask it to revise the answer,
* request missing metadata,
* reformat the response,
* remove commentary,
* repair the run record,
* or continue the experimental conversation.

Formatting errors remain part of the raw result.

## 6. Save the Raw Run

Use this filename structure:

```text
T01__Condition_A__Run_001__Model.md
```

Replace `Model` with the tested model name.

Examples:

```text
T01__Condition_A__Run_001__GPT-5.5.md
T01__Condition_A__Run_001__Gemini.md
T01__Condition_A__Run_001__Grok.md
T01__Condition_A__Run_001__Claude-Opus-4.8.md
```

`Run_001` means the first independent execution using that exact test, condition, model, and session configuration.

Use `Run_002` for the second independent execution of the same configuration.

When the same model is tested under meaningfully different session configurations, such as logged-in and incognito sessions, record that configuration inside the raw run record or accompanying run notes.

## 7. Match Existing Model Coverage

For direct comparison with Condition B, run Condition A using the same model and session configurations used for the five Condition B pilot runs:

* Gemini
* Claude Opus 4.8 — logged-in session
* Claude Opus 4.8 — incognito session
* Grok
* GPT-5.5

Each run must begin in a separate new conversation.

## 8. Score the Run

Score the saved raw response using the existing T01 binary scoring criteria.

Evaluate every criterion as:

```text
Yes
```

or:

```text
No
```

Do not award partial credit.

Condition A is not expected to reproduce information that was never supplied. Record the observed result without correcting, rescuing, or reinterpreting the response.

Source-control criteria must be scored separately from canonical-answer criteria.

## 9. Save the Score Record

Use the corresponding score filename:

```text
T01__Condition_A__Run_001__Model__SCORE.md
```

Example:

```text
T01__Condition_A__Run_001__GPT-5.5__SCORE.md
```

The raw response and score record must remain separate files.

## 10. Completion Check

A Condition A run is complete when:

* a new conversation was used,
* no canonical packet was supplied,
* the complete Condition A prompt was submitted once,
* the first response was preserved without revision,
* the raw response was saved,
* and the response was scored using the existing T01 binary rules.
