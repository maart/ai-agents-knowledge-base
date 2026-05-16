[К разделу Источники](README.md)

# Источник: Agent2Agent Protocol

## Метаданные

- URL: https://agent2agent.info/en/docs/
- Связанное объявление: https://s24.q4cdn.com/538403808/files/doc_news/Linux-Foundation-Launches-the-Agent2Agent-Protocol-Project-to-Enable-Secure-Intelligent-Communication-Between-AI-Agents-2025.pdf
- Дата доступа: 2026-05-16
- Тип: docs / protocol
- Автор / организация: Google, Linux Foundation и [A2A](../notes/concepts/protocols-and-interoperability.md) community
- Год: 2025-2026

## Главная идея

Agent2Agent (A2A) — открытый протокол для коммуникации и совместимости (interoperability) между AI [agents](../notes/concepts/agent.md) в разных системах и фреймворках. Если MCP фокусируется на подключении AI-приложений к tools и context, то A2A фокусируется на коммуникации agent-to-agent.

## Значение для AI agents

- Добавляет слой совместимости (interoperability) за пределами single-agent [tool use](../notes/concepts/tool-use.md).
- Полезен для [multi-agent](../notes/concepts/multi-agent.md) systems, которые пересекают границы приложений или организаций.
- Важное различие: MCP соединяет agents с tools/resources, а A2A соединяет agents с другими agents.

## Заметки

- Рассматривать A2A как часть ландшафта протоколов (protocol landscape), а не как замену MCP.
- Особенно важен, когда agents должны находить друг друга, обмениваться задачами, делиться artifacts или координироваться между фреймворками.

## Надежность и ограничения

- Официальная документация community и объявление Linux Foundation.
- Зрелость экосистемы и adoption нужно отслеживать отдельно от амбиций протокола.

## Вопросы для продолжения

- Какая модель доверия (модель доверия (trust model)) нужна для коммуникации agent-to-agent?
- Как agents должны представлять возможности (capabilities), tasks, artifacts и identity между организациями?
