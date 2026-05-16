[К разделу Источники](README.md)

# Источник: OpenAI AgentKit

## Метаданные

- URL: https://openai.com/index/introducing-agentkit/
- Связанная документация: https://platform.openai.com/docs/guides/agents
- Дата доступа: 2026-05-16
- Тип: product / docs
- Автор / организация: OpenAI
- Год: 2025

## Главная идея

AgentKit объединяет несколько частей agent product development в один [platform layer](../01-glossary.md#agent-platforms): Agent Builder для создания [workflows](../notes/concepts/workflow.md), ChatKit для встраивания agent chat experiences, Connector Registry для управления data/tool connections и [Evals](../notes/concepts/evals.md) для измерения agent behavior.

## Значение для AI agents

- Показывает движение от agent SDKs к end-to-end [agent platforms](../01-glossary.md#agent-platforms).
- Полезен для различения model capability и product infrastructure.
- Важен для темы workflow/agent hybrid: Agent Builder явно описывает agents как workflows, которые можно строить, версионировать, встраивать и оценивать (build, version, embed и evaluate).

## Заметки

- AgentKit особенно полезен для отслеживания того, как agent systems становятся productized: build, deploy, connect, evaluate.
- Сравнить с n8n-style workflow builders: оба используют визуальную композицию (visual composition), но AgentKit центрирован на AI-agent workflows и model/tool evaluation.

## Надежность и ограничения

- Официальный анонс продукта OpenAI и документация.
- Продуктовая упаковка может меняться; документацию стоит периодически пересматривать.

## Вопросы для продолжения

- Какая часть agent development перейдет в визуальные builders?
- Как AgentKit evals соотносятся с standalone eval platforms и framework-specific tracing?
