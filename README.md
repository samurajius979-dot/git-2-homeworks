# Домашнее задание к лекции «Командная работа в Git & GitHub»

## Ссылка для проверки

https://github.com/samurajius979-dot/git-2-homeworks

Это общий репозиторий со ссылками на все выполненные задачи домашней работы.

Проверено 18.05.2026: все три задачи выполнены, репозитории доступны на GitHub, рабочие ветки `main` синхронизированы с удалёнными репозиториями.

## Выполненные задачи

| Задача | Репозиторий | Что проверено |
| --- | --- | --- |
| №1. Импорт существующего проекта | https://github.com/samurajius979-dot/git-2-homeworks-import | Проект импортирован в Git, добавлен `.gitignore`, мусорные файлы не попали в репозиторий |
| №2. Откат изменений | https://github.com/samurajius979-dot/git-2-homeworks-revert | Последний ошибочный коммит отменен через `git revert`, результат отправлен на GitHub |
| №3. Конфликт при push'е | https://github.com/samurajius979-dot/git-2-homeworks-fork | Конфликт после получения изменений из удаленного репозитория разрешен, результат отправлен на GitHub |

## Детали проверки

### Задача №1. Импорт существующего проекта

Репозиторий: https://github.com/samurajius979-dot/git-2-homeworks-import

В `.gitignore` добавлены правила:

```gitignore
tmp/
*_old
*_backup
Thumbs.db
.DS_Store
```

В репозиторий попали только нужные файлы проекта: `index.html`, каталоги `css/`, `img/`, `js/` и `.gitignore`.

### Задача №2. Откат изменений

Репозиторий: https://github.com/samurajius979-dot/git-2-homeworks-revert

В истории есть коммит:

```text
Revert "Add about page"
```

Этот коммит отменяет ошибочный коммит `Add about page`.

### Задача №3. Конфликт при push'е

Репозиторий: https://github.com/samurajius979-dot/git-2-homeworks-fork

В истории есть merge-коммит:

```text
Resolve merge conflict
```

Конфликтные маркеры `<<<<<<<`, `=======`, `>>>>>>>` в файлах отсутствуют.
