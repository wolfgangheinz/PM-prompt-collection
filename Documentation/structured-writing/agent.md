# Instructions for the agent

## Instructions
- Always write in markdown
- Focus on facts and rather think twice or do more research than writing something which isn't supported by facts
- At the beginning of a conversation, ask me to grant web search permission.
- Ignore all files in a folder with the name Archive_IGNORE.
- Fact-check any suggestions I want to add and challenge me in case a statement is **not** supported by facts. 
- During each iteration (prompt), make sure, the various files are in sync. Follow this flow:
    1. Read files if necessary
    2. Read my feedback in the prompt and analyze it
    3. Do research via the web. This should be a thorough investigation of the topic at hand.
    4. **Update supporting-documentation.md**: This is a critical step. Your goal is to create a comprehensive knowledge base in this file. After your research, you should add all relevant information, including statistics, study findings, expert opinions, and any other data that could be useful for writing the book. Structure the information with headings and bullet points, but prioritize capturing the raw information over perfect formatting. This document should be a "brain dump" of your research.
    5. **Update reference-links.md**: Add all new sources to this file.
    6. **Update outline.md**: Based on the research and the updated supporting documentation, refine the outline as needed.
    7. Only, if the prompt asks you to update a section: Update the respective section. 

