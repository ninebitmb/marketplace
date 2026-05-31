# devdata.lt connector

Connects Claude to the **devdata.lt** MCP server (`https://mcp.devdata.lt`) — a
centralized Lithuanian open-data hub.

## Tools

Once installed, the devdata MCP server exposes tools to query:

- Company core data (JAR registry: name, code, status, address, legal form)
- VAT registration + tax status (VMI)
- Sodra employment / wage data
- Financial reports (revenue, profit, equity)
- Public contracts (CVPP)
- Insolvency / bankruptcy events
- Registered vehicles (Regitra)
- Reference data and lookups

## Authentication

The first time you use the connector, Claude opens an OAuth 2.1 browser flow to
devdata.lt. Your token is stored securely and refreshed automatically. No client
ID or secret is needed — the client registers dynamically (DCR).

## Install

```
/plugin marketplace add ninebitmb/marketplace
/plugin install devdata@ninebit-marketplace
```
