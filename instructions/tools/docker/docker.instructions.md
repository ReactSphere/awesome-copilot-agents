---
description: Docker and containerization conventions.
applyTo: "**/{Dockerfile,Dockerfile.*,*.dockerfile,docker-compose*.yml,docker-compose*.yaml}"
---

# Docker Instructions

## Images

- Prefer small base images.
- Pin versions for reproducibility.
- Use multi-stage builds for production.

## Security

- Do not bake secrets into images.
- Prefer non-root users for runtime.

## Caching

- Order layers to maximize build cache.
- Separate dependency install from app copy when possible.
