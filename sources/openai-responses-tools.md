[К разделу Источники](README.md)

# Источник: OpenAI Responses API и tools

## Метаданные

- URL: https://platform.openai.com/docs/guides/tools?api-mode=responses
- Связано: https://platform.openai.com/docs/api-reference/responses
- Дата доступа: 2026-05-16
- Тип: docs
- Автор / организация: OpenAI
- Год: 2025-2026

## Главная идея

Responses API относится к [Model](../01-glossary.md#model) / [API layer](../01-glossary.md#api-layer) и делает [tool use](../notes/concepts/tool-use.md) частью поверхности взаимодействия с моделью (model interaction surface). Он поддерживает custom function calling и встроенные tools: web search, file search, code interpreter, computer use и remote [MCP](../notes/concepts/protocols-and-interoperability.md) servers.

## Значение для AI agents

- Показывает, как tool use становится стандартным API-level primitive.
- Важен для понимания различия между "модель отвечает" (model answers) и "модель действует через инструменты" (model acts through tools).
- Связывает [agentic systems](../notes/concepts/agent.md) с MCP, computer use и long-running [workflows](../notes/concepts/workflow.md).

## Заметки

- Отслеживать, как Responses соотносится с Agents SDK и AgentKit.
- Полезный источник по текущей OpenAI terminology вокруг tools и stateful interactions.

## Надежность и ограничения

- Официальная документация OpenAI.
- Продуктовая поверхность быстро меняется; источник нужно периодически пересматривать.

## Вопросы для продолжения

- Какие tools считать core agent primitives?
- Как applications должны ограничивать tool choice?
