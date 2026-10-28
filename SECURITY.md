# Security Policy

MediQPlus is designed for healthcare workflows, so security reports are taken seriously.

## Reporting a vulnerability

Please **do not** open a public issue. Use GitHub's private reporting instead:
**Security tab → "Report a vulnerability"** on this repository.

Include: what you found, steps to reproduce, affected version or commit, and potential impact. Do not include real patient data.

## What to expect

- Acknowledgement within 7 days
- A status update within 30 days
- Credit in the changelog if you want it, once a fix is released

## Supported versions

Only the latest release and the `main` branch receive security fixes while the project is in early stage.

## Scope notes

- Never run MediQPlus with real patient data without your own security and compliance review.
- Do not commit secrets. Use environment variables and `.env` files that are git-ignored.
