Вики-документация Orion
Документация для плагина Orion — платное дополнение для FastAsyncWorldEdit (Minecraft).

Ссылка на вики
https://almarelplugins.github.io/orion-docs/

Технический стек
Генератор сайта : MkDocs Material
Хостинг : GitHub Pages (бесплатный, источник — GitHub Actions)
Автосборка : .github/workflows/ci.yml— запускается при нажатии на мастера
Репозиторий :https://github.com/AlmarelPlugins/orion-docs
Организация : AlmarelPlugins
Как обновить документацию
Открой проект orionwikiв IntelliJ IDEA
Отредактируйте файлы в почтеdocs/
Ctrl+K → выбор файлов → Зафиксировать и отправить
Подожди 1-2 минуты → сайт обновится автоматически
Если сборка упала: github.com/AlmarelPlugins/new-catalog/actions→ посмотреть журнал ошибок

Структура проекта
new-catalog/ ├── mkdocs.yml — отображение MkDocs (меню, тема, навигация) ├── README.md — этот файл (техническая справка) ├── .github/workflows/ │ └── ci.yml — автоматическая сборка и деплой └── docs/ — все страницы документации ├── index.md — Сообщество (главная) ├── Brushes.md — Кисти ├── Masks.md — Маски ├── Patterns.md — Паттерны ├── Commands.md — Команды └── Permissions.md — Права доступа

текст


## Как добавить новую страницу

1. Создай новый `.md` файл в папке `docs/`
2. Добавь его в `mkdocs.yml` в раздел `nav:` — без этого страница не появится в меню
3. Commit and Push

## Как добавить изображение

1. Создай папку `docs/images/` (если её нет)
2. Положи картинку в `docs/images/`
3. В markdown-файле вставь: `![Описание](images/название.png)`

## Как изменить оформление

Вся настройка внешнего вида — в `mkdocs.yml`, секция `theme:`.

## Примечания

- Язык документации: русский (перевод на английский — позже)
- Сайт доступен из РФ без VPN

## Примеры красивых сайтов

https://squidfunk.github.io/mkdocs-material/

https://www.mkdocs.org/

Примеры https://github.com/squidfunk/mkdocs-material/wiki/List-of-community-adaptations

