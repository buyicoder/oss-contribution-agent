# Daily Hunt Workflow

Use this workflow for each hunting session.

## 1. Refresh Existing Targets

- Check open PR statuses.
- Check maintainer comments and review requests.
- Check whether any issue comments received replies.
- Update `data/targets.yaml`, `data/contributions.yaml`, and `data/issues.yaml`.

## 2. Scan Main Targets First

For each Main Target:

- List open issues with `documentation`, `good first issue`, `help wanted`, `bug`, or equivalent labels.
- Prefer unassigned issues.
- Skip issues with active claims or existing PRs.
- Check whether `main` already resolves the issue.

## 3. Choose the Best Action

Prefer actions in this order:

1. L1/L2 PR when the fix is obvious and repository rules allow PRs.
2. L3 test or repro when validation is local and clear.
3. I2/I3 issue comment when the fix requires maintainer confirmation.
4. No action when the contribution would be noisy or duplicative.

## 4. Execute Carefully

- Keep PR scope narrow.
- Include summary and test plan.
- Star repositories that are real targets.
- Comment naturally after PR creation when useful.
- Record every action in `data/`.

## 5. End-of-Session Report

Summarize:

- Actions taken.
- Repositories skipped and why.
- Current blockers.
- Next best move for each Main Target.
