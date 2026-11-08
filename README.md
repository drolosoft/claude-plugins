# Drolosoft plugins for Claude Code

One marketplace for every plugin and mod Drolosoft publishes.

```bash
claude plugin marketplace add drolosoft/claude-plugins
```

| Plugin | What it is | Install |
|---|---|---|
| [taskrail](https://github.com/drolosoft/taskrail) | A live board of your session's plan above the prompt (a mod) | `claude plugin install taskrail@drolosoft-marketplace` |
| [immich-photo-manager](https://github.com/drolosoft/immich-photo-manager) | MCP server and skills for Immich photo libraries | `claude plugin install immich-photo-manager@drolosoft-marketplace` |
| [go-docs-mcp](https://github.com/drolosoft/go-docs-mcp) | MCP server for local documents: PDF with OCR, Office, EPUB, text, images | `claude plugin install go-docs-mcp@drolosoft-marketplace` |

Each plugin lives in its own repository with its own releases; this catalog only points at them. The go-docs-mcp entry is the exception: it is only the MCP registration and lives here under `plugins/go-docs-mcp`, while the server itself is released from its own repository. Updates arrive with `claude plugin update <name>@drolosoft-marketplace`.

MIT. Copyright (c) 2026 Drolosoft.
