# Player 1 for Grok Bot and Cursor

Your own Player 1 file, read live: how you like to be written to, your plans, your people and your routines, one task at a time, with updates you approve in Player 1.

[Player 1](https://player1.bio) is a file about you that you build and keep: how you like to be written to, your plans, your people, your routines. This plugin lets Grok Bot and Cursor read the parts you choose, live, for the task at hand. Nothing about you is in this repo; everything is read from Player 1 when you sign in.

## Setup

1. Install the Player 1 plugin from the Marketplace.
2. When it connects, Player 1 opens its sign-in page. Sign in, choose which parts of your file this assistant may read (Money and Health stay closed unless you open them), and press Allow. No key or header is needed (OAuth with PKCE).
3. Try "Plan dinner on Saturday for the three of us." or "Draft a short update for my manager."

You need a Player 1 file. Make one free at https://player1.bio in about three minutes.

## What it includes

- **The Player 1 connector** (`mcp.json`): https://player1.bio/mcp, a remote MCP server.
- **Skill `player1`:** when to read the file, using only what the task needs, and suggesting updates the person approves.

## Tools

| Tool | What it does |
|---|---|
| `about_me` | The lines from your file that matter for one task |
| `file_search` | Lines that mention a word or name |
| `suggest_update` | Suggests a change to your file; it waits for you to approve in Player 1 |

## Your data

The assistant reads only the parts of your file you allowed for this connection. It can't change your file: it only suggests, and you approve or turn down each suggestion in Player 1. Disconnect any time at https://player1.bio/ais.

Support: https://player1.bio/support · Privacy: https://player1.bio/privacy · Terms: https://player1.bio/terms

## License

MIT (this plugin's files). Player 1 itself is a hosted service.

The plugin is in [plugins/player1](plugins/player1).
