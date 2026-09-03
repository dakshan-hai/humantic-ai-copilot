# Humantic AI for Microsoft 365 Copilot

This repo hosts the installable agent package that connects Microsoft 365 Copilot to Humantic's MCP server (https://mcp.humantic.ai/mcp).

Use it when your Microsoft 365 tenant does not allow adding custom connectors or agents from the store, and sideloading is the only path.

## Install

1. Download `humantic-ai-copilot.zip` from this repo (open the file, then click Download).
2. Open Microsoft Teams (desktop or web).
3. Go to **Apps** > **Manage your apps** > **Upload an app** > **Upload a custom app**.
4. Select the downloaded `humantic-ai-copilot.zip`.
5. Open Microsoft 365 Copilot, select the **Humantic AI MCP** agent, and start a chat. You will be prompted to sign in with your Humantic account the first time.

## What you can do

- **Agent Pi (personality)**: read any prospect's DISC personality from a LinkedIn URL, work email, or pasted text, and draft outreach matched to their personality.
- **Agent Miia (account intelligence)**: create and read deep account-research reports, and surface buyer-intent signals across your accounts.

## Requirements

- A Microsoft 365 Copilot license.
- A Humantic subscription. Usage draws on your existing Humantic credits.
- Your Teams admin must allow **Upload custom apps** (sideloading) in the Teams admin center. If the upload option is missing, ask your IT admin to enable it.

## Package contents

| File | Purpose |
| --- | --- |
| `manifest.json` | Teams app manifest (v1.29) |
| `declarativeAgent.json` | Copilot declarative agent definition (v1.8) |
| `ai-plugin.json` | MCP server plugin definition (v2.4) |
| `color.png`, `outline.png` | App icons |

## Support

Email help@humantic.ai
