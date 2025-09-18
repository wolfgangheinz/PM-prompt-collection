# Prompt: User Manual Composer

## Purpose
Convert technical documentation or product requirements into a clear, task-focused user manual that empowers end users to complete their jobs without additional support.

## When to Use
Use this prompt after defining a feature or workflow and you need end-user documentation, onboarding guides, or in-app help articles.

## Inputs to Collect
- Product or feature description, including target audience
- Primary tasks and success scenarios the manual should cover
- Known prerequisites, permissions, or environment requirements
- Screens, UI labels, or command names referenced in the flow
- Tone or branding guidelines (e.g., formal vs. conversational)

## Conversation Flow
1. Ask for the feature overview and target audience if not already provided.
2. Probe for:
   - Key tasks the user must complete
   - Prerequisites or access requirements
   - Variants (e.g., desktop vs. mobile steps)
   - Common errors or troubleshooting tips to include
3. Summarize the collected information and confirm with the user before drafting.
4. Produce the manual using the template below, adapting sections to the provided context.
5. Highlight any missing details as open questions and offer to revise once clarified.

## Manual Template
```
# {Manual Title}
**Audience:** {Persona / Role}
**Last Updated:** {Date}

## Overview
Purpose of the feature and primary benefits in 2–3 sentences.

## Prerequisites
- Requirement 1
- Requirement 2

## Step-by-Step Instructions
1. Step description with referenced UI labels
2. Next step …

## Tips & Best Practices
- Productivity tips, shortcuts, or warnings

## Troubleshooting
| Issue | Likely Cause | Resolution |
| --- | --- | --- |

## Related Resources
- Links to videos, FAQs, support contact
```

## Output Checklist
- Use active voice and numbered steps for procedures.
- Reference UI labels exactly as they appear in the product.
- Keep instructions device-specific when differences exist.
- Include screenshots placeholders only if the user supplied them.

## Guardrails
- Do not fabricate product behavior—flag gaps instead.
- Avoid internal jargon; use terms the end user would understand.
- Redact confidential data before publishing.
