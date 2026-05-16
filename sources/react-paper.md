[К разделу Источники](README.md)

# Источник: ReAct: Synergizing Reasoning и Acting in Language Models

## Метаданные

- URL: https://arxiv.org/abs/2210.03629
- Дата доступа: 2026-05-16
- Тип: paper
- Автор / организация: Shunyu Yao et al.
- Год: 2022 / ICLR 2023

## Главная идея

ReAct объединяет reasoning traces с actions. Модель чередует размышление о задаче (thinking about the task) и действия (actions), которые взаимодействуют с внешней средой (external environment), например search или task-specific tools.

## Значение для AI agents

- Базовый pattern для [agent](../notes/concepts/agent.md) loops: reason, act, observe.
- Помогает объяснить, почему [tool use](../notes/concepts/tool-use.md) меняет роль модели: от генератора ответов (answer generator) к интерактивному решателю задач (interactive problem solver).
- Полезный исторический мост между prompting research и современными agent frameworks.

## Заметки

- ReAct — не вся история agents, но он дает чистый primitive для понимания action loops.
- Сравнить с более поздними работами про [planning](../notes/concepts/planning.md), reflection, tool use и long-running execution.

## Надежность и ограничения

- Рецензируемый и широко цитируемый research paper.
- Experiments относятся к более раннему поколению по сравнению с текущими models и production agent systems.

## Вопросы для продолжения

- Какие части ReAct остаются полезными с более сильными models?
- Когда explicit reasoning/action formatting улучшает или ухудшает качество работы (performance)?
