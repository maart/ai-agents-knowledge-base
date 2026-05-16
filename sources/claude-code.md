[К разделу Источники](README.md)

# Источник: Claude Code

## Метаданные

- URL: https://www.anthropic.com/product/claude-code
- Документация: https://docs.anthropic.com/en/docs/claude-code/overview
- Дата доступа: 2026-05-16
- Тип: product / docs
- Автор / организация: Anthropic
- Год: 2025-2026

## Главная идея

Claude Code — agentic coding system от Anthropic. Он предназначен для чтения codebase, внесения изменений в нескольких файлах (edits across files), запуска commands/tests и передачи code changes на review.

## Значение для AI agents

- Coding agents — одна из самых понятных production categories для [agentic systems](../notes/concepts/agent.md).
- Claude Code подсвечивает практические вопросы: permissions, workspace access, command execution, testing, review, configuration и long-running coding tasks.
- Полезная точка сравнения для OpenAI Codex и SWE-agent.

## Заметки

- Coding agents делают agent loop видимым: inspect files, edit, run tests, observe results, revise.
- Этот источник стоит читать вместе с независимыми papers/benchmarks, такими как SWE-bench и SWE-agent.

## Надежность и ограничения

- Официальная продуктовая страница (product page) и документация.
- Документация vendor показывает заявленную возможность (capability), а не нейтральную оценка (evaluation).

## Вопросы для продолжения

- Какие permissions должны быть у coding agents по умолчанию?
- Как review, tests и audit trails должны быть встроены в coding-agent [workflows](../notes/concepts/workflow.md)?
