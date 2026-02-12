# CLAUDE.md

This file provides guidance for AI assistants (including Claude Code) working in this repository.

## Repository Overview

- **Repository**: `Zaeem-ch/code`
- **Status**: New project — no source code, build system, or CI/CD pipelines have been set up yet.
- **Remote**: Hosted on a Git server at the configured origin.

## Project Structure

The repository is currently empty. As the project grows, update this section to reflect the directory layout:

```
/
├── CLAUDE.md          # AI assistant guidance (this file)
└── (no other files yet)
```

## Development Setup

No build tools, package managers, or dependencies are configured yet. Once the project is initialized, document:

- **Language(s)**: (e.g., TypeScript, Python, Go)
- **Package manager**: (e.g., npm, pip, cargo)
- **Install command**: (e.g., `npm install`)
- **Build command**: (e.g., `npm run build`)
- **Dev server**: (e.g., `npm run dev`)

## Testing

No test framework is configured yet. Once set up, document:

- **Test command**: (e.g., `npm test`)
- **Test directory**: (e.g., `tests/`, `__tests__/`)
- **Coverage command**: (e.g., `npm run coverage`)

## Linting and Formatting

No linters or formatters are configured yet. Once set up, document:

- **Lint command**: (e.g., `npm run lint`)
- **Format command**: (e.g., `npm run format`)
- **Config files**: (e.g., `.eslintrc`, `.prettierrc`)

## Code Conventions

When contributing to this project, follow these principles:

- **Keep changes minimal** — only modify what is necessary for the task at hand.
- **Avoid over-engineering** — don't add abstractions, utilities, or feature flags unless they are clearly needed now.
- **Don't add unused code** — no speculative helpers, no dead code, no backwards-compatibility shims for things that don't exist yet.
- **Write clear commit messages** — use imperative mood, explain the "why" not just the "what".
- **Security first** — never commit secrets, credentials, or `.env` files. Validate user input at system boundaries.

## Git Workflow

- **Default branch**: To be established with the first commit.
- **Branch naming**: Feature branches should use descriptive names (e.g., `feature/add-auth`, `fix/login-bug`).
- **Commits**: Keep commits atomic and focused on a single change.
- **Pull requests**: Include a summary and test plan.

## Key Files to Update

When the project structure is established, update this `CLAUDE.md` with:

1. Actual directory layout and module descriptions
2. Build, test, lint, and format commands
3. Environment variable requirements
4. Deployment procedures
5. Architecture decisions and patterns used
6. Key dependencies and their purposes
