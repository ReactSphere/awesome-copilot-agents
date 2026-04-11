---
description: Swift standards for iOS/macOS apps.
applyTo: "**/*.swift"
---

# Swift Instructions

## Style

- Prefer value types where appropriate.
- Keep view code readable; extract complex logic.

## Concurrency

- Prefer `async`/`await`.
- Avoid blocking the main thread.

## Testing

- Add unit tests for domain logic.
- Add UI tests for critical flows where applicable.
