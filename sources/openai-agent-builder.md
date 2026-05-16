[К разделу Источники](README.md)

# Источник: OpenAI Agent Builder

## Метаданные

- URL: https://platform.openai.com/docs/guides/agent-builder
- Дата доступа: 2026-05-16
- Тип: docs
- Автор / организация: OpenAI
- Год: 2025-2026

## Главная идея

[Agent](../notes/concepts/agent.md) Builder — [visual builder](../01-glossary.md#visual-builders) для создания agent workflows. Он трактует создание agent как задачу проектирования graph/[workflow](../notes/concepts/workflow.md): разработчики собирают nodes, настраивают tools, тестируют behavior, версионируют workflows и выполняют deploy через связанные компоненты OpenAI agent platform.

## Значение для AI agents

- Сильный пример того, как agentic systems становятся workflow-native.
- Полезен для различения workflow, agentic workflow и fully agent-led loops в проекте.
- Показывает, что visual workflow tools не находятся вне agent ecosystem; они могут стать одним из основных способов собирать и управлять agent behavior.

## Заметки

- Этот источник важен для обсуждения n8n/workflow: branching и visual orchestration могут оставаться workflow, а model-selected steps внутри bounded regions могут становиться agentic workflow.
- Сравнить с LangGraph как code-first graph orchestration.

## Надежность и ограничения

- Официальная документация OpenAI.
- Документация описывает задуманное поведение продукта (intended product behavior), а не независимые findings по reliability.

## Вопросы для продолжения

- Какие agent workflows лучше выражать визуально, а какие требуют кода?
- Как визуальные agent builders должны показывать версионирование (versioning), [evals](../notes/concepts/evals.md) и audit trails?
