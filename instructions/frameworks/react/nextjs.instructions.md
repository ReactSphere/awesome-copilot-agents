---
description: Instructions for Next.js (React) applications.
applyTo: "**/*.{ts,tsx,js,jsx}"
---

# Next.js Instructions

## Routing

- Prefer file-based routing conventions.
- Keep server-only code out of client components.

## Data Fetching

- Prefer server components for data loading when possible.
- Use caching intentionally; call out revalidation settings.

## UI

- Keep components small and accessible.
- Avoid layout shift; size images and reserve space.

## Performance

- Avoid shipping large libraries to the client unless necessary.
- Prefer dynamic import for heavy optional UI.
