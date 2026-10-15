# Kevin's Coaching Brain

Ask a football coaching question in your AI assistant. Get short passages from Kevin Middleton's own writing, each with the link to where he wrote it.

Kevin has coached football since 2010.

## What you can ask
- Plan a session from your age group and the time you have.
- Pick a method: guided, questioning or practising.
- Use AI for your coaching without losing your own voice.
- Handle match day and parents.

## Tools
- `search_brain(query, limit)`: passages that match your question, with the source link.
- `list_sources()`: every article in the brain, with its link.

Both tools only read. No account, no sign-in, no email box.

## Install (about a minute)
Server address: `https://hub.360tft.com/api/brain/mcp`

**Claude**
1. Open Settings, then Connectors.
2. Choose Add custom connector.
3. Paste the address and save.

**ChatGPT**
1. Open Settings, then Connectors.
2. Choose Create and paste the address.
3. Set authentication to none and save.

**Claude Code**
```
claude mcp add --transport http coaching-brain https://hub.360tft.com/api/brain/mcp
```

**Cursor**
1. Open Settings, then MCP, then Add new server.
2. Add the address as the server URL and save.

## Privacy
Coaching Brain tool calls need no sign-in. We use your IP address to rate limit requests. The counter is kept for about a minute. Privacy page: https://footballgpt.co/privacy

## Support
https://footballgpt.co/support

Landing page: https://hub.360tft.com/brain
