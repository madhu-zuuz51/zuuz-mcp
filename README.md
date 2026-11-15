# ZUUZ AI CRM MCP Server

Find deals and follow-ups hiding in your email that never made it into your CRM.

ZUUZ is a hosted MCP server that gives AI assistants access to your ZUUZ CRM: leads, deals, pipeline, conversations and prospecting.

## Connect

| | |
|---|---|
| **Endpoint** | `https://mcp.zuuz.ai/mcp` |
| **Transport** | Streamable HTTP |
| **Website** | [zuuz.ai](https://zuuz.ai) |

Add it to any MCP client that supports remote servers:

```json
{
  "mcpServers": {
    "zuuz": {
      "url": "https://mcp.zuuz.ai/mcp"
    }
  }
}
```

## What you can do

- **Leads**: list, search and review leads, move them between stages, reassign owners
- **Deals and pipeline**: see deal stats and move deals through your pipeline
- **Conversations**: search email threads and link them to the right lead
- **Prospecting**: browse prospects and see why they scored the way they did

## Listings

- Official MCP Registry: `ai.zuuz/zuuz`
- LobeHub: [madhu-zuuz51-zuuz-mcp](https://lobehub.com/mcp/madhu-zuuz51-zuuz-mcp)

This repository holds listing metadata only. The server itself is hosted by ZUUZ.
