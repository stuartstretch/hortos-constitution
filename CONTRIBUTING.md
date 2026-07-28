---
title: Contribution Guide
status: approved
owner: Chief Systems Architect
version: 1.0
last_reviewed: 2026-07-28
review_cycle: semiannual
---

# Contributing to the HORTOS Constitution

## Core rule

Do not add isolated knowledge. Extend the existing system of record.

## Before proposing a change

1. Read `START-HERE.md`, `STATUS.md`, and the relevant roadmap phase.
2. Search for existing terminology, specifications, and decision records.
3. Identify the authoritative document and owner.
4. Determine whether the change is minor, substantive, or constitutional.
5. Record unresolved dependencies in `OPEN-DECISIONS.md` rather than hiding assumptions.

## Document requirements

Authoritative documents must include front matter with:

- `title`
- `status`
- `owner`
- `version`
- `last_reviewed`
- `review_cycle`

Add `depends_on`, `related`, and `supersedes` when useful.

## Writing standard

- Use direct, testable language.
- Define one concept in one authoritative location.
- Link instead of duplicating.
- Separate current requirements from future possibilities.
- Label assumptions, examples, and unresolved questions.
- Include anti-patterns where misinterpretation is likely.
- Preserve canonical terminology from `GLOSSARY.md`.

## Pull request expectations

A documentation pull request should state:

- why the change is needed;
- what authority level it affects;
- which documents or domains are impacted;
- whether an ADR is required;
- what remains unresolved;
- how reviewers can verify completeness.

## Completion checklist

- [ ] Existing sources were checked.
- [ ] Terminology is consistent.
- [ ] Status and owner are correct.
- [ ] Related documents are linked.
- [ ] Contradictions were resolved or flagged.
- [ ] Relevant ADRs were added or updated.
- [ ] `STATUS.md`, `ROADMAP.md`, and `CHANGELOG.md` were updated if needed.
- [ ] Deprecated guidance was marked or archived.

## AI-assisted contributions

AI-generated work must be reviewed by an accountable human or role owner. AI agents must not invent approvals, mark their own proposals approved, or resolve material contradictions silently.

Prompts and generated drafts are working material until reviewed and merged through the same process as human-authored work.
