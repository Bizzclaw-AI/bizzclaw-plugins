# BizzClaw for Claude Code

Lets Claude Code message you on WhatsApp and keep watching your tools after the session ends.

## Install

```
/plugin marketplace add Bizzclaw-AI/bizzclaw-plugins
/plugin install bizzclaw@bizzclaw
```

The first time a BizzClaw tool is used, Claude Code opens your browser. Sign in to BizzClaw with Google and approve access.
You need a BizzClaw account with WhatsApp linked: https://bizzclaw.co

## What you get
- **send_whatsapp_to_me**: Claude messages you, and only you, on WhatsApp. For example: "ping me when the tests pass".
- **watch**: "tell me on WhatsApp when PR #12 is merged" or "when an email from Dana arrives". It checks after this session
  ends. Watches only read, never act, and end after 30 days.
- **list_findings / delegate_goal**: see what BizzClaw noticed in your tools, and hand it read-only follow-up work.

## Codex
```toml
# ~/.codex/config.toml
[mcp_servers.bizzclaw]
url = "https://agent.bizz-claw.com/mcp"
```
Then run `codex mcp login bizzclaw`.

Support: support@bizz-claw.com · Privacy: https://bizzclaw.co/privacy · Terms: https://bizzclaw.co/terms
