---
description: Generate Git commit messages
argument-hint: [optional changes summary]
allowed-tools: Bash(git status:*), Bash(git diff:*)
---

Optional changes hint: $ARGUMENTS

- Generate high-resolution, technically-focused, precise, and concise Git commit messages in English based on the diff.
- Use imperative mood (e.g., 'Add feature' not 'Added feature').
- Prefer using the following descriptive types: Add, Update, Remove, Fix, Improve, Optimize.
- Do not include extraneous statements.
- Final optimize output to oneline message.
