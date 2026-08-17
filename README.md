# classync
Automates timetable-to-calendar sync and coursework template generation from your OneDrive syllabus folder.


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
