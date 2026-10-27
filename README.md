# my-claude-skills

Скилы для Claude Code. Лежат в `.claude/skills/` и подключаются автоматически в любой сессии с этим репозиторием.

| Скил | Что делает | Источник |
|------|------------|----------|
| `/ponytail` | Режим «ленивого сеньора»: самое маленькое изменение, которое полностью решает задачу | [dietrichgebert/ponytail](https://github.com/dietrichgebert/ponytail) |
| `/ponytail-review` | Ревью изменений: баги, безопасность, нагрузка, тесты, лишний код | там же |
| `/ponytail-audit` | То же самое для всего репозитория | там же |
| `/ponytail-debt` | Список отложенных упрощений (`shortcut:` комментарии) | там же |
| `/ponytail-gain` | Результаты бенчмарка ponytail | там же |
| `/ponytail-help` | Справка по ponytail | там же |
| `/graphify` | Граф знаний по коду и документам, запросы к нему | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) |

graphify при первом запуске ставит Python-пакет `graphifyy` из PyPI.

Чтобы установить скилы локально, скопируйте папки из `.claude/skills/` в `~/.claude/skills/`.
