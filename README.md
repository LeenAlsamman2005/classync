# Classync

Automates the tedious parts of managing university coursework. Classync parses your MMU timetable export and syncs it to Outlook (or Google Calendar) as recurring events, then watches a OneDrive folder for new syllabus/coursework uploads — automatically extracting assignment, lab, and tutorial deadlines and generating starter document templates for each one.

## Features

- **Timetable sync** — Parses a downloaded MMU timetable (PDF/Excel) and pushes recurring class events to Outlook Calendar via Microsoft Graph API
- **OneDrive folder watcher** — Detects new syllabus/coursework files dropped into a designated OneDrive folder
- **Deadline extraction** — Uses an LLM to read syllabus text and pull structured assignment/lab/tutorial deadlines
- **Template generation** — Auto-generates starter documents (assignment templates, lab report templates, tutorial guides) back into the OneDrive folder

## Status
🚧 Early development — building phase by phase (timetable sync first).

## Roadmap

- [ ] Phase 1: Timetable → Outlook Calendar sync
- [ ] Phase 2: OneDrive folder watcher (Graph API delta query)
- [ ] Phase 3: Syllabus parsing + deadline extraction (LLM-based)
- [ ] Phase 4: Auto-generated coursework templates
- [ ] Stretch: Google Calendar as a second sync target

## Tech Stack

- Python
- Microsoft Graph API (Outlook Calendar + OneDrive) via MSAL device code flow
- pdfplumber / openpyxl for timetable parsing
- python-docx for template generation

## Setup

_Coming soon — setup instructions will be added once Phase 1 is functional._

## License

MIT
