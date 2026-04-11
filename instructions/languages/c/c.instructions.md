---
description: C standards for system utilities and libraries.
applyTo: "**/*.{c,h}"
---

# C Instructions

## Portability

- Prefer standard C (C11+) and POSIX where appropriate.
- Avoid compiler-specific extensions unless required.

## Memory Safety

- Initialize variables.
- Check allocation and IO return codes.
- Avoid unchecked `strcpy`, `sprintf`.

## Style

- Keep functions small.
- Prefer explicit error handling paths.

## Testing

- Add unit tests for parsing and boundary conditions when feasible.
