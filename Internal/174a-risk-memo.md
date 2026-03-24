# Section 174A — Risk Assessment Memo

## Date
[DATE]

## Author
[DEVELOPER NAME]

## Statutory Basis

IRC Section 174A, enacted July 2025 by the One Big Beautiful Bill Act. Section 174A(d)(3) provides for deduction of "any amounts paid or incurred in connection with the development of software."

## The Concern

The developer bills at $[RATE]/hour. This project represents substantial qualified research expenditure at that rate. The risk is that an auditor, tax opinion counsel, or the IRS will attempt to characterize the developer's time as non-deductible by arguing:

1. The developer's role was "managerial" — i.e., they told an AI what to build and the AI built it.
2. The AI tool (billed at its subscription cost) was the entity performing the qualified research activity.
3. Therefore, the deductible amount is limited to the AI subscription cost, not the developer's time.

## Why This Argument Fails

1. **The developer is the architect.** Every design decision originates with the developer. [Cite specific architectural decisions from your project.]

2. **The developer writes code.** They do not merely approve AI-generated code. They specify implementations, debug failures, reject incorrect approaches, and refactor results. The transcripts demonstrate this.

3. **The developer's expertise is the input.** [Describe your domain expertise and why it is essential to this project. The AI tool does not possess this expertise.]

4. **Claude is a productivity tool.** It is analogous to an IDE with autocomplete, a compiler, or a reference database. No one argues that a lawyer's time is non-deductible because they used Westlaw. The same logic applies here.

5. **The documentary record supports this.** Transcripts show the developer giving specific technical instructions, rejecting proposals, redirecting architecture, and making every material judgment call.

## Mitigation

- Maintain complete transcripts of all development sessions (`Transcripts/`).
- Maintain logs of Claude's internal reasoning to demonstrate it operates under direction (`Logs/`).
- Maintain timesheets of developer hours per session (`Timesheets/`).
- Track guidance changes to show the developer's ongoing technical direction (`Guidance/`).
- Preserve this memo and all supporting materials (`Internal/`).
