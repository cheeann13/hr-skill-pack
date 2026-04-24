# Inputs Checklist: Post-Training Report

The skill produces a Kirkpatrick-aligned evaluation report. Each input below maps to a specific level of evaluation evidence. The agent works with partial data, but more inputs produce a stronger report.

## Required inputs

### 1. Survey results (Kirkpatrick Level 1: Reaction)

The weakest but most commonly collected form of training evidence. Required as a baseline.

Any of:
- HRDC Output Assessment (OA) form export (Excel / CSV)
- Google Forms results (CSV)
- Microsoft Forms results (Excel)
- Lark Base export (CSV)
- Typeform, Jotform, or similar (CSV)

The skill auto-detects rating scales (1-5, 1-7, 1-10, NPS) and section structure. Column names can be in any language.

### 2. Training metadata

A short text file, or paste directly into chat:

- Client / company name
- Training title
- Cohort number or label (e.g. "Cohort 3" or "Batch A")
- Dates (start and end)
- Venue (or "virtual" or "hybrid")
- Duration (e.g. "2 days, in-person")
- Trainer name and credentials
- Trainer organisation (if applicable)

## Highly recommended

### 3. Collaboration board export (Kirkpatrick Level 2: Learning)

The strongest evidence available in a post-training window. Artifacts produced during the programme demonstrate cognitive skill acquisition across Bloom's taxonomy (Apply, Analyze, Create), not just satisfaction.

Any of:
- Padlet board, exported as PDF or image collage
- Miro board, exported as PDF
- Mural, exported as PDF
- Notion page, exported as PDF
- A zip of screenshots

The skill extracts:
- Artifacts each participant produced (title, description, tool used, participant)
- Direct quotes from reflection sections (early Level 3 behaviour indicators)
- Peer engagement signals (comments, replies, likes) as evidence of social learning (Bandura's 70-20-10 layer)

### 4. Participant list

CSV with at minimum `name, department` or `name, function`. Often already embedded in the survey; if so, skip this input.

## Optional but strengthens the report

### 5. Facilitator notes

A markdown or text file with:
- Key moments that landed (icebreaker, specific exercise, Day 2 recap)
- Surprising questions from participants
- Observations about peer dynamics
- Self-efficacy shifts you noticed (Bandura: "I can do this now" moments)

This lets the agent write a stronger Engagement Analysis section grounded in your direct observation, rather than inferring from quotes alone.

### 6. Session photos

A folder of session photos. Optional. The skill can reference them in the footer or embed thumbnails if required for HRDC documentation.

## What the skill does not need

- Budget or pricing information
- Internal Slack threads
- Trainer's private notes on specific participants (keep those off any shared workflow)
- Anything under NDA
- Data the participants did not consent to have in an evaluation report

## Scope note

The skill produces Level 1 (Reaction) and Level 2 (Learning) evidence, plus early Level 3 (Behaviour) indicators where reflections are available. It does not produce Level 4 (Results: business impact), which requires a post-programme measurement window of 3 to 6 months and is outside the scope of an immediate post-training report.

## Next step

Upload your files to Manus, paste the contents of `SKILL.md`, and type:

> *"Run the skill on the files I uploaded."*
