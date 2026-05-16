[К разделу Источники](README.md)

# Источник: AgentBench: Evaluating LLMs as Agents

## Метаданные

- URL: https://arxiv.org/abs/2308.03688
- Дата доступа: 2026-05-16
- Тип: paper / benchmark
- Автор / организация: Tsinghua University и соавторы
- Год: 2023 / ICLR 2024

## Главная идея

AgentBench оценивает LLMs как [agents](../notes/concepts/agent.md) в нескольких интерактивных средах (интерактивные среды (interactive environments)): operating systems, databases, knowledge graphs, games, web shopping и web browsing.

## Значение для AI agents

- Важен, потому что оценивает модели в environments, а не только на статические prompts.
- Подсвечивает long-term reasoning, decision-making и instruction following как ключевые сложности agents.
- Полезен для сравнения доменов задач (task domains) и режимы отказа (failure modes).

## Заметки

- AgentBench помогает рассматривать agent оценка (evaluation) как качество взаимодействия во времени.
- Его стоит читать вместе с domain-specific benchmarks вроде SWE-bench.

## Надежность и ограничения

- Исследовательский benchmark, опубликованный на ICLR 2024.
- Симулированные или benchmarked environments все равно могут отличаться от production-развертывания.

## Вопросы для продолжения

- Какие environments лучше всего предсказывают реальную полезность продукта?
- Как agent benchmarks должны учитывать safety и cost?
