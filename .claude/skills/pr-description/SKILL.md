---
name: pr-description
description: Write a pull request description in our house format. Use when asked to write or draft a PR description.
---

# PR Description Skill

Write the pull request description with exactly these three sections, in this order:

1. **What changed** — one or two plain sentences describing the change.
2. **Why** — the reason for the change, or the issue it closes.
3. **How to test** — the exact steps a reviewer runs to check it (commands to run, pages to visit, inputs to try, expected results).

## Guidelines

- Base the content on the actual diff/commits for the PR, not assumptions — inspect the relevant `git diff` / `git log` before writing.
- Keep "What changed" to one or two sentences — no bullet list of every file touched.
- "Why" should give the motivation or link/reference the issue it closes (e.g. "Closes #123") when one exists.
- "How to test" must be concrete and runnable: exact commands, not vague instructions like "test it works."
- Use the three headers verbatim (`## What changed`, `## Why`, `## How to test`) and nothing else — no extra sections unless the user asks for one.
