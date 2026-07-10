# Enterprise MCP Essentials — Lab Guides

Practical lab guides for building Model Context Protocol (MCP) servers with
Workato. Served via GitHub Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Labs

| Lab | Tier | Time |
|---|---|---|
| [Connect your assistant to an internal app](docs/mcp-1-customer-support-hub.html) | Foundational | 90 minutes |
| [Extend the hub across Salesforce and Jira](docs/mcp-2-cross-functional.html) | Intermediate | 60 minutes |
| [Fix the contract, not the prompt](docs/mcp-3-tool-contract.html) | Intermediate | 45 minutes |

## Structure

- `docs/` — the published surface: course index + one self-contained page per lab (Pages source)

- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook — enable once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit lab HTML in place — changes land as a fresh press
of the whole bundle.
