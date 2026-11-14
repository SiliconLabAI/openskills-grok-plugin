# OpenDef Grok Build Plugin

Connects Grok Build to the hosted OpenDef Skills MCP server.

## MCP Server

- **URL:** `https://skills.opendef.com/api/skills/mcp`
- **Transport:** Streamable HTTP
- **Auth:** OAuth 2.1 (Bearer) — user signs in on first use

## What it does

Lets Grok discover and load agent skills exposed by the OpenDef Skills MCP server.

## Network endpoints

- `https://skills.opendef.com/api/skills/mcp` — MCP tools and resources
- OAuth endpoints under `https://www.opendef.com` (authorization, token, well-known metadata)

## Credentials / permissions

Requires an OpenDef account. Authentication is handled via OAuth 2.1 by the Grok MCP client. No API keys or secrets are stored in this plugin.

## License

MIT
