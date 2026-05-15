# AI Engineering Hub RU

Русскоязычная редакторская версия каталога [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub) для практиков, разработчиков и вайбкодеров.

Это не просто форк с переводом README. Задача этой версии — убрать перегрузку от большого каталога и помочь быстро понять:

- что запускать первым
- что реально даёт быстрый результат
- что можно поднять локально
- где проект дорогой, хрупкий или переусложнённый
- чем заменить сервисы и стек под более практичный RU-friendly сценарий

## Что Это За Репозиторий

В основе лежит большой каталог проектов по:

- `LLMs`
- `RAG`
- `AI agents`
- `MCP`
- fine-tuning
- production-style AI apps

Но для большинства людей проблема не в нехватке ссылок. Проблема в навигации. Когда в репозитории десятки папок, непонятно, что открывать сегодня и что вообще стоит твоего времени.

Эта редакция решает именно это.

## Для Кого

- Для вайбкодеров, которым нужен быстрый визуальный или прикладной результат.
- Для Python и JS разработчиков, которые хотят зайти в AI engineering через рабочие проекты, а не через бесконечную теорию.
- Для людей, которые хотят local-first путь: `Ollama`, open-weight models, локальные векторные базы, минимум лишнего облака.
- Для тех, кто хочет собрать полезные штуки под реальные сценарии: document chat, OCR, research assistants, code agents, MCP integrations.

## С Чего Начать

Если ты здесь впервые, иди по такому маршруту:

1. Открой [CURATED_COLLECTIONS.md](./CURATED_COLLECTIONS.md).
2. Выбери не модель, а цель: RAG, OCR, локальный чат, агенты, MCP.
3. Возьми один проект, который можно довести до результата за вечер.
4. После первого запуска добавь к нему нормальную русскую карточку по [PROJECT_CARD_TEMPLATE.md](./PROJECT_CARD_TEMPLATE.md).

## Быстрые Маршруты

### Хочу Что-То Запустить Уже Сегодня

- [simple-rag-workflow](./simple-rag-workflow)
- [document-chat-rag](./document-chat-rag)
- [local-chatgpt](./local-chatgpt)
- [llama-ocr](./llama-ocr)
- [streaming-ai-chatbot](./streaming-ai-chatbot)

### Хочу Local-First И Без Лишней Боли

- [llama-ocr](./llama-ocr)
- [gemma3-ocr](./gemma3-ocr)
- [qwen-2.5VL-ocr](./qwen-2.5VL-ocr)
- [simple-rag-workflow](./simple-rag-workflow)
- [github-rag](./github-rag)

### Хочу Агентов И Workflow-Автоматизацию

- [agentic_rag](./agentic_rag)
- [zep-memory-assistant](./zep-memory-assistant)
- [agent-with-mcp-memory](./agent-with-mcp-memory)
- [content_planner_flow](./content_planner_flow)
- [motia-content-creation](./motia-content-creation)

### Хочу Разобраться С MCP

- [cursor_linkup_mcp](./cursor_linkup_mcp)
- [llamaindex-mcp](./llamaindex-mcp)
- [mcp-agentic-rag](./mcp-agentic-rag)
- [mcp-agentic-rag-firecrawl](./mcp-agentic-rag-firecrawl)
- [mcp-voice-agent](./mcp-voice-agent)

## Навигация По Этой Редакции

- [CURATED_COLLECTIONS.md](./CURATED_COLLECTIONS.md) — подборки проектов по целям и типу пользы.
- [PROJECT_CARD_TEMPLATE.md](./PROJECT_CARD_TEMPLATE.md) — шаблон карточки проекта для RU-аудитории.
- [POSITIONING.md](./POSITIONING.md) — позиционирование и готовые тексты для GitHub, Telegram и X.
- [UPSTREAM_README.md](./UPSTREAM_README.md) — ссылки на исходный англоязычный каталог и апстрим.

## Редакционные Принципы

- Не делать ещё один link dump.
- Не продвигать проект без объяснения, зачем он нужен.
- Всегда отмечать сложность, стоимость и реальную вероятность быстрого запуска.
- Для дорогих, нестабильных или region-sensitive проектов явно указывать ограничения.
- По возможности давать local-first и open-source substitute path.

## Что Дальше Имеет Смысл Сделать

Следующий сильный шаг для этого форка — не добавлять ещё больше ссылок, а подробно оформить 10–15 flagship projects:

- короткое описание по-русски
- кому подходит
- что получится за один вечер
- что может сломаться
- чем заменить стек под более практичный сценарий

Когда это появится, репозиторий начнёт выглядеть не как копия, а как самостоятельная полезная редакция.

## Credits

- Original repository: [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub)
- This fork keeps the original project structure and adds a Russian editorial navigation layer on top.