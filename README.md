# HireSeeker для Cursor

Плагин подключает MCP HireSeeker для поиска IT-вакансий из Telegram и карьерных сайтов компаний. Доступны инструменты только для чтения: профессии и фильтры, города и страны, поиск вакансий, подробности одной или нескольких вакансий.

Подключение: `https://hireseeker.ru/mcp`, Streamable HTTP. Регистрация, API-ключи, npm-процессы и Docker для подключения MCP не требуются. Работа самого AI-агента зависит от модели и тарифов клиента.

Плагин содержит `.cursor-plugin/plugin.json`, `mcp.json` и навык `skills/hireseeker/SKILL.md`. Он не содержит исполняемых hooks, не читает локальные файлы и не запрашивает GitHub-доступы.

Поиск поддерживает профессии из каталога сервера, географию, формат работы и зарплатные диапазоны. Свободный текст, грейд и точный порог зарплаты не поддерживаются.

Сайт: https://hireseeker.ru

MCP Registry: https://registry.modelcontextprotocol.io/v0.1/servers/io.github.FRAGnatt%2Fhireseeker/versions/1.0.0

Отдельный npm CLI и инструкции: https://github.com/hireseeker/hireseeker-cli

Лицензия файлов плагина: MIT. Серверная часть работает как hosted endpoint; её исходники не входят в плагин.
