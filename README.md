# layero-config-skill

[![skills.sh](https://img.shields.io/endpoint?url=https://www.skills.sh/api/badge/dealenx/layero-config-skill)](https://www.skills.sh/dealenx/layero-config-skill)

## Установка

Установить глобально:

```bash
npx skills add dealenx/layero-config-skill -g
```

Установить в проект:

```bash
npx skills add dealenx/layero-config-skill
```

## Что делает скилл

Составляет `layero.json` — конфигурационный файл деплоя на [layero.ru](https://layero.ru): определяет фреймворк, команды установки и сборки, папку результата сборки и версию Node.js. Скилл помогает агентам (Claude, Cursor) писать корректный конфиг одним PR.
