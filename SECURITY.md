# Security Policy

## Supported Versions

This is a GitHub profile repository. While it primarily contains documentation and configuration, we take security seriously.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability in this repository, please report it responsibly:

1. **DO NOT** open a public issue
2. Use GitHub's [Security Advisories](https://github.com/warrenet/warrenet/security/advisories/new) to report privately
3. Or email security concerns to: contact@warrenet.dev

### What to include in your report:

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

### What to expect:

- **Initial Response**: Within 48 hours
- **Status Update**: Within 1 week
- **Fix Timeline**: Depends on severity, typically within 2 weeks for high severity issues

## Security Best Practices

This repository follows these security practices:

- ✅ All secrets are stored in GitHub Secrets, never in code
- ✅ GitHub Actions workflows use pinned versions
- ✅ Dependabot monitors for vulnerable dependencies
- ✅ Regular security audits of workflows and integrations
- ✅ Principle of least privilege for workflow permissions

## Scope

Security considerations for this repository include:

- GitHub Actions workflows and their permissions
- Third-party integrations and APIs
- Exposure of sensitive information in README or workflows
- Malicious content injection through automated updates

Thank you for helping keep this project secure! 🔐
