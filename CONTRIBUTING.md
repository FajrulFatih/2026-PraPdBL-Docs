# Contributing Guide

## Purpose
This guide explains how to contribute to PraPdBL documentation and aligns with the Git workflow in [git-workflow.md](git-workflow.md).

## Getting Started
1. Pull the latest `develop`.
2. Create a task branch using the correct prefix (`feature/`, `chore/`, `docs/`).
3. Keep changes focused on a single task.

## Branch Naming Rules
- Use lowercase and hyphens for readability.
- Match the task scope when possible.
- Examples: `feature/booking-validation`, `chore/ci-setup`, `docs/git-workflow`.

## Commit Rules
Follow Conventional Commits as defined in [git-workflow.md](git-workflow.md).

## Pull Request Requirements
- PRs must target `develop` unless it is a release PR to `main`.
- Include a short description of changes and screenshots if UI changes exist.
- Link related issues or tasks.

## Code Review Expectations
- At least one reviewer approval is required.
- Resolve all review comments before merging.
- Keep PRs small and focused to reduce merge conflicts.
