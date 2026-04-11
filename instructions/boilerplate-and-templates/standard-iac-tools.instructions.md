---
description: Boilerplate instructions for Infrastructure-as-Code repositories.
applyTo: "**/*.{tf,tfvars,tmpl,yaml,yml,json,sh,ps1}"
---

# Standard IaC Tools Instructions

Use these rules when generating or editing IaC code.

## General

- Prefer small, composable modules over monolith templates.
- Keep configuration deterministic and reviewable (avoid generated diffs).
- Treat secrets as out-of-repo. Never inline credentials in code.

## Naming

- Use consistent resource naming (prefix, environment, region).
- Avoid abbreviations unless they are already standard in the org.

## Safety

- Default to least privilege for IAM policies and roles.
- Avoid destructive operations unless explicitly requested.
- If a change can cause downtime, call it out and propose a rollout plan.

## Documentation

- Document module inputs/outputs.
- Add examples for non-obvious usage.
