# GitHub Copilot Instructions

## Project Overview

FlyRank is a capstone project for the AI-assisted development track.

The project should be developed incrementally, with a focus on clean, maintainable code and effective use of AI-assisted development.

## Tech Stack

- Node.js (LTS)
- JavaScript / TypeScript
- Git
- GitHub
- GitHub Copilot

Use the technologies already established in the project before introducing new frameworks, libraries, or dependencies.

## Code Conventions

- Write clean, readable, and maintainable code.
- Use clear and descriptive names for variables, functions, components, and files.
- Keep functions and components small and focused.
- Prefer simple solutions over unnecessary abstractions.
- Follow the existing project structure and coding patterns.
- Avoid unnecessary dependencies.
- Reuse existing utilities and components where appropriate.
- Handle errors explicitly where necessary.
- Do not hardcode secrets, API keys, passwords, or other sensitive information.
- Use environment variables for configuration and secrets.

## Git Conventions

Use Conventional Commits for all Git commit messages.

Use the following format:

`type: description`

Common types include:

- `feat:` for new functionality
- `fix:` for bug fixes
- `docs:` for documentation changes
- `refactor:` for code restructuring without changing behavior
- `test:` for tests
- `chore:` for maintenance tasks
- `style:` for formatting or styling changes

Examples:

- `feat: add user authentication`
- `fix: handle invalid API response`
- `docs: update README`
- `test: add ranking tests`
- `chore: update dependencies`

## AI-Assisted Development

GitHub Copilot is used as an AI development assistant for this project.

When generating or modifying code:

- Review AI-generated code before accepting it.
- Do not blindly accept generated code.
- Make sure generated code follows the project's existing conventions.
- Prefer straightforward implementations that are easy to understand and maintain.
- Do not introduce dependencies unless they are necessary.
- Do not generate or commit secrets or credentials.
- When making significant architectural changes, explain the reasoning before implementation.
- Preserve existing functionality when modifying code unless a change is explicitly requested.

## Project Structure

Follow the existing project structure and conventions.

When adding new files or directories, place them according to their purpose and the patterns already established in the project.

## Quality

Before considering a change complete:

- Check that the code is consistent with the project conventions.
- Review the changes for unintended behavior.
- Run relevant tests or checks when available.
- Ensure no secrets or unnecessary files are committed.
- Use a clear Conventional Commit message.
