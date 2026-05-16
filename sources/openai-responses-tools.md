[К разделу Sources](README.md)

# Source: OpenAI Responses API and tools

## Metadata

- URL: https://platform.openai.com/docs/guides/tools?api-mode=responses
- Related: https://platform.openai.com/docs/api-reference/responses
- Accessed: 2026-05-16
- Type: docs
- Author / organization: OpenAI
- Year: 2025-2026

## Main idea

The Responses API makes [tool use](../notes/concepts/tool-use.md) part of the model interaction surface. It supports custom function calling and built-in tools such as web search, file search, code interpreter, computer use and remote [MCP](../notes/concepts/protocols-and-interoperability.md) servers.

## Relevance to AI agents

- Shows how tool use is becoming a standard API-level primitive.
- Important for understanding the difference between "model answers" and "model acts through tools".
- Connects [agentic systems](../notes/concepts/agent.md) to MCP, computer use and long-running [workflows](../notes/concepts/workflow.md).

## Notes

- Track how Responses relates to Agents SDK and AgentKit.
- Useful source for current OpenAI terminology around tools and stateful interactions.

## Reliability and limitations

- Official OpenAI documentation.
- Product surface changes quickly; revisit periodically.

## Follow-up questions

- Which tools should be considered core agent primitives?
- How should applications constrain tool choice?
