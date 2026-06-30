# Денис Пышкин — personal portfolio site

Статический сайт-портфолио для GitHub Pages, собранный на HTML, CSS и JavaScript без сборщика.

## Что внутри

- `index.html` — структура страницы.
- `styles.css` — визуальный стиль.
- `script.js` — переключение RU/EN и рендеринг карточек.
- `data/projects.js` — список проектов. Чтобы добавить новый проект, скопируйте один объект и измените поля.
- `.github/workflows/pages.yml` — деплой на GitHub Pages через GitHub Actions.
- `.nojekyll` — чтобы GitHub Pages не запускал Jekyll.

## Как обновить сайт

Скопируйте файлы из этой папки в корень репозитория `hammonddddd.github.io`, сделайте commit и push в ветку `main`.

В настройках репозитория должно быть:

`Settings → Pages → Build and deployment → Source → GitHub Actions`
