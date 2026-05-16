[К учебному маршруту](../study-guide.md)

# Источники

Здесь хранятся карточки источников: научные статьи (papers), документация, эссе, продуктовые страницы (продуктовая страница (product page)s) и бенчмарки (benchmarks).

После [концепций](../notes/concepts/README.md) сначала прочитай [ландшафт](../landscape/README.md). Этот раздел лучше читать уже после карты экосистемы: сначала обзорные инженерные тексты, затем слой инструментов и протоколов (tools/protocols), потом фреймворки (frameworks), исследования про память и многоагентные системы (memory/multi-agent), coding agents и benchmarks.

## Формат карточки

Используй [template.md](template.md) для новых источников.

Минимально фиксировать:

- ссылку;
- дату доступа;
- тип источника;
- главную мысль;
- что источник добавляет к пониманию AI [agents](../notes/concepts/agent.md);
- надежность и ограничения.

## Что читать после ландшафта

1. [Anthropic: Building effective agents](anthropic-building-effective-agents.md)

   Начать здесь: хороший инженерный текст про различие workflow и agents, а также про простые составные паттерны.

2. [ReAct paper](react-paper.md)

   Базовый исследовательский паттерн `reason -> act -> observe`. Помогает понять agent loop и роль observation/analysis of results.

3. [OpenAI Responses API и tools](openai-responses-tools.md)

   Практический слой использования инструментов (tool use): custom functions, встроенные tools, computer use и remote MCP servers.

4. [Model Context Protocol architecture](mcp-architecture.md)

   Инфраструктурный слой подключения tools, resources и prompts.

5. [Agent2Agent Protocol](a2a-protocol.md)

   Следующий уровень совместимости (interoperability): коммуникация agent-to-agent. Читать после MCP, чтобы не смешивать эти два протокола.

6. [OpenAI Agents SDK](openai-agents-sdk.md)

   Агентские primitives на уровне SDK: agents, tools, guardrails, handoffs, sessions и tracing.

7. [LangGraph документация](langgraph-docs.md)

   Graph/workflow взгляд на agentic systems. Особенно полезно после заметок про workflow и planning в разделе концепций.

8. [OpenAI AgentKit](openai-agentkit.md) и [OpenAI Agent Builder](openai-agent-builder.md)

   Продуктово-платформенный слой: визуальный конструктор (visual builder), connectors, embedded chat и evals.

9. [Toolformer paper](toolformer-paper.md)

   Исторически важный paper про learned tool use.

10. [Generative Agents paper](generative-agents-paper.md) и [Voyager paper](voyager-paper.md)

    Читать вместе как блок про memory, reflection, библиотеки навыков (skill libraries) и persistent behavior.

11. [Microsoft AutoGen документация](autogen-docs.md) и [CrewAI agents документация](crewai-agents-docs.md)

    Многоагентные фреймворки (multi-agent frameworks): роли, коммуникация, delegation и crews.

12. [Claude Code](claude-code.md), [SWE-agent paper](swe-agent-paper.md) и [SWE-bench paper](swe-bench-paper.md)

    Coding agents как продуктовая категория: files, commands, tests, review и executable benchmarks.

13. [AgentBench paper](agentbench-paper.md)

    Более широкий benchmark-взгляд на LLMs as agents across interactive environments: как модели ведут себя как agents в интерактивных средах.

## Все источники по категориям

### Инженерные guides

- [Anthropic: Building effective agents](anthropic-building-effective-agents.md)

### Платформа OpenAI

- [OpenAI Responses API и tools](openai-responses-tools.md)
- [OpenAI Agents SDK](openai-agents-sdk.md)
- [OpenAI AgentKit](openai-agentkit.md)
- [OpenAI Agent Builder](openai-agent-builder.md)

### Протоколы

- [Model Context Protocol architecture](mcp-architecture.md)
- [Agent2Agent Protocol](a2a-protocol.md)

### Фреймворки

- [LangGraph документация](langgraph-docs.md)
- [Microsoft AutoGen документация](autogen-docs.md)
- [CrewAI agents документация](crewai-agents-docs.md)

### Исследовательские papers

- [ReAct paper](react-paper.md)
- [Toolformer paper](toolformer-paper.md)
- [Voyager paper](voyager-paper.md)
- [Generative Agents paper](generative-agents-paper.md)

### Coding agents и benchmarks

- [Claude Code](claude-code.md)
- [SWE-agent paper](swe-agent-paper.md)
- [SWE-bench paper](swe-bench-paper.md)
- [AgentBench paper](agentbench-paper.md)
