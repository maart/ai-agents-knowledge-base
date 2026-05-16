[К разделу Источники](README.md)

# Источник: Building effective agents

## Метаданные

- URL: https://www.anthropic.com/engineering/building-effective-agents
- Дата доступа: 2026-05-16
- Тип: essay / engineering guide
- Автор / организация: Anthropic
- Год: 2024

## Главная идея

Anthropic различает [workflows](../notes/concepts/workflow.md) и agents: workflows идут по заранее заданным путям выполнения (code paths), а agents динамически направляют собственный процесс и [tool use](../notes/concepts/tool-use.md). Статья предлагает начинать с простых составных паттернов (composable patterns) и осторожно добавлять autonomy, а не по умолчанию выбирать сложные [agent](../notes/concepts/agent.md) frameworks.

## Значение для AI agents

- Дает ясное концептуальное различие между workflow и agent.
- Полезен для архитектурных паттернов (architecture patterns): prompt chaining, routing, parallelization, orchestrator-workers, evaluator-optimizer и autonomous agents.
- Дает практическое предупреждение: увеличивать agency только там, где задача действительно выигрывает от этого.

## Заметки

- Это ключевой концептуальный источник для различения chatbot, workflow и agent в проекте.
- Его стоит читать вместе с implementation docs и эмпирическими оценками (empirical evaluations).

## Надежность и ограничения

- Сильная инженерная перспектива от frontier model provider.
- Это не benchmark и не нейтральный survey; лучше воспринимать как практическое руководство.

## Вопросы для продолжения

- Какие задачи действительно требуют agent autonomy?
- Как перевести принцип "simple first" в правила product design?
