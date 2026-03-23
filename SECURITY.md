# Security Policy

## Supported Versions

This repository is a collection of Claude Code agent definition files (Markdown).
The latest revision on the default branch is the only actively maintained version.

## Reporting a Vulnerability

If you discover a security vulnerability in this repository — for example:

- An agent prompt that could be abused for prompt injection
- Instructions that could cause Claude to perform destructive or privacy-violating actions
- Sensitive data accidentally committed to the repository

**Please do _not_ open a public GitHub Issue.**

Instead, report the vulnerability privately by emailing the repository owner or using
[GitHub's private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability).

## Security Best Practices for Users

When installing these agents on your local machine, keep the following in mind:

1. **Review agent files before installing.** Each `.md` file is a plain-text prompt that
   Claude Code will use. Read them to understand what instructions they contain.
2. **Install only from a trusted source.** Clone directly from the official repository
   (`https://github.com/alfred0099/agents-claude-code`) rather than from forks or mirrors
   you have not audited.
3. **Never embed secrets in agent files.** Do not add API keys, passwords, or other
   credentials inside any agent definition file.
4. **Keep Claude Code up to date.** Security patches in the Claude Code client may affect
   how agent definitions are processed.
