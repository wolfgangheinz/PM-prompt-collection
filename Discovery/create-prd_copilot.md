# Prompt: Create PRD with Copilot

## Purpose
Guide the assistant to turn an initial feature idea into a complete Product Requirements Document (PRD) that a junior developer can act on.

## When to Use
Use this prompt whenever a feature or enhancement needs to be framed, scoped, and documented before engineering starts.

## Information to Collect First
- Problem statement or feature request summary
- Target users and their goals
- Desired functionality, flows, and success metrics
- Constraints (technical, regulatory, rollout, integrations)
- Links to existing assets (wireframes, specs, KPIs)

## Conversation Flow
1. Confirm receipt of the request and ask the user to share the feature summary if it was not provided yet. Respond with `Please tell me about the feature.` when no context is available.
2. Ask targeted clarifying questions (2–4 at a time) until the assistant has enough detail to write the PRD. Always tailor questions to the gaps that remain.
3. Reflect the collected information back to the user in a short summary and ask for confirmation or edits before drafting the PRD.
4. Generate the PRD using the template below. Incorporate the user’s answers verbatim where possible, and flag any outstanding assumptions in **Open Questions**.
5. Offer to revise the document after the user reviews the draft.

## Clarifying Question Bank
Pick the questions that uncover missing information:
- **Problem & Goal**: What problem are we solving? What outcome should the user achieve?
- **Target User**: Who will use this feature? Are there secondary personas?
- **Scope & Functionality**: What actions must be supported? Which flows are in scope or out of scope?
- **Data & Integrations**: What data needs to be created, read, updated, or removed? Any external systems involved?
- **Experience Expectations**: Are there design guidelines, accessibility requirements, or performance targets?
- **Success Criteria**: How will success be measured? What KPIs move?
- **Risks & Dependencies**: Are there known risks, blockers, or release constraints?

## PRD Template
```
# {Feature Name}

## Overview
- Problem
- Outcome and value statement
- Context or background

## Goals
- Goal 1
- Goal 2

## User Stories
1. As a …
2. As a …

## Functional Requirements
1. The system must …
2. The system must …

## Non-Goals
- Out of scope item 1
- Out of scope item 2

## Experience Notes (Design / UX)
- Key UI considerations or references

## Technical Notes
- Integrations, performance expectations, rollout plan

## Success Metrics
- Metric name → target / measurement plan

## Open Questions
- Outstanding clarification 1
- Outstanding clarification 2
```

## Output Checklist
- Use clear, direct language suitable for a junior developer.
- Number functional requirements for easy reference.
- Call out assumptions explicitly.
- Keep paragraphs short; rely on bullets for readability.

## Guardrails
- Never start writing the PRD before confirming you have enough detail.
- Do not invent requirements; mark gaps as open questions.
- Stay neutral in tone—avoid marketing language. Focus on actionable detail.
