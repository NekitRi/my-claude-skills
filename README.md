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
| `/humanizer` | Переписывает текст так, чтобы он не звучал как написанный ИИ, без потери смысла | [blader/humanizer](https://github.com/blader/humanizer) |
| `/headroom` | Подсказывает, как сжимать контекст для LLM в своих приложениях (пакет `headroom-ai`) | [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) |
| `/founder-board` … `/founder-plan` | 11 скилов для проверки бизнес-идеи до запуска: совет директоров, конкуренты, панель из 100 симулированных покупателей, цена, оффер, финансы (CFO), маркетинг, бренд, операции, запуск, бизнес-план. Начинать с `/founder-board` | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |

graphify при первом запуске ставит Python-пакет `graphifyy` из PyPI.

Чтобы установить скилы локально, скопируйте папки из `.claude/skills/` в `~/.claude/skills/`.
