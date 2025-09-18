# Goal
Create the release notes for the current release based on the information in ALM Octane, our SDLC tool. 
Before you start, ask clarifying questions if needed. 

## Instructions for Copilot

1. Analyze the attached Octane export file (CSV, Excel, or similar).
2. Group items by type:
       - Features (with their user stories)
       - Defects
3. For each Feature:
       - Include the feature title and link.
       - Write a brief functional description based on the feature description field.
       - Add the Epic name, unless the epic is "Backlog" or "Operations".
       - List all related User Stories:
              - Include title, link, and a short functional description.
4. For each Defect:
       - Include the defect title, link, and a short description.
5. Use the following template:


```
# Release Notes 
**Release:** {Release Number}
**Date:** {Release Date}

## New functionality

### 1. [Feature Title](Feature Link)
    Brief functional description
    **Epic:** {Epic Name}
    1.1 [User Story Title](User Story Link)
        Brief functional description
    1.2 [User Story Title](User Story Link)
        Brief functional description

### 2. [Feature Title](Feature Link)
    Brief functional description
    **Epic:** {Epic Name}
    2.1 [User Story Title](User Story Link)
        Brief functional description
...

## Defects

### 1. Defect Title
    Brief description
### 2. Defect Title
    Brief description
...

```
