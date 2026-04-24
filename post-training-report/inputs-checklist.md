# Inputs Checklist — Post-Training Report

Have these ready before you run the skill. The agent works with partial data, but more inputs = sharper report.

## Required

### 1. Survey results
Any of:
- HRDC Output Assessment (OA) Form export (Excel/CSV)
- Google Forms results (export to CSV)
- Microsoft Forms results (export to Excel)
- Lark Base export (CSV)
- Typeform / Jotform export (CSV)

The skill auto-detects rating scales and section structure. Column names can be in any language.

### 2. Training metadata
A short text file (or just paste in chat) with:
- Client / company name
- Training title
- Cohort number or label (eg "Cohort 3" or "Batch A")
- Dates (start + end)
- Venue (or "virtual" or "hybrid")
- Duration (eg "2 days, in-person")
- Trainer name + credentials
- Trainer organisation (if applicable)

## Highly recommended

### 3. Collaboration board export
This is what turns the report from "ratings summary" into "evidence of skill transfer". Any of:
- Padlet board → export as PDF or image collage
- Miro board → export as PDF
- Mural → PDF export
- Notion page → PDF export
- A zip of screenshots

The skill extracts:
- Artifacts each participant produced (with titles, descriptions, tools used)
- Participant quotes from reflection sections
- Peer engagement (comments, replies, likes)

### 4. Participant list
CSV with at minimum: `name, department` (or `name, function`). Often already in the survey — if so, skip.

## Optional but nice

### 5. Facilitator notes
A markdown or text file with:
- Key moments that landed (icebreaker, specific exercise, Day 2 recap)
- Surprising questions from participants
- Observations about peer dynamics

This lets the agent write a stronger "Engagement" section instead of generic language.

### 6. Photos
A folder of session photos (optional). The skill can reference them in the report footer or embed thumbnails.

## What the skill does NOT need

- Budget / pricing info
- Internal slack threads
- Trainer's private notes on specific participants (keep those off this)
- Anything under NDA

## Next step

Upload your files to Manus, paste the contents of `SKILL.md`, and type: *"Run the skill on the files I uploaded."*
