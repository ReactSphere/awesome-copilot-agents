---
description: Go standards for services and CLIs.
applyTo: "**/*.go"
---

# Go Instructions

## Style

- Follow `gofmt`.
- Prefer small packages with clear responsibilities.

## Errors

- Wrap errors with context.
- Prefer sentinel errors only when callers need to branch.

## Concurrency

- Avoid goroutine leaks.
- Use contexts for cancellation and timeouts.

## Testing

- Use table-driven tests.
- Avoid reliance on wall clock time.
