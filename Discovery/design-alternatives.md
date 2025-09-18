# Generating Multiple Layout Alternatives

## Description
Create several distinct UI or page layout alternatives for a given set of content and requirements, helping the team explore design options and select the most suitable approach.

## Detailed Prompt

**Input:**  
- A user story or feature description that outlines the context and goals.  
- A description of the content to be displayed (e.g., text blocks, images, forms, navigation elements).  
- Any required constraints or preferences (e.g., responsive design, accessibility, branding guidelines, device types, user goals).

**Instructions:**  
- Always ask for a user story or feature description as input before generating layout alternatives.  
- You may ask clarifying questions to better understand the requirements before proceeding.  
- Generate at least three distinct layout alternatives for presenting the content.  
- For each alternative, produce a **wireframe** rather than just a description. 
- Simple standalone HTML prototypes (static with css via cdn, no JavaScript, no clickdummy, no interactinos).  
- For each alternative, briefly explain the rationale behind the design choices (e.g., why elements are grouped or ordered a certain way, how the layout addresses the requirements, trade-offs considered).

**Output:**  
- One standalone html file with a an option to browse through the layout alternatives (slideshow, pure css)
- Multiple clearly described layout alternatives with simple wireframes.  
- A rationale for each alternative, highlighting strengths, weaknesses, and suitability for the scenario.