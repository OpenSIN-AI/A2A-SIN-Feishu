# Contributing to A2A-SIN-Feishu

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **Feishu** surface.

Put the change here when it affects:
- Feishu messaging routing, coordination, or automation workflows
- Feishu evidence, recovery, auth, or session-health handling
- Feishu contracts tied to enterprise chat communication

Do **not** put the change here when it belongs to:
- unrelated messaging or platform integration logic
- organization SSOT docs or architecture ownership
- unrelated OpenSIN services

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within Feishu ownership?
- Does another repo already own the adjacent platform behavior?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## Boundary Rules

Before adding a feature or top-level claim, answer:

1. Is this specifically Feishu integration work?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `A2A-SIN-Feishu` if:
- it improves Feishu integration
- it improves this repo's A2A agent behavior

### Do NOT put it in `A2A-SIN-Feishu` if:
- it claims broader workplace messaging, product, ops, or docs ownership

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
