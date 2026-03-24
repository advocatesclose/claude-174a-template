# .claude — Section 174A Documentation Template

A drop-in documentation framework for software developers who use AI tools and need to substantiate qualified research expenditure under IRC Section 174A(d)(3).

## The Problem

You build software. You use Claude (or Copilot, or Cursor, or any AI tool). You bill at a professional rate. An auditor sees the AI subscription at $20/month and argues that the AI did the work — not you. Your deduction disappears.

## The Solution

This template creates a documentary record that forecloses that argument. It captures:

- **What you said** (Transcripts)
- **What the AI thought** (Logs)
- **How long you worked** (Timesheets)
- **What you directed** (Guidance)
- **Why it matters** (Internal memos)

The record shows — in every session, on every prompt — that you are the principal investigator and the AI is a tool you direct.

## Structure

```
.claude/
├── CLAUDE.md               ← Project instructions (Claude reads this automatically)
├── Transcripts/            ← Full dialogue, timestamped, annotated
├── Logs/                   ← AI internal reasoning per prompt
├── Timesheets/             ← Developer time entries per session
│   └── TEMPLATE.md         ← Timesheet template
├── Tests/                  ← R&D artifacts and experiments
├── Guidance/               ← Standing instructions, tracked changes
│   └── section-174a-documentation-protocol.md
└── Internal/               ← Supporting memos and materials
    └── 174a-risk-memo.md
```

## Setup

1. Copy this directory into your project root as `.claude/`
2. Fill in the bracketed fields in `CLAUDE.md` — your name, entity, rate, project description
3. Fill in the bracketed fields in `Internal/174a-risk-memo.md`
4. Update the date in `Guidance/section-174a-documentation-protocol.md`
5. Begin your next Claude Code session — it will read `CLAUDE.md` automatically

## How It Works

Claude Code reads `CLAUDE.md` at the start of every conversation. The instructions in this template direct Claude to:

- Maintain timestamped transcripts of all dialogue
- Log its internal reasoning, tool calls, and decisions per prompt
- Annotate the developer's contributions to highlight substantive technical direction
- Respect recording controls (stop/start) for off-the-record segments

## Recording Controls

In any conversation, you can say:

> `---[STOP_RECORDING_[2025-03-24_22:30:00]]---`

to pause logging, and:

> `---[START_RECORDING_[2025-03-24_22:45:00]]---`

to resume. The gap is recorded; the content is not.

## Legal

This template provides a documentation framework. It does not constitute legal advice. Consult qualified tax counsel regarding your specific Section 174A position.

---

Prepared by Advocates Close Corp., New York.
