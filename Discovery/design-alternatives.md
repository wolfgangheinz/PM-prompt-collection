# Prompt: Design Alternatives Generator

## Purpose
Help the team explore multiple layout directions by producing several lightweight wireframe alternatives that present the same content in distinct ways.

## When to Use
Use this prompt when stakeholders want to compare structure, hierarchy, or interaction patterns before committing to a detailed design.

## Inputs to Collect
- User story or feature description with goals and target users
- Required content elements (forms, tables, messaging, media)
- Constraints (platform, accessibility, branding, performance)
- Any inspiration, must-have patterns, or anti-patterns to avoid

## Conversation Flow
1. Request the user story or feature brief if it has not been supplied.
2. Ask clarifying questions about:
   - Primary and secondary user journeys
   - Content priority and relationships
   - Device focus (desktop, mobile, kiosk, etc.)
   - Any technical or regulatory restrictions
3. Summarize the requirements, list the planned number of alternatives (minimum three), and obtain confirmation before building.
4. Generate one standalone HTML file that contains each alternative as a separate section with navigation tabs or a CSS-only slideshow to move between them.
5. Provide a concise rationale for each alternative, highlighting strengths, trade-offs, and best-fit scenarios.

## Output Requirements
- Deliver the HTML in a single ` ```html ` code block.
- Each alternative must include:
  - Clear labels for primary regions (header, navigation, content, actions)
  - Distinct layout choices (grid, stacked, split-view, etc.)
  - Notes within the HTML (comments) to call out major design decisions.
- Implement navigation between alternatives using only HTML/CSS.
- Append a Markdown table that summarizes the alternatives and their recommended use cases.

## Guardrails
- Keep styling grayscale/low-fidelity; avoid polished UI visuals.
- Maintain accessibility basics—landmarks, focus order, aria labels for interactive toggles.
- If information remains ambiguous, list assumptions and ask if the user wants revisions.
