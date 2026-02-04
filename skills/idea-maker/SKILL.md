---
name: idea-maker
description: Create, expand, and update idea entries in the ideas library, producing IDEA.md and optional supporting docs. Use when creating a new idea entry, expanding or editing an existing idea, or turning a rough concept into a clear execution guide.
---

# Idea Maker

Use this skill to create or update idea entries in the `ideas/<idea-name>/` library. The output should be a structured `IDEA.md` and, when helpful, supporting docs in `references/`, `assets/`, or `files/`.

## Output rules

- Create or update one idea folder under `ideas/<idea-name>/`
- Always create or update `IDEA.md`
- Only add supporting files if they add clarity
- Keep content concise and actionable

## Workflow

1. Clarify the idea (problem, audience, scope, constraints).
2. Decide the minimum required artifacts.
3. Generate or update `IDEA.md` using the schema in `references/idea_schema.md`.
4. Add optional supporting docs from `assets/templates/` if needed.
5. Summarize what was created or changed.

## Optional artifacts

- `references/prd.md` if the scope is non-trivial (use `assets/templates/prd.md`)
- `references/risks.md` for open questions and dependencies (use `assets/templates/risks.md`)
- `references/metrics.md` for success criteria (use `assets/templates/metrics.md`)
- `assets/` for images, mockups, or diagrams
- `files/` for datasets or miscellaneous files

## Notes

- If the user gives only a short idea, keep `IDEA.md` short and defer heavy documentation.
- Prefer a clear, minimal idea over a bloated plan.
