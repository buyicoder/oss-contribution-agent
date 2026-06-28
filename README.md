# OSS Contribution Agent

A structured open-source contribution agent for finding, tracking, and executing low-risk contribution opportunities in AI, MCP, agent, and developer-tooling repositories.

The goal is not to maximize pull request count. The goal is to build maintainer trust in valuable repositories through a steady ladder of issues, small PRs, follow-up comments, and eventually deeper contributions.

## Repository Structure

- `docs/` contains the strategy, contribution levels, target-repository criteria, and maintainer etiquette.
- `data/` stores machine-readable tracking files for target repositories, contributions, and issue actions.
- `workflows/` documents repeatable operating loops such as daily hunting, PR checks, and maintainer replies.
- `scripts/` is reserved for future automation once the manual workflow is stable.

## Operating Principles

1. Choose valuable repositories before choosing easy issues.
2. Prefer low-risk L1-L3 actions until maintainer trust is established.
3. Use issues and analysis comments when a PR would be premature.
4. Check for duplicate PRs, assignments, and existing fixes before acting.
5. Escalate to L4 only after evidence of maintainer responsiveness.
6. Notify the human before any L5 architecture or long-term ownership work.

## Current Status

This repository is the control center for a long-term open-source contribution campaign. It starts with documents and tracking templates; automation should be added only when the workflow is clear enough to encode safely.
