---
name: add-or-update-command-doc
description: Workflow command scaffold for add-or-update-command-doc in everything-claude-code.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-or-update-command-doc

Use this workflow when working on **add-or-update-command-doc** in `everything-claude-code`.

## Goal

Adds or updates documentation for a command, typically in Markdown under a language or locale-specific docs directory.

## Common Files

- `docs/zh-CN/commands/*.md`
- `docs/tr/commands/*.md`
- `docs/pt-BR/commands/*.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Create or update a Markdown file for the command in the appropriate docs directory (e.g., docs/zh-CN/commands/ or docs/tr/commands/).
- Commit the new or changed file with a message referencing the command.
- Optionally update README or language count if adding a new language.

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.