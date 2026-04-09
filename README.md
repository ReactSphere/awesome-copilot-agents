# Awesome Copilot Agents [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[![Awesome Copilot Agents](.refs/imgs/awesome-github-copilot.svg)](.refs/imgs/awesome-github-copilot.svg)

A curated list of instructions, prompts, skills, MCPs, and custom agent markdown files to enhance your GitHub Copilot experience.

---

## Contents

- [Why Copilot Agents](#why-copilot-agents)
- [Instructions](#instructions)
  - [Boilerplates \& Templates](#boilerplates--templates)
  - [Languages \& Stacks](#languages--stacks)
  - [Workflows](#workflows)
- [Prompts](#prompts)
- [Custom Agents](#custom-agents)
- [Agent Skills](#agent-skills)
- [MCPs](#mcps)
- [How to Use](#how-to-use)

## Why Copilot Agents

Customized instructions, prompts, skills, MCPs, and custom agents help guide GitHub Copilot by adding repository context: coding standards, toolchains, frameworks, conventions, and preferred workflows.

Tip: Learn more about customizing GitHub Copilot in VS Code in the [VS Code documentation](https://code.visualstudio.com/docs/copilot/customization/overview).

## Instructions

Instructions provide Copilot with repository-specific context to improve suggestions.

### Boilerplates \& Templates

- [Standard Language Template](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/boilerplate-and-templates/standard-language.instructions.md) - A minimal template for new instruction files.

### Languages \& Stacks

- [JavaScript (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/javascript/javascript.instructions.md) - Modern JS for Node.js and browsers.
- [TypeScript (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/typescript/typescript.instructions.md) - TS in React/Node with strictness and ergonomic patterns.

### Workflows

- [PRD Creation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/prd-creation.instructions.md) - Create a Product Requirements Document.
- [Task Generation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/task-generation.instructions.md) - Break a PRD into actionable tasks.
- [Task Execution](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/task-execution.instructions.md) - Execute tasks with testing and Git hygiene.

## Prompts

Prompts are reusable task definitions that guide Copilot to produce a specific output.

- [PRD Creation Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/prd-creation.prompt.md) - Create a PRD from a feature idea.
- [Task Generation Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/task-generation.prompt.md) - Turn a PRD into a task list.
- [Task Execution Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/task-execution.prompt.md) - Execute a single task safely.

## Custom Agents

Custom agents let you define specialized Copilot personas (planner, architect, debugger, reviewer) as version-controlled markdown.

- [Architect](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/architect.agent.md) - Design and plan systems.
- [Clean Code](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/clean-code.agent.md) - Improve readability and maintainability.
- [Debugger](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/debugger.agent.md) - Diagnose and fix bugs.
- [PRD Creation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/prd-creation.agent.md) - Produce PRDs from rough ideas.

## Agent Skills

Agent Skills are portable, version-controlled folders of instructions and resources that agents can load on demand.

- [Calculator](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/skills/calculator/SKILL.md) - Perform precise arithmetic and conversions.

## MCPs

MCPs (Model Context Protocol servers) connect agents to tools and data sources.

- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Repo, issues, PRs, and workflows.
- [Model Context Protocol Servers](https://github.com/modelcontextprotocol/servers) - Official reference servers.

## How to Use

### VS Code Setup

1. Install and sign in to GitHub Copilot.
2. Keep your reusable assets version-controlled so your whole team can share them.

### File Types

| Type                | Purpose                                  |
| ------------------- | ---------------------------------------- |
| `*.instructions.md` | Contextual instructions.                 |
| `*.prompt.md`       | Reusable prompts.                        |
| `*.agent.md`        | Custom agents (personas).                |
| `SKILL.md`          | Skill definition inside a skill folder.  |

### Formatting

Use YAML front matter for metadata such as `description`, `mode`, and `applyTo`.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md).

Licensed under the MIT License. See [LICENSE](LICENSE).
