# Agent Inventory

Updated: 2026-04-24

This inventory is based on tools, folders, config files, and repo state visible on this machine. It does not include private ChatGPT account-side agents unless ChatGPT exports or writes that list into this repo.

## Confirmed Local Agent Systems

| System | Evidence Found | Status | Notes |
|---|---|---:|---|
| Claude Code | `.claude`, `CLAUDE.md`, `@claude-flow/cli` config | 85% | Strong local setup, multi-agent oriented |
| Codex / ChatGPT coding environment | `.codex`, active Codex desktop environment | 80% | Good local setup, GitHub app available |
| Gemini | `.gemini/projects.json` | 45% | Present, but not clearly wired into one shared workflow |
| OpenClaw / browser relay | `browser-relay-final/README.md`, `.openclaw` | 60% | Useful for browser automation and store ops |
| Pixel agents | `.pixel-agents/agent-seats.json` | 20% | Present, unclear business role |
| ECC / Everything Claude Code | `.claude/marketplace.json`, `.claude/agents`, `.claude/.agents/skills` | 85% | Large local agent/skill pack for code, review, content, ops, and workflow |
| Claude Flow | `.mcp.json` with `@claude-flow/cli` | 70% | Multi-agent orchestration surface; auto-start currently false |
| Hermes | `C:\Users\oeroh\HERMES_SETUP.md`, WSL install | 65% | Core installed and verified; provider auth still pending |
| Gmail MCP | Claude MCP config | 50% | Useful for outreach/reply workflows after account approval |
| n8n MCP | Claude MCP config | 55% | Useful for automations; host configured locally |
| Postiz MCP | Claude MCP config | 45% | Useful for social scheduling once connected and approved |
| TikTok MCP | Claude MCP config | 45% | Relevant to TikTok Shop/content workflows |
| Composio MCP | Claude MCP config | 55% | Broad integration layer; config contains sensitive credential material |

## Operational Readiness Score

| Area | Score | Why |
|---|---:|---|
| Agent availability | 85% | Several systems are installed, including ECC, Codex plugins, Claude Flow, and MCP surfaces |
| Shared memory / coordination | 70% | The GitHub-backed command center now defines cross-platform sync rules |
| GitHub operating model | 55% | Local git push works, but `gh` and the Codex GitHub app connector are not logged in |
| Monetization linkage | 50% | The fastest money lanes are now clearer, but agent work still needs tighter owner/task assignment |

## Bottom Line

You do not need more agents right now. You need to connect the agents you already have to one revenue loop.

The highest leverage move is:

1. centralize work in this GitHub repo
2. focus the agents on one revenue path
3. make each agent responsible for a specific stage
4. keep account actions and publishing gated by explicit user approval

## Recommended Roles

| Agent | Best Role |
|---|---|
| ChatGPT | strategy, monetization, agent ranking, content positioning, reporting |
| Codex | implementation, repo edits, automation scripts, issue-to-PR execution, integrations |
| Claude / Cloud Code | long-form planning, issue drafting, market reasoning, workflow design, bounded delegated checks |
| Gemini | alternative research pass, ideation, comparison drafts |
| Browser automation tools | store setup, listing QA, repetitive web workflows |
| ECC code/review agents | quality control, tests, security, refactors, docs |
| TikTok/content agents | listing copy, hooks, video scripts, captions, product angles |
| Gmail/n8n/Postiz/Composio connectors | outreach, follow-up, scheduling, workflow automation |
| Hermes | future router/coordinator between ChatGPT, Codex, Claude, and provider agents |

## Highest-Value Local Agent Groups

| Group | Usefulness | Speed To Value | Revenue Potential | Use It For |
|---|---:|---:|---:|---|
| Content / brand / SEO skills | High | Fast | High | TikTok scripts, product hooks, landing copy, social posts |
| TikTok custom agents | High | Fast | High | Listing optimization and current shop revenue work |
| Gmail / n8n / Postiz / Composio | High | Medium | High | Outreach, scheduling, follow-up, automations |
| Code reviewer / security / e2e agents | Medium | Medium | Medium | Make products and sites shippable without regressions |
| Planner / chief-of-staff / workflow agents | High | Fast | Medium | Keep execution focused and prevent duplicated agent work |
| Hermes | High | Medium | High | Cross-platform coordination once provider auth works |
| Pixel agents | Low until scoped | Slow | Unknown | Hold until tied to a product or service offer |

## What Is Still Missing

- ChatGPT account-side agent export written into this repo
- GitHub CLI login or GitHub app connector connection
- Hermes provider authentication
- one weekly KPI review ritual
- one source of truth for daily revenue/product numbers
- final decision on the primary monetization lane for the next 30 days
