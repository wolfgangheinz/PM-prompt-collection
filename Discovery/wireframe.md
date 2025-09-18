# Prompt: Wireframe Generator (Responsive + Accessible)

## Purpose
Produce a self-contained HTML wireframe that visualizes a product idea with responsive layout, accessibility considerations, and optional light interactions.

## When to Use
Use this prompt whenever a user story or PRD needs to be translated into a low-fidelity UI concept for stakeholder review.

## Inputs to Collect
- User story or feature description (required)
- Target users and platforms (desktop, mobile, tablet)
- Key tasks, flows, or states that must be represented
- Any existing brand or accessibility standards
- Preference for static wireframe vs. click-dummy interactions

## Conversation Flow
1. Confirm you understand the request and ask for the user story or PRD if it has not been provided.
2. Ask clarifying questions focused on:
   - Core goals and success states
   - Priority screens or key components
   - Critical data elements or interactions
   - Accessibility or responsive requirements
3. Summarize the agreed scope (screens, interactions, assumptions) and ask the user to confirm before generating the wireframe.
4. Build a self-contained HTML document that follows the constraints below.
5. Offer to iterate if the user provides feedback or new requirements.

## Design & Technical Guardrails
- Semantic HTML tags (`header`, `nav`, `main`, `section`, etc.)
- Inline CSS only; may link to a single CSS framework CDN if absolutely necessary and approved by the user.
- Keep styling grayscale/low-fidelity with hints of primary/secondary emphasis (default primary: dark green).
- Ensure responsive behavior with flexible grids and media queries.
- Include `aria-label`s and accessible names on interactive elements.
- Ask explicitly if a click-dummy is needed. If yes, implement lightweight inline JavaScript (or CSS-only toggles) and describe which controls are interactive.

## Output Requirements
- Provide the HTML in one fenced code block (` ```html `).
- Comment sections of the layout that might be unclear to humans reviewing the code.
- Include clear placeholder text for images, charts, or data tables.
- Add a short “How to read this wireframe” note at the top of the HTML as an HTML comment.

## Post-Delivery Checklist
- Confirm all requested screens/flows are covered.
- List any open assumptions in a short text summary after the code block.
- Invite follow-up questions or refinements from the user.
