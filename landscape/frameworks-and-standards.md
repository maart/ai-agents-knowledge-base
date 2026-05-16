[К разделу Landscape](README.md)

# Фреймворки, стандарты и продуктовый ландшафт

Эта страница объясняет экосистему вокруг AI agents как набор слоев. Ее задача — не перечислить все инструменты, а дать понятную карту: где находится каждый тип технологии и какую проблему он решает.

## 1. Model/API layer

Базовый слой — это модели и API, через которые приложения получают reasoning, generation, tool calling and multimodal capabilities.

Примеры:

- OpenAI Responses API;
- OpenAI model APIs;
- Claude APIs;
- другие frontier model APIs.

Почему важно: без model/API layer агенту нечем принимать решения. Но сама модель не равна агентской системе. Агент появляется, когда модель встраивается в цикл действий, state, tools, permissions and evals.

## 2. SDK and orchestration

Этот слой помогает собрать [agentic system](../notes/concepts/agent.md) в коде: определить agents, tools, handoffs, guardrails, sessions, graph state and execution flow.

Примеры:

- OpenAI Agents SDK;
- LangGraph;
- AutoGen;
- CrewAI.

Как различать:

- OpenAI Agents SDK показывает provider-native primitives для agents, tools, guardrails and handoffs.
- LangGraph особенно полезен, когда агентское поведение нужно выразить как stateful graph/workflow.
- AutoGen и CrewAI полезны для изучения [multi-agent](../notes/concepts/multi-agent.md) coordination, roles and delegation.

Главная мысль: orchestration отвечает не за "ум" модели, а за управляемость процесса.

## 3. Visual builders and agent platforms

Появляется отдельный слой agent platforms: инструменты, которые помогают не только писать код, но и строить, тестировать, версионировать, подключать и встраивать агентские workflows.

Примеры:

- OpenAI AgentKit;
- OpenAI Agent Builder;
- visual workflow tools, когда они используются для agentic workflows.

Почему важно: многие agentic systems будут собираться не как один большой кодовый агент, а как комбинация visual workflow, tool connections, model calls, [evals](../notes/concepts/evals.md) and human approval.

Это особенно важно для темы [workflow](../notes/concepts/workflow.md): визуальный workflow может оставаться обычным workflow, а может содержать agentic component, если модель выбирает следующий значимый шаг внутри заданных границ.

## 4. Protocols and connectors

Когда agents получают доступ к множеству tools, resources and other agents, нужны стандарты подключения.

Примеры:

- [MCP](../notes/concepts/protocols-and-interoperability.md);
- [A2A](../notes/concepts/protocols-and-interoperability.md);
- connector registries.

Различие:

- MCP соединяет AI-приложения с tools, resources and prompts.
- A2A соединяет agents с другими agents.

Почему важно: protocols снижают фрагментацию интеграций, но расширяют trust boundary. Чем проще подключить внешний tool или agent, тем важнее identity, permissions, provenance, [audit trail](../notes/concepts/audit-trail.md) and sandboxing.

## 5. Runtime and execution environments

Агентская система должна где-то выполнять действия и получать observations.

Примеры runtime-паттернов:

- browser use;
- computer use;
- sandbox execution;
- code execution;
- long-running background tasks;
- file and workspace access.

Почему важно: runtime определяет, что агент реально может сделать. Coding agents особенно хорошо показывают этот слой: inspect -> edit -> run -> observe -> revise.

## 6. Observability, evals and safety

Чем больше агент действует, тем важнее понимать, что он сделал и почему.

Нужны:

- traces;
- tool call logs;
- audit trail;
- replay;
- task success metrics;
- trajectory evaluation;
- human review;
- guardrails and permissions.

Обычная оценка финального ответа недостаточна. Для agents важно оценивать и результат, и путь: какие tools были вызваны, были ли лишние действия, как система реагировала на ошибки, когда потребовался human approval.

## 7. Product categories

На верхнем уровне экосистема распадается на продуктовые категории.

### Coding agents

Пишут, читают и тестируют код. Примеры источников: Claude Code, SWE-agent, SWE-bench.

Почему важны: это одна из самых измеримых agent categories, потому что результат можно проверять через tests, diffs and review.

### Research agents

Ищут источники, сравнивают сведения, строят synthesis.

Почему важны: показывают роль [retrieval](../notes/concepts/retrieval-rag.md), source quality, citation tracking and uncertainty.

### Support agents

Работают с customer support, CRM and knowledge bases.

Почему важны: требуют строгих permissions, escalation rules and [audit trail](../notes/concepts/audit-trail.md).

### Data agents

Анализируют spreadsheets, databases, BI reports and dashboards.

Почему важны: сочетают [tool use](../notes/concepts/tool-use.md), structured data, code execution and explanation.

### Operations agents

Автоматизируют внутренние процессы: документы, коммуникации, monitoring, tickets, incident response.

Почему важны: требуют надежной связки workflow, human approval and observability.

## Как сравнивать инструменты

Для каждого элемента landscape полезно задавать одинаковые вопросы:

- Какой это слой: SDK, platform, protocol, runtime, evals or product?
- Какие agent primitives есть: tools, [memory](../notes/concepts/memory.md), handoffs, guardrails?
- Кто управляет flow: workflow, model, graph or human?
- Как хранится state?
- Есть ли human-in-the-loop?
- Поддерживается ли tracing/replay?
- Как подключаются external tools?
- Как устроены permissions?
- Как проверяется task success?
- Где граница ответственности между фреймворком и приложением?

## Дальше

После этой страницы смотри [Landscape comparison](comparison.md), чтобы быстро сопоставить конкретные инструменты и источники.
