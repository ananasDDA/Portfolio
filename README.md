# Portfolio

Одностраничный сайт-портфолио. Дорохов Даниил.

Живой источник дизайна - проект в Claude Design:
`https://claude.ai/design/p/6b0a0704-22e4-4544-b13d-ee45d1d40d4a`, файл `Portfolio.html`.
Здесь он лежит как `index.html`, чтобы работал GitHub Pages.

## Что внутри

Один self-contained файл: разметка, стили и скрипт в `index.html`.
Внешних зависимостей нет, кроме шрифтов с Google Fonts
(Newsreader, Silkscreen, VT323).

Структура страницы: hero → развилка треков (AQA / PM / ML) → About →
Experience → Toolkit → Education → Side projects → Contact.
Переключатель языка RU/EN, тёмная тема по умолчанию.

## Локальный запуск

    python3 -m http.server 8000

Открыть http://localhost:8000. Можно и просто открыть `index.html` в браузере,
но через сервер ближе к продакшену.

## Синхронизация с Claude Design

Правки в Claude Design тянутся сюда через design MCP: файл `Portfolio.html`
проекта выгружается в `index.html`. Обратно - тем же путём, но под именем
`Portfolio.html`.
