<p align="center">
  <a href="https://trendshift.io/repositories/12800">
    <img src="assets/TRENDING-BADGE.png" alt="Trending Badge" style="width: 250px; height: 55px;" width="250" height="55"/>
  </a>
</p>

<p align="center">
  <img src="assets/ai-eng-hub.gif" alt="AI Engineering Hub Banner">
</p>

---

# AI Engineering Hub

Русифицированный форк [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub) с упором на понятную навигацию для русскоязычной аудитории.

Внутри собраны практические проекты по `LLM`, `RAG`, агентам, `MCP`, мультимодальным сценариям, OCR, голосовым интерфейсам, fine-tuning и прикладным AI-системам.

## Что Здесь Есть

- проекты для быстрого старта
- local-first сценарии с open-weight моделями
- примеры RAG разной сложности
- агентные и multi-agent пайплайны
- проекты по `MCP`
- сравнение моделей, evaluation и observability
- более сложные инженерные и исследовательские проекты

## Для Кого Этот Форк

- для разработчиков, которым нужны рабочие примеры, а не только теория
- для тех, кто хочет зайти в AI engineering через конкретные проекты
- для тех, кто ищет local-first и практический маршрут
- для русскоязычной аудитории, которой удобнее стартовать с понятной навигацией

## С Чего Начать

Если открываешь репозиторий впервые, сначала смотри:

- [START_HERE_RU.md](./START_HERE_RU.md)
- [TOP_PROJECTS_RU.md](./TOP_PROJECTS_RU.md)
- [PROJECT_INDEX_RU.md](./PROJECT_INDEX_RU.md)
- [RU_ALTERNATIVES.md](./RU_ALTERNATIVES.md)
- [PROJECT_CARD_TEMPLATE_RU.md](./PROJECT_CARD_TEMPLATE_RU.md)

Там собраны короткие маршруты по задачам и уровню входа.

## Быстрые Маршруты

### Первый Результат За Вечер

- [**simple-rag-workflow**](./simple-rag-workflow)
- [**document-chat-rag**](./document-chat-rag)
- [**local-chatgpt**](./local-chatgpt)
- [**llama-ocr**](./llama-ocr)
- [**streaming-ai-chatbot**](./streaming-ai-chatbot)

### Local-First

- [**simple-rag-workflow**](./simple-rag-workflow)
- [**github-rag**](./github-rag)
- [**llama-ocr**](./llama-ocr)
- [**gemma3-ocr**](./gemma3-ocr)
- [**qwen-2.5VL-ocr**](./qwen-2.5VL-ocr)

### RAG

- [**document-chat-rag**](./document-chat-rag)
- [**agentic_rag**](./agentic_rag)
- [**trustworthy-rag**](./trustworthy-rag)
- [**notebook-lm-clone**](./notebook-lm-clone)

### Агенты

- [**agentic_rag**](./agentic_rag)
- [**zep-memory-assistant**](./zep-memory-assistant)
- [**agent-with-mcp-memory**](./agent-with-mcp-memory)
- [**content_planner_flow**](./content_planner_flow)
- [**book-writer-flow**](./book-writer-flow)

### MCP

- [**cursor_linkup_mcp**](./cursor_linkup_mcp)
- [**llamaindex-mcp**](./llamaindex-mcp)
- [**mcp-agentic-rag**](./mcp-agentic-rag)
- [**mcp-voice-agent**](./mcp-voice-agent)
- [**mindsdb-mcp**](./mindsdb-mcp)

### Более Сложные Проекты

- [**DeepSeek-finetuning**](./DeepSeek-finetuning)
- [**Build-reasoning-model**](./Build-reasoning-model)
- [**Multi-Agent-deep-researcher-mcp-windows-linux**](./Multi-Agent-deep-researcher-mcp-windows-linux)
- [**context-engineering-workflow**](./context-engineering-workflow)
- [**notebook-lm-clone**](./notebook-lm-clone)

## Навигация По Каталогу

### Базовый Уровень

Здесь удобно начинать с:

- OCR и vision
- локальных чат-интерфейсов
- простого RAG
- небольших приложений с быстрым визуальным результатом

Хорошие стартовые папки:

- [**LaTeX-OCR-with-Llama**](./LaTeX-OCR-with-Llama)
- [**llama-ocr**](./llama-ocr)
- [**local-chatgpt**](./local-chatgpt)
- [**simple-rag-workflow**](./simple-rag-workflow)
- [**document-chat-rag**](./document-chat-rag)

### Средний Уровень

Здесь начинаются более составные системы:

- RAG с маршрутизацией и fallback-логикой
- агентные сценарии
- голос и аудио
- мультимодальные пайплайны
- `MCP` и работа с инструментами

Полезные папки:

- [**agentic_rag**](./agentic_rag)
- [**agentic_rag_deepseek**](./agentic_rag_deepseek)
- [**audio-analysis-toolkit**](./audio-analysis-toolkit)
- [**cursor_linkup_mcp**](./cursor_linkup_mcp)
- [**mcp-agentic-rag**](./mcp-agentic-rag)
- [**motia-content-creation**](./motia-content-creation)

### Продвинутый Уровень

Этот слой уже ближе к исследовательским и production-задачам:

- fine-tuning
- reasoning-модели
- глубокие research workflows
- document pipelines
- инфраструктурные `MCP`-проекты

Полезные папки:

- [**DeepSeek-finetuning**](./DeepSeek-finetuning)
- [**Build-reasoning-model**](./Build-reasoning-model)
- [**documentation-writer-flow**](./documentation-writer-flow)
- [**context-engineering-workflow**](./context-engineering-workflow)
- [**graphiti-mcp**](./graphiti-mcp)
- [**groundX-doc-pipeline**](./groundX-doc-pipeline)

## Как Лучше Использовать Этот Репозиторий

1. Выбери одно направление, а не десять сразу.
2. Доведи один проект до результата.
3. Только потом переходи к соседней теме.
4. Если нужен локальный путь, начинай с `Ollama`-дружественных и local-first проектов.
5. Если интересуют агенты, сначала разберись с обычным RAG и работой с инструментами.

## Лицензия

Репозиторий распространяется под лицензией [MIT](./LICENSE).

## Credits

- Original repository: [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub)
- В этом форке сохранена структура исходного каталога и добавлена русскоязычная навигация.