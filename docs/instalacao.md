# Instalação detalhada

JUCESP: Ficha Cadastral Simplificada é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_jucesp_ficha`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_jucesp_ficha` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_jucesp_ficha` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_jucesp_ficha` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.jucesp_ficha` (ou `servers.jucesp_ficha` no VS Code) do config do cliente e reinicie.
