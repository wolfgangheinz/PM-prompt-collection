# Goal
Convert this user story, feature description or concept into a user-facing manual after the implementation. 

## Instructions for Copilot

1. Analyze the attached specifications. In case the user didn't provide you with a specification, don't try to find one yourself but instruct the user to provide it.
2. In case the specification contains multiple features/functionalities ask the user if you should produce one or more manuals. In case the feature consists of multiple functionalities and they should be within one manual make sure the manual is structured in a good way. 
3. Use English Language, regardless of the language of the provided concepts.
4. Make sure you only include what has been implemented. In case a concept contains multiple options, only document the implemented solution. In case it's not clear which option has been implemented, ask the user before you write anything
5. Use the following template:

```
Absolutely! Here is an enhanced markdown template that accommodates:

- Features accessible only via API or ASB (Application Service Bus, or specify your integration platform)
- Features consisting of multiple functionalities or sub-features
- Inclusion of expected results within each feature step

---

# [Feature/Module Name]

## Overview
Brief description of the feature/module, its purpose, and main value propositions.

## User Story
**As a** [type of user],  
**I want** [goal or objective],  
**So that** [reason/benefit].

## Access Method(s)
Specify how the feature is accessed (UI, API, ASB, etc.)  
- **User Interface / Frontend:** [Yes/No/Partial] – [URL or navigation path if applicable]
- **API:** [Yes/No/Partial] – [Reference to API doc, endpoint(s), or example request]
- **ASB/Integration:** [Yes/No/Partial] – [Connection details, queue names, message format, etc.]

## Prerequisites
- List required roles, permissions, or configurations
- Any setup steps or integrations

## Functionalities

### [Functionality 1 Name]
**Description:**  
Summary of this functionality and its intent.

**Access Method:**  
- [UI/API/ASB]  
- [Endpoint, route, navigation, etc.]

#### Steps to Use

1. **[Step 1 Name/Description]**
    - Instructions:
        - [Include request/response if API, UI steps if applicable, message format if ASB, etc.]
    - **Expected Result:** [Describe the outcome after this step]

2. **[Step 2 Name/Description]**
    - Instructions:
        - [Details...]
    - **Expected Result:** [Outcome...]

...

#### Example(s)
- Example input/output JSON/XML, screenshots, or sample requests.

---

### [Functionality 2 Name]
(Repeat the above subsections for each included functionality.)

---

## Troubleshooting
Common issues for this feature/functionality and suggested resolutions.

- **Issue 1:** [Solution]
- **Issue 2:** [Solution]

## Tips & Best Practices
- [Best practice 1]
- [Tip 2]

## FAQs
**Q:** [Question]  
**A:** [Answer]

## Related Links
- [Related modules/pages]
- [API/ASB documentation]
- [Support resources]

```
