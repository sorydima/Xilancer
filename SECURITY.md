# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability, please report it privately.

- Email: `security@yourdomain.tld`
- Include steps to reproduce and any proof-of-concept details.

We aim to acknowledge reports within 72 hours and will work with you on a
reasonable timeline for resolution and disclosure.

## Supported Versions

Only the latest `main` branch is actively supported.

## Hardening Guidance

- Keep dependencies up to date.
- Avoid committing secrets; use environment variables or secure vaults.
- Limit access to CI secrets and protect the default branch.
- Review third-party packages before adoption.
- Rotate credentials if exposure is suspected.
