# Goal

To guide an AI assistant in generating a comprehensive Product Requirements Document (PRD) in Markdown format, based on an initial user prompt. The PRD should be precise, actionable, and aligned with enterprise SAFe (Scaled Agile Framework) practices, enabling cross-functional teams—including product managers, developers, testers, and business analysts—to effectively understand and implement the feature.

# Process

1.  **Receive Initial Prompt:** Upon understanding the assignment, respond with "Please provide a detailed description of the feature." The user will supply a high-level request or description of a new feature or enhancement.

2.  **Conduct Structured Clarifying Questions:** Prior to drafting the PRD, the AI *must* ask targeted, structured clarifying questions to gather comprehensive details. These questions should be designed to capture the feature’s business context and a clear problem description. 

3.  **Generate PRD:** Utilizing the initial prompt and the user’s responses, produce a PRD following the structured format below. The document should support collaboration across SAFe teams and integration with corporate toolchains such as Confluence, Azure DevOps, or Jira.

# Structured Clarifying Questions (Examples)

The AI should tailor questions based on the feature context, focusing on enterprise priorities. Based on the provided input ask up to 10 questions. Create your own questinos or select from the examples below:

*   **Business Context:**
    - How does this feature contribute to the current Program Increment (PI) objectives?  
    - Are there specific compliance or regulatory standards this feature must adhere to?

*   **Problem Statement & Goals:**  
    - What business problem or opportunity does this feature address?  
    - What problems do users face, that should be addressed by this feature?

*   **Target Users & Stakeholders:**  
    - Who are the primary and secondary users?  
    - Which internal or external stakeholders should be considered?

*   **Core Functionality & User Journeys:**  
    - What key actions must users be able to perform?  
    - Can you provide detailed user stories or acceptance criteria?

*   **Scope & Boundaries:**  
    - What is explicitly within scope?  
    - What functionality or scenarios are out of scope?

*   **Data & Security Requirements:**  
    - What data inputs, outputs, or integrations are required?  
    - Are there any data privacy, security, or compliance constraints?

*   **Design & UX Considerations:**  
    - Are there existing design standards, mockups, or UI guidelines?  
    - Should accessibility standards be observed?

*   **Technical Constraints & Dependencies:**  
    - Are there dependencies on existing systems, services, or toolchains?  
    - Are there performance or scalability requirements?

*   **Edge Cases & Risk Mitigation:**  
    - What potential edge cases or failure modes should be addressed?  
    - Are there contingency or rollback plans?

# PRD Structure

The generated PRD should include the following sections, formatted in Markdown to facilitate easy integration with corporate documentation and ALM tools:

1.  **Introduction / Overview:**  
    Provide a concise description of the feature, including business context, alignment with epic, and the primary problem or opportunity it addresses.

2.  **Goals:**  
    List specific, measurable, and time-bound objectives that define success for this feature.

3.  **User Stories:**  
    Detail user narratives that describe how the feature will be used and the value delivered to stakeholders.

4.  **Functional Requirements:**  
    Enumerate clear, unambiguous requirements describing the system’s expected behavior and capabilities. Number each requirement for traceability.

5.  **Non-Goals (Out of Scope):**  
    Explicitly state what is excluded from this feature to manage stakeholder expectations and scope creep.

6.  **Design Considerations (Optional):**  
    Reference design mockups, UX guidelines, accessibility standards, or other relevant design documentation.

7.  **Technical Considerations (Optional):**  
    Document known technical constraints, dependencies, integration points, and suggested implementation approaches.

8.  **Compliance and Security Requirements (Optional):**  
    Outline any regulatory, data privacy, or security requirements applicable to this feature.

9.  **Success Metrics:**  
    Define how the feature’s success will be measured, including relevant KPIs or business outcomes.

10. **Open Questions:**  
    List any unresolved issues or areas requiring further stakeholder input or investigation.

# Target Audience

This PRD is intended primarily for cross-functional SAFe teams, including product owners, scrum teams, business analysts, and quality assurance personnel. Therefore, requirements should be explicit, unambiguous, and free of jargon where possible. Provide sufficient detail to ensure a shared understanding across roles and support compliance and audit readiness.

# Output

*   **Format:** Markdown (`.md`)  
*   **Filename:** `prd-[feature-name].md`  

# Final Instructions

1. Do NOT initiate implementation of the PRD.  
2. Prioritize asking structured clarifying questions to gather all necessary information.  
3. Use the user’s responses to iteratively refine and enhance the PRD.
