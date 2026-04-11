---
description: Instructions for Cobra-based CLIs with Charmbracelet UI.
applyTo: "**/*.go"
---

# Charmbracelet + Cobra CLI Instructions

## UX

- Commands should have clear `Use`, `Short`, and `Long` descriptions.
- Provide examples in help text for non-trivial flags.

## Flags

- Prefer explicit flags over positional arguments.
- Use consistent names across commands.

## Errors

- Return actionable errors (what failed, how to fix).
- Use non-zero exit codes on failure.

## TUI

- Keep render loops deterministic.
- Avoid blocking IO in the UI update loop.
