## Искандар Гафаров

### Python-разработчик · AI-инструменты и автоматизация

📍 Казань, Россия

Коммерческий опыт. Делаю системы, которые снимают с людей рутину: агенты собирают данные из чужих
API, считают и отдают результат в том виде, в каком его реально используют —
дашборд, таблица, сообщение в мессенджере.

Работаю с AI-инструментами разработки как с частью процесса: архитектурные
решения фиксирую в ADR, ход работы — в журнале сессий, чтобы проект можно было
передать и продолжить без потери контекста.

### Проекты

**[marketplace-pnl-agent](https://github.com/garbidi/marketplace-pnl-agent)** —
агент ежедневного P&L для продавца на маркетплейсах. Собирает данные из 8
внешних источников (Ozon Seller и Performance, Wildberries РФ и КЗ, Яндекс
Директ и Кит, RetailCRM, курсы ЦБ), считает прибыль по дням и месяцам, отдаёт
дашборд на FastAPI и зеркалит результат в Google Sheets. Заменил ручную сборку
отчёта в таблицах.
`Python · FastAPI · APScheduler · Google Sheets API · SQLite · 1С`

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

**Python:** `FastAPI` `aiogram` `Flask` `PyQt5` `asyncio` `pytest` `ruff`
**C# / .NET:** `ASP.NET Core 8` `WPF` `Entity Framework Core` `JWT`
**Данные и интеграции:** `PostgreSQL` `SQLite` `MongoDB` `Google Sheets API` `REST API`
**Инфраструктура:** `Docker` `GitHub Actions` `Git`

### Связаться

[![telegram](https://img.shields.io/badge/Telegram-%40Mr__svavarsson-2CA5E0?logo=telegram&logoColor=white)](https://t.me/Mr_svavarsson)
[![email](https://img.shields.io/badge/email-akevropy%40gmail.com-informational?logo=gmail&logoColor=white)](mailto:akevropy@gmail.com)
