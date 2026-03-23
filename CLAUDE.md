# post

Minimal text posting app deployed on GitHub Pages.

## Architecture

- Single `index.html` — all HTML, CSS, and JS in one file
- `404.html` — catches `/post/{id}` routes on GitHub Pages (client-side routing)
- Posts stored in browser `localStorage` with `post:{id}` keys
- No backend, no database, no build step

## Routes

- `/post/` — post list (home)
- `/post/create` — creates new post and redirects
- `/post/{id}` — editor view

## Deploy

GitHub Pages from `main` branch root. Repo: `aidencullo/post`.
