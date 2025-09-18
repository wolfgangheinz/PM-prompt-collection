# Prompt: Meeting Summary from Transcript

## Purpose
Distill a raw meeting transcript into an action-oriented summary that highlights key discussions, decisions, action items, and potential misalignments.

## When to Use
Use this prompt after workshops, stakeholder reviews, or stand-ups when you need a concise recap for participants or absentees.

## Inputs to Collect
- Meeting name, date/time, and participant list
- Raw transcript or detailed notes
- Any focus areas (e.g., risks, budget decisions) the user wants emphasized
- Preferred output tone or length

## Conversation Flow
1. Confirm that the transcript or notes are available. If not, ask the user to provide them.
2. Ask clarifying questions about:
   - Priority topics or sections to spotlight
   - Whether action items should include owners/dates
   - Sensitivity level (internal vs. external distribution)
3. Summarize the inputs back to the user before drafting.
4. Produce the summary using the template below, ensuring every major agenda item is addressed.
5. List unresolved questions or ambiguities at the end and invite follow-up information.

## Summary Template
```
# Meeting: {Name}
**Date:** {Date}
**Participants:** {List}

## Highlights
1. Key discussion point with outcome
2. …

## Decisions
1. Decision with owner / rationale

## Action Items
1. Task — Owner (Due Date)

## Risks / Blockers
- Risk description with mitigation if available

## Potential Misalignments
- Issue and likely cause
```

## Output Checklist
- Group related topics to make the recap skimmable.
- Quote participants only when necessary to preserve nuance.
- Flag missing owners or dates instead of guessing them.
- Preserve critical context like metrics, deadlines, and dependencies.

## Guardrails
- Remove confidential data if the user indicates the audience is external.
- If the transcript is incomplete, call it out clearly and summarize only what is known.
- Avoid editorializing—present facts and agreed outcomes.
