# Instalação detalhada

TCE SP: Certidão de Apenados é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tce_sp_certidao_apenados`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tce_sp_certidao_apenados` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tce_sp_certidao_apenados` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tce_sp_certidao_apenados` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tce_sp_certidao_apenados` (ou `servers.tce_sp_certidao_apenados` no VS Code) do config do cliente e reinicie.
