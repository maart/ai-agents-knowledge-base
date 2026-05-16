[К roadmap](../../roadmap.md)

# Concepts

Этот раздел собирает базовые концептуальные заметки об AI agents. Его лучше читать подряд: порядок ниже построен так, чтобы сначала понять границы понятия "[agent](agent.md)", затем компоненты агентской системы, потом более сложные вопросы координации, оценки и рисков.

## Рекомендуемый порядок чтения

1. [Agent](agent.md)

   Что делает систему агентской: цель, действия, инструменты, observations (наблюдения результатов), состояние и правила остановки.

2. [Workflow](workflow.md)

   Почему [workflow](workflow.md) — не слабая версия агента, а надежный способ строить управляемые AI-системы.

3. [Agent vs workflow](agent-vs-workflow.md)

   Как выбирать между agent, workflow и гибридным дизайном.

4. [Tool use](tool-use.md)

   Как модель выходит за пределы текста: function calling, API, browser/computer use, [MCP](protocols-and-interoperability.md) и внешние системы.

5. [Planning](planning.md)

   Как агент разбивает цель на шаги, пересматривает план и понимает, когда нужно остановиться.

6. [Memory](memory.md)

   Разные смыслы памяти: [context window](context-window.md), [session state](session-state.md), [RAG](retrieval-rag.md), [long-term memory](long-term-memory.md), [skill library](skill-library.md) и [audit trail](audit-trail.md).

7. [Multi-agent systems](multi-agent.md)

   Когда несколько агентов или ролей помогают, а когда создают лишнюю сложность.

8. [Protocols and interoperability](protocols-and-interoperability.md)

   Чем различаются MCP и A2A, и почему агентской экосистеме нужны протоколы подключения и взаимодействия.

9. [Evals](evals.md)

   Как оценивать не только финальный ответ, но и траекторию действий, устойчивость, стоимость и human review burden.

10. [Risks](risks.md)

    Основные риски агентских систем: tool misuse, over-autonomy, context errors, prompt injection и слабая наблюдаемость.

## Как использовать раздел

- Читать подряд, если тема новая.
- Возвращаться к отдельным заметкам при работе над черновиком.
- Дополнять каждую заметку источниками из [sources](../../sources/README.md), когда появляется новая карточка.
