# DB Query Guard MCP

Paid remote MCP for governed database query review, SQL simulation, approvals, and audits.

## Connect

- Website: https://dbqueryguard.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://dbqueryguard.clauxel.com/mcp
- Server card: https://dbqueryguard.clauxel.com/.well-known/mcp/server-card.json
- Official Registry name: `com.clauxel.dbqueryguard/dbqueryguard-mcp`

This is a hosted Streamable HTTP MCP server. It requires an Authorization bearer token issued after checkout and token claim.

## What It Does

DB Query Guard MCP exposes a fixed, read-only tool surface for database query governance. It is designed for agent workflows that need a hosted MCP endpoint with explicit auth, public discovery metadata, and clear data boundaries.

## Authentication

Send the paid MCP token as:

```http
Authorization: Bearer <token>
```

The token is issued by the product checkout and MCP token claim flow. Do not put tokens in issues, pull requests, logs, or screenshots.

## Files

- [server.json](./server.json) - MCP Registry descriptor.
- [Usage guide](./docs/usage.md) - setup and request examples.
- [Security notes](./docs/security.md) - auth, data boundaries, and safe-use expectations.
- [llms.txt](./llms.txt) - short machine-readable discovery summary.

## Status

This public repository is a docs-only distribution package for directory review and MCP discovery. The hosted server runs at https://dbqueryguard.clauxel.com/mcp.
