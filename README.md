# Андрей Батин

.NET backend-разработчик. Екатеринбург, открыт к удалёнке и гибриду.

Пишу backend на .NET: от микросервисов в банковском low-code до L4-прокси на Go.

Год коммерческой разработки в Artsofte: микросервисы на ASP.NET Core для
low-code-конструктора банковских приложений — PostgreSQL, Redis, RabbitMQ,
Kubernetes, Grafana. После — командный Syncly API на .NET 9 и дипломный
L4-прокси WasmGate на Go.

## Стек

- **Языки:** C#, SQL, Go, Python
- **Backend:** ASP.NET Core, REST API, Dapper, EF Core, FluentMigrator, SignalR
- **Данные:** PostgreSQL, Redis, RabbitMQ
- **Инфраструктура:** Docker, Kubernetes, Grafana (Loki/Tempo), Prometheus, OpenTelemetry, CI/CD
- **Тесты:** xUnit, Postman, Swagger
- **Подходы:** Clean Architecture, DDD, SOLID

## Что посмотреть в первую очередь

### [WasmGate](https://github.com/Fridmak/WasmGate) — L4/TCP-прокси на Go

Дипломный проект. Балансировка `round_robin` / `least_conn`, graceful shutdown,
hot reload конфигурации, zero-copy через `splice(2)` на Linux, метрики Prometheus.
На бенчмарках — 557–977 МБ/с и 0 аллокаций на горячем пути.

### [FridmakWeb](https://github.com/Fridmak/FridmakWeb) — ASP.NET Core MVC

Чат с ботами, друзья, профили, cookie-аутентификация, EF Core + SQL Server,
собственные middleware для rate limiting и IP-фильтра.

### [Microservices](https://github.com/Fridmak/Microservices) — микросервисы на .NET

API Gateway на YARP, AuthService, TaskService, NotificationService.
JWT, PostgreSQL, EF Core, SignalR-уведомления, кэш ответов в памяти.

### [PyExeParser](https://github.com/Fridmak/PyExeParser) — разбор PE/MZ на Python

Заголовки, секции, таблица импортов, анализ машинного кода и дизассемблирование
через Capstone. Тесты на реальных `calc.exe` и `notepad.exe`.

## Open Source

- **[yandex/odyssey #1400](https://github.com/yandex/odyssey/pull/1400)** — merged:
  Go-style duration token в парсере конфига (C) и unit-тесты. `+521 / −12`, 13 файлов.

## Контакты

- Telegram: [@MrFridmak](https://t.me/MrFridmak)
- Email: androlimp22@gmail.com
- GitHub: [github.com/Fridmak](https://github.com/Fridmak)
