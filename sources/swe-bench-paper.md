[К разделу Источники](README.md)

# Источник: SWE-bench: Can Language Models Resolve Real-World GitHub Issues?

## Метаданные

- URL: https://arxiv.org/abs/2310.06770
- Дата доступа: 2026-05-16
- Тип: paper / benchmark
- Автор / организация: Carlos E. Jimenez et al.
- Год: 2023

## Главная идея

SWE-bench оценивает языковые модели (language models) на реальных GitHub issues, где model должна изменить codebase так, чтобы tests прошли. Он превращает software engineering в benchmark для multi-step, environment-grounded problem solving.

## Значение для AI agents

- Важный benchmark для coding [agents](../notes/concepts/agent.md) и выполнения реальных задач (real-world task completion).
- Подчеркивает, что agent оценка (evaluation) часто требует executable environments, а не только оценки ответов (answer grading).
- Подсвечивает long-context reasoning, repository navigation и test feedback.

## Заметки

- SWE-bench особенно релевантен для изучения "task success", а не качества разговора (conversational quality).
- Более поздние variants и critiques стоит отслеживать отдельно.

## Надежность и ограничения

- Широко используемый исследовательский benchmark.
- Passing tests — полезный сигнал, но не полная мера maintainability или product correctness.

## Вопросы для продолжения

- Что SWE-bench упускает в real software work?
- Как benchmarks должны учитывать time, cost и human review?
