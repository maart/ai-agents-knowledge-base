[К разделу Sources](README.md)

# Source: Model Context Protocol architecture

## Metadata

- URL: https://modelcontextprotocol.io/docs/learn/architecture
- Specification: https://modelcontextprotocol.io/specification/
- Accessed: 2026-05-16
- Type: docs / specification
- Author / organization: Model Context Protocol project
- Year: 2024-2026

## Main idea

MCP defines a standard way for AI applications to connect to tools, resources and prompts exposed by external servers. Its importance is architectural: it tries to make context and tool integration reusable across clients instead of rebuilding a custom integration for every AI app.

## Relevance to AI agents

- MCP is part of the infrastructure layer around agents.
- It helps separate the agent/client from external capabilities.
- It raises important questions about permissions, trust boundaries, transport, tool schemas and security.

## Notes

- For this project, MCP should be studied as a protocol for agent environments, not just as a developer convenience.
- Track the distinction between MCP clients, MCP servers, tools, resources, prompts and transports.

## Reliability and limitations

- Official docs/specification are the primary source for protocol concepts.
- The ecosystem is changing quickly; source cards should include access dates and be revisited.

## Follow-up questions

- How does MCP compare to ordinary function calling?
- What security model is required when agents can call MCP servers?
