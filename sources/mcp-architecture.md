[К разделу Источники](README.md)

# Источник: Model Context Protocol architecture

## Метаданные

- URL: https://modelcontextprotocol.io/docs/learn/architecture
- Specification: https://modelcontextprotocol.io/specification/
- Дата доступа: 2026-05-16
- Тип: docs / specification
- Автор / организация: Model Context Protocol project
- Год: 2024-2026

## Главная идея

[MCP](../notes/concepts/protocols-and-interoperability.md) определяет стандартный способ подключения AI-приложений к tools, resources и prompts, которые предоставляют external servers. Его значение архитектурное: он пытается сделать context и tool integration переиспользуемыми между clients, вместо того чтобы заново строить custom integration для каждого AI-приложения.

## Значение для AI agents

- MCP — часть infrastructure layer вокруг [agents](../notes/concepts/agent.md).
- Помогает отделить agent/client от external возможности (capabilities).
- Поднимает важные вопросы permissions, trust boundaries, transport, tool schemas и security.

## Заметки

- В этом проекте MCP стоит изучать как protocol для agent environments, а не просто как developer convenience.
- Отслеживать различия между MCP clients, MCP servers, tools, resources, prompts и transports.

## Надежность и ограничения

- Официальная документация и specification — основной источник по protocol concepts.
- Экосистема быстро меняется; карточки источников должны включать дату доступа и пересматриваться.

## Вопросы для продолжения

- Как MCP соотносится с обычным function calling?
- Какая security model нужна, когда agents могут вызывать MCP servers?
