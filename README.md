# NIDC Workshop 2025: Code & Conundrums: From Spec to Puzzle, an AI-Assisted Workshop.

Sample prompts for the workshop to develop a modern, web-based Logic Grid Puzzle application developed during the NIDC Workshop 2025. This project aims to transform classic logic grid puzzles into an interactive digital experience where users can deduce relationships between multiple categories from given clues.

## Project Overview

This repository contains the prompts to help develop a Logic Grid Puzzle application with a focus on:

- Test-driven development
- High code quality standards
- Strict development practices
- Modular and maintainable architecture

## Core Features

- Interactive web-based interface for creating and importing puzzles
- Visual logic grid for marking cells as confirmed, eliminated, or unknown
- Modular logic/constraint engine for puzzle validation and state management
- Local file system persistence for puzzles and user state
- Automatic propagation of symmetric changes

## Project Structure

```
docs/
├── constitution-prompt.md          - Development constitution guidelines
├── plan-prompt.md                  - Architecture and implementation plan
└── specify-prompt.md               - Project specifications
.github/
└── prompts
    └── review-standards.prompt.md  - Code review criteria
```

## Development Standards

This project follows strict development principles including:

- Test-First Development (Red-Green-Refactor cycle)
- Comprehensive code review process
- Quality gates and automated checks
- Clear branching and merge strategies
- Focus on simplicity and maintainability

## Local Development

The MVP is designed to run entirely locally on a developer's machine with:

- No external databases required
- No cloud services dependencies
- No containers needed
- Simple file-system based persistence

## Contributing

Please review the following documents before contributing:

- `docs/constitution-prompt.md` for project principles
- `docs/specify-prompt.md` for project specifications
- `.github/prompts/review-standards.prompt.md` for code review criteria

## Project Status

This project is currently in development as part of the NIDC Workshop 2025. The initial focus is on delivering a working MVP that demonstrates core puzzle-solving capabilities while maintaining high development standards.
