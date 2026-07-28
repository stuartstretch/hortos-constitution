---
title: Repository Governance
status: approved
owner: Chief Systems Architect
version: 1.0
last_reviewed: 2026-07-28
review_cycle: semiannual
---

# Governance

## Purpose

This repository preserves founder intent, records important decisions, and coordinates product, design, engineering, horticulture, operations, and AI work. Governance exists to keep the system coherent as the team grows.

## Roles

### Founder

Owns company vision, strategic priorities, commercial direction, and final escalation decisions.

### Chief Systems Architect

Owns repository coherence, system architecture, documentation standards, cross-domain consistency, decision traceability, and the integrity of the Constitution.

### Domain owner

Owns the correctness and maintenance of a defined product or technical domain.

### Reviewer

Validates work for domain accuracy, architectural fit, implementation clarity, and downstream impact.

### Contributor

May propose changes, research, specifications, and decision records through the contribution process.

## Authority model

Accepted decision records and approved constitutional documents are binding within their scope. Implementations and specifications must conform or explicitly propose a change.

No chat, meeting, mockup, issue comment, or code behavior silently overrides an approved decision.

## Change classes

### Minor

Clarification, typo correction, improved links, or wording that does not change meaning. Requires one appropriate reviewer.

### Substantive

Changes behavior, scope, terminology, data meaning, workflow, or responsibility. Requires the document owner and affected domain reviewers.

### Constitutional

Changes system-wide principles, primary domain boundaries, authority, security posture, or architectural direction. Requires an ADR and approval from the Founder and Chief Systems Architect.

## Decision protocol

1. Identify the problem and affected domains.
2. Check existing decisions and specifications.
3. Record alternatives and consequences.
4. Create or amend an ADR when the change is durable or cross-cutting.
5. Obtain required review.
6. Update all affected authoritative documents.
7. Update `STATUS.md`, `ROADMAP.md`, and `CHANGELOG.md` where relevant.

## Ownership rules

- Every authoritative document has one accountable owner.
- Ownership may be a named person or durable role.
- Ownership means maintaining accuracy, not exclusive authorship.
- Unowned authoritative documents must be assigned before substantive change.

## Review cadence

- Status: after every substantive change.
- Roadmap: monthly or whenever priorities materially change.
- Domain specifications: quarterly while active, semiannually when stable.
- Constitutional documents and ADRs: semiannually.
- Deprecated documents: archive or remove from active navigation promptly.

## Founder review policy

Founder attention is reserved for decisions involving vision, business model, material scope, brand promise, major sequencing, irreversible architecture, or significant risk. Routine consistency decisions should be resolved by the Chief Systems Architect and domain owners.

## Conflict resolution

When contributors disagree:

1. Use existing constitutional principles and accepted ADRs.
2. Prefer evidence from field operations and real users.
3. Optimize for system coherence over local convenience.
4. Escalate only the unresolved decision, with alternatives and consequences clearly stated.
