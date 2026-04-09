---
description: JavaScript standards for Node.js and browsers.
applyTo: "**/*.{js,mjs,cjs}"
---

# JavaScript Instructions

## Style

- Prefer modern syntax (ES2020+).
- Use `const` by default; use `let` only when reassigned.
- Avoid implicit type coercion in critical logic.

## Error Handling

- Prefer explicit error messages.
- Preserve original error causes when rethrowing.

## Testing

- Add tests when behavior changes.
- Cover edge cases and error paths.
