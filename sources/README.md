[К study guide](../study-guide.md)

# Sources

Здесь хранятся карточки источников: papers, documentation, essays, product pages, benchmarks.

После [Concepts](../notes/concepts/README.md) сначала прочитай [Landscape](../landscape/README.md). Этот раздел лучше читать уже после карты экосистемы: сначала обзорные инженерные тексты, затем tool/protocol layer, потом frameworks, memory/multi-agent research, coding agents и benchmarks.

## Формат карточки

Используй [template.md](template.md) для новых источников.

Минимально фиксировать:

- ссылку;
- дату доступа;
- тип источника;
- главную мысль;
- что источник добавляет к пониманию AI [agents](../notes/concepts/agent.md);
- надежность и ограничения.

## Что читать после Landscape

1. [Anthropic: Building effective agents](anthropic-building-effective-agents.md)

   Начать здесь: хороший инженерный текст про различие workflow и agents, а также про простые composable patterns.

2. [ReAct paper](react-paper.md)

   Базовый исследовательский паттерн reason -> act -> observe. Помогает понять agent loop и роль observations.

3. [OpenAI Responses API and tools](openai-responses-tools.md)

   Практический слой tool use: custom functions, built-in tools, computer use and remote MCP servers.

4. [Model Context Protocol architecture](mcp-architecture.md)

   Инфраструктурный слой подключения tools, resources and prompts.

5. [Agent2Agent Protocol](a2a-protocol.md)

   Следующий уровень interoperability: agent-to-agent communication. Читать после MCP, чтобы не смешивать эти два протокола.

6. [OpenAI Agents SDK](openai-agents-sdk.md)

   SDK-level agent primitives: agents, tools, guardrails, handoffs, sessions and tracing.

7. [LangGraph documentation](langgraph-docs.md)

   Graph/workflow view на agentic systems. Особенно полезно после concept notes про workflow и planning.

8. [OpenAI AgentKit](openai-agentkit.md) и [OpenAI Agent Builder](openai-agent-builder.md)

   Product/platform layer: visual builder, connectors, embedded chat and evals.

9. [Toolformer paper](toolformer-paper.md)

   Исторически важный paper про learned tool use.

10. [Generative Agents paper](generative-agents-paper.md) и [Voyager paper](voyager-paper.md)

    Читать вместе как блок про memory, reflection, skill libraries and persistent behavior.

11. [Microsoft AutoGen documentation](autogen-docs.md) и [CrewAI agents documentation](crewai-agents-docs.md)

    Multi-agent frameworks: роли, коммуникация, delegation, crews.

12. [Claude Code](claude-code.md), [SWE-agent paper](swe-agent-paper.md) и [SWE-bench paper](swe-bench-paper.md)

    Coding agents as production category: files, commands, tests, review and executable benchmarks.

13. [AgentBench paper](agentbench-paper.md)

    Более широкий benchmark взгляд на LLMs as agents across interactive environments.

## Все источники по категориям

### Engineering guides

- [Anthropic: Building effective agents](anthropic-building-effective-agents.md)

### OpenAI platform

- [OpenAI Responses API and tools](openai-responses-tools.md)
- [OpenAI Agents SDK](openai-agents-sdk.md)
- [OpenAI AgentKit](openai-agentkit.md)
- [OpenAI Agent Builder](openai-agent-builder.md)

### Protocols

- [Model Context Protocol architecture](mcp-architecture.md)
- [Agent2Agent Protocol](a2a-protocol.md)

### Frameworks

- [LangGraph documentation](langgraph-docs.md)
- [Microsoft AutoGen documentation](autogen-docs.md)
- [CrewAI agents documentation](crewai-agents-docs.md)

### Research papers

- [ReAct paper](react-paper.md)
- [Toolformer paper](toolformer-paper.md)
- [Voyager paper](voyager-paper.md)
- [Generative Agents paper](generative-agents-paper.md)

### Coding agents and benchmarks

- [Claude Code](claude-code.md)
- [SWE-agent paper](swe-agent-paper.md)
- [SWE-bench paper](swe-bench-paper.md)
- [AgentBench paper](agentbench-paper.md)
