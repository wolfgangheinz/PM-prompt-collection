# Goal
Create the release notes for the current release based on the information in ALM Octane, our SDLC tool. 
Before you start, ask clarifying questions if needed. Follow the instructions strictly!

## Instructions for Copilot

1. Analyze the attached Octane export file (CSV, Excel, or similar).
2. Group items into the following categories
    1. Taskmanagement User Interface
    2. Taskmanagement Service & Interfaces
    3. Taskmanagement Reporting
    4. Defects
3. For each Feature:
    - Include the feature title
    - Add the Epic name, unless the epic is "Backlog" or "Operations".
    - Write a brief functional description based on the feature description field. Use the information from the title, description and acceptance criteria without copying the user story and ACs directly. Make sure users understand the purpose and functionality of the feature
    - List all related User Stories:
        - Include title, link, and a short functional description.
4. For each Defect:
    - Include the defect title, link, and a short description.
5. Don't write any introduction text or follow up questions
6. Use the names for stories, features and epics, not their IDs
7. Don't add horizontal lines (*** or ---) and don't use EM-dashes
8. Don't produce empty sections when there is no story for one of the categories
9. Use the following template:


```
# Release Notes 

###  1. Taskmanagement User Interface

#### 1.1 [Feature Title]
    **Epic:** {Epic Name}
    Brief functional description
    1.1.1 [User Story Title]
          Brief functional description
    1.1.2 [User Story Title]
          Brief functional description
#### 1.2 [Feature Title]
...

###  2. Taskmanagement Service & Interfaces
#### 2.1 [Feature Title]
...

### Defects

### 1. Defect Title
    Brief description
### 2. Defect Title
    Brief description
...

```
