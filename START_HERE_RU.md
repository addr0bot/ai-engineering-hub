# С Чего Начать

Этот файл нужен для тех, кто открыл репозиторий впервые и не хочет теряться в десятках папок.

## Если Нужен Первый Результат Быстро

### Вариант 1: Понять Базовый RAG

Открой:

- [simple-rag-workflow](./simple-rag-workflow)

Что даст:

- понимание базовой схемы `retrieval -> context -> answer`
- знакомство с `LlamaIndex`
- локальный сценарий через `Ollama`

### Вариант 2: Сделать Чат С Документами

Открой:

- [document-chat-rag](./document-chat-rag)

Что даст:

- более прикладной RAG-сценарий
- работу с файлами вместо абстрактного примера

### Вариант 3: Собрать Локальный OCR

Открой:

- [llama-ocr](./llama-ocr)
- [gemma3-ocr](./gemma3-ocr)

Что даст:

- понятный визуальный результат
- хороший вход в мультимодальные сценарии

## Если Нужен Local-First Путь

Смотри сначала эти проекты:

- [llama-ocr](./llama-ocr)
- [gemma3-ocr](./gemma3-ocr)
- [qwen-2.5VL-ocr](./qwen-2.5VL-ocr)
- [simple-rag-workflow](./simple-rag-workflow)
- [github-rag](./github-rag)

Почему именно они:

- их проще запускать локально
- они дают понятный результат без сложной инфраструктуры
- они подходят для первого знакомства с open-weight моделями

## Если Интересуют Агенты

Начинай отсюда:

- [agentic_rag](./agentic_rag)
- [zep-memory-assistant](./zep-memory-assistant)
- [agent-with-mcp-memory](./agent-with-mcp-memory)

Что смотреть по ходу:

- как устроены инструменты
- как агент ходит за контекстом
- как подключается память
- где заканчивается обычный чат и начинается оркестрация

После этого можно переходить к:

- [book-writer-flow](./book-writer-flow)
- [content_planner_flow](./content_planner_flow)
- [motia-content-creation](./motia-content-creation)

## Если Интересует MCP

Хороший маршрут такой:

1. [cursor_linkup_mcp](./cursor_linkup_mcp)
2. [llamaindex-mcp](./llamaindex-mcp)
3. [mcp-agentic-rag](./mcp-agentic-rag)
4. [mcp-voice-agent](./mcp-voice-agent)

Задача этого маршрута:

- сначала понять базовую пользу MCP
- потом посмотреть интеграцию с локальными и агентными сценариями
- затем перейти к более сложным примерам

## Если Нужен Более Серьезный RAG

После стартовых проектов переходи сюда:

- [agentic_rag](./agentic_rag)
- [rag-sql-router](./rag-sql-router)
- [trustworthy-rag](./trustworthy-rag)
- [notebook-lm-clone](./notebook-lm-clone)

Это уже не просто базовые демо, а более практичные сценарии с маршрутизацией, надежностью и более продуктовым интерфейсом.

## Если Хочется Углубиться В Модели

Смотри:

- [DeepSeek-finetuning](./DeepSeek-finetuning)
- [Build-reasoning-model](./Build-reasoning-model)
- [ai-engineering-roadmap](./ai-engineering-roadmap)

Это уже не стартовые проекты. Их лучше открывать после того, как ты уже запускал прикладные приложения из репозитория.

## Рекомендуемый Порядок

Если нужен спокойный и понятный путь, бери такой:

1. `simple-rag-workflow`
2. `document-chat-rag`
3. `llama-ocr`
4. `agentic_rag`
5. `cursor_linkup_mcp`
6. `trustworthy-rag` или `notebook-lm-clone`

Такой порядок даёт нормальную прогрессию:

- от простого к составному
- от локальных сценариев к агентным
- от демо к более серьезным системам

## Что Не Стоит Делать Сразу

- Не открывай десять проектов подряд.
- Не начинай с fine-tuning, если еще не запускал базовый RAG.
- Не прыгай сразу в MCP только потому, что тема популярна.
- Не пытайся оценивать весь репозиторий за один вечер.

Лучше довести один проект до рабочего состояния, чем поверхностно посмотреть двадцать.