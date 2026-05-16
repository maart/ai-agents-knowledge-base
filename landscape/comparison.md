[На главную](../README.md)

# Landscape comparison

Стартовая сравнительная таблица. Она не заменяет глубокий анализ, а помогает быстро увидеть роли разных элементов экосистемы.

| Item | Type | Main idea | Useful for | Limitations / questions | Source |
| --- | --- | --- | --- | --- | --- |
| OpenAI Agents SDK | SDK / orchestration | Agents, tools, guardrails, handoffs, sessions and tracing | Building agentic apps around OpenAI models | Vendor-specific surface; compare with framework-neutral patterns | [source](../sources/openai-agents-sdk.md) |
| OpenAI Responses API | API | Stateful model responses with custom and built-in tools | Tool use, MCP, web/file search, computer use | Product surface changes quickly | [source](../sources/openai-responses-tools.md) |
| MCP | Protocol | Standard connection layer for tools, resources and prompts | Reusable external capabilities across clients | Security, permissions and trust boundaries need careful design | [source](../sources/mcp-architecture.md) |
| LangGraph | Framework | Stateful graph orchestration for agents/workflows | Durable workflows, human review, controlled agent loops | More structure than simple prototypes need | [source](../sources/langgraph-docs.md) |
| AutoGen | Framework | Multi-agent applications and agent communication | Studying coordination and conversational agents | Coordination can add complexity and hidden failure modes | [source](../sources/autogen-docs.md) |
| CrewAI | Framework | Role-based agents, crews, tasks and delegation | Applied multi-agent business automation | Team metaphor needs evaluation against real outcomes | [source](../sources/crewai-agents-docs.md) |
| ReAct | Research pattern | Alternates reasoning, action and observation | Understanding the agent loop | Prompt pattern, not full production architecture | [source](../sources/react-paper.md) |
| Toolformer | Research paper | Models learn when/how to call APIs | History of learned tool use | Older model setting; not full orchestration | [source](../sources/toolformer-paper.md) |
| Voyager | Research agent | LLM agent with skill library in Minecraft | Memory as reusable executable skills | Simulated environment limits transfer | [source](../sources/voyager-paper.md) |
| SWE-agent | Research / tool | Coding agent with an agent-computer interface | Software engineering agents | Domain-specific; depends on environment quality | [source](../sources/swe-agent-paper.md) |
| SWE-bench | Benchmark | Real GitHub issues as executable tasks | Evaluating coding agents | Tests do not capture all product quality | [source](../sources/swe-bench-paper.md) |
| AgentBench | Benchmark | Multi-environment agent evaluation | Comparing agent behavior across domains | Benchmark environments may differ from production | [source](../sources/agentbench-paper.md) |
