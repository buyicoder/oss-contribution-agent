# Contribution Levels

## Pull Request Levels

### L1: Tiny Docs Fix

Typos, stale paths, broken links, outdated names, or small mismatches between docs and code.

Use for first contact or low-confidence repositories.

### L2: Docs or Example Expansion

How-to sections, quickstart clarifications, checked-in examples, MCP integration notes, Cursor or VS Code setup notes, and README improvements.

Use when the issue is clear and the repository is worth building trust with.

### L3: Tests and Repro Cases

Regression tests, minimal repros, flaky test fixes, CLI smoke tests, and behavior documentation backed by tests.

Use after basic trust or when behavior is easy to verify locally.

### L4: Small Product Behavior

Small CLI flags, environment variables, adapter targets, exporter fields, MCP integration behavior, or compatibility fixes with tests and docs.

Use only after maintainer response or prior accepted contributions.

### L5: Deep Contribution

Architecture, runtime behavior, security model, migrations, compatibility design, performance work, or core module changes.

The agent must notify the human before starting L5 work.

## Issue Levels

### I1: Docs or Example Bug

Report the exact mismatch, current behavior, expected behavior, and file locations.

### I2: Reproducible Bug

Include environment, versions, minimal repro, actual output, expected output, and logs.

### I3: Analysis plus Fix Path

Add likely cause, relevant files, suggested fix, test plan, and compatibility risks.

### I4: Roadmap Breakdown

Split a larger feature into docs, tests, API surface, implementation, migration, and compatibility steps.

### I5: RFC or Design Discussion

Use for L5 preparation. Include background, goals, non-goals, options, tradeoffs, migration plan, and test strategy.

## Automation Boundary

The agent may automatically perform L1-L3 and I1-I3 actions when risk is low and repository rules allow it.

The agent must ask before L4/L5 work, design disagreements, force pushes, history rewrites, private credentials, or long-term maintenance commitments.
