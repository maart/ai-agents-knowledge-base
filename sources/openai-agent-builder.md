[К разделу Sources](README.md)

# Source: OpenAI Agent Builder

## Metadata

- URL: https://platform.openai.com/docs/guides/agent-builder
- Accessed: 2026-05-16
- Type: docs
- Author / organization: OpenAI
- Year: 2025-2026

## Main idea

[Agent](../notes/concepts/agent.md) Builder is a visual canvas for building agent workflows. It treats agent creation as a graph/[workflow](../notes/concepts/workflow.md) design problem: developers compose nodes, configure tools, test behavior, version workflows and deploy them through related OpenAI agent platform components.

## Relevance to AI agents

- Strong example of agentic systems becoming workflow-native.
- Useful for the project's distinction between workflow, agentic workflow and fully agent-led loops.
- Shows that visual workflow tools are not outside the agent ecosystem; they may become one of the main ways agent behavior is assembled and governed.

## Notes

- This source is important for the n8n/workflow discussion: branching and visual orchestration can remain workflow, while model-selected steps inside bounded regions can become agentic workflow.
- Compare with LangGraph for code-first graph orchestration.

## Reliability and limitations

- Official OpenAI documentation.
- Docs describe intended product behavior, not independent reliability findings.

## Follow-up questions

- Which agent workflows are better expressed visually, and which need code?
- How should visual agent builders expose versioning, [evals](../notes/concepts/evals.md) and audit trails?
