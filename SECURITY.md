# Security Policy

## Reporting a Vulnerability

Please do not disclose security vulnerabilities through public issues, pull requests, discussions, or other public channels.

Report suspected vulnerabilities privately to the maintainers of the affected project.

Please include, when safe to provide:

- A clear description of the vulnerability.
- The affected repository, component, or service.
- Reproduction steps or a minimal proof of concept.
- The potential security impact.
- Relevant logs, screenshots, or technical details.
- Suggested remediation, if known.

Never include passwords, API keys, access tokens, private keys, credentials, or unnecessary personal data in a security report.

## Response Process

Maintainers will assess the report, attempt reproduction where practical, determine the affected scope, coordinate remediation, add regression coverage where appropriate, and coordinate disclosure after a fix when appropriate.

## Security Principles

- Never commit secrets or credentials to Git.
- Use least-privilege access for users, services, tokens, and automation.
- Validate untrusted input at trust boundaries.
- Protect customer and production data.
- Keep dependencies and runtime components maintained.
- Prefer secure defaults.
- Log security-relevant events without exposing secrets.
- Add regression tests for security fixes where practical.
- Fail safely when security-critical dependencies or checks are unavailable.

## Scope

This policy applies to repositories and services maintained by the Sssssssddddd organization. Individual projects may define additional security requirements; follow those requirements together with this policy.
