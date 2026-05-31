# Ninebit Marketplace

A [Claude plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces)
for Ninebit tools and integrations.

## Plugins

| Plugin | Description |
|--------|-------------|
| `devdata` | Connect Claude to the [devdata.lt](https://devdata.lt) MCP server (Lithuanian company data). |

## Usage

Add the marketplace, then install a plugin:

```
/plugin marketplace add ninebitmb/marketplace
/plugin install devdata@ninebit-marketplace
```

The devdata connector authenticates via OAuth 2.1 (interactive, DCR) on first use.
