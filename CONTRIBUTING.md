# Contributing

Thanks for contributing to `ReactSphere/awesome-copilot-agents`.

## What To Contribute

We accept:

- Instructions: `*.instructions.md`
- Prompts: `*.prompt.md`
- Custom agents: `*.agent.md`
- Skills: folders that contain a `SKILL.md`
- MCP links: additions to the README list

## Folder Layout

- `instructions/`
- `prompts/`
- `agents/`
- `skills/`
- `.refs/` (assets used by docs)

## Conventions

### Markdown Front Matter

Prefer YAML front matter at the top of instruction, prompt, and agent files.

Example:

```yaml
---
description: Short description
applyTo: "**/*.ts"
---
```

### Naming

- Instructions: `something.instructions.md`
- Prompts: `something.prompt.md`
- Agents: `something.agent.md`

### Content Quality

- Be specific and actionable.
- Avoid “always do X” rules that conflict with common repositories.
- Prefer a small number of strong constraints over long checklists.

## Adding A New Entry

1. Add the markdown file to the appropriate folder.
2. Add a link to it in `README.md` under the correct category.
3. Ensure links are relative where possible.

## Local Validation (Optional)

If you use markdown linting in your editor or CI, fix warnings before submitting.

## Submitting A Pull Request

1. Create a feature branch.
2. Commit your change with a short, clear message.
3. Open a PR describing what you added and why.
