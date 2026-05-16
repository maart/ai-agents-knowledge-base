[К разделу Источники](README.md)

# Источник: Generative Agents: Interactive Simulacra of Human Behavior

## Метаданные

- URL: https://arxiv.org/abs/2304.03442
- Дата доступа: 2026-05-16
- Тип: paper
- Автор / организация: Joon Sung Park et al.
- Год: 2023

## Главная идея

Generative Agents изучает simulated agents с [memory](../notes/concepts/memory.md), reflection и [planning](../notes/concepts/planning.md). Paper меньше про tool execution и больше про то, как правдоподобное [agent](../notes/concepts/agent.md) behavior может возникать из хранения experiences, retrieval relevant memories и генерации plans.

## Значение для AI agents

- Важный источник про memory и reflection в agent systems.
- Помогает разделить "agent как исполнитель действий" (agent as action executor) и "agent как устойчивый симулированный участник" (agent as persistent simulated actor).
- Полезен для обсуждения [long-term memory](../notes/concepts/long-term-memory.md), [retrieval](../notes/concepts/retrieval-rag.md) и behavioral consistency.

## Заметки

- Environment является simulation, а не production tool-use setting.
- Все равно ценен, потому что дает конкретную architecture для memory streams, reflection и planning.

## Надежность и ограничения

- Рецензируемый и широко цитируемый research paper.
- Simulated social behavior не переносится напрямую на enterprise agent надежность (reliability).

## Вопросы для продолжения

- Какие memory patterns переносятся из simulations в практические agent [workflows](../notes/concepts/workflow.md)?
- Как agents должны решать, что помнить, summarize или forget?
