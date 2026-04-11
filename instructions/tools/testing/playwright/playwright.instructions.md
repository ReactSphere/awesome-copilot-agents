---
description: Playwright testing conventions.
applyTo: "**/*.{spec,test}.{ts,tsx,js,jsx}"
---

# Playwright Instructions

## Stability

- Prefer role-based selectors (`getByRole`) when available.
- Avoid fixed sleeps.
- Use explicit waits for navigation and network idle only when needed.

## Structure

- Keep tests independent.
- Reset state between tests.

## Debugging

- On flaky tests, add logging and screenshots/video only where helpful.
