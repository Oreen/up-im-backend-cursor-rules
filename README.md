# Cursor Rules for TypeScript Backend Projects

Репозиторий с централизованными правилами для IDE Cursor для TypeScript проектов на бэкенде.

## Содержимое

- `typescript.mdc` - Правила для TypeScript и Express.js

## Как использовать

### Добавление в проект

```bash
# В корневой директории вашего проекта
mkdir -p .cursor
git submodule add https://github.com/Oreen/up-im-backend-cursor-rules .cursor/rules
```

### Обновление правил

```bash
# Обновление submodule до последней версии
git submodule update --remote .cursor/rules
git add .cursor/rules
git commit -m "Update cursor rules"
```

### Для новых клонов

```bash
# После клонирования основного репозитория
git submodule init
git submodule update
```

## Содержимое правил

Правила включают стандарты кодирования для:
- TypeScript/JavaScript
- Express.js
- Структура проекта
- Соглашения по именованию и стилю кода
- Рекомендуемые библиотеки 