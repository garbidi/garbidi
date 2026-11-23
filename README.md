## Искандар Гафаров

### Python-разработчик · AI-инструменты и автоматизация

📍 Казань, Россия

Коммерческий опыт. Делаю системы, которые снимают с людей рутину: агенты
собирают данные из чужих API, считают и отдают результат в том виде, в каком его реально используют —
дашборд, таблица, сообщение в мессенджере.

Работаю с AI-инструментами разработки как с частью процесса: архитектурные
решения фиксирую в ADR, ход работы — в журнале сессий, чтобы проект можно было
передать и продолжить без потери контекста.

### Проекты

**[community-platform](https://github.com/garbidi/community-platform)** —
рабочая платформа бизнес-сообщества (потоки по 100+ участников): роли с
доступом на уровне данных, разборы созвонов (распознавание речи → выжимка
Claude → цели участника), финансы из Telegram-чата, автоматические посты
об оплатах, AI-помощник организаторов в Telegram с голосом.
`Python · FastAPI · SQLite FTS5 · Telethon · Claude API · faster-whisper · Docker`

**[kompas-finance](https://github.com/garbidi/kompas-finance)** — сервис
управленческого учёта: выписки из банка по API и в формате 1С, правила
автоматической разноски, ДДС и ОПиУ, миграция 17,6 тыс. операций из
прежнего SaaS. 157 тестов на PGlite, 16 e2e-сценариев.
`TypeScript · Next.js 16 · PostgreSQL · Drizzle · Better Auth · Playwright`

**[marketplace-pnl-agent](https://github.com/garbidi/marketplace-pnl-agent)** —
агент ежедневного P&L для продавца на маркетплейсах: Ozon, Wildberries РФ и КЗ,
Яндекс Маркет, Магнит, Директ, RetailCRM. Прибыль по дням, товарная
аналитика «SKU × день», планировщик поставок, сторожа данных. В продакшене
с июня 2026, 418 коммитов.
`Python · FastAPI · APScheduler · Google Sheets API · SQLite · 1С`

**[meeting-recorder](https://github.com/garbidi/meeting-recorder)** — бот,
который сам заходит в Zoom / Meet / Телемост, пишет встречу и отдаёт
расшифровку с именами говорящих и выжимку.
`Python · Playwright · GigaAM · faster-whisper · sherpa-onnx · Claude`

**[floorplan-3d](https://github.com/garbidi/floorplan-3d)** — конвейер
фотореалистичных 3D-видов квартир по планировкам: Gemini через CDP, свой
рендер на three.js, Blender + AI-проход, автоматическая проверка по плану
(wall IoU) и AI-приёмщик.
`Python · OpenCV · three.js · Blender · Gemini 3 Pro Image`

**[community-kb](https://github.com/garbidi/community-kb)** — база знаний из
Telegram-чатов: 28 тыс. сообщений, 21,7 часа голосовых в тексте,
поведенческие профили участников; однокнопочный сборщик под Windows и macOS.
`Python · Telethon · faster-whisper · SQLite · PyInstaller`

**[homework-reviewer](https://github.com/garbidi/homework-reviewer)** —
AI-проверка домашних работ на GetCourse: забирает работы с вложениями и
ссылками, Claude пишет ответ, куратор правит и отправляет.
`Python · FastAPI · Playwright · Claude`

**[github-radar](https://github.com/garbidi/github-radar)** — сканер GitHub,
который ищет и ранжирует AI-инструменты, агентные фреймворки и
RAG-инфраструктуру. Фильтрует шум, оценивает находки по сигналам полезности и
раз в неделю публикует дайджест через GitHub Actions. 37 тестов, ADR, документация.
`Python · GitHub API · pytest · ruff · GitHub Actions`

**[lombard-erp](https://github.com/garbidi/lombard-erp)** — ERP для сети
ломбардов на 20 филиалов, заменяет legacy-систему на Delphi/Firebird.
Клиент-серверная архитектура: ASP.NET Core 8 Web API и WPF-клиент с общими
доменными сущностями и DTO-контрактами. JWT с refresh-токенами, аудит изменений
через `SaveChangesInterceptor`, миграции EF Core.
`C# · .NET 8 · ASP.NET Core · WPF · PostgreSQL · EF Core`

**[ISTSys](https://github.com/garbidi/ISTSys)** — десктоп-приложение для
методистов: разбирает Word-документы с компетенциями, валидирует их и собирает
сводные отчёты в Word и Excel. Часы ручной работы → несколько кликов.
`Python · PyQt5 · python-docx · openpyxl`

**[Progmatic-Warning-System](https://github.com/garbidi/Progmatic-Warning-System)** —
Telegram-бот образовательного центра: уведомления о занятиях и заменах из Google
Sheets, подтверждение с эскалацией, watchdog для устойчивости. Работал в
продакшене.
`Python · aiogram 3 · asyncio · gspread`

**[SchoolHelperBot](https://github.com/garbidi/SchoolHelperBot)** — школьный
бот-помощник. Небольшой по объёму, но с аккуратным разделением на роутеры,
сервисы и утилиты.
`Python · aiogram 3 · FSM`

### Стек

**Python** — `FastAPI` `aiogram` `Telethon` `Playwright` `Flask` `PyQt5` `asyncio` `pytest` `ruff`

**AI** — `Claude API (tool use)` `Claude Code` `Gemini` `faster-whisper` `GigaAM` `prompt engineering` `LLM-агенты`

**TypeScript** — `Next.js` `React` `Drizzle ORM` `Vitest` `three.js`

**C# / .NET** — `ASP.NET Core 8` `WPF` `Entity Framework Core` `JWT`

**Данные и интеграции** — `PostgreSQL` `SQLite` `MongoDB` `Google Sheets API` `REST API` `банковские API`

**Инфраструктура** — `Docker Compose` `Caddy` `Linux VPS` `GitHub Actions` `Git`

### Связаться

[![telegram](https://img.shields.io/badge/Telegram-%40Mr__svavarsson-2CA5E0?logo=telegram&logoColor=white)](https://t.me/Mr_svavarsson)
[![email](https://img.shields.io/badge/email-akevropy%40gmail.com-informational?logo=gmail&logoColor=white)](mailto:akevropy@gmail.com)
