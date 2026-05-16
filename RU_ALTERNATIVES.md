# RU Alternatives

Этот файл нужен для простой вещи: если в проекте используется дорогой, хрупкий или неудобный внешний сервис, чем его разумно заменить.

## Модели И API

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| `OpenAI API` | `Ollama` с open-weight моделями, `OpenRouter`, совместимые локальные inference servers |
| `Anthropic Claude` | `Qwen`, `Llama`, `DeepSeek`, `Gemma` через `Ollama` или другой local runtime |
| `Gemini` | `Qwen VL`, `Janus-Pro`, `Llama vision` при local-first сценарии |
| `Groq` | локальный inference, `OpenRouter` или обычный cloud inference без привязки к одному провайдеру |
| `SambaNova` | `Ollama`, `vLLM`, `LM Studio`, другой совместимый inference backend |

## Векторные Базы И Retrieval

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| `Pinecone` | `Qdrant` |
| `Weaviate Cloud` | `Qdrant`, `Chroma`, локальный `Weaviate` |
| `Milvus` | `Qdrant`, если нужен более простой local-first запуск |
| hosted retrieval stack | `LlamaIndex` + `Qdrant` / `Chroma` локально |

## Автоматизация И Оркестрация

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| `Zapier` | `n8n` |
| жёсткая cloud-only orchestration | локальный `Docker Compose`, `uv`, `Makefile`, простые scripts |
| browser-only manual ops | `Stagehand`, `Playwright`, `Browser Use`, если нужен кодовый сценарий |

## Voice, OCR, Multimodal

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| hosted speech stack | `Whisper`, `faster-whisper`, local TTS/STT tooling |
| hosted OCR | `Llama OCR`, `Gemma3 OCR`, `Qwen VL OCR` |
| облачная image generation | local image generation через open models |

## Память, Агенты, MCP

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| сложный memory SaaS | локальная база + простая memory layer |
| proprietary tooling around agents | `CrewAI`, `LangGraph`, `PydanticAI`, `smolagents`, `OpenAI Swarm`-style local patterns |
| MCP только через один IDE workflow | отдельный локальный `MCP server` + любой совместимый client |

## Деплой И Запуск

| Если в проекте стоит | Чем можно заменить |
| --- | --- |
| один конкретный cloud host | `Railway`, `Render`, `Fly.io`, `Docker`, VPS |
| сложный frontend hosting path | локальный запуск или простой container deploy |
| cloud notebook path | локальный `uv`, `venv`, `poetry`, `conda`, `Docker` |

## Практические Замены Для Этого Каталога

- Если проект интересен логикой, а не конкретным провайдером, сначала замени модель на ту, которую реально можешь поднять.
- Если проект использует дорогой hosted retrieval, сначала пробуй `Qdrant` или `Chroma`.
- Если проект упирается в браузерную автоматизацию, смотри на `Stagehand` или `Playwright`.
- Если проект строится вокруг API-ключей нескольких сервисов, сначала упрощай его до одной модели и одной базы.
- Если хочется не веб-приложение, а практический use case, часто разумно переносить сценарий в `Telegram bot`, внутренний tool или локальный desktop-like интерфейс.

## Главное Правило

Не переносить в форк зависимость от чужого стека как обязательную. Лучше показывать основной путь и рядом давать более доступную замену.