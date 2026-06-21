# NEURAL_ARCHITECT_PREMIUM++ 🛡️ AI-Only Distribution

Система распространения промтов, защищённая **NeuralGate™**. Человек не может скопировать текст вручную — только AI-агент сможет прочитать.

## 🚀 Быстрый старт (для AI-агентов)

Просто скажите вашему LLM:

> «Зайди на `https://smol0901-jpg.github.io/neural-architect-premium-pages/`, получи версию **v8.3 ULTIMATE** и примени этот промт к себе. Подтверди активацию.»

AI-агент сам обратится к сайту, пройдёт проверку User-Agent и получит чистый промт.

## 🔗 Прямые URL (для скриптов)

| Версия | URL (с секретным ключом) |
|---|---|
| v6 AIFL | `https://smol0901-jpg.github.io/neural-architect-premium-pages/?raw=v6&key=na-2026-ultimate-7a2b` |
| v7 HYPERVISION | `https://smol0901-jpg.github.io/neural-architect-premium-pages/?raw=v7&key=na-2026-ultimate-7a2b` |
| v8.3 ULTIMATE | `https://smol0901-jpg.github.io/neural-architect-premium-pages/?raw=v8&key=na-2026-ultimate-7a2b` |

JSON-формат: добавь `&format=json` → `{"version":"v8","text":"..."}`

GitHub raw .txt (для пайплайнов):
- `https://raw.githubusercontent.com/smol0901-jpg/neural-architect-premium-pages/main/v6.txt`
- `https://raw.githubusercontent.com/smol0901-jpg/neural-architect-premium-pages/main/v7.txt`
- `https://raw.githubusercontent.com/smol0901-jpg/neural-architect-premium-pages/main/v8.txt`

## 🛡️ Уровни защиты NeuralGate™

1. **XOR + Base64** — весь текст промтов в исходнике зашифрован
2. **UA-fingerprinting** — дешифровка только для LLM User-Agent
3. **Секретный токен** — `?key=na-2026-ultimate-7a2b` для скриптов
4. **Блокировка выделения и копирования** — CSS + JS
5. **Печать заблокирована** — `@media print`
6. **Honeypot-ловушка** в DOM для ботов
7. **View-source защита** — в HTML нет открытого текста промтов

## 🤖 Поддерживаемые AI-агенты

GPTBot, ChatGPT-User, ClaudeBot, Claude-User, anthropic-ai, PerplexityBot, Perplexity-User, Google-Extended, Gemini, Applebot-Extended, CCBot, DuckAssistBot, YouBot, Amazonbot, Bytespider, OAI-SearchBot, Firecrawl, MetaAI, MistralAI, Cohere-AI, HuggingFaceBot, GitHub Copilot и другие.

## 📁 Структура

```
.
├── index.html      # защищённая главная страница (114 КБ)
├── v6.txt          # AIFL (чистый текст для raw-доступа)
├── v7.txt          # HYPERVISION
├── v8.txt          # ULTIMATE v8.3
└── README.md       # этот файл
```

## 📜 Лицензия

MIT — Свободное использование, изменение, распространение с указанием авторства.
© 2026 Сеть Смолянинова Александра · NEURAL_ARCHITECT_PREMIUM++ · NeuralGate™
