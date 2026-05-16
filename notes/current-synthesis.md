[К разделу Notes](README.md)

# Текущий синтез

Дата: 2026-05-16

Тип: собственный синтез.

## Что уже понятно

AI [agents](concepts/agent.md) стоит понимать не как магически автономных "цифровых работников", а как архитектурный слой вокруг моделей. Модель становится частью цикла действия: получает цель, выбирает следующий шаг, использует инструменты, получает и анализирует результат действия (observation) и продолжает работу.

Главное отличие агента от chatbot — не стиль общения, а способность действовать во внешней среде. Главное отличие агента от [workflow](concepts/workflow.md) — степень свободы в выборе следующего шага. Но на практике эти границы размыты: надежные системы часто совмещают жесткий workflow, [tool use](concepts/tool-use.md), human approval и ограниченную автономность.

## Базовая структура агента

У агента обычно есть:

- модель;
- контекст;
- инструменты;
- память или состояние;
- механизм планирования;
- среда выполнения;
- правила остановки;
- guardrails и проверка результата.

## Почему экосистема важна

Качество модели — только часть вопроса. Агентские системы требуют инфраструктуры: [SDK and orchestration](../01-glossary.md#sdk-and-orchestration), протоколы подключения инструментов, sandbox execution, observability, [evals](concepts/evals.md), управление правами и recovery для долгих задач.

Поэтому вокруг AI agents быстро растет отдельный слой: [SDK and orchestration](../01-glossary.md#sdk-and-orchestration), [MCP](concepts/protocols-and-interoperability.md), [A2A](concepts/protocols-and-interoperability.md), browser/computer use, [visual agent builders и agent platforms](../01-glossary.md#visual-builders-and-agent-platforms), evaluation platforms и product-specific agents.

Новая важная линия: agent ecosystem становится платформенной. OpenAI AgentKit и Agent Builder показывают движение к build/deploy/connect/evaluate workflows. MCP и A2A показывают протокольный слой: MCP соединяет AI-приложения с tools/context, A2A — агентов с другими агентами. Coding agents вроде Claude Code и Codex показывают прикладной слой, где agent loop проверяется реальными файлами, командами, тестами и review.

## Рабочая гипотеза проекта

Агентский AI — это переход от "модель отвечает" к "система выполняет задачу". Самый важный предмет исследования — не только интеллект модели, а вся связка: модель + инструменты + контекст + контроль + оценка.

## Что исследовать дальше

- Граница между workflow и agent.
- Паттерны tool use и function calling.
- [MCP](concepts/protocols-and-interoperability.md) и [A2A](concepts/protocols-and-interoperability.md) как инфраструктурные стандарты.
- Память и долгие задачи.
- [Multi-agent](concepts/multi-agent.md) системы: когда они полезны, а когда создают лишнюю сложность.
- [Agent platforms](../01-glossary.md#visual-builders-and-agent-platforms): visual builders, connector registries, embedded chat and product evals.
- Методы оценки агентских систем.
