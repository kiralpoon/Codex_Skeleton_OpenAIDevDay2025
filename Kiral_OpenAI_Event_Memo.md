---
codex:
  ignore: true
  reason: personal_memo
---
CODEx-IGNORE: true

# OpenAI Dev Day 2025 - Event Memo

# Codex IDE

## 1. Setup Checklist
1. Install Codex into your IDE
   - Visual Studio Code
   - Cursor
   - [Video Walkthrough Demo at the event]()
2. Update your editor layouts to the event-ready configuration.

## 2. Configuration File Location
The Codex configuration file lives at `~/.codex/config.toml`.

Open it quickly from the extension by using **Codex Settings > MCP Settings > Open config.toml** (top-right of the extension panel). The official docs are out of date, so rely on this path.

```toml
[tools]
web_search = true
```

## 3. MCP and Networked Tooling (Optional)
- Add networked MCP servers when you need search/fetch APIs or internal services.
- Enable outbound HTTP only for trusted tooling.
- Use the config snippet above to toggle built-in web search support.
Sandbox Settings Snippet(Optional)
```toml
[sandbox_workspace_write]
network_access = true
```

## 4. Agents.md Quick Reference
```
my-repo/
|- AGENTS.md              # tells Codex when/how to use plans, tests, style, etc.
|- .agent/
|  \- PLANS.md            # ExecPlan spec referenced by AGENTS.md
|- src/                   # your code
\- tests/                 # optional but recommended
```

## 5. Agent Model Choice
- Select `gpt-5-codex` (medium) for coding tasks. (In general)
- If you accidentally choose `gpt-5`, expect degraded PowerShell support and trouble editing `Agents.md`.

## 6. Project Kickoff Links
- Start from this skeleton: [GitHub Repository](https://github.com/kiralpoon/Codex_Skeleton_OpenAIDevDay2025/)
- Target outcome: launch the personal website.
- Demo recap: [Video Walkthrough Demo at the event]()

# AgentKit

## 1. Agentkit
- [Indroducing Agentkit]{https://openai.com/index/introducing-agentkit/}
Agent Builder -> A visual agent workflow builder like Dify, n8n, Flowise and etc.
Chatkit -> Embedded UI
https://platform.openai.com/agent-builder

## 2. Widget Studio
https://widgets.chatkit.studio/
