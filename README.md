# Involvex Community Health Files

Default community health files for all repositories in the `involvex` organization.

## Purpose

This repository contains the **default** community health files that automatically
apply to every repository under the `involvex` GitHub organization. Individual
repositories can override any of these files with their own versions.

## Files

| File | Purpose |
|------|---------|
| [`FUNDING.yml`](./.github/FUNDING.yml) | Sponsor and funding links shown on GitHub Sponsors |
| [`CODE_OF_CONDUCT.md`](./.github/CODE_OF_CONDUCT.md) | Code of Conduct (Contributor Covenant v2.1) |
| [`CONTRIBUTING.md`](./.github/CONTRIBUTING.md) | Contribution guidelines and workflow |
| [`SECURITY.md`](./.github/SECURITY.md) | Security policy and vulnerability reporting |
| [`SUPPORT.md`](./.github/SUPPORT.md) | Support channels and guidelines |
| [`CODEOWNERS`](./.github/CODEOWNERS) | Default code review assignments |
| [`PULL_REQUEST_TEMPLATE.md`](./.github/PULL_REQUEST_TEMPLATE.md) | Pull request template |
| [`ISSUE_TEMPLATE/config.yml`](./.github/ISSUE_TEMPLATE/config.yml) | Issue template configuration & contact links |
| [`ISSUE_TEMPLATE/bug_report.yml`](./.github/ISSUE_TEMPLATE/bug_report.yml) | Bug report form |
| [`ISSUE_TEMPLATE/feature_request.yml`](./.github/ISSUE_TEMPLATE/feature_request.yml) | Feature request form |

## How It Works

When a repository in the `involvex` org does not have its own version of one of
these files, GitHub automatically uses the file from this repository.

For example:
- A repository without a `CODE_OF_CONDUCT.md` will inherit the one from
  `.github/CODE_OF_CONDUCT.md`.
- A repository without a `SUPPORT.md` will inherit from
  `.github/SUPPORT.md`.

## Customizing Per Repository

If a repository needs different behavior, simply add the file to that
repository's `.github/` directory. The local version will override the default.

## Contact

- **Email**: involvex@proton.me
- **GitHub**: [@involvex](https://github.com/involvex)
