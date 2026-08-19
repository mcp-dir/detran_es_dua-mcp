# Instalação detalhada

DETRAN ES: Emissão de Documento Único de Arrecadação (DUA) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_es_dua`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_es_dua` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_es_dua` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_es_dua` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_es_dua` (ou `servers.detran_es_dua` no VS Code) do config do cliente e reinicie.
