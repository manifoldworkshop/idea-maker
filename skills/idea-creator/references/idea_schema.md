# IDEA.md schema

## Frontmatter (optional)

```
---
name: <idea name>
status: draft | exploring | validated | building | shipped
owner: <name or team>
tags: ["tag1", "tag2"]
complexity: low | medium | high
impact: low | medium | high
---
```

## Body sections (required unless marked optional)

- Summary (required): 2-6 sentences describing the idea.
- Problem (required): what user or business pain this solves.
- Target Users (required): who benefits and why.
- Solution (required): what the product does at a high level.
- Differentiation (required): why it is meaningfully different.
- Execution Plan (required): high-level steps or phases.
- Risks & Unknowns (required): open questions and dependencies.
- Success Metrics (optional): how to measure success.
- References (optional): links to supporting docs in `references/`.

## Style

- Use clear headings and short paragraphs.
- Prefer concrete outcomes over vague ambition.
- Avoid long lists unless necessary.
