# my-blog

A deliberately simple static blog: plain HTML, one CSS file, zero dependencies.

## Local preview

```sh
python3 -m http.server 8000
# open http://127.0.0.1:8000/
```

## Adding a post

1. Copy a file in `posts/` and edit the title and text.
2. Add a link to it in `index.html`.

## Deployment

Pushes to `main` deploy automatically to GitHub Pages via
`.github/workflows/deploy.yml`.
