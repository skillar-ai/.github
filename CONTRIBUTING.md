# Contributing to Skillar.ai

Guidelines for contributing to repositories across the Skillar.ai organization.

## Branching Strategy
Direct pushes to `main` and release branches are disabled via branch protection rules.

Create branches from `main` using standard prefixes:
- `feat/short-description`
- `fix/short-description`
- `docs/short-description`
- `refactor/short-description`
- `chore/short-description`

## Pull Request Workflow
1. Run local tests and linting before submitting a pull request.
2. Link the PR to an issue where applicable (e.g. `Fixes #123` or `Refs #123`).
3. Every PR requires at least one approved review before merge.
4. Use **Squash and merge** with a clean commit summary adhering to Conventional Commits (e.g. `feat: ...`, `fix: ...`).
5. Delete the branch after merge.

## Code Standards
- Adhere to the formatting and linting rules defined in the target repository.
- Ensure all new public interfaces, API contracts, and models are documented.
- If changes introduce new environment variables, update the corresponding `.env.example` file.
