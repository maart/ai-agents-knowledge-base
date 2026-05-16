[К разделу Источники](README.md)

# Источник: Voyager: An Open-Ended Embodied Agent with Large Language Models

## Метаданные

- URL: https://arxiv.org/abs/2305.16291
- Проект: https://voyager.minedojo.org/
- Дата доступа: 2026-05-16
- Тип: paper
- Автор / организация: Guanzhi Wang et al.
- Год: 2023

## Главная идея

Voyager — LLM-powered Minecraft [agent](../notes/concepts/agent.md), который исследует environment, пишет executable skills, сохраняет их в [skill library](../notes/concepts/skill-library.md) и переиспользует в будущих tasks.

## Значение для AI agents

- Сильный пример agent [memory](../notes/concepts/memory.md) как reusable skills, а не просто stored text.
- Показывает обратную связь среды (environment feedback), ошибки выполнения (execution errors) и self-verification как часть agent learning.
- Полезен для понимания embodied и open-ended agents: agents, которые действуют в среде и продолжают исследование без заранее фиксированного финального шага.

## Заметки

- Minecraft environment делает feedback конкретным и измеримым.
- Skill libraries — полезная линза для long-term agent возможность (capability) growth.

## Надежность и ограничения

- Исследовательский paper и open-source project.
- Environment симулированная и структурированная; выводы могут не переноситься напрямую на messy business [workflows](../notes/concepts/workflow.md).

## Вопросы для продолжения

- Как skill libraries могут переноситься в неигровые домены (non-game domains)?
- Что считать agent learning, если веса модели (model weights) не меняются?
