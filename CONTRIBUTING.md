# Contributing to MediQPlus

Thanks for helping. MediQPlus is maintained by one person today, so clear, small contributions get reviewed fastest.

## Ways to contribute

- **Code:** fix bugs, build roadmap items, add tests
- **Design and UX:** review screens, flag accessibility issues, propose flows
- **Docs:** improve setup steps, add diagrams, fix typos
- **Domain input:** if you work in or with clinics, tell us what your workflow actually looks like

## Workflow

1. Search existing issues. Open one before starting anything larger than a small fix.
2. Fork the repo and create a branch: `fix/short-description` or `feat/short-description`.
3. Keep each PR focused on one change.
4. Add or update tests and docs where relevant.
5. Open a pull request using the template. Link the issue it resolves.

## Commit messages

Use short, imperative messages, ideally Conventional Commits: `feat: add appointment queue view`, `fix: prevent duplicate patient IDs`, `docs: clarify setup`.

## Ground rules for a healthcare project

- **Never commit real patient data**, screenshots of real records, or credentials. Use synthetic data only.
- Changes touching authentication, access control, or data storage need a short note in the PR on security impact.
- UI changes should consider keyboard use, contrast (WCAG 2.2 AA), and empty / loading / error states.

## Review

Expect a first response within about a week. If a PR is stale for 30 days with no reply from the author, it may be closed (it can always be reopened).

## Conduct

By participating you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).
