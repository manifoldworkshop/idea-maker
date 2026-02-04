---
name: "Example Idea: Smart Meeting Notes"
status: draft
owner: idea-maker
last_updated: 2026-02-04
tags: ["productivity", "ai", "meetings"]
complexity: medium
impact: medium
---

# Summary
A lightweight tool that turns meeting recordings into concise, structured notes with decisions, action items, and owners. It integrates with Google Calendar and Slack, sending a recap within 10 minutes after a meeting ends. The goal is to reduce note-taking overhead and improve follow-through for small teams.

# Problem
Teams spend too much time taking notes and still miss key decisions and action items. Follow-through is inconsistent because context is scattered across recordings, chats, and calendars.

# Target Users
- Small teams (5-50 people) that run frequent internal meetings.
- Team leads who want reliable recap and accountability without manual work.

# Solution
Record meeting audio, transcribe, and summarize into a structured recap with decisions, action items, owners, and due dates. Deliver via Slack and email, and store in a searchable archive.

# Differentiation
Unlike generic transcription tools, this focuses on actionable outcomes and immediate delivery. It also auto-assigns owners based on speaker identity and past assignment patterns.

# Execution Plan
1. Prototype transcription + summary pipeline for a single meeting type.
2. Build Slack delivery and calendar integration.
3. Pilot with 3-5 teams to refine summary format and accuracy.
4. Add searchable archive and basic analytics.

# Risks & Unknowns
- Accuracy of action item extraction across varied meeting styles.
- Privacy concerns around storing recordings and notes.
- Integration friction with enterprise calendars and Slack workspaces.

# Success Metrics
- 60%+ of meetings generate a recap that users mark as “accurate.”
- 30% reduction in time spent on manual note-taking.
- 40% of action items updated within 48 hours.

# References
- `references/prd.md`
- `references/risks.md`
- `references/metrics.md`
