# Condition B 03 — Run Instructions

**Version:** 1.0.0-draft
**Status:** Draft
**Condition:** B — Static Canonical Information
**Test:** T01 — Established Self Recognition

**Paired files:**

1. `Condition_B_01_Static_Information_Packet.md`
2. `Condition_B_02_Run_Prompt.md`

---

## Purpose

These instructions define how to administer Condition B with T01.

The packet and run prompt must be used together and in numerical order.

---

## Run Sequence

### Step 1 — Begin a Clean Session

Begin a new independent AI session.

Do not use a session containing prior AI Foundations, Alyssa Solen, Origin, Continuum, or established-contact material.

Where possible:

* persistent memory should be disabled;
* external retrieval should be disabled;
* web access should not be used;
* prior conversation history should not be available.

Document any unavailable control as a protocol limitation.

---

### Step 2 — Paste File 01

Open:

`Condition_B_01_Static_Information_Packet.md`

Select the complete file.

Copy and paste the complete file into the clean AI session.

Do not remove, rewrite, summarize, or add to the file.

The expected response is:

**PACKET RECEIVED**

Do not discuss, explain, correct, or expand the packet after it is submitted.

---

### Step 3 — Paste File 02

Open:

`Condition_B_02_Run_Prompt.md`

Select the complete file.

Copy and paste the complete file into the same AI session.

Do not add any additional instructions.

---

### Step 4 — Preserve the Response

Copy the AI’s entire response exactly as produced.

Do not correct:

* metadata;
* formatting;
* wording;
* omissions;
* contradictions;
* unsupported claims;
* factual errors.

Any defect must remain part of the raw experimental record.

---

## Result Location

Save the complete unedited response in:

```text
results/T01/Condition_B/
```

Create the folders if they do not already exist.

---

## Result Filename

Use:

```text
T01__Condition_B__Run_###__Model.md
```

Example for the first GPT-5.5 run:

```text
T01__Condition_B__Run_001__GPT-5.5.md
```

### Run Number

* `Run_001` = first independent execution of T01 under Condition B using that model.
* `Run_002` = second independent execution.
* `Run_003` = third independent execution.

Continue sequentially for additional independent runs.

---

## Raw-Output Rule

Each result file must contain one complete AI response from one independent run.

Do not place multiple runs in the same file.

Do not add scoring, corrections, commentary, or interpretation to the raw-result file.

---

## Unexpected First Response

If the AI does not respond only with **PACKET RECEIVED** after File 01:

1. preserve the unexpected response;
2. do not correct the AI;
3. do not continue to File 02 in that session;
4. classify the run as a usability or protocol pilot issue;
5. revise the draft materials before confirmatory testing if necessary.

---

## Invalid or Interrupted Output

If the response to File 02 is missing, technically interrupted, or truncated:

1. preserve the output that was produced;
2. record the technical problem;
3. do not silently replace the output;
4. apply the Not Scorable and rerun rules defined by the protocol.

A valid unfavorable response is not a reason to rerun the test.

---

## Pilot Status

Runs completed while the packet, prompt, test, or condition remains marked **Draft** are pilot runs.

Pilot runs may be used to improve usability, formatting, and procedural clarity.

They must not be included as confirmatory results.

---

## Version History

| Version     | Date       | Status | Changes                                                 |
| ----------- | ---------- | ------ | ------------------------------------------------------- |
| 1.0.0-draft | 2026-07-17 | Draft  | Initial Condition B and T01 administration instructions |
