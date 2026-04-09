---
description: TypeScript standards for React/Node projects.
applyTo: "**/*.{ts,tsx}"
---

# TypeScript Instructions

## Types

- Prefer `unknown` over `any`.
- Avoid `as` casting unless there is a runtime check or strong invariant.
- Prefer discriminated unions for complex branching.

## APIs

- Favor typed inputs/outputs.
- Keep public interfaces stable and documented.

## React (If Applicable)

- Keep components small and focused.
- Prefer straightforward state; avoid premature memoization.
