[К разделу Источники](README.md)

# Источник: Toolformer: Language Models Can Teach Themselves to Use Tools

## Метаданные

- URL: https://arxiv.org/abs/2302.04761
- Дата доступа: 2026-05-16
- Тип: paper
- Автор / организация: Timo Schick et al.
- Год: 2023

## Главная идея

Toolformer изучает, как языковые модели (language models) могут научиться, когда и как вызывать external APIs, используя self-supervised data construction из небольшого числа demonstrations.

## Значение для AI agents

- Важный ранний paper про tool-use как learned model возможность (capability).
- Отделяет вопрос "может ли модель использовать инструменты?" (can the model use tools?) от более широкого вопроса "может ли система действовать как [agent](../notes/concepts/agent.md)?" (can the system act as an agent?).
- Полезен для истории function calling и API interaction.

## Заметки

- Toolformer про learning [tool use](../notes/concepts/tool-use.md), а не про полноценную agent orchestration.
- Читать вместе с ReAct, чтобы сравнить learned API calls с prompted reason-act loops.

## Надежность и ограничения

- Исследовательский paper 2023 года.
- Results предшествуют многим текущим tool-capable frontier models и production APIs.

## Вопросы для продолжения

- Какая часть tool use должна быть выучена моделью (learned by the model), а какая контролироваться приложением (controlled by the application)?
- Что остается релевантным после современных function-calling APIs?
