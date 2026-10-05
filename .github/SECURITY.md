# Security Policy

## Supported Versions

We release security patches for the following branches and versions:

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < Latest| :x:                |

> Refer to individual repositories for their version support policy.

## Reporting a Vulnerability

We take security vulnerabilities seriously. Please report them responsibly:

1. **Do not open a public issue** for security-related problems.
2. Email us at **involvex@proton.me** with a description of the issue.
3. You should receive a response within **48 hours**.
4. We will investigate, reproduce, and confirm the vulnerability before providing a full response.
5. We will work on a fix and coordinate disclosure (typically within 1–4 weeks, depending on complexity).
6. After the fix is released, we will credit you publicly (unless you prefer to remain anonymous).

### What to Include in Your Report

- A clear description of the vulnerability
- Steps to reproduce the issue
- The impact (e.g., data exposure, remote code execution, denial of service)
- Any suggested mitigations or fixes (optional but appreciated)
- Your contact information for follow-up

### Out of Scope

The following are **not** considered security vulnerabilities but may be reported as regular issues:

- Issues in third-party dependencies (report upstream)
- Missing security headers that do not introduce a direct exploit
- Debug information exposed in development mode (when not in production)
- Issues that require social engineering or physical access

## Security Best Practices for Users

- **Update regularly** — Always use the latest stable version.
- **Pin dependencies** — Use lockfile-based installs where possible.
- **Review changes** — Audit diffs before merging or deploying.
- **Report concerns** — If in doubt, reach out to `involvex@proton.me`.

## Bug Bounty

We do not currently operate a bug bounty program. All security reports are handled responsibly and acknowledged.

---

Thank you for helping keep Involvex and our community safe!
