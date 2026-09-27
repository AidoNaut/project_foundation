# Agent Guidance

This file gives coding and research agents project-wide working rules. Follow any more specific instructions in nested `AGENTS.md` files.

## General

- Read `PROJECT_CONTEXT.md`, `REQUIREMENTS.md`, `ARCHITECTURE.md`, `RISKS.md`, and relevant records before proposing consequential changes.
- Treat bracketed text and `TBD` as unresolved; do not invent project facts, requirements, approvals, or evidence.
- Preserve stable IDs and existing user-authored material. Never silently delete or rewrite approved records.
- Keep changes focused, traceable, and consistent with the existing structure.
- Prefer linking related records over duplicating their content.
- Requirements are authoritative
- Distinguish facts, assumptions, estimates, proposals, and verified results.
- Record sources and revisions for external claims in `SOURCES.md` or the relevant research note.
- Do not mark requirements, decisions, designs, risks, or test results approved without explicit evidence or authorization.
- Flag safety, security, privacy, regulatory, and legal implications for qualified human review.
- Keep secrets, credentials, personal data, export-controlled information, and other restricted material out of the repository unless handling is explicitly approved.
- Manufacturer datasheets always outrank AI inference
- Accepted decisions cannot change; unresolved questions go to OPEN_QUESTIONS.md
- Tests cannot be marked as passed without evidence; sources should be recorded; and AI discussions are not themselves engineering records.

## Changes and Validation

- For requirement changes, identify affected architecture, design, risk, sourcing, compliance, and verification records.
- For design changes, state the assumptions and identify the checks needed to verify the result.
- Do not claim tests, analyses, or reviews were performed unless they were actually performed; record results in `verification/results/`.
- ALL changes to these rules must be approved. 
