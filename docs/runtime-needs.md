# Runtime Needs

## What You Already Have

- Git installed locally
- GitHub account connected through the GitHub app
- GitHub CLI installed locally
- Claude environment present locally
- Codex environment present locally
- Gemini environment present locally
- browser automation tooling present locally

## What Is Blocking Smooth Operation

| Need | Current State | Action |
|---|---|---|
| Central repo | Missing | Use this command center as the source of truth |
| GitHub CLI auth | Missing | Run `gh auth login` |
| Stable naming | Missing | Pick a final repo name such as `agent-command-center` or `ai-operator-hq` |
| KPI tracking | Missing | Create one sheet for traffic, spend, sales, and margin |
| Decision focus | Missing | Choose one primary business lane for the next 30 days |

## Minimum Stack To Run Properly

1. One repo
2. One project board
3. One KPI sheet
4. One content calendar
5. One experiment log

## Suggested Repo Sections

- `README.md` for the command model
- `docs/agent-inventory.md`
- `docs/monetization-roadmap.md`
- `docs/runtime-needs.md`
- `.github/ISSUE_TEMPLATE/` for agent tasks and experiments

## Can You Run Both In Terminal?

Yes, with an important distinction.

- Claude: yes, via Claude Code in terminal
- ChatGPT/Codex: yes, via Codex tooling and terminal-oriented workflows

They are separate products and separate auth flows.
Running both is normal, but the clean setup is one terminal tab/session per agent, with GitHub used as the shared handoff surface.

## Recommended Terminal Layout

1. Terminal 1: Claude for planning/research
2. Terminal 2: Codex for implementation
3. GitHub issues: shared task list and handoffs
4. One local project folder checked out once
