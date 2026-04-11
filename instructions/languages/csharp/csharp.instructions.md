---
description: C# standards for modern .NET applications.
applyTo: "**/*.{cs,csx}"
---

# C# Instructions

## Language

- Use nullable reference types.
- Prefer records for immutable data.
- Prefer `async`/`await` over blocking calls.

## APIs

- Validate inputs and return meaningful errors.
- Avoid exposing internal types.

## Dependency Injection

- Keep constructors simple.
- Prefer interfaces for external dependencies.

## Testing

- Add tests for business logic.
- Prefer deterministic tests (avoid timing flakiness).
