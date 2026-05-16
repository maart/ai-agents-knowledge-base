[К study guide](study-guide.md)

# Roadmap

Этот roadmap задает порядок развития проекта. Для чтения и изучения используй [Study guide](study-guide.md); roadmap нужен, чтобы понимать, какие части базы знаний расширять дальше.

## Iteration 1: базовые определения

Цель: объяснить, что такое AI [agent](notes/concepts/agent.md) и чем он отличается от chatbot и [workflow](notes/concepts/workflow.md).

Результаты:

- уточнить [карту темы](00-map.md);
- расширить [глоссарий](01-glossary.md);
- развить заметки в [concepts](notes/concepts/README.md);
- собрать и прочитать ключевые источники по маршруту в [sources](sources/README.md).

## Iteration 2: architecture patterns

Цель: описать повторяющиеся архитектуры агентских систем.

Темы:

- model + tools + state + control loop;
- workflow vs agent loop;
- graph orchestration;
- human-in-the-loop;
- guardrails and permissions;
- long-running tasks.

## Iteration 3: tools, MCP and runtime

Цель: понять инфраструктуру, которая позволяет агентам действовать и подключаться к внешним возможностям.

Темы:

- function calling;
- built-in tools;
- remote [MCP](notes/concepts/protocols-and-interoperability.md) servers;
- [A2A](notes/concepts/protocols-and-interoperability.md) and agent interoperability;
- browser/computer use;
- sandbox execution;
- audit logs and tracing.

## Iteration 4: memory and knowledge

Цель: отделить разные смыслы слова "[memory](notes/concepts/memory.md)".

Темы:

- [context window](notes/concepts/context-window.md);
- [session state](notes/concepts/session-state.md);
- [retrieval/RAG](notes/concepts/retrieval-rag.md);
- [long-term memory](notes/concepts/long-term-memory.md);
- [skill libraries](notes/concepts/skill-library.md);
- [audit trail](notes/concepts/audit-trail.md);
- [retrieval](notes/concepts/retrieval-rag.md) and forgetting.

## Iteration 5: multi-agent systems

Цель: понять, когда несколько агентов дают пользу, а когда создают лишнюю сложность.

Темы:

- role-based agents;
- planner/executor/critic;
- handoffs;
- collaborative software agents;
- coordination failure.

## Iteration 6: evals, safety and reliability

Цель: описать, как проверять агентские системы.

Темы:

- task success;
- tool trajectory;
- regression scenarios;
- SWE-bench and AgentBench;
- safety benchmarks;
- human review and incident analysis.

## Iteration 7: first long-form draft

Цель: собрать первый связный текст на 5-8 страниц.

Черновой заголовок: `drafts/what-are-ai-agents.md`.

Структура:

- AI agents as task-performing systems;
- core components;
- agent vs workflow;
- [tool use](notes/concepts/tool-use.md) and MCP;
- memory and [planning](notes/concepts/planning.md);
- [multi-agent](notes/concepts/multi-agent.md) patterns;
- evaluation and [risks](notes/concepts/risks.md);
- product landscape.

## Iteration 8: agent platforms and product patterns

Цель: понять, как агентские системы превращаются в продукты и платформы.

Темы:

- visual agent builders;
- connector registries;
- embedded agent chat;
- coding agents;
- product eval loops;
- permissions, audit and deployment.
