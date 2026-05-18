# Design Principles

This document defines the core design principles of the KTP Trace Intelligence Specification v0.1.

The purpose of this specification is not to create an automatic judgment system.

Its purpose is to preserve trace evidence, document possible origin candidates, and support later review within the Kazene Trace Protocol.

---

## 1. Origin Candidates Are Not Final Origins

The most important principle of this specification is:

> Origin candidates are not final origins.

A Trace Intelligence Record must never claim that a candidate is the definitive origin of a work, structure, idea, question, or AI-generated output.

Instead, it records that a candidate may be relevant based on available trace evidence.

This distinction protects the specification from becoming a premature enforcement mechanism.

A record may say:

> This target appears structurally related to this origin candidate.

It must not say:

> This origin candidate is the final and legally valid origin.

---

## 2. Evidence Before Enforcement

Trace intelligence must begin with evidence, not enforcement.

A Trace Intelligence Record exists to collect and preserve evidence such as:

- semantic similarity;
- structural similarity;
- conceptual similarity;
- explicit citation;
- metadata;
- watermark evidence;
- chain-of-custody information;
- structure fingerprint references;
- human or AI-assisted observations.

These forms of evidence may support later review.

They must not directly trigger penalties, royalty allocation, account restrictions, or legal claims.

Evidence comes first.

Enforcement, if any, belongs to later governance layers.

---

## 3. Inference Is Not Judgment

Many trace relationships are inferential.

For example, a system may detect:

- similar conceptual structure;
- similar terminology;
- similar reasoning flow;
- similar layered architecture;
- implicit influence;
- possible absorption;
- paraphrase;
- translation;
- blended influence from multiple sources.

These signals are useful.

However, they are not final judgment.

Similarity may arise from:

- direct influence;
- shared cultural context;
- convergent development;
- common technical vocabulary;
- independent discovery;
- model-generated recombination;
- coincidence.

Therefore, every inference must remain reviewable.

---

## 4. Separate Provenance From Structure

Provenance and structure are related, but not the same.

Provenance refers to traceable history, such as:

- metadata;
- signatures;
- timestamps;
- content credentials;
- chain-of-custody logs;
- platform records.

Structure refers to internal patterns, such as:

- conceptual architecture;
- question design;
- reasoning sequence;
- philosophical framing;
- schema design;
- system relationships;
- multi-layer composition.

A file may have strong provenance but weak structural originality.

Another work may have weak metadata but strong structural similarity to an earlier origin candidate.

KTP Trace Intelligence must keep these layers separate.

This separation prevents metadata from being treated as the whole truth, and prevents structural similarity from being treated as proof of origin.

---

## 5. No Direct Allocation

A Trace Intelligence Record must not directly trigger royalty allocation.

This specification is not an allocation engine.

It does not calculate final contribution shares.

It does not determine who should be paid.

It does not assign ownership.

Allocation requires a separate process, such as an Allocation Readiness layer, human review, multi-wing review, dispute handling, and governance rules.

The correct flow is:

