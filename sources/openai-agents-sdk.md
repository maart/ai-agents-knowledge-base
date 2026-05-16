[К разделу Sources](README.md)

# Source: OpenAI Agents SDK

## Metadata

- URL: https://platform.openai.com/docs/guides/agents-sdk/
- Related docs: https://openai.github.io/openai-agents-python/agents/ and https://openai.github.io/openai-agents-js/guides/agents/
- Accessed: 2026-05-16
- Type: docs
- Author / organization: OpenAI
- Year: 2025-2026

## Main idea

OpenAI Agents SDK presents agents as an orchestration layer around models, tools, guardrails, handoffs, sessions and execution. The important shift is not only model quality, but the surrounding runtime that lets models take structured actions and coordinate multi-step work.

## Relevance to AI agents

- Useful as a reference for agent primitives: agent, runner, tools, guardrails, handoffs, sessions.
- Shows how agentic systems move from prompt-only patterns to application infrastructure.
- Important for tracking current product direction around long-running agents, sandboxed execution and computer/[tool use](../notes/concepts/tool-use.md).

## Notes

- Treat the SDK as an implementation reference, not as the definition of agents in general.
- Compare its concepts with LangGraph, AutoGen and CrewAI to separate universal patterns from vendor-specific APIs.

## Reliability and limitations

- Official documentation is authoritative for OpenAI APIs and SDK behavior.
- It is product documentation, so it emphasizes supported patterns and may not discuss limitations as deeply as independent evaluations.

## Follow-up questions

- Which abstractions are common across SDKs?
- How do guardrails and human approval differ between SDK-level and application-level design?
