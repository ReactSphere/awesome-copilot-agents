---
description: Terraform conventions and safety checks.
applyTo: "**/*.{tf,tfvars}"
---

# Terraform Instructions

## Modules

- Keep modules focused.
- Document inputs/outputs.

## State Safety

- Do not suggest `terraform state rm` unless explicitly asked.
- Avoid moving resources without a clear migration plan.

## Variables

- Use explicit types.
- Provide sane defaults only when safe.

## Reviewability

- Prefer deterministic `for_each` keys.
- Avoid complex nested conditionals when readability suffers.
