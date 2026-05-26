# CLAUDE.md

This file documents the repository for AI assistants working in this codebase.

## Repository Overview

**Repository:** `avsarba/test`
**Status:** Minimal sandbox/test repository

This is a bare-bones repository containing only a `README.md`. There is no application code, build system, or test suite at this time. Use this repo to experiment, prototype, or build out a new project.

## Repository Structure

```
test/
└── README.md   # Project title placeholder
```

## Git Workflow

- **Default branch:** `master`
- **Feature branches:** use descriptive names like `feature/<short-description>` or `fix/<short-description>`
- Commit early, commit often; keep commits focused on a single logical change
- Write commit messages in the imperative mood ("Add X", "Fix Y", "Remove Z")
- Push to `origin/<branch>` and open a pull request against `master` for review

## Development Conventions

Since no language or framework has been established yet, follow these defaults when adding new code:

- Choose the language/framework that best fits the task; document the choice in `README.md`
- Keep the root directory clean — source code goes in `src/` or a similarly named subdirectory
- Add a `.gitignore` appropriate to the language before committing generated or dependency files
- Write a `README.md` section describing how to install dependencies and run the project once code exists

## Working with Claude Code

- All significant changes should be on a feature branch, not directly on `master`
- After pushing a branch, do not open a pull request unless the user explicitly asks
- When the repository grows, update this file to reflect new structure, tooling, and conventions
