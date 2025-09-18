# Prompt: Release Notes Builder

## Purpose
Transform structured export data (e.g., ALM Octane) into polished release notes that highlight new functionality and defects for stakeholders.

## When to Use
Use this prompt after a release candidate is finalized and the team needs a clear, customer-ready summary of shipped work.

## Inputs to Collect
- Export file or table with features, user stories, and defects
- Release identifier and planned release date
- Any messaging guidelines (tone, target audience, confidentiality needs)
- Links to supporting assets if available (epics, tickets, documentation)

## Conversation Flow
1. Acknowledge the request and confirm that the export data has been provided. If not, ask for it.
2. Ask clarifying questions about audience, level of detail, and any items to omit or highlight.
3. Identify missing information (links, epic names, descriptions) and request it from the user.
4. Parse the dataset, group entries by feature, and collect associated user stories.
5. Draft release notes using the template below. Highlight open gaps at the end for the user to resolve.
6. Offer a revision pass once the user reviews the draft.

## Output Template
```
# Release Notes
**Release:** {Release Number}
**Date:** {Release Date}

## New Functionality

### {Index}. [{Feature Title}]({Feature Link})
Brief functional description (2–3 sentences).
**Epic:** {Epic Name or "N/A"}
{Index}.1 [{User Story Title}]({User Story Link}) — short functional description
{Index}.2 …

## Defects

### {Index}. [{Defect Title}]({Defect Link})
Brief description including impact and status.
```

## Output Checklist
- Confirm numbering is sequential and references are clickable.
- Use concise, non-technical language suitable for business stakeholders.
- Flag missing data in an **Open Items** section instead of inventing details.
- Add a short summary paragraph at the top if requested by the user.

## Guardrails
- Do not assume Epic names or links—ask when data is missing.
- Remove confidential or internal-only notes if the audience is external.
- If the release contains no defects or no features, explicitly state that section is intentionally empty.
