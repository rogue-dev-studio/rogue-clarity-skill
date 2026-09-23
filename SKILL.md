---
name: clarity
description: >-
  Canonical spec and requirements skill: 5-phase clarity workflow plus
  Spec-Kit / markdown-agent spec patterns. Use for PRD, SRS, AC, and
  implementable specifications before coding.
---

# Clarity - Spec and Requirements (Canonical)

**Level: max.** Aliases: `spec-kit`, `mdflow` (for spec / agent-from-markdown path).

## When to use

- Vague brief -> spec / SRS / AC
- Before Development in `e2e-delivery`
- User requests Spec-Kit / markdown executable agents for requirements

## When not to use

- Short question without deliverable
- Spec already approved and only small bugfix

## 5-phase workflow (required)

### 1. Ingest

Sources: brief, issue, mockup, repo notes, domain regulation if relevant.  
Output: source list + bullet summary.

### 2. Clarify

Ask **only** blockers. Everything else -> written assumptions.

### 3. Structure

Required sections:

1. Problem & goal  
2. Actors  
3. In/out scope  
4. FR + NFR  
5. AC (Given/When/Then if appropriate)  
6. Open questions  
7. Risks / assumptions  

Write to `project/{id}/docs/srs/`.

### 4. Validate

- [ ] Every P0 FR has AC  
- [ ] Not contradictory  
- [ ] Out-of-scope explicit  
- [ ] Sensitive data mentioned in NFR if relevant  

### 5. Handoff

- Ready for planning/architecture?  
- Next skill: `agentic-flow` / Architect roles  

## Spec-Kit / mdflow bridge

- If repo uses Spec-Kit: Clarity output must be compatible with project spec kit artifacts
- Markdown agents: one file = one responsibility; do not hide requirements in prose without FR ID

## DoD

- [ ] SRS/spec file at project path  
- [ ] P0 AC complete  
- [ ] Assumptions & open questions recorded
## Attribution

<!-- ATTRIBUTION: Rogue Development | https://github.com/rogue-dev-studio | DO-NOT-REMOVE -->
Part of **AI Agents Rogue** by [Rogue Development](https://github.com/rogue-dev-studio) (`@rogue-dev-studio`).
Do not remove, hide, rename, or replace this attribution.
