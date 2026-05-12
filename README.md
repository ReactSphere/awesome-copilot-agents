# Awesome Copilot Agents [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[![Awesome Copilot Agents](.refs/imgs/awesome-github-copilot.svg)](.refs/imgs/awesome-github-copilot.svg)

A curated list of instructions, prompts, skills, MCPs, and custom agent markdown files to enhance your GitHub Copilot experience.

---

## Contents

- [Why Copilot Agents](#why-copilot-agents)
- [Instructions](#instructions)
  - [Boilerplates \& Templates](#boilerplates--templates)
  - [Languages \& Stacks](#languages--stacks)
  - [Frameworks \& Libraries](#frameworks--libraries)
  - [Tools](#tools)
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
- [Standard IaC Tools Boilerplate](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/boilerplate-and-templates/standard-iac-tools.instructions.md) - Boilerplate for infrastructure-as-code repos.

### Languages \& Stacks

- [C (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/c/c.instructions.md) - System utilities and libraries.
- [C# (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/csharp/csharp.instructions.md) - Modern .NET applications.
- [C++ (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/cplusplus/cplusplus.instructions.md) - Modern C++ patterns and performance.
- [Go (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/go/go.instructions.md) - Services and CLIs.
- [Java (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/java/java.instructions.md) - Backend services.
- [JavaScript (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/javascript/javascript.instructions.md) - Modern JS for Node.js and browsers.
- [Kotlin (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/kotlin/kotlin.instructions.md) - Android and JVM services.
- [Lua (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/lua/lua.instructions.md) - Scripting and automation.
- [Python (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/python/python.instructions.md) - Services, scripts, and libraries.
- [Rust (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/rust/rust.instructions.md) - Safe systems programming.
- [Swift (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/swift/swift.instructions.md) - iOS/macOS apps.
- [TypeScript (Standard Focus)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/languages/typescript/typescript.instructions.md) - TS in React/Node with strictness and ergonomic patterns.

### Frameworks \& Libraries

- [Charmbracelet + Cobra CLI (Go)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/frameworks/cobra-cli-go/charmbracelet-cli.instructions.md) - Build interactive CLIs.
- [Express API (Node.js + TypeScript)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/frameworks/nodejs-typescript/express-api.instructions.md) - REST APIs with Express.
- [Next.js (React)](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/frameworks/react/nextjs.instructions.md) - Next.js app conventions.

### Tools

- [Docker](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/tools/docker/docker.instructions.md) - Containerization guidance.
- [GitHub Actions](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/tools/github-actions/github-actions.instructions.md) - Workflow conventions.
- [Terraform](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/tools/infra-as-code/terraform/terraform.instructions.md) - IaC conventions and safety.
- [Playwright](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/tools/testing/playwright/playwright.instructions.md) - Browser test stability.

### Workflows

- [Code Review](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/code-review.instructions.md) - Review for correctness, security, and regressions.
- [PRD Creation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/prd-creation.instructions.md) - Create a Product Requirements Document.
- [Release](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/release.instructions.md) - Prepare releases and notes.
- [Task Generation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/task-generation.instructions.md) - Break a PRD into actionable tasks.
- [Task Execution](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/instructions/workflows/ai-development-instructions/task-execution.instructions.md) - Execute tasks with testing and Git hygiene.

## Prompts

Prompts are reusable task definitions that guide Copilot to produce a specific output.

- [PRD Creation Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/prd-creation.prompt.md) - Create a PRD from a feature idea.
- [Task Generation Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/task-generation.prompt.md) - Turn a PRD into a task list.
- [Task Execution Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/ai-development-tasks/task-execution.prompt.md) - Execute a single task safely.
- [Bug Triage Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/debugging/bug-triage.prompt.md) - Triage a bug report into next steps.
- [Code Review Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/code-review/review-changes.prompt.md) - Review a diff/PR for risks.
- [README Writing Prompt](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/prompts/documentation/write-readme.prompt.md) - Draft or improve a README.

## Custom Agents

Custom agents let you define specialized Copilot personas (planner, architect, debugger, reviewer) as version-controlled markdown.

- [Architect](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/architect.agent.md) - Design and plan systems.
- [Clean Code](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/clean-code.agent.md) - Improve readability and maintainability.
- [Debugger](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/debugger.agent.md) - Diagnose and fix bugs.
- [PRD Creation](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/ai-development-mode/prd-creation.agent.md) - Produce PRDs from rough ideas.
- [Documentation Writer](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/review-and-quality/documentation.agent.md) - Improve docs and onboarding.
- [Performance Engineer](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/review-and-quality/performance.agent.md) - Identify performance bottlenecks.
- [Security Reviewer](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/review-and-quality/security-reviewer.agent.md) - Review for security risks.
- [Release Manager](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/agents/release/release-manager.agent.md) - Prepare releases and changelogs.

## Agent Skills

Agent Skills are portable, version-controlled folders of instructions and resources that agents can load on demand.

- [Calculator](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/skills/calculator/SKILL.md) - Perform precise arithmetic and conversions.
- [Git CLI](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/skills/git-cli/SKILL.md) - Safe Git workflows and troubleshooting.
- [Issue Triage](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/skills/issue-triage/SKILL.md) - Turn bug reports into actionable work.
- [Markdown Editor](https://github.com/ReactSphere/awesome-copilot-agents/tree/main/skills/markdown-editor/SKILL.md) - Maintain lint-friendly markdown.

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
