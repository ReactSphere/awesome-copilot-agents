---
description: Kotlin standards for Android and JVM services.
applyTo: "**/*.kt"
---

# Kotlin Instructions

## Idioms

- Prefer data classes for simple models.
- Avoid nullable types when invariants can be enforced.

## Coroutines

- Use structured concurrency.
- Do not leak scopes.

## Testing

- Prefer deterministic tests.
- Test coroutine cancellation paths for async workflows.
