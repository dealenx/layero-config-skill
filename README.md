# layero-config-skill

<!--[![skills.sh](https://img.shields.io/endpoint?url=https://www.skills.sh/api/badge/dealenx/layero-config-skill)](https://www.skills.sh/dealenx/layero-config-skill)-->


## Что делает скилл

Составляет `layero.json` — конфигурационный файл деплоя на [layero.ru](https://layero.ru): определяет фреймворк, команды установки и сборки, папку результата сборки и версию Node.js. Скилл помогает агентам (Claude, Cursor) писать корректный конфиг одним PR.


## Установка

Установить глобально:

```bash
npx skills add dealenx/layero-config-skill -g
```

Установить в проект:

```bash
npx skills add dealenx/layero-config-skill
```

### Через APM

Разово в проект (устанавливает скилл во все обнаруженные agent-харнесы — Claude Code, Copilot, Cursor и др.):

```bash
apm install dealenx/layero-config-skill --target copilot
```

Или добавьте зависимость в `apm.yml` проекта:

```yaml
dependencies:
  apm:
    - dealenx/layero-config-skill
```

и выполните:

```bash
apm install
```

Установить APM: `curl -sSL https://aka.ms/apm-unix | sh` (Linux/macOS), `irm https://aka.ms/apm-windows | iex` (Windows). Подробнее — [документация APM](https://microsoft.github.io/apm/).
