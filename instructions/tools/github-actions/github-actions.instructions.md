---
description: GitHub Actions workflow conventions.
applyTo: ".github/workflows/**/*.{yml,yaml}"
---

# GitHub Actions Instructions

## Reliability

- Prefer pinned major versions for actions (e.g. `@v4`).
- Avoid overly-broad triggers.

## Security

- Use least-privilege permissions.
- Avoid printing secrets.

## Maintainability

- Keep jobs small and clearly named.
- Prefer reusable workflows when patterns repeat.
