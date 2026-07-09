# Security Policy

## Reporting a vulnerability

If you discover a security issue, please report it directly and privately.

Before disclosure, please include:

- A short description of the issue
- Steps to reproduce (if applicable)
- Version/build you tested on
- Potential impact

Please avoid posting sensitive security details in public issues until we can review it.

## Scope

Codex Meter reads only local session logs in:

- `~/.codex/sessions`
- `~/.codex/archived_sessions`

It does not collect or upload prompt content, replies, or auth credentials.
