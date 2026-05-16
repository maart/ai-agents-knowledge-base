[К разделу Sources](README.md)

# Source: Building effective agents

## Metadata

- URL: https://www.anthropic.com/engineering/building-effective-agents
- Accessed: 2026-05-16
- Type: essay / engineering guide
- Author / organization: Anthropic
- Year: 2024

## Main idea

Anthropic distinguishes workflows from agents: workflows follow predefined code paths, while agents dynamically direct their own processes and tool use. The article argues for simple, composable patterns and careful use of autonomy rather than defaulting to complex agent frameworks.

## Relevance to AI agents

- Gives a clear conceptual distinction between workflow and agent.
- Useful for architecture patterns: prompt chaining, routing, parallelization, orchestrator-workers, evaluator-optimizer and autonomous agents.
- Offers a practical caution: increase agency only when the task benefits from it.

## Notes

- This is a key conceptual source for the project's distinction between chatbot, workflow and agent.
- It should be paired with implementation docs and empirical evaluations.

## Reliability and limitations

- Strong engineering perspective from a frontier model provider.
- It is not a benchmark or neutral survey; treat it as practical guidance.

## Follow-up questions

- Which tasks truly need agent autonomy?
- How can "simple first" be translated into product design rules?
