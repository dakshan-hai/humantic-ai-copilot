# Humantic AI Connector

This repo hosts the Humantic AI connector definition files, so you can install the Humantic connector into your Claude account directly from this repo, without downloading anything.

The connector connects Claude to Humantic's MCP server (https://mcp.humantic.ai/mcp).

## Install in Claude

1. Open Claude (claude.ai).
2. Paste this repo link into the chat: https://github.com/dakshan-hai/humantic-ai-copilot
3. Ask Claude to install the Humantic AI connector from this repo into your account.
4. Approve the prompts, and sign in with your Humantic account when asked.

If your plan does not allow Claude to add the connector for you, use developer mode: download `ai-plugin.json` and `manifest.json` from this repo and upload them there.

## Files

| File | Purpose |
| --- | --- |
| `ai-plugin.json` | Connector/plugin definition, points Claude at the Humantic MCP server |
| `manifest.json` | App manifest (v1.29) |
| `declarativeAgent.json` | Agent definition with instructions and conversation starters (v1.8) |
| `color.png`, `outline.png` | App icons |

## What you can do

- **Agent Pi (personality)**: read any prospect's DISC personality from a LinkedIn URL, work email, or pasted text, and draft outreach matched to their personality.
- **Agent Miia (account intelligence)**: create and read deep account-research reports, and surface buyer-intent signals across your accounts.

## Requirements

- A Humantic subscription. Usage draws on your existing Humantic credits.
- If your plan restricts custom connectors, use the developer-mode path above or ask your admin.

## Support

Email help@humantic.ai
