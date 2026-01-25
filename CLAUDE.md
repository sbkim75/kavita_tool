# CLAUDE.md

> This file provides guidance for AI assistants (like Claude) working on this repository.

## Project Overview

This is a newly initialized repository. The project is currently in its nascent stage with minimal structure.

**Repository Status:** Empty/Initial Setup

## Current Structure

```
/home/user/test/
├── .git/           # Git version control
├── CLAUDE.md       # AI assistant guidance (this file)
└── README.md       # Project readme
```

## Development Guidelines

### General Conventions

1. **Code Quality**
   - Write clean, readable, and maintainable code
   - Follow language-specific best practices and idioms
   - Keep functions/methods focused and single-purpose
   - Use meaningful variable and function names

2. **Documentation**
   - Document public APIs and complex logic
   - Keep README.md updated with project information
   - Add inline comments only for non-obvious code

3. **Git Workflow**
   - Write clear, descriptive commit messages
   - Use conventional commit format when applicable: `type(scope): description`
   - Keep commits atomic and focused on a single change
   - Never commit secrets, credentials, or sensitive data

### File Organization

When adding new files, follow these conventions:
- Source code: `src/` directory
- Tests: `tests/` or `__tests__/` directory (or co-located with source)
- Documentation: `docs/` directory
- Configuration: Root directory for standard config files

### Security Best Practices

- Never hardcode secrets or API keys
- Use environment variables for sensitive configuration
- Validate and sanitize all user inputs
- Be cautious with dependencies - prefer well-maintained packages

## Commands

*No build/test commands configured yet. Update this section as the project develops.*

```bash
# Placeholder commands - update when project tooling is added
# npm install    # Install dependencies
# npm run build  # Build the project
# npm test       # Run tests
# npm run lint   # Run linter
```

## Tech Stack

*To be determined. Update this section when the technology stack is chosen.*

## Testing

*No testing framework configured yet. Update this section when tests are added.*

Testing guidelines to follow:
- Write tests for new features and bug fixes
- Maintain good test coverage
- Use descriptive test names that explain what is being tested
- Follow the Arrange-Act-Assert pattern

## Common Tasks

### Adding a New Feature
1. Create a feature branch from main
2. Implement the feature with tests
3. Ensure all tests pass
4. Create a pull request with clear description

### Fixing a Bug
1. Reproduce the bug and understand the root cause
2. Write a test that catches the bug
3. Fix the bug
4. Verify the test passes

## Notes for AI Assistants

- Always read and understand existing code before making modifications
- Prefer minimal, focused changes over large refactors
- Don't add unnecessary dependencies
- Ask clarifying questions when requirements are ambiguous
- Update this CLAUDE.md file as the project evolves

---

*Last updated: 2026-01-25*
