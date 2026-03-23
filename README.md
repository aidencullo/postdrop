# post

A minimal text posting app. Posts are stored in localStorage — no server, no accounts.

**Live:** https://aidencullo.github.io/post/

## Routes

- `/post/` — list all posts
- `/post/create` — create a new post
- `/post/{id}` — view/edit a post

## How it works

Single `index.html` with a `contenteditable` div. Posts auto-save to localStorage on typing. Each post gets a random 8-char ID. GitHub Pages serves the static files; the 404.html handles client-side routing for post URLs.

## Deploy

Push to `main` — GitHub Pages deploys automatically from the root of the `main` branch.
