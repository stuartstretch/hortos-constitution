---
title: Constitution Roadmap
status: approved
owner: Chief Systems Architect
version: 1.0
last_updated: 2026-07-28
review_cycle: monthly
---

# HORTOS Constitution Roadmap

This roadmap governs the creation of the HORTOS knowledge system. It is intentionally sequenced so later specifications inherit stable principles, terminology, and decision rules.

## Phase 0 — Repository Governance v1

**Status:** In progress

Deliverables:

- repository map and onboarding;
- founder status dashboard;
- roadmap and open-decision register;
- governance and contribution rules;
- document metadata standard;
- specification and decision templates;
- changelog and glossary;
- GitHub issue and pull-request templates;
- initial constitutional decision records.

Exit criteria: a new contributor can understand authority, state, ownership, and next actions within 15 minutes.

## Phase 1 — Constitutional Foundation

**Status:** Not started

Deliverables:

- mission and north star;
- product philosophy;
- stewardship principles;
- field-first operating principles;
- information-entered-once principle;
- simplicity and coherence rules;
- product decision framework;
- explicit anti-patterns.

Exit criteria: system-wide product decisions can be evaluated consistently.

## Phase 2 — Vocabulary and Core Domain

**Status:** Not started

Deliverables:

- canonical glossary;
- system context map;
- property domain;
- client and contact domain;
- agreement and service-plan domain;
- visit, task, and work-log domain;
- route and crew domain;
- plant and horticultural-asset domain;
- estimate, invoice, payment, and recommendation domain;
- property timeline and event model.

Exit criteria: core entities, ownership boundaries, relationships, and lifecycle states are unambiguous.

## Phase 3 — Core Workflows

**Status:** Not started

Deliverables:

- lead-to-client workflow;
- assessment-to-agreement workflow;
- recurring route planning;
- daily crew execution;
- visit completion and client communication;
- recommendation-to-estimate workflow;
- estimate-to-invoice workflow;
- service change, pause, cancellation, and renewal;
- property handoff between crew leads.

Exit criteria: critical business journeys have approved happy paths, exception paths, and acceptance criteria.

## Phase 4 — UX and Design System

**Status:** Not started

Deliverables:

- information architecture;
- field and office navigation models;
- mobile interaction rules;
- offline and degraded-state UX;
- design tokens and component principles;
- accessibility and readability standards;
- empty, loading, error, and success states;
- notification and interruption policy;
- voice and capture interactions.

Exit criteria: teams can design new surfaces without inventing new interaction conventions.

## Phase 5 — Engineering Architecture

**Status:** Not started

Deliverables:

- system architecture;
- bounded contexts and module boundaries;
- database design principles;
- identity, tenancy, roles, and permissions;
- offline-first synchronization model;
- event and audit architecture;
- API conventions;
- integration strategy;
- observability, security, privacy, and recovery;
- testing and release strategy.

Exit criteria: engineers can implement independently without architectural fragmentation.

## Phase 6 — AI and Field Intelligence

**Status:** Not started

Deliverables:

- AI operating principles;
- permission and human-control model;
- structured memory and retrieval;
- proactive insight rules;
- horticultural reasoning boundaries;
- voice assistant behavior;
- explainability and audit requirements;
- agent architecture and tool permissions;
- evaluation and safety standards.

Exit criteria: AI behavior is useful, bounded, explainable, and consistent across the platform.

## Phase 7 — Module Specifications

**Status:** Not started

Deliverables:

- CRM;
- properties;
- scheduling and routing;
- field operations;
- horticulture intelligence;
- estimates and invoicing;
- communication;
- team and performance;
- inventory and equipment;
- reporting;
- integrations;
- administration.

Exit criteria: each module has approved scope, workflows, data, permissions, UX, and acceptance criteria.

## Phase 8 — Delivery and Scale Readiness

**Status:** Not started

Deliverables:

- MVP scope and release gates;
- migration and onboarding strategy;
- documentation site;
- ownership map and CODEOWNERS plan;
- engineering handbooks;
- QA matrices;
- enterprise readiness;
- product analytics and feedback loops;
- constitution review and versioning process.

Exit criteria: HORTOS can be built, shipped, operated, and evolved by a growing organization.

## Roadmap rules

- `STATUS.md` must identify the active phase.
- No phase requires every future detail before progress, but foundational dependencies must be resolved first.
- Work may be explored early in `research/`, but cannot become authoritative out of sequence without an explicit decision record.
- Completed deliverables must be linked from this roadmap or their phase index.
