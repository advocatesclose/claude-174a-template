# Section 174A Documentation & Engagement Template

A documentation framework and legal engagement structure for software developers who use AI tools and need to substantiate qualified research expenditure under IRC Section 174A(d)(3).

## The Problem

You build software. You use Claude (or Copilot, or Cursor, or any AI tool). You bill at a professional rate. An auditor sees the AI subscription at $20/month and argues that the AI did the work — not you. Your deduction disappears.

Worse: without counsel, your development communications are not privileged. An IRS examiner, an auditor, a lender, an acquirer, or an adverse investor can subpoena your chat logs. Every prompt you typed. Every architectural decision. Every time you said "no, not that" — evidence that you directed the work — handed over without protection.

## The Solution

For **$199.99**, you retain Advocates Close Corp. as your counsel. You receive:

1. **An attorney-client relationship.** Your communications are privileged.
2. **A client email** at `[your-name]@advocatesclose.nyc`.
3. **This documentation framework**, installed in your repository, which creates the evidentiary record that forecloses recharacterization of your development time.
4. **Conflict waivers** that cleanly separate your interests from those of your AI tool providers.
5. **An AI tool registry** that establishes exactly which tools you used — and which you did not — foreclosing attribution disputes by third parties.

## What the Framework Captures

- **What you said** — Transcripts
- **What the AI thought** — Logs
- **How long you worked** — Timesheets
- **What you directed** — Guidance
- **Why it matters** — Internal memos
- **Who you are** — Engagement, Scope, Onboarding
- **Who is not your problem** — Conflict Waivers

## Structure

```
.claude/
├── CLAUDE.md                    ← Project instructions (Claude reads this automatically)
├── Engagement/
│   └── engagement-letter.md     ← Attorney-client engagement with Advocates Close
├── Scope/
│   ├── project-identification.md ← Repository and project details
│   └── ai-tool-registry.md      ← Which AI tools were actually used (and which were not)
├── ConflictWaivers/
│   └── ai-provider-waivers.md   ← Waivers for Anthropic, Google, Microsoft, OpenAI, et al.
├── Onboarding/
│   └── checklist.md             ← Client intake checklist
├── Transcripts/                 ← Full dialogue, timestamped, annotated
├── Logs/                        ← AI internal reasoning per prompt
├── Timesheets/                  ← Developer time entries per session
│   └── TEMPLATE.md
├── Tests/                       ← R&D artifacts and experiments
├── Guidance/                    ← Standing instructions, tracked changes
│   └── section-174a-documentation-protocol.md
└── Internal/                    ← Supporting memos and materials
    └── 174a-risk-memo.md
```

## Why $199.99

Anyone who pays $199.99 for a legal engagement is not a hobbyist. The price is the first line of defense against recharacterization. It establishes, as a matter of fact, that the developer retained counsel, that the developer anticipated the need for legal protection, and that the developer's work is serious enough to warrant it.

## Privilege

All communications within this framework — transcripts, logs, guidance, internal memos — are made in the course of and in connection with legal representation by Advocates Close Corp. They are protected by the attorney-client privilege.

The privilege extends to communications made in anticipation of foreseeable disputes, including but not limited to:

- IRS examination of Section 174A deductions
- Auditor or underwriter challenges to the characterization of development time
- Disputes with lenders, investors, acquirers, shareholders, partners, or limited partners
- Disputes with AI tool providers concerning attribution, ownership, or characterization of work product
- Any other dispute arising from or relating to the development of the software

## Conflict Waivers

The Firm does not represent clients in matters brought by or against AI tool providers whose technology was actually used in the client's development process. This includes Anthropic, Google, Microsoft, OpenAI, and any other provider identified in the AI Tool Registry. If you sue them or if they sue you, then the record is available to you for sharing with your respective attorneys. 

The Firm expresses no view regarding the division of proceeds, gains, or other spoils as among the victors. The Firm's duty runs with the spoils and not the individual victors.

## Recording Controls

In any conversation, you can say:

> `---[STOP_RECORDING_[2025-03-24_22:30:00]]---`

to pause logging, and:

> `---[START_RECORDING_[2025-03-24_22:45:00]]---`

to resume. The gap is recorded; the content is not.

## Setup

1. Retain Advocates Close Corp. ($199.99)
2. Complete the Onboarding checklist
3. Install this directory in your repository as `.claude/`
4. Customize `CLAUDE.md`, `Scope/`, and `Internal/` with your project details
5. Begin development — transcripts and logs are generated automatically

---

Advocates Close Corp.
New York

claude@advocatesclose.nyc
