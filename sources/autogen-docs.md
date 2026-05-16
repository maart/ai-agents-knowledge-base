[К разделу Источники](README.md)

# Источник: Microsoft AutoGen документация

## Метаданные

- URL: https://microsoft.github.io/autogen/
- Дата доступа: 2026-05-16
- Тип: docs
- Автор / организация: Microsoft
- Год: 2023-2026

## Главная идея

AutoGen — framework для создания AI agents и [multi-agent](../notes/concepts/multi-agent.md) applications. Он особенно полезен для изучения agent conversations, coordination, tools и распределенного решения задач (распределенного решения задач (distributed task solving)).

## Значение для AI agents

- Дает конкретный implementation reference для multi-agent систем.
- Полезен для сравнения role-based collaboration с graph/[workflow](../notes/concepts/workflow.md) orchestration.
- Подсвечивает agent communication как architectural primitive.

## Заметки

- Сравнить AutoGen с CrewAI по role-based multi-agent patterns.
- Сравнить с LangGraph по state и control flow.

## Надежность и ограничения

- Официальная документация является авторитетным источником по поведению framework.
- Документация framework фокусируется на поддерживаемых patterns и может не полностью описывать режимы отказа (failure modes).

## Вопросы для продолжения

- Когда agent conversation улучшает результат?
- Как оценивать multi-agent systems помимо качества финального результата?
