---
name: hermes-skill-test-driven-development
description: Implement changes through RED-GREEN-REFACTOR with focused regression coverage. Use when a user asks for this workflow or a closely related task.
---

# Test-Driven Development

Use a disciplined RED-GREEN-REFACTOR loop for behavior changes.

## Workflow

1. Translate the requirement into observable behavior and edge cases.
2. Write the smallest test that fails for the right reason.
3. Implement the smallest production change that makes it pass.
4. Run the focused test and the relevant suite.
5. Refactor for clarity without changing behavior; keep the tests green.
6. Add regression coverage for discovered failure modes.
7. Report commands, results, and any tests not run.

Prefer behavior-level tests over brittle implementation coupling. Do not weaken a test just to obtain a green result.
