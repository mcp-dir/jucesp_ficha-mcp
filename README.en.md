# JUCESP: Ficha Cadastral Simplificada

### JUCESP: Ficha Cadastral Simplificada for Claude, ChatGPT and AI agents

Simplified company registration sheet at JUCESP (by CNPJ, NIRE or name). Platform-hosted, no credentials, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `JUCESP: Ficha Cadastral Simplificada`, URL `https://api.mcp.ai/p_jucesp_ficha`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=jucesp_ficha&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9qdWNlc3BfZmljaGEifQ==)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=jucesp_ficha&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_jucesp_ficha%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_jucesp_ficha
```

---

## 1 tool

| Tool | Description |
|---|---|
| `jucesp_ficha_consultar` | Ficha cadastral simplificada de uma empresa na JUCESP (dados de registro por CNPJ, NIRE ou nome). |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_jucesp_ficha` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
