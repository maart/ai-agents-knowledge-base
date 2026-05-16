[К разделу Landscape](README.md)

# Landscape comparison

Эта таблица помогает быстро сравнить элементы экосистемы. Читать ее лучше после [объясняющей карты ландшафта](frameworks-and-standards.md).

| Layer | Item | Type | Main idea | Useful for | Limitations / questions | Source |
| --- | --- | --- | --- | --- | --- | --- |
| [Model/API](../01-glossary.md#modelapi-layer) | OpenAI Responses API | API | Stateful model responses with custom and built-in tools | Tool use, MCP, web/file search, computer use | Product surface changes quickly | [source](../sources/openai-responses-tools.md) |
| [SDK/orchestration](../01-glossary.md#sdk-and-orchestration) | OpenAI Agents SDK | SDK / orchestration | Agents, tools, guardrails, handoffs, sessions and tracing | Building agentic apps around OpenAI models | Vendor-specific surface; compare with framework-neutral patterns | [source](../sources/openai-agents-sdk.md) |
| [Platform](../01-glossary.md#visual-builders-and-agent-platforms) | OpenAI AgentKit | Platform | Builder, ChatKit, connectors and evals for agent products | End-to-end agent product development | Product bundle may hide architectural tradeoffs | [source](../sources/openai-agentkit.md) |
| [Platform](../01-glossary.md#visual-builders-and-agent-platforms) | OpenAI Agent Builder | Visual builder | Visual canvas for agent workflows | Designing, testing and versioning agent workflows | Visual abstraction may not fit complex code-first systems | [source](../sources/openai-agent-builder.md) |
| Protocol | MCP | Protocol | Standard connection layer for tools, resources and prompts | Reusable external capabilities across clients | Security, permissions and trust boundaries need careful design | [source](../sources/mcp-architecture.md) |
| Protocol | A2A | Protocol | Agent-to-agent communication and interoperability | Cross-framework or cross-organization agent coordination | Adoption and trust model are still key questions | [source](../sources/a2a-protocol.md) |
| [SDK/orchestration](../01-glossary.md#sdk-and-orchestration) | LangGraph | Framework | Stateful graph orchestration for agents/workflows | Durable workflows, human review, controlled agent loops | More structure than simple prototypes need | [source](../sources/langgraph-docs.md) |
| Multi-agent framework | AutoGen | Framework | Multi-agent applications and agent communication | Studying coordination and conversational agents | Coordination can add complexity and hidden failure modes | [source](../sources/autogen-docs.md) |
| Multi-agent framework | CrewAI | Framework | Role-based agents, crews, tasks and delegation | Applied multi-agent business automation | Team metaphor needs evaluation against real outcomes | [source](../sources/crewai-agents-docs.md) |
| Product category | Claude Code | Coding agent | Agentic coding system that reads, edits and tests codebases | Production coding-agent patterns | Vendor-specific; evaluate against independent benchmarks | [source](../sources/claude-code.md) |
| Research pattern | ReAct | Research pattern | Alternates reasoning, action and observation | Understanding the agent loop | Prompt pattern, not full production architecture | [source](../sources/react-paper.md) |
| Research pattern | Toolformer | Research paper | Models learn when/how to call APIs | History of learned tool use | Older model setting; not full orchestration | [source](../sources/toolformer-paper.md) |
| Research agent | Voyager | Research agent | LLM agent with skill library in Minecraft | Memory as reusable executable skills | Simulated environment limits transfer | [source](../sources/voyager-paper.md) |
| Research agent | Generative Agents | Research paper | Memory, reflection and planning in simulated agents | Studying persistent behavior and memory architecture | Simulation differs from tool-use production systems | [source](../sources/generative-agents-paper.md) |
| Benchmark/tool | SWE-agent | Research / tool | Coding agent with an agent-computer interface | Software engineering agents | Domain-specific; depends on environment quality | [source](../sources/swe-agent-paper.md) |
| Benchmark | SWE-bench | Benchmark | Real GitHub issues as executable tasks | Evaluating coding agents | Tests do not capture all product quality | [source](../sources/swe-bench-paper.md) |
| Benchmark | AgentBench | Benchmark | Multi-environment agent evaluation | Comparing agent behavior across domains | Benchmark environments may differ from production | [source](../sources/agentbench-paper.md) |

## Как пользоваться таблицей

Не сравнивай все со всем. Сначала выбери layer:

- если нужен control flow, смотри [SDK/orchestration](../01-glossary.md#sdk-and-orchestration);
- если нужны integrations, смотри protocols/connectors;
- если нужна product assembly, смотри [platforms](../01-glossary.md#visual-builders-and-agent-platforms);
- если нужна проверка качества, смотри benchmarks/evals;
- если нужен прикладной пример, смотри product categories.

После выбора layer возвращайся к карточкам источников в [Sources](../sources/README.md).
