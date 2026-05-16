[К study guide](../study-guide.md)

# Landscape

Landscape — это карта экосистемы вокруг AI [agents](../notes/concepts/agent.md). Этот раздел не про глубокое чтение источников, а про ориентацию: какие классы инструментов существуют, зачем они нужны и где искать подробности.

Читать после [Concepts](../notes/concepts/README.md) и перед [Sources](../sources/README.md).

## Зачем нужен этот раздел

После concepts обычно понятно, что такое [agent](../notes/concepts/agent.md), [workflow](../notes/concepts/workflow.md), [tool use](../notes/concepts/tool-use.md), [memory](../notes/concepts/memory.md) and [evals](../notes/concepts/evals.md). Но еще непонятно, как это превращается в реальный рынок и инженерную практику.

Landscape отвечает на вопросы:

- какие слои есть в agent ecosystem;
- чем SDK отличается от platform;
- где место protocols вроде [MCP](../notes/concepts/protocols-and-interoperability.md) и [A2A](../notes/concepts/protocols-and-interoperability.md);
- почему runtime и observability важны не меньше модели;
- какие product categories уже видны.

## Карта слоев

```text
Model/API layer
  -> SDK and orchestration
  -> Visual builders and agent platforms
  -> Protocols and connectors
  -> Runtime and execution environments
  -> Observability, evals and safety
  -> Product categories
```

## Как читать

1. [Фреймворки, стандарты и продуктовый ландшафт](frameworks-and-standards.md)

   Главная объясняющая страница. Читать сначала: она раскладывает экосистему по слоям и объясняет, зачем каждый слой нужен.

2. [Landscape comparison](comparison.md)

   Сравнительная таблица. Читать после объясняющей страницы, когда хочется быстро сопоставить конкретные инструменты, papers and benchmarks.

## Что читать после Landscape

Дальше переходи в [Sources](../sources/README.md). Там первичные материалы уже упорядочены так, чтобы не прыгать сразу в самые сложные papers без контекста.
