# [PROJECT NAME] — Claude Project Instructions

## Project

[Describe your project. What does it do? What problem does it solve?]

## Developer

- **Name:** [Your full legal name]
- **Entity:** [Your company or sole proprietorship name]
- **Role:** Principal Investigator, Architect, Developer
- **Billing rate:** $[rate]/hour
- **Engagement:** [Description of how this rate is established — e.g., "consistent with rates billed to clients for comparable technical and legal work over [N] years"]

## Architecture

- **Language:** [e.g., Swift, Python, TypeScript]
- **Frameworks:** [e.g., SwiftUI, React, Django]
- **Key design decisions:** [List 3-5 architectural decisions YOU made and why]

## Development Practices

[Your standing instructions for Claude. These demonstrate that you direct the work.]

## Recording & Documentation

All conversations are documented in `Transcripts/` and `Logs/`.

- **Transcripts** capture the full dialogue between the developer and Claude, with timestamps.
- **Logs** capture Claude's internal reasoning, tool calls, and decision process per prompt.
- **Timesheets** record the developer's time entries per session.
- **Tests** is for R&D artifacts, experiments, and validation work.
- **Guidance** contains standing instructions that re-anchor conversations and track changes to those instructions.
- **Internal** is for materials that do not fit the above categories.

### Recording Controls

Transcripts support stop/start markers:
- `---[STOP_RECORDING_[YYYY-MM-DD_HH:MM:SS]]---` — Pause transcript logging.
- `---[START_RECORDING_[YYYY-MM-DD_HH:MM:SS]]---` — Resume transcript logging.

Off-the-record segments are not logged. The existence of a gap is recorded; the content is not.

## Section 174A Context

This project constitutes qualified research expenditure under IRC Section 174A (as enacted by the One Big Beautiful Bill Act, July 2025). The developer identified above is the principal investigator and architect. Their role is substantive, technical, and non-managerial. They direct all design decisions, write code, define architecture, specify algorithms, debug, test, and make every material technical judgment.

Claude is a tool used by the developer, analogous to an IDE, compiler, or reference manual. Claude does not independently direct research. Claude executes instructions given by the developer. The developer's contribution is not supervisory — it is the research itself.

See `Guidance/` and `Internal/` for supporting materials.
