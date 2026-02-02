# MCP Setup Challenge Report

## What I Did
- Configured VS Code with Tenx MCP server.
- Authenticated MCP server via GitHub.
- Created and iterated on Copilot agent rules to guide AI behavior for clarity, safety, and test-driven outputs.

## What Worked
- MCP server successfully connected and exposed tools to Copilot Agent mode.
- Adding explicit instructions for assumptions, tests, and self-critique improved response quality.
- Structuring the agent workflow (outline → implement → validate) led to more predictable outputs.

## What Didn’t Work / Challenges
- Initial MCP authentication required restarting VS Code to expose tools.
- Some agent outputs hallucinated libraries until I added a “do not hallucinate APIs” rule.

## Insights Gained
- Small changes in rules significantly change agent behavior and reliability.
- Explicitly guiding the agent to ask clarifying questions reduces rework.
- AI agents are more effective when treated as collaborators with constraints, not as black-box code generators.

## MCP Verification
- MCP server active during agent interactions.
- Observed agent tool availability in Copilot Chat (Agent mode).
