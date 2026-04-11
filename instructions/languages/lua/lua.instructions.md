---
description: Lua standards for scripting and automation.
applyTo: "**/*.lua"
---

# Lua Instructions

## Style

- Keep modules small.
- Prefer explicit local variables.

## Safety

- Validate external inputs.
- Avoid dynamic `load` unless sandboxed.

## Testing

- Add tests for non-trivial transformations.
