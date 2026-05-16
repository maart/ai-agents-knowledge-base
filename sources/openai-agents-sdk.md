[К разделу Источники](README.md)

# Источник: OpenAI Agents SDK

## Метаданные

- URL: https://platform.openai.com/docs/guides/agents-sdk/
- Связанная документация: https://openai.github.io/openai-agents-python/agents/ и https://openai.github.io/openai-agents-js/guides/agents/
- Дата доступа: 2026-05-16
- Тип: docs
- Автор / организация: OpenAI
- Год: 2025-2026

## Главная идея

OpenAI Agents SDK представляет agents как orchestration layer вокруг models, tools, guardrails, handoffs, sessions и execution. Важный сдвиг не только в качестве модели, но и в runtime вокруг нее, который позволяет models выполнять structured actions и координировать multi-step work.

## Значение для AI agents

- Полезен как reference для agent primitives: agent, runner, tools, guardrails, handoffs, sessions.
- Показывает, как agentic systems переходят от prompt-only patterns к инфраструктуре приложения (application infrastructure).
- Важен для отслеживания текущего продуктового направления (current product direction) вокруг long-running agents, sandboxed execution и computer/[tool use](../notes/concepts/tool-use.md).

## Заметки

- Рассматривать SDK как implementation reference, а не как определение agents вообще.
- Сравнить его concepts с LangGraph, AutoGen и CrewAI, чтобы отделить универсальные patterns от vendor-specific APIs.

## Надежность и ограничения

- Официальная документация является авторитетным источником по OpenAI APIs и поведению SDK.
- Это продуктовая документация (product documentation), поэтому она подчеркивает поддерживаемые patterns и может не обсуждать ограничения (limitations) так глубоко, как independent evaluations.

## Вопросы для продолжения

- Какие abstractions общие для разных SDKs?
- Чем guardrails и human approval отличаются между SDK-level и application-level design?
