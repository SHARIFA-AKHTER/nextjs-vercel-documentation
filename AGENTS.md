> **First-time setup**: Customize this file for your project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `mint.json`
- Run `mintlify dev` to preview locally
- Run `mintlify broken-links` to check links

## Terminology

- **Agent**: Use "Agent" instead of "Bot" or "AI Chatbot".
- **Workspace**: Use "Workspace" instead of "Project".
- **Leads**: Use "Leads" for individuals who provide information via the agent.
- **Knowledge Base**: Refers to the data used to train the agent.
- **Widget**: The chat interface visible on the website.

## Style preferences

{/* Project-specific style rules */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}

- **Included**: All user-facing features, onboarding steps, and widget customization for BoundBot.
- **Excluded**: Internal API logic and administrative backend tools.