# Contributing to Involvex

Thank you for your interest in contributing to the Involvex community! This
document outlines the guidelines for contributing to projects under the
`involvex` organization.

## Table of Contents

- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Coding Standards](#coding-standards)
- [Pull Requests](#pull-requests)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Code of Conduct](#code-of-conduct)

## Getting Started

1. Fork the repository you wish to contribute to.
2. Clone your fork locally:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

3. Add the upstream remote to stay synced:

   ```bash
   git remote add upstream https://github.com/involvex/<repo-name>.git
   ```

4. Create a feature branch:

   ```bash
   git checkout -b feat/your-feature-name
   ```

## How to Contribute

You can contribute in several ways:

- **Report bugs** — Use the "Bug Report" issue template.
- **Request features** — Use the "Feature Request" issue template.
- **Improve documentation** — Any documentation fixes or improvements are welcome.
- **Fix bugs or implement features** — Submit a pull request.

Before starting any non-trivial work, please open an issue or start a
discussion so we can align on the approach and avoid duplicate effort.

## Development Setup

Clone the repository and install dependencies:

```bash
# Using Bun (recommended)
bun install

# Run tests
bun test

# Start dev server (if applicable)
bun dev
```

> Refer to the specific repository's `README.md` for project-specific setup
> instructions.

## Coding Standards

- Follow the existing code style in the repository.
- Ensure all tests pass before submitting a pull request.
- Keep pull requests focused — prefer small, single-purpose PRs.
- Add tests for any new functionality.
- Update documentation as needed.

## Pull Requests

1. Ensure your branch is up to date with `main` (or the target branch):

   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. Make your changes with clear, conventional commit messages:

   ```
   feat: add dark mode toggle
   fix: resolve crash on empty input
   docs: update API reference
   ```

3. Push to your fork and open a pull request.

4. Fill out the pull request template.

5. Be responsive during review — we'll aim to review promptly.

### Commit Message Format

We follow [Conventional Commits](https://www.conventionalcommits.org/):

| Type       | Purpose                                     |
| ---------- | ------------------------------------------- |
| `feat`     | A new feature                               |
| `fix`      | A bug fix                                   |
| `docs`     | Documentation changes                       |
| `style`    | Code style changes (formatting, whitespace) |
| `refactor` | Code refactoring                            |
| `test`     | Adding or fixing tests                      |
| `chore`    | Maintenance tasks, tooling, deps            |
| `perf`     | Performance improvements                    |
| `build`    | Build system or external dependency changes |
| `ci`       | CI configuration changes                    |

## Reporting Bugs

Use the **Bug Report** issue template. Please include:

- A clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Environment details (OS, Node version, package version)

## Suggesting Features

Use the **Feature Request** issue template. Please include:

- The problem you're trying to solve
- Your proposed solution
- Any alternatives you've considered

## Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to
abide by its terms. Please report unacceptable behavior to
**involvex@proton.me**.

---

Thank you for contributing!
