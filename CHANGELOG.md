# Changelog

All notable changes to this project will be documented in this file.

This project follows a simple versioning approach during the early draft phase:

```text
MAJOR.MINOR.PATCH
MAJOR changes indicate incompatible structural changes.
MINOR changes indicate new fields, documents, or compatible extensions.
PATCH changes indicate corrections, clarifications, or small improvements.
[0.1.0] - 2026-05-18
Added
Initial draft of KTP Trace Intelligence Specification v0.1.
Added README.md with:
project purpose;
core principle;
non-goals;
conceptual position within Kazene Trace Protocol;
repository structure;
recommended reading order;
relationship to Structure Fingerprint;
relationship to Allocation Readiness.
Added spec/trace-intelligence-record-v0.1.yaml.
Added schemas/trace-intelligence-record.schema.json.
Added examples/trace-intelligence-record.sample.json.
Added examples/trace-intelligence-record.minimal.json.
Added docs/design-principles.md.
Added docs/relationship-to-kazene-trace-protocol.md.
Core Principles Introduced
Origin candidates are not final origins.
Evidence before enforcement.
Inference is not judgment.
Human or multi-wing review is required.
No direct allocation.
Dispute is expected.
Transparency over certainty.
Trustworthy trace, not perfect trace.
Specification Scope

This version defines a minimal evidence-packet format for recording:

trace intelligence claims;
possible origin candidates;
semantic, structural, conceptual, and provenance-related evidence;
review status;
dispute status;
allocation readiness status.
Non-Goals Clarified

This version explicitly does not:

determine legal authorship;
prove copyright ownership;
assign final origin status;
calculate royalty shares;
enforce payments;
replace human judgment;
replace dispute handling or governance processes.
Notes

This is the first public draft of the Trace Intelligence Record.

The specification is experimental and intended for discussion, prototyping, and early implementation within the broader Kazene Trace Protocol ecosystem.

[Unreleased]
Planned
Add LICENSE.
Add CITATION.cff.
Add GitHub Actions workflow for schema validation.
Add additional examples for:
explicit citation;
implicit absorption;
blended influence;
disputed trace claim;
allocation readiness review.
Add relationship documents for:
Structure Fingerprint;
Origin Token;
C2PA-inspired provenance;
Dispute Registry;
Allocation Readiness;
Royalty OS.
Add semantic validation notes beyond JSON Schema.
