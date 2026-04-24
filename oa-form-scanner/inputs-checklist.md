# Inputs Checklist: OA Form Scanner

## Required

### 1. Completed OA forms (photos or scans)

One image or PDF page per completed form. Submit as:

- A folder of JPG / PNG / HEIC files
- A zip file of images
- A multi-page PDF (one form per page)
- Scanned TIFF batch

Capture tips for best accuracy:

- Lay forms flat on a plain surface. Avoid shadows across the form.
- Capture the full form including the header (name, department) and the open-comment box.
- Good light beats high resolution. Phone camera in daylight is fine.
- If participants filled the form in multiple colours (ratings in blue, comments in black), that is fine.
- Do not crop out the form edges. The agent uses layout to detect sections.

## Optional

### 2. Form template specification

If the form is not standard HRDC OA V2.0, you can upload a blank copy of the form template. The skill will detect the variant automatically, but an explicit template reduces edge-case extraction errors.

### 3. Output format preference

Tell the skill at the start whether you want:

- CSV (default, universal, opens in Excel and Sheets)
- Excel .xlsx (native formatting, sheet tabs for summary)
- Both

### 4. Participant roster

If you have a pre-existing participant list with names and departments, uploading it improves name-matching accuracy. The skill will cross-reference handwritten names against the roster and flag mismatches.

## What the skill does not need

- The paper forms themselves. Photos are enough.
- Access to your HRDC portal or claim system.
- Pre-processed or corrected images.
- Any Personally Identifiable Information beyond what participants wrote on the form themselves.

## Privacy note

OA forms contain participant names and handwritten feedback. Treat the image files as confidential training records. Delete them from your Manus session after the CSV is extracted and verified if your organisation requires it.

## Next step

Upload your files to Manus, paste the contents of `SKILL.md`, and type:

> *"Run the skill on the files I uploaded. Output as CSV."*

(or `Excel` or `Both`.)
