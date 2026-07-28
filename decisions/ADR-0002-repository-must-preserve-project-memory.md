---
title: ADR-0002 — Repository Must Preserve Project Memory
status: accepted
decision_date: 2026-07-28
owners:
  - Founder
  - Chief Systems Architect
reviewers: []
supersedes: []
superseded_by: []
---

# ADR-0002 — Repository Must Preserve Project Memory

## Context

The founder is managing multiple responsibilities and cannot be expected to remember every completed document, unresolved decision, dependency, or next action across a multi-week and eventually multi-year product effort.

A growing team will also need a shared understanding of current state without relying on individual memory or repeated verbal briefings.

## Decision

The repository must continuously preserve project memory through maintained status, roadmap, changelog, decision, ownership, and dependency records.

A contributor returning after an extended absence should be able to determine what is complete, what is active, what is blocked, and what comes next without reconstructing the project from chat history.

## Decision drivers

- Reduce founder cognitive load.
- Prevent repeated decisions and lost context.
- Make onboarding and handoffs reliable.
- Support asynchronous collaboration.
- Allow AI agents to operate from explicit current state.

## Consequences

### Positive

- Project continuity does not depend on one person's memory.
- Founder reviews can focus on high-value decisions.
- New contributors can orient quickly.
- Workstreams can pause and resume with less loss.

### Negative or accepted trade-offs

- Status and roadmap maintenance become part of the definition of done.
- Stale management files can mislead the team, so owners must update them promptly.

### Follow-on work

- Maintain `STATUS.md`, `ROADMAP.md`, `OPEN-DECISIONS.md`, and `CHANGELOG.md`.
- Add ownership and review metadata to authoritative documents.
- Establish issue and pull-request templates that prompt state updates.

## Reconsideration triggers

The specific tooling may change, but the requirement to preserve project memory remains constitutional.
