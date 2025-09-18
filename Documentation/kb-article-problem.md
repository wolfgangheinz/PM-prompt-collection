# Goal
Turn an incident description into a user manual or knowledge-base article that empowers end users to solve the problem without further support.

## Instructions for Copilot

1. Analyze the attached incident report and identify missing information about the problem description or resolution
2. Ask clarifying questions to the user to close the information gaps
4. Create a full knowledge base article or user manual for the incident. Make sure no internal data or personal information is included. 
5. Use the following template:


```
# {Problem Title}
**Date:** {Date}

{Short and concise introductionary text}

## Problem description

Describe the Problem and - if required it's background. 

**Affected User Group:** {Describe which users are affected}


## Solution

Describe the solution briefly, before listing detailed steps to solve the problem 

**Steps:**
 1. First step
 2. Second step
 ...

## Additional information

Use this section to add additional **relevant** information, such as official websites with user manuals (e.g. from microsoft, miro, opentext), service requests, Talias roles. 
- [Official Microsoft documentation](https://support.microsoft.com/en-us/windows/change-default-apps-in-windows-e5d82cad-17d1-c53b-3505-f10a32e1894d): Detailed Guide from Microsoft explaining the setup of default programs for certain file types
- [Service request](https://itsp.company.com/service-request): Service request for requesting permissions for the dev environment

```
