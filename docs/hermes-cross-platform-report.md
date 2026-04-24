# Hermes Cross-Platform Report

Updated: 2026-04-24

## Purpose

Hermes should become the connector/coordinator layer between ChatGPT, Codex, Claude / Cloud Code, local repos, and external agents.

## Current Hermes State

Source report: `C:\Users\oeroh\HERMES_SETUP.md`

- Hermes core is installed in WSL Ubuntu.
- Install path: `/home/oeroh/.hermes/hermes-agent`
- Command path: `~/.local/bin/hermes`
- Reported version: `Hermes Agent v0.10.0`
- `hermes doctor` was verified successfully.
- Provider auth is not fully complete.
- Anthropic / Claude is supported, but Hermes does not yet see usable Anthropic credentials.
- Next setup step is interactive provider configuration with `hermes model`.

## Operating Model

- ChatGPT decides strategy, priorities, monetization, and reporting.
- Codex executes repo changes, scripts, integrations, setup, and verification.
- Claude / Cloud Code handles bounded delegated tasks and returns status through handoff files.
- Hermes should pass structured context between them so planning and execution do not drift.

## Information Hermes Should Pass

- current objective
- active repo and path
- task owner
- last completed step
- current blocker
- next action
- credit/cost status if known
- account/publishing permission status
- handoff file path
- links to changed files, issues, commits, or PRs

## Sync Flow

1. ChatGPT writes strategy and monetization direction.
2. Codex turns strategy into files, scripts, integrations, and verification steps.
3. Claude / Cloud Code receives bounded tasks through repo handoff files.
4. Hermes routes summaries and next actions between platforms.
5. Durable state is committed to this GitHub repo.

## Current Blockers

- Hermes provider authentication still needs user-approved interactive setup.
- Exact ChatGPT-side agent inventory is only available after the user pastes or exports it into this shared repo/context.
- Live account edits and publishing remain blocked until explicit user confirmation.
