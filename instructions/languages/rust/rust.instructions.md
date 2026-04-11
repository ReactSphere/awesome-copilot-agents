---
description: Rust standards for safe systems programming.
applyTo: "**/*.rs"
---

# Rust Instructions

## Ownership

- Prefer borrowing over cloning.
- Make lifetimes explicit only when necessary.

## Errors

- Prefer `thiserror`/`anyhow` if already used; otherwise keep error types simple.
- Include context when bubbling errors.

## Testing

- Add unit tests for parsing and invariants.
- Add property tests if the project already uses them.
