[На главную](../README.md)

# Source: ReAct: Synergizing Reasoning and Acting in Language Models

## Metadata

- URL: https://arxiv.org/abs/2210.03629
- Accessed: 2026-05-16
- Type: paper
- Author / organization: Shunyu Yao et al.
- Year: 2022 / ICLR 2023

## Main idea

ReAct combines reasoning traces with actions. The model alternates between thinking about the task and taking actions that interact with an external environment, such as search or task-specific tools.

## Relevance to AI agents

- Foundational pattern for agent loops: reason, act, observe.
- Helps explain why tool use changes the model's role from answer generator to interactive problem solver.
- Useful historical bridge between prompting research and modern agent frameworks.

## Notes

- ReAct is not the whole story of agents, but it gives a clean primitive for understanding action loops.
- Compare with later work on planning, reflection, tool use and long-running execution.

## Reliability and limitations

- Peer-reviewed research paper and widely cited.
- Experiments are earlier-generation compared with current models and production agent systems.

## Follow-up questions

- Which parts of ReAct remain useful with stronger models?
- When does explicit reasoning/action formatting improve or harm performance?
