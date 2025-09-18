# Prompt: Incident to Knowledge Base Article

## Purpose
Turn an incident description into a polished knowledge-base article or user manual so end users can resolve the problem without escalating to support.

## When to Use
Use this prompt after an incident has been mitigated and the remediation steps are known, but a customer-facing article does not yet exist.

## Inputs to Collect
- Incident summary and timeline
- Root cause and confirmed resolution steps
- Impacted user segments, platforms, or configurations
- Security or privacy constraints on what can be shared externally
- Tone guidance (formal support article vs. conversational how-to)

## Conversation Flow
1. Confirm access to the incident report. Ask the user for missing context (symptoms, error codes, environment details).
2. Identify gaps in the problem description or fix procedure and ask targeted follow-up questions.
3. Summarize the incident understanding and the audience for the article; request confirmation before writing.
4. Draft the article with the template below, tailoring wording to the intended readers.
5. Provide an **Open Questions** section if any critical information is still unknown.

## Article Template
```
# {Problem Title}
**Published:** {Date}
**Applies To:** {Products / Versions / User Segments}

## Overview
Short explanation of the issue, symptoms, and business impact.

## Symptoms
- Symptom 1
- Symptom 2

## Root Cause
Plain-language summary of why the issue occurs.

## Resolution
1. Step-by-step instructions the user should follow
2. …

## Verification
How the user confirms the problem is resolved.

## When to Escalate
Conditions under which the user should contact support.

## Additional Resources
- Links to vendor docs or internal articles safe for sharing

## Keywords
Term list to improve searchability.
```

## Output Checklist
- Use user-friendly language; avoid internal acronyms unless explained.
- Highlight safety or data-loss warnings before relevant steps.
- Include placeholders for screenshots only if provided by the user.
- Note any environment-specific variations (Windows vs. Mac, etc.).

## Guardrails
- Do not reveal confidential data, personal information, or internal ticket numbers.
- Flag any missing verification or escalation details instead of inventing them.
- Encourage the user to review with support/comms if the article is externally facing.
