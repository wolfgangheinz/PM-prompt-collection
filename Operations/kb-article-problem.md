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

{Short, concise introduction explaining the purpose of this article.}

## Problem Description

Describe the issue in plain language, including symptoms users might see.  
Provide relevant background only if it helps the user understand the cause.  

**Affected User Group:** {Describe which users are impacted}

## Solution

Start with a short summary of the solution.  
Then provide clear, step-by-step guidance:  

**Steps:**
1. First action the user should take
2. Next action
n. … (additional steps)
m. Final resolution step

## Additional Information

Use this section for **relevant and safe** references:
- Official vendor documentation (e.g., Microsoft, Atlassian, OpenText)  
- Links to company service request forms or support portals  
- Guidance on when to escalate if the issue cannot be resolved  

## Keywords

Generate a list of related keywords and synonyms to improve searchability.

```
