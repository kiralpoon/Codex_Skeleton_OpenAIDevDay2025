---
codex:
  ignore: true
  reason: personal_memo
---
CODEx-IGNORE: true

# OpenAI Dev Day 2025 - Event Memo

## Setup Checklist
1. Install Codex into your IDE
   - Visual Studio Code
   - Cursor
   - [Video Walkthrough Demo at the event]()
2. Update your editor layouts to the event-ready configuration.

## Configuration File Location
The Codex configuration file lives at `~/.codex/config.toml`.

Open it quickly from the extension by using **Codex Settings > MCP Settings > Open config.toml** (top-right of the extension panel). The official docs are out of date, so rely on this path.

```toml
[tools]
web_search = true
```

## MCP and Networked Tooling
- Add networked MCP servers when you need search/fetch APIs or internal services.
- Enable outbound HTTP only for trusted tooling.
- Use the config snippet above to toggle built-in web search support.

## Sandbox Settings Snippet
```toml
[sandbox_workspace_write]
network_access = true
```

## Agents.md Quick Reference
```
my-repo/
|- AGENTS.md              # tells Codex when/how to use plans, tests, style, etc.
|- .agent/
|  \- PLANS.md            # ExecPlan spec referenced by AGENTS.md
|- src/                   # your code
\- tests/                 # optional but recommended
```

## Agent Model Choice
- Select `gpt-5-codex` (medium) for coding tasks.
- If you accidentally choose `gpt-5`, expect degraded PowerShell support and trouble editing `Agents.md`.

## Project Kickoff Links
- Start from this skeleton: [GitHub Repository](https://github.com/kiralpoon/Codex_Skeleton_OpenAIDevDay2025/)
- Target outcome: launch the personal website.
- Demo recap: [Video Walkthrough Demo at the event]()
