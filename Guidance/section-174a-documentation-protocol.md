# Section 174A Documentation Protocol

## Effective Date
[DATE]

## Purpose

Ensure that all development activity on [PROJECT NAME] is documented in a manner that substantiates qualified research expenditure under IRC Section 174A(d)(3) ("any amounts paid or incurred in connection with the development of software").

## The Risk

An auditor, underwriter, or IRS examiner may argue that:

1. The developer's time was "managerial" or "supervisory" rather than substantive technical work.
2. Claude (or another AI tool, billed at its subscription cost) was the "principal investigator" performing the actual development.
3. Therefore, the allowable deduction should be limited to the cost of the AI tool rather than the developer's time at their established billing rate.

This argument must be foreclosed by the documentary record.

## What the Record Must Show

1. **The developer directs every material decision.** Architecture, algorithm selection, UI design, data model design, API design, error handling strategy, and deployment decisions are all made by the developer. Claude proposes; the developer disposes.

2. **The developer's instructions are substantive and technical.** The transcripts must show that the developer's prompts contain technical specificity — not "build me an app" but specific, detailed technical instructions that demonstrate domain expertise and engineering judgment.

3. **Claude is a tool, not a collaborator.** Claude is used the way a lawyer uses Westlaw or a programmer uses Stack Overflow. The developer asks specific questions, evaluates the responses, accepts or rejects them, and integrates the results into a design that the developer conceived.

4. **The developer exercises independent judgment at every step.** Rejected suggestions, course corrections, architectural vetoes, and design overrides must be visible in the transcript.

## How to Document

- **Transcripts:** Full dialogue, timestamped. Every prompt and response. Developer actions annotated to highlight technical decision-making.
- **Logs:** Claude's internal reasoning per prompt. Tool calls, file reads, search queries, decision trees.
- **Timesheets:** Developer time entries per session. Start time, end time, hours, description of work performed.
- **Guidance:** Standing instructions (like this document). Changes tracked with dates.
- **Internal:** Supporting materials — e.g., the developer's hourly rate documentation, engagement letters, time records, billing practices.

## Recording Controls

The developer may stop and start recording at any time:

- `---[STOP_RECORDING_[YYYY-MM-DD_HH:MM:SS]]---` — Pause transcript logging.
- `---[START_RECORDING_[YYYY-MM-DD_HH:MM:SS]]---` — Resume transcript logging.

Off-the-record segments are not logged. The existence of a gap (stop/start timestamps) is recorded; the content is not.

## Changes to This Guidance

| Date | Change | Reason |
|------|--------|--------|
| [DATE] | Initial version | Establish documentation protocol for 174A substantiation |
