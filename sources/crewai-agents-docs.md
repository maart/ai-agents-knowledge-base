[К разделу Источники](README.md)

# Источник: CrewAI agents документация

## Метаданные

- URL: https://docs.crewai.com/en/concepts/agents
- Дата доступа: 2026-05-16
- Тип: docs
- Автор / организация: CrewAI
- Год: 2023-2026

## Главная идея

CrewAI описывает agents как role-based units, которые выполняют tasks, используют tools, сотрудничают с другими agents, поддерживают [memory](../notes/concepts/memory.md) и опционально делегируют. Его продуктовый язык близок к метафоре "AI team".

## Значение для AI agents

- Полезен для изучения абстракций role/task/crew.
- Показывает популярный прикладной framing для [multi-agent](../notes/concepts/multi-agent.md) automation.
- Дает контраст к более низкоуровневым orchestration frameworks.

## Заметки

- Метафора team интуитивна, но ее нужно проверять на реальных надежность (reliability) и оценка (evaluation) constraints.
- Сравнить "crew" abstractions с explicit graph control.

## Надежность и ограничения

- Официальная документация CrewAI.
- Продуктовый framing может сильнее подчеркивать успешные use cases, чем ограничения.

## Вопросы для продолжения

- Какие части role-based agents являются полезной architecture, а какие — interface metaphor?
- Как delegation влияет на надежность (reliability)?
