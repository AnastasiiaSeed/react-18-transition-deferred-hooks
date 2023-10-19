# Проект React 18 Features Demo

Проект React 18 Features Demo - это простое веб-приложение, созданное для демонстрации новых возможностей и фичей, представленных в React версии 18. Этот проект содержит два основных компонента: `App` и `Comments`, которые позволяют загружать и фильтровать комментарии с использованием новых хуков и функциональности React 18.

## Иерархия файлов

src/
├── App.js
├── Comments.js
├── index.js
├── ...
...
README.md

### `src/`

- `App.js`: Главный компонент приложения, который загружает комментарии и позволяет пользователю выполнять поиск и фильтрацию.

- `Comments.js`: Компонент для отображения комментариев. Он использует новый хук `useDeferredValue` из React 18 для оптимизации производительности при рендеринге большого количества комментариев.

- `index.js`: Точка входа приложения.

## Запуск проекта

1. Запустите команду `npm install` для установки зависимостей.
2. Запустите команду `npm start` для запуска приложения в режиме разработки.

После выполнения этих шагов, проект будет доступен в вашем веб-браузере по адресу `http://localhost:3000/`.