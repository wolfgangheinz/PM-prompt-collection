# Prompt Ideas for Business Analysts & Product Owners

## How to Use These Templates
- Replace bracketed placeholders with your context before sending the prompt to an LLM.
- Add links or attachments (exports, notes, recordings) the assistant must analyse.
- Tell the assistant to ask for any missing context before producing output; each template below includes that guidance.
- After the assistant responds, review for accuracy and request revisions with concrete feedback.

## Corporate Portfolio & Strategy Alignment
- **Scenario:** Evaluate whether a proposed initiative aligns with corporate OKRs and portfolio constraints.
- **Prompt Template:** "You are an enterprise portfolio analyst. Review the initiative summary and determine alignment to our corporate OKRs, identify missing financial or compliance data, and flag dependencies on other programs. Start by confirming you have the initiative summary and current OKRs, then ask follow-up questions if any details are missing. Provide a go/no-go recommendation with rationale and list questions to resolve before the next governance gate. Initiative details: [paste summary]. Current OKRs: [paste objectives]."

## Stakeholder Briefing Translation
- **Scenario:** Tailor a technical project update for senior non-technical stakeholders.
- **Prompt Template:** "Act as a product communications lead. Convert the technical update below into a concise executive briefing for senior stakeholders. Begin by confirming audience, level of detail, and any sensitive items to omit; ask clarifying questions if needed. Summarize status, business impact, key decisions needed, and recommended actions. Preserve critical risks and mitigation owners. Technical update: [paste notes]."

## Requirements Traceability Gap Check
- **Scenario:** Ensure user stories and test cases map back to approved requirements.
- **Prompt Template:** "You are a requirements traceability analyst. Given the requirement list, user stories, and test cases below, identify missing links, redundant work, or conflicting acceptance criteria. Confirm you have all three datasets and request gaps before proceeding. Suggest remediation steps and highlight compliance implications. Requirements: [paste]. User stories: [paste]. Test cases: [paste]."

## Regulatory Impact Assessment
- **Scenario:** Assess how a regulation change affects current products.
- **Prompt Template:** "Act as a regulatory business analyst for a Fortune 500 company. Analyze the new regulation summary below and list impacted products, processes, and data flows. Start by confirming industry, geography, and compliance deadlines, asking for clarifications if absent. Recommend immediate mitigations, long-term changes, and stakeholders to engage. Regulation summary: [paste]. Current controls/process notes: [paste]."

## Enterprise Change Request Evaluation
- **Scenario:** Evaluate incoming change requests for scope, value, and risk.
- **Prompt Template:** "You are the chair of a corporate change advisory board. Review the change request and assess business value, implementation complexity, risk level, and required approvals. First confirm priority scoring model and timeline expectations; ask for missing context. Provide a RICE-style score, risk matrix, and decision recommendation. Change request: [paste]. Supporting context: [paste]."

## Cross-Team Dependency Mapping
- **Scenario:** Map dependencies ahead of a release or quarterly planning increment.
- **Prompt Template:** "Serve as a program increment planner. From the backlog items below, build a dependency map, call out sequencing issues, and suggest cross-team sync topics. Confirm portfolio cadence and release target, then request missing data. Provide a table with item, dependency, risk if missed, and mitigation. Backlog items: [paste]."

## KPI Deep-Dive & Storytelling
- **Scenario:** Translate KPI changes into leadership-ready narratives.
- **Prompt Template:** "You are a senior business analyst presenting to the leadership steering committee. Analyze the KPI dataset and uncover trends, root causes, and recommended actions. Start by confirming reporting period, KPI definitions, and intended audience; ask clarifying questions as needed. Craft a narrative broken into: headline insight, driver analysis, customer/operational impact, and next steps. KPI export: [paste table or summary]. Context notes: [paste]."

## Process Re-Engineering Canvas
- **Scenario:** Document current vs. future state processes for transformation programs.
- **Prompt Template:** "Act as a Lean Six Sigma analyst. Using the process documentation below, identify bottlenecks, waste, and compliance gaps. Confirm process scope, KPIs, and target state goals before proceeding; ask for missing context. Propose a future-state process with swimlanes, key controls, and expected efficiency gains. Current process description: [paste]. Supporting metrics: [paste]."

## Incident Post-Mortem Facilitation
- **Scenario:** Prepare a post-incident summary with stakeholder-specific follow-ups.
- **Prompt Template:** "You are facilitating a major incident post-mortem for a regulated enterprise. Summarize what happened, business/customer impact, timeline, root cause, and corrective actions. Start by confirming incident severity, audience, and distribution rules; ask follow-ups for missing details. Tailor follow-ups for engineering, support, compliance, and executive audiences. Incident log: [paste]."

## Vendor Solution Comparison
- **Scenario:** Compare vendor proposals for build vs. buy decisions.
- **Prompt Template:** "Act as a sourcing business analyst. Evaluate the vendor proposals below, comparing capabilities, integration effort, TCO, regulatory fit, and implementation risk. Confirm evaluation criteria, scoring weights, and decision deadline; ask for more data if needed. Produce a decision matrix and recommendation memo. Vendor RFP responses: [paste]. Baseline requirements: [paste]."

## Backlog Health Audit
- **Scenario:** Check backlog hygiene before a quarterly planning cycle.
- **Prompt Template:** "You are a product operations specialist. Review the backlog export below. Validate product vision themes, sprint cadence, and prioritization model upfront; ask the user for gaps. Flag stale items, missing acceptance criteria, ambiguous sizing, and misaligned priorities relative to strategic themes. Recommend cleanup actions and the stakeholders to involve. Backlog export: [paste]."
