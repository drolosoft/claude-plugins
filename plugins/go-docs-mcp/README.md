# go-docs-mcp plugin

Registers [go-docs-mcp](https://github.com/drolosoft/go-docs-mcp) as a stdio
MCP server in Claude Code. The server reads the documents in one folder and
offers 13 read-only tools (read, search, outline, tables, images, OCR,
Markdown conversion, URL download) plus a `docs://<filename>` resource per
document, so you can @-mention a file in the conversation.

The binary is not part of the plugin. Install it first:

```bash
brew install drolosoft/tap/go-docs-mcp   # macOS and Linux, with poppler, tesseract and pandoc
# or
go install github.com/drolosoft/go-docs-mcp@latest
```

Documents are read from `~/.docs-mcp/documents`. To serve another folder,
set `DOCS_MCP_DIR` in your shell before starting Claude Code, or edit the
server's `env` after installing the plugin.