```text
Trace Intelligence Record
        ↓
Review / Dispute
        ↓
Allocation Readiness
        ↓
Royalty OS

This principle prevents premature value distribution based only on similarity scores.

6. Human or Multi-Wing Review Is Required

Trace intelligence may be assisted by AI systems, embedding models, structure fingerprint tools, or automated provenance systems.

However, important trace claims require review.

Review may be performed by:

a human reviewer;
a group of human reviewers;
a multi-agent review process;
a multi-wing AI architecture;
a governance body;
a hybrid human-AI process.

The review layer is especially important when a trace claim may affect reputation, allocation, rights, or institutional decisions.

Automated trace detection may observe.

It must not become the final judge.

7. Dispute Is Expected

Trace claims are not static.

They may be:

challenged;
revised;
rejected;
reaffirmed;
superseded;
merged with other claims;
escalated to governance review.

Dispute is not a failure of the system.

Dispute is part of the lifecycle.

A healthy trace protocol must allow uncertainty, disagreement, correction, and appeal.

For this reason, Trace Intelligence Records should be designed to connect naturally with dispute registry systems.

8. Transparency Over Certainty

Trace intelligence should prefer transparency over false certainty.

A record should clearly state:

what evidence exists;
what evidence is missing;
what method was used;
what confidence level was assigned;
what uncertainty remains;
what next review step is required.

A low-confidence but transparent trace record is better than a high-confidence black box judgment.

The goal is not to pretend that origin detection is perfect.

The goal is to make trace reasoning visible.

9. Preserve Uncertainty

Uncertainty should not be hidden.

It should be recorded.

A Trace Intelligence Record may include uncertainty notes, limitations, confidence scores, and recommended next steps.

This is especially important for cases involving:

implicit absorption;
blended influence;
model-generated recombination;
paraphrase;
translation;
structural similarity without citation;
cultural or technical convergence.

Uncertainty is not a weakness.

In trace governance, uncertainty is a safety feature.

10. Protect Against False Claims

Trace systems can be abused.

Possible abuses include:

false origin registration;
exaggerated influence claims;
malicious attribution;
reputation attacks;
automated claim spam;
artificial similarity manipulation;
attempts to capture royalties from weak evidence.

For this reason, KTP Trace Intelligence must avoid direct enforcement.

Every trace claim should remain open to review and dispute.

Evidence must be preserved, but not weaponized.

11. Support Multiple Origins

AI-mediated creation often does not come from a single source.

A target may be influenced by multiple origin candidates.

These may include:

one direct source;
several conceptual influences;
a structural template;
a translated work;
a paraphrased work;
a blended set of ideas;
an AI-generated recombination of many inputs.

The specification therefore supports multiple origin_candidates.

This reflects the reality of modern creation.

The goal is not to force every work into a single-origin model.

The goal is to document the trace field around the target.

12. Record the Trace Field, Not Only the Source

KTP Trace Intelligence is not only about finding “who came first.”

It is also about recording the field of influence around a target.

This may include:

origin candidates;
structural echoes;
conceptual dependencies;
missing citations;
weak signals;
uncertainty;
possible convergence;
review status;
allocation readiness.

In this sense, a Trace Intelligence Record is not a verdict.

It is a map.

13. Cultural Protocol, Not Only Technical Protocol

The Kazene Trace Protocol is not only a technical system.

It is also a cultural protocol.

The long-term goal is to encourage a culture where:

origins are respected;
citations are valued;
trace links are preserved;
derivatives acknowledge their roots;
review is possible;
disputes are handled fairly;
value circulation does not reward only surface-level copies.

A technical specification can support this culture.

It cannot replace it.

14. Trustworthy Trace, Not Perfect Trace

Perfect automatic trace detection is not realistic.

AI systems can paraphrase, blend, translate, compress, expand, and regenerate structures in ways that weaken direct evidence.

Metadata can be lost.

Watermarks can degrade.

Citations can be omitted.

Structure can survive even when surface expression changes.

Therefore, the purpose of this specification is not perfect trace.

The purpose is trustworthy trace.

Trustworthy trace means:

evidence is preserved;
uncertainty is visible;
candidates are not treated as verdicts;
review is required;
disputes are expected;
allocation is separated from detection.
15. Minimal but Extensible

This v0.1 specification is intentionally minimal.

It defines only the core record needed to preserve trace intelligence evidence.

Future versions may extend the model with:

stronger provenance bindings;
structure fingerprint references;
origin token integration;
dispute registry linkage;
allocation readiness profiles;
confidence scoring models;
multi-wing review protocols;
platform interoperability profiles;
privacy-preserving trace mechanisms.

The first goal is not completeness.

The first goal is a safe and usable minimum.

Summary

KTP Trace Intelligence Specification v0.1 is based on the following core commitments:

Candidate, not verdict.
Evidence, not enforcement.
Inference, not judgment.
Review before allocation.
Transparency over certainty.
Dispute as lifecycle.
Trustworthy trace, not perfect trace.

A Trace Intelligence Record is an evidence packet.

It observes, preserves, and prepares.

It does not decide, punish, or allocate.
