[К разделу Sources](README.md)

# Source: Voyager: An Open-Ended Embodied Agent with Large Language Models

## Metadata

- URL: https://arxiv.org/abs/2305.16291
- Project: https://voyager.minedojo.org/
- Accessed: 2026-05-16
- Type: paper
- Author / organization: Guanzhi Wang et al.
- Year: 2023

## Main idea

Voyager is an LLM-powered Minecraft [agent](../notes/concepts/agent.md) that explores an environment, writes executable skills, stores them in a [skill library](../notes/concepts/skill-library.md) and reuses them for future tasks.

## Relevance to AI agents

- Strong example of agent [memory](../notes/concepts/memory.md) as reusable skills, not just stored text.
- Shows environment feedback, execution errors and self-verification as part of agent learning.
- Useful for understanding embodied and open-ended agents.

## Notes

- The Minecraft environment makes feedback concrete and measurable.
- Skill libraries are a useful lens for long-term agent capability growth.

## Reliability and limitations

- Research paper and open-source project.
- Environment is simulated and structured; conclusions may not transfer directly to messy business [workflows](../notes/concepts/workflow.md).

## Follow-up questions

- How can skill libraries translate to non-game domains?
- What should count as agent learning if model weights do not change?
