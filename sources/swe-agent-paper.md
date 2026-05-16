[К разделу Источники](README.md)

# Источник: SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering

## Метаданные

- URL: https://arxiv.org/abs/2405.15793
- Проект: https://github.com/swe-agent/SWE-agent
- Дата доступа: 2026-05-16
- Тип: paper / open-source project
- Автор / организация: SWE-agent team
- Год: 2024

## Главная идея

SWE-agent изучает, как языковая модель (language model) [agents](../notes/concepts/agent.md) могут решать задачи software engineering, взаимодействуя с computer-like interface: inspecting files, editing code и running tests.

## Значение для AI agents

- Coding agents — одна из самых понятных practical categories для agentic systems.
- Показывает, как interface между model и environment влияет на качество работы (performance).
- Связывает [tool use](../notes/concepts/tool-use.md), long context, execution feedback и оценка (evaluation).

## Заметки

- Полезно сравнить с general browser/computer use agents.
- Interface design не нейтрален: он формирует, что agent может делать хорошо.

## Надежность и ограничения

- Исследовательский paper и поддерживаемый open-source project.
- Software engineering tasks важны, но не репрезентативны для всех agent domains.

## Вопросы для продолжения

- Что делает agent-computer interface эффективным?
- Как coding agents должны показывать uncertainty и просить review?
