---
title: ADR-0001 — Repository Is the Canonical Source of Truth
status: accepted
decision_date: 2026-07-28
owners:
  - Founder
  - Chief Systems Architect
reviewers: []
supersedes: []
superseded_by: []
---

# ADR-0001 — Repository Is the Canonical Source of Truth

## Context

HORTOS will be developed by a growing combination of founders, employees, contractors, domain experts, and AI agents. Decisions distributed across chats, meetings, mockups, code, and personal memory will become contradictory and inaccessible.

## Decision

The `hortos-constitution` repository is the canonical source of truth for HORTOS product, design, engineering, data, AI, terminology, and cross-functional operating decisions.

Code repositories may contain implementation-specific documentation, but they must reference and conform to the Constitution for system-wide meaning and direction.

## Decision drivers

- Preserve founder intent.
- Support a team of 20+ contributors.
- Make decisions searchable and reviewable.
- Give humans and AI agents the same authoritative context.
- Prevent chat history and implementation accidents from becoming policy.

## Options considered

### GitHub repository

Versioned, reviewable, linkable, compatible with engineering workflows and AI coding tools.

### Google Docs or disconnected documents

Easy to author, but weaker for ownership, dependency tracking, review discipline, and code-adjacent workflows.

### Code as the only source of truth

Accurately reflects current implementation but cannot reliably preserve intent, rejected alternatives, future direction, or cross-system principles.

## Consequences

### Positive

- Decisions become durable and traceable.
- New contributors have a defined onboarding path.
- Contradictions can be identified explicitly.
- Product and engineering can share one vocabulary.

### Negative or accepted trade-offs

- Documentation must be maintained alongside implementation.
- Contributors must follow review and metadata standards.
- The repository may occasionally lag unless completion rules are enforced.

### Follow-on work

- Maintain governance, templates, roadmap, status, and changelog.
- Link implementation repositories back to the relevant Constitution documents.
- Introduce automated validation as the repository matures.

## Reconsideration triggers

Reconsider the storage or publishing platform if scale, permissions, search, or access requirements materially exceed GitHub's usefulness. The need for a canonical source of truth is not reconsidered by a platform change.
