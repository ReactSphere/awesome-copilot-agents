---
description: Instructions for building Express REST APIs with TypeScript.
applyTo: "**/*.{ts,tsx}"
---

# Express API (TypeScript) Instructions

## API Design

- Use consistent error shapes (status, code, message, details).
- Validate inputs at the boundary (params, query, body).
- Prefer explicit HTTP status codes.

## Structure

- Keep routing thin; put business logic in services.
- Keep DB access behind repositories/adapters.
- Avoid global mutable state.

## TypeScript

- Avoid `any`.
- Use `zod`/`yup` style schemas if already present; otherwise use minimal runtime checks.

## Observability

- Log request id / correlation id when available.
- Do not log secrets or full request bodies for auth endpoints.

## Testing

- Add request-level tests for new endpoints.
- Cover auth/permission edge cases.
