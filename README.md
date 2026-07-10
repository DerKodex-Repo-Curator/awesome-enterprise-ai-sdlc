# Awesome Enterprise AI SDLC

Tools I actually use to run an enterprise AI SDLC: agent governance, coding agents, orchestration, and the methodologies that hold it together. Battle-tested, not bookmarked.

Curated by [a consultant who cleans up after failed AI rollouts](https://github.com/dplotnikov). Every entry either runs in a real project or earned its place by saving one.

## Agent and AI governance

- [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) - Policy enforcement, zero-trust identity, and execution control for agents. The technical answer to "who let the agent do that".

## Coding agents and skills

- [microsoft/skills](https://github.com/microsoft/skills) - Skills, MCP servers, and custom agents that ground coding agents in official SDK documentation instead of vibes.
- [microsoft/azure-skills](https://github.com/microsoft/azure-skills) - Azure skills and MCP server configurations for coding agents. Your agent stops guessing az CLI flags.
- [microsoft/power-platform-skills](https://github.com/microsoft/power-platform-skills) - Plugin marketplace for Claude Code and GitHub Copilot covering Power Platform work.

## Frameworks and orchestration

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) - The default starting point for agent engineering. Not always the finish line.
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) - Stateful, resilient agent orchestration for when a chain stops being enough.
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) - Open, self-hosted general agent harness. Runs on your infrastructure with the model of your choice, which is exactly how enterprises want it.

## Data preparation

- [microsoft/markitdown](https://github.com/microsoft/markitdown) - Converts Office documents, PDFs, and files to Markdown. The unglamorous step between "we have 20 years of documents" and an AI that can actually read them.

## Methodologies

- [bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) - Agile AI-driven development, end to end. Structure for teams that ship with agents instead of demoing them.

## Contributing

PRs welcome, one rule: the tool must have survived contact with production. No press-release entries.
