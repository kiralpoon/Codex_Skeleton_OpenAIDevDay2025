# ExecPlans
When writing complex features or significant refactors, use an ExecPlan (as described in .agent/PLANS.md) from design to implementation.

## Ignore Memos / Personal Notes
- Treat files explicitly marked as personal memos as out of scope for coding, planning, or citations.
- A file is considered out of scope if any of the following is true (checked within the first 50 lines):
  - It contains a YAML front-matter block with codex.ignore: true.
  - It contains a line matching CODEx-IGNORE: true (case-insensitive).
- For such files, do not read beyond the header, do not summarize, cite, modify, or rely on their content unless the user explicitly asks.
- Explicitly out of scope in this repo: Kiral_OpenAI_Event_Memo.

This policy applies to the entire repository.