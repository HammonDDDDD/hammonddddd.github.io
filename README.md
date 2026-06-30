# Denis Pyshkin — personal portfolio site

Static GitHub Pages portfolio built with plain HTML, CSS and JavaScript.

## How to publish

1. Create a public repository named `hammonddddd.github.io`.
2. Copy all files from this `site/` folder into the root of that repository.
3. Commit and push to `main`.
4. In GitHub, open **Settings → Pages** and make sure the source is set to the `main` branch and `/root` folder.
5. The site should become available at `https://hammonddddd.github.io`.

## How to add a project

Open `data/projects.js`, copy one project object in `window.PORTFOLIO_PROJECTS`, and edit:

- `title`
- `url`
- `period`
- `status.ru` / `status.en`
- `role.ru` / `role.en`
- `summary.ru` / `summary.en`
- `impact.ru` / `impact.en`
- `tags`

No build step is needed.
