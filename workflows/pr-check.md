# Pull Request Check Workflow

Use this workflow after opening a PR and during follow-up sessions.

## Status Fields

Track:

- Open, merged, closed, or draft status.
- Mergeability.
- Required reviews.
- CI status.
- Maintainer comments.
- Requested changes.
- Whether the branch needs updates.

## Safe Automatic Replies

The agent may reply automatically when:

- A maintainer says thanks.
- A maintainer asks for a small docs/test adjustment.
- CI failure is clearly unrelated or awaiting maintainer approval.
- A duplicate is found and the correct action is to acknowledge and close gracefully.

## Pause Conditions

Ask the human before:

- Changing design direction.
- Expanding scope.
- Force pushing or rewriting history.
- Taking on L4/L5 work.
- Agreeing to ongoing maintenance.

## Closeout

When a PR is merged:

- Thank the maintainer if they left a direct review or comment.
- Update `data/contributions.yaml`.
- Upgrade repository trust only if the response was concrete and positive.

When a PR is closed:

- Record the reason.
- Extract the lesson.
- Avoid repeating the same mistake.
