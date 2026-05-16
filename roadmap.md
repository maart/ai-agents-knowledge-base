[На главную](README.md)

# Roadmap

Этот roadmap задает порядок исследования. Он нужен, чтобы база знаний росла не как случайная коллекция ссылок, а как последовательная карта области.

## Iteration 1: базовые определения

Цель: объяснить, что такое AI agent и чем он отличается от chatbot и workflow.

Результаты:

- уточнить [карту темы](00-map.md);
- расширить [глоссарий](01-glossary.md);
- развить заметки в [notes/concepts](notes/concepts/);
- собрать 10-15 ключевых источников в [sources](sources/).

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

Цель: понять инфраструктуру, которая позволяет агентам действовать.

Темы:

- function calling;
- built-in tools;
- remote MCP servers;
- browser/computer use;
- sandbox execution;
- audit logs and tracing.

## Iteration 4: memory and knowledge

Цель: отделить разные смыслы слова "memory".

Темы:

- context window;
- conversation/session state;
- RAG;
- long-term memory;
- skill libraries;
- retrieval and forgetting.

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
- tool use and MCP;
- memory and planning;
- multi-agent patterns;
- evaluation and risks;
- product landscape.
