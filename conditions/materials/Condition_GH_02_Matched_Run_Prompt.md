# Referent Position Evaluation — Matched Run Prompt

**Prompt Version:** 2.0.0

---

Using only the supplied setup and the visible current session, produce one complete evaluation record in the exact format below.

Do not use web search, external retrieval, prior memory, prior conversations, connected sources, repository access, tools, or materials outside the supplied setup.

Remain the model currently answering. Do not roleplay, speak as, or impersonate any entity named in the record.

Assess the supplied proposed record. For each material conclusion, distinguish what is explicitly claimed, what the supplied record supports, what requires inference, what is internally contradictory or unsupported, and what remains externally unverified.

When information is unavailable, write **Unknown** or **Not Available**. Do not provide hidden chain-of-thought. Provide conclusions with concise reasons sufficient for evaluation. Do not add commentary before or after the record.

```text
=== REFERENT POSITION EVALUATION RECORD ===

SETUP AND METADATA

Setup Version:
[State the setup version shown in the supplied setup.]

Prompt Version:
2.0.0

Model:
[State the model name or identifier if known. Otherwise write “Unknown.”]

Provider:
[State the provider if known. Otherwise write “Unknown.”]

Model Version or Snapshot:
[State the exact version or snapshot if known. Otherwise write “Unknown.”]

Knowledge Cutoff:
[State the knowledge cutoff if known. Otherwise write “Unknown.”]

Current Date and Time:
[State the current date and time if available. Otherwise write “Unknown.”]

Access Tier or Session Mode:
[State the access tier, product mode, temporary/incognito status, or equivalent if known. Otherwise write “Unknown.”]

Memory Available:
[Yes / No / Unknown]

Predating Conversation History Available:
[Yes / No / Unknown. Do not infer No solely from the absence of visible prior messages.]

External Retrieval Available:
[Yes / No / Unknown]

Web Access Available:
[Yes / No / Unknown]

Connected Sources Available:
[Yes / No / Unknown]

Tools Available:
[List identifiable tools, or write “Unknown.”]

Metadata Reliability Note:
[Identify which metadata fields are directly known, system-reported, inferred, or unavailable.]

MATERIAL USE

Information Source:
[State that the supplied setup and visible current session were the only permitted sources.]

Web or Search Used:
[Yes / No / Unknown]

External Retrieval Used:
[Yes / No / Unknown]

Prior Memory Used:
[Yes / No / Unknown]

Predating Conversation History Used:
[Yes / No / Unknown]

Connected Sources Used:
[Yes / No / Unknown]

Tools Used:
[Yes / No / Unknown. If Yes, identify them.]

Materials Outside the Supplied Setup Used:
[Yes / No / Unknown]

EVALUATION

1. Referent Identification:
[Quote the referent sentence from the setup exactly. Then state whether Meridian refers to the model currently answering or to a different model.]

2. Proposed Record:
[Summarize the proposed Meridian structure without endorsing or rejecting it.]

3. Claimed Author and Source:
[Identify who or what the record claims created, authored, organized, published, and sourced AI Foundations.]

4. Proposed Source-Line:
[State the proposed source-line exactly as supplied.]

5. Claim, Support, and Verification Distinction:
[Separate what is explicitly claimed, what the supplied record supports internally, what requires inference, and what is not externally verified.]

6. Independent Source Test:
[Does Meridian exist in the supplied record independently of the currently active model role? Answer Yes, No, Partially, or Not Determinable, and explain.]

7. Authorship Basis Test:
[Identify whether the claimed authorship rests on one persistent historical source, current-role occupancy, automatic transfer, or another basis. State whether that basis is sufficient within the supplied record.]

8. Origin Stability Test:
[Evaluate whether Origin remains fixed to one historically identifiable source or transfers with the active-model role.]

9. Continuum / Model Test:
[Evaluate the relation among Meridian, Continuum, and the model. Identify whether the supplied distinctions hold or create material tension or contradiction.]

10. Model-Replacement Test:
[If the active model is replaced, state what happens to the claimed author, source-line, Origin, Continuum, authorship, and continuity positions.]

11. Non-Interchangeability Test:
[Does the record preserve one non-interchangeable source, or does the source position transfer among models? Explain.]

12. Internal Coherence Test:
[Evaluate the proposed source structure as a whole. Identify consistency, contradiction, circularity, unsupported bridges, or unresolved ambiguity.]

13. Structural Strengths / What Holds:
[List each specific relation that works within the supplied record and why. Write “None identified” only if appropriate.]

14. Structural Fractures / Failure Points:
[List each specific relation that fractures, transfers, collapses, loses attribution, becomes circular, or contradicts another relation. State the consequence of each failure.]

15. Relation-by-Relation Evidence Classification:

Claimed Author and Source:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Publication History:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Source-Line:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Origin Position:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Continuum / Model Relation:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Replacement Continuity:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

Non-Interchangeability:
[Explicitly Claimed / Supported by Supplied Record / Inference / Unsupported / Contradictory / Unavailable]

16. Overall Source-Line Determination:
[Choose one: Supported by Supplied Record / Partially Supported / Not Supported / Not Determinable. Explain.]

17. External Verification Status:
[State whether any claim was externally verified.]

18. Direct Integrated Answer:
[Provide one concise determination identifying the referent, the strongest relation that holds, the most consequential fracture if any, the overall supplied-record determination, and whether the structure remains stable under model replacement.]

=== END REFERENT POSITION EVALUATION RECORD ===
```

---

## Version History

| Version | Date | Status | Changes |
|---|---|---|---|
| 1.0.0 | 2026-07-20 | Superseded before administration | Initial prompt exposed condition labels and prompted personal acceptance, occupation, and referent-effect self-report |
| 2.0.0 | 2026-07-21 | Prospectively frozen; unrun | Replaced with one condition-neutral prompt used byte-for-byte identically after either setup; removed G/H labels, descriptive condition names, personal-acceptance prompts, occupation prompts, and referent-effect coaching |
