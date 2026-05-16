[На главную](README.md)

# Study guide

Эта страница — основной маршрут изучения проекта. Она отвечает на вопрос: что читать сейчас и куда идти дальше.

## Логика маршрута

Сначала нужно понять язык и базовые различия. Потом — увидеть карту экосистемы. Только после этого имеет смысл идти в сложные источники: papers, docs, benchmarks and product docs.

```text
overview -> concepts -> landscape -> sources -> synthesis/drafts
```

## 1. Быстрый вход

Начни с двух коротких страниц:

1. [Карта темы](00-map.md)

   Общая рамка: AI -> LLM -> agents -> tools -> memory -> planning -> ecosystem.

2. [Текущий синтез](notes/current-synthesis.md)

   Короткое резюме того, что уже понятно в проекте.

Опционально: держи рядом [глоссарий](01-glossary.md), если термины начинают смешиваться.

## 2. Concepts: базовый язык

Дальше читать [Concepts](notes/concepts/README.md).

Цель этапа: понять основные различия, прежде чем смотреть на продукты и papers.

Особенно важно:

- [Agent](notes/concepts/agent.md)
- [Workflow](notes/concepts/workflow.md)
- [Agent vs workflow](notes/concepts/agent-vs-workflow.md)
- [Tool use](notes/concepts/tool-use.md)
- [Memory](notes/concepts/memory.md)
- [Protocols and interoperability](notes/concepts/protocols-and-interoperability.md)
- [Evals](notes/concepts/evals.md)
- [Risks](notes/concepts/risks.md)

Не обязательно читать все memory-подстраницы сразу. Их лучше открывать, когда встречаются конкретные вопросы про context window, session state, RAG, long-term memory, skill library or audit trail.

## 3. Landscape: карта экосистемы

После concepts переходи в [Landscape](landscape/README.md).

Цель этапа: понять, какие классы инструментов и продуктов существуют вокруг AI agents.

Порядок:

1. [Фреймворки, стандарты и продуктовый ландшафт](landscape/frameworks-and-standards.md)
2. [Landscape comparison](landscape/comparison.md)

Landscape нужно читать до sources, потому что он дает полки: SDK, orchestration, protocols, runtime, evals, coding agents, product categories.

## 4. Sources: доказательная база

После landscape переходи в [Sources](sources/README.md).

Цель этапа: читать первичные материалы уже с картой в голове.

Начальный маршрут:

1. [Anthropic: Building effective agents](sources/anthropic-building-effective-agents.md)
2. [ReAct paper](sources/react-paper.md)
3. [OpenAI Responses API and tools](sources/openai-responses-tools.md)
4. [Model Context Protocol architecture](sources/mcp-architecture.md)
5. [Agent2Agent Protocol](sources/a2a-protocol.md)
6. [OpenAI Agents SDK](sources/openai-agents-sdk.md)
7. [LangGraph documentation](sources/langgraph-docs.md)

Потом выбирать ветку:

- platform/product: [AgentKit](sources/openai-agentkit.md), [Agent Builder](sources/openai-agent-builder.md)
- memory/research: [Generative Agents](sources/generative-agents-paper.md), [Voyager](sources/voyager-paper.md)
- multi-agent: [AutoGen](sources/autogen-docs.md), [CrewAI](sources/crewai-agents-docs.md)
- coding agents and evals: [Claude Code](sources/claude-code.md), [SWE-agent](sources/swe-agent-paper.md), [SWE-bench](sources/swe-bench-paper.md), [AgentBench](sources/agentbench-paper.md)

## 5. Drafts: связный текст

После sources переходи к [Drafts](drafts/README.md).

Главный черновик:

- [What are AI agents?](drafts/what-are-ai-agents.md)

Цель этапа: собрать отдельные заметки и источники в связное понимание.

## 6. Roadmap: план развития проекта

[Roadmap](roadmap.md) — это не основной маршрут чтения, а план дальнейшего наполнения базы. К нему стоит возвращаться, когда решаем, какие разделы расширять дальше.
